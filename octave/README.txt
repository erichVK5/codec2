README.txt
For codec2/octave directory
Created 24 June 2012 by David Rowe

in addition to installing octave, and the GNU units package

i.e. for debian package manager based linux distributions:

   sudo apt-get install octave liboctave-dev units

further packages will be required:

1/ To support some of the Octave scripts (in particular fdmdv) in this
   directory the following Octave packages need to be installed:

      control general image miscellaneous optim signal specfun struct

2/ Download these tar balls from:

   http://octave.sourceforge.net/packages.php

3/ Install each package from the Octave command line with:

   octave:3> pkg install package_file_name.tar.gz

