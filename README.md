# [LibHaru2](https://libharu2.org)

This is a fork of the original libharu [Github repo](https://github.com/libharu/libharu).

#### Why the fork?

This fork will be the solely maintained version of libharu C library.
For language bindings, please create new repos.

## Contents

1. [About Haru Free PDF Library](#about-haru-free-pdf-library)
2. [Getting started](#getting-started)
   1. [Linux](#linux)
   2. [Windows](#windows)
   3. [MacOS & BSD](#macos-and-bsd)
3. [Supporting platforms](#supporting-platforms)
4. [Language Bindings](#language-bindings)
4. [License](#license)
5. [Acknowledgment](#acknowledgment)

## About Haru Free PDF Library

Haru is a free, cross platform, open-sourced software library for generating 
PDF. It supports the following features.

   1. Generating PDF files with lines, text, images.
   2. Outline, text annotation, link annotation.
   3. Compressing document with deflate-decode.
   4. Embedding PNG, Jpeg images.
   5. Embedding Type1 font and TrueType font.
   6. Creating encrypted PDF files.
   7. Using various character set (ISO8859-1~16, MSCP1250~8, KOI8-R).
   8. Supporting CJK fonts and encodings.

You can add the feature of PDF creation by using Haru without understanding 
complicated internal structure of PDF.

## Getting Started

Refer to [installation.md](./doc/installation.md) for the required libzlib and libpng libraries
which are dependencies for libharu

#### Linux

Once your dependencies are resolved (Most linux systems won't have this issue)

```sh
git clone https://github.com/Himujjal/libharu
cd libharu
./buildconf.sh # used to make ./configure file 
./configure && make && make install
```

#### Windows

This is only for MinGW-GCC compiler in Windows. For MSVC refer to [installation](./doc/installation.md#on-windows-msvc)

```sh
# TODO
```
#### MacOS and BSD

```sh
# TODO
```

## Supporting platforms

Haru is written in ANSI-C and should compile easily with any compliant C 
compiler. The following environments are tested and have their own build instructions

   3. MSYS + MinGW (Microsoft Windows)
   3. Microsoft VC++ (Microsoft Windows)
   5. GCC (Linux, FreeBSD, NetBSD, Solaris...)

Haru can work as both a static-library (.a, .lib) and a shared-library (.so, .dll).

## Language Bindings

Haru is available in different languages as bindings

1. ~~Nim~~
2. ~~Rust~~
3. ~~C++~~
3. ~~JavaScript~~
   1. ~~NodeJS~~
   2. ~~WASM~~
4. ~~Dart~~
5. ~~Python~~
6. ~~Go~~
7. ~~PHP~~
8. ~~.NET~~
   1. ~~C#~~
   2. ~~F#~~
9. ~~JVM~~
   1. ~~Scala~~
   2. ~~Java~~~
   3. ~~Kotlin~~
10. ~~Kotlin/Native~~


## License

Haru is distributed under the ZLIB/LIBPNG License. Because ZLIB/LIBPNG License 
is one of the freest licenses, You can use Haru for various purposes.

```
Copyright (C) 1999-2006 Takeshi Kanno
Copyright (C) 2007-2009 Antony Dovgal

This software is provided 'as-is', without any express or implied warranty.

In no event will the authors be held liable for any damages arising from the 
use of this software.

Permission is granted to anyone to use this software for any purpose,including 
commercial applications, and to alter it and redistribute it freely, subject 
to the following restrictions:

 1. The origin of this software must not be misrepresented; you must not claim 
    that you wrote the original software. If you use this software in a 
    product, an acknowledgment in the product documentation would be 
    appreciated but is not required.
 2. Altered source versions must be plainly marked as such, and must not be 
    misrepresented as being the original software.
 3. This notice may not be removed or altered from any source distribution.
```


## Acknowledgment

1. Takeshi Kanno and Antony Dovgal for their efforts into building the 
   first version of libHaru.

2. [Adobe Systems Inc.]() We thank Adobe Systems Inc. for publishing
   PDF specification.

