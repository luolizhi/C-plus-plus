INC_DIR:=./include/
SRC_SIR:=./src/
SRCS:=$(wildcard *.cc)
LIBS:=-lpthread
CXX:= g++
CXXFLAGS:=-Wall -g -std=c++11 $(addprefix -I, $(INC_DIR)) $(LIBS)

EXE:=./bin/main	

$(EXE):$(SRCS)
	$(CXX) -o $@ $(SRCS) $(CXXFLAGS)
clean:
	rm -rf $(EXE)
