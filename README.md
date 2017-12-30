# Curl for Visual Studio < 2015

Curl is a command line tool for transferring data specified with URL
syntax. Find out how to use curl by reading the curl.1 man page or the
MANUAL document. Find out how to install Curl by reading the INSTALL
document.

libcurl is the library curl is using to do its job. It is readily
available to be used by your software. 

# About

This repository is a collection of submodules (dependencies)
that curl need to build successfully.
By following the tutorial below, you should be able build
a working, statically linked version of libcurl.

**Both x86 and x64 builds are supported.**

Happy linking ;)

# Curl dependencies

- [Openssl](https://github.com/openssl/openssl): 1.0.0.1e
- [Libssh2](http://libssh2.org): 2.1.4.3
- [Zlib](http://zlib.net): 1.2.8


# Obtaining prerequisites 
	
    $ git clone https://github.com/peters/curl-for-windows.git
    $ git submodule update --init --recursive
      

  
By now you should have sweet, statically linked, CURL! ;)
