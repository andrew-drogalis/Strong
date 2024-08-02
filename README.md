
# Strong

Welcome to the Strong keyboard layout!

If you have a Linux, Mac, or Windows layout software and want to contribute it to the repository, submit a pull request. Thank you!

## Table of Contents

* [Goals](#Goals)
* [Layout](#Layout)
    * [Hand Split](#Hand-Split)
    * [QWERTY and Vim](#QWERTY-and-Vim)
    * [Full Statistics](#Full-Statistics)
        * [Rolls](#Rolls)
        * [Redirects](#Redirects)
        * [LSB](#LSB)
        * [SFB](#SFB)
* [Weaknesses](#Weaknesses)
    * [Left Pinky](Left-Pinky)
    * [Scissors](Scissors)
* [Terminology](#Terminology)
* [Etymology](#Etymology)
* [Sources](#Sources)
* [Contact](#Contact)

## Goals

The goal of this project was to improve upon the design of Sturdy, Canary, and Gallium either by increasing rolls and maintaining redirects or maintaining rolls and decreasing redirects.

Here's a brief summary table of the main statistics for each:

```
                     Strong      Sturdy     Canary     Gallium    Graphite
Sfb:                 0.990%      0.935%     0.962%     0.956%     0.996% 
Dsfb:                6.236%      6.222%     8.057%     6.456%     6.260%
Lsb:                 0.293%      2.413%     2.675%     1.456%     1.358%

Total Rolls:        48.010%     48.082%    48.537%    44.566%    44.276%
Total Redirects:     3.763%      5.399%     7.152%     3.157%     3.043%
```
[Data Source](https://getreuer.info/posts/keyboards/alt-layouts/stats.html)

There are other important metrics to consider, such as hand split, scissors, Vim usage, and difficulty to learn from QWERTY — all to be discussed below.

## Layout

Here's the keyboard layout with finger heatmap:

<img src="https://raw.githubusercontent.com/andrew-drogalis/Strong/main/strong-layout.png" alt="Strong Alt Keyboard" style="padding-top: 10px;">

```
Strong
p l d y w q f o u ,
n r t s g x h a e i
b j k c v z m ' ; .
```

And here is the statistics from the oxeylyzer keyboard analyzer:

<img src="https://raw.githubusercontent.com/andrew-drogalis/Strong/main/strong-stats.png" alt="Strong Alt Keyboard" style="padding-top: 10px;">

```
                     Strong
Sfb:                 0.990%
Dsfb:                6.236%
Lsb:                 0.293% 

Inrolls:            24.089%
Outrolls:           23.922%
Total Rolls:        48.010%
Onehands:            1.503%

Alternates:         30.963%
Alternates (sfs):    7.270%  
Total Alternates:   38.233%

Redirects:           3.368%
BadRedirects:        0.394%
Total Redirects:     3.763%
```

#### Hand Split

It's important to have a

```
                 Strong     Sturdy    Canary    Gallium    Graphite
Right Hand:      49.43%     55.13%    56.09%    51.50%     51.74%
Left Hand:       50.22%     44.52%    43.56%    48.14%     48.07%
```

These don't sum to 100% due to use of other symbols outside the 30 key layout.

#### QWERTY and Vim

#### Full Statistics

- Extremely Low LSB

- High Rolls

- Low Redirects

- Low SFB

## Weaknesses

#### Left Pinky

relatively higher left pinky usage compared to other layouts


```
                 Strong     Sturdy    Canary    Gallium    Graphite 
Left Pinky:      10.32%      7.53%     4.96%     8.46%      8.35%
```

#### Scissors

```
                          Strong     Sturdy    Canary    Gallium    Graphite
Pinky/Ring Scissors:       0.93%      0.41%     0.38%     0.49%      0.25%
```


## Terminology

- Bigram: A sequence of two keys (not containing space)
- Trigram: A sequence of three keys (not containing space)
- SFB: Same Finger Bigram; a bigram that requires the same finger for both keys
- DSFB: Disjointed Same Finger Bigram; pressing two keys with the same finger, separated by x letters
- LSB: Lateral Stretch Bigram; a bigram typed with adjacent fingers, but requires a lateral stretch
- Redirect: A trigram which changes direction on the same hand (excluding SFBs)
- Roll: A trigram which changes hands once (excluding SFBs)
- Alternate: A trigram which changes hands twice (excluding SFBs)

## Etymology

The name comes from an anagram of the left hand home row, 'NTRSG' -> 'STRNG'. It was either, Strong, String, Strung, or Strang, so Strong seemed like the best choice!

## Sources

A great deal of inspiration came from these sources, and I highly recommend checking them out:

- [Sturdy](https://oxey.dev/sturdy/index.html)
- [Canary](https://github.com/Apsu/Canary)
- [Gallium](https://github.com/GalileoBlues/Gallium)
- [Graphite](https://github.com/rdavison/graphite-layout)
- [Keyboard Doc](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit#heading=h.rnpdk4wy8guw)
- [Oxeylyzer](https://github.com/O-X-E-Y/oxeylyzer)

## Contact

You can open an issue, and I will respond as soon as possible, or send an email to:

- Github Email: [108765079+andrew-drogalis@users.noreply.github.com](mailto:108765079+andrew-drogalis@users.noreply.github.com)
