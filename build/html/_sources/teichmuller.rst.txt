
Teichmüller Space
=================

Let S be the genus :math:`g` surface with :math:`n` punctures.
The `Teichmüller space <http://en.wikipedia.org/wiki/Teichm%C3%BCller_space>`_ T(S) of S is the space of hyperbolic metrics on S, under the equivalence relation given by d ~ d' if and only if the identity map from (S, d) to (S, d') is isotopic to an isometry.
We can get `Fenchel--Nielsen coordinates <http://en.wikipedia.org/wiki/Fenchel%E2%80%93Nielsen_coordinates>`_ on T(S) by cutting S along :math:`3g-3+n` disjoint loops, into a collection of pairs of pants.
The coordinates for a point in T(S) consist of 3g-3+n length parameters and 3g-3+n twist parameters.
Twist parameters are given by a real number while length parameters are given by a positive real number.
For a metric d in T(S) we denote the length (with respect to d) of the shortest essential loop on S by L(d).

Let S be the once-punctured torus.
Take one essential loop on S, cutting S into a single pair of pants.
Use the Fenchel--Nielsen coordinates to identify T(S) with the upper half-plane.
We colour the point of the plane correponding to the metric d in T(S) according to L(d): with :math:`L(d) = 0` being black, :math:`L(d) \geq 1.5` being white and interpolating linearly inbetween.
Doing so we obtain the figure on the right.

.. figure:: _static/thin_parts.png
    :scale: 75%
    :align: center

    A slice of Teichmüller space
