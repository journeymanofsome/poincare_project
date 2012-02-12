Open Sets
---------

In :doc:`open_balls_and_continuity`, I said:

    Imagine that you don't know the distance function of either the domain or co-domain of the function but someone who does has precalculated all the open balls for you. Of course, for most metric spaces, there would be an infinite number of these, but the key point here is that you only need to know what the open balls are to test continuity. You don't need to know the distance function.

So imagine that a friend has given you a set along with all of the subsets that are open balls. From this alone, you can establish whether a function on the set is continuous.

We can simplify the definition of continuity (and other concepts) by introducing a more general subset than the open ball called an *open set*. Even though we will initially define open sets in terms of open balls, we can simply provide the open sets without reference to open balls, much like your friend provided the open balls without reference to the metric.

A subset of a set :math:`X` is called an **open set** if it is the union of open balls of :math:`X`.

Now continuity can be defined in terms of open sets (and this definition can be proven to be the same as that using open balls). A function from :math:`X` to :math:`Y` is continuous if and only if, for each open set in :math:`Y`, the inverse in :math:`X` is also an open set.

So, instead of giving you the open balls, your friend could give the open sets. And from that, you'd be able to establish whether a function was continuous.

Now you might be wondering: in the absence of the original metric, how would we know whether the collection of open sets was really a collection of open sets and not just some random selection of subsets? (Perhaps you don't trust your friend.) Well, it turns out open sets have some interesting properties:

* the union of any collection of open sets in :math:`X` is also an open set in :math:`X`;
* the intersection of any finite collection of open sets in :math:`X` is also an open set in :math:`X`;
* the empty set is open;
* the set :math:`X` itself is open.

What is so significant about this is that a collection of subsets of :math:`X` is a collection of open subsets of :math:`X` if (and only if) it has the four properties above. It doesn't matter if it came from a distance function or open balls or some random selection of subsets. As long as the four properties above hold, the subsets are open subsets and can be used to demonstrate continuity (along with many other things).

**NOTE**: It is important that the union can be of any collection whereas the intersection can only be of a *finite* collection.

For a while, I thought the second two rules might be redundant and derivable from the first but a number of people (including Michael Walter and Richard Plagge) have clarified it for me. Michael points out the case where :math:`X = \{1, 2\}` and the candidate collection of sets is :math:`\{\{1\}\}`. This meets the first two rules but not the second two. Richard gives the example :math:`X = \{a, b, c, d\}` with the candidate collection :math:`\{\{a\}, \{a, b\}, \{a, b, c\}\}`. Again, the first two rules are met but the second two clearly do not follow.
