SUBDIRS=sofprobeclient

bin_PROGRAMS = cplay crecord tinycompinfo

cplay_SOURCES = cplay.c wave.c
crecord_SOURCES = crecord.c wave.c
tinycompinfo_SOURCES = tinycompinfo.c

cplay_CFLAGS = -I$(top_srcdir)/include
crecord_CFLAGS = -I$(top_srcdir)/include
tinycompinfo_CFLAGS = -I$(top_srcdir)/include


cplay_LDADD = $(top_builddir)/src/lib/libtinycompress.la
crecord_LDADD = $(top_builddir)/src/lib/libtinycompress.la
tinycompinfo_LDADD = $(top_builddir)/src/lib/libtinycompress.la
