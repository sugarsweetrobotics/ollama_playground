CXX = clang++
CXXFLAGS = -std=c++17 -Wall -Wextra

TARGET = hello

all: $(TARGET)

$(TARGET): hello_world.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

clean:
	rm -f $(TARGET)

.PHONY: all clean
