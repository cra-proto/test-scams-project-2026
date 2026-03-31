# Test scams project

*description of the project*

**Timeframe** 2026-03-17 - 2026-06-23

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/test-scams-project-2026](https://cra-proto.github.io/test-scams-project-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-31

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(MP Kit for CRA-related scams and fraud)
    node4(Scams and fraud - CRA)
    node5(Scams and fraud – CRA - Recognize a scam)
    node6(Scams and fraud - CRA - Report a scam or identity theft)
    node7(Scams and fraud - Government of Canada)
    node8(The Government of Canada cracks down on tax cheating in real estate transactions)
    node9(Tax season may be over, but protecting your information is a year-round priority)
    node10(CRA Multimedia library)
    node11(Individuals video gallery)
    node12(Webinar – Be scam smart)
    node13(Videos about the underground economy)
    node14(When nobody cheats, everybody wins)
    node15(Sign in to your CRA account)
    node16(Help with using your CRA account)
    node17(CRA account help - Keep your CRA account secure)
    node18(Important Security Information)
    node19(Forms and publications - CRA)
    node20(Canada Revenue Agency forms listed by number)
    node21(RC213 Identity theft and suspicious activity declaration form for individual, business and trust)
    node22(Best page ever)
    node23(Taxes)
    node24(Charities and giving)
    node25(Give to a registered charity or another type of qualified donee)
    node26(Avoid donation-related scams)
    node27(Report suspected donation-related scams or other non-compliance)
    node1 --x node2
    node2 --x node3
    node2 --> node4
    node4 --> node5
    node4 --> node6
    node4 --x node7
    node4 --x node8
    node4 --x node9
    node2 --x node10
    node10 --> node11
    node11 --> node12
    node10 --x node13
    node13 --> node14
    node2 --> node15
    node15 --> node16
    node16 --> node17
    node15 --x node18
    node2 --> node19
    node19 --> node20
    node20 --> node21
    node21 --x node22
    node1 --> node23
    node23 --> node24
    node24 --> node25
    node25 --> node26
    node25 --> node27
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/campaigns/information-kit-tax-related-scams-fraud.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/corporate/scams-fraud.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/corporate/scams-fraud/recognize-scam.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/corporate/scams-fraud/report-scam.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/campaigns/fraud-scams.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/news/2017/06/the_government_ofcanadacracksdownontaxcheatinginrealestatetransa.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/news/2025/08/tax-season-may-be-over-but-protecting-your-information-is-a-year-round-priority.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/individuals-video-gallery.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/individuals-video-gallery/webinar-be-scam-smart.html" _blank
    click node13 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/videos-about-underground-economy.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/videos-about-underground-economy/transcript-when-nobody-cheats-everybody-wins.html" _blank
    click node15 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    click node16 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services.html" _blank
    click node17 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services/keep-sign-in-services-secure.html" _blank
    click node18 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/important-security-information.html" _blank
    click node19 "https://www.canada.ca/en/revenue-agency/services/forms-publications.html" _blank
    click node20 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms.html" _blank
    click node21 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/rc213.html" _blank
    click node22 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/rc213/best-page-ever.html" _blank
    click node23 "https://www.canada.ca/en/services/taxes.html" _blank
    click node24 "https://www.canada.ca/en/services/taxes/charities.html" _blank
    click node25 "https://www.canada.ca/en/revenue-agency/services/charities-giving/giving-charity-information-donors.html" _blank
    click node26 "https://www.canada.ca/en/revenue-agency/services/charities-giving/giving-charity-information-donors/donate-wisely-avoid-fraud.html" _blank
    click node27 "https://www.canada.ca/en/revenue-agency/services/charities-giving/giving-charity-information-donors/report-suspected-donation-scams-non-compliance.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node4,node5,node6,node7,node8,node9,node12,node14,node17,node18,node21,node22,node26,node27 inscope
    classDef isnew fill:#00706f,color:#fff
    class node22 isnew
    classDef ismoved fill:#eab308,color:#000
    class node7,node8,node9 ismoved
```
