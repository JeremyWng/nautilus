CFLAGS := $(filter-out -fsanitize=address, $(CFLAGS))
CXXFLAGS := $(filter-out -fsanitize=address, $(CXXFLAGS))

# did not add sanitizer_common_nolibc.o
# because it will cause multiple definition
obj-y += sancov_flags.o \
	sanitizer_allocator_checks.o \
	sanitizer_allocator.o \
	sanitizer_allocator_report.o \
	sanitizer_common.o \
	sanitizer_common_libcdep.o \
	sanitizer_coverage_fuchsia.o \
	sanitizer_coverage_libcdep_new.o \
	sanitizer_coverage_win_dll_thunk.o \
	sanitizer_coverage_win_dynamic_runtime_thunk.o \
	sanitizer_coverage_win_sections.o \
	sanitizer_coverage_win_weak_interception.o \
	sanitizer_deadlock_detector1.o \
	sanitizer_deadlock_detector2.o \
	sanitizer_errno.o \
	sanitizer_file.o \
	sanitizer_flag_parser.o \
	sanitizer_flags.o \
	sanitizer_fuchsia.o \
	sanitizer_libc.o \
	sanitizer_libignore.o \
	sanitizer_linux.o \
	sanitizer_linux_libcdep.o \
	sanitizer_linux_s390.o \
	sanitizer_mac.o \
	sanitizer_mac_libcdep.o \
	sanitizer_netbsd.o \
	sanitizer_openbsd.o \
	sanitizer_persistent_allocator.o \
	sanitizer_platform_limits_freebsd.o \
	sanitizer_platform_limits_linux.o \
	sanitizer_platform_limits_netbsd.o \
	sanitizer_platform_limits_openbsd.o \
	sanitizer_platform_limits_posix.o \
	sanitizer_platform_limits_solaris.o \
	sanitizer_posix.o \
	sanitizer_posix_libcdep.o \
	sanitizer_printf.o \
	sanitizer_procmaps_bsd.o \
	sanitizer_procmaps_common.o \
	sanitizer_procmaps_fuchsia.o \
	sanitizer_procmaps_linux.o \
	sanitizer_procmaps_mac.o \
	sanitizer_procmaps_solaris.o \
	sanitizer_rtems.o \
	sanitizer_solaris.o \
	sanitizer_stackdepot.o \
	sanitizer_stacktrace.o \
	sanitizer_stacktrace_libcdep.o \
	sanitizer_stacktrace_printer.o \
	sanitizer_stacktrace_sparc.o \
	sanitizer_stoptheworld_fuchsia.o \
	sanitizer_stoptheworld_linux_libcdep.o \
	sanitizer_stoptheworld_mac.o \
	sanitizer_stoptheworld_netbsd_libcdep.o \
	sanitizer_suppressions.o \
	sanitizer_symbolizer.o \
	sanitizer_symbolizer_libbacktrace.o \
	sanitizer_symbolizer_libcdep.o \
	sanitizer_symbolizer_mac.o \
	sanitizer_symbolizer_markup.o \
	sanitizer_symbolizer_posix_libcdep.o \
	sanitizer_symbolizer_report.o \
	sanitizer_symbolizer_win.o \
	sanitizer_termination.o \
	sanitizer_thread_registry.o \
	sanitizer_tls_get_addr.o \
	sanitizer_type_traits.o \
	sanitizer_unwind_linux_libcdep.o \
	sanitizer_unwind_win.o \
	sanitizer_win.o \
	sanitizer_win_dll_thunk.o \
	sanitizer_win_dynamic_runtime_thunk.o \
	sanitizer_win_weak_interception.o

