#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([sl], [8.1.0], [kokkiemouse+bugs@gmail.com])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([src/sl.h])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
# FIXME: Replace `main' with a function in `-lncursesw':
AC_CHECK_LIB([ncursesw], [main])

# Checks for header files.
AC_CHECK_HEADERS([unistd.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT
