Skulpt Google Summer of Code application
===========

##Organization

[Skulpt](http://skulpt.org) is a python compiler written in javascript. It's mainly used for educatiuonal purposes, it's being used by two universities, Rice and Luther College and an online interactive textbook developed by one of the authors. We are a small team of about 6 active programmers who already do most of the work over the summer. 

The project administrators are: 

* Brad Miller (@bnmnetp)
* Scott Rixner (@rixner)

##Why?

While skulpt is used mostly as a language/runtime for beginners. It's internals are a very good way to learn how compilers and run-time systems work. Students who would help us over the summer would definitely learn a lot, as they are guided by a team that teaches the whole year through. Next to teaching students about compilers and open source software.  The work will also be beneficial to the project, as we are a small team and there are several interesting features that are waiting to be implemented.  We also have a variety of open issues that would serve as get your feet wet type projects to help students get started.  These are all issues on our [github project page](http://github.com/skulpt/skulpt).

Students would also be contributing to the efforts of computer science education.  To get an idea of how Skulpt is used in the education world check out these sites:

* [interactivepython.org](http://interactivepython.org/runestone/static/thinkcspy/index.html)
* [codeskulptor.org](http://codeskulptor.org)  --  Used in Scott's Coursera course
* [Geometry Zen](http://geometryzen.org)

## Ideas List

6. Expand the skulpt standard library to include more modules from the CPython standard library.  So far we have math, random, turtle, time (partial) random (partial) urllib (partial) unittest, image, DOM (partial) and re (partial).  Any of the partial modules could be completed, or many other CPython modules could be added.  Potential new modules from the standard library include:  functools, itertools, collections, datetime, operator, and string.  Many of these would be relatively easy projects for a less exeperienced student to take on.

7. Over time we have had numerous requests for more advanced Python modules to be included in Skulpt.  These include, portions of matplotlib, tkinter, and numpy.  These are much more challenging because they contain C code in their implementation, but if a reasonable subset could be implemented in Javascript this would make it much easier to directly add many more python modules that rely on these three.  In addition, it would allow for skulpt to potentially be used in teaching an even broader set of topics.

5. Expand and clean up the foreign function API.  This API is critical for implementing parts of the standard library.

3. Do a better job of supporting Python3 semantics, but make
Python2/Python3 behavior configurable with a single flag. Sk.python3 is
already there for this purpose.

4. Make fully workable, and expand support for DOM access as
part of the standard library.

1. Currently builtin types (list, tuple, string, etc) are not subclassable.  Making the builtins subclassable would eliminate several known bugs in Skulpt.

1. Expand and improve overall language coverage.   Currently Skulpt does an excellent job of meeting the 80/20 rule.  We cover the vast majority of the language features used by the 80% (maybe even 90%) of the coede.  But there are builtins that are not implemented at all, and there are builtins with only partial implementations.  

1.  Change the execution model so that each line/step is interruptible.
Currently, skulplt runs an entire python program from beginning to end.  We have an interrupt timer in place to prevent programs from running more than 30 seconds, during that thirty seconds, the browser is locked up.  Over time we have had various suggestions on how to restructure the main interpreter so that the program could be interrupted after each line.  This is an advanced project, that would need a lot of testing and a lot of Javascript skill to make sure that we do not sacrifice too much performance for the gain of interruptability.

2.  Implement the hooks for a debugger. This may be a half step towards
1 or may be in a completely different direction, but allowing students
to debug line by line a program they have written would have some real
benefit.




### Skills Required

Each of the projects above will require that the student knows both Python and Javascript.  Students should also be familiar with github. 


##Licence
[MIT](http://opensource.org/licenses/MIT) and [PSF v2](http://opensource.org/licenses/PythonSoftFoundation.php)

##Mailinglists
* [Google groups](https://groups.google.com/forum/#!forum/skulpt)
* [Github issues](https://github.com/skulpt/skulpt/issues?state=open)

##Mentors 

* Brad Miller  (Luther College)
* Scott Rixner (Rice University)
* Albert-Jan Pieter Nijburg
* David Holmes

