CFLAGS := $(filter-out -fsanitize=address, $(CFLAGS))
CXXFLAGS := $(filter-out -fsanitize=address, $(CXXFLAGS))


obj-y += lsan_allocator.o \
	lsan.o \
	lsan_malloc_mac.o \
	lsan_common.o \
	lsan_fuchsia.o \
	lsan_posix.o \
	lsan_common_fuchsia.o \
	lsan_interceptors.o \
	lsan_preinit.o \
	lsan_common_linux.o \
	lsan_linux.o \
	lsan_thread.o \
	lsan_common_mac.o \
	lsan_mac.o

