# Trapezium rule
*Higher tier only*

## Ingredients
- How to read a graph
- Basic shapes
- Formation of algebraic expressions
- Substitution

## Foreword
[Skip to method](#method)

Here's a graph:  
  
<img src="img/trapezium-rule-graph-1.svg" width="70%">

How can we get the area under the curve? The area under the curve is the area highlighted in green.
Well, we could divide the curve into a series of rectangles:

<img src="img/trapezium-rule-graph-2.svg" width="70%">

And we could get an approximate area of the curve by adding up the areas of all the rectangles.
However, you can tell visually that this is a very inaccurate approach. Can we do better?

Well, we could use trapeziums instead.

Recall that the area of a trapezium is ½ × (a + b) × h:

<img src="img/area-of-trapezium.svg" width="70%">

Therefore, we could instead divide the curve into a series of trapeziums:

<img src="img/trapezium-rule-graph-3.svg" width="70%">

The long sides of the trapeziums have labels.
Y<sub>first</sub> and Y<sub>last</sub> are the first and last lengths of the trapeziums.
Y<sub>1</sub> to Y<sub>n</sub> are the rest of the lengths of the trapeziums.
The height of the trapezium is how wide it is on the graph. In this example, it's four slots wide.

Using the formula for the area of the trapezium, we can construct a formula for the approximate area of the curve:
<pre>
Area under curve = ½(Y<sub>first</sub> + Y<sub>1</sub>)h + ½(Y<sub>1</sub> + Y<sub>2</sub>)h + ... + ½(Y<sub>n</sub> + Y<sub>last</sub>)h
</pre>

Because every length appears twice, except for the first and last, we can simplify this formula into:
<pre>
Area under curve = ½ × h(Y<sub>first</sub> + Y<sub>last</sub> + 2(Y<sub>1</sub> + Y<sub>2</sub> + ... + Y<sub>n</sub>))
</pre>

## Method
<img src="img/trapezium-rule-graph-3.svg" width="70%">
<pre>
Area under curve = ½ × h(Y<sub>first</sub> + Y<sub>last</sub> + 2(Y<sub>1</sub> + Y<sub>2</sub> + ... + Y<sub>n</sub>))
</pre>
