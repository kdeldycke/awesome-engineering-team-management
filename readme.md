<!--lint disable awesome-heading-->

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-engineering-team-management/">
    <img src="https://github.com/kdeldycke/awesome-engineering-team-management/raw/main/assets/awesome-management-header.png" alt="Awesome Engineering Team Management">
  </a>
</p>

<p align="center">
  <a href="https://github.com/sponsors/kdeldycke">
    <strong>Yᴏᴜʀ Pʀᴏᴅᴜᴄᴛ ʜᴇʀᴇ!</strong>
    <br/>
    <sup>Add a link to your company or project here: purchase a GitHub sponsorship.</sup>
  </a>
</p>

---

<p align="center">
  <i>The manager's function is not to make people work, but to make it possible for people to work.</i><br>
  — Tom DeMarco<sup id="intro-quote-ref"><a href="#intro-quote-def">[1]</a></sup>
</p>

A curated [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) list **for software developers to transition to an engineering management role**. Compiles advice, anecdotes, knowledge tidbits, discussions, industry small-talks and rants. A bibliography of sort, gathered the last few years while [transitioning my career from a software engineer to an engineer's manager](https://devtomanager.com/interviews/kevin-deldycke/). And later from a manager to a manager's managers (you all love recursion right? ʘ‿ʘ).

- You're a developer and wonders what it feels like to be a manager?
- You just started your first position as the leader of a team?
- You're stuck into the day-to-day operations of the job?
- How can I move up to the next level?

You'll find answers in this guide! It stands out from generic leadership and management literature, by providing uncompromising insights and practical advice. It will bootstrap your journey into the management career track, from a technical background.

This list helps in the transition to management, with a progression from general to specifics. It starts with an overview of the role, then describes its requirements, and its position relative to others. Then we details the day-to-day tools of the trade, both organizational and behavioral. At last we discuss some of the dark sides of the job.

## Contents

<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->

- [Engineering to Management Transition](#engineering-to-management-transition)
- [Building Teams](#building-teams)
- [Roles](#roles)
  - [Executives](#executives)
  - [CTO & VP of Engineering](#cto--vp-of-engineering)
  - [Engineering Managers](#engineering-managers)
  - [Engineers](#engineers)
  - [Consultants](#consultants)
- [Recruitment](#recruitment)
  - [Job Boards](#job-boards)
  - [Hiring Process](#hiring-process)
  - [Interview](#interview)
  - [Coding Challenge](#coding-challenge)
  - [Negotiation](#negotiation)
- [Onboarding](#onboarding)
- [Motivation](#motivation)
  - [Happiness](#happiness)
  - [Procrastination](#procrastination)
- [Culture](#culture)
- [Cognitive Tools](#cognitive-tools)
  - [Collections](#collections)
  - [Explaining](#explaining)
  - [Problem Solving](#problem-solving)
  - [Systems](#systems)
  - [Brainstorming](#brainstorming)
  - [Behavioral](#behavioral)
- [Team Dynamics](#team-dynamics)
- [Engineering](#engineering)
  - [The Technical Engineering Manager](#the-technical-engineering-manager)
  - [Systems Complexity](#systems-complexity)
  - [Technology](#technology)
  - [Engineering Practices](#engineering-practices)
  - [Technical Debt](#technical-debt)
- [Remote Work](#remote-work)
- [Meetings](#meetings)
  - [1 on 1](#1-on-1)
  - [Standups](#standups)
- [Facilities](#facilities)
- [Product Management](#product-management)
  - [Hiring PMs](#hiring-pms)
  - [Product-Market Fit](#product-market-fit)
  - [Product Strategy](#product-strategy)
  - [User-Centered Design](#user-centered-design)
  - [Product Marketing](#product-marketing)
- [Project Management](#project-management)
  - [Specifications](#specifications)
  - [Estimations](#estimations)
  - [Tickets](#tickets)
  - [Delivery](#delivery)
- [Agile](#agile)
- [Key Performance Indicator (KPI)](#key-performance-indicator-kpi)
- [Objectives and Key Results (OKR)](#objectives-and-key-results-okr)
- [Training](#training)
- [Communication](#communication)
  - [Knowledge](#knowledge)
  - [Reading](#reading)
  - [Documentation](#documentation)
  - [Writing](#writing)
  - [Style](#style)
  - [Presentations](#presentations)
- [Career](#career)
  - [Promotion](#promotion)
  - [Performance Reviews](#performance-reviews)
- [Compensation](#compensation)
  - [Salary](#salary)
  - [Equity](#equity)
- [Politics](#politics)
- [Re-organizations](#re-organizations)
  - [Team-level](#team-level)
  - [Company-level](#company-level)
  - [Acquisition](#acquisition)
- [Health](#health)
  - [Holidays](#holidays)
  - [Stress](#stress)
  - [Burnout](#burnout)
- [Setbacks and Failures](#setbacks-and-failures)
- [Exits](#exits)

<!-- mdformat-toc end -->

## Engineering to Management Transition

The first step. The hardest. How to requalify oneself from an Individual Contributor (IC) to a front-line manager.

- You always been a developer. Being offered [a management position is not a promotion. It is a change in career](https://fractio.nl/2014/09/19/not-a-promotion-a-career-change/).

- [17 Reasons not to be a Manager](https://charity.wtf/2019/09/08/reasons-not-to-be-a-manager/) - An article to [discourage the faint-hearted recruits](https://youtu.be/b07887ZzKiw?t=40).

- [Advice to New Managers: Don't Joke About Firing People](https://staysaasy.com/engineering/2020/06/09/Don%27t-Joke.html) - “The second you became their manager you forfeited the right to joke around in any capacity about their employment at the company.”

- [Advice to new managers](https://x.com/ValaAfshar/status/966125964861280256) - 9 fundamental principles of the behavior required to be a great manager.

- [Mistakes I've Made as an Engineering Manager](https://css-tricks.com/mistakes-ive-made-as-an-engineering-manager/) - Mistakes: “1) Thinking people give feedback the way they want to receive it; 2) Trying to do everything yourself; 3) Communicating something one time is enough; 4) You have to have everything together all the time.”

- [Why It's Easier to Manage 4 People Than It Is to Manage 1 Person](https://staysaasy.com/management/2020/07/24/Managing-One-Person.html) - “Avoid at all costs the combination of: new manager, 1 report, report is new-to-industry, manager is not a subject-matter expert.”

- [Going from Developer to Manager. What should I know or learn?](https://news.ycombinator.com/item?id=18823616)

- [How to be a Manager – A step-by-step guide to leading a team](https://getweeklyupdate.com/manager-guide) - A full, detailed guide on modern management practices.

- [On being an Engineering Manager](https://ruiper.es/posts/engineer-manager-2017/) - Some of these points needs nuance, but others are a good taste of things to come for first-time managers.

- [Responsibility vs. accountability](https://news.ycombinator.com/item?id=21892816) - The biggest difference between manager (accountable) and engineers (responsible): “'Bad things' happen for the person accountable, whereas the person responsible can move on to the next project.”

- “A computer can never be held accountable. Therefore a computer must never make a management decision.” - An [IBM slide from 1979](https://x.com/mit_csail/status/1604884273789603842).

- “It is a job where your goal is to try disappoint people most slowly.” ([source](https://news.ycombinator.com/item?id=18222488)).

- “So the trick is basically to put them (your direct reports) in charge, not you. You have the supporting role, they can request things from you. But the goal needs to be very clear.” ([source](https://news.ycombinator.com/item?id=23973859)) - A recipe on how to work with your direct reports, from a section of [7 habits of highly effective people](https://www.amazon.com/dp/1982137274?&linkCode=ll1&tag=kevideld-20&linkId=5920a3d486de941b37430f948d377bc9&language=en_US&ref_=as_li_ss_tl).

- [The One Minute Manager Meets the Monkey](https://www.amazon.com/dp/0688103804?&linkCode=ll1&tag=kevideld-20&linkId=704eff2e2cddae6d97ef082a6f25bafd&language=en_US&ref_=as_li_ss_tl) - The author use a parable in which problems are monkeys. Unexperienced managers let monkeys being transferred to them, accumulates on their back and compounds. From this, the book teach you how to change from taking on responsibilities to delegating them so you don't become a bottleneck.

## Building Teams

You got the title and the pay grade. Congratulation! This doesn't make you a manager yet. Whether you inherit an already existing team or have to start from scratch, you'll need to practice the art of building (and consolidating) them.

- [Building and Motivating Engineering Teams](http://www.elidedbranches.com/2016/11/building-and-motivating-engineering.html) - What DO engineers want? Money, purpose and respect.

- [What Google Learned From Its Quest to Build the Perfect Team](https://web.archive.org/web/20250601205421/https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html) - “Google's data indicated that psychological safety, more than anything else, was critical to making a team work. (…) The behaviors that create psychological safety — conversational turn-taking and empathy — are part of the same unwritten rules we often turn to, as individuals, when we need to establish a bond.”

- [Paper we love: Software Engineering Organizations](https://github.com/papers-we-love/papers-we-love/tree/master/software_engineering_orgs) - “The practice of software engineering, and its history is, itself, a complex study in humanity, coordination, and communication.”

- [Developer Tropes: "Google does it"](https://tomaytotomato.com/developer-tropes-2/) - It's [cargo-cultish](https://en.wikipedia.org/wiki/Cargo_cult) to imitate the big names in our industry as a path to success. Instead, the take home from this article “would be that managers and other leaders should be like ecologists; who measure, observe and nurture their ecosystems. Doing so will help build a unique workplace that will yield great results.”

## Roles

On the profiles, attitude, behaviors, and expectations between developers, managers and executives.

### Executives

Executives are the senior/highest management layers of a company. They reports to a board of directors in bigger companies, or directly to the shareholders in smaller ones. Leadership is expected at this level. As a manager these are the people you report to.

- [What do executives do, anyway?](https://apenwarr.ca/log/20190926) - Paraphrasing [Andy Grove's book, High Output Management](https://www.amazon.com/dp/0394532341?&linkCode=ll1&tag=kevideld-20&linkId=f80a2e0610594cad92d301c587380f0a&language=en_US&ref_=as_li_ss_tl), “the job of an executive is: to define and enforce culture and values for their whole organization, and to ratify good decisions.” The article also details the failures modes of a CEO: forcing his own decisions downstream, or various ways of not resolving conflicts.

- [Executives ratify decisions made on the spot](https://news.ycombinator.com/item?id=18089716) - Tolstoy's thesis to business.

- [Army Leadership and the Profession](https://fas.org/irp/doddir/army/adp6_22.pdf) - Establishes and describes what leaders should be and do.

- [US Air Force's Strategic Leadership Studies](https://web.archive.org/web/20190308062113/http://leadership.au.af.mil/sls-skil.htm) - A reference of leadership's competencies and skills.

- [What Only the CEO Can Do](https://archive.ph/CcScN) - “1. Defining and interpreting the meaningful "outside" of the company; 2. Answering the two-part question: What business are we in and what business are we not in? 3. Balancing sufficient yield in the present with necessary investment in the future; 4. Shaping the values and standards of the organization.”

- [How CEOs Manage Time](https://archive.ph/S32wu) - A study on what CEO of large companies spent their time on, and how. Opens a new window into what leadership is all about and into its many components and dimensions.

- [Operations and Internal Communication Strategies For Effective CEOs](https://archive.ph/9DkfA) - After insisting on the importance of context and narratives, the author provide an interesting template (good for inspiration) of ritual and recurring internal communication devices.

- [Regis McKenna's talk at Silicon Valley Leaders Symposium](https://youtu.be/5Z13NI0SuyA?t=2026) - “These are the things we (marketers) used to do with individuals and bodies. They've all become automated. The CIO is the marketing chief now.”

- [Narcissistic CEOs Weaken Collaboration and Integrity](https://www.gsb.stanford.edu/insights/narcissistic-ceos-weaken-collaboration-integrity) - “The prototypic visionary leader profile is so similar to that of a narcissist, if boards aren't careful, they're going to end up choosing people who are narcissistic as CEOs”.

- “Hiring isn't the challenge. The challenge is finding people who can be effective while working for executives whose only qualifications and training are narcissistic levels of self confidence.” ([source](https://x.com/kellan/status/1205113384632500224)).

- “The CEO positions himself as a controlling, micromanaging individual at the center of everything. This makes it possible for the CEO to intercept financials and other crucial numbers en route to people who might catch on.” ([source](https://news.ycombinator.com/item?id=24519247)) - Or how fraud can endure at the top level. That's generally why you need a board of directors as an oversight.

### CTO & VP of Engineering

In tech companies these roles are critical, and the frontier between the two is often blurry.

- [CTO vs VP Engineering: What's the Difference?](https://www.ivyexec.com/career-advice/2015/cto-versus-vp-engineering-whats-the-difference/) - CTO manage a small staff of hackers. VP of Engineering lead an organization of engineers.

- [Want to Know the Difference Between a CTO and a VP Engineering?](https://bothsidesofthetable.com/want-to-know-the-difference-between-a-cto-and-a-vp-engineering-4fc3750c596b) - Another way to look at thing: placing these roles along the “Process Orientation” and “Technical Capability” quadrants.

- [The different skills needed to be a successful CTO](https://madewithlove.be/one-job-many-roles-the-different-skills-needed-to-be-a-successful-cto/) - The premise is a little misleading, as what is detailed there is the journey, in a startup, of the technical founder growing with the company to become a CTO. At which point the position described in the article is not CTO, but VP of Engineering.

- [Hiring a VP of Engineering? Use This Framework](https://review.firstround.com/hiring-a-vp-of-engineering-use-this-framework-from-shopifys-vpe-to-get-it-right/) - “*How do I hire a VP of Engineering?* After more than 20 years, eight companies, and thousands of hires, I'm starting to suspect this may be the wrong question. A better one is, *What is a VP of Engineering?*”

- [“That's usually about the time I nope right out of the interview”](https://news.ycombinator.com/item?id=19188246) - Bad signs of a CTO trying to recruit an engineering manager, or the perils of not believing in hierarchies.

### Engineering Managers

Managers came in all form and shape, and the title and daily activities varies a lot depending on companies. When developers directly reports to you, you'll find yourself at the first management level: you are a front-line engineering manager.

- [What are the signs that you have a great manager?](https://news.ycombinator.com/item?id=20230133) - “The irony is that you don't really notice a great manager.”

- [Identify what makes a great manager](https://rework.withgoogle.com/en/guides/managers-identify-what-makes-a-great-manager#learn-about-googles-manager-research) - Google tried to prove managers don't matter. Instead, it discovered [10 Traits of the Very Best Ones](https://archive.ph/1USa4).

- [As a product manager, how do you earn the respect and trust of your team?](https://web.archive.org/web/20220115172555/https://twitter.com/johncutlefish/status/1124938723093766144)

- [Good Boss, Bad Boss: A Peek Inside the Minds of the Best (and Worst)](https://www.youtube.com/watch?v=lmBSh1FGQyY) - A good boss: gets rid of rotten apples (no asshole rule) and protects people from idiocy from on high.

- “One of your roles is to act as an information filter in both directions” ([source](https://news.ycombinator.com/item?id=19187593)) - Some tips on how to balance which kind of information needs to be shared or muted.

- [Great PMs don't spend their time on solutions](https://web.archive.org/web/20250511211605/https://www.intercom.com/blog/great-product-managers-dont-spend-time-on-solutions/) - Not on solutions, no. But on customer's problems.

- [Things I have learnt as the software engineering lead of a multinational](https://minnenratta.wordpress.com/2017/01/25/things-i-have-learnt-as-the-software-engineering-lead-of-a-multinational/) - Some interesting points here, some others needs to be challenged.

- [Surprising Things About Working at Well-Known Tech Unicorns](https://blog.pragmaticengineer.com/surprising-things-about-working-at-tech-unicorns/) - Echoes my own experience on differences between expectations and reality in high growth and visible companies from the point of view of an engineering manager.

- [100+ Lessons Learned for Project Managers](https://llis.nasa.gov/lesson/1956) - 122 aphorisms providind insights into NASA project management success. Covers design, decision-making, managing staff, working with superiors and contractors.

- [Engineering Manager Resources](https://github.com/ryanburgess/engineer-manager) - Huge list, but need some curation.

- [A vitally important part of the job: being a crap shield](https://news.ycombinator.com/item?id=24802483) - “A lot of the work of an EM is wading into the slurry pit with a shovel so your team are free to get the job done”.

### Engineers

- [Programmer Moneyball: Challenging the Myth of Individual Programmer Productivity](https://insights.sei.cmu.edu/sei_blog/2020/01/programmer-moneyball-challenging-the-myth-of-individual-programmer-productivity.html) - “Since software project managers have limited ability to evaluate individual developer capability, they should rely on a productive environment and developing talent.”

- “10x developers (…) rapidly become 1x developers (or worse) if you don't let them make their own architectural choices” ([source](https://news.ycombinator.com/item?id=5496914)).

- [7 absolute truths I unlearned as junior developer](https://monicalent.com/blog/2019/06/03/absolute-truths-unlearned-as-junior-developer/) - “1. I'm a senior developer; 2. Everyone writes tests; 3. We're so far behind everyone else (a.k.a. tech FOMO); 4. Code quality matters most; 5. Everything must be documented; 6. Technical debt is bad; 7. Seniority means being the best at programming”.

- [On Being A Senior Engineer](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/) - “I expect a 'senior' engineer to be a *mature* engineer.”

- [Things I Learnt from a Senior Software Engineer](https://neilkakkar.com/things-I-learnt-from-a-senior-dev.html) - “I sat next to a senior software engineer for a year. Here's what I learnt.”

- [5 Things I've Learned in 20 Years of Programming](https://daedtech.com/5-things-ive-learned-in-20-years-of-programming/) - “A programmer with 5 years of experienced has more industry tenure than half of the entire industry.” Also see this follow-up comment of [10 things I've learned after 35 years](https://news.ycombinator.com/item?id=21612990).

- [Devs I really enjoy pairing with](https://x.com/ScribblingOn/status/1002598672444448768) - “Don't act like know-it-all; Openly admit if they don't know something; Try to figure stuff out together”.

- [All the best engineering advice I stole from non-technical people](https://medium.com/@bellmar/all-the-best-engineering-advice-i-stole-from-non-technical-people-eb7f90ca2f5f) - “It's intriguing that the stuff that really seems to make a difference in the quality of software never seems to be about software.”

- [What Makes A Great Software Engineer?](https://faculty.washington.edu/ajko/papers/Li2015GreatEngineers.pdf) - Doesn't conclude on a definitive answer to the question, but details a model based on 53 attributes (!). Still a good source referencing other papers on the topic.

- [What makes a Senior Dev](https://news.ycombinator.com/item?id=11341567) - “Time, man. You gotta do your fucking time.”

- [The different engineering levels at Google](https://news.ycombinator.com/item?id=24627229) - From L3 to L8: a quick description of what makes an engineer at each level.

- [How I operated as a Staff engineer at Heroku](https://amyunger.com/blog/2020/09/10/staff-engineer-at-heroku.html) - A great window into the somewhat nebulous title of Staff Engineer, also called Principal Engineer or Software Architect at times. I.e. a role in which you are a technical expert, but know how to solve non-obvious engineering issues, most of the time because they are rooted in social, communications and hierarchical complexities.

- [StaffEng](https://staffeng.com) - Once you've reached the Senior Software Engineer level, you're at the crossroad. Either you pursue engineering management or continue down the path of technical excellence to become a Staff Engineer. This isa collection of guides about the later position.

- [10 Admirable Attributes of a Great Technical Lead](https://betterprogramming.pub/10-admirable-attributes-of-a-great-technical-lead-251d13a8843b) - “They are smart yet kind. Knowledgeable, yet humble. Busy, yet approachable.”

### Consultants

- “A consultant is someone 4 pages ahead in the manual” ([source](https://news.ycombinator.com/item?id=20786286)).

- “The value that most orgs get from a consultant (…) is the political cover to make changes they knew they should make all along, but didn't have the social capital or the focus to make those changes” ([source](https://news.ycombinator.com/item?id=21714791)). And that's the reason bureaucracies and highly political organizations are fertile grounds for consultants.

- [The Prosperous Software Consultant](https://dabit3.medium.com/the-prosperous-software-consultant-5dc8d705c5dd) - This article let you understand how an independent consultant operates.

## Recruitment

You're in a competitive sector in which talents are in high demand. Be prepared as a manager to spend a lot of time recruiting people, either to expand your team or fill-in open positions. The dynamics gets interesting too, as you are now on both sides of the hiring process: as a candidate to get a job, and as a recruiter to staff up your team.

### Job Boards

By targeting the right place to post your job offer to, you're increasing your chances of targeting the right candidates.

- [Awesome Job Boards](https://github.com/tramcar/awesome-job-boards) - Niche job boards by domains, technology, roles and area.

- [Hiring Without Whiteboards](https://github.com/poteto/hiring-without-whiteboards) - List of companies without the kind of CS trivia questions that are associated with bad interview practices.

### Hiring Process

High-growth company will all need to industrialize the hiring process at one point.

- [Why I Never Hire Brilliant Men](https://en.wikisource.org/wiki/Why_I_Never_Hire_Brilliant_Men) - 5 simple rules for hiring men, from 1924. Things haven't changed a lot in a century.

- [A Good Tech Resume](https://thetechresume.com/A_Good_Tech_Resume.pdf) - A compilation of advice and example, but containing a good description of a typical hiring pipeline.

- [Job Interviewing Guide](https://www.homerun.co/artofwork/guides/job-interviewing) - A detailed description of a hiring process, a great source of inspiration for when your company gets big enough to start to formalize things up.

- [Open Sourced Interview Process](https://github.com/cockroachlabs/open-sourced-interview-process) - Cockroach Labs published their process “to create familiarity for candidates and account for bias, resulting in a better candidate experience and hiring decisions.”

- [Rethinking the Hiring Process](https://www.karllhughes.com/posts/rethinking-hiring) - “Testing programmers at something they aren't actually expected to be good at and expecting to learn something about how they would work at your company is delusional, and I think these kind of interviews only serve to make the hiring team feel smarter and ensure better outcomes for engineers with traditional CS backgrounds.”

### Interview

List of questions that can be used when vetting potential candidates, and topics to draw inspiration from to be used as conversation starters.

- [The Technical Interview is an Ego Trip](https://web.archive.org/web/20221101193146/https://kowsheek.com/the-technical-interview-is-an-ego-trip/) - Starts with anecdote of developers using a job interview as a vehicle to demonstrate their superiority. Then the author details a reasonable interview process that is trying to not waste anyone's time.

- [The Intangible Skills You Can't Interview For](https://staysaasy.com/leadership/2021/04/12/the-intangible-skills-you-cant-interview-for.html) - “1) Cut-Through on Crappy Tasks; 2) Knowing How to Finish; 3) Knowing How to Start; 4) Giving (And Receiving) Diagonal Feedback; 5) Harnessing the Value of Intangibles.”

- [Back-End Developer Interview Questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions) - A great source of inspiration.

- [Engineering Leadership Interviews](https://github.com/kaushikb9/em-interviews) - An outline on how to recruit for engineering manager roles.

- [Reverse interview](https://github.com/viraptor/reverse-interview) - Questions to ask the company during your interview. Be prepared to answer them as a manager.

- [Culture Queries](https://www.keyvalues.com/culture-queries) - A sample of question to ask in job interviews to try to understand the values of a company.

- [Book Summary of "Who: The A Method for Hiring"](https://medium.com/mbreads/book-summary-who-c4a437d8ae3a) - The essential of [*Who*, a popular book](https://www.amazon.com/Who-Geoff-Smart/dp/0345504194?_encoding=UTF8&qid=1686402298&sr=1-1&linkCode=ll1&tag=kevideld-20&linkId=d4a63bc5d11e6d00d942c293a640e2c1&language=en_US&ref_=as_li_ss_tl) on recruiting executives.

- “It's true that not all developers make positive contributions, however, I think that blaming "lowering hiring standards" (…) is a complete red herring.” ([source](https://news.ycombinator.com/item?id=13209317)) - Examples in which developers that might pass tough job interview just fine are bringing negative value later.

### Coding Challenge

The absence of coding exercise will left the door open to fraud. OTOH, if elitist challenges decrease the number of false-positive, you will pass on perfectly capable and great developers. Now it is your job as manager to find balance between these two extremes, and set the tone on how to have the candidate demonstrate coding skills.

- [How to Freaking Find Great Developers By Having Them Read Code](https://web.archive.org/web/20230416055512/https://freakingrectangle.com/2022/04/15/how-to-freaking-hire-great-developers/) - “Instead of writing code, consider having the candidate read existing code and talk about how it works. 1) Reading code is 95% of what a developer does as part of their job. 2) A candidate can tell you a lot about their programming skill in the first five minutes of reading. 3) Stress is your enemy because it raises adrenaline which lowers IQ by several points, causing you to miss good candidates.”

- [Organizational Skills Beat Algorithmic Wizardry](https://prog21.dadgum.com/177.html) - “When it comes to writing code, the number one most important skill is how to keep a tangle of features from collapsing under the weight of its own complexity.”

- [The Horrifically Dystopian World of Software Engineering Interviews](https://web.archive.org/web/20210911031845/https://www.jarednelsen.dev/posts/The-horrifically-dystopian-world-of-software-engineering-interviews) - The dark side on relying too much on algorithm challenges.

- [Fizz Buzz Test](https://wiki.c2.com/?FizzBuzzTest) - “Designed to help filter out the 99.5% of programming job candidates who can't seem to program their way out of a wet paper bag.”

- [FizzBuzz 2.0: Pragmatic Programming Questions for Software Engineers](https://web.archive.org/web/20211020130141/https://triplebyte.com/blog/fizzbuzz-2-0-pragmatic-programming-questions-for-software-engineers) - Five multiple-choice questions to easily separate the real software engineers from the rest.

- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - A satire of over-engineering for the sake of enterprise-grade software.

- [Awesome Interviews](https://github.com/MaximAbramchuck/awesome-interview-questions) - A huge database of questions sorted by topic to get inspiration from.

### Negotiation

A critical step to close up the hiring process.

- [How Not to Bomb Your Offer Negotiation](https://haseebq.com/how-not-to-bomb-your-offer-negotiation/) - “A good negotiator is empathetic and collaborative. They don't try to control you or issue ultimatums. Rather, they try to think creatively about how to fulfill both your and their needs.”

- [How to answer the “What's your current salary?” job interview question](https://web.archive.org/web/20190228034111/https://42hire.com/how-to-answer-the-whats-your-current-salary-job-interview-question-486254cb59ad?gi=a7f878096392) - This article explain the dynamic of that sneaky question and how to defuse it.

- [Salary Negotiation: Make More Money, Be More Valued](https://www.kalzumeus.com/2012/01/23/salary-negotiation/) - “Your salary negotiation — which routinely takes less than 5 minutes to conclude — has an outsized influence on what your compensation is.”

- [Ten Rules for Negotiating a Job Offer](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/) - “First part will be about conceptualizing the negotiating process, about how to begin the process and set yourself up for maximal success. The second part will be advice on the actual back-and-forth portion of negotiating and how to ask for what you want.”

## Onboarding

How to get newcomers up to speed with the rest of the team you manage. And how to introduce yourself to teams you just joined or inherited.

- [The Most Important Performance Management Rule For Software Engineers](https://staysaasy.com/startups/2022/04/03/performance-management.html) - “Merge code every week. That's what you should be saying to your new Software Engineering hire.”

- [Optimize Onboarding](https://staysaasy.com/management/2020/08/28/Optimize-Onboarding.html) - “Your organization has painfully slow onboarding. Endless HR videos, slow security processes, a mountain of fragile technology setup - these all make for a shitty and counterproductive start at a company. Optimize your onboarding to get people doing what you hired them to do.”

- [As a manager of a new employee I make an absolute point of being a "helicopter mom" from the moment they hit the area until about week 2 or 3](https://news.ycombinator.com/item?id=24404676) - Navigating a new organization will be hard the first few weeks, and the presence of a manager can help speed things up.

- [A Career Cold Start Algorithm](https://boz.com/articles/career-cold-start) - The author developed an algorithm to ramp-up quickly when joining an existing team where he had a massive knowledge deficit and no pre-existing relationships.

- [Meeting everyone on a new team](https://www.annashipman.co.uk/jfdi/meeting-everyone.html) - Right after inheriting a position at the top of an organization of 50 engineers, the author bootstraped the relationship with that big team by meeting everyone in 30 minutes 1:1s. It was a huge time investment, and despite fears of being boring, it allows for recognizing patterns of what change was needed.

## Motivation

- [Drive: The surprising truth about what motivates us](https://www.youtube.com/watch?v=u6XAPnuFjJc) - Daniel Pink summarizes it concisely: people are motivated by autonomy, mastery and purpose.

- Reflecting on the postulates above, [Bryan Cantrill defines that the role of management](https://x.com/bcantrill/status/1216491615264489473?s=20) “is in constructing that environment, not micromanaging it. If engineering performance is suffering, it's (likely) a management problem: wrong problem, wrong mission, or wrong team -- or all three.”

- [What Silicon Valley "Gets" about Software Engineers that Traditional Companies Do Not](https://blog.pragmaticengineer.com/what-silicon-valley-gets-right-on-software-engineers/) - “1. Autonomy for software engineers; 2. Curious problem solvers, not mindless resources; 3. Internal data, code, and documentation transparency; 4. Exposure to the business and to business metrics; 5. Engineer-to-engineer comms over triangle-communication; 6. Investing in a less frustrating developer experience; 7. Higher leverage --> higher {autonomy, pay}”.

- [Some reasons why enterprise software is good and maybe even fun](https://news.ycombinator.com/item?id=21231455) - The majority of us will not build the next unicorn: we statically have a better chance to build enterprise software. The twist? It might even be more interesting than you expect.

### Happiness

- [First, Break All the Rules: What the World's Greatest Managers Do Differently](https://www.amazon.com/dp/1595621113?&linkCode=ll1&tag=kevideld-20&linkId=cc8ac8de84cb23f23ca5577dcb7af139&language=en_US&ref_=as_li_ss_tl) - We learn in this book that employee happiness was not correlated to company success. A comment on HN details the [questions that were highly correlated to company success](https://news.ycombinator.com/item?id=20571219).

- “My team tracks life impact as a metric (pages outside business hours) and works to drive that down to zero.” ([source](https://x.com/dwc/status/962179099606200320)) - Maybe the best indicator of a happy team is how little it is disturbed outside office hours.

- [6 Signs You're a Micromanager (And What to Do Instead)](https://unito.io/blog/micromanagement-signs/) - “You're more involved with your employees than ever, yet they seem disgruntled, unhappy, and less productive than usual. Your check-ins seem to go unappreciated. And no one seems receptive to all of your great feedback on their work. What's going on? Well, we hate to break it to you, but you might be a micromanager.”

### Procrastination

- [3 tricks to start working despite not feeling like it](https://www.deprocrastination.co/blog/3-tricks-to-start-working-despite-not-feeling-like-it) - “'Screw it, let's do it'; Start sloppy; Start small”.

- [Why procrastination is about managing emotions, not time](https://www.bbc.com/worklife/article/20200121-why-procrastination-is-about-managing-emotions-not-time) - “Research shows that once the first step is made towards a task, following through becomes easier”.

## Culture

- [hacker-laws](https://github.com/dwmkerr/hacker-laws) - Laws, Theories, Principles and Patterns that developers will find useful.

- [Adaptation vs adaptability](https://sci-hub.st/10.1016/s0303-2647%2801%2900170-8) - There is a spectrum between perfect efficiency and being completely flexible. This article explores ecosystems and the flows of material and energy between different organisms within the ecosystem. ([hinted by HN comment](https://news.ycombinator.com/item?id=20963513))

- [The IT revolution and southern Europe's two lost decades](https://voxeu.org/article/it-revolution-and-southern-europes-two-lost-decades) - If you still doubt management culture could make or break an industry: “inefficient management practices have kept southern European firms from taking full advantage of the IT revolution”.

- [Meaningful differences that makes Google offices more productive](https://news.ycombinator.com/item?id=20443133) - “The people are smarter, your manager (and their manager) cares a lot about you and it's easy to move.”

- [It's Not Enough to Be Right—You Also Have to Be Kind](https://archive.ph/RoW6v) - “It's harder to be kind than clever”, or put another way by Abraham Joshua Heschel: “When I was young, I used to admire intelligent people; as I grow older, I admire kind people.”

- “It is not your job to protect people (particularly senior management) from the consequences of their decisions. Make your decisions in your own best interest; it is up to the organization to make sure that your interest aligns with theirs.” ([source](https://news.ycombinator.com/item?id=7179946)).

- “If you cannot disrupt a perverted culture by introducing a new culture, the politics of the perverted culture will work against you until you break, align, or leave. It is not unwise to leave before you break and it is easier to leave before you align.” ([source](https://news.ycombinator.com/item?id=20914779)) - At one point, even with the most unselfish of intentions, your attempts to elevate the culture might stall. It is not fair, but it's probably the time to leave.

- [You have only 4 options](https://news.ycombinator.com/item?id=16126082) - “1. Change you; 2. Change the other; 3. Fly; 4. Stay and suffer.” A more concise way of saying the same thing as above.

- [Netflix Culture](https://www.slideshare.net/reed2001/culture-1798664) - “The actual company values, as opposed to the nice-sounding values, are shown by who gets rewarded, promoted, or let go.”

- [High Performance Organizations Reading List](https://github.com/pdfernhout/High-Performance-Organizations-Reading-List) - A list of books, web pages, and videos about how to design better organizations, divided into 3 categories: organization and motivation, health and wellness, and software development specific.

- [A Conversation with Werner Vogels, Learning from the Amazon technology platform](https://queue.acm.org/detail.cfm?id=1142065) - Scaling systems is not only a technical challenge. It has to be about teams and culture too. One lesson learned from the early days of AWS: “Giving developers operational responsibilities has greatly enhanced the quality of the services, both from a customer and a technology point of view. (…) You build it, you run it.”

- [The principles of Amazon service-oriented collaboration](https://www.theregister.com/2019/05/14/amazons_away_teams/?page=2) - A compilation of anonymous sources from AWS which ehoes the interview above: “teams are ostensibly autonomous and can make any important decision needed to meet their goals.”

## Cognitive Tools

Thinking frameworks and mental models to improve decision making, understand systems and solve problems.

### Collections

Expansive lists of well-known models and concepts.

- [Gigerenzer's simple rules](https://www.foundingfuel.com/article/gigerenzers-simple-rules/) - The reason we often relies on these simple heuristics: “outside the lab, in real world, we cannot do well with just with logical rationality, we need ecological rationality - the kind of thinking that helps us get what we want in an environment that's uncertain and dynamic. This means exercising our instincts, using simple but robust rules of thumb.”

- [The Best Way to Make Intelligent Decisions](https://fs.blog/mental-models/#military_and_war) - A collection of 109 models.

- [Mental Models I Find Repeatedly Useful](https://medium.com/@yegg/mental-models-i-find-repeatedly-useful-936f1cc405d#.qb3gkdmtk) - Huge compiled list of mental models. Became the basis of book.

- [Tools for better thinking](https://untools.co) - “Collection of thinking tools and frameworks to help you solve problems, make decisions and understand systems.”

- [A Few Rules](https://www.collaborativefund.com/blog/a-few-rules/) - A formalized list of some wisdom you probably encountered elsewhere.

- [Awesome Concepts](https://github.com/lukasz-madon/awesome-concepts) - Laws, principles, mental models and cognitive biases.

- [UX Core](https://keepsimple.io/uxcore) - 105 cognitive biases with simple descriptions, brief and detailed examples.

### Explaining

- [Hanlon's razor](https://en.wikipedia.org/wiki/Hanlon%27s_razor) - “Never attribute to malice that which is adequately explained by stupidity.” My favorite flavor of [Occam's Razor](https://en.wikipedia.org/wiki/Occam%27s_razor), and a crucial mantra to defuse rampant paranoia in a highly political setting.

- [Regression toward the mean](https://en.wikipedia.org/wiki/Regression_toward_the_mean) - Or why after a period of intense euphoria and ambition, things slowly get back to their usual mediocrity.

- [Locus of control](https://en.wikipedia.org/wiki/Locus_of_control) - A framework on “the degree to which people believe that they have control over the outcome of events in their lives, as opposed to external forces beyond their control.”

### Problem Solving

- [First principles and asking why](https://www.theengineeringmanager.com/growth/first-principles-and-asking-why/) - “Our ability to think in abstractions can weaken our judgement, as those abstractions may no longer be as true as they once were. Also a similarly dangerous evolutionary trait is our ability to think in analogy, where we make assumptions based on the comparison of two things that are not actually related.” [Elon Musk explains it better](https://www.youtube.com/watch?v=NV3sBlRgzTI).

- “People who excel at software design become convinced that they have a unique ability to understand any kind of system at all, from first principles, without prior training, thanks to their superior powers of analysis. Success in the artificially constructed world of software design promotes a dangerous confidence.” - A reminder of the needs of humility and recognition of limits in our industry, [from a panel on the Moral Economy of Tech](https://idlewords.com/talks/sase_panel.htm).

- [The Art of Powerful Questions - Catalyzing Insight, Innovation, and Action](https://www.betterevaluation.org/sites/default/files/the-art-of-powerful-questions.pdf) - “Leaders believe that they are being paid for fixing problems rather than for fostering breakthrough thinking.”

### Systems

- [To Get Good, Go After The Metagame](https://commoncog.com/blog/to-get-good-go-after-the-metagame/) - “Every sufficiently interesting game has a metagame above it. This is the game about the game. It is often called 'the meta'. (…) The meta is what you get after you master boring fundamentals. But observing the state of the current meta often reveals what boring fundamentals you need to learn.”

### Brainstorming

- [Yes, and…](https://en.wikipedia.org/wiki/Yes,_and...) - “A rule-of-thumb in improvisational comedy (…). It is also used in business and other organizations as a principle that improves the effectiveness of the brainstorming process, fosters effective communication, and encourages the free sharing of ideas.”

- [Strong Opinions, Weakly Held — a framework for thinking](https://medium.com/@ameet/strong-opinions-weakly-held-a-framework-for-thinking-6530d417e364) - “Allow your intuition to guide you to a conclusion, no matter how imperfect — this is the 'strong opinion' part. Then – and this is the 'weakly held' part – prove yourself wrong.”

### Behavioral

- [Programmer Interrupted](http://blog.ninlabs.com/2013/01/programmer-interrupted/) - Research shows the devastating effect of interrupting developers: 1. 15 min is required to resume work; 2. A programmer get just one uninterrupted 2-hour session in a day; 3. Worst time to interrupt: during edits, searches & comprehension.

- “People make bad choices if they're mad or scared or stressed.” - [Disney's Frozen](https://web.archive.org/web/20250123004447if_/https://i.pinimg.com/originals/b5/17/97/b5179700050b96f91f63e086e053b5ee.jpg).

- [I coached CEOs, founders, VCs and other executive: These are the biggest takeaways](https://leowid.com/2019-2) - Excerpt: “We're all just big, complicated bags of emotion walking around; Power comes with the ability to receive a No; Learning to manage your focus, not your time.”

- [Intellectual Humility Cheat Sheet](https://web.archive.org/web/20200526135036/https://images.squarespace-cdn.com/content/v1/53419b80e4b0cccdfc3bbcf8/1579371627532-SANUEQ1REPX09L8NE1XM/ke17ZwdGBToddI8pDm48kI9Q46LYBJG1wKj9b7EvhSB7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmWp-RWlGnWD_Yv5axNBE_gjfhPXbI2t7MOi3WVleCqN9URFC-c33mY-I6dtTBVWXC/ih-cheat-sheet-v2.jpg) - “is about being open and able to change your mind about important things, and being able to discern when you should.”

- [Avoiding Intellectual Phase Lock](https://books.google.com/books?id=__CnDwAAQBAJ&lpg=PT21&dq=intellectual%20phase%20lock%20Frank%20Dunnington&pg=PT21#v=onepage&q=intellectual%20phase%20lock%20Frank%20Dunnington&f=false) - Anticipating an important result so much, humans by nature are susceptible to introduce subtle confirmation bias. To combat IPL, you might introduce random unknowns to suppress any attempt to game the system toward the object of your desire. I.e. avoid to cheat yourself to success.

- [The six ways to influence people](https://www.bakadesuyo.com/2013/06/robert-cialdini-influence/) - 6 universal principles of influence that are used to persuade business professionals: reciprocity, consistency, social proof, getting people to like you, authority and scarcity.

- [On Bullshit](http://ruby.fgcu.edu/courses/twimberley/EnviroPhilo/bullshit.pdf) - This [HN comment](https://news.ycombinator.com/item?id=23147605) perfectly describes the concept. “Unlike lying/fraud, where falsehood is instrumental, Frankfurt defined bullshit as potentially false speech where the truth *simply wasn't important*. Bullshit is characterized by giving the *surface appearance* of confidence, intelligence, or a convincing argument; whether it's actually true or not is besides the point.”

## Team Dynamics

On the day-to-day dynamics of the team, and its interaction with other teams.

- [How to Celebrate the Small Wins](https://web.archive.org/web/20190714235605/https://medium.dave-bailey.com/how-to-celebrate-the-small-wins-4a03004a1816?gi=90c401bc3fd1) - My takeaway: “Celebrating Slow Progress; Hunt for Key Milestones”.

- [Team Leader Venn Diagram](https://larahogan.me/blog/team-leader-venn-diagram/) - “A tool for gaining a shared understanding of responsibilities”.

- [When your coworker does great work, tell their manager](https://jvns.ca/blog/2020/07/14/when-your-coworker-does-great-work-tell-their-manager/) - Highlighting unseen work in public allows managers to recognize efforts their reports are doing. Still, there is some cases in which it might put your colleague in a tight spot. So always ask if it's ok first.

- [Eye Candy QA](https://techreflect.net/2020/01/05/eye-candy-qa-2005-2011/) - Retelling of author's job at Apple: “John Louch was my boss. (…) John always shared everything with us, even the *don't share this with your team* stuff. We were people he trusted, so it was as it should be. It made you feel like you were part of something greater.” Or why sharing some open secret promote strong trust in your entourage.

- [The Apollo Syndrome](https://www.teamtechnology.co.uk/tt/t-articl/apollo.htm) - A phenomenon discovered by Dr Meredith Belbin, and exposed in his 1981 [book on Management Teams](https://www.amazon.com/dp/1856178072?&linkCode=ll1&tag=kevideld-20&linkId=486a53a41992fa334ccd6de4b3f689e1&language=en_US&ref_=as_li_ss_tl), where teams of highly capable individuals can, collectively, perform badly.

- [A conversation with Elon Musk about Starship](https://youtu.be/cIQ36Kt7UVg?t=203) - In a team with very talented contributors, everyone's is a chief engineer: you are expected to challenge the status-quo and questions other department's constraints. This allow smart engineers to avoid the trap of optimizing for something that should not exist in the first place. Might be a cure for the Apollo Syndrome.

- [Symptoms of Groupthink](https://web.archive.org/web/20210925184712/https://courses.washington.edu/psii101/Powerpoints/Symptoms%20of%20Groupthink.htm) - Overconfidence, tunnel vision and conformity pressure can led a group astray.

- [It's Not Sabotage, They're Drowning](https://shermanonsoftware.com/2019/11/15/its-not-sabotage-theyre-drowning/) - Some kind of push backs shouldn't be interpreted as intentional sabotage, but as drowning people sinking the lifeboat in an attempt to save themselves.

- “Community already exists, you just create a communication platform for it” ([source](https://news.ycombinator.com/item?id=21828666)) - Or why trying to create a community from the ground up might not be the right way of looking at things: a better and more subtle strategy would be to empowers the already existing channels and make them visible.

## Engineering

You're no longer an engineer. Still, your team is responsible for the systems, technology and all the processes surrounding them. You'd better know a bit about engineering tenets.

### The Technical Engineering Manager

You shouldn't spend your time coding. Leave that to the engineers: your value lies elsewhere now. But does that means you must forget all things technical? The answer is an astounding *NO*. Here are some arguments:

- [Do engineering managers need to be technical?](https://increment.com/teams/do-engineering-managers-need-to-be-technical/) - Yes. “Looking forward to the next 30 years of management trends, only a few things seem certain: Managers should be technical, and the definition of technical will continue to change.”

- [If Your Boss Could Do Your Job, You're More Likely to Be Happy at Work](https://archive.ph/J2vlo#selection-1025.8-1025.64) - “Although we found that many factors can matter for happiness at work – type of occupation, level of education, tenure, and industry are also significant, for instance – they don't even come close to mattering as much as the boss' technical competence.”

- “The best managers I met tended to be those that if the circumstance required it, could do the job of those two levels below.” ([source](https://news.ycombinator.com/item?id=23891984)) - Another way of putting it: managers needs domain knowledge and to know the work their reports do.

- “Over the years we have developed the policy that it is important for the supervisor to thoroughly know and understand the work of his group.” ([source](https://news.ycombinator.com/item?id=20683609)) - This quote is [from David Packard](https://www.amazon.com/HP-Way-Hewlett-Built-Company/dp/0887307477?_encoding=UTF8&qid=1686404404&sr=1-1&linkCode=ll1&tag=kevideld-20&linkId=e6069674f9b0b4ef884b0f8f70eb8f94&language=en_US&ref_=as_li_ss_tl) (HP co-founder), decades before current [management fad](https://en.wikipedia.org/wiki/Management_fad).

### Systems Complexity

Whatever the technical stack, we are building systems first, and have to manage its complexity.

- [Second-system effect](https://en.wikipedia.org/wiki/Second-system_effect) - “Tendency of small, elegant, and successful systems, to be succeeded by over-engineered, bloated systems”.

- [Living with Complexity, by Donald A. Norman](https://www.amazon.com/Living-Complexity-Donald-Norman-2010/dp/B00DEKM5GK?_encoding=UTF8&qid=1686404524&sr=1-1&linkCode=ll1&tag=kevideld-20&linkId=497ae387bbd398624d897bdfbf90f7b6&language=en_US&ref_=as_li_ss_tl) - In which we learn that, based on [Tesler's law of the conservation of complexity](https://en.wikipedia.org/wiki/Law_of_conservation_of_complexity), “the total complexity of a system is a constant: as you make the person's interaction simpler, the hidden complexity behind the scenes increases. Make one part of the system simpler, said Tesler, and the rest of the system gets more complex.”

- [The Efficiency-Destroying Magic of Tidying Up](https://flocrivello.com/the-efficiency-destroying-magic-of-tidying-up/) - “Efficiency tends to look messy, and good looks tend to be inefficient.” A reminder that sometimes we should just accept [the messiness of the world](https://github.com/kdeldycke/awesome-falsehood).

- [I try to optimize my code around reducing state, coupling, complexity and code, in that order](https://news.ycombinator.com/item?id=11042400) - An engineer's perspective on which priorities should be addressed first to increase robustness of systems.

- [SpaceX's 5-Step design and manufacturing process](https://www.youtube.com/watch?v=t705r8ICkRw&t=13m30s) - “1. Make requirement less dumb; 2. Try to delete parts; 3. Simplify or optimize; 4. Accelerate cycle time; 5. Automate”. See [full transcript](https://news.ycombinator.com/item?id=28517976).

### Technology

- [Choose Boring Technology](http://boringtechnology.club) - “Boring, in the sense that it's well understood.”

- [Choose Well-known Technology](https://news.ycombinator.com/item?id=23445535) - A rephrasing of the above advice. “Choose the technology: 1. You know in and out, and are immediately productive with; 2. Which is sure to be around in 5-7 years, preferably 10-15; 3. For which you are comfortable hiring the next 15 engineers.”

- [Industry Data Models](https://web.archive.org/web/20220330034214/http://databaseanswers.org/data_models/) - A huge list of database templates collected over 25 years by Barry Williams to represent any business process.

- “Lots of people make the mistake of thinking there's only two vectors you can go to improve performance, high or wide. High - throw hardware at the problem, on a single machine. Wide - add more machines. [There's a third direction you can go, I call it *going deep*.](https://news.ycombinator.com/item?id=8902739)”

- [You need to be this tall to use (micro) services](https://news.ycombinator.com/item?id=12509533) - Do not chase the hype. Yet. Micro-services only brings value past a certain infrastructure and organization size. This is a list of stuff you should focus on before bringing micro-services to the mix.

- [LEGO blocks and organ transplants](https://www.johndcook.com/blog/2011/02/03/lego-blocks-and-organ-transplants/) - “People have been comparing software components to LEGO blocks for a couple decades. (…) Integrating two software systems is usually more like performing a heart transplant than snapping together LEGO blocks.”

- “Software development is more akin to the product design and development phase of industrial production than to the manufacturing.” ([source](https://accu.org/bookreviews/1998/kloss_1668/)) - This quote is from a review of [*Superdistribution - Objects as Property on the Electronic Frontier*](https://www.amazon.com/dp/0201502089?&linkCode=ll1&tag=kevideld-20&linkId=dc65849a678d52afa9f3685159673d6e&language=en_US&ref_=as_li_ss_tl), in which the creator of Objective-C was advocating in the 90's for a new economic framework that rewards creation of components in proportion to their use. But software production is not like manufacturing of widgets in a factory. [A (software) object is not an (hardware) widget](https://x.com/kdeldycke/status/1697974273623675254).

### Engineering Practices

- [Software Engineering's Greatest Hits](https://www.youtube.com/watch?v=HrVtA-ue-x0) - When scientific method meet the practice of software development. My takeaways: the best metric is less lines of code, there is no 10x developers, too much unused configuration options, pair programing is for transfer of domain-specific knowledge and hackathon don't produce long term projects.

- [Code reviews at Google](https://github.com/google/eng-practices/blob/master/review/reviewer/speed.md#why-should-code-reviews-be-fast-why) - “Why Should Code Reviews Be Fast? (…) To optimize for the speed at which a team of developers can produce a product together, as opposed to optimizing for the speed at which an individual developer can write code.”

- [Google Engineering Practices](https://google.github.io/eng-practices/) - Explains how to perform code reviews and how to submit them.

- [Embedded Rules of Thumb](https://embeddedartistry.com/blog/2018/04/26/embedded-rules-of-thumb/) - Guidelines and heuristics to provide a reasonable approximation of the truth while developing embedded devices. Most also applies to software projects in general.

- [How to Misuse Code Coverage](https://web.archive.org/web/20180508120159/http://www.testingeducation.org/BBST/foundations/Marick_coverage.pdf) - “If a part of your test suite is weak in a way that coverage can detect, it's likely also weak in a way coverage can't detect.” I.e. the great benefit of a coverage report is that it tells you what you forgot to think about when you wrote the test suite itself ([source](https://news.ycombinator.com/item?id=28678098)).

### Technical Debt

- [Tech Due Diligence Calculator](https://decodingvc.gitbooks.io/p9-startup-tech-due-diligence-calculator/content/) - A list of questions by topic to help understand how you are building your tech and engineering team, trying to highlight red flags.

- [Technical Debt Is Like Tetris](https://web.archive.org/web/20190313164624/https://medium.com/@erichiggins/technical-debt-is-like-tetris-168f64d8b700) - Another way to explain technical debt: “Scenarios like these create technical debt within the product code. A buried gap in Tetris represents technical debt. (…) Paying down technical debt keeps you competitive. It keeps you in the game.”

- [Technical debt as a lack of understanding](https://daverupert.com/2020/11/technical-debt-as-a-lack-of-understanding/) - “The problem lies in "never reorganizing [the code] to reflect your understanding." (…) Organizationally, you pay in velocity and turnover; talented people are going to leave after a few rounds of bullshit.”

- [The Framing of the Developer](https://www.amazingcto.com/develop-for-impact-not-for-backlog/) - Default framing is around the backlog, which leads to an asymmetry in which failure is blamed on lacks of developer performance, and success is celebrated as the full realization of the PM's vision. But “technology is the bank that gave credit”, and technical debt should be called product debt “because product took the credit to get a feature faster and must pay back by investing the time to clean up.” The alternative? “Companies today need a frame of impact. In this world-view success is defined by impact.”

- [Goodbye, Clean Code](https://overreacted.io/goodbye-clean-code/) - “My boss invited me for a one-on-one chat where they politely asked me to revert my change. I was aghast. The old code was a mess, and mine was clean! (…) I see now that my 'refactoring' was a disaster in two ways: I didn't talk to the person who wrote it; My code traded the ability to change requirements for reduced duplication”.

## Remote Work

- [The Surprising Traits of Good Remote Leaders](https://www.bbc.com/worklife/article/20200827-why-in-person-leaders-may-not-be-the-best-virtual-ones) - “the confidence, intelligence and extroversion that have long propelled ambitious workers into the executive suite are not enough online because they simply don't translate into virtual leadership. (…) Instead, workers who are organized, dependable and productive take the reins of virtual teams.” As the [source paper](https://link.springer.com/article/10.1007/s10869-020-09698-0) say it best: “virtually, the emphasis shifts from saying to doing.”

- [Things to look for when hiring remote workers](https://news.ycombinator.com/item?id=17022563) - “1. You have to adhere to employment laws within the country you're hiring from; 2. To employ someone full time, many countries require you to have a legally entity within that country; 3. Prioritize countries where we have the most interest; 4. Keep a healthy timezone overlap in each of our teams.”

- [Managing Remote Teams - A Crash Course](http://klinger.io/post/180989912140/managing-remote-teams-a-crash-course) - Compilation of easy rules and processes to bootstrap a remote team.

- [GitLab's Guide to All-Remote](https://about.gitlab.com/company/culture/all-remote/guide/) - “GitLab is the world's largest all-remote company”. Here is what it means and how it works.

- [Asynchronous Communication: The Real Reason Remote Workers Are More Productive](https://web.archive.org/web/20250506052542/https://async.twist.com/asynchronous-communication/) - “Remote workers are more productive than their office-bound counterparts.”

- [A guide to distributed teams](https://increment.com/teams/a-guide-to-distributed-teams/) - A nice wrap up on the numerous dispositions required to have a highly effective distributed team.

- [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Resources on working remotely, including job boards, coworking spaces, and a list of companies embracing the culture.

## Meetings

Two humans + a (virtual) room = a meeting.

- [Dear Manager, You're Holding Too Many Meetings](https://archive.ph/1P4FQ) - “Employee productivity was 71% higher when meetings were reduced by 40%. This is largely because employees felt more empowered and autonomous. Rather than a schedule being the boss, they owned their to-do lists and held themselves accountable.”

- [How to have great meetings, according to 200 scientific studies](https://qz.com/work/1713662/how-to-have-great-meetings-according-to-200-scientific-studies/) - A roadmap for getting meetings right.

- [Wadge's Law (of Meetings)](https://billwadge.wordpress.com/2019/03/24/laws-of-the-universe-and-teaching/) - “Before every formal meeting there's a smaller, more exclusive, less formal meeting where all the important decisions are made.”

### 1 on 1

The most important meetings you'll have are frequent 1:1s with your direct reports.

- “1on1s are the managers Swiss army knife” ([source](https://news.ycombinator.com/item?id=22341739)) - Another advice from the source: make them walk'n'talks.

- [Questions for our first 1:1](https://larahogan.me/blog/first-one-on-one-questions/) - A personal list of high-level questions from a manager.

- [1 on 1 Meeting Questions](https://github.com/VGraupera/1on1-questions) - A mega list in which most of them are great starters for conversation, some others are clearly bad ideas. A great source of inspiration nonetheless, but choose carefully.

### Standups

A staple of agile decorum, too often misused.

- [Your daily standups should be async. Here's why](https://web.archive.org/web/20200515171636/https://www.cadencework.com/blog/async-standups.html) - “Daily, real-time meetings aren't practical for remote teams” might be the best practical reason.

- [The Good, the Bad and the Ugly Standup](https://kristoff.it/blog/good-bad-ugly-standup/) - Author experienced 3 formats of stand-ups before ending with one working for his team, and concludes that “the details that make up a good meeting are subtle and the pursuit of an artificial standard of aesthetics will prevent you from doing the necessary experimentation to improve from an ugly equilibrium”.

- [We Cancelled Standups and Let The Team Build. Here's What Happened…](https://www.usehaystack.io/blog/we-cancelled-standups-and-let-the-team-build-heres-what-happened) - Team felt burned out by long, daily status update meetings masquerading as standups. Eliminating these faux standups got the team back on track.

## Facilities

The environment we work in shapes us. Perks too.

- [The impact of the 'open' workspace on human collaboration](https://sci-hub.st/https://royalsocietypublishing.org/doi/full/10.1098/rstb.2017.0239) - Open-plan offices decrease face-to-face collaboration.

- [Noise, Cognitive Function, and Worker Productivity](https://joshuatdean.com/wp-content/uploads/2020/02/NoiseCognitiveFunctionandWorkerProductivity.pdf) - “An increase of 10 dB reduces productivity by approximately 5%.”

- [The Elves Leave Middle Earth – Sodas Are No Longer Free](https://steveblank.com/2009/12/21/the-elves-leave-middle-earth-%E2%80%93-soda%E2%80%99s-are-no-longer-free/) - Company stopped providing free soda. The engineers were very upset, but it was just soda and they could afford it. But really it wasn't soda. Soda was the canary in the coal mine, triggering an exodus of its best engineers.

## Product Management

The Product Manager is supposed to be the *voice of the market*. Here are more links on the role and its reach.

- “You're the broker for a lot of unstructured information and have to fend off all kinds of disruptive influences to land even close to where you're trying to go.” ([source](https://news.ycombinator.com/item?id=19050555))

- [Awesome Product Management](https://github.com/dend/awesome-product-management) - A reference. All the missing pieces are found below.

- [Open Product Management](https://github.com/tron1991/open-product-management) - Resources, interviews, case studies, sample products & projects, communities, open source tools, free & paid services on product management, for technical people to learn the field.

- [Things Many People Find Too Obvious To Have Told You Already](https://archive.ph/vH4D1) - A set of heuristics on tech companies and the ecosystem they live in.

- [The Heilmeier Catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism) - A simple set of question which helped DARPA evaluates research programs to generate big rewards by taking big risks.

- [Akin's Laws of Spacecraft Design](https://web.archive.org/web/20250528080513/https://spacecraft.ssl.umd.edu/akins_laws.html) - Lots of wisdom about space program management.

- [How to exit vim, the Product Manager way](https://github.com/hakluke/how-to-exit-vim/blob/master/README.md#the-product-manager-way) - A satire with a grain of truth, especially the comparison between the basic vs experienced level.

### Hiring PMs

On interviewing for a PM position. And how to conduct an interview to assess a PM's abilities.

- [What Everybody Ought To Know About The Product Manager Case Interview](http://www.venturegrit.com/what-everybody-ought-to-know-about-the-product-manager-case-interview/)

- [What are frequently asked questions in product manager interviews?](https://www.quora.com/What-are-frequently-asked-questions-in-product-manager-interviews)

### Product-Market Fit

The first step to validate your product: is the market finding interest in your venture?

- [I wasted \$40k on a fantastic startup idea](https://tjcx.me/posts/i-wasted-40k-on-a-fantastic-startup-idea/) - A tale of building a product no user want to pay for. “You can't just create value for the user: that's a charity. You also can't just create value for your company: that's a scam. Your goal is to set up some kind of positive-sum exchange, where everyone benefits, including you. A business plan, according to this textbook, starts with this simple question: how will you create value for yourself and the company?”

- [David Rusenko - How To Find Product Market Fit](https://www.youtube.com/watch?v=0LNQxT9LvM0) - “Details the story of how Weebly developed one of the most popular website creation and hosting sites on the web today.”

- [Fundamentals of Product-Market Fit](https://www.holloway.com/s/rvc-fundamentals-of-product-market-fit) - A complete overview of the concept: what is product-market fit and to measuring it.

### Product Strategy

Where your product lies in the value chain and how to position it in the market.

- [Sustainable Sources of Competitive Advantage](https://www.collaborativefund.com/blog/sustainable-sources-of-competitive-advantage/) - “The ability to learn faster than your competition; to empathize with customers more than your competition; to communicate more effectively than your competition; The willingness to fail more than your competition; to wait longer than your competition”.

- [Coglode: bite-size behavioral research analysis](https://www.coglode.com) - Mostly applied behaviour insights to help you build up strategies and tactics on product, design and planning.

- [“Why does the tire company rate restaurants”](https://mobile.x.com/trevmckendrick/status/1218748974321954816) - A great example on why you should investigate complementary businesses.

- [Laws of Tech: Commoditize Your Complement](https://www.gwern.net/Complement) - A step further from the previous advice, in which is detailed an aggressive strategy to consolidate monopolies.

- Windows Vista as a prime example of a [sacrificial lamb product](https://x.com/SwiftOnSecurity/status/851861076429991937): a massive unpopular re-architecture required to pave the way for future innovative release. That's the cautionary tale of why you should be ready for intense criticism and adversity, if by chance or fate your wander down the path of monumental changes in a business software.

- Talking about Vista, Microsoft found out following its unsuccessful launch that [the #1 bug predictor is not technical, it's organizational complexity](https://augustl.com/blog/2019/best_bug_predictor_is_organizational_complexity/).

- [Osborne effect](https://en.wikipedia.org/wiki/Osborne_effect) - “A social phenomenon of customers canceling or deferring orders for the current soon-to-be-obsolete product as an unexpected drawback of a company's announcing a future product prematurely.” This is the price to pay for hasty marketing actions.

- [Reverse Engineering A Successful Lifestyle Business](https://web.archive.org/web/20230129184848/http://www.toomas.net/2017/07/18/reverse-engineering-a-successful-lifestyle-business-heres-everything-ive-learned-from-reading-indiehackers-com/) - Targets lifestyle entrepreneur, but still full of fantastic quotes from reference books on customer relation, pricing and marketing a product.

- [The Atlassian Syndrome](https://x.com/maikzumstrull/status/1309497246946406400) - Your organization will end up with Atlassian products because “their business model is: 1. Collect requirement lists from customers and prospective customers; 2. Make sure their product checks every damn box, no matter how stupid.”

- “Linear roadmaps are misleading” ([source](https://x.com/PavelASamsonov/status/1296818042928861184)).

### User-Centered Design

On how to focus on user's problem to have your product delivers value.

- [The product roadmap is dead: welcome to the age of problem roadmaps](https://medium.com/product-managers-at-work/the-product-roadmap-is-dead-welcome-to-the-age-of-problem-roadmaps-7c7745ac8ae0) - “Fall in love with your problems and not with your solutions.”

- [Kasparov's Law](https://web.archive.org/web/20220120220730/https://curatedintelligence.wordpress.com/2017/10/20/kasparovs-law/) - Weak human + Machine > Machine > Strong Human.

- [The Psychology of Design](https://growth.design/psychology/) - An extensive list of cognitive biases and design principles with examples and tips to fine-tune your product and UX.

### Product Marketing

How to find users, grow your customer base and make people talks about you product.

- [Marketing for Engineers](https://github.com/LisaDziuba/Marketing-for-Engineers) - Lots of resources to help bootstrap your marketing activities and solve practical tasks.

- [How the biggest consumer apps got their first 1,000 users](https://archive.ph/DggAq) - How the biggest apps out there started: from going to your user directly (both online and offline), creating FOMO and word-of-mouth, to build a community first and get press.

## Project Management

If product management is about *what* is to be developed of the product, then project management activities answers on *how* to deliver that development. It is all about the execution, with a particular attention to delivery critical path and planning.

But don't worry too much, every company has its own definition of the two roles, and sometimes hybrid positions.

- [Let's have no managers, instead of managers with no engineering experience](https://medium.com/hackernoon/lets-have-no-managers-instead-of-managers-with-no-engineering-experience-e8b7cd29d398) - The title is misleading, article's argument is: we don't need *project* managers if we already have *product* managers and scrum masters.

- [Best project management practices in 2018?](https://news.ycombinator.com/item?id=16377523) - There is no silver bullet.

- [Strategies for long Projects](http://benbrostoff.github.io/2019/09/28/long-projects.html) - Relentless, irrational optimism; Daily progress documentation; Compounding investments; Time budgeting.

- [Developers can't fix bad management](https://iism.org/article/developers-can-t-fix-bad-management-57) - “Why do so many software projects fail? Software development is much closer to creating a new factory than running an existing factory. (…) Software development is made up of many unknown duration tasks, this fundamentally unpredictable nature makes traditional management's predictive planning techniques particularly unsuited for software projects.”

### Specifications

- “Walking on water and developing software from a specification are easy if both are frozen.” Edward V. Berard - [Essays on object-oriented software engineering](https://www.amazon.com/dp/0132888955?&linkCode=ll1&tag=kevideld-20&linkId=559e579e5b00fde12559bbbb91ec1b95&language=en_US&ref_=as_li_ss_tl).

- [The art of destroying software](https://www.youtube.com/watch?v=Ed94CfxgsCA) - Greg Young described a good way to deal with requirements volatility: optimize from the beginning to be able to delete your code, and structure your code so that any part of it is no bigger than 1 week's worth of coding. So that any part can be re-written in 1 week.

- [Requirements volatility is the core problem of software engineering](https://stackoverflow.blog/2020/02/20/requirements-volatility-is-the-core-problem-of-software-engineering/) - “Start by accepting that change is inevitable. (…) As a consequence of this, software is never finished, only abandoned. (…) This means that no software product is ever exactly, perfectly satisfactory.”

### Estimations

Time management and planning starts with estimates, but often degenerates into deadlines.

- [Don't (guess)timate your projects, forecast with confidence](https://www.reaktor.com/blog/forecasting-method/) - “The problem with spending a lot of time on estimating is that it can feel useful, but often is so inaccurate that it hardly yields much value to the business.” The best we can do is measure and forecast.

- [Dear Startup: You have no idea how much that costs](http://kyleprifogle.com/dear-startup/) - “We are completely clueless about how long things should take.” Here is a [trick to handle expectation of unreasonable estimates](https://news.ycombinator.com/item?id=21069178).

- [Escalation of commitment](https://en.wikipedia.org/wiki/Escalation_of_commitment) - A.k.a. sunk-cost fallacy, or the rational explanation of why the hell do we still irrationally keep investing in a bad project.

- [Who are you trying to impress with your deadlines?](https://archive.ph/9Hq7N) - “There are companies where those deadlines are set in stone, and a missed deadline is next to fire. That's when the problem starts.”

- [Apple Aperture: Senior QA](https://techreflect.net/2019/12/10/aperture-senior-qa-2004-2005/) - How not to manage projects approaching deadlines: “cutting finished features, yelling at people, and working people to the point of nervous breakdowns. Then they came upon a brilliant idea: let's steal over a hundred engineers from other teams and then the project will magically get done on time.”

- [Robert "Uncle Bob" Martin talk about professionalism in software development](https://youtu.be/LmRl0D-RkPU?t=3202) - The only honest estimate is "I don't know". But you can come up with some kind of probability assessment, that will inform about the shape of the risk. This is not unlike PERT, where an activity is bounded by [optimistic, pessimistic and most-likely time](https://en.wikipedia.org/wiki/Program_evaluation_and_review_technique#Time). Now if managers don't take a range for an answer, don't fall in that trap. Tell them you're already trying as you possibly can. “And then the manager will have to do something very foreign: they'll have to manage. That's what management is: managing risk.”

- [Why software projects take longer than you think: a statistical model](https://erikbern.com/2019/04/15/why-software-projects-take-longer-than-you-think-a-statistical-model.html) - “Confirms the hunch that developers estimate the median well, but the mean ends up being much higher.”

- [Developers spend most of their time figuring the system out](https://lepiter.io/feenk/developers-spend-most-of-their-time-figuri-9q25taswlbzjc5rsufndeu0py/) - “A hand drawn picture about the current system is a belief. Decisions should never be based on beliefs. Not in engineering. (…) As software is highly contextual we cannot predict specific problems. We can only predict classes of problems.” And that's why it is hard to estimate software projects: because developer's main activity is a long process of deducting the assumptions a system is built on.

- [Software effort estimation is mostly fake research](https://shape-of-code.com/2021/01/17/software-effort-estimation-is-mostly-fake-research/) - “The NASA dataset contains 93 rows (that is not a typo, there is no power-of-ten missing), COCOMO 63 rows, Desharnais 81 rows, and (…) the China dataset contains 499 rows.”

### Tickets

- [There Are No Bugs, Just TODOs](https://almad.blog/essays/no-bugs-just-todos/) - Issue trackers needs to materialize ownership, queue position, state, task breakdown and aggressive closing. Priority, ticket type, software version, severity and long-life tickets are anti-patterns.

### Delivery

- [How I ship projects at big tech companies](https://www.seangoedecke.com/how-to-ship/) - “Shipping is a social construct within a company. Concretely, that means that a project is shipped when the important people at your company believe it is shipped.” That is the dark side of delivery, in which you optimize for visibility by upper-management for the next performance evaluation cycle.

## Agile

- [The SAFe Delusion](https://safedelusion.com) - Curated review of facts, evidence, and opinions from relevant sources without vested interests, to help decision-makers make informed choices and get better results.

- [How Big Tech Runs Tech Projects and the Curious Absence of Scrum](https://newsletter.pragmaticengineer.com/p/project-management-in-tech) - There's an interesting table in this article on the strereotypes of companies, their funding models, main engineering actors, and their central methodologies.

- [Why do some developers at Google consider Agile development to be nonsense?](https://archive.ph/pSUhM) - Because the short-term focused Scrum processes “seem suited to particular types of development, most notably consulting or contract programming, where the customer is external to the organizations, runs the show because they are paying for development, and can change their mind at any time”. Still, google engineers already practice a culture close to what looks like the original 10-points Agile manifesto. But that's it.

- [Story Points Revisited](https://web.archive.org/web/20250604004212/https://ronjeffries.com/articles/019-01ff/story-points/Index.html) - The alleged inventor of story points says they are probably a mistake.

- [Detecting Agile Bullshit](https://web.archive.org/web/20250601171312/https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF) - US Department of Defense guide to detect software projects that are really using agile development versus those that are simply waterfall or spiral development in agile clothing (“agile-scrum-fall”).

- “The fundamental problem that drives most agile failures isn't in the team's execution, it's in the business' expectations. One side is signed up for incremental delivery, and one side is set up for a fixed scope and deadline and the result is misery.” ([source](https://news.ycombinator.com/item?id=20326074))

- [Failed #SquadGoals - Spotify doesn't use "the Spotify model" and neither should you](https://www.jeremiahlee.com/posts/failed-squad-goals/) - “Why it didn't work? 1. Matrix management solved the wrong problem; 2. It fixated on team autonomy; 3. Collaboration was an assumed competency; 4. Mythology became difficult to change”.

- [Recurring opinions or productive improvements — what agile teams actually discuss in retrospectives](https://link.springer.com/article/10.1007/s10664-016-9464-2) - An 3-years analysis of a team's retrospectives, with dire conclusions: people keep forgetting what they already learned, keep discussing unsolveable problems out of their control, and keep debating opinions based on biased interpretations or incorrect understandings.

## Key Performance Indicator (KPI)

KPIs are a set of quantitative measurements at the team or organizational level, to measure the success of the business.

- “Numerical goals set for other people, without a road map to reach the goal, have effects opposite to the effects sought.” - [W. Edwards Deming](https://www.amazon.com/Out-Crisis-W-Edwards-Deming/dp/0911379010?_encoding=UTF8&qid=&sr=&linkCode=ll1&tag=kevideld-20&linkId=ec7a442a2cd5bfcfb5b6c32ea1409f2f&language=en_US&ref_=as_li_ss_tl)

- [SRE fundamentals: SLIs, SLAs and SLOs](https://cloudplatform.googleblog.com/2018/07/sre-fundamentals-slis-slas-and-slos.html) - If you are in the business of cloud services, these metrics are certainly great KPIs.

- [The 4 Worst Software Metrics Agitating Developers in 2019](https://www.gitclear.com/blog/the_4_worst_software_metrics_agitating_developers_in_2019) - The worst KPIs to track a software team output: Lines of Code, Commit Count, Issues Resolved (aka “Shipping Velocity”) and Code Churn (aka "Efficiency").

## Objectives and Key Results (OKR)

OKRs are a framework. Extending KPIs, they applies individually to each members of an organization, down to the IC level. In theory, everyone is supposed to have its own set of OKRs.

- [OKRs from a development team's perspective](https://archive.ph/dmASK) - On how OKRs articulates with a backlog.

- [Team Objectives – Overview](https://svpg.com/team-objectives-overview/) - Why OKRs might not work at your company: 1. You're still using feature teams instead of product teams; 2. Mixed-up manager and individual objectives; 3. Leadership opting-out of active management.

- “One way in which I've seen OKRs used effectively is as a defense against the type of middle or upper manager who is constantly coming up with new ideas or tasks.” ([source](https://news.ycombinator.com/item?id=19550614)) - Or how OKRs can be weaponized to prevent top managers to mess with the (already established) schedule.

- [Why individual OKRs don't work for us](https://web.archive.org/web/20250218070530/https://hrblog.spotify.com/2016/08/15/our-beliefs) - Spotify decision to stop using OKRs for individuals.

- [Google's usage of OKRs](https://news.ycombinator.com/item?id=17492038) - OKR grades are public, but not used for promotion. It was never taken very seriously there.

- [Awesome OKR](https://github.com/domenicosolazzo/awesome-okr) - There is no shortage of content on how to measure and communicate objectives.

## Training

On mentoring, education and learning.

- [Developers mentoring other developers: practices I've seen work well](https://blog.pragmaticengineer.com/developers-mentoring-other-developers/) - Discusses mentorship practices that work well engineer-to-engineer.

- [What Medieval People Got Right About Learning](https://www.scotthyoung.com/blog/2019/06/07/apprenticeships/) - “Why apprenticeships beat classrooms”.

- [Developer Roadmaps](https://roadmap.sh/roadmaps) - Very high-level guides and paths to learn different practice and tools.

## Communication

It is not only about reading, writing and talking. It encompass all the social practice and context sharing of the team's activities.

Especially a software team, which generates a huge amount of knowledge. All this knowledge is fragile and about to be lost for good. Unless you materialization it in the form of writing.

### Knowledge

On knowledge surrounding a team.

- [What senior engineers do: fix knowledge holes](http://www.mooreds.com/wordpress/archives/3232) - “This is the textbook definition of a senior engineer. You see a problem, you solve it (thoroughly), you document it and you level up your team.”

- [Chesterton's fence](https://en.wikipedia.org/wiki/Wikipedia:Chesterton%27s_fence) - “If you're considering nominating something for deletion, or changing a policy, because it doesn't appear to have any use or purpose, research its history first.” It's not we'd like to play conservative here, but because we need to fix the knowledge hole as described above.

- [You're Not Managing a Team of Software Engineers, You're Managing a Team of Writers](https://medium.com/coaching-notes/youre-not-managing-a-team-of-software-engineers-you-re-managing-a-team-of-writers-b263d3a10cc7) - Because writing software is “a creative process which is by its nature unpredictable and personal, in an environment which craves certainty, predictability and consistency.”

### Reading

Before you know how to write, you need to know how to read.

- [How to Read a Paper](http://svr-sk818-web.cl.cam.ac.uk/keshav/papers/07/paper-reading.pdf) - Outlines a practical and efficient three-pass method for reading research papers.

### Documentation

The various forms of technical writing, their structure and target audience.

- [What nobody tells you about documentation](https://www.divio.com/blog/documentation/) - There is four kinds of documentation: tutorials, how-to guides, explanation and reference. Each with their own structure and mode of writing.

- [Flying Circus Platform - Disaster recovery](https://flyingcircus.io/doc/reference/security/disaster-recovery.html#disaster-recovery) - Critical infrastructure which aims to be available 24/7 needs a [Disaster Recovery Plan](https://en.wikipedia.org/wiki/Disaster_recovery). It generally takes the form of a document providing an overview of the expected severe failures and a set of procedures on how the system and the team operating it is prepared to deal with. The one linked here is a great example of such document, and is strong evidence the team is prepared for the worse.

### Writing

General advice on how to convey meaning and clarity by mastering the style. If badly written, your documentation is likely to have poor usage and utility.

- [How to Write a Technical Paper](https://pdfs.semanticscholar.org/441f/ac7c2020e1c8f0d32adffca697bbb8a198a1.pdf) - Serves as a guideline on how to write a good technical paper, in the form of a typical journal publication.

- [Learning Technical Writing Using the Engineering Method](https://www.cs.tufts.edu/~nr/pubs/learn.pdf) - An alternative approach, involving a weekly meeting of a writing group. An interesting dynamic to gather feedback and experience.

- [Technical Writing Courses](https://developers.google.com/tech-writing) - This collection of courses and learning resources aims to improve your technical documentation. Learn how to plan and author technical documents. You can also learn about the role of technical writers in a company.

- [Algorithm for writing a scientific manuscript](https://sci-hub.st/https://iubmb.onlinelibrary.wiley.com/doi/full/10.1002/bmb.20329) - A process to guide the preparation and refinement of manuscripts.

- [The Baldwin Formula for scientific writing: writing papers and reviews](https://people.clas.ufl.edu/jlichstein/files/Baldwin_Formula_for_writing_a_scientific_paper_and_reviewing_papers.pdf) - “The most efficient way to write scientific papers is to write while you are still conducting experiments”.

- [Ten simple rules for structuring papers](https://www.biorxiv.org/content/10.1101/088278v5.full.pdf) - “Focusing on how readers consume information, we present a set of 10 simple rules to help you get across the main idea of your paper.”

- [Tips for Writing Technical Papers](https://cs.stanford.edu/people/widom/paper-writing.html) - Another set of tips, specifically using the example of a technical paper describing an improvement of an algorithm.

- [Write an Excellent Programming Blog](https://speakerdeck.com/pycon2016/a-jesse-jiryu-davis-write-an-excellent-programming-blog) - Tips on structure and style to produce great blog posts.

- [Notes on Technical Writing](https://mkaz.blog/misc/notes-on-technical-writing/) - An effective list of do and don't when it comes to writing documentation.

### Style

Once you have the right structure and content thanks to advice above, you can now copy-edit and fine tune your style with the tools below.

- [Please don't say just hello in chat](https://nohello.net/en/) - When properly used, interactive written medium allows for asynchronous communication.

- [BLUF: The Military Standard That Can Make Your Writing More Powerful](https://www.animalz.co/blog/bottom-line-up-front/) - “BLUF is a military communications acronym—it stands for “bottom line up front”—that's designed to enforce speed and clarity in reports and emails.”

- [The Punctuation Guide](https://www.thepunctuationguide.com) - Simple reference on how (and why) to use these special characters.

### Presentations

- [It's time to start writing](https://alexnixon.github.io/2019/12/10/writing.html) - On “Jeff Bezos's dotcom-era policy of banning PowerPoint within Amazon”, and how “this is neither about powerpoint nor about reading - it's about thinking.”

- [Presentation Rules](https://web.archive.org/web/20220720230551/http://www.jilles.net/perma/2020/06/05/presentation-rules.html) - A set of 16 rules to avoid boring and ineffective presentations, and have your message reach your audience.

- [The Greatest Sales Deck I've Ever Seen](https://medium.com/the-mission/the-greatest-sales-deck-ive-ever-seen-4f4ef3391ba0) - “1. Name a big change in the world; 2. Show there'll be winners and losers; 3. Tease the promised land; 4. Introduce features as "Magic Gifts"; 5. Present evidence that you can make the story come true.”

- [Some tips on public speaking](https://news.ycombinator.com/item?id=6199544) - “If you ever find yourself buffering on output, rather than making hesitation noises, just pause. People will read that as considered deliberation and intelligence.”

## Career

Now that you've proven your worth as a front-line manager, what's the next step? These articles explore the follow-up roles, from managing managers, to director, and everything in between.

- [Work at different management levels](https://larahogan.me/blog/manager-levels/) - A great progressive breakup of what it feels like to work at different levels of management.

- [Levels of abstraction in engineering management](https://medium.com/@rvprabhu/levels-of-abstraction-in-engineering-management-6bac9410e89a) - Another take on the differences between Manager, Manager of Managers, Head of Org and Head of Function.

- [My questions for prospective employers (Director/VP roles)](https://jacobian.org/2019/apr/23/questions-for-employers-director-vp/) - Be prepared to ask them as a recruiter or being asked about them for senior management roles.

- [Founder to CEO](https://docs.google.com/document/d/1ZJZbv4J6FZ8Dnb0JuMhJxTnwl-dwqx5xl0s65DE3wO8/) - You can build you own career engine, starting as a technical founder of a startup, building a great team, then grow with the company to learn and become a full-fledge CEO.

- [How title, money and scope affect your fulfillment](https://x.com/shreyas/status/1268372416427786240) - “For talented mid-career folks, when making job changes, how do you rank: 1. Title 2. Money 3. Scope”.

- [Amazon Wants to 'Win at Games.' So Why Hasn't It?](https://www.wired.com/story/amazon-wants-to-win-at-games-so-why-hasnt-it/) - “Any product manager can go between any business—from groceries to film to games to Kindle. The skillset is interchangeable. They just have to learn the particular market.”

- “Since managers are not tied to a sector (in the way nurses or musicians are), the good ones tend to go where they are paid good money and the bad ones end up wreaking havoc where they are paid at least some money. That, also, is [Baumol](https://en.wikipedia.org/wiki/Baumol%27s_cost_disease) in action.” ([source](https://news.ycombinator.com/item?id=20448929)) - Explains how the pool of professional managers gets distributed into the various sectors of the economy.

### Promotion

Stepping stones advancing a career in a company takes the form of promotions. They unlock raises, bonuses and more responsibility.

- [How do managers get stuck?](http://www.elidedbranches.com/2017/09/how-do-managers-get-stuck.html) - Identify scenario preventing managers to be promoted at the next level.

- [The Evolution of Management: Transitioning up the ladder](https://queue.acm.org/detail.cfm?id=3350548) - Describe the path and expectations at each management level.

- [If management isn't a promotion, then engineering isn't a demotion](https://charity.wtf/2020/09/06/if-management-isnt-a-promotion-then-engineering-isnt-a-demotion/) - This essay deconstruct why management ends up being seen as a promotion, how its new acquired privileges and powers creates an implicit hierarchy, which in turns creates bad incentives because of loss aversion. At the end, the only way forwards is to change the organization's culture.

- [How to discipline overeager engineer](https://web.archive.org/web/20240914135841/https://workplace.stackexchange.com/questions/145709/how-to-discipline-overeager-engineer) - Over-achieving talent is looking for a management promotion. Management does not recognize effort. Engineer become disgruntled and management is looking to discipline him. A case-study of a bad situation in which both side shows clumsiness.

- “Most people realize by their 30s that prestige is a sucker's game” ([source](https://news.ycombinator.com/item?id=11833832)) - Do not chase promotion for the title only.

- [For all you future CTOs, consider your incentive schemes carefully](https://news.ycombinator.com/item?id=24463676) - How a promotion scheme marked the end of Uber's engineering excellence and the start of what made the company turn into a bureaucratic mess.

- [How to get promoted](https://archive.ph/nlUrG) - The cynical take: “an opportunist's career advice is: ignore OKRs, switch projects well before the consequences of your decisions can be measured, act happy and easy-going, package bad news as appeals for slow systemic adjustments, don't make anyone look bad, perform rituals with enthusiasm, grow headcount faster than baseline, let work invent itself, follow management fashions, avoid acute failures, believe this sincerely.”

### Performance Reviews

Reviews and performance evaluations are the tool of the trade to unlock promotions. As a manager, your going to write and instrument them for your team members to get the raise they deserve. And getting through them as any other employee to advance your career.

- [Get your work recognized: write a brag document](https://jvns.ca/blog/brag-documents/) - There's this idea that, if you do great work at your job, people will (or should!) automatically recognize that work and reward you for it with promotions / increased pay. In practice, it's often more complicated than that.

- [Incentive Pay Considered Harmful](https://www.joelonsoftware.com/2000/04/03/incentive-pay-considered-harmful/) - “Incentives (or bribes) simply can't work in the workplace. (…) Most software managers have no choice but to go along with performance review systems that are already in place. If you're in this position, the only way to prevent teamicide is to simply give everyone on your team a gushing review”.

- “If anything in your performance review is a surprise, then I have failed as a manager.” ([source](https://news.ycombinator.com/item?id=17249767)).

- “This is what I loved about working at Netflix. We didn't have performance reviews. It was assumed that your performance was good to excellent, otherwise you wouldn't be working there anymore. You had a constant feedback loop with your manager on performance, but nothing was ever formal.” ([source](https://news.ycombinator.com/item?id=23861960)).

- “The system a software developer works in shapes their performance so much more than individual differences.” ([source](https://news.ycombinator.com/item?id=21972033)).

## Compensation

It's not only about the salary, but the whole package: equity, bonuses, perks, and the dealings around all of these.

### Salary

- [levels.fyi](https://www.levels.fyi) - Compares salary range and compensation charts across big tech companies.

- [benefits.fyi](https://benefits.fyi) - Same as above, but trying to evaluate the values of benefits across companies.

- [L8-L10 salaries at AWS](https://news.ycombinator.com/item?id=21823987) - A reference point to what \$M+ compensation packages looks like.

- [Why new hires often get paid more than existing employees](https://web.archive.org/web/20250415095157/https://bloomberry.com/why-new-hires-often-get-paid-more-than-existing-employees/) - “and why the best way to get a bigger pay is to move to a new job.”

- [Salaries never stay secrets forever. Hiding them only delays the inevitable.](https://news.ycombinator.com/item?id=2439478)

### Equity

- “Never accept a lower salary in exchange for equity.” ([source](https://news.ycombinator.com/item?id=21868845))

- [On VC funding and huge growth](https://news.ycombinator.com/item?id=17448035) - “Startups need an exit strategy. (…) The idea is to raise money fast, hire experienced people for ancillary services and develop the application in a way so that it is able to hold up till IPO. Defer all costs for post IPO.” So from this angle, the only reason to join a startup is for future money windfall.

- [Equity Compensation](https://www.holloway.com/g/equity-compensation) - Stock options, RSUs, job offers, and taxes—a detailed reference, including hundreds of resources, explained from the ground up and made to be improved over time.

- “Public RSUs for stock you can sell immediately on the open market are fantastic.” ([source](https://news.ycombinator.com/item?id=22386728)).

## Politics

Here we are, at the intersection of power and influence lies the political game. If its nature and intensity is sourced from the company's core culture and history, you're unfortunately unlikely to avoid it past a certain hierarchical level. Be prepared.

- [About corporate middle management](https://news.ycombinator.com/item?id=28336658) - “As a manager in a large corporation you are expected to be an aligner. (…) You have to manage frictions and strive to make the people above you look good.”

- “Politics is how a middle manager runs interference and creates distractions to make sure you can't see over, around, or through them, and that the people behind them closer to the money can't see you.” ([source](https://news.ycombinator.com/item?id=22808280)).

- [HiPPO FAQ](https://exp-platform.com/hippo/) - HiPPO stands for “Highest Paid Person's Opinion”, a trait of dysfunctional culture, in which power politics trumps data.

- [The Prince](https://en.wikipedia.org/wiki/The_Prince) - Machiavelli's ideas on how to accrue honor and power as a leader. Resorting to that level of politics in a company is a sure way to render the culture highly toxic, as well as corrupting and demoralizing the organization at all levels.

- [The Gervais Principle](https://www.ribbonfarm.com/the-gervais-principle/) - A cynical, bleak, but still fascinating take on the management ladder, based on *The Office*.

- [The 48 Laws of Power](https://www.amazon.com/dp/0140280197?&linkCode=ll1&tag=kevideld-20&linkId=bf129d7f7a3495a445cf2bf667d3d3c6&language=en_US&ref_=as_li_ss_tl) - By Robert Greene. Can teach you how to cover your ass and be effective in a highly political org.

- [7 Rules of Power](https://www.amazon.com/Rules-Power-Surprising-but-True-Advice-Advance/dp/1637741227?_encoding=UTF8&qid=&sr=&linkCode=ll1&tag=kevideld-20&linkId=1a2a7107ccffa7b19e03cdb88e616daf&language=en_US&ref_=as_li_ss_tl) - By Jeffery Pfeffer. Tells you [how to play office politics if success in the workplace is the only thing you care about](https://news.ycombinator.com/item?id=39084979).

- [Selectorate theory](https://en.wikipedia.org/wiki/Selectorate_theory) - “In selectorate theory, three groups of people affect leaders. These groups are the nominal selectorate, the real selectorate, and the winning coalition. (…) To remain in power, leaders must maintain their winning coalition.”

- [Circulation of elite](https://en.wikipedia.org/wiki/Circulation_of_elite) - “Changes of regime, revolutions, and so on occur not when rulers are overthrown from below, but when one elite replaces another.”

- [The Rules for Rulers](https://www.youtube.com/watch?v=rStL7niR7gs) - “Smart key supporters will always watch the balance of power, ready to change allegiance if the ruler look to be the loser in a shifting web of alliances. (…) Buy all the loyalty you can, because loyalty, in dictatorial organizations of all kinds, is everything.”

- “Playing the game well is now front and center” ([source](https://news.ycombinator.com/item?id=21925738)), or why the [key practices for achieving large professional goals](https://nodramadevops.com/2019/12/key-practices-for-achieving-large-professional-goals/) is missing the parts about office politics.

- [“Company I've worked for had manager who tried to ship features over the weekend with a ragtag team of developers who don't understand why that's a bad idea.”](https://news.ycombinator.com/item?id=22285123) - Tactics of hustling managers, and how the company reacting to that kind of manager makes or break a good place to work.

- [Making Nice or Faking Nice? Exploring Supervisors' Two-Faced Response to their Past Abusive Behavior](https://onlinelibrary.wiley.com.sci-hub.st/doi/10.1111/peps.12424) - “It behooves organizations that want to develop highly authentic supervisors or organizational climates to seek to hire supervisors that are lower (or at least not higher) on symbolized moral identity.”

- “The actual power wielded by a high level executive is usually inversely proportional to the size of the organization they manage.” (source: [comment](https://news.ycombinator.com/item?id=20260498) on [Why large companies are so difficult to rescue](https://news.ycombinator.com/item?id=20260114)).

- “Cutting costs gets you a raise. Delivering a big project is a path to promotion.” ([source](https://news.ycombinator.com/item?id=21230771))

- “You know your game fails when you read in the news about the feature you are supposed to have.” ([source](https://news.ycombinator.com/item?id=20220484)). A team learning about its roadmap at the same time of the general public is a sure sign something is wrong.

- “In a highly political environment there are two ways to create change, one is through overt manipulation, which is to collect political power to yourself and then exert it to enact change, and the other is covert manipulation, which is to enact change subtly enough that the political organism doesn't react. (sometimes called "triggering the antibodies").” ([source](https://news.ycombinator.com/item?id=5541517)).

- [Power Bends Light](https://honkathon.com/2019-08-18-power-bends-light/) - “Most things at most startups are perpetually on fire, but if you can accept that, there is a lot to like. One well-known one: at a fast-growing startup, a hard-working, talented person who has some support from company leadership can often acquire an impressive title (or at least a lot of de facto power) very quickly.”

- “It's common to promote someone to just get rid of that person :) Sometimes promoting is just easier that firing.” ([source](https://news.ycombinator.com/item?id=21767734)).

- [US spy manual has tips for coping with toxic bosses](https://qz.com/work/1717297/how-to-cope-with-a-toxic-boss-according-to-a-us-spy-manual-from-wwii/) - Derived from WWII-era [Simple Sabotage Field Manual](https://archive.org/details/SimpleSabotageFieldManual), a classic read to spot harassing and demoralizing behaviors.

- [4 Clues to Identify a Destructive Leader](https://www.tilt365.com/the-tilted-edge/blog/post/toxic-leadership-destructive-characteristics-examples) - “1. I'm kind of a big deal! 2. None of this is my fault! 3. Just do what I say! 4. Trust me; I'm never wrong.”

- “The president of MIT told me that tenure was not about research, productivity, or merit. It was about office politics & being liked by your department.” ([source](https://threadreaderapp.com/thread/1494369809538195456.html)) - Contemplating to switch from the industry? The grass is not greener in academia. Given a significant size, any organization comes with its political game.

## Re-organizations

As a manager, you have direct responsibility of the structure of the team. Past a certain size (around 8 to 12 depending on sources), you no longer have time to work with direct ICs, so you need to re-organize the team.

At a company level, re-orgs are mostly strategic and your influence on them depends on your political acumen.

### Team-level

- [Why it's difficult to build teams in high growth organisations](https://jchyip.medium.com/why-its-difficult-to-build-teams-in-high-growth-organisations-e1aee8446337) - Describes 3 different approach a manager can take to accommodate new people in the team: 1. Sink or Swim; 2. Split and Absorb; 3. Absorb and Split.

- [Teams are like bread](https://blog.jessitron.com/2019/06/15/teams-are-like-bread/) - Resonates with the *Absorb and Split* strategy discussed above: “if you have one team where the magic is flourishing, don't kill it. Feed it, grow it, and let it be a source of further strong teams. No rushing.”

- [Building a data team at a mid-stage startup: a short story](https://erikbern.com/2021/07/07/the-data-team-a-short-story.html) - Story of a manager trying to distill the concepts of a data-driven company while growing a tiny team of 3 people. Each step covers the evolution of the technical pipeline and interactions with existing stakeholders.

- [If I Close My Data Centers, What About the People/Jobs Lost?](https://news.ycombinator.com/item?id=17329028) - F50's data centers being migrated to commercial cloud provider. But what about the people currently doing legacy stuff? The answer: retrain.

- “This is the managerialist dream. To replace employees' judgement and competence with a process and management methodology. (…) It never works.” ([source](https://news.ycombinator.com/item?id=20881308)). And why the retraining answer above is the best one.

- [I've Built Multiple Growth Teams. Here's Why I Won't Do It Again.](https://conversionxl.com/blog/dont-build-growth-teams/) - “Few folks understand probability, and most executives don't care about the data, regardless of what it says.”

### Company-level

- [The SaaS Org Chart](https://archive.ph/vOuLQ) - Blueprints of an organization at each stage of its 50/125/400/1000-employees stages, with typical ratios and ARR.

- “If you have dealt with large, completely incompetent organizations and wondered how the hell they actually keep going - theres your answer. If built correctly it's genuinely difficult to mess things up.” ([source](https://news.ycombinator.com/item?id=20533922)). I.e. the structure of the organization is quintessential to its longevity.

- [A high-resilience org chart](https://jessitron.com/2021/05/26/a-high-resilience-org-chart/) - “If you know what problem you're solving and you know how to solve it, a bureaucratic organization will do. Stick with what you know. If you're writing software, that's a generative activity. You need a high-resilience org chart. Fewer boxes, more flexibility.”

- [An Alternative Approach to Re-Orgs At Your Company](https://caseyaccidental.com/alternative-approach-re-orgs/) - “Trying not to repeat re-org mistakes, we started working on a structure that would make the re-org act like a feedback-fueled progress driven by the teams instead of by people above them.” This is an attempt to extract from the ground up signals pointing to inadequate structure. My cautionary tale: this might only work up to a point depending on the company's culture.

- “When everything is great success, people behind that success shadow the people who could make success in the future. (…) Netflix is great example of how to do big transition right. Netflix was in renting DVDs by mail business. When the decision to move to streaming was made, Netflix CEO did not allow managers who responsible for DVD renting business into meetings where the future was planned.” ([source](https://news.ycombinator.com/item?id=21395557)).

- [Speaking Truth to Power: Reflections on My Career at Microsoft](https://onezero.medium.com/speaking-truth-to-power-reflections-on-a-career-at-microsoft-90f80a449e36) - After 3 decades in a deeply flawed company, the author comes to a humble conclusion: leaders should embodies the value of their employees. Not the other way around. “Changes at the top — not speeches, training or hashtags — make the most cultural impact. If you want real and lasting cultural change, sweep away the made-men who succeeded under the previous culture and promote the people who look, act, and think more like their employees than their managers.”

### Acquisition

A special case of re-org, that might take the form of inclusion, absorption or dissolution of the acquired company.

- [How the Digg team was acquihired](https://lethain.com/digg-acquihire/) - Acqui-hire of a whole team can be seen as a type of reorg. In which managers will have to negotiate the new employment contracts in bulk in one or two days: “Because acquihires are “star” oriented, if you're a senior leaders who doesn't explicitly refuse to move forward, pressure will converge on you from all sides”.

## Health

- [Good sleep, good learning, good life](https://supermemo.guru/wiki/Good_sleep,_good_learning,_good_life) - An e-book-sized synthesis on sleep research “with a view to practical applications, esp. in people who need top-quality sleep for their learning or creative achievements.”

### Holidays

- [Should we take a few long holidays, or lots of short ones?](http://timharford.com/2019/09/should-we-take-a-few-long-holidays-or-lots-of-short-ones/) - Short ones. “Reason one: holiday memories tend to depend not on how long the holiday was, but on the intensity of the experiences. Reason two: a change of activity can be a spur to creativity. Reason three for taking a short break: if we need rest to prevent exhaustion, a single, long vacation won't do the trick.”

### Stress

- [The Toxic Handler: Organizational Hero — and Casualty](https://www.companiesalive.com/toxichandlers-healthandhealing-lifecoaching-miami-leadershiptraining.htm) - “toxic handler, a manager who voluntarily shoulders the sadness, frustration, bitterness, and anger that are endemic to organizational life. Although toxic handlers may be found at every level in organizations, many work near the top”.

- [Manager Energy Drain](https://larahogan.me/blog/manager-energy-drain/) - “How do I handle how tired I am as a manager? 1. Defrag your calendar; 2. Delegate messy and unscoped projects; 3. Say no.”

- [How Slack Harms Projects](https://www.silasreinagel.com/blog/2019/08/12/how-slack-harms-projects/) - “Promote a false sense of urgency, destroy focus, allow for bypassing project prioritization, strip away essential business context, encourage poorly thought-out communication”. To remediate this, see [How to Use Slack and Not Go Crazy](https://pspdfkit.com/blog/2018/how-to-use-slack-and-not-go-crazy/) article.

- [Examples of harassments](https://news.ycombinator.com/item?id=21856352) - How a jealous boss, who felt either betrayed or ridiculed, bullied a capable employee to force him out. Don't be that kind of asshole boss.

### Burnout

- [How shitty job crush your soul, then lead to burnout](https://news.ycombinator.com/item?id=7789438) - “Burnout is a very serious situation. If you burn yourself out hard, it will be difficult to be effective at any future job you go to, even if it is ostensibly a wonderful job. Treat burnout like a physical injury.”

- “Burnout is caused by resentment. (…) No. Burnout is caused when you repeatedly make large amounts of sacrifice and or effort into high-risk problems that fail. It's the result of a negative prediction error in the nucleus accumbens. You effectively condition your brain to associate work with failure.” ([source](https://news.ycombinator.com/item?id=5630618)).

- [If You're So Successful, Why Are You Still Working 70 Hours a Week?](https://archive.ph/78aEf) - “Our tendency to overwork and burn out is framed by a complex combination of factors involving our profession, our organization, and ourselves. At the heart of it is insecurity.”

- [What Happens When Your Career Becomes Your Whole Identity](https://archive.ph/yqPAD) - “A particular confluence of high achievement, intense competitiveness, and culture of overwork has caught many in a perfect storm of career enmeshment and burnout.”

- “In my experience extreme workaholism can often be a way to avoid or defer major life decisions that someone doesn't want to make or even consciously recognize. (…) Eventually the debt comes due but sometimes not until many decades later.” ([source](https://news.ycombinator.com/item?id=21900054))

- [Burnout From an Organizational Perspective](https://ssir.org/articles/entry/burnout_from_an_organizational_perspective) - “Extensive research by the military on sustainable performance in stressful conditions teaches that leaders should become champions of health, rather than taskmasters.” Describe the symptoms of toxic organizations and how managers can protect their teams from systemic burnout.

- [Avoiding burnout as an ambitious developer](https://stackoverflow.blog/2020/01/13/avoiding-burnout-as-an-ambitious-developer/) - “Be willing to say no; Know what you don't want; Use your energy level realistically; Be kind to your future self”.

- [Psychology Today: How Programmers Can Avoid Burnout](https://www.psychologytoday.com/us/blog/dear-life-please-improve/202008/how-does-your-tech-job-burn-you-out) - “Veteran software developers often recommend to: 1. Work at a place where you can grow; 2. Build transferable skills; 3. Have creative outlets and create a space to focus on yourself, switch off, and relax; 4. Of course, there's always the nuclear option: make your money and get out.”

- [Average tenure of a CISO is just 26 months due to high stress and burnout](https://www.zdnet.com/article/average-tenure-of-a-ciso-is-just-26-months-due-to-high-stress-and-burnout/) - “Today, CISO jobs come with low budgets, long working hours, a lack of power on executive boards, a diminishing pool of trained professionals they can hire, but also a constant stress of not having done enough to secure the company's infrastructure against cyber-attacks, continuous pressure due to newly arising threats, and little thanks for the good work done, but all the blame if everything goes wrong.”

## Setbacks and Failures

- “What does not kill me makes me stronger”, Friedrich Nietzsche - Brutal, but with a grain of truth.

- “It is not the strongest of the species that survives, nor the most intelligent that survives. It is the one that is most adaptable to change.” Charles Darwin - [A quote](https://quoteinvestigator.com/2014/05/04/adapt/) to tame the one above.

- [Early-career setback and future career impact](https://www.nature.com/articles/s41467-019-12189-3) - “Despite an early setback, individuals with near misses systematically outperform those with narrow wins in the longer run.”

- [Huge success in business is largely based on luck](https://theconversation.com/huge-success-in-business-is-largely-based-on-luck-new-research-130843) - “Management research and education should focus on prescriptive theories that can help business practitioners move from 'incompetent to OK', rather than focusing on those that address how to move from 'good to great'.”

- [How Complex Systems Fail](https://stuff.mit.edu/afs/athena/course/2/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf) - “Short treatise on the nature of failure; how failure is evaluated; how failure is attributed to proximate cause; and the resulting new understanding of patient safety”.

<!--lint disable double-link-->

- [Normalization of deviance](https://danluu.com/wat/) - Explores how the factors accounting for disasters accumulates unnoticed until it's too late. This has been studied on other fields, but not in software engineering.

<!--lint enable double-link-->

- [Steve Jobs explains - Why companies fail?](https://www.youtube.com/watch?v=B-fAinNDbQU&t=6s) - On how sales and marketing takes over product focused companies.

- [The failure of Scaling Etsy](https://archive.ph/h07CR) - When a company lacks technical leadership: developers waste time in costly refactors, over-engineered systems, and ends up detached from the business and product.

## Exits

Sometimes, you just have to call it quits.

- [Why I Rejected My Manager](https://archive.ph/NxLVP) - “I understand now why the saying is: people leave managers, not companies.”

- [Colleague is leaving. How to investigate what went wrong?](https://news.ycombinator.com/item?id=20786755) - “Most of the time people leave bosses, not the job or the company.” And why you're unlikely to get any substantial insights from exit interviews. ([source](https://news.ycombinator.com/item?id=20787874))

- “*People do get pissed off in clusters* is the best description of a team/company meltdown that I've ever seen.” ([source](https://news.ycombinator.com/item?id=19755001))

<!--lint disable double-link-->

- “Something I've seen multiple times is that, when a VP leaves, a company will become a substantially worse place to work, and it will slowly dawn on people that the VP was doing an amazing job at supporting not only their direct reports, but making sure that everyone under them was having a good time.” ([source](https://danluu.com/wat/#fn:P))

<!--lint enable double-link-->

- “Next time your favorite manager and tech lead quit the company, ask them why.” ([source](https://news.ycombinator.com/item?id=21767843)).

- “[Good business mafias form](https://archive.ph/9Osm2) when there's a group of people who all have to quit their job for reasons that are exogenous to their performance. In the case of Paypal, it was an acquisition; at Tiger Management, a few years of underperformance; at Drexel Burnham Lambert, an indictment. In Reliance's case, the core group of early employees fled the port of Aden due to unrest and the withdrawal of the British.” ([source](https://archive.ph/WCxsu)) - And why mass exodus might be an opportunity for great new ventures.

- “It was my experience that no single departure had any effect. Mass departures did, trends did, but one person never did, even when that person was a founder.” ([source](https://news.ycombinator.com/item?id=4324615)).

- [As an Employee, You Are Disposable](https://nelson.cloud/as-an-employee-you-are-disposable/) - “It's okay to like your job and employer. Just understand that, as an employee, you are disposable.” Also: “This is not news. If you are loyal to your employer and do not own a significant part of the organization, then you should take a good hard look at why you're loyal -- and whether or not your employer is loyal to you in return.” ([source](https://news.ycombinator.com/item?id=40943681)).

- [P.T.'s Hidden Meaning](https://www.youtube.com/watch?v=yr4RvdREwl8) - How Hideo Kojima creatively used a playable teaser as a way to bypass NDA and to tell the story about the turmoil at Konami leading to his leaving of the company. But that only works if you're an influential and popular game designer.

- [Management Challenges for the 21st Century - Managing Oneself](https://www.thecompleteleader.org/sites/default/files/imce/Managing%20Oneself_Drucker_HBR.pdf) - “There is a great deal of talk today about the "mid-life crisis" of the executive. It is mostly boredom. At age forty-five most executives have reached the peak of their business career and know it.” In paragraph Ⅴ, you'll find why knowledge workers needs to manage themselves, and plan for the second half of their life.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](.github/contributing.md) first.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-engineering-team-management/blob/main/assets/awesome-management-header.png) is based on a modified [photo taken in November 2017](https://unsplash.com/photos/6dDHofabCQ8) by [Werner Du plessis](https://unsplash.com/@werner01).

<!--lint disable no-undefined-references-->

<a name="intro-quote-def">[1]</a>: [*Peopleware: Productive Projects and Teams, 1987*, page 34](https://www.amazon.com/dp/0321934113?&linkCode=ll1&tag=kevideld-20&linkId=9a6c692819b070f38feb70816e6635ab&language=en_US&ref_=as_li_ss_tl) (Addison-Wesley Professional, 3rd edition, 2013). [[↑]](#intro-quote-ref)
