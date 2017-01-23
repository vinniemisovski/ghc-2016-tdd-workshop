CC=g++

triangle: triangle.cpp triangle.t.cpp 
	@rm -f triangle && $(CC) -lpthread -I. -I/usr/local/include  -I./include ./gtest_main.a triangle.t.cpp triangle.cpp -o triangle && ./triangle

clean: 
	-@rm -f triangle 

