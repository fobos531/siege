##
## Makefile.am
##
## Copyright (C) 2000-2007 by 
## Jeffrey Fulmer - <jeff@joedog.org>, et al.
## This file is distributed as part of Siege
##
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2 of the License, or
## (at your option) any later version.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program; if not, write to the Free Software
## Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.
##

AUTOMAKE_OPTIONS  =    foreign no-dependencies  

WARN_CFLAGS       =    @WARN_CFLAGS@

AM_CFLAGS         =    $(WARN_CFLAGS)

SUBDIRS           =    . include lib src utils doc html

DIST_SUBDIRS      =    $(SUBDIRS)

EXTRA_DIST        =    KNOWNBUGS MACHINES README README.https README.solaris \
                       acspecific.m4 aclocal.m4 acinclude.m4

DISTCLEANFILES    =    libtool config.status PLATFORM

