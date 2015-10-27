# Makefile
#
#   (C) Copyright 2002-2015 Fred Gleason <fredg@paravelsystems.com>
#
#   This program is free software; you can redistribute it and/or modify
#   it under the terms of the GNU General Public License version 2 as
#   published by the Free Software Foundation.
#
#   This program is distributed in the hope that it will be useful,
#   but WITHOUT ANY WARRANTY; without even the implied warranty of
#   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#   GNU General Public License for more details.
#
#   You should have received a copy of the GNU General Public
#   License along with this program; if not, write to the Free Software
#   Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.
#

app0009-livewire-installation-ubuntu.pdf:	app0009-livewire-installation-ubuntu.xml
	xsltproc $(DOCBOOK_STYLESHEETS)/fo/docbook.xsl app0009-livewire-installation-ubuntu.xml | fop - -pdf app0009-livewire-installation-ubuntu.pdf

all:	app0009-livewire-installation-ubuntu.pdf
	app0009-livewire-installation-ubuntu.xml build_kernel_dialog.png kernel_built_dialog.png serial_number_dialog.png

clean:	
	rm -f *~ *.html *.pdf
