NULL = 

@INTLTOOL_DIRECTORY_RULE@
directorydir = $(datadir)/desktop-directories
directory_in_files =				\
	lxde-audio-video.directory.in		\
	lxde-development.directory.in		\
	lxde-education.directory.in		\
	lxde-game.directory.in			\
	lxde-graphics.directory.in		\
	lxde-hardware.directory.in		\
	lxde-internet-and-network.directory.in	\
	lxde-look-and-feel.directory.in		\
	lxde-menu-applications.directory.in	\
	lxde-menu-system.directory.in		\
	lxde-network.directory.in		\
	lxde-office.directory.in		\
	lxde-other.directory.in			\
	lxde-personal.directory.in		\
	lxde-settings.directory.in		\
	lxde-settings-system.directory.in	\
	lxde-system.directory.in		\
	lxde-system-tools.directory.in		\
	lxde-utility-accessibility.directory.in	\
	lxde-utility.directory.in		\
	$(NULL)

directory_DATA = $(directory_in_files:.directory.in=.directory)

EXTRA_DIST= $(directory_in_files)

DISTCLEANFILES = $(directory_DATA)
