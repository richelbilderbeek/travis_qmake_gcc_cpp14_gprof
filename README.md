# travis_qmake_gcc_cpp14_gprof

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)|[![Codecov logo](Codecov.png)](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gprof.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gprof)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gprof.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gprof)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` only
 * Code coverage: none
 * Profiling: `gprof`
 * Source: one single file, `main.cpp`

More complex builds:
 * Use C++17: [travis_qmake_gcc_cpp17_gprof](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_gprof)

Less complex builds:
 * No `gprof`: [travis_qmake_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14)
 * Use C++11: [travis_qmake_gcc_cpp11_gprof](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_gprof)
 * Use C++98: [travis_qmake_gcc_cpp98_gprof](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_gprof)
 