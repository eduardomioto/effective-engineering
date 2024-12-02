# Effective Engineering  ![GitHub](https://img.shields.io/github/license/eduardomioto/effective-engineering?style=flat-square) ![GitHub contributors](https://img.shields.io/github/contributors/eduardomioto/effective-engineering?color=%232E8DCD&style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/eduardomioto/effective-engineering?style=flat-square)


## Table of Contents
1. [The Effective Engineering](#effective-engineering)
2. [Managerial Accountability](#managerial-accountability)
    1. [Reducing Interruptions](#reducing-interruptions)
    2. [Flow State](#flow-state)
    3. [Possible Solutions](#possible-solutions)
3. [Confidence Factor](#confidence-factor)
    1. [Psychological safety and Confidence](#psychological-safety)
4. [Product Manager Accountability](#product-manager-accountability)
    1. [Prioritize Regularly](#prioritize-regularly)
5. [Engineer Accountability](#engineer-accountability)
    1. [Automated Testing](#automated-testing)
    2. [Repay Technical Debt](#repay-technical-debt)
    3. [Reduce Operational Complexity](#reduce-operational-complexity)
6. [Lead Engineer Accountability](#lead-engineer-accountability)
7. [Frameworks about Engineering Effectiveness](#frameworks)
    1. [SPACE: A Framework for Understanding Developer Productivity](#space-framework)
8. [Supportive Metrics](#supportive)
   1. [DORA Metrics](#dora)
9. [Supportive Practices](#practices)
   1. [Semantic Versioning](#versining)
   2. [Git Flow and Feature Branch](#gitflow)
   3. [Feature Flags](#featureflags)
   4. [Environments Stability](#environment)
   5. [Continuous Delivery](#cd)
   6. [Architectural Decision Records / ADR](#adr)
10. [Resources](#resources)
11. [Contributors](#contributors)
12. [References](#references)
13. [Inspirations](#inspirations)

## The Effective Engineering <a name="effective-engineering"></a>

In a broader scope, Effectiveness is the capability of producing a desired result or the ability to produce desired output. When something is deemed effective, it means it has an intended or expected outcome, or produces a deep, vivid impression.[1]

However, the software industry has a different approach to define Effectiveness. The effectiveness in Software Engineering is directly associated to the Impact Produced by an engineer, so the outcome produced by this person. [2]

Measuring and improving engineering effectiveness is a precondition to building a healthy engineering team: attracting talent, building an efficient system where they can produce their best work, and retaining that talent. What teams do with their time is the primary factor in determining its output. Even if you hire the best engineers, if they spend all their time on the wrong things, or they’re constantly interrupted while trying to do the right things, the team won’t succeed. [3]

There is also agreement that developer productivity is necessary not just to improve engineering outcomes, but also to ensure the well-being and satisfaction of developers, as productivity and satisfaction are intricately connected. [9] [10] [11]

## Managerial Accountability <a name="managerial-accountability"></a>

Managers should be held accountable for building productive teams. In particular, managers should both provide a system to measure productivity and lead the changes that need to happen. [3]

As a manager, it can be hard to remember what it was like to need primarily Maker Time to succeed because a manager’s role can be significantly more interrupt-driven.  To be most effective engineers require large blocks of uninterrupted time and for them any interruptions are disproportionately costly. [3]

#### Reducing Interruptions <a name="reducing-interruptions"></a>

Software projects typically require engineers to have several concepts and context in their memory to make forward progress. A task might require you to read a ticket with requirements, look at log output, read related code before you're able to start making changes. Any interruption causes an expensive context switch that forces you to start this whole process over. [3] 

#### Flow State <a name="flow-state"></a>
Flow state or being in the zone means having no worries about imminent interruptions - you’re fully in the moment and at your most productive. Fragmentation and interruptions kill flow state because context switching is so expensive for engineers. This state is typically where the most work gets done and it’s when the hardest problems can get solved. [3]

Because it takes time to get enough context to make forward progress on a task, we’ve found that the minimum unit of time that allows for flow state is 2 hours. Two hours of uninterrupted time is called Maker Time. It is certainly possible to achieve flow state in shorter periods of time but that’s typically an exception. Periods longer than 2 hours can also lead to higher quality flow states. [3]

#### Possible Solutions <a name="possible-solutions"></a>

A very important component of the Netflix Freedom & Responsibility culture [4] is “Context, not Control”, in other words, “high performance people will do better work if they understand the context.” In practice, this means that if your team is aware of their purpose and how it aligns to the company’s and/or organization’s priorities, they will make good decisions and will accomplish great things, without a “helicopter manager” hovering over their heads and dictating everything that must be done.  When the team has the appropriate context, we trust them to make decisions that are in the best interest of Netflix. We provide team members the appropriate context around projects and priorities so that they can identify what’s most important in their queue of projects and tasks. [5]

Adopt an OOPS rotation. Many teams (ours included) at Netflix subscribe to the “operate what you build” approach to DevOps. We use an OOPS (Operations, On-Call and Partner Support) rotation, whereby we have one member of the team on-call for a week at a time to handle all production issues, pipeline management, partner support questions and anything else out of the ordinary that arises.  This allows the other members of the team to focus on project work and avoid interruptions and context switching. We build the OOPS week into each person’s project schedule and the intent is that no project work is done during the week that someone is on-call. If the on-call person does happen to have excess bandwidth, we try to focus on paying off technical debt and ensuring alignment across the dozen or so services that we support. [5]

## Confidence Factor <a name="confidence-factor"></a>

Developing confidence and security in a competitive, exponential and agile environment is not an easy task. That's why Fabossi created the concept of the 4 dimensions, which will lead you and your team to the best results: [6]

- _1st dimension: Self-confidence_. Since no one can give what they don't have, knowing and trusting yourself is the starting point for building trusting relationships, a journey that involves self-knowledge and authenticity. [6]

- _2nd dimension: Personal trust_. Our actions need to be in line with our words. This dimension is linked to our ethics, our values and our principles, and is shown in the attitudes we take on a daily basis. [6]

- _3rd dimension: Interpersonal trust_. We are relational beings, we live on relationships. Empathy, equity and genuine interest are fundamental ingredients for this dimension to be established. [6]

- _4th dimension: Achievement confidence_. It involves the skills that lead us to achieve extraordinary results. But when talking about trust, the ways to achieve them are as important as the results. Aimed at professionals who occupy leadership positions or who act as agents of motivation and engagement of people on a day-to-day basis, The trust factor will help you to find the way to become a true leader. [6]

### Psychological safety and Confidence <a name="psychological-safety"></a>

In a study conducted by Google, the researchers had to determine how to quantitatively measure effectiveness. They looked at lines of code written, bugs fixed, customer satisfaction, and more. But Google’s leaders, who had initially pushed for objective effectiveness measures, realized that every suggested measure could be inherently flawed - **more lines of code aren’t necessarily a good thing and more bugs fixed means more bugs were initially created**. [7]

Instead, the team decided to use a combination of qualitative assessments and quantitative measures. For qualitative assessments, the researchers captured input from three different perspectives - executives, team leads, and team members. While they all were asked to rate teams on similar scales, when asked to explain their ratings, their answers showed that each was focused on different aspects when assessing team effectiveness. [7]

Executives were most concerned with results (e.g., sales numbers or product launches), but team members said that team culture was the most important measure of team effectiveness. Fittingly, the team lead’s concept of effectiveness spanned both the big picture and the individuals’ concerns saying that ownership, vision, and goals were the most important measures. [7]

Using input from executives across the globe, the research team identified 180 teams to study (115 project teams in engineering and 65 pods in sales) which included a mix of high- and low-performing teams. The study tested how both team composition (e.g., personality traits, sales skills, demographics on the team) and team dynamics (e.g., what it was like to work with teammates) impact team effectiveness. Ideas were pulled from existing research as well as Google’s own experience with what makes an effective team. [7]

They conducted hundreds of double-blind interviews with leaders to get a sense of what they thought drove team effectiveness. The researchers then looked at existing survey data, including over 250 items from the annual employee engagement survey and gDNA, Google’s longitudinal study on work and life, to see what variables might be related to effectiveness. [7]

With all of this data, the team ran statistical models to understand which of the many inputs collected actually impacted team effectiveness. Using over 35 different statistical models on hundreds of variables, they sought to identify factors that: [7]

- _impacted multiple outcome metrics, both qualitative and quantitative_
- _surfaced for different kinds of teams across the organization_
- _showed consistent, robust statistical significance_

The researchers found that what really mattered was less about who is on the team, and more about how the team worked together. **In order of importance**: [7]

- _Psychological safety_: Psychological safety refers to an individual’s perception of the consequences of taking an interpersonal risk or a belief that a team is safe for risk taking in the face of being seen as ignorant, incompetent, negative, or disruptive. In a team with high psychological safety, teammates feel safe to take risks around their team members. They feel confident that no one on the team will embarrass or punish anyone else for admitting a mistake, asking a question, or offering a new idea. [7]

- _Dependability_: On dependable teams, members reliably complete quality work on time (vs the opposite - shirking responsibilities). [7]

- _Structure and clarity_: An individual’s understanding of job expectations, the process for fulfilling these expectations, and the consequences of one’s performance are important for team effectiveness. Goals can be set at the individual or group level, and must be specific, challenging, and attainable. Google often uses Objectives and Key Results (OKRs) to help set and communicate short and long term goals. [7]

- _Meaning_: Finding a sense of purpose in either the work itself or the output is important for team effectiveness. The meaning of work is personal and can vary: financial security, supporting family, helping the team succeed, or self-expression for each individual, for example. [7]

- _Impact_: The results of one’s work, the subjective judgement that your work is making a difference, is important for teams. Seeing that one’s work is contributing to the organization’s goals can help reveal impact. [7]

![google-rework-psychological-safety](https://user-images.githubusercontent.com/3407254/207102728-35478f25-6cc2-4dce-95d1-0d792e107102.png)

## Product Manager Accountability <a name="product-manager-accountability"></a>

### Prioritize Regularly <a name="prioritize-regularly"></a>

In accordance with Edmond Lau [2][8]:
- Opportunity cost of working on wrong ideas can set back growth by years.
- Prioritize tasks based on ROI.
- Regular prioritization is high leverage activity.
- Focus on what directly produces value.
- Learn to say no.
- Find ways to get into flow. “A state of effortless concentration so deep that they lose their sense of time, of themselves, of their problems.”
- When possible, preserve larger blocks of focused time in the team schedule.
- Limit the amount of Work in Progress.
- Cost of context switching is high.
- Prioritizing is difficult.
- Prioritization is high leverage. It has huge impact on your ability to get right things done.

## Engineer Accountability <a name="engineer-accountability"></a>

### Automated Testing <a name="automated-testing"></a>
Invest time on Unit Testing [2][8]:
- Unit test cases and some integration testing provide a scalable way of managing growing codebase.
- A suite of extensive and automated tests can reduce overall error rates by validating the quality and by safeguarding against regressions.
- Tests also allow engineers to make changes, especially large refactorings, with significantly higher confidence.
- Despite its benefits, it can be difficult to foster a culture of automated testing.
- Focus on high leverage tests.
- Writing more tests, creating a virtuous feedback cycle and saving more development time.
- Automated test cases lead to higher confidence when refactoring.
- Write test cases when the code is fresh in mind.
- Don’t be dogmatic about 100% code coverage.
- Value of tests increases over time and cost to write goes down.

### Repay Technical Debt <a name="repay-technical-debt"></a>
Invest time to Repay Technical Debt [2][8]:
- Technical debt refers to all the deferred work that’s necessary to improve the health and quality of the codebase and that would slow us down if left unaddressed.
- Accumulating technical debt is fine as far as it is repaid within time.
- Refactor often.

#### The 6 Types of Technical Debt
Tech debt often falls under one enormous umbrella term that includes everything from latency speeds, to security vulnerabilities, to refactoring, to much more. Instead of the umbrella term, you need to understand the different types of technical debt you might be taking on to use it is a strategy lever. This classification will help individuals across the organization better understand what type of tech debt is at hand and what's involved, as opposed to talking ambiguously about 'tech debt.' [12]

The 6 key types of technical debt that teams encounter are: [12]
- Maintenance debt
- Developer efficiency debt
- Stability debt
- Security debt
- Technical product debt
- Decision debt

![image](https://user-images.githubusercontent.com/3407254/208244652-1f57bc60-279a-4001-a5e0-86377c21dd0a.png)

Note that a piece of tech debt can fall across more than a single category, making it a potentially more critical piece of work to address. [12]

##### Maintenance debt
When teams don't keep up with updates to tech work. This includes not deleting dead code at the right time after an experiment launch / feature rollout / unshipping event, updating libraries, commenting on pieces of code for context, and documenting implementation decisions. [12]

##### Developer efficiency debt
When companies do not have the right tests, monitoring, and/or alerting in place on the product. This is a common type of debt, where engineering workflows are highly inefficient, deployment and build times can take several hours or days, and developers lack the tools that allow them to detect technical issues before they go live in production. [12]

##### Stability debt
When an org builds up different types of technical debt, which then affects the stability of their infrastructure. This leads to scenarios where instead of proactively managing on-call, you have to reactively manage on-call by pulling in subject matter experts or, really, indirectly having the entire team on-call. This becomes quite an intense pain point for the engineers and on-call rotation team, but the rest of the company cannot grasp the issue to explain it well. Stability debt can also impact the reliability of the product, making it a customer-facing issue as well. [12]

##### Security Debt
When there are issues in the tech stack that leaves the company open to security vulnerabilities like brute forcing password info, data breaches, or competitors knowing how to collect confidential information. Since humans have trouble planning and evaluating hypotheticals that may (or may not) happen, this results in most orgs having significant security debt. [12]

##### Technical product debt
When there is visible negative product impact. This work is easiest and most compelling to address, since it has evident impacts to users and is outwardly facing so any team at the organization can see the repercussions to customers and sales/revenue. [12]

##### Decision debt
What this is = When a past technical decision was made that was X% wrong or had some tradeoffs on scope, time, or resources, and the team is now paying for that decision. **This is typically the most common form of tech debt**. [12]

#### Prioritizing Tech Debt Strategically
So far, we've gone through assumptions, classifications, and sizing in relation to tech debt. Once you understand those things you can make a strategic decision within the broader context of your product decisions. [12]

![image](https://user-images.githubusercontent.com/3407254/208305681-0fd1697f-9fdf-4e69-bb43-ad117da54b0d.png)

##### Strategic Tech Debt Portfolio, Based On Company Growth Stage

Another way to approach tech debt strategically is crafting your tech debt portfolio based on tech debt type in relation to your organization's size. Here at Reforge, we classify companies as they go through four stages of growth on the S-curve: [12]
![image](https://user-images.githubusercontent.com/3407254/208305760-c7e5fe01-a8f7-4577-9c09-bd02a9d13001.png)

- Traction = Bottom of the S-curve, pre-product market fit. Linear, unscalable efforts to get the growth engine going.
- Inflection = Bend in the S-curve, clear signals of product market fit on a small scale. Transitioning from unscalable to scalable growth loops.
- Scale = Hyper growth part of the S-curve. Optimizing core growth loops. Doubling down on what works.
- Expansion = Approaching top of the S-curve, saturation starts to hit. Need to think about PMF expansion and restarting the process all over again or layering on a new growth loop.

Related to the S-curve, each type of tech debt should be balanced appropriately based on the company's stage of growth. Represented visually below are guidelines to consider, for the distribution of tech debt (by type of tech debt) as an organization progresses over time. [12]

![image](https://user-images.githubusercontent.com/3407254/208305778-8bd77d4a-7442-4026-b052-2ad24e2ed1d5.png)


### Reduce Operational Complexity <a name="reduce-operational-complexity"></a>
Invest time to Reduce Operational Complexity [2][8]:
- Keep no. of technologies low. Don’t sway towards shiny new technologies.
- Every additional technology you add is is guaranteed to go wrong eventually. Will need your time.
- Do the simple thing first.
- Embrace operational simplicity.
- The first solution that comes to mind is generally complex. Don't stop. Keep peeling off the layers of onion.
- Simplify the architecture to reduce their operational burden.
- “What’s the simplest solution that can get the job done while also reducing our future operational burden?”
- Discipline to focus on simplicity is high leverage.

## Lead Engineer Accountability <a name="lead-engineer-accountability"></a>
Tips to Lead Engineer [2][8]:
- Invest in your team's Growth
- Invest in onboarding.
- The higher you climb up the engineering ladder, the more your effectiveness will be measured not by your individual contributions but by your impact on the people around you.
- "You’re a staff engineer if you’re making a whole team better than it would be otherwise. You’re a principal engineer if you’re making the whole company better than it would be otherwise. And you’re distinguished if you’re improving the industry.” ￼- Focus primarily on making everyone around you succeed.
- Your career depends on your team's success.
- Make hiring everyone's responsibility.
- Shared ownership of code.
- Keep bus factor more than one.
- Shared ownership removes isolated silos of information.
- Build collective wisdom through post mortems.
- Hire the best.
- Surround yourself with great advisors

## Frameworks about Engineering Effectiveness <a name="frameworks"></a>

### SPACE: A Framework for Understanding Developer Productivity <a name="space-framework"></a>

Productivity is about more than the individual or the engineering systems; it cannot be measured by a single metric or activity data alone; and it isn't something that only managers care about. The SPACE framework was developed to capture different dimensions of productivity because without it, the myths just presented will persist. The framework provides a way to think rationally about productivity in a much bigger space and to choose metrics carefully in a way that reveals not only what those metrics mean, but also what their limitations are if used alone or in the wrong context. [9]

- S: Satisfaction and well-being
- P: Performance
- A: Activity
- C: Communication and collaboration
- E: Efficiency and flow

#### Satisfaction and well-being

Productivity and satisfaction are correlated, and it is possible that satisfaction could serve as a leading indicator for productivity; a decline in satisfaction and engagement could signal upcoming burnout and reduced productivity. [9]

It is clear that satisfaction and well-being are important dimensions of productivity. These qualities are often best captured with surveys. To assess the satisfaction dimension, you might measure the following: [9]

- Employee satisfaction. The degree of satisfaction among employees, and whether they would recommend their team to others.
- Developer efficacy. Whether developers have the tools and resources they need to get their work done.
- Burnout. Exhaustion caused by excessive and prolonged workplace stress.

#### Performance

Performance is often best evaluated as outcomes instead of output. The most simplified view of software developer performance could be, Did the code written by the developer reliably do what it was supposed to do? Example metrics to capture the performance dimension include: [9]

- Quality. Reliability, absence of bugs, ongoing service health.
- Impact. Customer satisfaction, customer adoption and retention, feature usage, cost reduction.

#### Activity

A well-designed engineering system, will help in capturing activity metrics along different phases of the software development life cycle and quantify developer activity at scale. Some of the developer activities that can be measured and quantified relatively easily are: [9]

- Design and coding. Volume or count of design documents and specs, work items, pull requests, commits, and code reviews.
- Continuous integration and deployment. Count of build, test, deployment/release, and infrastructure utilization.
- Operational activity. Count or volume of incidents/issues and distribution based on their severities, on-call participation, and incident mitigation.

#### Communication and collaboration

Communication and collaboration capture how people and teams communicate and work together. Software development is a collaborative and creative task that relies on extensive and effective communication, coordination, and collaboration within and between teams. Effective teams that successfully contribute to and integrate each other's work efficiently rely on high transparency5 and awareness6 of team member activities and task priorities. In addition, how information flows within and across teams impacts the availability and discoverability of documentation that is needed for the effective alignment and integration of work. [9]

Understanding and measuring team productivity and team member expectations are, however, complicated because of items that are difficult to measure such as invisible work and articulation work for coordinating and planning team tasks.18 That said, the following are examples of metrics that may be used as proxies to measure communication, collaboration, and coordination: [9]

- Discoverability of documentation and expertise. 
- How quickly work is integrated.
- Quality of reviews of work contributed by team members.
- Network metrics that show who is connected to whom and how.
- Onboarding time for and experience of new members.

Some example metrics to capture the efficiency and flow dimension are: [9]
- Number of handoffs in a process; number of handoffs across different teams in a process.
- Perceived ability to stay in flow and complete work.
- Interruptions: quantity, timing, how spaced, impact on development work and flow.
- Time measures through a system: total time, value-added time, wait time.

#### Efficiency and flow

Finally, efficiency and flow capture the ability to complete work or make progress on it with minimal interruptions or delays, whether individually or through a system. This can include how well activities within and across teams are orchestrated and whether continuous progress is being made.

This conceptualization of productivity is echoed by many developers when they talk about "getting into the flow" when doing their work—or the difficulty in finding and optimizing for it, with many books and discussions addressing how this positive state can be achieved in a controlled way. For individual efficiency (flow), it's important to set boundaries to get productive and stay productive—for example, by blocking off time for a focus period. Individual efficiency is often measured by uninterrupted focus time or the time within value-creating apps (e.g., the time a developer spends in the integrated development environment is likely to be considered "productive" time).

At the team and system level, efficiency is related to value-stream mapping, which captures the steps needed to take software from idea and creation to delivering it to the end customer. To optimize the flow in the value stream, it is important to minimize delays and handoffs. 

## Supportive Metrics <a name="supportive"></a>

### DORA Metrics <a name="dora"></a>
DORA metrics come from an organization called DevOps Research and Assessment. This was a team put together by Google to survey thousands of development teams across multiple industries, to try to understand what makes a high performing team different than a low performing team. DORA metrics are also known as Accelerate metrics, thanks to the popular book "Accelerate: The Science of Lean Software and DevOps" by Nicole Forsgren [14], founder of DORA, Jez Humble, and Gene Kim. [13]

These are the four metrics:
- Deployment Frequency
- Change Lead Time 
- Change Failure Rate 
- Mean Time to Recovery (MTTR)

#### Deployment Frequency <a name="dora-deployment-frequency"></a>

Deployment frequency is very important. In fact, it's usually the first place teams start with DORA metrics. What you're doing is you're measuring how many times you change production. The goal of delivering code quickly to production is to ship as many times as possible. In order to make that work, you need to change the batch size to be as small as possible. In other words, ship as few changes to production at a time as you can. [13]

Technically, what you want to do here is you want to ship each pull request or individual change to a production at a time. That works great for smaller teams, but it doesn't always work for a bigger team. For example, if you're a big team on say a monolith, what you want to do is a technique called release train, where you ship to production in fixed intervals throughout the day. Again, your goal is to minimize the batch size as much as possible to reduce your overall risk and increase your deployment frequency. Again, ship more smaller. [13]

#### Change Lead Time  <a name="dora-change-lead-time"></a>

The key to Change Lead Time is to understand what composes change lead time. Change Lead Time as defined in DORA metrics is measured from the moment the developer starts working on a change to the moment that it shipped to production. But you can actually break that time down into buckets. For example, the time a developer's working on the change, that's one bucket. Or the time that your deployment process takes to push a change all the way out to production is another bucket. By looking at things in buckets, you can see what takes the most amount of time and work on optimizing that. Change Lead Time is a really important metric for your company, because what it's doing is it's measuring how quickly your team is able to respond to changing conditions, events, or needs.  [13]

Technically I found the biggest bucket in Change Lead Time is testing. Teams will often have test as a separate step in a release process, which means that you add days or even weeks to your change lead time. Instead of having it as a separate action, integrate your testing into your development process. Have your testers teach your developers how to write automated tests from the beginning so that you don't need a separate step. To improve your Change Lead Time, eliminate bottlenecks. [13]

#### Change Failure Rate  <a name="dora-cfr"></a>

Change Failure Rate is simply the ratio of the number of deployments to the number of failures. But the key here is to define what is a failure. This particular DORA metric will be unique to you, your team, and your service. In fact, it will probably change over time as your team improves. The common mistake is to simply look at the total number of failures instead of the change failure rate. The problem with this is it will encourage the wrong type of behaviors. Our goal here is to ship change as quickly, and if you're simply looking at the total number of failures, your natural response is try to reduce the number of deployments so that you might have fewer incidences. [13]
 
Technically, the key here is to get the developer involved in the production ideally doing the deployment. What you want, is when there is a failure, the developer is involved in production so that they understand the impact of their change and their failure, he can learn from it, creating a critical feedback loop so the developer ensures that this type of incident never happens again. [13]

#### Mean Time to Recovery (MTTR) <a name="dora-mttr"></a>

MTTR is just one step in the incident response process. First, you need to detect there's even a problem. Once you've detected it, how quickly can you ship a change out? This is what MTTR focuses on. [13]

The time to detection is a metric in itself, typically known as MTTD or Mean Time to Discovery. If you can detect a problem immediately, you can take MTTD down to practically zero, and since MTTD is part of the calculation for MTTR, improving MTTD helps you improve MTTR. [13]

If you just focus on improving MTTR and none of the other ones, you'll often create these dirty, quick, ugly hacks to try to get the system up and going again. But often, those hacks will actually end up making the incident even worse. This is why it's critical that your team has a culture of shipping lots of changes quickly so that when an incident happens, shipping a fix quickly is natural. It's what they do anyways. That way, the incident won't get any worse. [13]

Technically, try Feature Flags. Feature Flags are toggles that allow you to turn a change on or off in production with a click of a button, so that if you have an incident with the change, you can click a button, turn it off, and reduce your MTTR down to seconds. [13]

## Value-Driven Engineering

What benefits does software engineering produce? Consider the typical process of developing a feature, releasing it to users, and making adjustments. How does this cycle appear? Consider a startup where the software engineering team is fairly autonomous, empowered, and attentive to the needs of the market. In accordance with Kent Beck and Gergely Orosz [15], the typical development lifecyle is shown below.

![Development Lifecyle](https://github.com/eduardomioto/effective-engineering/assets/3407254/e2719583-e53a-4b00-bd43-0797ca2a50ef)

We start by deciding what to do next, and then we do it. This is the effort like planning, coding and so on. Through this effort, we produce tangible things like the feature itself, the code, design documents, etc. These are the output. Customers will behave differently as a result of this output, which is our outcome. For example, thanks to the feature they might get stuck less during the onboarding flow. As a result of this behavior change, we will see value flowing back to us like feedback, revenue, referrals. This is the impact [15].


#### Conclusion
Don't focus on metrics. It's not about the metrics, it's about your team and its goals. Metrics are how your team knows how well they're progressing towards those goals, so don't focus on the metric, focus on your team and its goals. The key here is to remember it's really all about your development. Empower your developers. Give them the tools they need to succeed because your developers are going to be the ones to be able to make the best changes to help your team reach its goals. [13]

## Supportive Practices <a name="practices"></a>

#### Semantic Versioning <a name="versining"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/semantic-versioning.md)

#### Git Flow and Feature Branch  <a name="gitflow"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/git-worflows.md)

#### Feature Flags <a name="featureflags"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/feature-flags.md)

#### Environments Stability <a name="environment"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/environment-stability.md)

#### Continuous Delivery  <a name="cd"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/continuous-delivery.md)

#### Architectural Decision Records (ADR)  <a name="adr"></a>
- [Go to a dedicated article](https://github.com/eduardomioto/effective-engineering/blob/main/practices/adr.md)

## Additional Resources <a name="resources"></a>
- [Collaborative Additional Resources](https://github.com/eduardomioto/effective-engineering/blob/main/RESOURCES.md)

## Contributors ✨  <a name="contributors"></a>

Thanks goes to these people as well as our references.

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center">
      <a href="https://eduardomioto.com"><img src="https://avatars.githubusercontent.com/eduardomioto" width="100px;" alt=""/>
      <br />
      <sub><b>Eduardo Mioto</b></sub></a>
      <br />
    </td>
 </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

## References <a name="references"></a>

- [1] [Dictionary.com, LLC. "Effectiveness | Define Effectiveness Dictionary.com." Web. 28 Sept. 2011](http://dictionary.reference.com/browse/effectiveness)
- [2] [The Effective Engineer | Edmond Lau. Book. 1st edition - March 19, 2015](https://www.amazon.com/Effective-Engineer-Engineering-Disproportionate-Meaningful/dp/0996128107)
- [3] [OkayHQ EE Handbook. Web. 12 Dec. 2022](https://www.okayhq.com/handbook/)
- [4] [Netflix Freedom & Responsibility culture](https://jobs.netflix.com/culture)
- [5] [Improving Team Productivity by Reducing Context Switching](https://www.linkedin.com/pulse/improving-team-productivity-reducing-context-karen-casella/)
- [6] [O Fator Confiança: a Base Para uma Liderança Extraordinária |  Marco Fabossi . Book. 1st edition - December 19, 2019](https://www.amazon.com.br/Fator-Confian%C3%A7a-Base-Lideran%C3%A7a-Extraordin%C3%A1ria/dp/8557173385)
- [7] [Understand team effectiveness - Psychological safety](https://rework.withgoogle.com/guides/understanding-team-effectiveness/steps/identify-dynamics-of-effective-teams/)
- [8] [Effective Engineer - Notes](https://gist.github.com/rondy/af1dee1d28c02e9a225ae55da2674a6f)
- [9] [The SPACE of Developer Productivity | Nicole Forsgren et al](https://queue.acm.org/detail.cfm?id=3454124)
- [10] [Happiness and the productivity of software engineers. In Rethinking Productivity in Software Engineering, ed. C. Sadowski and T. Zimmermann, 109-124](https://link.springer.com/chapter/10.1007/978-1-4842-4221-6_10)
- [11] [Towards a theory of software developer job satisfaction and perceived productivity. Storey, M. A., Zimmermann, T., Bird, C., Czerwonka, J., Murphy, B., Kalliamvakou, E. 2019](https://ieeexplore.ieee.org/document/8851296)
- [12] [Reforge - Managing Tech Debt](https://www.reforge.com/blog/managing-tech-debt)
- [13] [Dora Metrics Explained - Sleuth.io](https://www.sleuth.io/post/dora-metrics-explained)
- [14] [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations | Nicole Forsgren, Jez Humble, Gene Kim / 1st edition - 2018)](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
- [15] [Measuring developer productivity? A response to McKinsey](https://newsletter.pragmaticengineer.com/p/measuring-developer-productivity)

## Inspirations <a name="inspirations"></a>
- :star: [OkayHQ Effective Engineer Handbook](https://github.com/OkayHQ/ee-handbook/blob/main/content/en/resources.md)
- [Team Topologies Book - References](https://github.com/TeamTopologies/Team-Topologies-Book-References/blob/main/Team-Topologies-references-Markdown.md)
