# Free project 2

MarkTeX?? : Simple and possible to use in a WYSIWYG editor like Markdown,
but targeted at LaTeX's domain.

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.



### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

LaTeX is way too complicated. And moreover, all the WYSIWYG attempts suck.
What we need is a language that is as simple as possible but can still accomplish
similar tasks.
Moreover, we need a language with separated concerns. I don't want to use the same language 
or process to construct my document that I use to make a new character glyph or do
calculations.
I don't even want to describe the specifics of styles in the same way.

The ultimate goal would be a very user-friendly, minimalistic, and WYSIWYG experience
when building documents.  It would also be much more feasible than LaTeX for note-taking purposes.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

This area is already dominated by DSLs, and users are used to them.
They also closely mimic the output product.


### Why you?
_What excites you about this idea? How did you come up with it?_

Despite being a programmer, I love intuitive and easy to use GUIs.
Furthermore, although I use LaTeX a lot and am very happy with the results,
I think LaTeX is wildly less useable than it could be.
I already made a preprocessor to generate parts of my LaTeX using Python,
because it's so much easier and more expressive.
Finally, I don't have any note-taking formats I like.
Thus, I would be doing this specifically so that I could use it!


### Domain
_Describe the project's domain in five words._

Creating static documents and notes.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

Ideally, the user would eventually work with a fast semi-WYSIWYG editor.
Until then, it would look mostly like extended Markdown.
These are already things that users are familiar with.


### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The language uses a minimalistic syntax similar to Markdown, but with the
ultimate 


### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be extremely easy to write documents that look nice from absolute scratch.
Not even templates.

It should, given an editor, be nearly impossible to create syntactically invalid programs,
and when it is invalid it should be limited in scope.

There should be a separation of concerns, so that it is difficult to do calculations in
the document syntax. A different method - perhaps an embedded interface with a general purpose language -
would be used for more complicated things like that.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Yes, many. [Markdown](https://daringfireball.net/projects/markdown/) and [LaTeX](https://www.latex-project.org/)  are the biggest examples.
They've been discussed.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I think getting nice-looking output would be a lot of non-language work.
But a proof of concept would be almost entirely language and design work, because
it would essentially be trying to redesign LaTeX as minimalistically as possible.

### Scope
_How big an idea is this? How ambitious is this project?_

This is a pretty ambitious project for it to be usable, but a proof of concept that
has bad graphics could be manageable. It would probably produce HTML like Markdown does.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is a good idea for a project because most of the work (for a proof-of-concept)
would be on the language itself. This is a bad idea for a project because it could
easily get out of hand and too large in scope.

