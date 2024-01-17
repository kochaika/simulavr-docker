build:
	avr-gcc -g -O2 -mmcu=attiny2313 -o simple.elf simple.c

run:
	simulavr -d attiny2313 -f simple.elf -W 0x20,- -R 0x22,- -T exit
