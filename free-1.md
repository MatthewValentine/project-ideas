# Free project 1

LegalEase: A means of adding metadata to legal documents, creating a network that can support
()hopefully) powerful and useful queries.

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

Legal writing is both notoriously complex and requires a lot of context to interpret.
The users of the language would probably be lawyers, judges, lawmakers or reporters who wanted
to dig into the context, history and use of various laws, definitions, rulings and interpretations.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

Laws, rulings, etc. already need to be documented, and need to be accessed in a document form.
A DSL is appropriate in that it can also supersede that use case, because it contains both
the document form and metadata that is eminently useful for people browsing and researching
the documents.  Additionally, it is helpful in that it could require a minimum of modification
from the original documents to become syntactically valid (if not semantically useful).


### Why you?
_What excites you about this idea? How did you come up with it?_

I came up with the project because I thought of the name "LegalEase", which has of course
been invented a million times already.  It's exciting because I imagine that legal information
comprises a hideously large amount of information, and it really needs a sensible means of
managing that information via computer. (Not interpreting: law isn't black and white. 
Just connections.)
Especially if it could eventually be brought to the
point of making it easier for laypeople to understand, or even point out loopholes and such.
That's massively beyond the scope, but first there needs to be a standardized, fairly easy,
not-going-to-be-buggy O(n) way to put the information into a format that the computer can
manage.

### Domain
_Describe the project's domain in five words._

Organizing and connecting legal documentation.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

A user would most likely interact with the language by using a GUI interface,
because they are not going to be programmers-at-heart.
However, the basic level would just be adding specific kinds of metadata,
probably in a format similar to XML.

The idea is that the original documents would already be valid, but more information
can be added in a specific way over time to produce a more useful network of information.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

There would be many ways to run a program, more along the lines of queries.
You can take a particular ruling, and then it would be able to take you through
the chain of interpretations of specific laws that the ruling uses.
You can take terms, and see how they are defined in this context, but then also
how they are defined in a different context, and perhaps look for definition problems that way.
You can look at the different interpretations this law a related ones have had.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to add new information to a document, and to do fairly sophisticated queries
and workflows using that information.

The language is declarative. It should not be Turing complete.
It should also not be possible to ask the computer to give a ruling.
Not because that's beyond the scope, although it is by far,
but because that should never be allowed.
It should only be able to assist a human.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There is the [Open Law Initiative](http://open.innovatesf.com/openlaw/), which makes the text and general organization available
online. The expectation is that people will start to figure out useful things they can
do with that data, such as what I'm suggesting.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

It seems to me that the split would probably be 50-50.
It may be that the language is actually very straightforward, and just difficult to implement.
However, I believe that would not be the case. The language needs to be O(n) effort, meaning that
adding the info for a new law or ruling should not increase in work as the overall size of the
database increases. It also needs to be both easy enough to use, not mired in a programmer's
perspective, and still powerful enough to be useful.
I think the language would require a lot of work.



### Scope
_How big an idea is this? How ambitious is this project?_

The issue with this project is that finding out 
"This just basically not theoretically possible if you want it to be satisfyingly powerful at all"
is a reasonable possibility. This project could basically turn out to either be manageable
or way, way too ambitious. It's hard to say.


### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

It's a good idea because it would be useful, and that is the primary reason.
It is a bad idea because it requires looking at legal documents!
Additionally, there's a high chance that the only truly feasible manifestation of the
language would just be trivial.

