# musl libc

[musl] is a C standard library implementation for Linux. This is a wiki
maintained by the enthusiastic user community of musl. Some of musl's major
advantages over [glibc] and [uClibc]/[uClibc-ng] are its size, correctness,
static linking support, and clean code.

# Introduction

- [Getting started]
- [FAQ]
- [Compatibility] - software and standards compatibility of the API musl
  provides
- [Supported Platforms] - compilers, architectures, platforms, where musl works
- [Projects using musl] - Linux distributions and other projects using musl
- [Contacts] - mailing list, IRC, support, discussion

# Using musl

- [Official documentation]
- [Environment variables affecting musl][Environment variables]
- [Functional differences from glibc]
- [Guidelines for Distributions]

# Contributing

- [Reporting bugs]
- [Writing tests]
- [Funding maintenance and development]

# Development

- [Open issues]
- [Roadmap for post-1.0 development][Roadmap]
- [How to port musl to a new arch][Porting]
- [Ideas for future development][Future Ideas]
- [Design Concepts]
- [Coding Style]
- [Mathematical Library]
- [ABI Cheat Sheet]

# Further reading

- [Comparison] with other Linux libc implementations
- [Install notes], [readme], and [release notes] in the official repo.
- [Musl cross][musl-cross] - This is a small suite of scripts and patches to build a musl libc cross-compiler.
- [Musl cross make][musl-cross-make] (recommended) - Second generation advanced makefile-based approach for producing musl-targeting cross compilers
- [musl.cc pre-built cross compiler downloads][musl-cc-pre-built-cross] for different arches
- [skarnet pre-built cross compiler downloads][skarnet-pre-built-cross] for different arches
- Lightweight [alternatives to common libraries and software][Alternatives]
  that may be of interest in building small musl-based systems
- [Bugs found by musl] - mostly glibc and POSIX issues, some of them affect the
  development of musl
- [Building Busybox] explains how to build Busybox 1.22.1 against musl (and
  kernel header compatibility in general)

[musl]: https://www.musl-libc.org/
[glibc]: https://www.gnu.org/software/libc/
[uClibc]: http://www.uclibc.org/
[uClibc-ng]: http://uclibc-ng.org/
[Official documentation]: https://www.musl-libc.org/manual.html
[Comparison]: https://www.etalabs.net/compare_libcs.html
[Install notes]: https://git.musl-libc.org/cgit/musl/tree/INSTALL
[README]: https://git.musl-libc.org/cgit/musl/tree/README
[release notes]: https://git.musl-libc.org/cgit/musl/tree/WHATSNEW
[musl-cross]: https://github.com/GregorR/musl-cross
[musl-cross-make]: https://github.com/richfelker/musl-cross-make
[musl-cc-pre-built-cross]: https://musl.cc
[skarnet-pre-built-cross]: https://skarnet.org/toolchains/


