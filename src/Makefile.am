# This file is input to automake, that expands this high-level make description
# to a Makefile containing the usual goals, and being capable of handling
# portability issues.

# the executable created by make
bin_PROGRAMS = metamath

# the following header files are used during build, but need not be installed.
# There is nothing exported to external software.
noinst_HEADERS = \
	mmcmdl.h \
	mmcmds.h \
	mmdata.h \
	mmhlpa.h \
	mmhlpb.h \
	mminou.h \
	mmpars.h \
	mmpfas.h \
	mmunif.h \
	mmveri.h \
	mmvstr.h \
	mmword.h \
	mmwtex.h

# files used to build the executable.
metamath_SOURCES = \
	metamath.c \
	mmcmdl.c \
	mmcmds.c \
	mmdata.c \
	mmhlpa.c \
	mmhlpb.c \
	mminou.c \
	mmpars.c \
	mmpfas.c \
	mmunif.c \
	mmveri.c \
	mmvstr.c \
	mmword.c \
	mmwtex.c \
	$(noinst_HEADERS)

# man pages for the executable´
dist_man_MANS = metamath.1
