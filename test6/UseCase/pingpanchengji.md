﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “评定成绩”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|评定成绩|
|-------|:-------------|
|功能|老师评定一个学生的实验成绩|
|参与者|老师|
|前置条件|1.老师先登录该平台</br>2.老师选择评定哪门课程的成绩</br>3.查看成绩：评定该课程实验成绩之前，先显示出一个学生该门课程的所有实验成绩和评语信息|
|后置条件| 评定成绩提交之后，系统自动设置成绩更新日期为当前日期，自动计算平均成绩|
|主事件流| 1. 查看已有的成绩 <br/> 2. 输入一个或者多个实验的成绩和评语  <br/> 3. 提交  <br/> 4. 系统存储实验成绩和评语<br/> 5. 系统自动计算平均成绩|
|备选事件流|2a. 成绩必须是0至100之间，可以为空，但不能超界 <br/>&nbsp;&nbsp; 1.提示用户重新输入成绩分数|


## 2. 业务流程（顺序图） [源码](../src/评定成绩.puml)
![sequence1](../评定成绩.png) 

    
## 3. 界面设计
- 界面参照: https://github.com/zwdbox/is_analysis

- API接口调用

    - 接口1：[getNextPrevStudent](../Interface/getNextPrevStudent.md)
        
        用于取得上一个或者下一个学生的学号
        
    - 接口2：[getOneStudentResults](../Interface/getOneStudentResults.md)
        
        用于显示一个学生的所有实验成绩和评语
         
    - 接口3：[setOneStudentResults](../Interface/setOneStudentResults.md)
    
        用于设置一个学生的部分实验成绩和评语
    
## 4. 算法描述
    无
    
## 5. 参照表

- [STUDENTS](../shujukusheji.md/#STUDENTS)
- [GRADES](../shujukusheji.md/#GRADES)
- [TESTS](../shujukusheji.md/#TESTS)
- [COURSES](../shujukusheji.md/#COURSES)


