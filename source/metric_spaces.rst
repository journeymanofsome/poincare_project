Metric Spaces
-------------

A surface is more than just a set of points. Points on a surface have a notion
of *closeness* that doesn't exist with a set unless we add some structure.

One way we can introduce the idea of closeness is to introduce the idea of the
distance between points. That is, a function :math:`d` that gives us a number for any
pair of points.

To be a **distance function**, our function must meet some additional
requirements:

* all distances must be non-negative: :math:`d(x,y)>=0`
* the distance between :math:`x` and :math:`y` is zero if and only if :math:`x` and :math:`y` are the same point: :math:`d(x,y)=0 \iff x=y`
* the distance between :math:`x` and :math:`y` is the same as the distance between :math:`y` and :math:`x`. In other words, the distance function is always *symmetric*: :math:`d(x,y)=d(y,x)`
* finally, the distance between two points can never exceed the sum of the distance between each of the points and a third point. This is often referred to as the *triangle rule*: :math:`d(x,z)<=d(x,y)+d(y,z)`

A distance function is often called a **metric**. A set of points with a
distance function is called a **metric space**.

A metric space clearly has a notion of closeness. A point :math:`y` is closer to :math:`x`
than :math:`z` is if :math:`d(y,x)<d(z,x)`.
