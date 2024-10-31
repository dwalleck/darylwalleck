---
title: Why I Fail at Leetcode
description: Useful shortcodes that can be used in Markdown
date: 2024-10-31 00:00:00+0000
---

# Quick Disclaimer

The point of this post is not a knock against LeetCode or companies that LeetCode.
What I'm trying to convey is that everyone's journey to being successful at LeetCode/DSA
problems can look different, even if some of the conclusions reached end up being
standard advice.

# My Confession

I, as a developer with 17 years of experienced, had a meltdown and completely
bombed a LeetCode easy question. So how in the world did I reach that point?

I was laid off almost two months ago, so you can imagine my excitement when a company
reached out and was interested in interviewing me. The first round interview
was scheduled to be behavioral and architecture questions, so naturally I put on
my STAR hat to come up with scenarios to talk about and did a deep dive on
system architecture as I haven't had architecture in many interviews before.
I poured hours into preparing myself because this was also a dream position for
me with a change your life salary. I virtually walked into the interview feeling
like I was ready for anything.

# The Interview

The first portion of the interview went well as it was the standard "explain to me
in detail things you've built". We were about two-thirds of the way done and I was
confident I had things in the bag. Then the interviewer said we needed to switch
gears to the coding part of the interview. I wasn't remotely in the mindset to
do battle with LeetCode, but saying no wasn't really an option. The problem itself
was actually rather simple:

**Given a string `s`, find the first non-repeating character in it and return its index. If it does not exist, return `-1`.**

(If this looks familiar, it's because it is [LeetCode #387](https://leetcode.com/problems/first-unique-character-in-a-string/description/))

There was some extra complexity that the interviewer added, but I don't want to
give that part away in respect to the company. My anxiety had already kicked in
because I struggle with anxiety, but I knew this was something I could handle.
I even said "Well, I could use the Python Counter class....but nah, there's
probably a more efficient way to do this". I had it. I had the answer in my hands.
The interviewer even suggested I try that approach even if it wasn't the most
optimal, but I didn't listen because my brain had hyperfocused on what I thought
the most ideal solution was: the two pointers technique! After talking it out a
bit to myself, I dove into coding a solution.

I was getting very anxious at this point and things went off the rails. Simple
things like forgetting the Python typing syntax, forgetting what variables I
was using. When everything collapsed was when, for some reason, I decided that
if there were characters repeated multiple times in a row, that was a special
case I had to handle. Note that at this point I hadn't run my code a single time.
I had no idea if anything worked. After a few more minutes, the interviewer suggested
running my code to see if anything worked. As I mentioned before, there were a ton
of basic errors that immediately popped up. And then I forgot to print the output
from my function to see what it was returning. We had already run over the time limit
we had scheduled so my interviewer asked me to take my time and send them the
solution as soon as I finished.

After taking five minutes to clear my head, rational thought reactivated in my
brain and I realized how convuleted the solution I was trying to develop was.
I wiped out most of my code, used a Counter (for those who are not Python
developers, a counter is a quick way to create a hash set from a list, where
the key in this case was a character, and the value was the number of occurrances
of the character). I hoped because I was allowed extra time to complete the task
that it meant that the interviewer was confident enough that concerns about
my coding skills could be dealt with in the final round of interviews. Instead,
I received my rejection email several days later with an explanation that
being unprepared for a coding interview was not enough of a justification
for my performance given that it was a staff level position.

# The Fallout

After I closed that email my brain was in a state somewhere between absolute
shock and shame. I just blew a life-changing job because I couldn't code up
a solution for a relatively simple problem. I spent the next day rapidly
repeating the stages of grief. I had to be an awful developer. I was a fraud.
I failed my family. I must have made it this far because of the teams I
worked with. I had been laid off three times in 18 months. Maybe I couldn't
cut it anymore?

# Turning the Corner

Since I was just sitting around and I definitely didn't want to touch a computer,
I took my wife's advice and listened to audiobooks. There was one book in
particular called *Self Compassion* that my wife had been begging me to read
for years. The tag line for the book started with "Stop beating yourself up",
so it seemed like the medicine I needed. I'll save the details of my experiences
with that book for another time, but one of the core concepts I walked away with
was that beyond recognizing a thought or feeling and acknowledging it, anything
more was just causing suffering, which has no good purpose. Something about the
experience snapped my brain back into focus and I knew what I had to do. There
had to be something valuable I could take away from this experience.

# Being Curious

One of my ADHD coach's approaches to dealing with challenges was "to get curious"
about problematic things in our lives. So, as painful as it was, I started walking
through the coding portion of the interview step-by-step in my head. Some of
the obvious observations I made were:

    - I ignored a suggestion my interviewer made
    - I talked through my solution without writing a single thing down
    - I didn't verify my solution at all
    - I waited far too long to run my code

The straightforward conclusion I thought of was that I just wasn't as methodical
as I could be. This was far from my first coding interview, but I thought back
and realized I had never done any of those things in my interviews. Why not?
They sound like common sense. As I started to beat myself up, I took a step back,
forgave myself for not doing those things before, and turned my focus on the "why"
of the whole thing. Out of the blue, all the answers suddenly snapped into
place.

# It's Always ADHD Under the Vilian's Mask

I didn't know I had ADHD until about 8 years ago, so I thought I had already mostly figured
out how to navigate my career by writing everything down so I wouldn't forget things and
asking for help with accountablility for deadlines. Focus was something I previously
managed with caffiene and later used medications to help with. However, I never got
curious if it impacted how I actual coded. As I was reflecting on my coding,
I pulled up one of the lists of how ADHD impacts people's lives for thoughts.
One line jumped out at me: "Limited working memory". This is a fancy way of saying
that someone with ADHD may not be able to keep as many thoughts at the top
of their mind without forgetting something or having the details scrambled.
This is why many people with ADHD cling to note taking or scheduling apps for
their lives; it's just really hard to keep things straight. As a developer, this
is also why I make architecture and flow diagrams and keep a strict list of tasks
in whatever task tracking systems I'm using. I **need** those visual reminders
to stay on track. I flipped back to the "common sense" advice I wrote down earlier
and realized those weren't optional steps in my coding interview process: they're
absolutely necessary. But how I had I made it this far in interviews for all
these years? Memorization. It's the same reason I was a straight A student in
high school and barely drug my way through college. You can easily prep for high
school exams by cramming enough data into your head to get you through the test,
but that doesn't work though college. I realized I spent far more time first trying
to memorize exact LeetCode problems and then trying to memorize the general types of
solutions _that I never paid attention to how I was actually coding the solution_.
I could put together a solution in my mind, but I was relying on my mind,
which was under intense stress and very faliable, to keep all the details of
the solution in order. When I finally put all the pieces together, I laughed at
how obvious the problem was.

# The Solution

I will probably never be a top-tier LeetCode solver, but I can certainly improve
enough to fail because I've reached the limits of my knowledge rather than my
brain giving out on me. What I've tried and has worked so far in the limited
time I've had is the handy old checklist. Note that I'm not saying this should
be everyone's checklist; this is what I hope will work for me, and I hope will
make others curious enough to design their own.

    - Read the problem carefully.
    - Add a comment in your coding window of the problem you're solving in case your mind wanders
    - Pseudo code the solution on paper or in the terminal. This is where I started to go off the rails. This frees your brain of trying to remember your plan.
    - If you have time, draw out how the solution works. Now you have multiple reminders of how your solution works.
    - Code in short, iterative bits and run it often. Make sure either your brain hasn't wandered off the path or that you've found a problem with your solution

The key point for me is the visual reminders. My ADHD coach likes to say "if you
can't see it, it doesn't exist". Under stress I think that's a critical observation
for myself.

# The End?

This whole blob of text began as a LinkedIn post that I made on a whim to
as a reminder that we all fail sometimes, and if we can learn something
from that failure, then maybe future results will be better. The response
to that post has been overwhelming to say the least. I hope I can use this
as a springboard to keep myself blogging (I've only been trying to start that
for a decade) to keep chatting about coding, testing, test automation,
and nuerodiversity in tech. To everyone who responded to me on LinkedIn
and to everyone who reads this, thank you for giving me the reason and the
courage to start sharing my thoughts.
