﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “教师选课”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|教师选课|
|-------|:-------------|
|功能|教师选择自己本学期的所授课程|
|参与者|教师|
|前置条件|1.教师需先登录该平台</br>2.教师需先选择学期|
|后置条件|选课完毕后会更新老师的实验课程 |
|主事件流|1.登录系统平台</br>2.选择所处学期</br>3.选择课程</br>4.选择完毕，退出选课页面 |
|备选事件流| |

## 2. 业务流程（顺序图） [源码](../src/教师选课.puml)
![sequence1](../教师选课.png) 

## 3. 界面设计
- 界面参照: https://github.com/zwdbox/is_analysis
- API接口调用
    - 接口1：[getTeachers](../Interface/getTeachers.md) 
    - 接口2：[getTerms](../Interface/getTerms.md)
    - 接口3：[getCourses](../Interface/getCourses)

## 4. 算法描述

无 

## 5. 参照表

- [TEACHERS](../shujukusheji.md/#TEACHERS)
- [COURSES](../shujukusheji.md/#COURSES)
- [TERMS](../shujukusheji.md/#TERMS)

