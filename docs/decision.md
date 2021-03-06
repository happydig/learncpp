# C++ 判断

判断结构要求程序员指定一个或多个要评估或测试的条件，以及条件为真时要执行的语句（必需的）和条件为假时要执行的语句（可选的）。

下面是大多数编程语言中典型的判断结构的一般形式：

![C++ 中的判断语句](images/if.png)

## 判断语句

C++ 编程语言提供了以下类型的判断语句。点击链接查看每个语句的细节。

| 语句 | 描述 |
| ---- | ---- |
| [if 语句](http://www.runoob.com/cplusplus/cpp-if.html) | 一个  **if 语句**  由一个布尔表达式后跟一个或多个语句组成。 |
| [if...else 语句](http://www.runoob.com/cplusplus/cpp-if-else.html) | 一个  **if 语句**  后可跟一个可选的  **else 语句** ，else 语句在布尔表达式为假时执行。 |
| [嵌套 if 语句](http://www.runoob.com/cplusplus/cpp-nested-if.html) | 您可以在一个  **if**  或  **else if**  语句内使用另一个  **if**  或  **else if**  语句。 |
| [switch 语句](http://www.runoob.com/cplusplus/cpp-switch.html) | 一个  **switch**  语句允许测试一个变量等于多个值时的情况。 |
| [嵌套 switch 语句](http://www.runoob.com/cplusplus/cpp-nested-switch.html) | 您可以在一个  **switch**  语句内使用另一个  **switch**  语句。 |

## ? : 运算符

我们已经在前面的章节中讲解了 [ **条件运算符 ? :** ]，可以用来替代  **if...else**  语句。它的一般形式如下：

```C++
Exp1 ? Exp2 : Exp3;
```

其中，Exp1、Exp2 和 Exp3 是表达式。请注意，冒号的使用和位置。

? 表达式的值是由 Exp1 决定的。如果 Exp1 为真，则计算 Exp2 的值，结果即为整个 ? 表达式的值。如果 Exp1 为假，则计算 Exp3 的值，结果即为整个 ? 表达式的值。
