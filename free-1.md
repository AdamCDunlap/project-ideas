# Free project 1

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

My idea helps people who are writing game rules to ensure that they are
well-written without loopholes. Currently, game makers have to think hard about
edge cases and not just try to figure out what they are, but how they should be
handled so that they are most consistent with the rest of the rules. If they
used a DSL stemming from my idea, they could be notified about what cases are
left undecided, and the language could automatically help output their rules in
clear English.


### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is appropriate because the game maker can write their rules in the
language which will be optimized for rule writing. Writing rules in the
language will make rule-writing clearer because the syntax will be more
optimized for rules than English is. Then the system can automatically check
their rules for consistency and loopholes.

### Why you?
_What excites you about this idea? How did you come up with it?_

Often when I'm playing games I notice things that either don't really have a
rule applied to them or the rule that does govern how something works doesn't
make sense with the larger theme.

### Domain
_Describe the project's domain in five words._

Building and verifying game rules.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

The language will mostly be a text-based interface which is similar to a
standard programming language. The user can define different types of game
objects and how they interact. Programming is basically defining these game
objects in one section and in another section explaining how different classes
work together. There can be different layers of objects (so for a card game,
the ace of hearts can be part of the hearts class and the aces class) and rules
apply to each one.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The main non-syntax error would be that there is some case that the game
designer missed. These could just be printed out when the program is run.
If the language is accepted, rules printed in English will be output, and these
rules are guaranteed to be unambiguous.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to define most games. Simple turn-based card and board games
will obviously be easier than a complex real-time strategy online game, but it
should be possible to express both. I can't think of anything in the domain
that should be really impossible --- ideally, the system is flexible enough to
define most rule sets.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I was somewhat inspired by [Ari's CS111 project from
2014](https://github.com/AriHC/RuleBook), but our ideas are different in that
his scope was more limited to tic-tac-toe-like games and automatically made a
playable computer game, while mine will accept more general games and only
output rules. I also found some other cool game generators like
[PuzzleScript](http://www.puzzlescript.net/editor.html). But what makes my
project different is that it can specify arbitrary games, and trades this
flexibility for the lack of actually implementing them.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I would guess that quite a bit of time would go into figuring out exactly how
the user should interact with the language. This language would be some
combination of formal logic, general-purpose programming language, and English.
It needs to be easy to use but also extremely general --- it would be bad if a
game _almost_ fits in the language because then the language becomes useless.
Programming the interpreter for the language would also be difficult but
probably not as bad. If the language is closer to formal logic, some basic
translation could happen and then be fed into a logic prover. Outputting game
rules would be complex if one wanted them to look good but simple to get
something basic done.

### Scope
_How big an idea is this? How ambitious is this project?_

This seems like a fairy ambitious project. Both the design and implementation
sound pretty difficult and I'm still not sure if things would even work.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is a good idea for a project because it's clearly a place where a DSL is
good and could be used for a wide variety of games. Its disadvantages are that
it's probably not the most useful --- any text that it outputs would probably
be awkward enough that a game designer would reword it, and that could easily
reintroduce the very "bugs" that the system is designed to remove.

