# No computer project


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

The need is for people who want to restrict access to something. Before locks
were invented, people would have to either trust that people won't access the
thing they want to protect, hire someone to watch over it, or hide it. Since
locks, people can be secure in that others will not enter where they should not
go or steal their belongings.


### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

Users want to be able to enter a short program that only they know (a
combination) that will cause the language to grant access, and deny access to
everyone else. People can easily restrict access to the knowledge of this
program so that only the ones they trust know it, and the language of a lock
keeps everyone else out.

### Why you?
_What excites you about this idea? How did you come up with it?_

Locks are cool because each one is like its own language. Combinations and keys
are programs, and these programs have similar structure, but each lock accepts
a different program. There can also be some languages that accept multiple
programs, such as a "standard" and "master" key.

### Domain
_Describe the project's domain in five words._

Restrict access based on knowledge.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

A user will interact with the language by first acquiring a program that the
language accepts and then simply feeding the program to the language. The
language will only accept very few programs so ideally only trusted people can
get in. This is the right way because the programs are short enough to remember
but long enough that finding the right program is hard. Also, if you want to
access whatever is being restricted, you are usually right there and can enter
the program.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When a program runs, either access is granted or it is not. The program signals
this to the user by simply not turning or opening. An error could occur if the
lock jams which is a pretty catastrophic failure.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be very easy to enter a program because that needs to be done
regularly. It should be possible but difficult to change what programs the
language accepts, ideally requiring a previously working program to do so. And
it should be extremely difficult to generate a working program without having
it at the start.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are other similar DSLs in non-physical locks, such as phone locks. These
generally also require a combination and act in much the same ways, but they
are digital instead of physical.

More in the same domain as locks are things like nailing a door shut. This
works well to keep out many people, but since it is just as easy for an
unauthorized person to get in as the authorized person, it is less useful than
locks.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

The language design section would probably take some work because the programs
have to be easy to make at the time the language but difficult later. The
programs also have to easily accept the programs without jamming much. On the
other hand, a lot of time would have to go into actually fabricating the locks.
They have to be well-made because people will be trying to break them, and
making things out of metal is generally difficult.

### Scope
_How big an idea is this? How ambitious is this project?_

This project is not too ambitious, at least in the scope of metalworking.
Making anything complex out of metal is pretty difficult, but if one were
proficient a lock is not much harder than many other things. It's hard to say
how hard coming up with a design is because locks are so prevalent that
everyone already knows some pretty good designs for them.


### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This would be a good idea because locks are extremely useful and the design of
them is not too complex. It's not such a good idea because I'm better at
programming than metalworking.
