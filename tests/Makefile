all: MultikeyMap_test MultikeyMap_test2

CC=g++

MultikeyMap_test: MultikeyMap_test.cpp ../MultikeyMap.h
	$(CC) MultikeyMap_test.cpp -std=c++0x -o MultikeyMap_test

MultikeyMap_test2: MultikeyMap_test2.cpp ../MultikeyMap.h
	$(CC) MultikeyMap_test2.cpp -std=c++0x -o MultikeyMap_test2

clean:	
	rm MultikeyMap_test

