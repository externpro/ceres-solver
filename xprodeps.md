# ceres-solver dependencies

|project|license [^_l]|description [dependencies]|version|source|diff [^_d]|
|-------|-------------|--------------------------|-------|------|----------|
|<a id='ceres-solver' />[ceres-solver](http://ceres-solver.org)|[BSD-3-Clause](http://ceres-solver.org/license.html 'BSD 3-Clause New or Revised License')|C++ library for modeling and solving large, complicated optimization problems [deps: _Threads, eigen_]| |[upstream](https://github.com/ceres-solver/ceres-solver 'github.com/ceres-solver/ceres-solver')|  [patch]|
|<a id='Threads' />[Threads](https://cmake.org/cmake/help/latest/module/FindThreads.html)|[LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html 'GNU Lesser General Public License v2.1 or later')|Finds and determines the thread library of the system for multithreading support|[xpv1.0.4](https://github.com/externpro/Threads/releases/tag/xpv1.0.4 'release')|[repo](https://github.com/externpro/Threads 'github.com/externpro/Threads')|[diff](https://github.com/externpro/Threads/compare/v0...xpv1.0.4 'github.com/externpro/Threads/compare/v0...xpv1.0.4') [bin]|
|<a id='eigen' />[eigen](http://eigen.tuxfamily.org)|[MPL-2.0](http://eigen.tuxfamily.org/index.php?title=Main_Page#License 'Mozilla Public License 2.0')|C++ template library for linear algebra|[xpv3.4.0.5](https://github.com/externpro/eigen/releases/tag/xpv3.4.0.5 'release')|[repo](https://github.com/externpro/eigen 'github.com/externpro/eigen') [upstream](https://gitlab.com/libeigen/eigen.git 'gitlab.com/libeigen/eigen.git')|[diff](https://github.com/externpro/eigen/compare/3.4.0...xpv3.4.0.5 'github.com/externpro/eigen/compare/3.4.0...xpv3.4.0.5') [patch]|

![deps](xprodeps.svg 'dependencies')

Dependency version check: all 2 parent-manifest versions match pinned versions.

|diff  |description|
|------|-----------|
|patch |diff modifies/patches existing cmake|
|intro |diff introduces cmake|
|auto  |diff adds cmake to replace autotools/configure/make|
|native|diff adds cmake but uses existing build system|
|bin   |diff adds cmake to repackage binaries built elsewhere|
|fetch |diff adds cmake and utilizes FetchContent|

[^_l]: see [SPDX License List](https://spdx.org/licenses/ '') for a list of commonly found licenses
[^_d]: see table above with description of diff
