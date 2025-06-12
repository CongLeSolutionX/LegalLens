---
created: 2025-06-10 05:31:26
author: Cong Le
version: "1.0"
license(s): MIT, CC BY-SA 4.0
copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
main source: https://www.pearson.com/en-us/subject-catalog/p/ethics-for-the-information-age/P200000003489/9780135217979
other source: https://z-lib.id/book/ethics-for-the-information-age-8th-edition-1-zlibrary
---


> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷
> 
> This is a working draft in progress
> 
> ![Loading...](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXJlZmxkeXlvbWRidXVmZGV0a3VzNm5xanJ3dWR3ODdnNmR0bjlxZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tYpzCh5MkECzAbTz6l/giphy.gif)
>
> gif image is provided by [Giphy](https://giphy.com)
> 
> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷


----


## Visualizing "Ethics for the Information Age, 8th Edition"

> **Disclaimer:**
>
> This document contains my personal notes on the topic,
> compiled from publicly available documentation and various cited sources.
> The materials are intended for educational purposes, personal study, and reference.
> The content is dual-licensed:
> 1. **MIT License:** Applies to all code implementations (Swift, Mermaid, and other programming languages).
> 2. **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0):** Applies to all non-code content, including text, explanations, diagrams, and illustrations.
---

This collection aims to visually represent the structure, key themes, and concepts presented in Michael J. Quinn's textbook.

### 1. Overall Book Structure 🗺️

A mindmap is a great way to get a bird's-eye view of the book's organization, including its chapters, appendices, and the insightful interviews interspersed throughout.

```mermaid
---
title: "Overall Book Structure"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'mindmap': {
	    'nodeAlign': 'center',
	    'padding': 20
    },
    'themeVariables': {
      'primaryColor': '#FC82',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#EBF3',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
mindmap
  root)"**Ethics for the Information Age** <br/> *(8th Ed.)*"(
    Preface))"**Preface**"((
      What_New{{"**What's New**<br/>*(8th Ed.)*"}}
        ::icon(fa fa-plus-circle)
        Appendix B: Argumentation
        Sidebars: Privacy & Security
        New Developments
          Self-driving vehicle accidents
          Cambridge Analytica
          Foreign election interference
          Cell phone location records
          Software patent invalidation
          API fair use
          FBI & encrypted iPhone
          Bias in AI test data
          BYOD security risks
          IoT DDoS attacks
          Gig economy debate
          Net neutrality (FCC changes)
          Craigslist & newspaper decline
          Google Books resolution
          Cloud computing/storage
      Organization{{"**Organization**"}}
        ::icon(fa fa-sitemap)
        Ch 1: Catalysts & History
        Ch 2: Intro to Ethics
        Ch 3-10: Concentric Rings of Issues
      Note_to_Instructors{{"Note to Instructors"}}
        ::icon(fa fa-chalkboard-teacher)
        Mapping to CS Curricula 2013
    Chapters))"**Chapters**"((
      Ch_1{{"**Ch 1**:<br/>**Catalysts for Change**"}}
        Milestones: Computing
        Milestones: Networking
        Milestones: Info Storage & Retrieval
        Contemporary IT Issues
        Interview: Dalton Conley
      Ch_2{{"**Ch 2**:<br/>**Introduction to Ethics**"}}
        ::icon(fa fa-balance-scale)
        Defining Terms
        Ethical Theories
          Subjective Relativism
          Cultural Relativism
          Divine Command Theory
          Ethical Egoism
          Kantianism
          Act Utilitarianism
          Rule Utilitarianism
          Social Contract Theory
          Virtue Ethics
        Comparing Workable Theories
        Morality of Breaking Law
        Interview: James Moor
      Ch_3{{"**Ch 3**:<br/>**Networked Communications**"}}
        ::icon(fa fa-wifi)
        Spam
        Internet Interactions (Web, Mobile Apps)
        Text Messaging
        Political Impact (Social Media, Online Ads)
        Censorship
        Freedom of Expression
        Children & Inappropriate Content
        Breaking Trust (Identity Theft, Cyberbullying)
        Internet Addiction
        Interview: Cal Newport
      Ch_4{{"**Ch 4**:<br/>**Intellectual Property**"}}
        ::icon(fa fa-copyright)
        IP Rights (Locke's Theory)
        Protecting IP
          Trade Secrets
          Trademarks
          Patents
          Copyrights
        Fair Use (Sony, Google Books)
        Digital Media (DRM, DMCA)
        Peer-to-Peer Networks & Cyberlockers
        Software Protections
        Open-Source Software
        Creative Commons
        Interview: June Besek
      Ch_5{{"**Ch 5**:<br/>**Information Privacy**"}}
        ::icon(fa fa-user-secret)
        Perspectives on Privacy
        Information Disclosures (Public Records, RFID, Mobile Apps)
        Data Mining (Opt-in/Opt-out, Consumer Profiling)
        Consumer/Political Backlash (Facebook Beacon, Cambridge Analytica)
        Interview: Michael Zimmer
      Ch_6{{"**Ch 6**:<br/>**Privacy and the Government**"}}
        ::icon(fa fa-landmark)
        US Legislation (Restricting Collection)
        Gov Info Collection (Census, NCIC, Drones)
        Covert Gov Surveillance (Wiretaps, NSA)
        US Legislation (Authorizing Wiretapping)
        USA PATRIOT Act
        Regulation of Databases (Fair Info Practices)
        Data Mining by Gov
        National ID Card (REAL ID Act)
        Information Dissemination (FOIA)
        Invasion
        Interview: Jerry Berman
      Ch_7{{"**Ch 7**:<br/>**Computer and Network Security**"}}
        ::icon(fa fa-shield-alt)
        Hacking (Passwords, Social Engineering)
        Malware (Viruses, Worms, Ransomware, Botnets)
        Cyber Crime & Cyber Attacks (Phishing, SQL Injection, DDoS)
        Online Voting
        Interview: Matt Bishop
      Ch_8{{"**Ch 8**:<br/>**Computer Reliability**"}}
        ::icon(fa fa-cogs)
        Data-Entry/Retrieval Errors
        Software & Billing Errors
        Notable Failures
          Patriot Missile
          Ariane 5
          AT&T Network
          Mars Probes
          Denver Airport Baggage
          Tokyo Stock Exchange
          DRE Voting Machines
        Therac-25 Case Study
        Tesla Autopilot Accident
        Uber Test-Vehicle Accident
        Computer Simulations
        Software Engineering (4-step process)
        Software Warranties
        Interview: Avi Rubin
      Ch_9{{"**Ch 9**:<br/>**Professional Ethics**"}}
        ::icon(fa fa-users)
        Computing Professions Development
        Software Engineering Code of Ethics
        Case Studies
        Whistle-Blowing
        Interview: Paul Axtell
      Ch_10{{"**Ch 10**:<br/>**Work and Wealth**"}}
        ::icon(fa fa-briefcase)
        Automation & Employment
        Workplace Changes (Telework, Gig Economy, Monitoring)
        Globalization
        Digital Divide
        Winner-Take-All Society
        Interview: Martin Ford
    Appendices))"**Appendices**"((
      Appendix_A{{"Appendix A:<br/>Plagiarism"}}
        ::icon(fa fa-copy)
        Consequences, Types, Avoidance
      Appendix_B{{"**Appendix B**:<br/>**Introduction to Argumentation**"}}
        ::icon(fa fa-comments)
        Valid Arguments, Fallacies, Persuasive Essays
    Interviews))"**Interviews**"((
      ::icon(fa fa-microphone)
      (Listed under each chapter)
```

**Caption for Diagram 1:** This mindmap provides a hierarchical overview of "Ethics for the Information Age," 8th edition, detailing the preface, organization, chapter topics, appendices, and notable interviews. Key updates in the 8th edition are highlighted under the preface. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson.)

---

### 2. Concentric Rings Model of Chapters 3-10 🎯

The preface mentions that Chapters 3-10 can be thought of as "forming concentric rings around a particular computer user." This diagram illustrates that concept.

```mermaid
---
title: "Concentric Rings Model of Chapters 3-10"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  layout: elk
  theme: base
  look: handDrawn
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%%%%%%% Available curve styles include the following keywords:
%% basis, bumpX, bumpY, cardinal, catmullRom, linear, monotoneX, monotoneY, natural, step, stepAfter, stepBefore.
%%{
  init: {
    'flowchart': { 'htmlLabels': true, 'curve': 'basis' },
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'themeVariables': {
      'primaryColor': '#22BB',
      'primaryTextColor': '#F8B229',
      'lineColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#E2F1',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
flowchart TD
    subgraph ConcentricRings["Book Chapters 3-10 Organization"]
	style ConcentricRings fill:#DD22
        User["💻 Computer User"]
        Ch3["Ch 3:<br/>Networked Communications"]
        Ch4["Ch 4:<br/>Intellectual Property"]
        Ch5["Ch 5:<br/>Information Privacy"]
        Ch6["Ch 6:<br/>Privacy & the Government"]
        Ch7["Ch 7:<br/>Computer & Network Security"]
        Ch8["Ch 8:<br/>Computer Reliability"]
        Ch9["Ch 9:<br/>Professional Ethics"]
        Ch10["Ch 10:<br/>Work & Wealth"]

        User --> Ch3
        Ch3 --> Ch4
        Ch4 --> Ch5
        Ch5 --> Ch6
        Ch6 --> Ch7
        Ch7 --> Ch8
        Ch8 --> Ch9
        Ch9 --> Ch10
    end
    style User fill:#f9f2,stroke:#333,stroke-width:4px
    style Ch3 fill:#22BB
    style Ch4 fill:#22BB
    style Ch5 fill:#22BB
    style Ch6 fill:#22BB
    style Ch7 fill:#22BB
    style Ch8 fill:#22BB
    style Ch9 fill:#22BB
    style Ch10 fill:#22BB

    %% note right of Ch3
    %%    Innermost ring, focusing on
    %%    direct user communications.
    %% endnote
    %% note right of Ch10
    %%    Outer ring, focusing on
    %%    broader societal impacts.
    %% endnote
```

**Caption for Diagram 2:** This diagram visualizes the "concentric rings" model described in the preface for Chapters 3 through 10 of Quinn's textbook. It shows how the topics move from the individual user's immediate interactions outwards to broader societal and economic issues. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Preface, "Organization of the Book".)

---

### 3. Chapter 1: Milestones in Information Technology ⏳

Chapter 1 discusses the history of computing, networking, and information storage. A timeline helps visualize these parallel developments.

```mermaid
---
title: "Milestones in Information Technology ⏳"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
    'gantt': { 'htmlLabels': false},
    'fontFamily': 'Monaco',
    'themeVariables': {
      'primaryColor': '#F2E9',
      'primaryTextColor': '#F8B229',
      'lineColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#EBDEF0',
      'secondaryTextColor': '#DD99',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '15px'
    }
  }
}%%
timeline
    title Milestones in Information Technology (Chapter 1)
    section Computing (1.2)
        Aids to Manual Calculating : Abacus, Tablets
        Mechanical Calculators : Pascal, Leibniz, Arithmometer
        Cash Register
        Punched-Card Tabulation : Hollerith
        Precursors of Commercial Computers : Atanasoff-Berry, ENIAC, EDVAC
        First Commercial Computers : Ferranti Mark 1, UNIVAC
        Programming Languages & Time-Sharing : FORTRAN, COBOL, BASIC, DTSS
        Transistor & Integrated Circuit : Bell Labs, Fairchild
        IBM System/360
        Microprocessor : Intel 4004
        Personal Computer : Altair 8800, Apple II, IBM PC
    section Networking (1.3)
        Electricity & Electromagnetism
        Telegraph : Morse
        Telephone : Bell
        Typewriter & Teletype
        Radio : Marconi, Sarnoff
        Television
        Remote Computing : Stibitz
        ARPANET
        Email : Tomlinson
        Internet : TCP/IP
        NSFNET
        Broadband
        Wireless Networks : Cell phones, Wi-Fi
        Cloud Computing
    section Information Storage & Retrieval (1.4)
        Greek Alphabet
        Codex and Paper
        Gutenberg’s Printing Press
        Newspapers
        Hypertext : Bush (Memex), Nelson (Xanadu)
        Graphical User Interface : Engelbart (NLS), Xerox PARC, Macintosh, Windows
        Single-Computer Hypertext : Guide, HyperCard
        Networked Hypertext (WWW) : Berners-Lee
        Search Engines : Google (PageRank)
        Cloud Storage
```

**Caption for Diagram 3:** This timeline illustrates key milestones in computing, networking, and information storage/retrieval as detailed in Chapter 1 ("Catalysts for Change") of Quinn's textbook. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Sections 1.2, 1.3, 1.4.)

---

### 4. Chapter 2: Overview of Ethical Theories 🧐

Chapter 2 introduces various ethical theories. This DOT graph provides a classification.

```dot
/*
 * title: Chapter 2: Overview of Ethical Theories
 * author: Cong Le
 * version: 1.0
 * license(s): MIT, CC BY 4.0
 * copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
 */
digraph Ethical_Theories {
    rankdir=TB;
    node [shape=box, style=rounded];
    edge [arrowhead=vee];

    Ethics [label="Ethical Theories (Ch 2)"];

    subgraph cluster_relativism {
        label="Ethical Relativism";
        style=filled;
        color=lightgoldenrodyellow;
        SubjectiveRelativism [label="Subjective Relativism (2.2)\nEach person decides right/wrong.\nPros: Accommodates differing opinions.\nCons: No moral distinctions, not based on reason."];
        CulturalRelativism [label="Cultural Relativism (2.3)\nSociety's guidelines dictate right/wrong.\nPros: Different contexts need different rules.\nCons: Doesn't explain norm determination, shared core values exist."];
    }

    subgraph cluster_objectivism {
        label="Ethical Objectivism (Workable Theories Bolded)";
        style=filled;
        color=lightcyan;
        DivineCommand [label="Divine Command Theory (2.4)\nGood = Aligned with God's will.\nPros: Creator owed obedience, God is all-good.\nCons: Many holy books disagree, not based on reason."];
        EthicalEgoism [label="Ethical Egoism (2.5)\nFocus on self-interest.\nPros: Practical, let others care for themselves.\nCons: Can lead to immoral behavior, ignores others."];
        Kantianism [label="Kantianism (2.6)\nFocus on duty, universal moral laws.\nPros: Treats all as moral equals, universal guidelines.\nCons: Conflicting rules, no exceptions to perfect duties.\nCategorical Imperative:\n1. Act only on universalizable moral rules.\n2. Treat humanity as an end, never merely as a means.", fontname="Helvetica-Bold"];
        Utilitarianism_Eth [label="Utilitarianism"];
        ActUtilitarianism [label="Act Utilitarianism (2.7)\nAction is good if net effect is more happiness.\n$U_{act} = \\sum_{i} (Benefit_i - Harm_i)$\nPros: Focuses on happiness, practical calculus.\nCons: Unclear line for calculus, ignores duty.", fontname="Helvetica-Bold"];
        RuleUtilitarianism [label="Rule Utilitarianism (2.8)\nAdopt rules that, if followed by all, maximize happiness.\nPros: No need for constant calculus, handles moral luck.\nCons: Ignores unjust distribution of good.", fontname="Helvetica-Bold"];
        SocialContract [label="Social Contract Theory (2.9)\nMorality by agreement for mutual benefit.\nRawls's Theory of Justice.\nPros: Framed in rights, explains civil disobedience.\nCons: Implicit contract, conflicting rights.", fontname="Helvetica-Bold"];
        VirtueEthics [label="Virtue Ethics (2.10)\nFocus on character, virtues for human flourishing.\nPros: Considers emotions, relationships, moral development.\nCons: Disagreement on flourishing, not for gov. policy.", fontname="Helvetica-Bold"];
    }

    Ethics -> SubjectiveRelativism [label="sub-type"];
    Ethics -> CulturalRelativism [label="sub-type"];
    Ethics -> DivineCommand [label="based on"];
    Ethics -> EthicalEgoism [label="based on"];
    Ethics -> Kantianism [label="based on"];
    Ethics -> Utilitarianism_Eth [label="based on"];
        Utilitarianism_Eth -> ActUtilitarianism [label="type"];
        Utilitarianism_Eth -> RuleUtilitarianism [label="type"];
    Ethics -> SocialContract [label="based on"];
    Ethics -> VirtueEthics [label="based on"];

    {rank=same; SubjectiveRelativism; CulturalRelativism;}
    {rank=same; DivineCommand; EthicalEgoism; Kantianism; Utilitarianism_Eth; SocialContract; VirtueEthics;}
}
```

**Caption for Diagram 4:** This diagram classifies the ethical theories discussed in Chapter 2 of Quinn's textbook, outlining their core tenets and key pros/cons. Workable theories are bolded. The utilitarian calculus is conceptually represented as $U_{act} = \sum_{i} (Benefit_i - Harm_i)$. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Sections 2.2-2.10.)

---

### 5. Workable Ethical Theories: Core Focus ✨

Chapter 2 identifies five ethical theories as "workable" for analyzing moral problems. This diagram highlights their primary focus.

```mermaid
---
title: "Workable Ethical Theories: Core Focus"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  layout: elk
  theme: base
  look: handDrawn
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%%%%%%% Available curve styles include the following keywords:
%% basis, bumpX, bumpY, cardinal, catmullRom, linear, monotoneX, monotoneY, natural, step, stepAfter, stepBefore.
%%{
  init: {
    'flowchart': { 'htmlLabels': true, 'curve': 'basis' },
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'themeVariables': {
      'primaryColor': '#22BB',
      'primaryTextColor': '#F8B229',
      'lineColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#E2F1',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
    subgraph WorkableEthicalTheories["Workable Ethical Theories (Ch 2.11)"]
	style WorkableEthicalTheories fill:#FE22
        KANT["Kantianism (2.6)"] -- "Focus on <br/> DUTIES & UNIVERSAL RULES" --> K_CI{"Categorical Imperative"}
        ACTU["Act Utilitarianism (2.7)"] -- "Focus on <br/> CONSEQUENCES of specific ACTIONS" --> AU_PU{"Principle of Utility: <br> Maximize overall happiness"}
        RULEU["Rule Utilitarianism (2.8)"] -- "Focus on <br/> CONSEQUENCES of adopting general RULES" --> RU_PU{"Principle of Utility: <br> Rules leading to max happiness"}
        SCT["Social Contract Theory (2.9)"] -- "Focus on <br/> RIGHTS & AGREEMENTS for mutual benefit" --> SCT_RAWLS{Rawls's Theory of Justice}
        VE["Virtue Ethics (2.10)"] -- "Focus on <br/> CHARACTER & VIRTUES for human flourishing" --> VE_ARISTOTLE{"Aristotelian Virtues"}
    end

    style KANT fill:#afa2
    style ACTU fill:#adf2
    style RULEU fill:#adf2
    style SCT fill:#faa2
    style VE fill:#ffa2
```

**Caption for Diagram 5:** This diagram compares the five workable ethical theories identified in Chapter 2.11 of Quinn's textbook, focusing on their distinct approaches to moral decision-making. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Sections 2.6-2.11.)

---

### 6. Chapter 4: Protecting Intellectual Property 🛡️

Chapter 4 discusses various ways to protect intellectual property. PlantUML can illustrate these as types.

```plantuml
/'
title: Chapter 4: Protecting Intellectual Property
author: Cong Le
version: 1.0
license(s): MIT, CC BY-SA 4.0
copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
'/
@startuml IntellectualPropertyTypes
skinparam handwritten true
skinparam classAttributeIconSize 0
hide emptymembers

object "Intellectual Property (IP)" as IP {
  description = "Creations of the mind"
}

object "Trade Secret (4.3.1)" as TS {
  protection_mechanism = Confidentiality
  duration = Indefinite (as long as secret)
  example = Coca-Cola formula
}

object "Trademark / Service Mark (4.3.2)" as TM {
  protection_mechanism = Registration (Brand Identity)
  duration = Renewable (as long as used)
  example = Kleenex® brand facial tissue
}

object "Patent (4.3.3)" as PT {
  protection_mechanism = Government Grant (Exclusive rights to invention)
  duration = 20 years (typically)
  example = New machine, process
}

object "Copyright (4.3.4)" as CR {
  protection_mechanism = Automatic (for original expression)
  duration = Author's life + 70 years (typically)
  example = Books, music, software (expression)
}

IP <|-- TS
IP <|-- TM
IP <|-- PT
IP <|-- CR

note bottom of TS : Protects confidential info giving competitive advantage.
note bottom of TM : Identifies goods/services; protects brand.
note bottom of PT : Protects inventions; requires disclosure.
note bottom of CR : Protects original works of authorship.
@enduml
```

**Caption for Diagram 6:** This diagram outlines the four primary ways of protecting intellectual property discussed in Chapter 4 of Quinn's textbook: Trade Secrets, Trademarks/Service Marks, Patents, and Copyrights, along with their key characteristics. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Section 4.3.)

---

### 7. Chapter 5 & 6: Solove's Taxonomy of Privacy 🕵️‍♀️

Chapters 5 and 6 delve into privacy issues. The preface to Chapter 6 mentions organizing the discussion using Daniel Solove's taxonomy of privacy. This can be visualized.

```mermaid
---
title: "Chapter 5 & 6: Solove's Taxonomy of Privacy"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  layout: elk
  theme: base
  look: handDrawn
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%%%%%%% Available curve styles include the following keywords:
%% basis, bumpX, bumpY, cardinal, catmullRom, linear, monotoneX, monotoneY, natural, step, stepAfter, stepBefore.
%%{
  init: {
    'flowchart': { 'htmlLabels': true, 'curve': 'basis' },
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'themeVariables': {
      'primaryColor': '#22BB',
      'primaryTextColor': '#F8B229',
      'lineColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#E2F1',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
    S["Daniel Solove's Taxonomy of Privacy <br/>(referencing Ch 5 & 6 Organization)"] --> C("Information Collection")
    S --> P("Information Processing")
    S --> D("Information Dissemination")
    S --> I("Invasion")

    C --> C1["Activities that gather personal information"]
    C --> C2["Ch 6.2:<br/>US Legislation Restricting Collection"]
    C --> C3["Ch 6.3:<br/>Info Collection by Government<br/>(Census, NCIC)"]
    C --> C4["Ch 6.4:<br/>Covert Government Surveillance"]
    C --> C5["Ch 6.5:<br/>US Legislation Authorizing Wiretapping"]
    C --> C6["Ch 6.6:<br/>USA PATRIOT Act"]

    P --> P1["Activities that store, manipulate, and use collected info"]
    P --> P2["Ch 5.4:<br/>Data Mining"]
    P --> P3["Ch 6.7:<br/>Regulation of Public & Private Databases (Code of Fair Info Practices, Privacy Act)"]
    P --> P4["Ch 6.8:<br/>Data Mining by the Government"]
    P --> P5["Ch 6.9:<br/>National Identification Card"]

    D --> D1["Activities that spread personal information"]
    D --> D2["Ch 6.10:<br/>Information Dissemination<br/>(FERPA, HIPAA, FOIA)"]

    I --> I1["Activities that intrude upon a person's daily life or solitude"]
    I --> I2["Ch 6.11:<br/>Invasion<br/>(Telemarketing, AIT Scanners)"]

    style S fill:#fcc2,stroke:#333,stroke-width:2px
```

**Caption for Diagram 7:** This diagram illustrates Daniel Solove's taxonomy of privacy (Information Collection, Processing, Dissemination, and Invasion), which Chapter 6 of Quinn's textbook uses as an organizing principle for discussing privacy and the US government. Relevant sub-sections from Chapter 6 are mapped to this taxonomy, along with some topics from Chapter 5. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Preface to Ch 6, and sections as indicated.)

---

### 8. Chapter 8: Software Engineering Process ⚙️

Chapter 8 discusses software engineering, which includes a four-step process for software development.

```mermaid
---
title: "Chapter 8: Software Engineering Process"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  layout: elk
  theme: base
  look: handDrawn
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%%%%%%% Available curve styles include the following keywords:
%% basis, bumpX, bumpY, cardinal, catmullRom, linear, monotoneX, monotoneY, natural, step, stepAfter, stepBefore.
%%{
  init: {
    'flowchart': { 'htmlLabels': true, 'curve': 'basis' },
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'themeVariables': {
      'primaryColor': '#22BB',
      'primaryTextColor': '#F8B229',
      'lineColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#E2F1',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
    A[Specification (8.9.1) <br/> Defining functions, requirements, constraints] --> B(Development (8.9.2) <br/> Producing software to meet specs, design, coding)
    B --> C(Validation (8.9.3) <br/> Testing software against specs & user needs)
    C --> D(Evolution (8.9.4) <br/> Modifying software for changing needs)
    D --> A_loop((Start New Cycle / Maintenance))
    style A fill:#cceeff
    style B fill:#cceeff
    style C fill:#cceeff
    style D fill:#cceeff
```

**Caption for Diagram 8:** This flowchart illustrates the four-step software engineering process (Specification, Development, Validation, Evolution) as described in Section 8.9 of Quinn's textbook. It emphasizes the cyclical nature of software development and maintenance. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Section 8.9.)

---

### 9. Chapter 9: Software Engineering Code of Ethics - Preamble Insights 🤔

The preamble to the Software Engineering Code of Ethics (Chapter 9) suggests questions to ask when facing ethical tensions, reflecting various ethical theories.

```dot
/*
 * title: Chapter 9: Software Engineering Code of Ethics - Preamble Insights
 * author: Cong Le
 * version: 1.0
 * license(s): MIT, CC BY 4.0
 * copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
 */
digraph CodePreambleInsights {
    node [shape=box, style="rounded,filled", fillcolor=beige];
    edge [arrowhead=vee];
    rankdir=LR;

    Preamble [label="Preamble Questions for Ethical Tensions (Ch 9.4.1)"];

    Q1 [label="1. Who is affected?\n(Utilitarian Focus)"];
    Q2 [label="2. Am I treating others with respect?\n(Kantian Focus: Ends, not means)"];
    Q3 [label="3. Would decision hold up to public scrutiny?\n(Virtue Ethics Focus: Character)"];
    Q4 [label="4. How will the least empowered be affected?\n(Rawls/Social Contract Focus: Difference Principle)"];
    Q5 [label="5. Are my acts worthy of the ideal professional?\n(Virtue Ethics Focus: Role Model)"];

    Preamble -> Q1;
    Preamble -> Q2;
    Preamble -> Q3;
    Preamble -> Q4;
    Preamble -> Q5;
}
```

**Caption for Diagram 9:** This diagram highlights the key questions proposed in the preamble to the Software Engineering Code of Ethics (analyzed in Section 9.4.1 of Quinn's textbook) for guiding ethical judgment when rules conflict. Each question reflects underlying principles from different workable ethical theories. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Section 9.4.1.)

---

### 10. Appendix B: Valid Argument - Modus Ponens ⚖️

Appendix B introduces argumentation. Modus Ponens is a fundamental form of valid deductive reasoning. Logical notation can be used here.

```dot
/*
 * title: Appendix B: Valid Argument - Modus Ponens
 * author: Cong Le
 * version: 1.0
 * license(s): MIT, CC BY 4.0
 * copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
 */
digraph ModusPonens {
    rankdir=TB;
    node [shape=plaintext];

    label="Valid Argument: Modus Ponens (Affirming the Antecedent)\nAppendix B.2.1";
    fontsize=14;

    Premise1 [label="Warrant: If P, then Q  (P → Q)"];
    Premise2 [label="Grounds: P is true"];
    Conclusion [label="Therefore, Q is true"];

    edge [dir=none];
    Premise1 -> Premise2 [style=invis]; // for layout
    {Premise1, Premise2} -> Conclusion [label=" Logically Implies", dir=forward, color=blue, style=bold, labelfontcolor=blue];
}
```

**Caption for Diagram 10:** This illustrates the logical structure of *Modus Ponens* (Affirming the Antecedent), a type of valid argument discussed in Appendix B.2.1 of Quinn's textbook. If the premises ($P \rightarrow Q$ and $P$) are true, the conclusion ($Q$) must be true. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Appendix B.2.1.)

---

### 11. Appendix B: Common Fallacy - Affirming the Consequent 🚫

Appendix B also covers common logical fallacies. Affirming the Consequent is an example of an invalid argument form.

```dot
/*
 * title: Appendix B: Common Fallacy - Affirming the Consequent
 * author: Cong Le
 * version: 1.0
 * license(s): MIT, CC BY 4.0
 * copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
 */
digraph AffirmingConsequent {
    rankdir=TB;
    node [shape=plaintext];

    label="Fallacy: Affirming the Consequent\nAppendix B.4.1";
    fontsize=14;

    Premise1_F [label="Warrant: If P, then Q  (P → Q)"];
    Premise2_F [label="Grounds: Q is true"];
    Conclusion_F [label="Therefore, P is true (INVALID!)"];

    edge [dir=none];
    Premise1_F -> Premise2_F [style=invis]; // for layout
    {Premise1_F, Premise2_F} -> Conclusion_F [label=" Does NOT Logically Imply", dir=forward, color=red, style=bold, labelfontcolor=red];
}
```

**Caption for Diagram 11:** This diagram shows the structure of the fallacy of *Affirming the Consequent*, an invalid argument form discussed in Appendix B.4.1 of Quinn's textbook. Even if the premises ($P \rightarrow Q$ and $Q$) are true, the conclusion ($P$) is not necessarily true. (Source: Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. Appendix B.4.1.)

---

### 12. Typical Chapter Features 🧩

Many chapters in the book follow a consistent structure, including an introduction, core content, case studies, summaries, questions, and often an interview.

```mermaid
---
title: "Typical Chapter Features"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
    'fontFamily': 'American Typewriter, monospace',
    'logLevel': 'fatal',
    'mindmap': {
	    'nodeAlign': 'center',
	    'padding': 15
    },
    'themeVariables': {
      'primaryColor': '#FC82',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#EBF3',
      'secondaryTextColor': '#6C3483',
      'secondaryBorderColor': '#A569BD',
      'fontSize': '20px'
    }
  }
}%%
pie title Typical Chapter Features
    "Introduction" : 10
    "Main Content/Sections" : 45
    "Case Studies/Examples" : 15
    "Summary" : 5
    "Further Reading/Viewing" : 5
    "Review & Discussion Questions" : 10
    "In-Class Exercises" : 5
    "Interview (Most Chapters)" : 5
```

**Caption for Diagram 12:** This pie chart illustrates the typical components and relative emphasis found in many chapters of "Ethics for the Information Age," showcasing its pedagogical approach to exploring complex ethical issues. (Source: Observation based on the Table of Contents in Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson.)

---

These diagrams provide a visual journey through the main themes and structure of "Ethics for the Information Age, 8th edition." They aim to make the complex interplay of technology, society, and ethics more accessible and understandable. 👍 Computer ethics is a dynamic field, and this book appears to offer a thorough grounding in its multifaceted issues.

---

```mermaid
---
title: "❓...CongLeSolutionX....❓"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
    'flowchart': { 'htmlLabels': false },
    'fontFamily': 'Bradley Hand',
    'themeVariables': {
      'primaryColor': '#fc82',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#8784',
      'secondaryTextColor': '#6C3483',
      'lineColor': '#F8B229',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
    My_Meme@{ img: "https://raw.githubusercontent.com/CongLeSolutionX/CongLeSolutionX/refs/heads/main/assets/images/My-meme-questions-magnifying-glass-tangled-lines-bubble-thought.png", label: "✍️...🤔❓🤔...👨🏼‍💻", pos: "b", w: 200, h: 150, constraint: "on" }
    Link_to_my_profile{{"<a href='https://github.com/CongLeSolutionX' target='_blank'>Click here if you care about my profile</a>"}}

  Closing_quote@{ shape: braces, label: "If you understood all the world's rules,<br/>would you break them<br/>or<br/>write new ones....?"}
    
   Closing_quote ~~~ My_Meme
    
  Link_to_my_profile{{"<a href='https://github.com/CongLeSolutionX' target='_blank'>Click here if you care about my profile</a>"}}

  Closing_quote ~~~ My_Meme
  My_Meme animatingEdge@--> Link_to_my_profile
  
  animatingEdge@{ animate: true }


```

---
>**Licenses:**
>
>- **MIT License:**  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) - Full text in [LICENSE](LICENSE) file.
>- **Creative Commons Attribution-ShareAlike 4.0 International**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) [![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/) - Legal details in [LICENSE-CC-BY-SA-4.0](THE_PAST/LICENSE-CC-BY-SA-4.0) and at [Creative Commons official site](https://creativecommons.org/licenses/by-sa/4.0/).
>
---


**References (Primary):**

*   Quinn, M. J. (2020). *Ethics for the Information Age* (8th ed.). Pearson. (All diagrams are interpretations based on the Table of Contents and Preface of this book.)

----

