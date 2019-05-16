---
layout: post
title: Brain VS GPU
image: /img/brain_gpu.png
---

What's the best way to gain performance in the execution of your calculus intensive program?

Well, it's still your brain: just write better code, thanks mainly to vectorisation of the loops.

Here is an example, in four blog post. Probably this very example will be not useful to you, but the techniques I used are clearly explained, and you can replicate them in a relatively easy way.

How much I arrive to gain? Around 500x in execution speed. 
Which means that if the original program took 8 hours to be executed, with those tricks you have the results in a single minute.

Yes, that's a lot, and there is no way you can obtain a similar improvement just using a different hardware, like GPUs.

![tachimetro](/img/tachimetro.jpeg)

Ready to go?

[Part 1, problem description](https://towardsdatascience.com/speeding-up-your-code-1-the-example-of-the-mean-shift-clustering-in-poincar%C3%A9-ball-space-d46169bfdfc8)

[Part 2, vectorizing the loops](https://hackernoon.com/speeding-up-your-code-2-vectorizing-the-loops-with-numpy-e380e939bed3)

[Part 3, batches and multithreading](https://towardsdatascience.com/speeding-up-your-code-3-batches-and-multiprocess-52d2d34a4091)

[Part 4, in-time compilation](https://medium.com/@vincenzo.lavorini/speeding-up-your-code-4-in-time-compilation-with-numba-177d6849820e)
