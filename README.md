
# ABOUT

**DSBSu**
is a Qt frontend to su(1).

# INSTALLATION

## Dependencies

**DSBSu**
depends on
*devel/qt5-buildtools*, *devel/qt5-core*, *devel/qt5-linguisttools*,
*devel/qt5-qmake*, *x11-toolkits/qt5-gui*,
and
*x11-toolkits/qt5-widgets*

## Getting the source code

	# git clone https://github.com/mrclksr/DSBSu.git

## Building and installation

	# cd DSBSu && qmake
	# make && make install

# USAGE

	Usage: dsbsu [-m message] [-u user] command
	   -m: Message text.
	   -u: Username. Default is root.

