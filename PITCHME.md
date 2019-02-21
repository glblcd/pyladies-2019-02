@title[PyLadies Ghana: Control Flow]

## PyLadies Ghana
##### March 2019
![Global Code](GC_Logo_artwork_RGB-LOGO_colour_SMALL.png)

---
## Intro
* I'm Sam Moorhouse (@sammoorhouse)
* I teach programming for a living
* I run Global Code (@glblcd), a summer program for software engineers
* I'm also building turntabl (@turntablio), a sustainable startup in Ghana

---?gist=sammoorhouse/23eff05c64b53a6150e69161033aac0e&title=Python&lang=python
@[1] (hello)

@[3] (a = [1, 15, 94, 13, 12, 11, 5, 22, 65])
@[4] (b = 6)
@[5] 5

@[7] (goodbye)

---

@snap[east span-50]
Rule 1: Code is executed *Top Down*
@snapend

@snap[west span-40]
![Top-down](down-arrow.png)
@snapend

@snap[south]
Just like reading a poem
@snapend

---?gist=sammoorhouse/fcec9fbd0e688d7fde2c347da26f573e&title=Python&lang=python
@[1] (hello)

@[3] (a = [1, 15, 94, 13, 12, 11, 5, 22, 65])
@[4] (b = 6)
@[5] (is 6 > 3 ?)
@[6] (sure it is!)

@[10] (goodbye)

---

@snap[east span-50]
Rule 2: A branch means you take one path or the other
@snapend

@snap[west span-40]
![Top-down](branch.png)
@snapend


@snap[south]
Like points on a railway
@snapend

---?gist=sammoorhouse/b762b3a44ff853b0f764b84f2a084688&title=Python&lang=python

@[1] (hello)

@[3] (a = [1, 15, 94, 13, 12, 11, 5, 22, 65])
@[4] (b = 6)

@[6] (n=0)
@[7] (n=0)

@[6] (n=1)
@[7] (n=1)

@[6] (n=2)
@[7] (n=2)

@[6] (n=3)
@[7] (n=3)

@[6] (n=4)
@[7] (n=4)

@[6] (n=5)
@[7] (n=5)

@[6] (n=6)
@[7] (n=6)

@[6] (n=7)
@[7] (n=7)

@[6] (n=8)
@[7] (n=8)

@[9] (goodbye)

---

@snap[east span-50]
Rule 3: A loop means you go back
@snapend

@snap[west span-40]
![Top-down](loop.png)
@snapend

@snap[south]
Based on a condition
@snapend

---

@snap[west span-20 lines]
![Top-down](down-arrow.png)
@snapend

@snap[midpoint span-20 lines]
![Branch](branch.png)
@snapend

@snap[east span-20 lines]
![Branch](loop.png)
@snapend

---

@snap[west span-50]
But your code gets complex...
@snapend

@snap[east span-40]
![Mess](mess.png)
@snapend

---

@snap[west span-50]
But your code gets complex...
@snapend

@snap[east span-40]
![Mess](more-mess.png)
@snapend

---

# @size[3.5em](AAAAAARGH!)

---

So how do we manage complexity?

If a function grows really big and complicated, what do we do?

Use functions for repeated tasks

Use alternative syntax - more "pythonic"