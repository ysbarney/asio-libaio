asio-libaio
=======

Introduction
------------

asio-libaio is based on asio-1.26.0 and add asynchronous read/write file 
by used libaio. Read/write file buffer must be a multiple of the filesystem 
block size and be aligned to the memory page size.

Building asio-libaio
--------------------
libaio must be install first. 

```
$ ./autogen.sh
```

then configure:

```
$ ./configure
```
then compile:

```
$ make
```

**Important:**
In the linux system, libaio is used by default to read and write files.
