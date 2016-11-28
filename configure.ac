AC_PREREQ(2.60)

AC_INIT([gtk3hello], [1.0], [stephano.cetola@linux.intel.com])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([1.9.6 -Wall -Werror dist-bzip2])

AC_PROG_CC
# Compiling sources with per-target flags requires AM_PROG_CC_C_O
AM_PROG_CC_C_O
AC_PROG_INSTALL
AC_PROG_LIBTOOL

AM_PATH_GTK_3_0([3.0.0],,AC_MSG_ERROR([Gtk+ 3.0.0 or higher required.]))

AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
        Makefile
        src/Makefile
])
AC_OUTPUT
