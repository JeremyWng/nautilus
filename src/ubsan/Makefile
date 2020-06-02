CFLAGS := $(filter-out -fsanitize=address, $(CFLAGS))
CXXFLAGS := $(filter-out -fsanitize=address, $(CXXFLAGS))

obj-y += ubsan_diag.o \
	ubsan_signals_standalone.o \
	ubsan_diag_standalone.o \
	ubsan_type_hash.o \
	ubsan_flags.o \
	ubsan_type_hash_itanium.o \
	ubsan_handlers.o \
	ubsan_type_hash_win.o \
	ubsan_handlers_cxx.o \
	ubsan_value.o \
	ubsan_init.o \
	ubsan_win_dll_thunk.o \
	ubsan_init_standalone.o \
	ubsan_win_dynamic_runtime_thunk.o \
	ubsan_init_standalone_preinit.o \
	ubsan_win_weak_interception.o \
	ubsan_monitor.o
