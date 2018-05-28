.. _software:

Software
========

Most of the software that I have written can be found on `BitBucket <https://bitbucket.org/Mark_Bell>`_.
Here is some additional information about some of my larger projects.

.. _twister_software:

Twister
-------

`Twister <https://bitbucket.org/Mark_Bell/twister>`_ is a program by myself, Tracy Hall and Saul Schleimer for constructing triangulations of surface bundles and Heegaard splittings from a description of a `mapping class <http://en.wikipedia.org/wiki/Mapping_class_group>`_ of a surface.
These mapping classes are given as a composition of `Dehn twists <http://en.wikipedia.org/wiki/Dehn_twist>`_ on annuli and half twists on pairs of pants.
Twister is included in `SnapPy 1.3.10+ <http://www.math.uic.edu/t3m/SnapPy/index.html>`_ and this is how we recommend you use it.
Alternatively, you can `download Twister's source code <https://bitbucket.org/Mark_Bell/twister>`_, which you can compile as a Python 2 module, Python 3 module or standalone program and whose documentation now includes a users guide.
Twister is freely available under the GNU general public license.

I like to use Twister to build censuses of surface bundles, for example knot complements.
A `complete list of censuses <https://bitbucket.org/Mark_Bell/bundle-censuses/src>`_ I've generated can be found on BitBucket and I am happy to discuss generating new censuses that people are interested in.

    ===== = == == == ==
    Genus 1  2  3  4  5

    Depth 2 10 14 14 14
    ===== = == == == ==

One use for these censuses was to search for fibred knot complement monodromies.
This was done by using Twister to produce censuses of hyperbolic surface bundles over the circle for the surfaces S_{g,1} with :math:`1 \leq g \leq 5` to depths shown in the table.
Knot complements were then identified and compared to each of the fibred knot complement listed on `knotinfo <http://www.indiana.edu/~knotinfo/>`_ using SnapPy.

As of 18/03/2013, monodromies were found for approximately 63% of the knots listed and as shown in `this summary <https://bitbucket.org/Mark_Bell/bundle-censuses/src>`_.
This `monodromy data <http://www.indiana.edu/~knotinfo/descriptions/monodromy.html>`_ is now also part of knotinfo.
Note that, as the list of fibred knot complements built was a complete census, if a monodromy was not found for a particular knot then it cannot have a monodromy consisting of 2 / 10 / 14 / 14 /14 or fewer characters (depending on its three genus).

.. _flipper_software:

Flipper
-------

.. figure:: _static/stable_lamination_resized.png
    :scale: 75%
    :align: center

    The stable lamination of a Penner like pseudo-Anosov.

`Flipper <http://flipper.readthedocs.io>`_ is a program for computing the action of mapping classes on laminations on punctured surfaces using ideal triangulation coordinates.
It can decide the Nielsen--Thurston type of a given mapping class and, for pseudo-Anosov mapping classes, construct a layered, veering triangulation of their mapping torus, as described by `Agol <http://arxiv.org/pdf/1008.1606.pdf>`_.
Flipper is currently under development but can now also determine the conjugacy class of pseudo-Anosov mapping classes.
You can install `flipper from PyPI <https://pypi.python.org/pypi/flipper>`_ or from `flippers source code <https://bitbucket.org/Mark_Bell/flipper>`_.

.. _curver_software:

Curver
------

`Curver <http://curver.readthedocs.io>`_ is a program for performing calculations in the curve complex.
It implements the Bell–Webb algorithm to determine the Nielsen–Thurston type of a mapping class.
This algorithm runs in polynomial time but the constants involved currently make this implementation impractical.

It is currently under development but can you can install `curver from PyPI <https://pypi.python.org/pypi/curver>`_ or from `curvers source code <https://github.com/MarkCBell/curver>`_.
