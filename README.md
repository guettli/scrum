# Scrum: My point of view

I was a Scrum Master for one year (2020). It was fun and I want to share some of my findings.

My personal opinionated point of view about Scrum.

What is "Scrum"?

> Scrum is an agile framework for developing, delivering, and sustaining complex products,[1] with an initial emphasis on software development, although it has been used in other fields including research, sales, marketing and advanced technologies.[2] It is designed for teams of ten or fewer members, who break their work into goals that can be completed within time-boxed iterations, called sprints,

Source: [Wikipedia](https://en.wikipedia.org/wiki/Scrum).

Don't get me wrong: I like Scrum. The follow text contains some parts where I have a different opinion.

# Story points

> A: Will the old bridge hold us when we go over it?
>
> B: I am unsure. The bridge looks very old.
>
> A (fells fear): If we go over it and it ... collapses?
>
> B: Then it might be wise to not go over it, and instead we dance over it.
>
> A (relieved, happy): Great idea! If our heart is filled with joy we feel much lighter and then the bridge holds us. Good idea!
>
> B: ???

Most developers work 8 hours per day. Stakeholders want a solution within N weeks. Meetings are time-boxed to an hour or a half. But since some Scrum Gurus said you should use Story Points, most teams do it.

Please pay attention to the previous sentence. I wrote "Scrum Gurus", not "Scrum Guide". The official Scrum Guide only talks about "estimates".

Yes, I have read this [Jeff Sutherland "Story Points: Why are they better than hours?"](https://www.scruminc.com/story-points-why-are-they-better-than/).

I like challenges: As a developer, if I have a task which is estimated at 4 hours, this gives me a challenge: Solve it in three hours!

If I have a task that is measured in story points, then I don't have this personal challenge.

Now you could argue, I should find a magic function which maps from Story Points to hours. Then I have the same challenge. But wait: Why should I do this dancing forward and dancing backward? With "dancing" I mean converting between the unit "Story Points" and "Hours".

But maybe these fancy units have benefits. For examplel the "Jeff Bezos' 2 Pizza Rule". Why no use a boring range like "5 to 7 people"? Don't ask me. Somehow "2 Pizza Rule" is way better than a boring numbers. Maybe it is the same for "story points vs hours". 
Maybe selling colorful stories is more important than boring math.

I think estimating in hours would make more sense.

This would sharpen your awareness concerning interruptions. You could ask yourself: Why did it took longer than estimated?
Where there interrupts? What kind of interrupts?

You could argue that a juniour developer needs longer than a senior developer. Nevertheless I prefer hours. 

# Usefull Tools

For brainstorming, gathering ideas, simple voting I like [Jamboard](https://jamboard.google.com/).

It has the benefit (compared to "just talking"), that you can have a look at the feedback/opinions/text later.

But it does not make sense for daily or other short informal meetings.

You know a better or similiar tool? Great! Please tell me! [Open Source Jamboard clone?](https://softwarerecs.stackexchange.com/questions/78865/jamboard-clone)

# Team size

Most Agile and Scrum training courses refer to a 7 +/- 2 rule.

My personal opinion: The team should not have more than 6 members.

# Team lifetime

Every 12 to 18 month the scrum team should get dissolved and new teams should get born. 

This reorganization forces every team member to leave the autopilot. This is an interesting
adventure (although many people don't like changes). It helps knowledge-sharing and avoids the bore-out syndrome.

# Since three years there was never "one sprint goal".

> The Sprint Goal is the single objective for the Sprint. 

Source: [Scrum Guide 2020](https://scrumguides.org/scrum-guide.html#sprint-backlog)

Since three years I use Scrum at different companies, and in all these sprints there has never been a **single objective**. There have been almost always three or more completely unrelated goals.

Don't ask me why, but people seem to love this holy one single thing. 

This reminds of Yuval Noah Harari explaining the change from Polytheism to Monotheism.

“monotheism explains order, but is mystified by evil. Dualism explains evil, but is puzzled by order. There is one logical way of solving the riddle: to argue that there is a single omnipotent God who created the entire universe – and He’s evil. But nobody in history has had the stomach for such a belief.”

― Yuval Noah Harari, Sapiens: A Brief History of Humankind


# Sprints vs Kanban

Since Sprints in practice don't have a single goal, why not switch to a more suitable framework?

This raises the question: "Is a sprint goal needed?". I can happily live without it. It is like a constant flow of issues: New features, old bugs, refactoring and fire-fighting. Like playing [Tetris](https://en.wikipedia.org/wiki/Tetris): You managed to fill in one row, now the row disappears and you are again fighting get one row filled to make it disappear.

Example: We start a new sprint and have capacity for 40 Story Points. We fill the sprint backlog with 10 issues. Now have a look at these 10 issues. Many of them are not related to another. They are issues. Some small, some big. 

It would be nice to have one common sprint goal. Since we are all social beings, it gives us
a warm feeling inside. I think that is one major feature why a lot of people want to do scrum. Although I have never
seen a sprint with **one** sprint goal. 

If there is no useful common denominator, why create a Sprint Goal?

I think this kind of thinking is 100% fine. Maybe Kanban makes more sense?

I think it makes sense to have sprints. I don't want a continuous endless flow. The highlight at the end of the sprint is the [Sprint-Review](https://www.scrumguides.org/scrum-guide.html#sprint-review) where the Scrum Team presents the results of their work to key stakeholders.

# Thankfullness creates Happyness creates Motivation creates Productivity

If stakeholders are wise they know that it makes sense to be thankful during the sprint-review, since this motivates the developers.

If 98% of the work are done, and only 2% of the work is not perfect, and the stakeholders focus on these 2% as if this would as important as the solved 98% percent, then this will demotivate the people doing the actual work.

# Velocity

The Scrum Guide does not use the term "Velocity". But this glossary does contain it: [Glossary of scrum.org](https://www.scrum.org/Resources/Scrum-Glossary)

There are rumours that the velocity should get better and better and better until the scrum team flies with the speed of light (joking).

If the leaders want the velocity to increase, they will get what they want. The puzzle is easy to solve. Developers will just need to use higher estimates. Higher estimates, higher velocity.

I don't think that you can measure velocity. Every development task is different. 

If leaders want high and increasing velocity, then developers won't do very important tasks like cleaning up code, writing tests, trying new tools, etc. 

If leaders want it like this, they will get it. Finally some developers will get annoyed by the too abstract velocity blabla and look for a different company to work for.

# Review/Demo

I prefer the term "Demo", since "Review" could mean "Pull-Request Review", too.

Here are three ways how to present the increment to the stakeholders.

* Best: A fluent live demo. The new features get presented in a testing system and there are not hiccups.
* Good: A fluent presentation of screenshots. The screenshots show the state before the change and after the change.
* Bad: A live demo with a lot of hiccups

Since it is waste of time to make things perfect ([Pareto Principle](https://en.wikipedia.org/wiki/Pareto_principle)) I prefer the second solution: A fluent presentation of before/after screenshots.

The people who did the changes should present their work. Not the scrum master or product owner.

# Scrum is free - no money involved?

Scrum is free. We all love each other. No money is involved?

If I search for "scrum guide" I get this result:

![google search for "scrum guide"](scrum-guide--google-search2.png)

There is an advertisment.

This means scrum.org is paying google money to get to the top of this page.

So you should be aware of the fact that there is some marketing campaign behind scrum.

There are people who earn more money if more people use scrum.

Maybe Scrum is more successful than Kanban in the last years (see [Google Trend "Scrum Kanban"](https://trends.google.com/trends/explore?date=today%205-y&q=%2Fm%2F01mwhw,%2Fm%2F0ck_p8)) because Scrum has a better marketing campaign?

This gets apparent if you read about the [SEU (Scrum Education Units)](https://www.scrumalliance.org/get-certified/scrum-education-units).

Why are so many people attending the scrum conferences? Because the people want to get Scrum Education Units. Why are there many Scrum conferences? Because people want to get Scrum Education Units.... 

It is like a [pyramid scheme](https://en.wikipedia.org/wiki/Pyramid_scheme). At the top is the Scrum Alliance which gets money from the [Registered Education Providers](https://www.scrumalliance.org/get-certified/trainers/become-a-rep). The Registered Education Providers get money by people like you and me.

There are a lot of certications in the scrum/agile context. Like in every pyramid scheme, you can climb the ladder step by step by attending courses.

See: [Scrum Alliance Certs](https://www.scrumalliance.org/get-certified)

Maybe it is better to invest money in certification than to spend money on beer, but I am sceptical. 


But a lot of other institutions do it the same way. See [Professional Development Units (PDU)](https://www.pmi.org/certifications/maintain/pdu)

# The term "Sprint".

I like long-distance running. A half marathon (21km) is a great distance. Depending on the mood and entuisiasm this means one and a half or two hours of constant workout. I like it.

I am not a sprinter. I am too slow on short distances.

And now back to software development with Scrum: The interesting things won't get solved in one sprint.

I am not happy with the term "Sprint", but up to now I found no better alternative. Do you have one?

# Beyond Sprint

I guess the C-level wants more than two week planing. They think in quarters and years.

Scrum only defines the sprint, but no higher level or long term planing. Although the term "Product Goal" gets used.

[Quarterly OKRs](https://en.wikipedia.org/wiki/OKR) can be used for planing beyond two/three week sprints.

That's great. This way we can make everybody happy. Those who love Scrum and those who love Waterfall/Gantt. Oh what fun.

# Collective Intelligence

How can we in our team achieve [collective intelligence](https://en.wikipedia.org/wiki/Collective_intelligence) and avoid [groupthink](https://en.wikipedia.org/wiki/Groupthink)?

The daily helps to foster collective intelligence (if the team is small and if it is ok to interrupt the speaker).

You need a tool, so that, the participants don't see what the other participants write. They need to think on their own first.

Later you can share your screen and everybody can see the answers of all participants.

If you know a cool open source tool to foster collective intelligence, then please let me know!


# Prepare a meeting with a short Survey

A Jamboard is great for ad-hoc brainstorming. But it has the disadvantage that you see the text of other participants immideately. This means relaxed slow-thinking people might get influenced by the text of excited fast-thinking people.

You want collective-intelligence, not group-think.

A simple form to gather the ideas of each indiviual makes sense. For example [Google Forms](https://docs.google.com/forms)

If you ask people to please fill in the form **before** a meeting this increases the quality since people get prepared for the meeting.

# Personal Feedback Retro

After a scrum team worked for several sprints, it is time for a personal feedback retro. I did it like this: I created a empty Jamboard for every team member. Each board had a heading (the name of the team member) and three columns (keep on doing, stop doing, start doing).

In 15 minutes everybody could add sticky notes to the board of an other team members. Before that the moderator (Scrum Master) should remind the people to use a kind and future-focused perspective. The focus should be on "What could be improved in the future?", not "What was done wrong in the past".

After that every team member had time to read the note he received.

One day later we go through the board and everybody has the possiblity to speak about the feedback he received and to ask questions.

This was very fruitfull.

# Pragmatic Post-Mortem

If there was a bug which caused trouble to users, then it is wise to schedule a post-mortem. This helps to find the root-cause, get a common perspective and it should result in some action points to ensure the same bug does not appear again.

One of several ways to run such a meeting is to use a timeline and three levels:

* First (and lowest) level, yellow: The facts. All participants should agree here
* Second level, blue: Should: What should have been done, but was not?
* Third level: green: Action-items. Who does what during the next days?

It is important that this is not about blaming people. It is about finding ways to improve the processes. The moderator (Scrum Master) should remind the participants if the mood gets non-professional.

![post-mortem-timeline](post-mortem.png)

# "Scrum Master"

I worked as Scrum Master for one year. I learned a lot. Nevertheless if I could give the role a name, I would call it "Team Coach". This would underline the actual role: Be a servant leader for the team. And be a coach, not the one who is actually doing things.

# First "Agile", then "Blabla".

I like the [Agile Manifesto](https://agilemanifesto.org/). If you don't know it yet, then please follow the last hyperlink and read the short text.

Let's have some fun. Look at these terms:

* Agile Transformation
* Agile Management
* Agile Journey
* Agile Champions
* Agile Principles
* Agile Process
* Agile Mindset
* Agile World
* Agile Terminology
* Agile Teams
* Agile Organization
* Agile Framework
* Agile Thinking

Sounds good?

Or do you prefer it strategic? OK, here you go:

* Strategic Transformation
* Strategic Management
* Strategic Journey
* Strategic Champions
* Strategic Principles
* Strategic Process
* Strategic Mindset
* Strategic World
* Strategic Terminology
* Strategic Teams
* Strategic Organization
* Strategic Framework
* Strategic Thinking

Does this sound even more serious?

Managers and Leaders tend use these terms because .... I don't know why.

In the year 2000 the term "Internet" was the current buzzword.

But what does the average non-manager, non-leader hear if the upper levels talk like this? I hope you are able to laugh about yourself,
if you like to play the buzzword bingo game. This is what workers hear:

* Childish Transformation
* Childish Management
* Childish Journey
* Childish Champions
* Childish Principles
* Childish Process
* Childish Mindset
* Childish World
* Childish Terminology
* Childish Teams
* Childish Organization
* Childish Framework
* Childish Thinking

Finally it is about one thing: Can we deliver a something which customers will like? How much does it cost us, how much will we receive?

My guideline: Avoid the meta-level, otherwise communicating will likey get childish blabla-blublue. Be precise, implement small solutions today instead of talking about big solutions which are likely to fail.

BTW, I like the [Getting Things Done Method](https://en.wikipedia.org/wiki/Getting_Things_Done) of David Allen, [WOOP](https://woopmylife.org/en/home) of Prof. Dr. Gabriele Oettingen and [Nonviolent Communication](https://en.wikipedia.org/wiki/Nonviolent_Communication) of  Marshall Rosenberg. These methods help me more than too abstract meta level theory.

Some years ago "strategic" was the buzzword. Today "agile" is the buzzword. Let's see what will come next. Maybe "sustainable", "resilient" or "cloud native".

# "Agile" and "Scrum" don't get mentioned

There is a 500 pages book about [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/). It contains condensed wisdom by great experts. The index of the book does not contain the words "Agile" or "Scrum". If you use the full-text search, you find both terms, but only in non-relevant side-notes.

# Sprint Retrospective
 
[Scrum Guide: Sprint Retrospective](https://www.scrumguides.org/scrum-guide.html#sprint-retrospective)
 
> The Scrum Team inspects how the last Sprint went with regards to individuals, interactions, processes, tools, and their Definition of Done.
 
A common question: Should PO to participate the retrospective?
 
The "Scrum Team" means: Dev, Product-Owner and Scrum-Master. So the answer to this question is "Yes, the PO participates the Retro".
 
The PO is pushing the team. That's his job. He decides what to do by ordering Product Backlog items. 
The developers mostly care about the "how to do it".
 
If there is a good relationship between the PO and the developers, then this is no problem.

Let's celebrate a prejudices: Developers tend to be silent, they prefer to program and avoid detailed discussions.

It is the job of the SM to ensure that during the Retro the PO does not push. The SM needs to encourage silent team members to speak up.

But if the PO is pushing hard, and the developers are too shy, then there is a problem.
Developers might predict upcoming technical issues better
than the PO (since the PO usualy prefers new features to clean code). It is important to listen to everybody.


If the Scrum-Master has the feeling that there is an [elephant in the room](https://en.wikipedia.org/wiki/Elephant_in_the_room) 
then it is his/her
duty to set up a meeting without the PO.


# Listening vs Listening

I think I like communicating more than most developers. That's why I switched from Python/Django development to the role Scrum Master in Start-Up in Chemnitz. I like to listen, if someone talks to me. 

After some months I realized: There are two types of listening: If someone speaks to me, then I enjoy it, and I can help by listening and asking some questions.

But the Role of Scrum Master requires a different kind of listening skill. During the ceremonies, the team does not speak to me. They speak to the team. And that's where I struggle. If I am not involved, than I sometimes prefer to follow my thoughts instead of the current topic. My thoughts are most likely still
on a work related topic. Maybe the topic which was discussed two minutes ago. Maybe I am too detail-oriented. That's not an issue, if I am in the role of a software developer. Then I am focused if team talks about code which I am involved in.

Listening while the team discusses something is sometimes hard for me, if I am not involved in the details. Somehow I work in a kind of binary mode: I am involved and motivated XOR I am not involved and I don't care. 

Being a mediator/moderator is much harder as I initialy thought. You need to pay attention although your role is to have almost no opinion. 
Your role is to foster the collective intelligence, not to be smart.

# Blockers/Impediments created by Scrum

If you are new developer in a team, then you are not lost in the daily work. This means you can focus on your tasks, and if you are lucky you get the things done soon. And now you might get blocked by the Scrum process: There are no tickets which are "ready". There are plenty of tickets, but they are not estimated yet. The estimation should be done by the whole team. What now? You have time and motivation, but the other team members are busy.....

# Time wasted by Scrum: First we need to remove a ticket from the sprint.

There is an urgent blocker. It is unplaned and the Product Onwer wants to add it to the current sprint. The Scrum Master wants a ticket to get removed from the sprint because something new comes in. Now the whole team is involved for several minutes to decide which one should removed from the sprint. This discussion feels unproductive for me. A domain expert would have solved the blocker during the time several decide which one to remove.

# Dev waiting for Customer feedback: Unplannable

Working in Sprints sound good, but response time from customers/stakeholders is unplannable. 

1. Developer reads user-story. Product-Owner does not have the answer. A customer needs to be consulted.
2. Waiting time number 1.
3. Dev gets the answer.
4. Dev works.
5. First prototype is done. Ready to show customer. But customer has no time this week.
6. Waiting time number 2.
7. ...

As soon as you depend on people who are outside of your Sprint-circle, then it is likely that the delays let you wait again and again.

I think you can't fix this wainting time, since the customer has the right to more important stuff. 
The customer is the one who pays, this means the customer is king. The PO/Dev can only kindly remind him about
testing. Of course you can define response times in contracts, but I think this does not matter much. As soon as
you get unfriendly the customer won't come again, and then you failed completely.

This means Developers and Product-Owners don't have the power to force customers to reply soon.

If the customer does not reply again and again, then it is time to focus on other customers.

Scrum and Sprints give you a false feeling of control, if depend on things you can't control.


# The Definition of Done is just dust in the wind

Most teams working with Scrum have a "Definition of Ready" which lists the general requirments for tickets before development starts. And there
is a "Definition of Done"  which lists the general requirements which need to be fullfilled so that a ticket can be considered done.

Both texts usualy contain the word "should" very often.

The DoR and DoD have a problem: 

* They are general. But every ticket is different.
* "From idea to ticket to development to testing to releasing to communicating the change" is a long process. DoR and DoD are just two small steps in the process.
* People ignore them, because following the process strictly would slow them down.

If you don't trust the developers, than you should enforce them.

If you trust your developers, then you might not need them. You don't need them if you development process is documented. And
this is more than DoR and DoD.

During the daily work I saw most tickets did not met the requirement list of DoR and DoD. And that's ok.

I think it is important that the overall process is easy to understand and documented.



# More

[Thomas WOL: Working out Loud](https://github.com/guettli/wol)

