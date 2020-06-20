# Linux C makeFile使用

## 编译的配置工具
     创建Makefile 文件
     注意，tab = 6空格
## 举例使用(先写main文件，再写依赖文件)
   hello.out:  max.o hello.c
        gcc max.o hello.c -o hello.out
   max.o: max.c
        gcc -c max.c










        






