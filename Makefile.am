CLEANFILES           = .deps main.o sshpass stamp-h1
DISTCLEANFILES       = Makefile INSTALL Makefile.in aclocal.m4 \
                       autom4te.cache config.h config.h.in config.log \
                       config.status configure
EXTRA_DIST           = $(man_MANS)
MAINTAINERCLEANFILES = $(DISTCLEANFILES)
MOSTLYCLEANFILES     = $(CLEANFILES)
PACKAGE              = @PACKAGE_NAME@
VERSION              = @PACKAGE_VERSION@
bin_PROGRAMS         = sshpass
man_MANS             = sshpass.1
sshpass_SOURCES      = main.c
