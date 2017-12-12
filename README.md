# Enki (QT5)

a fast 2D robot simulator using the QT5 build system.

© 1999-2017 Stéphane Magnenat and others ([full list](AUTHORS))

© 2017 Bernd Porr <mail@berndporr.me.uk>

## License

[GPL 2.0](LICENSE).

## Prerequisites

To compile Enki and programs who depend on it, you need:
* a working and fairly recent C++ compiler
* QT5

## Enki simulator compilation under Unix (library)

Change into the enki subdirectory and type:

	qmake

and then build Enki by running:

	make

and finally install the library with
	
	sudo make install


## Compiling/running the examples

To compile the examples you need to do again `qmake` and `make`. This uses the
previously compiled enki library.

To run it type `./playground`
