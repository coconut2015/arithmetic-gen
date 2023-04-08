README.md
=========

This is a simple program to generate arithmetic problems for kids.  It is
used to train kids' ability to quickly solve these problems in their heads.
Typically, an exercise is timed for 5 minutes to see how many problems
kids can solve and how accurately they can solve them.

It generates a PowerPoint Presentation that contains 100 simple arithemtic
problems per page.  User can specify the number of pages of problems to be
generated.

The problems are in the following format.
```
	5 x 9 + 99
```

There can be minus operations as well, but the result will not go below
zero.

See the attached [problems](problem.pptx) and [solutions](solution.pptx).
There are 100 pages of exercises in there.

Prerequsites
------------

This python utility requires [python-pptx](https://python-pptx.readthedocs.io/en/latest/).


Usage
-----

```bash
usage: ./genarithmetic.py [options]
options:
    -h,--help           displays this help information, then exit
    -p,--page number    number of pages to be generated.  default is 1
```

License
-------

This utility is released under [APL 2.0](https://www.apache.org/licenses/LICENSE-2.0).
