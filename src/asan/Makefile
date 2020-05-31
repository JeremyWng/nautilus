CFLAGS = -fno-omit-frame-pointer -ffreestanding -fno-stack-protector -fno-strict-aliasing -fno-strict-overflow -mno-red-zone -mcmodel=large -O2  -fno-delete-null-pointer-checks -no-pie -fno-pic -fno-PIC -fno-PIE -fno-exceptions -fno-rtti  -D__NAUTILUS__ -Iinclude  -include include/autoconf.h -D__NAUTILUS__ 
CXXFLAGS = -fno-omit-frame-pointer -ffreestanding -fno-stack-protector -fno-strict-aliasing -fno-strict-overflow -mno-red-zone -mcmodel=large -O2  -fno-delete-null-pointer-checks -no-pie -fno-pic -fno-PIC -fno-PIE -fno-exceptions -fno-rtti  -D__NAUTILUS__ -Iinclude  -include include/autoconf.h -D__NAUTILUS__ 

obj-y += asan_utils.o \
	asan_allocator.o \
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
