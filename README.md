I was quite impressed by the recent picture of Brady on his numberphile YT
channel. The visualisation of rational and irrational numbers due to a simple
construction rule revealed nice patterns!

Here is a very simple script to generate png images with this construction
rules. I expanded the functionality also to complex numbers altough there is
no good argument for this. But the results look prety ;)

To restrict the complex numbers I used for modulo: a-floor(a/b)*b

One can imediately see that this will result in numbers with abs(z)>1.
I have the feeling that one should only take numbers with abs(z) <= 1.
Not done so far...

In the modulo extension used, b may also be complex resulting in very nice
clusters.

![][