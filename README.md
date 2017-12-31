# Curl for Visual Studio < 2015

Curl is a command line tool for transferring data specified with URL
syntax. 

This is an updated version with Curl v7.57.0, libssh2 v1.8.0, OpenSSL v1.1.0h, zlib v1.2.10
that build in Visual Studio 2015 and 2017 

libcurl is the library curl is using to do its job. It is readily
available to be used by your software. 

# About

This repository is a collection of submodules (dependencies)
that curl need to build successfully.
Simply open curl.sln and start build, you should be able build
a working, statically linked version of libcurl.

**Both x86 and x64 builds are supported.**

Happy linking ;)

# Curl dependencies

- [Openssl](https://github.com/openssl/openssl): 1.1.0h
- [Libssh2](http://libssh2.org): 2.1.8.0
- [Zlib](http://zlib.net): 1.2.10


# Obtaining prerequisites 
	
    $ git clone -b 7.57-1.80-1.2.10 --single-branch https://github.com/gelotus/curl-for-windows
    $ git submodule update --init --recursive
      

  
By now you should have sweet, statically linked, CURL! ;)
