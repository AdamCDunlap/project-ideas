# Anti project


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

The main kind of person using this language is someone who wants to check up on
many different websites all in one place. Right now they have to individually
load up each different site and see if there's anything new, but with a
language to help them they could see everything in one place. With this
language they could just input what they care about and it would show them what
they want to see.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL could be appropriate because it would specify what the user cares about.
Unfortunately, I don't think it would work because websites have so many
different formats that trying to incorporate all of them would be a nightmare.
A standard user would probably want text posts, images, and videos all in the
same place, and to do this a large part of the Internet would need to be
scraped and parsed to get them what they want.

### Why you?
_What excites you about this idea? How did you come up with it?_

Sometimes when I get to my computer after being out a while, I check up on a
bunch of sites. Sometimes when I miss one I miss seeing messages that people
have sent me and get back to them way too late. It would be nice if this were
alleviated somewhat.

### Domain
_Describe the project's domain in five words._

Cross-site updates and checks.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

A user could interact with this language by just writing down what sites they
are interested in. Possibly there could just be a button that appears on
supported sites that a user could click to say "I'm interested in this site!"
This seems like the right way to interact with the domain because actually
saying what sites you are interested in is a very small part of your time so it
doesn't matter too much.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The programs will run in the background making checks and giving notifications.
All of these different sites can be aggregated to the same place and have some
consistency applied to them so they look good together. Errors could occur if a
site changes its format so it can no longer be parsed.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to add most common sites, and possible but difficult to add
sites that don't have official support, since the user would then have to write
the parser for that site. It should be impossible to subscribe to sites where
subscribing doesn't make sense, like sites that never change their content.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are some DSLs in this domain, like [RSS](http://www.whatisrss.com/). This
appear to be somewhat widely supported, but I don't know anyone who uses it. It
can do well with some things like blogs, but for other types of content it is
not useful, and the website creator has to specifically support and publish it.

## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Very little of their time would be spent on language design because writing in
the language is the smallest part of the user experience. A ton of time would
be necessary to parse websites and figure out how to get all of their different
types of data and updates together.

### Scope
_How big an idea is this? How ambitious is this project?_

This is a scalable project. Since the language design aspect is so easy and
almost all of the time would be devoted to adding website support, the project
could be toned down or up by just supporting more or fewer websites.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This could be a good idea for a project because it is a pretty good choice for
a language, but it's overall a bad idea because of the amount of work it would
take to support everything. I also don't think it would be very useful because
most people do not have a ton of different things to check, and this would just
become one more thing to look at.
