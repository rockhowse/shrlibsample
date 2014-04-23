shrlibsample
============

This is a more windows-centric version of the Matlab sample .c dll including a Visual Studio 2012 project pre-configured.

### Major changes

* used a basic windows .dll template including the 
* removed any references to "mex" as anyone who codes windows but not matlab won't know what this is
* added the "extern C" to the .h file so that function names would be C compatible instead of C++ mangled