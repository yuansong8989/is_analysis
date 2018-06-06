﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “学生选课”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|学生选课|
|-------|:-------------|
|功能|学生选择自己本学期的实验课程|
|参与者|学生|
|前置条件|1.学生需先登录该平台</br>2.学生选择的课程必须是在老师已选的课程当中|
|后置条件|选课完毕后会更新学生的实验课程 |
|主事件流|1.登录系统平台</br>2.选择所处学期</br>3.选择老师已选的课程</br>4.选择完毕，退出选课页面 |
|备选事件流| |

## 2. 业务流程（顺序图） [源码](../src/学生选课.puml)
![sequence1](../学生选课.png) 

## 3. 界面设计
- 界面参照: https://github.com/zwdbox/is_analysis
- API接口调用
    - 接口1：[getCourses](../Interface/getCourses.md) 
    - 接口2：[getTerms](../Interface/getTerms.md)

## 4. 算法描述

无 

## 5. 参照表

- [STUDENTS](../shujukusheji.md/#STUDENTS)
- [TEACHERS](../shujukusheji.md/#TEACHERS)
- [COURSES](../shujukusheji.md/#COURSES)
- [TERMS](../shujukusheji.md/#TERMS)




