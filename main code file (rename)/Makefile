
all: compile link
compile:
	g++ -I srs/include -c main.cpp
link:
	g++ main.o -o main -L srs/lib -l sfml-graphics -l sfml-window -l sfml-system