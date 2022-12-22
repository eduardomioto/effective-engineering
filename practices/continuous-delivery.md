## Additional Relevant Practives <a name="relevant-practices"></a>

### Continuous Delivery <a name="cd"></a>

DORA research found that the following technical capabilities drive the ability to achieve continuous delivery. Transformational leadership within the organization also drives the implementation of many of these technical capabilities. [1]

To help your team get higher throughput and lower risk releases, implement the following continuous delivery practices: [1]

- Test automation: The use of comprehensive automated test suites primarily created and maintained by developers. Effective test suites are reliable—that is, tests find real failures and only pass releasable code.

- Deployment automation: The degree to which deployments are fully automated and do not require manual intervention.

- Trunk-based development: Characterized by fewer than three active branches in a code repository; branches and forks having very short lifetimes (e.g., less than a day) before being merged into mainline; and application teams rarely or never having code lock periods when no one can check in code or do pull requests due to merging conflicts, code freezes, or stabilization phases.

- Shift left on security: Integrating security into the design and testing phases of the software development process. This process includes conducting security reviews of applications, including the information security team in the design and demonstration process for applications, using pre-approved security libraries and packages, and testing security features as a part of the automated test suite.

- A loosely coupled architecture: Architecture that lets teams test and deploy their applications on demand, without requiring orchestration with other services. Having a loosely coupled architecture allows your teams to work independently without relying on other teams for support and services, which in turn enables them to work quickly and deliver value to the organization.

- Empowering teams to choose tools: Teams that can choose which tools to use do better at continuous delivery. No one knows better than practitioners what they need to be effective.

- Continuous integration (CI): A development practice where code is regularly checked in, and each check-in triggers a set of quick tests to discover regressions, which developers fix immediately. The CI process creates canonical builds and packages that are ultimately deployed and released.

- Continuous testing: Testing throughout the software delivery lifecycle rather than as a separate phase after dev complete. With continuous testing, developers and testers work side by side. High performers practice test-driven development, get feedback from tests in less than ten minutes, and continuously review and improve their test suites (for example, to better find defects and keep complexity under control).

- Version control: The use of a version control system, such as Git or Subversion, for all production artifacts, including application code, application configurations, system configurations, and scripts for automating build and configuration of environments.

- Test data management: Effective practices include having adequate data to run your test suite, the ability to acquire necessary data on demand, and the data not limiting the number of tests you can run. We caution that your teams should minimize, whenever possible, the amount of test data needed to run automated tests.

- Comprehensive monitoring and observability: Allows teams to understand the health of their systems. Effective solutions enable teams to monitor predefined metrics, including system state as experienced by users, as well as allowing engineers to interactively debug systems and explore properties and patterns as they emerge.

- Proactive notifications: Monitoring system health so that teams can preemptively detect and mitigate problems.
Database change management: Database changes don't slow teams down if they follow a few key practices, including storing database changes as scripts in version control (and managing these changes the same way as production application changes), making database changes visible to everyone in the software delivery lifecycle (including engineers), and communicating with all parties when changes to the application require database changes.

- Code maintainability: Systems and tools that make it easy for developers to change code maintained by others, to find examples in the codebase, to reuse other people's code, and to add, upgrade, and migrate to new versions of dependencies without breaking their code.
While continuous delivery is often combined with continuous integration and shortened to CI/CD, research shows that continuous integration is only one element of implementing continuous delivery. To achieve reliable, low-risk releases, you need close collaboration between everyone involved in the software delivery process, not just software developers, and your team needs to adopt new ways of working and learn new skills.

## References
- [1] [Implementing Continuous Delivery](https://cloud.google.com/architecture/devops/devops-tech-continuous-delivery#implementing_continuous_delivery)
