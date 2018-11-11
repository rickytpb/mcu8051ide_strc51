MCU 8051 IDE v1.4.9.1

DESCRIPTION:
-------------

Integrated development environment for MCS-51 based processors.
Written in Tcl/Tk, for POSIX Systems (GNU/Linux, etc.)



INSTALLATION:
--------------

At first make sure than you have all dependencies installed and install the missing ones.

1) DEPENDENCIES

	-----------------------------------------------------------------------------------------------------
	Package		min. Version	Where it's available
	-----------------------------------------------------------------------------------------------------
	REQUIRED PACKAGES:	(Without these packages this program WILL NOT run)
	tcl		8.5.9		http://www.tcl.tk/software/tcltk/downloadnow84.html
	tk		8.5.9		http://www.tcl.tk/software/tcltk/downloadnow84.html
	bwidget		1.8		http://sourceforge.net/projects/tcllib
	itcl		3.4		http://sourceforge.net/projects/incrtcl
	tdom		0.8		http://tdom.github.com/
	tkimg		1.3		http://sourceforge.net/projects/tkimg
	tcllib		1.6		http://sourceforge.net/projects/tcllib
	Tclx		8.4		http://tclx.sourceforge.net
	-----------------------------------------------------------------------------------------------------
	OPTIONAL PACKAGES:	(Without these packages some features will not be available)
	cmake		2.4.3		http://www.cmake.org/HTML/Download.html
			(If you want to install it using "./configure && make && make install".)
	rxvt-unicode	8.3		http://software.schmorp.de/
	asem-51		1.3		http://plit.de/asem-51/download.htm
	asl				(I don't know. My e-mail is <martin.osmera@mail.com>)
	vim				http://www.vim.org/download.php
	emacs				http://www.gnu.org/software/emacs/
	nano				http://www.nano-editor.org/
	le				http://www.gnu.org/directory/text/editors/le-editor.html
	hunspell
			(If you want the spelling checker function available.)
	-----------------------------------------------------------------------------------------------------

	NOTE:
		If you had any problems with installation of any of these packages
		please mention it at http://mcu8051ide.sourceforge.net/dependencies .

2) INSTALLING MCU 8051 IDE
	You can install this IDE in two ways:

	A) General
		cmake .		# <-- In case you want to install to a different
				#     directory that /usr/local, for example to /usr,
				#     then run cmake with this option:
				#     "-DCMAKE_INSTALL_PREFIX=/usr".
		make
		make install	# <-- Here you must be root.

	A) OS specific:
		If possible, download installation files/package specific for you OS, i.e.
			- .ebuild (Gentoo)
			- .rpm (RedHat)
			- .deb (Debian)
			- PKGBUILD (Arch)
			- .exe (Windows)
			- Makefile, ... (freeBSD)

	Tip:
		You can check if all needed libraries are properly installed by this command:
		mcu8051ide --check-libraries
		If you are upgrading from some previous version and the IDE won't run, try this:
		mcu8051ide --reset-user-settings --ignore-last-session

3) If you have failed to install this software, please let me know at the project web page.


PROBLEMS & SUGGESTIONS:
-----------------------

	Project web page:
		http://www.moravia-microsystems.com/mcu8051ide

	E-mail to the author:
		martin.osmera@moravia-microsystems.com or martin.osmera@gmail.cz (Only English or Czech please)


BUGS:
------
	Currently I don't know about any bug.
	If you find some bug, please let me know <martin.osmera@moravia-microsystems.com> or <martin.osmera@gmail.cz>.

NOTE:
-----
	You can help me make installation easier by making installation package for your OS.
	Thank your for trying/using MCU 8051 IDE.
