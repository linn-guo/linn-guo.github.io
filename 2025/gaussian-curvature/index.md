# From a Slice of Pizza to Gauss's “Remarkable Theorem”--- Exploring Gaussian Curvature


## The Secret Behind a Folded Pizza

Picture this:
today is pizza night! You grab a fresh, cheesy slice of pizza.
It's hot, it's gooey... and it immediately flops over like it's given up on life.

<!--more-->

<p align="center">
  <img src="/img/gaussian0.png" width="30%"/>
</p>

So, what do you do?

You pull the classic move — you fold the slice.
Just a quick bend along the crust toward the center, and magically, the floppy slice becomes firm and easy to hold!

<p align="center">
  <img src="/img/gaussian1.png" width="30%"/>
</p>

## Gaussian Curvature

Picture that slice of pizza in your hand.

Before you fold it, it's just a flat piece of dough — smooth, even, and perfectly level.
Every point on it is flat, meaning its curvature is zero.

In mathematics, we describe how a surface bends by looking at two special directions at any point:

- the maximum value of curvature in one direction — that's $k_1$.

- the minimum value of curvature in the other direction — that's $k_2$.

Multiply those two numbers, and you get the Gaussian curvature:

$$K = k_1 \cdot k_2.$$

And just like that, different surfaces reveal their own "bending personalities".

<p align="center">
  <img src="/img/gaussian2.png" width="100%"/>
</p>

Before you fold the pizza, it's a flat surface — which means

$$K = k_1 \times k_2 = 0 \times 0 = 0.$$

And here's the beautiful part: according to Gauss's Remarkable Theorem,

> The Gaussian curvature of a surface does not change if you bend the surface without stretching it.

In other words — folding the pizza doesn't change its Gaussian curvature.

That is, even after the fold, it still belongs to the geometric world of plane.

## Why Does the Pizza Hold Up?

Why does a folded pizza suddenly become strong enough to hold all that gooey cheese and sauce?

From a mathematical point of view, the pizza's Gaussian curvature K stays at zero — both before and after you fold it.

But here's the cool part: when you fold the slice along one direction, turning it into a neat little “V” shape, something interesting happens:
- In the direction across the fold, the pizza bends — so $k_1 \neq 0$.
- Hence, along the fold curve itself, $k_2 = 0$, meaning, that fold curve is a straight line, staying perfectly flat.

<p align="center">
  <img src="/img/gaussian3.png" width="30%"/>
</p>

In other words, folding the slice greatly increases its stiffness along that fold line.
Once folded, the pizza can't bend easily in that direction— that's why it suddenly gains strength, feels firm, steady, and ready to handle all that cheesy weight. 

## Developable vs. Non-developable Surfaces

In math, if a smooth surface has Gaussian curvature K = 0 everywhere, we call it a developable surface.
In simple terms, it's the kind of surface you could flatten perfectly onto a sheet of paper without stretching or tearing.

Think of:
- a folded pizza slice,
- a roll of toilet paper,
- or an ice-cream cone


<p align="center">
  <img src="/img/gaussian5.png" width="50%"/>
</p>

By contrast, if a surface has places where its Gaussian curvature isn't zero ($K \neq 0$), it's called a non-developable surface.

That means it refuses to lie flat — you can't turn it into a plane without stretching, squeezing, or ripping it apart, no matter how hard you try.

- Orange peel: it curves in every direction ($K > 0$), which is why it can never lie flat.
- Potato chip: one side curves up, the other curves down ($K < 0$); try to flatten it, and it'll snap.

<p align="center">
  <img src="/img/gaussian4.png" width="60%"/>
</p>

This also explains why a perfectly distortion-free world map is impossible.

The Earth's surface is curved — it has positive Gaussian curvature — while paper has zero curvature. 
And by Gauss's Remarkable Theorem, bending without stretching doesn't change curvature. So when we try to project our round planet onto a flat map, something has to give — area, shape, or distance will always end up distorted.

Not a design flaw — just mathematics doing its thing

## From Pizza to the Cosmos 

Gaussian curvature isn't just a neat geometric curiosity — it's one of the cornerstones of modern physics.

A century after Gauss, Albert Einstein took this elegant idea and used it to build General Relativity. In Einstein's universe, gravity isn't some invisible force tugging at planets and stars — it's the curvature of spacetime itself.

And that curvature? It's described using the very same mathematics — Riemannian geometry, the higher-dimensional extension of Gauss's work on surfaces.

Gauss exlored how a two-dimensional surface bends.

Einstein took that idea and expanded it to a four-dimensional universe.

So in a wonderfully literal way,
the way a slice of pizza folds and the way the universe curves are part of the same mathematical story — one you can taste,
and one you can marvel at among the stars.
Cheers!

