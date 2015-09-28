# Anti project



## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.



### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

The question is, how should users make traditional sketches
on a computer, as similarly as possible to how they do in real life?
We could suppose that the result should be in a vector graphic format. 
For context, I will strongly take the stance that something like a Wacom tablet is not a DSL.

This helps artists in the digital age. It might be that an artist would be somehow able to
describe their desired artwork, and it would be created.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is not appropriate for the users in the following sense. Consider a DSL that solves this
problem. To some extent, it removes the direct interaction that an artist traditionally has
with their work. There are many styles that benefit from that, but we are specifically considering
those that don't.
Any DSL that solves this problem could be made a little better by making it a little less like
a DSL. The ideal situation would be something where the user drew normally on (perhaps special) paper,
and the result was recorded. We want to preserve almost all of the interactions the user has
as they already are.

### Why you?
_What excites you about this idea? How did you come up with it?_

I tried to think about something which was actually worse with computers.

### Domain
_Describe the project's domain in five words._

Creating digital versions of sketches.


### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

They might use coordinates, which would be awful.
They might have a GUI editor, where they create shapes and manipulate them and such.
That creates wonderful art, but loses the kinds of interactions the artist has that we're trying to 
preserve. They might even do some strange machine-learning on their art style and then describe what
they wanted to draw, which would be incredibly weird but interesting.


### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The user would probably interact with the program as it ran, although not necessarily.
The final result would be a vector-graphics image similar to a sketch the artist would be able
to produce on paper.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to do sketches, with such interactions as realistic erasing.
It should be impossible to do much of anything that isn't art-related.


### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are lots of DSLs in similar domains, such as (MS Paint.)[https://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/mspaint_overview.mspx?mfr=true]
They typically embrace the idea of computer-like art. Using a Wacom tablet to control such a
program would be a DSL, but actually using the Wacom tablet to directly draw starts to become
"not a DSL." Unfortunately, this question is impossible to answer without drawing some lines.
(ha ha ha, get it, *drawing some lines.*)


## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Unless the graphics work was somehow outsourced to a different program,
then almost all of the work would be systems. Some of those systems would even be hardware.


### Scope
_How big an idea is this? How ambitious is this project?_

It would be immensely ambitious.


### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

It is not a good idea for a project, because the less language work there was,
the better the project would be.

