
Teichmüller Space
=================

.. figure:: _static/thin_parts.png
    :scale: 100%
    :align: center

Let :math:`S` be the genus :math:`g` surface with :math:`n` punctures.
The `Teichmüller space <http://en.wikipedia.org/wiki/Teichm%C3%BCller_space>`_ :math:`T(S)` of :math:`S` is the space of hyperbolic metrics on :math:`S`, under the equivalence relation given by :math:`d ~ d'` if and only if the identity map from :math:`(S, d)` to :math:`(S, d')` is isotopic to an isometry.
We can get `Fenchel--Nielsen coordinates <http://en.wikipedia.org/wiki/Fenchel%E2%80%93Nielsen_coordinates>`_ on :math:`T(S)` by cutting :math:`S` along :math:`3g-3+n` disjoint loops, into a collection of pairs of pants.
The coordinates for a point in :math:`T(S)` consist of :math:`3g-3+n` length parameters and :math:`3g-3+n` twist parameters.
Twist parameters are given by a real number while length parameters are given by a positive real number.
For a metric :math:`d` in :math:`T(S)` we denote the length (with respect to :math:`d`) of the shortest essential loop on :math:`S` by :math:`L(d)`.

Let :math:`S` be the once-punctured torus.
Take one essential loop on :math:`S`, cutting :math:`S` into a single pair of pants.
Use the Fenchel--Nielsen coordinates to identify :math:`T(S)` with the upper half-plane.
We colour the point of the plane correponding to the metric :math:`d` in :math:`T(S)` according to :math:`L(d)`: with :math:`L(d) = 0` being black, :math:`L(d) \geq 1.5` being white and interpolating linearly inbetween.
Doing so we obtain the figure on the above.

