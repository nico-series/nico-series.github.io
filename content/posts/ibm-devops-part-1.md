---
title: IBM DevOps Training - Early Thoughts
description: In the summer of 2026, I decided to set up my good friends Development and Operations on a blind date. 
date: 2026-07-14
modified: 2026-07-14
draft: false
tags: [development]
---
## Intro
A short while ago I decided to pursue the [IBM DevOps and Software Engineering Certificate](https://www.coursera.org/professional-certificates/devops-and-software-engineering). I did this for a few very predictable reasons: 
- Technology is always changing, and practitioners must follow suit.
- DevOps methodologies in particular are relevant to me as they are an iteration on practices I utilized in a previous role.
- In addition to methods, this training makes use of tools spanning the full range of development - some of which I haven't used before. 

This training is estimated to take around 6 months if the trainee puts in around 10 hours a week. As I go, I'm going to document my thoughts here and in follow-up posts. 
## My Context Going Into This
While the technology stacks that various organizations use to approach their design challenges are heterogeneous, the strategies they throw at their respective software development lifecycles seem to chase homogeneity. Of the roles I've recently applied for, around a third mention Agile. Around a tenth mention the [SDLC](https://aws.amazon.com/what-is/sdlc/) and/or DevOps. None mention Waterfall (I'd be surprised). Last week one mentioned [GitOps](https://www.gitops.tech/)! In some ways, these work like fads - a new technique for organizing work will come out and a lead or manager will shave off weeks or years of development time and then every organization has to restructure. Will the trend-setters slow down as methods are perfected? Could there be some foundational misunderstanding about work that causes us to throw all of these methods out one day in favor of something else? Who knows! In the scheme of things, the Industrial Revolution and the following events that kicked a lot of this into motion happened basically yesterday. 

Since my longest role was with a Very Large Company™ with complex team structures and interconnected applications that must work in conjunction with one another, I think it comes as no surprise to the reader that I'm familiar with Agile. I was formally trained in [Agile Scrum](https://www.scrum.org/), but on later discussions with my team's scrum master about how our actual process deviated from the standard (the self-organizing aspects were a bit more top down, and we had this thing called a _release train_) he agreed that our process wasn't standard Scrum and looked a little more like the Scaled Agile Framework ([SAFe](https://framework.scaledagile.com/)). 

To go back further, my first encounter with Agile was seeing the [manifesto](https://agilemanifesto.org/) open on a coworker's workstation. I can't recall if he was considering pitching it to the rest of the team or satiating personal curiosity. I have fond memories from that role, but I can't say I learned a "development process". I can't say the team even used Waterfall because the sites we were working with were at least a decade into maintenance. Looking back, my two cents is that the team was small and Kanban would have sufficed for keeping tasks moving in maintenance. Also, I hope they use version control now. Oh-ho-ho yes, there was no version control! We had the power of _prayer_ in that shop. 

Early on, the reception I recall was that developers hated the amount of meetings it added to their day. I also dislike meetings... if they are inefficient. Agile caught on regardless of this because when applied to the scenarios it was designed for, it works. 
## Initial Comments on the Training
To get started, I need to answer what kind of problem DevOps is meant to solve, and in what way that deviates from what I'm used to. 

Agile is all about getting a demoable project in front of stakeholders as early on in the development process as possible so that feedback can be gained and direction can be changed in order to minimize time and resource wastage and then iterating on that. 

Once that code is written, it's not done - the code has got to go somewhere, be built, tested, revised, rebuilt, retested, accepted, deployed, and maintained. This is the part that isn't always correctly addressed with Agile alone. This occurs because often, development is one person or team's responsibility, and the responsibility of all-that-other-stuff goes to other people or teams. The problem is silos. 

DevOps aims to integrate these silos, including the ALL of the specialties that go into a given project are co-located on a more expanded idea of a fully cross-functional team. This includes developers, QA, operations, everyone relevant, and extends throughout the project's life. The people developing it need to be the people operating and maintaining it. The remainder is process optimization - if development is meant to go fast, how do we make that happen, and how do we keep fast from equaling sloppy? DevOps says the answer to this is automation - for its speed, for its consistency - applied to building, testing, deploy, and monitoring of the entire architecture. 

The training itself covers the theory and methods as well as the various tools that support this. For me, this means a review of Agile and cloud from IBM's perspective (my introduction was with AWS). It also includes an abundance of other tools and methods spanning [CI/CD](https://github.com/resources/articles/ci-cd). Some of which I'm very familiar with, some parts I've only had indirect involvement with professionally, and some that I haven't touched entirely. 
### The Topic
The training opens with an overview of what DevOps is. My gut response is that it feels exactly like the Agile training I had a few years ago - I'm being sold a product. The tools are products,. The culture is a product which reinforces itself and requires training, which is also a product. 

Products have applications, markets, etc. so the key to buying correctly is understanding the market it's for, what correct application looks like and when it's appropriate, as well as if there are competitors and when, if ever, they are better. 
### The Delivery
The training starts with the conditions surrounding the birth of DevOps. Particularly the who, the when, and the why. For me, usually details like "proper noun was done/said/written by this person on this date" aren't easily retained. Repetition doesn't really help unless it is spaced out over a period of time, usually longer than standardized testing can account for. Let's consider that I'm good at learning a few things:
- Fine motor skills, particularly regarding crafts
- Understanding a technique, especially how something is constructed, painted, or otherwise comes together
- Understanding narratives and motivations, parsing possible dynamics between people and things, walking through cause and effect, and making predictions based on examples I've seen
If we make the thing I'm bad at more like the thing I'm good at, we can succeed at retaining random facts! In this case, I have to have a narrative. To the instructor's credit he did frame the early evolution of DevOps as a narrative, but it was a very Cliffnotes-ed version and with too many proper nouns in quick succession and not as much plot. The result was that I ended up doing far more reading on each individual bullet point thrown in front of me than I imagine the training includes in its time estimate in order to retain the contents of those bullet points and place them in their context. 

That first topic is fortunately brief, the training basically states that the founders and their actions and materials are primarily discussed in order to emphasize that the methodology comes from workers and practitioners and not random spitballing administrators. Understood. I drilled it enough to pass the quizzes and moved on. Later content has had similar issues when it comes to engaging my insatiable rock-flipping, but fortunately is more about processes and techniques and hasn't featured as many names or dates.

{{< callout text="Since I'm doing a lot of side reading I think the training will be more of a time investment than it estimates. In this case, this isn't a bad thing. Each of these topics are valuable, and it means that I'm interested in what I'm learning." >}}

The training makes frequent use of quizzes with multiple choice questions - \*Gasp\*. The questions are often worded weirdly, which comes with the territory. Multiple choice is popular because it is easy to configure and easy to score, so I'll leave that as it is. Aside from that, there's been one instance so far where the content review for a section involved having a discussion with an LLM. It's 2026 - I've read plenty about LLMs, interacted with them briefly in a few contexts, and discussed them with those that build and train them, but it was fascinating and eerie to experience the sycophancy in a longer duration conversation firsthand. I expect that I'll encounter this evaluation method again.

It looks like later material will be more hands-on. This is why I picked Coursera - you really can't replace hands-on experience. Early on in the training, an account feature code is generated for accessing student cloud resources, but my code is invalid and customer support hasn't addressed my issue yet. I'm 2 tickets in, yay! We'll see how that goes, but I'll look into alternative means to access the resources if necessary because the practical experience is valuable to me.
### Final Thoughts (For Now)
So far I've completed the Introduction to DevOps course, and am most of the way through Introduction to Cloud Computing. Has anything changed? A little. Going into this I was under the impression DevOps was about automation and doing CI/CD. I've had conversations with friends in tech that discuss DevOps as if it is a role someone can have or a team. Now, I understand the first impression is sort of accurate, but doesn't really capture the picture of why it's used and the problem it's trying to solve. I was lacking in context. The second impression now feels like it could be counterproductive outright if it creates the silos that DevOps practices are supposed to remove. The cloud section has been almost entirely review - there's been some "ah did I understand that the same way the first time through" or "wait, AWS and IBM must do XYZ differently..." moments, but they've been rare. 

Since I'm still early on in this training, my opinions are still developing. Updates to follow. 
## Links
- Agile Manifesto - https://agilemanifesto.org/
- Scrum.org (the formal training I did at my last role) - https://www.scrum.org/
- SAFe - https://framework.scaledagile.com/
- GitOps - https://www.gitops.tech/
- Amazon on the SDLC - https://aws.amazon.com/what-is/sdlc/
- IBM on DevOps - https://www.ibm.com/think/topics/devops
- GitHub on CI/CD - https://github.com/resources/articles/ci-cd