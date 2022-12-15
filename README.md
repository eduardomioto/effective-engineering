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
8. [Resources](#resources)
9. [Contributors](#contributors)
10. [References](#references)
11. [Inspirations](#inspirations)


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

## Inspirations <a name="inspirations"></a>
- :star: [OkayHQ Effective Engineer Handbook](https://github.com/OkayHQ/ee-handbook/blob/main/content/en/resources.md)
- [Team Topologies Book - References](https://github.com/TeamTopologies/Team-Topologies-Book-References/blob/main/Team-Topologies-references-Markdown.md)

