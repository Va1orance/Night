# Night - A thumb alpha keyboard layout.

<img height="300" src="https://files.catbox.moe/t5pnes.png" />

*Layout image made with [VIA](https://usevia.app/)
## Preface
As custom ergonomic keyboards become more available, layouts that utilize thumb alpha keys becomes more viable. Of the current list of popular, non-trick* utilizing thumb alpha layouts, only [Dusk](https://altlayouts.com/dusk/) is recommended. Night serves to join the recommendation list as a potential alternative to Dusk.

This page will cover the design of Night - exploring how it was made, potential modifications, problems, and my own experience using the layout.

*Layouts that utilize magic, repeat key, double letters, etc.

## Statistics
Night boasts good stats in general. It focuses on minimal SFBs, good SFSs, low 2U SFSs, and ultra-low bad redirects. It is designed to feature high alternation, a factor some prefer, while others do not. (See what these terms mean in the following section).

<img height="500" src="https://files.catbox.moe/pefdyu.png" />

See: [Cyanophage's Web Analyzer](https://cyanophage.github.io/playground.html?layout=bflkzpgou%2Cnshtmycaei-xvjdq%27w%3B%2F.r&mode=ergo&lan=english)

<img height="500" src="https://files.catbox.moe/zmj7z0.png" />

See:[KeySolve](https://clemenpine.github.io/keysolve-web/) (This one you will need to input the layout yourself. Also, it must be mirrored due to Keysolve only supporting a right thumb alpha.)

<img height="300" src="https://files.catbox.moe/seal5h.png" />

See: [AKL Discord Server](https://discord.gg/2qq8qmDtFf) (Go to #cmini and type in !cmini view Night)



## Terminology
What is SFB, what is SFS, etc.? These are terms used to describe certain statistics of a keyboard layout. They help us quantify what exactly is good or bad in a layout.
It is important to understand these as each plays a role in how layouts are designed.


*All examples are in reference with the QWERTY keyboard layout.

### Primary/Essential:
**SFB:** Same finger bigram. You use the same finger to type two keys. This is much slower than using different fingers. (Example: ED)
**SFS/DSFB:** Same finger skipgram/Disjointed same finger bigram. You use the same finger to type two keys, however, there is a key between which involves another finger. Debated in certain parts of the community, SFSs are slower as one key in between is not enough time for a finger to move to the next. (Example: WAS)
**2U SFS:** Same as above, however, the distance the repeating finger has to move is 2 key units or greater. Noticeably worse than SFS/DSFB due to the added movement. (Example: MAY)
**Bad Red:** A variant of a redirect, bad redirects do not involve the index finger. Redirects involve the key sequences against a common direction. This series of key sequences is considered more difficult although not uncomfortable. (Example: SAD)

### Secondary/Preferential:
**Roll:** Two key presses on the same hand with different fingers, followed by one more keypress on the other hand.
**Red:** Redirect. Redirects involve the key sequences against a common direction. This series of key sequences is considered more difficult although not uncomfortable. Compared to Bad Reds, regular redirects are considered minor due to their effects in typing being questionable.


## How, What, Where, When, **Why?**
At this point, I have reached 160+ WPM twice, 140+ WPM thrice, 120+ WPM quadrice, and 100+ WPM a good few times. Going through so many layouts, I had to learn, relearn, adapt, undo, among many other things, on each layout. However, each time I approached those top speeds, one particular skill had to be learned: chording. 

Also commonly referred to as chunky typing, this method involves learning/memorizing common sequences of letters (such an OU; as in "you", "could", "would", etc.) or even whole words instead of typing l e t t e r  b y  l e t t e r . 

In MY learning, I noticed that learning these chunks/chords were easier when they feature natural directions of movement (i.e. typing QWE QWE QWE over WQE WQE WQE) and feature fingers that are in close proximities (i.e. QWE QWE QWE over QXC QXC QXC (type C with middle)) along with the typical SFB optimizations. 

These factors translates roughly into these metrics:
- Minimal bad redirects (normal redirects have minor effects)
- Maximal same row usage (this will help keep all the fingers together)
- "Minimal finger movement" - will be discussed at a later section
- Minimal 2U SFSs
- Minimal SFBs

Overall, this should narrow down to a layout that feels comfortable at high speeds.

## Notice
Everything I mention below will have variations or other ideas I ultimately did not decide to go through with. Take a look at the    `Modifications` section for suggestions :D.

# Basic Layout
Before we get into optimizing for the theory, I first needed a basis, a homerow. I was tempted to use Stern (I still really really like STH).
But, it had a two main problems:
- S repeats commonly enough that it's annoying for a pinky to be doing "SS"
- T being on the ring is fine, but a little much with D and K added on.

The reason I used STH in the first place was because S paired well with F or V, allowing a mostly low movement pinky, and TH being an inroll. If you want to maintain this, you can run NSTH. A simple index swap to Dusk would suffice (add link here:tm:):
```
x f d ; j  p y o u .
n s t h m  g c a e i
b v k l z  q w ' / ,
      r
(this isn't Nightfall)
```
This layout idea was originally picked up by Brownfox and you can check out his layout series Nightfall on cmini.

However, this layout does not address the theory goals mentioned in the section above.
In order to accommodate for the appropritate letter stacks (discussed in the next passage), NSHT was chosen as the consonat homerow.

Along with the letter stacks, this setup enables repeat S to be moved away from the pinky, and moves the high frequency T to the index. *More details later...*

## Layout Basics Part 2
Now that we settled on the homerow, what about the consonant stacks (we will do vowels)? First, we have to decide on whether top row or bottom row is better. This is still a form of debate, layout families like Hands Down prefer the lower row. However, in my opinion, the top row is superior due to:
- Middle up is a very comfortable and ideal position while bottom is rather poor comparatively.
- Ring up is a comfortable and ideal position while bottom is
questionable to most.
- Pinky and index up or down generally both accepted (index down favoring) or minor in effect.

Through this, top-row likely would be preferred. 

Now after tinkering with many many layouts, a few special column setups come to mind.
- DTK alike to Dusk, Stern, Nightfall. Good SFBs and very minimal SFSs.
- LHM alike to Dusk, Stern, Nightfall. Good SFBs, but rather high SFSs.
- PNB alike to SNTH/SNTHR/SNTHRF. Good SFBs, but PN causes rather high SFSs.
- FSV alike to Dusk. Good SFBs, acceptable SFSs.

*Layouts mentioned are by no means a comprehensive list, it is simply for reference.

With these preliminary setups, the problem with NSTH is revealed due to the reliance on an LHM index (otherwise the good positions are wasted). Hence, a simple TH swap into NSHT allows us the freedom of the high use T index. So, to just throw everything together:
```
b f l d
n s h t
p v m k
      r
```
*already looking familiar...*

Now yes, I will still be using an `R` thumb. The short reason for this is that it simply has the best stats. `R` interacts rather terribly with every other key and thus the best position would be to isolate it to the thumb.

Now quite accidentally, we setup `LD` being right next to each other. If you do little digging, you will find a lot of layouts using `T` which place the `D` in the bottom position. This is because the index curling position is regarded as one of, if not the best non-homerow positions.

However, this LD setup is great as there are a lot of words with LD ("would", "could", etc.) which follows are design theory of close fingers. That being said, there are some pretty obvious issues with the rest of the layout: 
- BNP pinky is horrendous in movement.
- M is a rather common key, going against our same-row theory.
- Rest of the index keys are not utilized.

This is pretty bad, but let's fill in the rest of the keyboard first.
```
b v l d q
n s h t j 
p z m k x
      r    
```

## Vowel Hand Basics
The vowel hand of layouts are generally well developed. With the remaining letters, a `C` index can be used to maintain low SFBs.
```
b f l d z  ; y o u .
n s h t j  g c a e i 
p v m k x  q w ' / ,  
      r    
```
This is a pretty generic setup with `AO` and `EU`. `AO` and `EU` enables low SFBs among other stats. The advantage of `AO EU` over `EU AO` is `AO` features higher movement, thus being better suited for the middle finger. Meanwhile, `EU` has `E` with higher usage, but `U` features significantly lower usage compared to all other vowels; an overall lower movement and thus better suited to the weaker finger.

With this, `you` is able to be a roll instead of a redirect. If they were to be reversed, a `YI` pinky would have to be used (to maintain `you`). The main disadvantage of this setup is `I` is very ideal for puntucation. Again, check `Modifications` for further info.

## Nights
The vowel hand isn't quite done yet, but we have to fix the consonant hand first.

The first major problem is `BNP`. The whole setup itself is just too much movement for pinky. Hence, we should split it up. 
```
p b l d v  q y o u .
n s h t j  g c a e i 
x v m k x  f w ' / ,  
      r    
```
This first setup, known as Nights can still be found on cmini. I don't reccommend it, but BS is an interesting setup to consider:
```
b p l d v  q y o u .
s n h t j  g c a e i 
x z m k x  f w ' / ,  
      r    
```
You may notice `S` and `N` are actually swapped here. This is because the `PN` pairing is significantly more usage than the `SB` pairing. Now of course, this reason for spliting up `PNB` wasn't done just for that.

One common thing I noticed was the frequency of interactions with `L`. Specifically with `F, P, B, D`. This lead me to place these letters in close proximity to L in order to maximize these, without sacrificing SFBs if possible. As a resual of this constraint, F must be pushed to the vowel hand.

Following this, V is pushed up to the top corner of the index in line with the design theory. 

```
b p l d v  f w o u .
s n h t j  g y a e i 
x z m k x  ; c ' / ,  
      r    
```
