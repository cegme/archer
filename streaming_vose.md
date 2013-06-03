
# Streaming Alias algorithm

Vose algorthim is one of the best methods to sample random numbers from a discreet distribution.
However, we come across an application where the items to be sampled are not fixed.
Instead, they are being continuously updated.

Here we look into how we can improve the Vose's alias algorithm for sampling with streaming updates.

We also look to sample with removals and edits.

We hope to support this while keeping the \Theta(n) construction time, 
sampling time of \Theta(1) and any incremental updates 
should be performed in O(1) time.



### Papers

+ [An Efficient Method for Generating Discrete Random Variables with General Distributions](http://dl.acm.org/citation.cfm?doid=355744.355749) by  Alastair J. Walker
+ [A Linear Algorithm For Generating Random Numbers With a Given Distribution](http://web.eecs.utk.edu/~vose/Publications/random.pdf) 
by Michael D Vose



### Links 
+ [Darts, Dice, and Coins: Sampling from a Discrete Distribution](http://www.keithschwarz.com/darts-dice-coins/)
+ [The Alias Method for Sampling from Discrete Distributions](http://pandasthumb.org/archives/2012/08/lab-notes-the-a.html)
+ [Alias Method](http://en.wikipedia.org/wiki/Alias_method)
