---
title: "Web Accessibility Deep Dive: India"
description: Part 3 of my series on Web Accessibility, taking a look at developments in India. 
date: 2026-10-13
modified: 2026-10-13
draft: false
tags: [design, development, accessibility]
---

# Intro
Hi all! Continuing the post series [Web Accessibility Deep Dive](https://nico-series.github.io/posts/accessibility-01-intro/) and following up on the introduction to this segment on the legal landscape of web accessibility in [Web Accessibility Deep Dive: Legislation Lifecycles & The UN](https://nico-series.github.io/posts/accessibility-02-legal-landscape/), we're going to take a look at India.

I think it would be an understatement to say that there is anything less than a highway of technical expertise and practices between India, Canada, and the USA. Ideas in one will osmose to the others, and India is very much carving out more and more real estate in software and the decisions impacting those that use it. I will begin here. 
# Development
To start, India joined the wave of legislation in the 90s to pass *The Persons with Disabilities (Equal Opportunities, Protection of Rights and Full Participation) Act, 1995* ([PWD 1995](https://media.unesco.org/sites/default/files/webform/r2e002/42fc9808f00926c6b43390588c83ba0e8d7addfc.pdf)). This act outlines the rights of disabled people, including the rights to non-discrimination, employment, education, and transportation, as well as declaring its intent to support research and affirmative action initiatives.  It also requires that institutions for disabled people are registered according to the act. 

In 2009 India began publishing guidelines for the quality and accessibility of government websites with the *Guidelines for Indian Government Websites and Apps* ([GIGW](https://guidelines.india.gov.in/introduction/)). These guidelines are broad in scope, and successive iterations include a focus on web accessibility and cybersecurity.

*The Rights of Persons with Disabilities Act, 2016* ([RPwD](https://depwd.gov.in/en/acts/)) provided necessary follow-up to the prior works as well as the *UN Convention on the Rights of Persons with Disabilities*. **Chapter VIII Section 40** requires accessible information and communication, facilities, and services regardless of location and **Section 42** specifically mentions the right to accessible media and every day electronic devices. This law is notable among others because it is legally enforceable across the public and private sector and in **Section 90** it allows leadership to be held accountable if the case of violations if they are found to be knowingly neglectful. It is administered by the **Department of Empowerment of Persons with Disabilities**.

GIGW was iterated on in 2019 with GIGW 2.0 adding support for WCAG 2.0 and then again in 2023 with GIGW 3.0 updating to reference WCAG 2.1 as well as adding a plethora of other guidelines in addition to accessibility regarding application quality, cybersecurity, and lifecycle management. GIGW 3.0 is a product of the **Ministry of Electronics and Information Technology (MeitY)** and the **Indian Computer Emergency Response Team (CERT-In)**. 

Also hitting the books in 2023, the Indian standard *Accessibility for the ICT Products and Services* (IS 17802 [Part 1](https://archive.org/details/gov.in.is.17802.1.2021/mode/1up) & [Part 2](https://archive.org/details/gov.in.is.17802.2.2022/mode/1up)) provided specifics for accessibility compliance as well as how those would be evaluated. Since this is described as a living document it is likely to be updated over time, but at time of writing it cites WCAG 2.1. Because this standard is backed by the RPwD, it is applicable across many sectors.

The question is, are these laws actually enforced? The answer is that they are being enforced _very inconsistently_ depending on where you are but the wheels are currently turning to change this. A key part of enforcing the RPwD is the appointment of a **State Commissioner for Persons with Disabilities**, whose role it is to essentially ensure follow up on compliance with the act. Without one of these, there isn't really an easy way for a person with disabilities to pursue recourse if they are discriminated against. So, while it was the law for resources on the web to be accessible and that law was enforceable on paper, in some cases there wasn't anyone around to do so. Also absent was a good way to collect penalties if they were deemed appropriate under **Section 89** of RPwD, making enforcement doubly difficult. 

In July of this year, India's Supreme Court made a move to correct this and [ordered](https://api.sci.gov.in/supremecourt/2005/9321/9321_2005_6_301_72783_Order_29-Jul-2026.pdf) that ten states and union territories (there are 28 states and 8 union territories total) that had not yet done so appoint State Commissioners for Persons with Disabilities, including Delhi and Karnataka. This [article](https://halfaccessible.com/rpwd-act-disability-rights-india-supreme-court/) on HalfAccessible goes into great detail and provides necessary context, including how developments in the court case *Rajive Raturi v Union of India ([Diary Number 9321/2005](https://api.sci.gov.in/supremecourt/2005/9321/9321_2005_1_1503_56986_Judgement_08-Nov-2024.pdf))* have played into this additional ruling (and disability legislation in general). Essentially, at the end of 2024 the Supreme Court found that the standards referenced in **Rule 15** of the *Rights of Persons with Disabilities Rules ([RPwDR](https://thc.nic.in/Central%20Governmental%20Rules/Rights%20of%20Persons%20with%20Disabilities%20Rules,%202017.pdf))* were phrased too flexibly as guidelines, resulting in inconsistent enforcement and subverting the intent of the RPwD, which was to provide a baseline of accessibility that could be developed over time. 

They threw Rule 15 out and then in July of this year provided a 4 week deadline to get enforcers ready to go and a 6 month deadline to re-evaluate accessibility standards. It wouldn't be a bad idea to monitor the news in India around the turn of the year as this is ongoing.
## Next
The series will continue with a post on web accessibility in China. I'll update this post to include a link when it's up!
## Links
- PWD Act: https://media.unesco.org/sites/default/files/webform/r2e002/42fc9808f00926c6b43390588c83ba0e8d7addfc.pdf
- DEPWD & RPwD Content: https://depwd.gov.in/en/acts/
- GIGW 3.0: https://guidelines.india.gov.in/introduction/
- IS 17802 Part 1 Requirements: https://archive.org/details/gov.in.is.17802.1.2021/mode/1up
- IS 17802 Part 2 Determination of Conformance: https://archive.org/details/gov.in.is.17802.2.2022/mode/1up
- July 29 2026 Supreme Court Order: https://api.sci.gov.in/supremecourt/2005/9321/9321_2005_6_301_72783_Order_29-Jul-2026.pdf
- HalfAccessible on RPwD Developments: https://halfaccessible.com/rpwd-act-disability-rights-india-supreme-court/
- Rajive Raturi v Union of India: https://api.sci.gov.in/supremecourt/2005/9321/9321_2005_1_1503_56986_Judgement_08-Nov-2024.pdf
- RPwDR: https://thc.nic.in/Central%20Governmental%20Rules/Rights%20of%20Persons%20with%20Disabilities%20Rules,%202017.pdf