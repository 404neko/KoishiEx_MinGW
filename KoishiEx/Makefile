

all: shared

shared:
	g++ *.cpp -lpng -L../lpng1530 -lzlib -L../zlib-1.2.11 -I../lpng1530 -I../zlib-1.2.11 -shared -o KoishiEx.dll

clean:
	rm -rf *.o *.a *.dll

