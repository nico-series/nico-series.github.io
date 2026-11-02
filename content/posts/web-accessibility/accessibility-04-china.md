---
title: "Web Accessibility Deep Dive: China"
description: Part 4 of the Web Accessibility Deep Dive post series - this time taking look at China. 
date: 2026-10-29
modified: 2026-10-29
draft: false
tags: [design, development, accessibility]
---

## Intro
Hi all! This post continues the series [Web Accessibility Deep Dive](/posts/web-accessibility/accessibility-01-intro/) and follows my post on India in [Web Accessibility Deep Dive: India](/posts/web-accessibility/accessibility-03-india/).

I chose China as a wild card for this series because it's insulated enough from my corner of the world that I would assume that it might be the least affected by the decisions made by governments I must regularly interact with. My guess is that if I'm looking for a state to take a distinct approach, China would be most at liberty to do so. 

Outside of one time that I was trying to understand the documentation for a laser etching machine's proprietary software, this might be the first time I've properly ventured into territory where I can't read much of the relevant documentation. In this case, I've had to take a more circuitous route when I can't find what I'm looking for. Thankfully, university research papers (one) exist! 
## Development
To start, two organizations come up regularly concerning China's efforts towards accessibility: the **Ministry of Industry and Information Technology (MIIT)** and the **China Disabled Persons' Federation (CDPF)**.

The legal foundation starts with the [Law on the Protection of Persons with Disabilities 1990, as amended in 2008](http://english.cdpf.org.cn/2017-07/30/c_914832.htm), which has two notable articles that have implications on web accessibility as well as enforcement guidelines:
- **Article 44** discusses the state's intentions to encourage and assist disabled people's participation in creative pursuits. 
- **Article 54** discusses the state's intentions to remove barriers to communication and public information, and to develop technology and products suitable for those with disabilities. It specifically mentions assistance for the visually impaired regarding entrance examinations. 
- **Section VIII** describes the rights of disabled persons to seek assistance in investigation, filing lawsuits, and applying for arbitration in the case that their rights are infringed. It also outlines consequences for those that delay those actions or otherwise violate the dignity of disabled people. 

This essentially provides a framework for people to start making their needs known and getting assistance to have them met, creating a grounds for more specific recommendations to grow in the following years.

The *Technical Requirements for Web Accessibility*  (YD/T 1761-2008) was approved in 2008 and to my best understanding was updated in [2012](https://www.chinesestandard.net/PDF.aspx/YDT1761-2012) to pull in some elements of WCAG 2.0. To be clear, the text "WCAG" does not appear in the standard - it instead elects to write each item out, for example explicitly including the "perceivable" principle added in WCAG 2.0. More recently China approved the *Information Technology requirements and Testing Methods for Accessibility of Web Content* (GB/T 37668-2019) standard which references WCAG 2.0 and 2.1. As with other standards, enforcement comes later. 

The *Guiding Opinions of the China Disabled Persons' Federation on Promoting Information Accessibility* [MIIT GXBLXG [2020] No. 146](https://www.miit.gov.cn/jgsj/xgj/scgl/art/2020/art_eca74f5b0c4a493e9e466195bd71ec74.html) and the *Implementation Plan to Help the Elderly Use Digital Technologies* ([State Council No.45](https://www.who.int/docs/default-source/wpro---documents/countries/china/policy-docs/implementation-plan-to-help-the-elderly-use-digital-technologies.pdf?sfvrsn=f77270c5_3)) resulted in the *Special Action Plan on Transforming Internet Apps For Better Access by Senior and People with Disabilities* [MIIT GXBLXG [2020] No. 200](https://www.who.int/docs/default-source/wpro---documents/countries/china/policy-docs/special-action-plan-on-transforming-internet-apps.pdf?sfvrsn=8eb37ac5_3), which specifies a list of websites which must be made accessible by 2021 ranging from government sites to shopping and entertainment. The approach is fairly focused as far as disability legislation goes, pledging increased development and implementation of standards for disabled people as well as going into detail about targeting the needs of older users. It rewards successes with displayable badges and assigns penalties to organizations' Enterprise Credit Evaluation for failing to meet requirements on time. 

In 2023 China implemented the *Barrier-Free Environment Construction Law* ([no alias](https://www.gov.cn/yaowen/liebiao/202306/content_6888910.htm)) which outlines accessibility requirements for new construction, enhancements, and how information is distributed. As of 2025, a State Council Information Office press conference [claimed](http://english.scio.gov.cn/m/pressroom/2025-07/23/content_117991950.html), in addition to other barrier removals, that over 3000 websites and mobile apps had undergone accessibility modifications. 

We'll now look at the paper I found. Typically I'd do a few things to vet a research paper, but in this case I cannot do anything but gesture at Tsinghua University and the word "published", so on we go! Enqiao Gu's research article, [Before and After the Barrier-Free Law: Legal Implementation of Accessibility in China](https://www.researchgate.net/publication/383343052_Before_and_After_the_Barrier-Free_Law_Legal_Implementation_of_Accessibility_in_China), discusses the environment preceding the law as well as its reception. They cite criticisms of prior legislation, including that it was often softly worded and featured disconnects between who was granted the power to enforce legislation and what offices actually existed to do so. Given my prior post on India, it may be stating the obvious to suggest that this is a common issue with developing legislation that I'll see continue the more I pry. 

Prior legislation had issued from different administrative bodies and by merit of being issued by the **Standing Committee of the National People's Congress** the Barrier-Free Law has a lot more legislative power behind it and has predictably resulted in more action, especially in regard to the creation of supplementary material and discussion. The Barrier-Free Law particularly cares about the adherence of organizations providing public information and transportation, telecommunications providers, and anything regarding emergency services, and takes steps to reduce and remove a previously perpetuated disparity between urban and rural accessibility requirements. 

Enforcement includes fines for specific types of failures but power to take action largely falls on the government; individuals are limited in options to self-advocate via the court system. It's also not complete from my perspective - there are a lot of entities that are in the grey area for required compliance depending on how public spaces are defined, and a lot of private sector entities that are out of scope. Enqiao Gu speculates that this gap could be filled with social law - law of incentives and cooperation, rather than a more administrative or punitive one. 

Since this is fairly recent, I imagine that follow-up is to come. 

Returning to my initial assumption that China might be a good wild card - was it warranted? Did I get some neat alternative approach to WCAG to read through? Aside from earlier documents - no. China is throwing their support towards development of the same global standard (WCAG). However, the state does put an emphasis on accessibility as it pertains to the needs of the elderly. Given that we all live longer and longer, assuming seniors will be occupying the same space and environments and granting them the tools and independence to do so as much as possible can only help in the long run. Peeking ahead to the scaffolding of following posts I actually don't see this approach frequently, so yes, it was definitely worthwhile.   

As a final side note, I found this [handbook](https://articles.unesco.org/sites/default/files/medias/fichiers/2024/04/Handbook%20on%20Media%20Reporting%20for%20Promoting%20Disability%20Equality%20in%20China%20%281%29.pdf) on media reporting while I was trying to find relevant documents pertaining to China and I think it's a great read. It discusses the framing of disability in news reporting and I think it has pretty widespread tie-ins about how how our modes of thinking and speaking impact communities at scale. 
## Next
My plan is for this series to continue with the EU and UK!
## Links
- Law on the Protection of Persons with Disabilities via CDPF: http://english.cdpf.org.cn/2017-07/30/c_914832.htm
- Law on the Protection of Disabled Persons via UNESCO: https://media.unesco.org/sites/default/files/webform/r2e002/c8c673b9a684f2a77cdca091a95100259ccf26dd.pdf
- Ruoxi Ran's W3 Blog on GB/T 37668-2019: https://www.w3.org/blog/2020/updated-chinese-accessibility-standard/
- YD/T 1761-2012: https://www.chinesestandard.net/PDF.aspx/YDT1761-2012
- Baidu's Review of Chinese accessibility advances: https://baike.baidu.com/item/%E7%BD%91%E9%A1%B5%E4%BF%A1%E6%81%AF%E6%97%A0%E9%9A%9C%E7%A2%8D/8126897
- CDPF: http://english.cdpf.org.cn/2023-08/29/c_914622.htm
- UNESCO on Disability in Media Reporting: https://articles.unesco.org/sites/default/files/medias/fichiers/2024/04/Handbook%20on%20Media%20Reporting%20for%20Promoting%20Disability%20Equality%20in%20China%20%281%29.pdf
- State Council No. 45: https://www.who.int/docs/default-source/wpro---documents/countries/china/policy-docs/implementation-plan-to-help-the-elderly-use-digital-technologies.pdf?sfvrsn=f77270c5_3
- MIIT GXBLXG [2020] No. 146: https://www.miit.gov.cn/jgsj/xgj/scgl/art/2020/art_eca74f5b0c4a493e9e466195bd71ec74.html
- MIIT GXBLXG [2020] No. 200: https://www.who.int/docs/default-source/wpro---documents/countries/china/policy-docs/special-action-plan-on-transforming-internet-apps.pdf?sfvrsn=8eb37ac5_3
- Barrier-Free Environment Construction Law: https://www.gov.cn/yaowen/liebiao/202306/content_6888910.htm
- 2025 SCIO Press Conference: http://english.scio.gov.cn/m/pressroom/2025-07/23/content_117991950.html
- Enqiao Gu's Research on the Barrier-Free Law: https://www.researchgate.net/publication/383343052_Before_and_After_the_Barrier-Free_Law_Legal_Implementation_of_Accessibility_in_China    