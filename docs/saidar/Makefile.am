# Makefile for libstatgrab/docs/saidar
# http://www.i-scream.org/libstatgrab/
# $Id$

if MANPAGES
if SAIDAR
man_MANS = saidar.1
endif
endif

EXTRA_DIST = $(man_MANS)

.xml.1:
	docbook2man -N --symlinks $<

