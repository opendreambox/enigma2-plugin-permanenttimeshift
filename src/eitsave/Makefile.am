AM_CPPFLAGS = \
	@PYTHON_CPPFLAGS@ \
	-include Python.h

AM_CXXFLAGS = \
	-Wall \
	-fno-exceptions \
	@ENIGMA2_CFLAGS@ \
	@PTHREAD_CFLAGS@

plugindir = $(libdir)/enigma2/python/Plugins/Extensions/PermanentTimeshift

plugin_LTLIBRARIES = eitsave.la

eitsave_la_SOURCES = \
	eitsave.cpp 

eitsave_la_LDFLAGS = \
	-avoid-version \
	-module \
	-shared
