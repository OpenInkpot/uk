AC_PREREQ(2.57)
AC_INIT(uk, 0.1, dottedmag@dottedmag.net)
AM_INIT_AUTOMAKE(foreign)

AC_LANG_C
AC_PROG_CC

PKG_CHECK_MODULES(XCB,[xcb])
PKG_CHECK_MODULES(XCB_UTIL,[xcb-event xcb-aux])
PKG_CHECK_MODULES(LIBLOPS, [liblops])

AC_OUTPUT(Makefile src/Makefile)
