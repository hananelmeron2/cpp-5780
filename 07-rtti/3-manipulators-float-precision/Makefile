#!make -f
CXX=clang++-5.0
CXXFLAGS=-std=c++17 -Wunused-comparison

ifndef MAIN
  MAIN=./main.cpp
endif

all: 
	$(CXX) $(CXXFLAGS) $(MAIN)
	./a.out
