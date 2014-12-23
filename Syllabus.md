# CSC 591/791 Course Syllabus - DevOps

North Carolina State University

| Information  | &nbsp;                   |
|--------------|--------------------------|
| Instructor   | Dr. Christopher Parnin (cjparnin@ncsu.edu)|
| Readings     | Provided by instructor   |
| Credit-hours | 3                        |
| Office Hours | EBII 3270, Thur 11am-12pm|


## Prerequisites
CSC510 (Software Engineering) or graduate or senior standing with
at least 3.0 GPA, good knowledge of at least one high
level programming language.

## Outline

Modern software development organizations require entire teams of DevOps to automate  and maintain software engineering processes and infrastructure vital to the organization. In this course, you will gain practical exposure to the skills, tools, and knowledge needed in automating software engineering processes and infrastructure. 
Students will have the chance to build new or extend existing software engineering tools and design a DevOps pipeline.

## Objectives

Students are expected to gain practical exposure to tools, processes, and principles of software engineering through hands-on projects while understanding models and research ideas behind the tools and processes.  Lectures will include workshop style learning experiences, where students get to work on a problemset and receive feedback from the instructor and other classmates.  When possible, guest lectures from industry will help illustrate examples of how the technology is deployed in practice.

## Course Topics

Topics include: Static analysis,  build management, automatic testing, goverance, quality gates, monitoring, and configuration and release management. Additional topics include provisioning, quality assurance, unit testing, test generation, static and dynamic analysis and service, platform, and infrastructure as a service.

## Course Overview

In the course, a mixture of traditional lectures with activities and in-class workshops will be used.  During lectures, we will cover core concepts related to a topic. During the in-class workshops, we will perform sample exercises with relevant tools that reinforce lecture material.  Evaluation will be based on tech talks, homework assignments, workshop attendance, and final project.

### Tech Talks

Students in CSC 591 will organize in groups and present one tech talk during lecture.  For a *tech talk*, students are expected to cover one tool or technology revelant to DevOps in a 15-20 minute presentation.  Students should perform a small demo to help illustrate the tool. Three days during the semester will be reserved for these presentations.

### Homeworks

Homework assignments will be regularly released throughout the semester and reinforce class material.  Homeworks will typically mirror a scenario or common task that a DevOps engineer may face.

### Project

The primary objective of the course will be to allow students to gain experience in incrementally building a continous delivery pipeline from scratch.  Throughout the semester, students are expected to complete a component of the pipeline by each milestone deadline.  Students in CSC 791 are expected to implement a research component to their pipline. 

Students are able to choose their own app and technology choices for building a deployment pipeline.  Otherwise, a default app and technology stack will be provided.

##### Milestones

Details on requirements for milestones will be released throughout the course.  A student's pipeline should demonstrate the following components by the milestone deadline:

* BUILD
* TEST+ANALYSIS
* DEPLOY
* SPECIAL

## Schedule and Topics - Spring 2015

The following schedule is subject to change.

| Class    | Topics                           |  Resources |  Deadlines |
|----------|----------------------------------|------------| ----------            |
| Jan 8th  | Hello                            | &nbsp;     |  &nbsp;               | 
| Jan 13th | Core Concepts + Skills           | &nbsp;     |  &nbsp;               |
| Jan 15th | Workshop: Git, Branches, Servers | &nbsp;     |  &nbsp;               |
| Jan 20th | Configuration Management         | &nbsp;     |  &nbsp;               |
| Jan 22nd | Workshop: Managed Environments   | [Docker](), [Chef](), [Vagrant](), [Ansible]()     |  HW #1 - Provisioning Servers |
| Jan 27th | Build Management                 | &nbsp;     |  &nbsp;               |
| Jan 29th | Workshop: Build Servers          | [Jenkins](), [CruiseControl]()     | &nbsp; |
| Feb 3rd  | Test Management                  | &nbsp;     |  MILESTONE: BUILD     |
| Feb 5th  | Workshop: Test Suites            | &nbsp;     |  &nbsp;               |
| Feb 10th | Static + Dynamic Analysis        | &nbsp;     |  &nbsp;               |
| Feb 12th | Workshop: Fuzzing                | &nbsp;     |  HW #2 - Test Suite Minimization |
| Feb 17th | Tech Talks #1                    | &nbsp;     |  &nbsp;               |
| Feb 19th | Project Planning                 | &nbsp;     |  &nbsp;               |
| Feb 24th | Operations + Concepts            | &nbsp;     |  &nbsp;               |
| Feb 26th | Tech Talks #2                    | &nbsp;     |  HW #3 - Mass Refactoring |
| March 3rd| Infrastructure Management        | [OpenStack](http://www.openstack.org/), [AWS]() | &nbsp;  |
| March 5th| Workshop: Queues, Proxies, Caches| &nbsp;     | MILESTONE: TEST+ANALYSIS |
| March 7th-13th  | ~~~ Spring Break ~~~      | &nbsp;     | &nbsp;                |
| March 17th | Staging Patterns               | &nbsp;     | &nbsp;                |
| March 19th | Workshop: Staging Servers      | &nbsp;     | &nbsp;                |
| March 24th | Deployment                     | &nbsp;     | &nbsp;                |
| March 26th | Workshop: Deflighting          | &nbsp;     | HW #4 - Data Migration                |
| March 31st | Tech Talks #3                  | &nbsp;     | MILESTONE: DEPLOY     |
| April 2nd  | ~~~ Spring Holiday ~~~         | &nbsp;     | &nbsp;                |
| April 7th  | Analysis + Monitoring          | [Flame Graphs](https://www.usenix.org/conference/lisa13/technical-sessions/plenary/gregg), [Splunk](http://www.splunk.com/), [NewRelic](http://newrelic.com/) | &nbsp;                   |
| April 9th  | Workshop: A/B Testing | &nbsp;     | &nbsp;                   |
| April 14th | Auditing              | &nbsp;     | &nbsp;                   |
| April 16th | Guest Slot            | &nbsp;     | MILESTONE: SPECIAL       |
| April 21st | TBD/Demos             | &nbsp;     | &nbsp;                   |
| April 23rd | TBD/Demos             | &nbsp;     | HW #5 - Server Inventory |

## Resources

##### Books
The following books are not required but may provide useful references.

* [Ansible: Up and Running](http://www.ansiblebook.com/)
* [Continous Delivery](http://continuousdelivery.com/)
* [Continous Integration](http://www.amazon.com/Continuous-Integration-Improving-Software-Reducing/dp/0321336380)
* [Designing Data-Intensive Applications](http://dataintensive.net/)
* [Systems Performance: Enterprise and the Cloud](http://www.brendangregg.com/sysperfbook.html)
* [The Practice of Cloud System Administration](http://the-cloud-book.com/)



## Late Policy
No late assignments will be accepted. Many of your assignments will be collaborative
effort with other members of your group. Thus, late papers by one member
of the group will affect the entire group. The due date for assignments will be
posted on the assignment and will generally be submitted electronically.

## Teaching Philosophy
We will make use of intensive classroom activities and readings. You will be expected to participate actively in discussions. On any given issue, you may be asked to summarize and criticize reading assignments from the text or articles that you have read for your assignments and projects. We view the web as a valuable
resource. Our course website will serve as our ”information system” this semester; you will be expected to visit the site on a daily basis for updates and to obtain your homework / project assignments.
Only you can learn. As the instructors, we can only guide and assist you. Thus, all of the class activities are aimed at helping you learn.

## Academic Integrity
The course will follow all NCSU academic [integrity regulations](http://www.ncsu.edu/provost/academic_policies). All students are expected to maintain traditional standards of academic integrity by giving proper credit for all work. All suspected cases of academic dishonesty will be aggressively pursued. A student shall be guilty of a violation of academic integrity if he or she represents the work of others as his or her own or aid another’s misrepresentation.
Any violation associated with a homework/lab assignment, project
deliverable, examination or quiz will result in a failing grade for the course. Such violations will be reported to the Office of Student Conduct, which may impose penalties beyond those by the instructors.

We encourage you to read the ACM Code of Ethics, particularly Sections 1.3, 1.5, 1.6, 2.2 and 2.4. (http://www.acm.org/constitution/code.html)

## Equity Policy

All persons, regardless of age, race, religion, gender, physical disability or sexual orientation shall have equal opportunity without harassment in this course. Any harassment should be reported immediately to the instructor.

## Students with Disabilities
The course will follow all NCSU regulations relevant to students with disabilities. Any students requiring additional assistance due to disabilities (e.g., learning disabilities), should contact the professor during the first week of the semester. Students requiring extra time for examinations and quizzes are asked to make
arrangements at least three days in advance. You may contact the NCSU Disability Services for Students Office regarding campus services at the Student Health Center for more information and assistance (http://www.ncsu.edu/dso/students/).

## Course Evaluation

Online class evaluations will be available for students to complete during the last two weeks of class. Students will receive an email message directing them to a website where they can login using their Unity ID and complete evaluations. All evaluations are confidential; instructors will never know how any one student responded to any question, and students will never know the ratings for any particular instructors.

| Resources     | &nbsp; |
|---------------|--------|
|Evaluation website:   | https://classeval.ncsu.edu|
|Student help desk:    | classeval@ncsu.edu|
|Info about ClassEval: | http://www2.acs.ncsu.edu/UPA/classeval/index.htm|

## Course Grading

| Category           | Weight |
|--------------------|--------|
| Homework           | 25%    |
| Class workshops    | 25%    |
| Tech Talk/Research | 10%    |
| **Final Project**  | 40%    |

The Final Project will be evaluated during each milestone, each worth 10%.
