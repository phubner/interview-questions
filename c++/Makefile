TARGET=$(CURDIR)/target

dummy:=$(shell mkdir -p $(TARGET))

.DEFAULT: all

.PHONY: all clean

all: src/test.cpp
	$(CXX) $(CXXFLAGS) -o $(TARGET)/lru_cpp src/test.cpp

clean:
	-rm -rf target
