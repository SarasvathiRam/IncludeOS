CPP=g++
CPPOPTS = -std=c++11 -c -Wall -Wextra -O3
OBJS = vmbuild.o
OUT = vmbuild

.cpp.o:
	@ $(CPP) $(CPPOPTS) $< -o $@

all: $(OBJS)
	@ echo ">>> Building vmbuilder"
	@ $(CPP) $(OBJS) -o $(OUT)
	@ echo "  * Done \n"

clean:
	$(RM) $(OBJS) $(OUT) *~


