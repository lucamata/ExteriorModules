# ExteriorModules
A Macaulay2 package for working with modules over exterior algebra. For more details, please consult this [paper](https://msp.org/jsag/2021/11-1/p08.xhtml).

Introduction
===================
Let K be a field, E the exterior algebra of a finite dimensional K-vector space, and F a finitely generated graded free E-module with homogeneous basis {g_1, ..., g_r} such that deg(g_1) <= deg(g_2) <= ... <= deg(g_r). This package allows to manage some classes of monomial submodules of F.

- The package is an extension of the one on monomial ideals (```ExteriorIdeals```), and contains some algorithms for computing stable, strongly stable and lexicograhic E-submodules of F.
- Such a package also includes some methods to check whether a sequence of nonnegative integers is the Hilbert function of a graded E-module of the form F/M with M graded submodule of F.
- Moreover, if H_(F/M) is the Hilbert function of a graded E-module F/M, some routines are able to compute the unique lexicograhic submodule L of F such that H_(F/M) = H_(F/L).
