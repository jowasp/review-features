# OWASP Review: Indicators Per Project Category
The following table provides an overview of the indicators that determine when an Code/Tool OWASP project belongs to a certain maturity level. This table is a basic guideline for the reviewer to establish how to classify an OWASP project and is based on community feedback and known methodologies for establishing sucessfull FOSS projects . It is not 'black/white' checklist. The reviewer should use his/her judgement to analyze the specific situation of each project. The most important indicators to keep in mind are:
* <b>User feedback</b>: Because it determines user adoption and based on the feedback, reviewer can actually establish code maturity level by looking at (positive/negative) feedback
* <b>Industry recognition</b>: A project that has community recognition , such as, appearing in important news outlets, being selected as speaker or trainier, in important security conferences, shows that the project has reached also some quality and uniqueness level due to the level of requirements to be accepted (see for example speaker requirements: https://www.blackhat.com/us-15/call-for-papers.html) or the kind of information quite relevant to the subject, significant enough to called the attention of the press
* <b>Active leadership</b>: A project leader involved in the development and promotion of his/her project shows a level of commitment to it. This is quite critical to establish the potential continuity of a project.
* <b>Vendor neutrality</b>: OWASP does not endorse any product, services or tools. The following disclaimer/About OWASP text can be used in projects or press releases that reference external products, services or tools. We ask that the community look out for inappropriate uses of the OWASP brand including use of our name, logos, project names and other trademark issues. (https://www.owasp.org/index.php/Talk:Marketing/Resources)

These above indicators provide a signal of maturity level regarding user adoption of a project, which aligns to OWASP mission and should, at all times, be the highest and important indicators to establish its level. The reviewer is not required to test the project , such as to confirm  if the project builds correctly, however, having some experience as developer/software programmer is advisable in order to look for clear signals of quality and understand the development of the project. 

* 'X' Symbolizes  a required requirement for that category.

* '-' Symbolizes that requirement is not needed for that category

##Substantiation
A review should at all times be properly substantiated, with a conclusion about why the reviewer considers that it complies with a criteria or not. The following are some examples for Code and Documentation reviews:
* Code:  https://gitprint.com/jowasp/review-features/blob/master/example_review.md
* Tools: https://gitprint.com/jowasp/review-features/blob/master/example_review_doc.md

Recommended reading:
Qualipso Project: Quality Recommendations for FLOSS development processes
http://qualipso.icmc.usp.br/files/Quality.recommendations.for_.FLOSS_.development.processes.pdf

Open Source Software Evaluation Models
http://jose-manuel.me/wp-content/uploads/2013/06/JMLL_MTI_Thesis_I-OSSEM_C4.pdf

Producing Open Source Software: How to Run a Successful Free Software Project
Karl Fogel
http://producingoss.com/en/producingoss.html

| Requirement/Indicator   |   Project Idea     |        Incubator   |          Lab       |       Flagship     |
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
