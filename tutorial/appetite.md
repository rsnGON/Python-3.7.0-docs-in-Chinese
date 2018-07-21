1. 开胃菜
*************************
1. Whetting Your Appetite
*************************

如果你在电脑上工作很多, 结果你发现有一些任务你想让它自动完成.  
举个例子, 你可能希望在一个很大的文本文件上做搜索和替换，或者
用一个复杂的方式重命名和重新整理一大堆图片文件.可能你会写一个
小的定制数据库，或者一个特定的GUI程序，或者一个小游戏.

If you do much work on computers, eventually you find that there’s
some task you’d like to automate.  For example, you may wish to
perform a search-and-replace over a large number of text files, or
rename and rearrange a bunch of photo files in a complicated way.
Perhaps you’d like to write a small custom database, or a specialized
GUI application, or a simple game.


如果你是一个专业的软件开发者，你可能必须用一些C/C++/Java库开发,但是发现通常的
编写/编译/测试/重新编译的步骤是太慢了.可能你正在为这样的库写一个测试套件，但是
发现写测试代码是一个无趣的任务。或者你可能开发出了一个可以使用扩展语言的程序，
然后你不想为你的程序设计和实现一整个新语言.

If you’re a professional software developer, you may have to work with
several C/C++/Java libraries but find the usual write/compile/test/re-
compile cycle is too slow.  Perhaps you’re writing a test suite for
such a library and find writing the testing code a tedious task.  Or
maybe you’ve written a program that could use an extension language,
and you don’t want to design and implement a whole new language for
your application.

Python刚好是这样适合你的语言.

Python is just the language for you.

你可以为一些其中的这些任务写一个Unix shell脚本或者Windows批处理文件，
shell脚本擅长移动文件和改变文本内容，但是不是很适合GUI程序和游戏.你
可以写一个C/C++/Java程序，但是要花很多开发时间才得到甚至就一页程序.
Python使用更简单，在Windows,Mac OS X,和Unix操作系统上都可用，能帮助
你更快的完成工作.

You could write a Unix shell script or Windows batch files for some of
these tasks, but shell scripts are best at moving around files and
changing text data, not well-suited for GUI applications or games. You
could write a C/C++/Java program, but it can take a lot of development
time to get even a first-draft program.  Python is simpler to use,
available on Windows, Mac OS X, and Unix operating systems, and will
help you get the job done more quickly.

虽然Python使用很简单，但是它是一个真正的编程语言，它相对shell脚本和批处理文件，
为大型程序提供了更多的数据结构和支持.另一方面,Python比C语言提供了更多的错误检查,
作为一个*非常高级的语言*,它有内建的高级数据类型,比如可变长数组和词典.因为它的更
一般数据类型,Python相比Awk，甚至Perl适合更大的问题领域.许多事情相比这些语言在
Python中至少一样简单.

Python is simple to use, but it is a real programming language,
offering much more structure and support for large programs than shell
scripts or batch files can offer.  On the other hand, Python also
offers much more error checking than C, and, being a *very-high-level
language*, it has high-level data types built in, such as flexible
arrays and dictionaries.  Because of its more general data types
Python is applicable to a much larger problem domain than Awk or even
Perl, yet many things are at least as easy in Python as in those
languages.

Python允许你把你的程序分成一些模块,这些模块可以在其它Python程序中复用.
Python有一个很多标准模块的集合,你可以使用它们作为你的程序的基础,或者作为开始
学习用Python编程的例子.其中一些这些模块提供了像文件I/O,系统调用,套接字,
图形用户接口工具包像Tk.

Python allows you to split your program into modules that can be
reused in other Python programs.  It comes with a large collection of
standard modules that you can use as the basis of your programs — or
as examples to start learning to program in Python.  Some of these
modules provide things like file I/O, system calls, sockets, and even
interfaces to graphical user interface toolkits like Tk.

Python是一个解释型的语言,它可以在程序开发期间给你节省出相当多的时间,因为编译
和链接都不需要.python解释器可以以交互方式使用,这样可以更容易体验Python语言的
特性,更容易写一次性临时的程序,更容易在自底向上程序开发期间测试函数.它也是一个
方面的桌面计算器.

Python is an interpreted language, which can save you considerable
time during program development because no compilation and linking is
necessary.  The interpreter can be used interactively, which makes it
easy to experiment with features of the language, to write throw-away
programs, or to test functions during bottom-up program development.
It is also a handy desk calculator.

Python使程序可以被简洁地和具有可读性地编写.
用Python写的程序比等价的C,C++,或者Java程序更短,因为几个原因:

Python enables programs to be written compactly and readably.
Programs written in Python are typically much shorter than equivalent
C,  C++, or Java programs, for several reasons:

* 高级数据类型允许你用一条语句表达复杂的操作.
* the high-level data types allow you to express complex operations
  in a single statement;

* 语句分块是通过缩进完成的,而不是左右括号.
* statement grouping is done by indentation instead of beginning and
  ending brackets;

* 变量和参数声明是不需要的.
* no variable or argument declarations are necessary.

Python是*可扩展的*:如果你知道怎么用C语言编程,那很容易给解释器添加一个新的内建函数
或者模块,

Python is *extensible*: if you know how to program in C it is easy to
add a new built-in function or module to the interpreter, either to
perform critical operations at maximum speed, or to link Python
programs to libraries that may only be available in binary form (such
as a vendor-specific graphics library). Once you are really hooked,
you can link the Python interpreter into an application written in C
and use it as an extension or command language for that application.

顺便,Python语言以BBC show“Monty Python’sFlying Circus”命名的.

By the way, the language is named after the BBC show “Monty Python’s
Flying Circus” and has nothing to do with reptiles.  Making references
to Monty Python skits in documentation is not only allowed, it is
encouraged!

Now that you are all excited about Python, you’ll want to examine it
in some more detail.  Since the best way to learn a language is to use
it, the tutorial invites you to play with the Python interpreter as
you read.

In the next chapter, the mechanics of using the interpreter are
explained.  This is rather mundane information, but essential for
trying out the examples shown later.

剩下的教程通过例子介绍了各种Python语言和系统的特性,通过函数和模块,开始一些
简单的表达式,语句,和数据类型,最后接触到高级的概念像异常和自定义类.

The rest of the tutorial introduces various features of the Python
language and system through examples, beginning with simple
expressions, statements and data types, through functions and modules,
and finally touching upon advanced concepts like exceptions and user-
defined classes.
