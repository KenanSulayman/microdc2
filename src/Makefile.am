SUBDIRS = common tth

AM_CFLAGS = \
  -Wall \
  $(LIBXML2_CFLAGS)

AM_CPPFLAGS = \
  -I$(top_builddir)/lib \
  -I$(top_srcdir)/lib

bin_PROGRAMS = microdc2

microdc2_SOURCES = \
  command.c \
  connection.c \
  variables.c \
  fs.c \
  xml_flist.c \
  hub.c \
  huffman.c \
  main.c \
  lookup.c \
  filelist-in.c \
  screen.c \
  search.c \
  user.c \
  util.c \
  tth_file.c \
  tth_file.h \
  local_flist.c \
  hash.c \
  charsets.c \
  charsets.h \
  microdc.h

#microdc_tth_SOURCES = \
#  tth_file.c \
#  tth_file.h \
#  microdc_tth.c

microdc2_LDADD = \
  common/libcommon.a \
  tth/libtth.a \
  ../lib/libgnu.a \
  $(READLINE_LIBS) \
  $(LIBINTL) \
  $(LIBICONV) \
  $(LIBXML2_LIBS)


#microdc_tth_LDADD = \
#  tth/libtth.a \
#  ../lib/libgnu.a

# $(LIBICONV) - not yet used

man_MANS = microdc2.1

EXTRA_DIST = \
  $(man_MANS)
