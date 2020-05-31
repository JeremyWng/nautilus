CFLAGS := $(filter-out -fsanitize=address, $(CFLAGS))
CXXFLAGS := $(filter-out -fsanitize=address, $(CXXFLAGS))


obj-y += asan_allocator.o \
	asan_activation.o \
	asan_debugging.o \
	asan_descriptions.o \
	asan_errors.o \
	asan_fake_stack.o \
	asan_flags.o \
	asan_fuchsia.o \
	asan_globals.o \
	asan_globals_win.o \
	asan_interceptors.o \
	asan_interceptors_memintrinsics.o \
	asan_linux.o \
	asan_mac.o \
	asan_malloc_linux.o \
	asan_malloc_mac.o \
	asan_malloc_win.o \
	asan_memory_profile.o \
	asan_poisoning.o \
	asan_posix.o \
	asan_premap_shadow.o \
	asan_report.o \
	asan_rtems.o \
	asan_rtl.o \
	asan_shadow_setup.o \
	asan_stack.o \
	asan_stats.o \
	asan_suppressions.o \
	asan_thread.o \
	asan_win.o
