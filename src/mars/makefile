.PHONY: all clean
all: mars-engine
mars-engine:
	g++ -O3 -fpermissive -w src/*.cpp -o $@
eleeye-engine:
	g++ -O3 -w eleeye/base/*.cpp eleeye/eleeye/*.cpp -o $@
clean:
	rm -rf mars-engine
