# Free project 2


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

The need met is people who want to figure out what they need to do at any
moment and what they can do if they are feeling productive. Currently, there is
some combination of calendar where events can be manually put, potentially todo
lists, some of which have different types of deadlines which are all mixed
together. If this language works out, people can have all of their TODO-like
things all in one place: things such as mandatory meetings presented one way,
optional events in another, and hard a soft deadlines that come with some
weighting so the user knows how important they are.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A language is appropriate because the user can write a program that is all of
their activities. This consolidates all of the relevant information and then
the program can be executed to tell the user about things they need to do.

### Why you?
_What excites you about this idea? How did you come up with it?_

I'm really excited by this project because scheduling well sounds like
something that should be easy but I still have trouble finding something that
doesn't require me to remember and plan ahead enough. I thought of this idea
after reading [Michaels' previous project](https://github.com/mculhane/dPete).
I have avoided reading it in depth to not pollute my ideas, but the idea
resonances we me a lot.

### Domain
_Describe the project's domain in five words._

Person-oriented task management system.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

There will have to be several different ways to interact with the language for
it to be feasible. There has to be easy ways to add events from emails. When an
email comes in that says there's an interesting-sounding talk on a certain day,
it should be very easy to put this in, and change settings like how much you
want to go to it. There should be some similar interface with TODOs, even for
things such as "deal with this email." Setting up events outside of email
should also be easy, and it's important to have a nice interface for recurring
events.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_


Once events and TODOs are in, getting the information out should also be easy.
Ideally, there will be some levels of reminders that go from "this is what you
should take care of today" to "you have to start this assignment now or else
you'll skip the talk you really want to go to later."

I feel this is the right way because it's how my brain works. When I see a new
thing I have to do, I only think of it for so long before it leaves my mind so
I want to get it down as soon as possible. I also am often asking "Do I have
enough free time to play a few games?" or "I'm feeling productive, what do I
need to do now?" This system could solve both.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to add both events with defined starting and ending points
and tasks that have to get done and have an approximate length but no specified
time frame. Having some other type of event might be possible but difficult,
although I don't know of anything else necessary. Nothing in the domain should
really be impossible since the language should be generic enough to support
basically any tasks.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are lots of other DSLs in this domain. Google Inbox, for example, tries
to combine email and todos, but doesn't have great support for mandatory
events. I got the idea of importing from email from Google as well, but their
system doesn't work as well as I hoped.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

A lot of the time would be spent on figuring out good ways to interact with the
user. Keeping track of events is pretty easy and notifications can be anywhere
from easy to pretty difficult. However, the user interaction can also be pretty
incremental: adding support for manual input would be one level, gmail input
would be harder, and other methods of input and output could get trickier.

### Scope
_How big an idea is this? How ambitious is this project?_

This is potentially a big project depending on how many different devices and
platforms it supports, but could pretty easily be toned down to something
reasonable. If it does get big and is done well, it could be very useful and I
could definitely see myself using it.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is a good idea for a project because it is very language-y and useful.
There are some drawbacks in that supporting enough different methods of input
and output could be technically difficult, but that is all part of the language
design.
