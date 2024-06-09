# Night - A family of keyboard layouts.
And so the stats rot consumes...

Night
```
b f l k q  p g o u .
n s h t m  c y a e i
x v j d z  ; w ' / ,
      r    
```
<img height="200" src="https://files.catbox.moe/jhfhne.png" />

Nightingale
```
b f l d v  p g o u .
n s h t m  c y a e i
x z ; k q  j w ' / ,
      r      
```
<img height="200" src="https://files.catbox.moe/0z2ej6.png" />

*Heatmaps generated with [KLAnext](https://klanext.keyboard-design.com/#/main) using custom text from "Three Days of Happiness" by Sugaru Miaki*
## Preface
Welcome to the design ramble of Night(s). This is a family of layouts I created - originally under one design theory, but shifted to each their own later down the line.
This is going to be a long ramble, so I'll just summarize here:

Nightingale is an alternative keyboard layout designed for column-staggered keyboards. Much like how a bird spreads its wings to take flight, Nightingale tries to take advantage of the staggering of the keys by allowing one's fingers to maintain close proximity with one another; creating a comfortable typing experience at fast speeds - akin to how one's fingers would rest on a mouse. 

Night is a modification of Nightingale that considers more       
Here is the **basic** summary:
N
Night
- Great SFBs
- Great Alternation
- Good (-1) Finger Positions
- Decent SFSs

Nightingale
- Great SFBs
- Good Alternation
- Decent Finger Positions
- Decentish SFSs

Nights
- Great SFBs
- Decent Alternation
- Decent SFSs
- Okay Finger Positions

In short, the Night family focuses on having minimal SFBs and minimal bottom row usage.
If you want to learn why there are three layouts, when one clearly seems better than the rest, read on!

## How, What, Where, When, **Why?**
Before I discuss how the layouts came to be, I have to talk about the reasoning behind them. I **strongly reccomend you read this** as if you disagree, these layouts are probably not optimal for you. I design these layouts for me, and my style of typing; if you have a similar style to mine, you may like this; if you don't that's okay! Just know these layouts may not be so suited to you.

At this point, I have reached 160+ WPM twice, 140+ WPM thrice, and 120+ WPM quadrice. In learning typing at these speeds, there is a method called "chunky typing" or "chording". This method recommends learning/memorizing common sequences of letters (such an OU; as in "you", "could", "would", etc.) instead of typing letter by letter (or even entire words). What I have personally noticed is that I find learning these chunks/chords easier when they feature natural directions of movement (i.e. typing QWE QWE QWE over WQE WQE WQE), feature fingers that are in the same position (i.e. QWE QWE QWE over QXC QXC QXC (type C with middle)), and overall do not require one finger flying from one extreme row to another (i.e. GET GET GET over BET BET BET). Through this set, we can narrow down into actual metrics:
- Minimal bad redirects
- Maximal per row usage 
- Minimal finger movement
- *Minimal 2U SFBs/SFSs*
- (and of course classic SFBs)

Defining each:
- Bad redirects are redirects that do not involve the index finger and are a series of movements between fingers that do not all "go one direction." An example is ASD vs SAD.
*I personally don't consider redirects involving index to have any issues but Night generally has low redirects regardless*
- Maximal per row usage (i.e. maximizing the usage of one row while minimizing the other) combines with minimal finger movement. If you have all the common letters together on one row, you won't have a lot of row skipping or finger movement.
- 2U (U standing for units in keys) SFBs refers to letter combinations that require the same finger to type, but also requires that finger to travel a distance of two keys instead of the usual one (distance over two units are still called 2U). A SFSs 2U is simply the same thing but there is a letter in between the two that doesn't require that same finger.

One additional theory that I intended to optimize for was spacegrams. You can think of these as the end of a word + space + beginning of a word (Ex. This is = s_i where _ is space). I didn't really dive too deep into this because I soon realized the difficulty, but it is an interesting thought. It would certainly be possible to predict the most common following words to other words, but I don't have the resources to do that. What I can do however is Monkeytype. Monkeytype realizes on TBD

Overall, this should narrow down to a layout that feels comfortable at high speeds.


With the theory done, we can now move onto the layout itself!

# Basic Layout
Before we get into optimizing for the theory, I first needed a basis, a homerow. I was tempted to use Stern (I still really really like STH).
But, it had a two main problems:
- S repeats commonly enough that it's annoying for a pinky to be doing "SS"
- T being on the index is fine, but still is a lot of usage with D added.

The reason I used STR in the first place was because S paired well with F or V, allowing a mostly low movement pinky, and TH being an inroll. If I wanted to keep this, I would have to run something like NSTH. If this is all you wanted, you could easily do with a simple index swap to Dusk (add link here:tm:):
```
x f d ; j  p c o u .
n s t h m  g y a e i
b v k l z  q w ' / ,
      r                 
```
In fact, this layout is quite decent, and I would give it a shot if you wanted TH onehand.
*update, this layout is very similar to one created by the user brownfox named "nightfall"; I currently have it named as evening if you want to check statistics on CMINI*

But here's where the theory comes in. 

## Layout Basics Part 2
First we have to decide on whether top row or bottom row maxing is better (so we know where to place the keys). In short top row is better:
- Middle up is a very comfortable and ideal column while bottom is rather poor
- Ring up is a very comfortable and ideal column while bottom is rather poor
- Pinky and ring up or down generally or minor in difference

Through this, we arrive at the conclusion of having to minimize bottom-row usage. The problem with NSTH is the reliance on an LHM index which severely limits where we can place other letters. Hence, a simple TH swap into NSHT allows us the freedom of T index and also just T being on the index (T is very common as you may know). With this established, we currently have:
```

n s h t

      r    
```
"wow so much amazingness!"

Now yes, I will still be using an R thumb. The short reason for this is that it simply has the best stats. R interacts rather terribly with every other key and thus the best position would be the thumb.
With this, I will now input the lowest SFB causing letters.

```
b v l d
n s h t
p z m k
      r    
```
Now quite accidentally, we setup LD being right next to each other. This is great as there are a lot of words with LD ("would", "could", etc.). But there are some pretty obvious issues: 
- BNP pinky is horrendous in usage
- M being too common for its position
- M_D/D_M + MD/DM being common

This is pretty bad, but let's fill in the rest of the keyboard first.
```
b v l d q  ; y o u .
n s h t j  g c a e i
p z m k x  w p ' / ,
      r    
```
Using C as an index allows the lowest possible SFBs, so naturally, I went with that.

## Index Sorting

**TBD**
