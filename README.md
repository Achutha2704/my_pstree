# my_pstree
This is my first kernel program. It is a simple program that creates a process tree iteratively and prints the process tree in a simiilar way to the pstree command does.
Steps to run
1) cd directory containing my_kernel_module.c and Makefile
2) make
3) sudo insmod my_kernel_module.ko   #insert module
4) sudo dmesg                        #dispaly logs
5) sudo rmmod my_kernel_module       #remove module
