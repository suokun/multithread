multithread
===========

主线程做自己的事情，生成2个子线程，task1为分离，任其自生自灭，而task2还是继续送外卖，需要等待返回


编译时，在terminal中输入：
gcc -o multithread.o -pthread multithread.c
