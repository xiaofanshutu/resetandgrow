## Java9新特性

Java9经过4次推迟，历经曲折的Java9最终在2017年9月21日发布，提供了超过150项新功能特性。

- JEP 261: Module System
  - JDK 9 开始引入的一种全新的模块化编程方式。JPMS 的目的是为了更好地支持大型应用程序的开发和维护，同时也可以使 Java 程序在更为动态、可移植和安全的环境下运行。
- JEP 222: jshell: The Java Shell (Read-Eval-Print Loop)
  - 一种交互式的 Java Shell，可以在命令行上快速地进行 Java 代码的编写、验证和执行，从而提高开发者的生产力。
- JEP 213: Milling Project Coin（细化工程改进，该计划旨在引入小型语言特性来提高代码的简洁性和可读性）
  - 在Java 9中，@SafeVarargs注解可以用于一个私有实例方法上。在Java 7和Java 8中，@SafeVarargs注解只能用于静态方法、final实例方法和构造函数。
  - 在Java 9中，可以将效果等同于final变量作为try-with-resources语句块中的资源来使用。在Java 7/8中，try-with-resources语句块中的资源必须是显式的final或事实上的final（即变量在初始化后未被修改），否则编译器会报错。这个限制限制了Java程序员使用try-with-resources语句块的能力，特别是在涉及lambda表达式、匿名类或其他读取外部变量的代码段时。
  - Java 9允许在匿名类实例化时使用钻石操作符(<>)来简化代码，但参数类型必须是具体的、可推导的类型。
  - 从Java9开始，不能使用一个单一的“_”作为标识符了。
  - 从Java9开始，接口中支持定义私有方法。
