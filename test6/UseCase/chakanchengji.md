﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “查看成绩”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|查看成绩|
|-------|:-------------|
|功能|学生查看自己每门课程的每个实验的实验成绩及实验评价|
|参与者|学生|
|前置条件|学生需要先登录|
|后置条件| |
|主事件流|1.学生登录后选择自己需查询的课程</br>2.然后选择查询哪次的实验</br>3.查看所得成绩和实验评价 |
|备选事件流| |

## 2. 业务流程（顺序图） [源码](../src/查看成绩.puml)
![sequence1](../查看成绩.png) 

## 3. 界面设计
- 界面参照: https://github.com/zwdbox/is_analysis
- API接口调用
    - 接口1：[getOneStudentResults](../Interface/getOneStudentResults.md) 

## 4. 算法描述
    无
    
## 5. 参照表
- [STUDENTS](../shujukusheji.md/#STUDENTS)
- [GRADES](../shujukusheji.md/#GRADES)
- [TESTS](../shujukusheji.md/#TESTS)
- [COURSES](../shujukusheji.md/#COURSES)

