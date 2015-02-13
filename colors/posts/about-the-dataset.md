---
title: "About the Dataset"
author: "Vishesh Gupta"
tags: ["colors"]
summary: "Check out this data set of color values taken from an author's color thesarus. The main takeaways - how do you group colors? How do you determine if there are missing/superfluous colors in the data set?"
created: "2015 February 12 00:48:22"
---

## About the Dataset

The story begins with Ingrid Sundberg, an author that came up with a color thesaurus.
Color is an important thing to use in any kind of visual design, and a lot of interfaces need easy access to more colors than just red blue green etc.

So someone made a [github project][githubcolors] and gave all these colors hex values and provided them free to use for everyone.

However, the grouping really bothered me. Let's consider the categories; we have (in order):

<div style="margin: 0 auto; width:90%; height: 40px; display:flex; justify-content:space-around; text-align:center; vertical-align: center;">
  <span style="flex:1; background-color: #fffefc;">White</span>
  <span style="flex:1; background-color: #0074d9;">Blue</span>
  <span style="flex:1; background-color: #e5dbac;">Tan</span>
  <span style="flex:1; background-color: #ffdc00;">Yellow</span>
  <span style="flex:1; background-color: #ff851b;">Orange</span>
  <span style="flex:1; background-color: #ff4136;">Red</span>
  <span style="flex:1; background-color: #f69acd;">Pink</span>
  <span style="flex:1; background-color: #b10dc9;">Purple</span>
  <span style="flex:1; background-color: #2ecc40;">Green</span>
  <span style="flex:1; background-color: #241709; color: #e5dbac;">Brown</span>
  <span style="flex:1; background-color: #aaaaaa;">Grey</span>
  <span style="flex:1; background-color: #111111; color: #aaaaaa">Black</span>
</div>

So there are 4 "neutral" categories - white, black, tan and grey. The rest are colors of some form or another (I guess brown is on the fence, but I'm calling it a color). Of the remaning 8 categories, 6 are warm colors, and 2 are cold colors, which seems a little imbalanced. On top of that, the categories themselves are a little too simplistic. Each contains about 18-21 colors, but I'm not convinced all of them are really in the right location. For example, <span style="background-color:#757b87; padding: 0.25em 2px; text-align: center;"> slate </span> is put in the blue category, but I'm pretty sure it should go in the grey category. Pink and Purple aren't really categories in their own right - something like <span style="background-color:#fc4c4e; padding: 0.25em 2px; text-align: center;"> strawberry </span> really belongs in the red category, not the pink category, and <span style="background-color:#290916; color: white; padding: 0.25em 2px; text-align: center;"> raisin </span> really should go in the brown or black category.

So the two problems boil down to:

* Bad groupings of the already present colors
* Imbalanced coverage of the color spectrum (few cold colors, lots of hot colors).

My mission, should I accept it (and I did) is to make new groupings and fix the color imbalance - we need more greens and blues in this house.

[githubcolors]: http://dudleystorey.github.io/thenewdefaults/