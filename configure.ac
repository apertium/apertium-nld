AC_PREREQ(2.52)

AC_INIT([Apertium Dutch], [0.2.0], [apertium-stuff@lists.sourceforge.net], [apertium-nld], [https://wiki.apertium.org/wiki/Apertium-nld])
AM_INIT_AUTOMAKE

AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.6.0)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.0)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.0)

PKG_CHECK_MODULES(REGTEST, apertium-regtest >= 0.0.1, [],
                  [AC_MSG_WARN([Running tests requires apertium-regtest])])

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-nld.pc])
