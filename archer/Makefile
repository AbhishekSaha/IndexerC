main: recurse.c process.c process.h sl.h sorted-list.c sorted-list.h uthash.h
	clear
	gcc -o index recurse.c process.c process.h sl.h sorted-list.c sorted-list.h uthash.h
	./index Test6.txt TAInput/test6
	./index Test7.txt TAInput/test7
	./index Test8.txt TAInput/test8
	./index Test10.txt TAInput/test10
	./index Test11.txt TAInput/test11
	./index Test12.txt TAInput/test12.txt
	./index Test13.txt TAInput/test13.txt
	./index Test14.txt TAInput/test14
	./index Test16.txt TAInput/test16

	


debug: recurse.c process.c process.h sl.h sorted-list.c sorted-list.h uthash.h
	clear
	gcc -g recurse.c process.c process.h sl.h sorted-list.c sorted-list.h uthash.h
	gdb a.out
	
clean: 
	rm main
	rm aux.txt

