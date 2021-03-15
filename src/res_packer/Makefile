all: res_packer

res_packer: res_pack.o crc32.o
	$(CXX) --static -o $@ $^

clean:
	rm -f res_packer *.o

