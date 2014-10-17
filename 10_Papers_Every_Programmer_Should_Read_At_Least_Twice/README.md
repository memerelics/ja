[10 Papers Every Programmer Should Read (At Least Twice)](http://web.archive.org/web/20121024173845/http://blog.objectmentor.com/articles/2009/02/26/10-papers-every-programmer-should-read-at-least-twice)

------------------------------------

I spent most of yesterday afternoon working on a paper I’m co-writing. It was one of those days when the writing came easy. I was moving from topic to topic, but then I realized that I was reaching too far backward – I was explaining things which I shouldn’t have had to explain to the audience I was trying to reach.

When I first started writing, one of the pieces of advice that I heard was that you should always imagine that you are writing to a particular person. It gets your juices going – you’re automatically in an explanatory state of mind and you know what you can expect from your audience. I was doing that, but I noticed that I was drifting. I was losing my sense of audience. I started to explain one thing, and then I realized that I would have to explain something else to help it make sense. I couldn’t imagine that person any more. How could I know what they know and what they don’t?

The problem I was experiencing is only getting worse. People come into programming from many different directions. Some started in other fields, and others started programming as teens. Some started with BASIC, others started with Ruby or C. The industry is filled with knowledge, but it isn’t common knowledge. It isn’t knowledge that we all share. We have to dig for it because of a peculiar fact about our industry: we reinvent our languages and notations every ten years. It’s hard to find deeply technical books and articles which stand the test of time in software: they are all Latin within 20 years.

So, I was thinking about this and trying to not to get too glum. I realized that instead of complaining, I could help by pointing to some papers which are easily available online and which (to me at least) point to some of the most interesting ideas about software. To me, these are classic papers which contain deep “things you oughta know” about code – the material you work with.

We’ve taken an interesting turn in the industry over the past ten years. We’ve come to value experiential learning much more, and we’ve regained a strong pragmatic focus, but I think it would be a shame if we lost sight of some of the deeper things which people have learned over the past 50 years. Rediscovering them would be painful, and (to me) not knowing them would be a shame.

Here’s the original list. It’s a rather personal list of foundational papers and papers with deep ideas. I wrote it “off the cuff” and threw it into a tumblr blog the other day and I got responses from people who suggested others. I’ll add those in a later blog.
Most are easy to read but some are rough going – they drop off into math after the first few pages. Take the math to tolerance and then move on. The ideas are the important thing.


1. [On the criteria to be used in decomposing systems into modules](http://web.archive.org/web/20121024173845/http://sunnyday.mit.edu/16.355/parnas-criteria.html) -- David Parnas
2. [A Note On Distributed Computing](http://web.archive.org/web/20121024173845/http://research.sun.com/techrep/1994/abstract-29.html) -- Jim Waldo, Geoff Wyant, Ann Wollrath, Sam Kendall
3. [The Next 700 Programming Languages](http://web.archive.org/web/20121024173845/http://portal.acm.org/citation.cfm?id=365257) -- P. J. Landin
4. [Can Programming Be Liberated from the von Neumann Style?](http://web.archive.org/web/20121024173845/http://portal.acm.org/citation.cfm?id=359579) -- John Backus
5. [Reflections on Trusting Trust](http://web.archive.org/web/20121024173845/http://cm.bell-labs.com/who/ken/trust.html) -- Ken Thompson
6. [Lisp: Good News, Bad News, How to Win Big](http://web.archive.org/web/20121024173845/http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.50.6083) -- Richard Gabriel
7. [An experimental evaluation of the assumption of independence in multiversion programming](http://web.archive.org/web/20121024173845/http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.29.363) -- John Knight and Nancy Leveson
8. [Arguments and Results](http://web.archive.org/web/20121024173845/http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.50.7565) -- James Noble
9. [A Laboratory For Teaching Object-Oriented Thinking](http://web.archive.org/web/20121024173845/http://c2.com/doc/oopsla89/paper.html) -- Kent Beck, Ward Cunningham
10. [Programming as an Experience: the inspiration for Self](http://web.archive.org/web/20121024173845/http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.31.562) -- David Ungar, Randall B. Smith

(edit: Added a brief synopsis of each of them and why I think they are special):

**On the criteria to be used in decomposing systems into modules – Parnas**

This is a very old paper, but it is more than a classic. In in it, Parnas introduces a forerunner to the Single Responsibility Principle. He introduces the idea that we should use modularity to hide design decisions – things which could change. People still don’t consider this as often as they should.

Another thing I really like in the paper is his comment on the KWIC system which he used as an example. He mentioned that it would take a good programmer a week or two to code. Today, it would take practically no time at all. Thumbs up for improved skills and better tools. We have made progress.



**A Note On Distributed Computing – Waldo, Wyant, Wollrath, Kendall**

Abstraction is great but it can only go so far. In this paper, the authors lay to rest what was once a pervasive myth – that we could design a distributed system and make distribution transparent. Ever wonder why you had to implement specific interfaces to do remoting in Java? This is why.

In the aftermath it might seem hard to believe that people thought this was possible. I think we can we partially thank this paper for that.


**The Next 700 Programming Languages – Landin**

Most of us have spent a lot of time working in traditional programming languages, but functional programming languages are slowly seeing an uptick and many OO languages are gaining functional features. This paper (which reads like a tutorial) makes an argument for an expression-oriented style of programming. It also lays the foundation for lazy evaluation.

One of the other neat things about this paper, from a historical point of view, is that there is a discussion section at the end in which there a number of questions and comments about whether making indentation significant in a language is a good idea. I was thrown to see people asking whether or not this would be a problem for functions which span over several pages(!).


**Can Programming Be Liberated from the von Neumann Style? – Backus**

John Backus is known for a number of achievements in computer science. He received the ACM Turing Award for his work on Fortran. This paper, which he presented at the award ceremony was rather shocking at the time because it said, in essence, “we got it wrong.” Backus took the opportunity to make a plea for pure functional programming. His arguments were convincing and they helped to set a research agenda which is just now starting to make some waves in the mainstream.


**Reflections on Trusting Trust – Thompson**

I once heard that when this paper was presented, people in attendance rushed back to de-compile their C compilers and look for, er, problems. This paper unveiled a hard problem at the heart of computer security. If you’ve spent any time at all thinking about security, you need to read it.


**Lisp: Good News, Bad News, How to Win Big – Gabriel**

This paper is a bit atypical in this list. It’s aimed at the Lisp community and it comes off as a bit of a lament. But, hidden deep within it is the Gabriel’s description of the ‘Worse is Better’ philosophy – an idea with profound implications for the acceptance and spread of technology.


**An experimental evaluation of the assumption of independence in multiversion programming – John Knight and Nancy Leveson**

Behind this dry title lies something very interesting. I first heard about this paper from Ralph Johnson in a newsgroup discussion about program correctness. It turns out that one of the avenues that engineers in other disciplines take to make their products stronger -- redundancy -- doesn’t really work in software. Multi-version programming was the idea that you could decrease faults in critical systems by handing the spec to several teams, having them develop the software independently, and then having the systems run in parallel. A monitoring process verifies their results and if there is any discrepancy it picks the most common result. Sounds like it should work, right? Well..


**Arguments and Results – Noble**

I think that all of the other papers in this list are rather well known in some circles. This one isn’t, or if it is, I just haven’t found that circle yet. What I like about this paper is that it takes something which we deal with every day – the set of arguments and results of functions – and it works them through a series of variations which just don’t occur to many people. The fact is, every function that you work with has a number of possible directions if could evolve in. Not all of them are appropriate, but if you know the possible directions, you’re richer for it.


**A Laboratory For Teaching Object-Oriented Thinking – Beck, Cunningham**

There are an incredible number of papers about there about object orientation. The thing which makes this one great is its directness. OO went through a number of stages. It was once fresh and novel, then it was ornate, and then it became matter-of-fact. This paper hits upon key ideas which many people don’t talk about much any more: anthropomorphism and dropping the top/down perspective. It also shows you how you can design with index cards. It may not sound cool but it is incredibly effective.


**Programming as an Experience: the inspiration for Self – Ungar, Smith**

How many people know about the Self Project? Not enough in my opinion. Self was an attempt to take two ideas in computing and push them as far as humanly possible. The first was minimalism: the Self programming language was thoroughly in the Lisp and Smalltalk vein – everything was defined in terms of the smallest number of primitives possible. The other idea was direct manipulation -- the idea that the object metaphor could be pushed all the way in the user interface -- the programmer and user sit with a mouse in a sea of directly clickable objects and use them for everything. If they could’ve gotten away with dropping the keyboard, I think they would’ve.

The amount of technology which the Self project threw off is terrifying also. Self broke ground in dynamic language optimization and VM design. Chances are, your VM uses technology it pioneered. It’s also one of the more perverse ironies that the most widely distributed programming language today (JavaScript) is a prototype-based programming language which borrowed ideas from the hyper-research-y Self.

What would you add to the list?
