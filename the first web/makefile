src=$(wildcard *.c)
obj=$(patsubst %.c,%.out,$(src))
ALL:$(obj)
	
%.out:%.c
	gcc  $< -o $@ -pthread -IRead.h