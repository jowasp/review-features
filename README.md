# OWASP Review Requirements Per Project Category
The following table provides an overview of the indicators that determine when an Code/Tool OWASP project belongs to a certain maturity level. This table is a basic guideline for the reviewer to establish how to classify an OWASP project. It is not 'black/white' checklist. The reviewer should use his/her judgement to analyze the specific situation of each project.
The most important indicators to keep in mind are:
* User feedback: Because determines user adoption and based on the feedback, reviewer can actually establish code maturity level by looking at (positive/negative) feedback
* Industry recognition: A project that has community recognition , such as being selected as speaker or trainier in important community conferences, shows that the project has reached also some quality and uniqueness level due to the level of requirements to be accepted (see for example speaker requirements: https://www.blackhat.com/us-15/call-for-papers.html)
* Active leadership: A project leader involved in the development and promotion of a projects shows a level of commitment to it. This is quite important to establish the potential continuity of a project.

These indicators provide a signal of maturity level regaridng user adoption of a project and should, at all times, be the highest and important indicators to establish community adoption and maturity level.
The reviewer is not required to test the project , such as to confirm the if the project builds correctly, howeverr, having some experience as developer/software programmer is advisble in order to look at clear indicators that the project has a certain code quality. 

The 'X' simbolize  a required requirement for that category.'-' Symbolizes that requirement is not needed for that category

##The OWASP Project Lifecycle:

is broken down into the following stages
###Project Idea:

During this phase, a potential project leader promotes his project idea without a define roadmap or plan. No requirements are needed during this phase

(THIS TABLE IS IN PROGRESS)

Recommended reading:
Qualipso Project: Quality Recommendations for FLOSS development processes
http://qualipso.icmc.usp.br/files/Quality.recommendations.for_.FLOSS_.development.processes.pdf

Open Source Software Evaluation Models
http://jose-manuel.me/wp-content/uploads/2013/06/JMLL_MTI_Thesis_I-OSSEM_C4.pdf

Producing Open Source Software: How to Run a Successful Free Software Project
Karl Fogel
http://producingoss.com/en/producingoss.html

| Requirement   |   Project Idea     |        Incubator   |          Lab       |       Flagship     |
|---------------|:------------------:|:------------------:|:------------------:|:------------------:|
| [Low, Moderate to High Activity level](http://blog.openhub.net/about-project-activity-icons/)|  - |  - | X | X |
| [Wiki page updated](Wiki-page-updated.md) |  - | X | X | X |
| [Vendor neutral](vendor_neutral.md)  |  - | X | X | X |
| [> + 1 contributor](contributors.md) |  - | - | X | X |
| [Open Source License](licenses.md) |  - | X | X | X |
| [Open Source Repository](https://www.openhub.net/orgs/OWASP)  |  - | X | X | X |
| [Outlined Roadmap](outlined_roadmap.md)  |  - | X | X | X |
| [Active leader](active_leader.md) |  -  | - | X | X |
| Standalone Executable/installer-only(Tool projects) |  -  | - | X | X |
| [Presence of Bug Tracking system](bugtrackingindicator.md)  |  - | X | X | X |
| [Online Documentation](onlinedocumentation.md) |  -  | X | X | X |
| [Build Automation](https://en.wikipedia.org/wiki/Build_automation)  | - | - | X | X |
| [Developer Community](developer.md) |  -  | - | - | X |
| [Innovative approach](innovation.md) |  -  | - | - | X |
| [Versioning control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)|  -  | - | X | X |
| [Alpha Release](alpha_release.md)|  - | X | - | - |
| Beta Release |  -  | - | X | - |
| Production Release |  -  | - | - | X |
| Use of Unit/Test cases |  -  | - | - | X |
| [User feedback](active_mailinglist.md) |  -  | - | X | X |
| [External References/Industry Recognition](industry_recognition.md) |  -  | - | X | X |
