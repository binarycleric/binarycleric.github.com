---
layout: post
title: "Identifying Weakness"
date: 2013-01-01 14:50
comments: true
categories: 
---

Recognizing, managing, and improving on weaknesses is a core skill that any
developer should possess (or human being for that matter). Far too many times
developers take themselves down the wrong path simply because they don't realize
there is a better tool for the job. I'm not just talking about operating
systems, programming languages, databases, libraries either. I'm talking about
everything from architectures, algorithms, prior art, to all the other items
mentioned previously. What is boils down to is:

**You should know when you don't know something.**

Being able to identify that your approach is suboptimal and that a better tool
must exist is the first step in the right direction. For example, when working
with a previous codebase (won't name names to protect the innocent) a found a
200+ line class full of complex (stdlib and homegrown) string manipulation code.
It was a huge, disgusting, untested mess that ultimate could have been replaced
by a regular expression of fairly medium complexity.

After discovering the original author of this class I asked them why they chose
this method instead of a regular expression. This individual's answer left a
sour taste in my mouth.

_What's a regular expression?_

This wasn't a recent graduate either, this was a developer with a few years
experience who had worked on some pretty intricate systems. Instead of getting
upset or attacking this developer's work, I sat down with them, walked them
through the basics of regex and helped them to identify their weakness and in
end we both ended up better for the experience. 

Identifying weakness can be difficult, especially when we don't even realize
they exist. It's not exactly a skill that can be applied at a moment's notice,
it's more of a pattern that can be recognized. There's no specific training for
learning these patterns but there are things you can do to help yourself along. 

### Get outside your comfort zone

Spend some time experimenting and make sure this is slightly outside your
comfort zone. Are you a Ruby developer by day? Hack on some C. Do you spend your
days as a Java developer? Teach yourself Closure. Don't like programming outside
of work? Build robots.

Try new things and try to see the world from a different prospective. Techniques
gained by learning a new skill can sometimes be applied to your existing
skillet. Learning Assembly made me a better programmer, learning Chemistry made
me a better cook, learning Physics made me a better driver. Learning new things
give me a clearer perspective on existing skills and helped me to identify
better solutions to problems. 
 
### Local Community

Get involved in the local tech (professional and hobbyist) tech community.
You'll get to meet your peers, discuss past and present projects and problems,
and share from the combined pool of experience. 

I highly recommend joining a user group for a technology you don't understand.
In 2010 I started attending Pittsburgh Ruby Brigade meetings despite not knowing
Ruby. Doing so was one of the best decisions I made in my career, as it
introduced me to lots of amazing people, helped me get over my fear of learning
new programming languages, and helped me to become a significantly stronger
programmer.

It will feel overwhelming at first and no you won't understand everything, but
if you walk out of that experience knowing something you didn't know when you
walked in then it was worthwhile. That knowledge will begin to add up and
eventually you'll begin assisting other newcomers who were in the same position
as you.

### Online Community

Not everyone can spend their days keeping up with mailing lists, but glancing at
a few Stack Exchange sites regularity can do wonders. I personally keep
[Programmers](http://programmers.stackexchange.com) and
[StackOverflow](http://stackoverflow.com) in my bookmarks bar. It's not always
perfect but I've learned enough to make it worthwhile.

I try to spend 30 minutes or so a week reading about (semi-complex) problems
others are having, even if they have nothing to do with my projects. Sometimes
it's a waste of time but a lot of times I end up walking away with valuable
knowledge that may help me or a fellow developer down the line. 

### Research Failure

Learning about failure is just as important. While amusing [The Daily
WTF](http://thedailywtf.com) has been invaluable to me over the years. Reading
about failures and anti-patterns in the tech industry has taught me to
recognize warning signs for when a project is headed down the wrong path. 

Remember: _A facepalm a day keeps the failwhale away_.

