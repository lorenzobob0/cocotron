Cocotron-Xcode-5
================

Xcode 5 compatible Version of Cocotron

https://github.com/forensix/Cocotron-Xcode-5-Plugin must previously be installed!

Only Foundation was configured. In order to use AppKit etc. add/change the following
settings:

OS X Deployment Target —> Compiler Default

Compiler for C/C++/Objective-C —> Cocotron (GCC 4.3.1)

OTHER_C_FLAGS —> -DWINDOWS

Path to Linker Dependency Info File —> Remove

NOTE:
NSPropertyListReader is still unusable since Xcode 5 has changed XIB (XML) format!
