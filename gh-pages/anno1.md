---
layout: entry
title: prueba de renderización de anotaciones
---
Sacado de [aquí](https://spyysalo.github.io/annodoc/).

The .ann standoff (Ann) format:

~~~ ann
Barack Obama is the current president.
T1 PERSON 0 12 Barack Obama
~~~

A single tree in the Stanford Dependency format:

~~~ sdparse
Dogs run
nsubj(run, Dogs)
~~~

Parses represented in the CoNLL-X format can be embedded as illustrated by the following example:

~~~ conllx
1    Dogs   dog    _    NNS    _    2    nsubj
2    run    run    _    VBP    _    0    ROOT
~~~

Finally, parses in the CoNLL-U format can be embedded as shown below:

~~~ conllu
1    They    they    PRON    PRN    Case=Nom|Num=Plur            2    nsubj    _    _
2    buy     buy     VERB    VBP    Num=Plur|Per=3|Tense=Pres    0    root     _    _
3    books   book    NOUN    NNS    Num=Plur                     2    dobj     _    _
~~~
