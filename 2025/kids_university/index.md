# Treasure Hunting ---Zeno's Paradox (1)


## Story Time Twist:

A few days ago, while reading Pedro’s Pirate Treasure to my kid, I made up a new puzzle story:


"Imagine you are the little pirate, Leo.
One day, you spot a brand-new mark on the treasure map!
Excited, you set off on your adventure.
But oh no—the map has a strange spell written on it:

<!--more-->


'To reach the treasure, you can only walk half of the distance left each time.
No faster, no slower.'

So, the first time, you walk half of the distance, that is $1/2$. 

The second time, you walk half of what’s left, which is $1/4$. 

The third time, you go half of the remainder, which is $1/8$.

And it keeps going, and going, and going..."

The kid shouted:
"Oh no! This will never end! Does that mean I can never get there?"

I smiled and said:
“Not true! Imagine this: 

if it takes you one whole day to walk the first half, then the rest—no matter how many tiny steps it’s split into—only takes one more day. So, in just two days, boom—you’ve got the treasure!”

The kid: "OHHHH, haha, I get it!"

Now it's fun time for us  big kids! @_@ Let’s see the math explanation.

## Math Explanation:

The trick isn’t only about "Can you get there?" — it’s really about "Can you make it in a limited amount of time?"

After all, nobody in real life keeps walking forever! That’s why looking at the time makes more sense than just adding up the distance.

### Time Calculation:

Let the total distance from $A$ to $B$ be $D$.

Assume motion is at constant speed $v$.

We may slice the journey into infinitely many segments: first coveMWr $D/2$, then $D/4$, then $D/8$ ...

Let the distance of the n-th segment be: 
$$d_n = \frac{D}{2^n}, \quad n = 1, 2, 3,…$$

The total time after n segments is 
 $$ T_n = \sum_{k=1}^n t_k = \frac{1}{v} \sum_{k=1}^n d_k = \frac{1}{v} \sum_{k=1}^n  \frac{D}{2^n} =\frac{1}{v} S_n. $$
 Thus
$$\lim_{n\to\infty} T_n = \frac{1}{v} \lim_{n\to\infty} S_n =  \frac{D}{v}\lim_{n\to\infty}  \sum_{k=1}^n \frac{1}{2^n} = \frac{D}{v}.$$

Hence even though you “divide into infinitely many times or steps,” the total time is finite, namely D/v. You arrive at B at time T = D/v. 

### Tips
Thus the paradox is resolved: infinite subdivision does not force infinite time, because each successive distance moved forward gets smaller and smaller, making the time contributions shrink to zero.

Bingo! ^_^

## Follow-Up  

Zhuangzi’s Stick

Zhuangzi once said:
“A foot-long stick, if halved each day, will never be used up.”
This expresses the idea of infinite divisibility—no matter how many times you cut it in half, there is always something left.

Is that similar to our "treasure hunting", or any contradiction between the two stories?

The story isn’t over yet — let's stay tuned! ^_^





 


