# python_wrapper_example
a python wrapper example

编译：
gcc -fPIC wrapper.c -o example.so -shared -I/usr/include/python2.6 -I/usr/lib/python2.6/config

使用：
在example.o所在的目录进入python环境，然后运行以下命令
import example
example.fact(9)
