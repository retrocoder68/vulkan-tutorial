# Copyright (C) 2023 Skywalker <j.karlsson@retrocoder.se>

CFLAGS=-Wall -Wextra -g -std=c++17 -O2
LDFLAGS=-lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi

VulkanTest: main.cpp
	clang++ $(CFLAGS) -o VulkanTest main.cpp $(LDFLAGS)

.PHONY: test clean

test: VulkanTest
	./VulkanTest

clean:
	rm -f VulkanTest

