all: main

main: main.cpp binheap.cpp monsters.cpp world.cpp printing.cpp sprite.cpp monster.cpp pc.cpp dice.cpp
	g++ -Wall -Werror -ggdb main.cpp binheap.cpp monsters.cpp world.cpp printing.cpp sprite.cpp monster.cpp pc.cpp dice.cpp -lm -lncurses -o dungeon_generator

gpp: sprite.cpp monster.cpp pc.cpp
	g++ -c -Wall -Werror -ggdb sprite.cpp monster.cpp pc.cpp

clean:
	rm dungeon_generator *.o

