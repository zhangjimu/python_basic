#### Python

##### 一.基础语法

###### 1.注释

- 注释：对代码的解释说明
- 目的：增强代码的可读性；更容易看懂代码
- 特点：不会被解释器执行

###### 2.注释的分类

- 单行注释# 和 多行注释"""xx""" 或'''xx'''  快捷键：ctrl +/
- 注意事项
  - 逻辑复杂的代码，应先编写注释再编码；
  - 不使用中文翻译python代码含义

###### 3.变量

- 概念 变量在计算机语言中能储存计算结果或表示某个数据值
- 定义：变量名=数据值  例：name="张三"
- 说明
  - 变量名自定义，要满足'标识符'命名规则
  - 数据值为要存储的数据，可为不同的数据类型
  - 单引号用于赋值 ，不具备比较功能

###### 4.标识符

- 概念：标识符是用户编程时使用的名字，用于给变量、函数、类等命名
- 标识符规则
  - 由数字、字母、下划线组成
  - 不能由数字开头
  - 不能使用Python内置关键字
  - 严格区分大小写、不建议使用中文

**Python中的关键字**

![image-20220819143648131](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220819143648131.png)

- 标识符-命名习惯
  - 驼峰命名
    - 大驼峰：每个单词首字母大写, 例如: `MyName'
    - 小驼峰：第二个单词开始首字母大写, 例如: `myName`
  - 下划线命名
    - 每个单词之间使用下划线连接, 例如: `my_name`

###### 5.数据类型

**分类**

![image-20220819144155205](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220819144155205.png)

**类型转换**

![image-20220819144329081](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220819144329081.png)

##### 程序的输入与输出

###### 程序的输出

- 语法：print(数据/变量) ，例：name="小米"  print(name)

###### 格式化输出

- 将程序的运行结果按一定的格式输出

![image-20220819150029979](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220819150029979.png)

###### 格式化输出-format方法实现

- 调用字符串的format方法可以实现字符串的格式化

![image-20220823104515198](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220823104515198.png)

###### ==格式化输出-f格式化输出==

- f-格式化字符串是Python3.6中新增的格式化方法，更实用

![image-20220823111543406](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220823111543406.png)

###### 转义字符

- **常见的转义字符**
  - \n 换行
  - \t Tab键(制表符)
  - 移除换行：print('内容', end='')

![image-20220823111915393](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220823111915393.png)

###### 程序的输入

- 在Python中接受用户输入的数据的过程为程序的输入

语法：变量名 = input('提示信息：')

==注意事项==

![image-20220823112807334](C:\Users\jimu\AppData\Roaming\Typora\typora-user-images\image-20220823112807334.png)

##### 运算符

- 运算符：在各种运算中起到特定作用的符号
- 运算符
