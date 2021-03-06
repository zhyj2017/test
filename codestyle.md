﻿## 代码风格

- 缩进  

  采用4个空格，可使用tab字符（1个tab为4个空格）。
- 变量命名
  
    1. 变量的命名不以下划线或美元符号开始，也不以下划线或美元符号结束。      
    2. 变量的命名使用标准的英文单词或缩写，不使用拼音与英文混合的方式，更不直接使用中文。    
    3. 变量命名尽量使用全称，如果使用缩写会对其进行注释和说明。
- 每行最多字符数

  单行字符数限制不超过120个，超出需要换行。 
- 函数最大行数

一个函数最大的行数不超过80行。  
- 函数、类命名

    1. 函数命名使用lowerCamelCase风格，遵从驼峰形式，尽量以动宾形式。  
    2. 类命名使用使用lowerCamelCase风格，遵从驼峰形式，领域模型的相关命名）DO / BO / DTO / VO等除外。
- 常量

    1. 任何魔法值（即未经定义的常量）不会直接出现在代码中。  
    2. long或者Long初始赋值时，使用大写的L而不是小写的l。  
    3. 常量命名全部大写，单词间用下划线隔开。  
    4. 常量名力求语义表达完整清楚，不嫌名字长。
- 空行规则

    1. 方法体内的执行语句组、变量的定义语句组、不同的业务逻辑之间或者不同的语义之间插入一个空行。  
    2. 相同业务逻辑和语义之间不需要插入空行。
- 注释规则

    1. 类、类属性、类方法的注释使用Javadoc规范，使用/*内容/格式，不得使用//xxx方式。
    2. 方法内部单行注释，在被注释语句上方另起一行，使用//注释。方法内部多行注释使用/ */注释，注意与代码对齐。
- 操作符前后空格

    1. 左括号和后一个字符之间不出现空格；同样，右括号和前一个字符之间也不出现空格。  
    2. if/for/while/switch/do等保留字与左右括号之间都加空格。
    3. 任何运算符左右必须加一个空格。
    4. 方法参数在定义和传入时，多个参数逗号后边必须加空格。
- 其他规则

    1. 换行规则：
		* 第二行相对第一行缩进 4个空格，从第三行开始，不再继续缩进。
		* 运算符与下文一起换行。
		* 方法调用的点符号与下文一起换行。
		* 在多个参数超长，逗号后进行换行。
		* 在括号前不换行。

    2. 大括号的使用约定：
		* 如果是大括号内为空，则简洁地写成{}，不换行。
		* 如果是非空代码块，左大括号前不换行；左大括号后换行；右大括号前换行；右大括号后还有else等代码则不换行，表示终止右大括号后必须换行。