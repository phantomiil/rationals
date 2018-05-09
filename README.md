I was quite impressed by the recent clip of Brady on his numberphile YT
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

Be aware that this script uses Slang! (not Slash) http://www.jedsoft.org/slang

Examples:
![](https://github.com/phantomiil/rationals/blob/master/0_17733%2B0_819102i-1.png "Seed: 0.17733+0.819102i, Modulo: 1")

![](https://github.com/phantomiil/rationals/blob/master/0_3183098861837907-1.png "Seed: 1/PI, Modulo: 1")

![](https://github.com/phantomiil/rationals/blob/master/1_41421%2B1_41421i-0_3%2B0_5i.png "Seed: sqrt(2)+sqrt(2)i, Modulo: 1")

![](https://github.com/phantomiil/rationals/blob/master/1_41421%2B1_41421i-0_3%2B0_5i.png "Seed: sqrt(2)+sqrt(2)i, Modulo: 0.3+5.i")

![](https://github.com/phantomiil/rationals/blob/master/_0_6180339887498949-1%2B0_3i.png "Seed: (1-sqrt(5))/2, Modulo: 0.3i")

And of course:

![](https://github.com/phantomiil/rationals/blob/master/awesome.png "Seed: (1-sqrt(5))/2+0.2i, Modulo: 1")