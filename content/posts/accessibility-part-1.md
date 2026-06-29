---
title: "Accessibility Deep Dive: Part 1"
description: Let's outline our starting point for this series on accessibility.
date: 2026-06-28
modified: 2026-06-28
draft: false
tags: [design, development]
---

## Intro
Accessibility is one of those topics that is often looked at in a very narrow sense, and only after a concern is raised, a complaint has been lodged, or money has been lost. I think that there is a critical reason behind this:
> Organizations aren't framing what accessibility is correctly, and therefore don't understand its value.

Accessibility is the degree of usability for all users, _especially_ taking into account those with differing needs. At scale this applies to the spaces, services, devices, and technology that we interact with. All of it. The practice of making a given thing (in my case, software) accessible starts with considering how it will be practically used, and how different users will either need or want to approach its use. 

For example, users may have:
- Limited mobility
- Limited use of their hands
- Slow reaction time
- Limited senses like sight, hearing, or smell
- A tendency for motion sickness 
- Discomfort at extreme or uncontrollable sensory input
- Language barriers, including dialect, slang, or jargon
- Cognitive impairment

Consider that accessibility can _vary by the device being used_. A site that is accessible on desktop may not be on Android or iOS. 

Lastly, even if it isn't the primary target, it can be useful to consider that even if a user doesn't have a disability, they may need or prefer to use your invention in unconventional ways. For example, if a user has disruptive responsibilities - think children - they may have difficulty completing tasks in one sitting. In that case, allowing users to save form data or pause an activity could go a long way. I don't have kids but I could imagine how such a thing could assist me - think of how many times you may have accidentally refreshed an involved form and then had to refill it, or clicked a supplementary document on a page only to find out you clicked away from the page and lost all your progress. Improving accessibility raises the standard for everyone, not just the targeted communities. 

I'll say this because you likely do not know me - I think that we should seek to ensure that the things we make are widely accessible even if the money incentive isn't there, _but I'm going to die on the hill that I believe the incentive IS there._ If you make a product or provide a service that is better for some, nine times out of ten it'll make a product or service that is better for all. 

I don't like flashing lights, movement, noise, or often even bright colors. If I'm surprised by these things, I may struggle to process how to remove them quickly, and _I'll run from your site rather than try to figure out how._ This is an entirely reasonable response! 
## Standards and Enforcers
Accessibility is enforced by community guidelines as well as legal standards. Community organizations like the [A11y Project](https://www.a11yproject.com/), [IAAP](https://www.accessibilityassociation.org/), and [W3C](https://www.w3.org/) gather and share information to determine the best methods to advance accessibility initiatives, outlined in documents like [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/). 

Governments outline laws to define how their internal organizations must operate, according to government disability and accessibility initiatives at the time. For example:
- The [European Accessibility Act](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en) - a 2019 directive consolidating accessibility laws across the European Union
- The [Accessible Canada Act (ACA)](https://laws-lois.justice.gc.ca/eng/acts/a-0.6/) and various province-level acts, in my case [AODA](https://www.ontario.ca/laws/statute/05a11)
- The [Americans with Disabilities Act](https://www.ada.gov/topics/intro-to-ada/) and [Section 508](https://www.section508.gov/)

There are often exceptions to these legal requirements, but it is important to keep in mind that even if legal consequences are not applicable, a bad user experience due to accessibility failures will drive at least some users away. 
## Resources & Auditing Tools
There are organizations that provide guidance and resources in addition to the organizations listed above which contributed to WCAG:
- [WebAIM](https://webaim.org/) - Utah State University's Institute for Disability Research
- [Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/accessibility-fundamental/) - probably all of the big CSPs will have relevant courses
- [Accessibility Services Canada](https://accessibilitycanada.ca/get-help/resources/) - funded by Ontario govt, provides paid courses and a nice list of resources

Paid courses are offered by many colleges and organizations selling compliance training, but since I am currently paying for [Coursera](https://www.coursera.org/courses?query=web%20accessibility) that's where I'm most likely to spend time first. 

Many site builders are beginning to include accessibility checks in their toolkits, but dedicated tools are also available to perform accessibility audits on other sites:
- [Accessibilitychecker.org](https://www.accessibilitychecker.org/) - reviews your website's source code against guidelines 
- [Chrome Lighthouse](https://developer.chrome.com/docs/lighthouse) - Google's auditing tool, provides performance and accessibility reviews
- [WAVE](https://wave.webaim.org/extension/) - WebAIM's auditing tool
- [Silktide](https://silktide.com/) - full UX auditing tool with paid and free options
## What is to Follow
This, more or less, was the state of my notes after I spent a day or so looking into accessibility in 2025. This isn't the whole ball game; it's the first throw, and it can be taken in a few different directions in the posts to follow:
- What are the specific requirements of the laws and guidelines listed above and how would I go about meeting them? 
- How does the legal landscape differ, both between the US, CA, and the EU as well as at the province level?
- For that matter, what about other countries? Businesses are global, the things I will work with may need to be utilized elsewhere. Accessibility applies to location as well.
- In what way are the laws potentially deficient? Should I build things that exceed them?
- Explore auditing: how do each of the auditing tools above work, and when should I use them? Are there other tools? Are there ways in which the tools fail to assess accessibility?
## Links
- A11y Project: https://www.a11yproject.com/
- IAAP: https://www.accessibilityassociation.org/
- WCAG: https://www.wcag.com/resource/what-is-wcag/
- WCAG W3: https://www.w3.org/WAI/standards-guidelines/wcag/
- Mozilla's Guide: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility
- WebAim: https://webaim.org/
### Laws
- European Accessibility Act: https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en
- Accessible Canada Act: https://laws-lois.justice.gc.ca/eng/acts/a-0.6/
- Accessibility for Ontarians with Disabilities: https://www.ontario.ca/laws/statute/05a11)
- Americans with Disabilities Act: https://www.ada.gov/topics/intro-to-ada/
- Section 508: (https://www.section508.gov/)
- ADA Design Standards: https://www.ada.gov/law-and-regs/design-standards/
### Video
- Imran Siddiq's 2025 overview of the legal landscape surrounding accessibility and some of what will be required: [The deadline is running out for Web Accessibility](https://www.youtube.com/watch?v=qsA2baZILX4)
