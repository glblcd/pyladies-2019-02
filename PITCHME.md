## PyLadies Ghana
##### March 2019
![Global Code](GC_Logo_artwork_RGB-LOGO_colour_SMALL.png)

---
## Who's this guy
and what is he doing here?

---

#### I'm Sam Moorhouse 
I ❤️ to teach programming

---

#### I run Global Code
a summer program for software engineers

@snap[north-west]
←
@snapend

---

#### I'm building turntabl
a sustainable startup in Ghana

---?gist=sammoorhouse/23eff05c64b53a6150e69161033aac0e&title=Python&lang=python
@[1] (hello)

@[3] (a = [1, 15, 94, 13, 12, 11, 5, 22, 65])
@[4] (b = 6)
@[5] 5

@[7] (goodbye)
@[]

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
@[]

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
@[]

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

AAAAAARGH!

---

So how do we manage complexity?
* Repeated code
* Lots of loops & branches
* I've run out of variable names :)

---?gist=sammoorhouse/54ec0e75e2e976e5c4c934b7f8bab52d&title=Managing Complexity&lang=python
@[6-13](Lots of repeated code)
@[]

---?gist=sammoorhouse/dbb29fa1bb54c63328f1ba47229724fe&title=Managing Complexity&lang=python
@[6-8](I can just define a function)
@[10-12](...and call it when I need to)
@[]

---?gist=sammoorhouse/ac2eb546db335ffb1121f605d024e44d&title=Managing Complexity&lang=python
@[9](easier to make changes)
@[]

---

If a function grows really big and complicated

* just create a new one
* they're free!

Use functions for repeated tasks

---?gist=sammoorhouse/a5ac4b5cfafa150c3f3e935a11cdf10e&title=exercise&lang=python
@[1-7] Python Dictionary
@[]

---

Use alternative syntax - more "pythonic"

---?gist=sammoorhouse/d151cafd9289d8223205cd064fa76008&title=List Comprehension&lang=python

@[10](get the data out)
@[11](filter the data)
@[9](what do we want to end up with?)

---

# Thanks 👋

@fa[twitter twitter-blue] @sammoorhouse

@fa[twitter twitter-blue] @glblcd
