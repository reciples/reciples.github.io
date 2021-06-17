---
layout: posts
title:  "Spaguetti aglio e olio + bacon. simpl. reflexivity."
date:   2021-06-16 19:33:00 -0400
published: true
categories: spagetti aglio olio
author: Hanneli Tavante
---

  

### Ingredients

* 250g Spaghetti \# 8
* 2.5 tbsp olive oil
* 2 cloves garlic
* Salt and black pepper
* 1 tbsp lemon juice
* Parsley
* 3 bacon stripes
* Other types of pepper if desired (Optional)

### Preparation

The low-effort series is back! Don't expect complex proofs here.

In a large boiling pot, add 3L of water, add 1 teaspoon of salt, let it boil. Cut the garlic in very thin slices (use a mandoline if you have one). 

If you are planning to add bacon, pile up the slices and cut them in very small pieces. Heat up (medium heat) a separate pan, add the bacon, cover the pan. Watch it from time to time to prevent it from burning. 

After the water starts to boil, add the spaghetti. *DO NOT BREAK THE SPAGHETTI*. There is no LEM here. 

After you put the spaghetti in the boiling pan, take a large and (tall) frying pan. Add the olive oil and the garlic. The olive oil must cover completely the bottom of the pan; if 2.5 tbsp was not enough, add some extra. Medium heat, wait 2-3 min for a golden set of sliced garlic. Add the pepper(s) and the parsley (I like a lot of parsley in this recipe). Add salt.

Pour one ladle of the boiling pasta water into the frying pan, enjoy the nice sound it produces when it touches the hot oil. By this time, your spaguetti must be nearly _al dente_ (namely very firm, not soft; you don't want it to be soft). 

Remove the spaghetti from the boiling water, put it in the frying pan. Mix everything in the frying pan. Add the lemon juice (it will remove the greasy aspect of this recipe). Mix it again. Add bacon, if any. Final pan shake, and it's ready to serve.

Qed.

Enjoy!

### Useful hints

This recipe goes well with zucchini or broccoli too! I often make it vegetarian by not having any meat and having one of these two elements instead.
It is also relatively simple and quick to make. After some practice, you can get it in less than 10 min, plus the time to do the dishes. 

I also use tiny cubes of chicken breast if I have them as leftovers from another dish.

Can you use other types of pasta? Yes, sure. Just watch out for the cooking time. I like spaghetti because the prep. time of the ingredients matches perfectly with my cooking speed. But nothing prevents you from using tagiatelle or linguine. 

### Appendix, Types and Artifact

I'd write some proofs, but I am busy eating the spaghetti that I just made. If you break your spaghetti, I'll be very sad. 


{% highlight coq %}

Theorem break_spaghetti_implies_bottom: forall (sp : spaghetti),
  break sp -> sp.
Proof.
  simpl. contradiction. Qed.

{% endhighlight %}