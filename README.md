# DevOps: CSC 591/791-004
-------------------------

Modern software development organizations require entire teams of DevOps to automate  and maintain software engineering processes and infrastructure vital to the organization. In this course, you will gain practical exposure to the skills, tools, and knowledge needed in automating software engineering processes and infrastructure. 
Students will have the chance to build new or extend existing software engineering tools and design a DevOps pipeline.

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

### Resources

##### Books

* [Ansible: Up and Running](http://www.ansiblebook.com/)
* [Continous Delivery](http://continuousdelivery.com/)
* [Continous Integration](http://www.amazon.com/Continuous-Integration-Improving-Software-Reducing/dp/0321336380)

##### Glossary of Tools

* [http://newrelic.com/devops/toolset](http://newrelic.com/devops/toolset)
