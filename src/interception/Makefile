CFLAGS := $(filter-out -fsanitize=address, $(CFLAGS))
CXXFLAGS := $(filter-out -fsanitize=address, $(CXXFLAGS))

obj-y += interception_linux.o \
	interception_type_test.o \
	interception_mac.o \
	interception_win.o
