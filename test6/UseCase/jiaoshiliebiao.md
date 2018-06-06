﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “教师列表”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|教师列表|
|-------|:-------------|
|功能|以表形式的显示出所有老师的选课信息|
|参与者|学生，老师|
|前置条件|学生，老师需要先登录|
|后置条件| |
|主事件流|学生选课时会显示教师已选课程信息 |
|备选事件流| |

## 2. 业务流程（顺序图） 

无

## 3. 界面设计
- 界面参照: https://github.com/zwdbox/is_analysis
- API接口调用
    - 接口1：[getTeachers](../Interface/getTeachers.md)
    - 接口2：[getCourses](../Interface/getCourses.md)

## 4. 算法描述

无

## 5. 参照表

- [TEACHERS](../shujukusheji.md/#TEACHERS)
- [COURSES](../shujukusheji.md/#COURSES)

