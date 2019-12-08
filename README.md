First steps
-----------

Generate the documentation: make doc

Build the application and test.

V. Santos, 07-dez-2019,13:27

Instructions and main packages
------------------------------
To develop and build the application, besides the GNU C/C++ compiler,
you need to have installed some packages:

  cmake
  libgtk-3-dev
  glade

and some documentation tools are highly advised:

   libgtk-3-doc
   gtk-3-examples
   libcairo2-doc
   devhelp
   Doxygen

So, perform the following:

   sudo apt install cmake
   sudo apt install libgtk-3-dev libgtk-3-doc gtk-3-examples
   sudo apt install glade
   sudo apt install libcairo2-doc
   sudo apt install devhelp
   sudo apt install doxygen doxygen-gui

To test whether GTK was properly installed and also get acquainted with GTK
possibilities, you can use the following command to perform some testings and
verifications.

  /usr/bin/gtk3-demo

prototypes.h
------------

To generate the prototypes file from the proper cmake target, the following is needed:

  sudo apt install cproto exuberant-ctags indent


misc
----
There are other packages that can be useful for some scripts to work 
properly, but they are not necessary for this project. Follow some examples.

  sudo apt install xutils-dev
  sudo apt install graphviz
  sudo apt install imagemagick

asciidoc
--------
If you want to edit documents in asciidoc format, the following are
needed/recomended:

  sudo apt install asciidoc dblatex fop source-highlight


opencv
------
If you also need to use opencv, install it and its documentation:

  sudo apt install libopencv-dev
  sudo apt install opencv-doc

Although the documentation can be found online.
After version 3, openCV is focused on C++ and Python. So, its documentation is
oriented in those directions:

  https://docs.opencv.org/master/

However, up to that version, the documentation also incuded C language, keeping
the compatibility with the existing programs in C. So, if you use C language
for openCV, report to the last documentation version available for C, such as
version 2.4.X:

  https://docs.opencv.org/2.4/




