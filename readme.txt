操作步骤：
	
1、打开终端，根据文件夹路径，cd到文件夹目录下（Linux里在文件夹名前加‘/’）。本例为home文件夹，即：cd /home
	
2、输入./compile.sh,对源程序进行编译
	（即运行gcc -run.c -o run.o）
3、输入./run.sh +参数，运行程序。传参时用'$@'进行传参。

(chmod 777 compile.sh或chmod 777 run.sh赋予权限。)