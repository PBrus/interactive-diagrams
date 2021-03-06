# Interactive-diagrams
[![Build Status](https://travis-ci.org/pbrus/interactive-diagrams.svg?branch=master)](https://travis-ci.org/pbrus/interactive-diagrams)
[![Code](https://img.shields.io/badge/code-Python-blue.svg "Python")](https://www.python.org/)
[![PyPI version](https://badge.fury.io/py/idgrms.svg)](https://badge.fury.io/py/idgrms)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg "MIT license")](https://github.com/pbrus/interactive-diagrams/blob/master/LICENSE)

This program allows to visualize points on different diagrams and interact with them.

![photometric_diagrams](http://www.astro.uni.wroc.pl/ludzie/brus/img/github/phot-diagrams.gif)

## Installation

To install the package please type from the command line:
```bash
$ sudo pip3 install idgrms
```
or alternatively:
```bash
$ git clone https://github.com/pbrus/interactive-diagrams
$ cd interactive-diagrams
$ sudo python3 setup.py install
```

## Usage

To use the program properly you need to prepare a file with data. At the beginning call the script from the terminal window with the `-h` option:
```bash
$ interactive_diagrams.py -h
```
This will give you a description of all options. If you need to see the program in action immediately, please download the `example_data/` directory from the repository to your working directory. A basic call:
```bash
$ interactive_diagrams.py example_data/mags.db --col 12 -10 --col 12 -4
```
More advanced call:
```bash
$ interactive_diagrams.py example_data/mags.db --col 12 -10 --col 12 -4 --grp example_data/best.num green --grp example_data/better.num yellow -t
```
In both cases try to click on any point to see changes on diagrams.

I encourage to visit my website to see more detailed description of this program. The current link can be found on my [GitHub profile](https://github.com/pbrus).

## License

**Interactive-diagrams** is licensed under the [MIT license](http://opensource.org/licenses/MIT).
