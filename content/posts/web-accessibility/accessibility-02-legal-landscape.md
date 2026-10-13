---
title: "Web Accessibility Deep Dive: Legislation Lifecycles & The UN"
description: Part 2 of my series on Web Accessibility, starting with what we're looking for in legislation as well as developments in the UN.
date: 2026-10-13
modified: 2026-10-13
draft: false
tags: [design, development, accessibility]
---

## Intro
Hi all! This is a follow up from my first post in this series: [Web Accessibility Deep Dive: Intro](https://nico-series.github.io/posts/accessibility-01-intro/). In this segment of the series I'll go over the history of legislation concerning web accessibility, including some general disability and human rights developments. It ended up being fairly long so I'll be breaking it into multiple posts for readability. Details on standards, compliance, and tools (the _HOW_ to do accessibility) will follow later.

Oftentimes people go into specific fields because of their background - they think XYZ field can help them contribute in some way. Early on in my software career I came to the conclusion that the tools I build _should_ make other people's work and lives better, easier, or more enjoyable, so - full disclosure - this post is from the perspective of someone that _wants laws and practices that serve those ends_. Since I've lived in Canada and the USA my focus will be there, but for perspective I'll be casting a wide net both geographically and topically. As I write my post there are a few different potentially relevant political upheavals occurring and the potential for a Canadian "Associate" status within the EU, so this approach feels more and more appropriate as I go.
### My Process
The blog series as a whole is exploratory for me but since this specific topic deals in more concrete, fact-heavy information as opposed to personal experimentation and experience I'm taking a different approach than I've done elsewhere.

This is the first time I've tried to write anything _approaching_ an academic level of rigor since college a little over a decade ago and I find the environment has changed quite a lot since then. As I watch news, read discourse on social media, and read articles written in an authoritative tone on this and tangentially related topics, I find I've made some assumptions about what's expected. Instead of documented, verifiable paper trails, I see researchers arguing about whether or not they can write with AI. I see people positioning themselves as authorities saying that you can just tell the AI not to hallucinate, silly. I see articles discussing the implications of law that don't cite or so much as link back to copies of the documents they discuss. Not to be "back in my day..." and all but the bar appears to be being jerked around a bit. 

This post takes a bit of a relative middle ground. I'm gathering as many quality resources as I can, especially the legislation in question, but I often haven't noted the lines in documents that I'm basing my statements on as I'm aggregating and writing. This isn't academic, but it's not unaccountable either. I'm avoiding sources that I feel are untrustworthy, which includes:
- Sources that don't help me find copies of documents they discuss
- Sources that aren't affiliated with authorities in the space or news
- Anything that looks to be based in AI

I've got an *Obligatory AI Post* on the books for later, but as of right now, suffice it to know that I don't think AI sources constitute citation material outside of the self-referential. However, I can't say I've successfully avoided unreliable information. If I can't read a document, who is to say the articles and translations I've deferred to are based in legitimate interpretations? _raggle fraggle_ We learn, I guess. 
### The Recipe for Success
Before I start, please note that several types of documents will be discussed. Each state will handle their legal approach slightly differently, but from my recent reading this is how these documents tend to be defined:
- **Policies** generally regard a state's intentions but do not provide concrete practices to be followed and are not enforceable. For example, a party can have policy before their candidates are even elected. 
- **Laws** and **Acts** go further than policy - they say that the state will enforce certain behaviors, but they do not necessarily have to describe how to do this. Laws that are too vague are difficult to enforce and may result in confusion in court systems or whatever bodies are charged with interpreting them. This is why regulations often come later. 
- **Standards** outline specific practices that can be followed and are often developed by independent organizations. 
- **Regulations** outline the enforcement of laws, and in our case will likely cite a given standard to adhere to.  

In my experience terms like "law" and "policy" seem to be used to refer to miscellaneous legislation regardless of enforceability in less formal settings but "regulation" doesn't appear to be thrown around as carelessly. 

As I understand it policy is a gesture and laws and standards get the ball rolling, but applicable regulations are what are needed to enforce accessibility in a given jurisdiction. You also need data and the funding to collect it - you can't tell if your regulations are doing anything without data. Essentially, you get a pattern that looks like this: 

**Sentiment** --> **Policy** --> **Laws** --> **Research, Standards, Lawsuits** --> **Regulations** 

Additionally, we care about who these documents apply to - sometimes they only apply to government affiliated organizations or contractors. However, in order to have a properly accessible society enough employers and businesses must adhere to these standards that those needing services within the accessibility ecosystem have real choices outside of "which one can I even use?" Accessibility endgame isn't about offering a product or public service that can be used correctly one way and then a premium alternative to those people with disabilities that need it, it's about making the assumption that humans will need to interact with their environments in a variety of ways and building that way first, across the board. This is called **Universal Design**. 
# Development by Jurisdiction
In the following sections I'll go a bit more into detail on the actions of specific bodies. I'll start with the United Nations and then in following posts take a look at the European Union and a selection of countries which I picked based on their relevance to me and those entities I am most likely to interact with. 
## The United Nations Directives and The CRPD
The United Nations is a body that facilitates diplomacy. Its output is declarations and treaties, and it functions because sometimes states do what they say they will. The declarations that are made aren't binding - they are more in line with what I understand policy to be - but the treaties that follow are binding in the sense that they are promises that states make to one another that can then be pointed to later as evidence of good or bad faith. 

Disability legislation is one such case where there was follow-through; declarations led to a treaty that was signed and in turn led to real legislation.

The United Nations work concerning disability goes all the way back to *The Universal Declaration of Human Rights* ([UDHR or General Assembly Resolution 217 A](https://www.un.org/en/about-us/universal-declaration-of-human-rights)) of 1948. In this declaration, **Article 2** specifies that _everyone_, without distinction of any kind, is entitled to the rights outlined in the document. **Article 25** specifies a right to an adequate standard of living and security in times of need, including disability. **Article 27** specifies a right to participate in culture, art, and benefit from scientific advancements. Reading through this document almost 80 years after its release, it's more than a little sad that we still haven't achieved much of what this document aspired to. Opposition and slow adoption of human rights stances advanced by a new and not-entirely-accepted body such as the UN could be taken into context and understood or we could say "this is human rights, they should have been here yesterday, why on Earth are we prioritizing things other than having human rights yesterday?" We need both attitudes in order to make progress. It'll just have to be the work of more than one lifetime. 

In 1975, the UN got a bit more specific, issuing the *Declaration on the Rights of Disabled Persons* ([A/RES/3447(XXX)](https://digitallibrary.un.org/record/189608?ln=en&v=pdf)) which declares that people with disabilities have the same fundamental rights as "fellow-citizens of the same age... to enjoy a decent life, as normal and full as possible" and that therefore their needs should be taken account in economic and social planning, they should be protected from discrimination and exploitation, and that they should be able to take legal action in their defense. As we will see, legislation does follow! During this time we get early disability rights protections and the first standards. 

However, this wasn't enough. 

Three decades later, in 2006 the UN held the *Convention on the Rights of Persons with Disabilities* ([CRPD or A/RES/61/106](https://social.desa.un.org/issues/disability/resources/handbook-for-parliamentarians/handbook-for-parliamentarians-on-the)). During this convention, member states agreed that people with disabilities were being denied basic rights and that legislation was required to enshrine said rights. In our case the most relevant right is the right to access information. In **Chapter 5** it is made clear that said legislation should grant disabled people the right to seek legal recourse for infringements and for appropriate resources to be available to support that endeavor. Finally, it establishes a multi-national committee to follow up - the **Committee on the Rights of Persons with Disabilities** ([CRPD](https://www.ohchr.org/en/treaty-bodies/crpd)).

This convention was key because member states that ratified it were obliged to implement (or otherwise directly adhere to, if their legal system permits) the above legislation and several states that follow here have cited it as a direct reason for doing so. As we will see, its expectations are in fact viewed as obligatory. 

At time of writing,164 out of 194 member states have signed the CRPD. Record is kept of signing date and any statements on the UN treaty [depositary](https://treaties.un.org/Pages/ViewDetails.aspx?src=TREATY&mtdsg_no=IV-15&chapter=4&clang=_en).
## Next
The series continues with a look at India in [Web Accessibility Deep Dive: India](https://nico-series.github.io/posts/accessibility-03-india/).
## Links
- Universal Declaration of Human Rights: https://www.un.org/en/about-us/universal-declaration-of-human-rights
- UN Early Disability History: https://www.un.org/development/desa/disabilities/history-of-united-nations-and-persons-with-disabilities-the-decade-of-the-nineties.html
- 1993 SREOPD: https://www.un.org/esa/socdev/enable/dissre00.htm
- CRPD Convention Overview: https://social.desa.un.org/issues/disability/resources/handbook-for-parliamentarians/handbook-for-parliamentarians-on-the
- CRPD Committee: https://www.ohchr.org/en/treaty-bodies/crpd
- CRPD Overview (Canadian Source): https://lop.parl.ca/sites/PublicWebsite/default/en_CA/ResearchPublications/201309E
- UNDIS 1.0 Summary: https://unsdg.un.org/resources/system-wide-evaluation-un-disability-inclusion-strategy-terms-reference
- UNDIS 2.0 Summary: https://www.un.org/en/disabilitystrategy
- UN CRPD Ratification Record: https://treaties.un.org/Pages/ViewDetails.aspx?src=TREATY&mtdsg_no=IV-15&chapter=4&clang=_en