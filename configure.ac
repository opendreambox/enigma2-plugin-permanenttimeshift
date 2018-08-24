AC_INIT([enigma2-plugin-extensions-permanenttimeshift],[4.3.0],[https://github.com/opendreambox/enigma2-plugin-permanenttimeshift/issues])
AM_INIT_AUTOMAKE([foreign])

AM_SILENT_RULES([yes])

AC_USE_SYSTEM_EXTENSIONS
AC_SYS_LARGEFILE

AC_PROG_CXX
LT_INIT
AC_CONFIG_MACRO_DIR([m4])

AM_PATH_PYTHON
AX_PYTHON_DEVEL
AX_PTHREAD

PKG_CHECK_MODULES(ENIGMA2, enigma2)

AC_CONFIG_FILES([
Makefile
images/Makefile
meta/Makefile
src/Makefile
src/createapscfiles/Makefile
src/eitsave/Makefile
Components/Makefile
Components/Converter/Makefile
Components/Sources/Makefile
skin/Makefile
])
AC_OUTPUT
