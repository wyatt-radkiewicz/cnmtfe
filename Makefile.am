AM_CFLAGS = $(DEPS_CFLAGS)
AM_LIBS = $(DEPS_LIBS)
bin_PROGRAMS = cnmtfe
cnmtfe_SOURCES = \
	src/main.c \
	src/glad/glad.c \
	include/glad/glad.h \
	include/KHR/khrplatform.h
cnmtfe_CFLAGS = $(AM_CFLAGS) -I$(builddir)/include
