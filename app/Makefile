all: x10_send 

CFLAGS	= -Wall -g -O3 -Wno-unused-variable 
LDFLAGS	= -lm -lrt -lpthread 
CCP = g++ 
CC = gcc 


x10_send: x10_send.cpp ../src/librpitx.h ../src/librpitx.a
	
	$(CCP) $(CFLAGS) -o x10_send x10_send.cpp ../src/librpitx.a $(LDFLAGS) 

clean:
	
	rm -f  x10_send
