---
layout: posts
title:  "Low-Effort Bread (Haskell Impl)"
date:   2021-06-13 19:42:49 -0400
published: true
categories: bread low-effort lazy haskell proof
author: Hanneli Tavante
---


## A Lazy implementaiton of Bread

### Ingredients

* 375g white flour
* 250g whole wheat flour
* 2 teaspoon full dry yeast
* 400ml warm water
* 45g brown sugar
* 2 teaspoon salt
* 35g coconut oil
* 1 tablespoon some(honey) or some(maple syrup) or some(cane molasses) or none (Optional type)
* Seeds or Oats for decoration

### Preparation

Sift both flours in a large bowl. Mix them up. Add the brown sugar in the bowl, then the yeast. 

Put the yeast in the center of the bowl, and the salt closer to the border of the bowl. Add coconut oil. Add the optional element if some. 

Slowly add water (always in the middle of the bowl), mix it up, repeat. 

You might need less water than specified. Mix it up with your hands. You should end up with a fluffy sticky dough. 

Knead the dough. It will be irregular, it's fine. 

Cover it with a dishcloth, let it rest for ~1h in a warm environment (~25C-28C). It should double its size. 

Grease the baking loaf form. Shape it by folding (no mapping!) the dough once and put it into de baking loaf form. 

Let it rest for 30 min. It should reach the height of the form. Pre-heat the oven (200C). Add some oats or seeds on top, if you want. Let it bake for \~1h15min. 

Enjoy!

### Useful hints

Baking time may vary. Try local stores for specific products, i.e. Maple Syrup may be hard to find in Europe or South America. 

### Appendix, Theorems and Artifact


Some theorems with trivial proofs for the reader.

{% highlight coq %}

Theorem commutativity_of_flours: forall (flb flw : flour),
  add_dry(flb, flw) = add_dry(flw, flb).
Proof.
  Admitted.

{% endhighlight %}

At this time, we are still working on an artifact. 
