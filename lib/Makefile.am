## Process this file with automake to produce Makefile.in.
# Copyright (C) 2004 Free Software Foundation, Inc.
#
# This file is free software, distributed under the terms of the GNU
# General Public License.  As a special exception to the GNU General
# Public License, this file may be distributed as part of a program
# that contains a configuration script generated by Automake, under
# the same distribution terms as the rest of that program.
#
# Generated by gnulib-tool.
# Reproduce by: gnulib-tool --import --dir=. --lib=libgnu --source-base=lib --m4-base=m4 --aux-dir=build-aux --macro-prefix=gl dirname fnmatch-gnu free full-read full-write getaddrinfo getline getopt gettext human iconv iconvme memmem minmax progname quote quotearg sig2str stdbool stdint stpcpy strftime strnlen version-etc xalloc xalloc-die xgethostname xstrndup xvasprintf

AUTOMAKE_OPTIONS = 1.5 gnits no-dependencies

noinst_LIBRARIES = libgnu.a

libgnu_a_SOURCES =
libgnu_a_LIBADD = @LIBOBJS@
EXTRA_DIST =
BUILT_SOURCES =
SUFFIXES =
MOSTLYCLEANFILES =
CLEANFILES =
DISTCLEANFILES =
MAINTAINERCLEANFILES =

## begin gnulib module alloca


libgnu_a_LIBADD += @ALLOCA@
## end   gnulib module alloca

## begin gnulib module alloca-opt

BUILT_SOURCES += $(ALLOCA_H)
EXTRA_DIST += alloca_.h

# We need the following in order to create <alloca.h> when the system
# doesn't have one that works with the given compiler.
alloca.h: alloca_.h
	cp $(srcdir)/alloca_.h $@-t
	mv $@-t $@
MOSTLYCLEANFILES += alloca.h alloca.h-t

## end   gnulib module alloca-opt

## begin gnulib module argmatch

libgnu_a_SOURCES += argmatch.h argmatch.c

## end   gnulib module argmatch

## begin gnulib module dirname

libgnu_a_SOURCES += basename.c stripslash.c

## end   gnulib module dirname

## begin gnulib module exit

libgnu_a_SOURCES += exit.h

## end   gnulib module exit

## begin gnulib module fnmatch

BUILT_SOURCES += $(FNMATCH_H)
EXTRA_DIST += fnmatch_.h fnmatch_loop.c

# We need the following in order to create <fnmatch.h> when the system
# doesn't have one that supports the required API.
fnmatch.h: fnmatch_.h
	cp $(srcdir)/fnmatch_.h $@-t
	mv $@-t $@
MOSTLYCLEANFILES += fnmatch.h fnmatch.h-t

## end   gnulib module fnmatch

## begin gnulib module full-read

libgnu_a_SOURCES += full-read.h full-read.c

## end   gnulib module full-read

## begin gnulib module full-write

libgnu_a_SOURCES += full-write.h full-write.c

## end   gnulib module full-write

## begin gnulib module getaddrinfo

libgnu_a_SOURCES += getaddrinfo.h

## end   gnulib module getaddrinfo

## begin gnulib module getopt

BUILT_SOURCES += $(GETOPT_H)
EXTRA_DIST += getopt_.h getopt_int.h

# We need the following in order to create <getopt.h> when the system
# doesn't have one that works with the given compiler.
getopt.h: getopt_.h
	cp $(srcdir)/getopt_.h $@-t
	mv $@-t $@
MOSTLYCLEANFILES += getopt.h getopt.h-t

## end   gnulib module getopt

## begin gnulib module gettext-h

libgnu_a_SOURCES += gettext.h

## end   gnulib module gettext-h

## begin gnulib module iconvme

libgnu_a_SOURCES += iconvme.h iconvme.c
libgnu_a_LIBADD += $(LTLIBICONV)

## end   gnulib module iconvme

## begin gnulib module memmem

libgnu_a_SOURCES += memmem.h

## end   gnulib module memmem

## begin gnulib module minmax

libgnu_a_SOURCES += minmax.h

## end   gnulib module minmax

## begin gnulib module progname

libgnu_a_SOURCES += progname.h progname.c

## end   gnulib module progname

## begin gnulib module size_max

libgnu_a_SOURCES += size_max.h

## end   gnulib module size_max

## begin gnulib module stdbool

BUILT_SOURCES += $(STDBOOL_H)
EXTRA_DIST += stdbool_.h

# We need the following in order to create <stdbool.h> when the system
# doesn't have one that works.
stdbool.h: stdbool_.h
	sed -e 's/@''HAVE__BOOL''@/$(HAVE__BOOL)/g' < $(srcdir)/stdbool_.h > $@-t
	mv $@-t $@
MOSTLYCLEANFILES += stdbool.h stdbool.h-t

## end   gnulib module stdbool

## begin gnulib module stdint

BUILT_SOURCES += $(STDINT_H)
EXTRA_DIST += stdint_.h

# We need the following in order to create <stdint.h> when the system
# doesn't have one that works with the given compiler.
stdint.h: stdint_.h
	sed -e 's/@''HAVE_LONG_64BIT''@/$(HAVE_LONG_64BIT)/g;s/@''HAVE_LONG_LONG_64BIT@/$(HAVE_LONG_LONG_64BIT)/g' < $(srcdir)/stdint_.h > $@-t
	mv $@-t $@
MOSTLYCLEANFILES += stdint.h stdint.h-t

## end   gnulib module stdint

## begin gnulib module stpcpy

libgnu_a_SOURCES += stpcpy.h

## end   gnulib module stpcpy

## begin gnulib module time_r

libgnu_a_SOURCES += time_r.h

## end   gnulib module time_r

## begin gnulib module vasnprintf

libgnu_a_SOURCES += printf-args.h printf-parse.h vasnprintf.h

## end   gnulib module vasnprintf

## begin gnulib module vasprintf

libgnu_a_SOURCES += vasprintf.h

## end   gnulib module vasprintf

## begin gnulib module verify

libgnu_a_SOURCES += verify.h

## end   gnulib module verify

## begin gnulib module version-etc

libgnu_a_SOURCES += version-etc.h version-etc.c

## end   gnulib module version-etc

## begin gnulib module xalloc-die

libgnu_a_SOURCES += xalloc-die.c

## end   gnulib module xalloc-die

## begin gnulib module xgethostname

libgnu_a_SOURCES += xgethostname.h xgethostname.c

## end   gnulib module xgethostname

## begin gnulib module xsize

libgnu_a_SOURCES += xsize.h

## end   gnulib module xsize

## begin gnulib module xstrndup

libgnu_a_SOURCES += xstrndup.h xstrndup.c

## end   gnulib module xstrndup

## begin gnulib module xstrtoumax

libgnu_a_SOURCES += xstrtoumax.c

## end   gnulib module xstrtoumax

## begin gnulib module xvasprintf

libgnu_a_SOURCES += xvasprintf.h xvasprintf.c xasprintf.c

## end   gnulib module xvasprintf


# Makefile.am ends here
