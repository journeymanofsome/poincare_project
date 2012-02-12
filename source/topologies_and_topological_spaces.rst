Topologies and Topological Spaces
---------------------------------

We saw in :doc:`open_sets` that open subsets of a set :math:`X` always follow the rules:

* the union of any collection of open sets in :math:`X` is also an open set in :math:`X`;
* the intersection of any finite collection of open sets in :math:`X` is also an open set in :math:`X`;
* the empty set is open;
* the set :math:`X` itself is open.

If you pick a collection of subsets of :math:`X` that follows the four rules above, that collection is said to be a **topology on X**. Furthermore, a set along with a choice of topology on that set is called a **topological space**.

The use of the word *choice* is an important one. A given set will (unless it is a singleton) allow multiple valid topologies. It is the choice of topology that gives a topological space its characteristics rather than the the set itself.

Consider a simply set :math:`\{a, b\}`. The smallest possible topology would be:

:math:`\{ \{\}, \{a, b\} \}`

In other words, the empty set and the the set itself are the only two open sets. This meets the definition of a topology and, in fact, for any set will be the smallest possible topology.

Another valid topology on :math:`\{a, b\}` would be:

:math:`\{ \{\}, \{a\}, \{b\}, \{a, b\} \}`

In other words, all subsets are open. This also meets the definition of a topology. For any set the topology which defines all subsets to be open will be the largest possible topology.

There are two other possible topologies that can be defined on the set :math:`\{a, b\}`:

:math:`\{ \{\}, \{a\}, \{a, b\} \}`

and

:math:`\{ \{\}, \{b\}, \{a, b\} \}`

Step through the four rules to convince yourself that these are valid topologies for :math:`\{a, b\}`.

Note that, although this example has involved a small, finite set, everything here applies to infinite sets too. It is possible to define, for example, different topologies on the set of real numbers. One such topology is one that equates the open intervals with the open sets. This is by far the most intuitive topology on the reals but by no means the only one. 
