objects = addition.o subtraction.o multiplication.o division.o main.o

headers = operations.h

calculator: $(objects)
	cc -o calculator $(objects)

%.o: %.c $(headers)
	cc -c $< -o $@

clean:
	rm -f calculator $(objects)

.PHONY: clean