#OBJS defines files to compile
OBJS = ./src/main.cpp 
CC = g++
COMPILER_FLAGS = -g -Wall -Wextra -Wpedantic -std=c++17
LINKER_FLAGS = -lpqxx -lpq 
OBJ_NAME = ../dist/serve 

all : $(OBJS) 
		$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)
