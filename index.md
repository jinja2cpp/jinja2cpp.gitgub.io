---
layout: default
title: Home
nav_order: 1
description: "Powerful text template engine for your C++ project!"
permalink: /
---

<div align="center"><img width="200" src="https://avatars0.githubusercontent.com/u/49841676?s=200&v=4"></div>

# Bring the powerful text template engine to your C++ project!
{: .no_toc }

{: .fs-6 }
Jinja2C++ is a modern C++ implementation of the [Python Jinja2 template engine](http://jinja.pocoo.org/docs/2.10/). Originally, it was inspired by [Jinja2CppLight](https://github.com/hughperkins/Jinja2CppLight) library and now Jinja2C++ brings support for mostly all Jinja2 templates engine features into C++ world.
{: .fs-6 .fw-300 }

## Main features of Jinja2C++:
{: .no_toc }

- C++14/17 library
- Supports mainstream compilers (Visual C++, gcc, clang)
- Easy-to-use interface/Great UI.
- Conformance to [Jinja2 specification](http://jinja.pocoo.org/docs/2.10/)
- Partial support for both narrow- and wide-character strings both for templates and parameters.
- Built-in reflection for C++ types and popular json libraries ([nlohmann]( https://github.com/nlohmann/json) and [rapid](https://github.com/Tencent/rapidjson)).
- Powerful full-featured Jinja2 expressions with filtering (via '\|' operator) and 'if'-expressions.
- Control flow statements ('set', 'filter', 'for', 'if', 'do', 'with').
- Templates extension ('extends', 'block').
- Templates reuse ('include', 'import', 'from').
- Macros ('macro', 'call').
- Rich error reporting.
- Shared template enironment with templates cache support.

[View it on GitHub](https://github.com/jinja2cpp/Jinja2Cpp){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on Conan](https://bintray.com/beta/#/flexferrum/conan-packages/jinja2cpp:flexferrum?tab=overview){: .btn .fs-5 .mb-4 .mb-md-0 }

## How to get Jinja2C++
{: .no_toc }

The simplest way: to get the latest conan.io package: [
jinja2cpp/0.9.1@Manu343726/testing](https://bintray.com/manu343726/conan-packages/jinja2cpp%3AManu343726/0.9.1%3Atesting)

Or follow the [build and install instructions](/docs/build_and_install.html)

## About the project
{: .no_toc }

Jinja2C++ is &copy; 2018-2019 by [Flex Ferrum](https://github.com/flexferrum). 

### License
{: .no_toc }

Jinja2C++ is distributed by a [Mozilla Public License 2.0](https://github.com/jinja2cpp/Jinja2Cpp/blob/master/LICENSE).

### Contributing
{: .no_toc }

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change.

### Acknowledgments and copyrights
{: .no_toc }

Thanks to authors of original Jinja2 specification for the exceptional work!

Thanks to [**manu343726**](https://github.com/Manu343726) for CMake scripts improvement, conan.io packaging and bugs hunting and fixing.

Thanks to [**martinmoene**](https://github.com/martinmoene) for perfectly implemented xxx-lite libraries.

Thanks to [**vitaut**](https://github.com/vitaut) for the amazing text formatting library.

Thanks to [**martinus**](https://github.com/martinus) for the fast hash maps implementation.

File [include/jinja2cpp/value_ptr.hpp](https://github.com/jinja2cpp/Jinja2Cpp/blob/master/include/jinja2cpp/value_ptr.hpp) Copyright © 2017-2019 by [**Martin Moene**](https://github.com/martinmoene)

File [src/lexertk.h](https://github.com/jinja2cpp/Jinja2Cpp/blob/master/src/lexertk.h) Originally copyright © 2001 by Arash Partow
