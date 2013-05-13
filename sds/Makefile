all : demo

demo : sds_demo.c sds.c
	gcc -Wall -Wextra -o $@ $^

test : sds_test.c sds.c
	gcc -Wall -Wextra -o $@ $^

clean :
	-rm -f demo test

