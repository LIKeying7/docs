---
layout: relation
title: 'ccomp:cleft'
shortdef: 'clefted clausal complement'
udver: '2'
---

FrenchSpoken uses the `ccomp:cleft` relation in cleft sentences when the clefted element is not a nominal subject or object . 
Else the appropriate relation is [acl:cleft]().

~~~ sdparse
Juliette n'est pas ma confidente. C' est à Camille que je raconte tout. \n Juliette isn't my confidante. I tell everything to Camille.
ccomp:cleft(Camille,raconte)
nsubj:expl(Camille,C')
~~~ 

~~~ sdparse
Il y a longtemps que j' habite ici. \n I've lived here for a long time.
ccomp:cleft(longtemps, habite)
nsubj:expl(a,Il)
advmod(a,y)
obj(a,longtemps)
~~~

~~~ sdparse
Nager avec les dauphins ne me fait pas rêver. C' est explorer la forêt tropicale qui m' intéresse. \n Swimming with the dolphins isn't my dream. It's exploring the rainforest that interests me.
ccomp:cleft(explorer, intéresse.)
nsubj:expl(explorer,C')
~~~ 

N.B.: Also see the [specific-syntax](http://universaldependencies.org/fr/overview/specific-syntax.html) page.
