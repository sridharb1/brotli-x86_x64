# brotli-x86_x64
Native Visual Studio projects/solutions to compile on Windows x86/x64/Release/Debug

# Background #
brotli provides a CMake-based build solution. This, in Windows, is not
easy to use because of the quality of project/solution files that it
generates. I have tried to remove all the extraneous junk (ZERO_CHECK,
ALL_BUILD, INSTALL ETC. ETC.) and concentrate on
Win32/x64/Release/Debug, with DLL and static libraries and DLL
run-times.

# Installation #

  * git clone [brotli, tested w/ v1.0.7+](https://github.com/google/brotli)
  * git clone [brotli-x86_x64](https://github.com/sridharb1/brotli-x86_x64)
    to another folder
  * Copy the contents of this folder to a folder called build_folder in
    the brotli folder.
