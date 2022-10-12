# Common Description Format for C++ Libraries and Packages

Authors: Gabriel Dos Reis (Microsoft), and Luis Caro Campos (Conan)

WG21 paper number: D2673R0

Date: 2022-10-12

# Summary

The incorporation of C++ Modules into C++20 has increased the pressure for C++ package providers and consumers to find a shared communication mechanism to describe module-based C++ libraries and packages.  The community has skimped by with traditional header file-based libraries and packages, leading to multiple solutions that work well in some scenarios, but that lack interoperabiloty across compilers, build systems, package managers, and repository maintainers.


With the arrival of modules, those conventional methods are no longer sufficient.  Failure to act now is likely to lead to further fragmentation of the C++ community along boundaries of a variety of more-or-less competing or incompatible tools.  This paper requests the creation of a focused subgroup to define, ideally with some reference implementation, a format specification for describing C++ libraries and packages.  The output of the subgroup is expected to submitted to the ISO C++ committee for considerarion as input to a Technical Report on C++ Packages Description.  Consequently, we request that it be hosted alongside other WG21 working groups' projects.
