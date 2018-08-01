
AC_PREREQ([2.69])
AC_INIT( nmos_node, 0.1, sergey.serebryanskiy@macnica.com)
AC_CONFIG_SRCDIR([src/main.cpp])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])
AM_INIT_AUTOMAKE

# Checks for programs.
AC_PROG_CXXCPP
AC_LANG([C++])


# Checks for libraries.
LT_INIT
AC_ENABLE_SHARED
AC_DISABLE_STATIC
AC_PROG_LIBTOOL(libtool)


# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([stdio.h])


# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T
AC_HEADER_STDBOOL
AC_C_INLINE


# Checks for library functions.

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT
