CC  	= g++
CCFLAGS	= -Wall -Wextra -O3 -lgmp -lgmpxx
PROGRAM	= 0055.out
OBJ 	= 		 	\
	main.o   	 	\
	../timer.o


%.o: %.c
	$(CC) -c -o $@ $< $(CCFLAGS)

$(PROGRAM): $(OBJ)
	$(CC) -o $@ $^ $(CCFLAGS)


.PHONY: clean

clean:
	rm -f src/*.swp *.swp *~ src/*~ *.o
