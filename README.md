Skulpt Google Summer of Code application
===========

##Organization

Skulpt is a python compiler written in javascript. It's mainly used for educatiuonal purposes, it's being used by two universities, Rice and Luther College and an online interactive textbook developed by one of the authors. We are a small team of about 6 active programmers who already do most of the work over the summer. 

The project administrators are: 

* Brad Miller (@bnmnetp)
* Scott Rixner (@rixner)

##Why?

While skulpt is used mostly as a language/runtime for beginners. It's internals are a very good way to learn how compilers and run-time systems work. Students who would help us over the summer would definitelly learn a lot, as they are guided by a team that teaches the whole year through. Next to teaching students about compilers and open source software.  The work will also be beneficial to the project, as we are a small team and there are several interesting features that are waiting to be implemented.

Students would also be contributing to the efforts of computer science education.  To get an idea of how Skulpt is used in the education world check out these sites:

* [interactivepython.org](http://interactivepython.org/runestone/static/thinkcspy/index.html)
* [codeskulptor.org](http://codeskulptor.org)  --  Used in Scott's Coursera course
* [Geometry Zen](http://geometryzen.org)

## Ideas List

1.  Change the execution model so that each line/step is interruptible.
I know that others have given this some thought, and I recall that Scott
has some real reservations about what it might do for performance, but
if each line didn't lock up the browser for more than a line I think
that would have some benefit.

2.  Implement the hooks for a debugger. This may be a half step towards
1 or may be in a completely different direction, but allowing students
to debug line by line a program they have written would have some real
benefit.

3. Do a better job of supporting Python3 semantics, but make
Python2/Python3 behavior configurable with a single flag. Sk.python3 is
already there for this purpose.

4. Make fully workable, and expand support for DOM access as
part of the standard library.

5. Expand and clean up the foreign function API.  This API is critical for implementing parts of the standard library.

6. Expand the skulpt standard library to include more modules from the CPython standard library.  So far we have math, random, turtle, time (partial) random (partial) urllib (partial) unittest, image, DOM (partial) and re (partial).  Any of the partial modules could be completed, or many other CPython modules could be added.

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

