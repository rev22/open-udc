# Makefile for lud
#

DESTDIR =	/usr/local/bin
PREFIX =	/usr

all:
	# Nothing to compile, run directly "make install" (as root)

install:
	install -m 555 src/lud_genudid src/lud $(DESTDIR)$(PREFIX)/bin
	install -m 444 src/lud_set.env src/lud_utils.env src/lud_generator.env $(DESTDIR)$(PREFIX)/share/openudc-lud

uninstall:
	rm -vf $(DESTDIR)/lud_genudid.sh $(DESTDIR)/lud_*.env

