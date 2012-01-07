Open Balls and Continuity
-------------------------

Previously, we introduced the notion of a :doc:`metric_spaces`.

Once you have a metric space (that is, a set of points and a function that specifies how distant you consider any two points) then you can start to develop notions of continuity and limits that form the basis for analysis.

For a metric space :math:`(X, d)`, let us call all the points less than :math:`r` away from a point :math:`a` the **open ball** of radius :math:`r` at point :math:`a`. In other words, :math:`B(X, d, a, r) = \{x \in X | d(a,x) < r\}`.

We can then define continuity by saying that a function :math:`f` between the metric spaces :math:`(X_1, d_1)` and :math:`(X_2, d_2)` is **continuous** at point :math:`a` in :math:`X` iff, given a positive :math:`r_2`, there is a positive :math:`r_1` such that :math:`f(B(X_1, d_1, a, r_1))` is a subset of :math:`B(X_2, d_2, f(a), r_2)`. In other words, :math:`f` is continuous at point :math:`a` if you can always provide an open ball at :math:`a` that maps to points within an arbitrarily small radius open ball at :math:`f(a)`.

Once you think of continuity in terms of open balls, you're able to do something interesting. Imagine that you don't know the distance function of either the domain or co-domain of the function but someone who does has precalculated all the open balls for you. Of course, for most metric spaces, there would be an infinite number of these, but the key point here is that you only need to know what the open balls are to test continuity. You don't need to know the distance function.

Let's call a set of points with the open balls precalculated an **open ball space**. Clearly it is easy to turn any metric space into an open ball space. You can't go the other way, however, as we've thrown out what the actual radius of each open ball is.

But we're now able to talk about continuity with a more general set structure than a metric space. There are many other notions that can be introduced on an open ball space, some of which we'll get to on our journey through the Poincaré Conjecture.

In the next Poincaré Project entry, however, we will take one more step of abstraction and get to the very core concept of topology itself.
