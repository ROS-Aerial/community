# Aerial Robotics Working Group

*Community-driven*

The goal of the aerial robotics working group is to gather aerial robotics enthusiasts within the ROS community and facilitate the sharing of ideas and discussion of issues regarding autonomous robotic platforms operating in the air. The initial focus of the group is to create an overview of the landscape of aerial robotics, including autonomy stacks, communication standards, and simulation, through the establishment of regular meetings, a website, and a literature review. The long-term roadmap of the group involves investigating standards for communication, simulation, and autonomy, and establishing a standard aerial robotics autonomy stack for ROS.

The working group aims to focus on any (autonomous) robotic platform that operates in the air. The group plans to create a starting portal for anyone starting out in aerial robotics, like a website that describes the landscape of all things aerial robotics, like autonomy stacks, communication standards, and simulators. We also aim to gather information about existing Aerial Robotics autonomy stacks, to investigate which features are currently missing in the ROS ecosystem to properly facilitate aerial robotics. The group will investigate what is missing with the current communication standard messaging or alternative communication protocols, and see if these also can be improved for swarm broadcasting. Also, we will keep oversight of aerial robotic simulation possibilities and investigate the implementation of propulsion and aerodynamics and realistic weather conditions. Moreover, as the learning curve is high in aerial robotics, providing tutorials on how to get started with Aerial robotics and ROS will be the focus as well if these have not been made available yet. 

Meetings information can be [found here](meetings.md).

A list of active participants can be [found here](#list-of-active-participants).

## Subprojects

This Working Group owns and maintains the following Subprojects.
Its meetings and membership are largely focused on the direction, design, and work on the projects.

### Documentation and overview
There is currently a lot of documentation and projects related to aerial robotics. The current effort will therefore be to collect all of these in an overview of the landscape of all aerial robotic projects going on. 

Links: TBD

### Proposed subproject list

Since this working group is at it’s beginning stage but here is a list of potential topics that could be created as a subproject in the future:
* Aerial robotics simulation
* Message standards for UAV
* Autonomy stacks for UAVs
* Communication for swarms of UAVs
* Safety and management systems
* Tutorials and education


### Standards for subprojects

Subprojects must meet the following criteria (and the WG agrees to maintain them upon adoption).

* Build passes against ROS 2 master
* The ROS 2 standard linter set is enabled and adhered to
* If packages are part of nightly builds on the ROS build farm, there are no reported warnings or test failures
* Quality builds are green (address sanitizer, thread sanitizer, clang thread safety analysis)
* Test suite passes
* Code coverage is measured, and non-decreasing level is enforced in PRs
* Issues and pull requests receive prompt responses
* Releases go out regularly when bugfixes or new features are introduced
* The backlog is maintained, avoiding longstanding stale issues

### Adding new subprojects

To request introduction of a new subproject, add a list item to the "Subprojects" section and open a Pull Request to this repository, following the default Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

### Subproject changes

Modify the relevant list item in the "Subprojects" section and open a Pull Request to this repository, following the default Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

### Deprecating subprojects

Projects cease to be useful, or the WG can decide it is no longer in their interest to maintain.
We do not commit to maintaining every subproject in perpetuity.

To suggest removal of a subproject, remove the relevant list item in the "Subprojects" section and open a Pull Request in this repository, following instructions in the Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

If the repositories of the subproject are under the WG's GitHub organization, they will be transferred out of the organization or deleted at this time.

## Governance

### Meetings

* Regular WG Meeting: Montly meetings, last wednesday of the Month at 2 pm UTC
  * The meetings will be announced on discourse at least a week in advance
  * Recordings and meeting notes will be made available after each recording

### Communication Channels

For now, Discourse only, however we will discuss a chat based communication channel soon.

### Backlog Management

Github Projects

### Membership, Roles and Organization Management

Working Group members may act in one or more of the following roles:

* **Member**
  * Prerequisite: Attend at least one out of the last three Working Group meetings
  * Responsible for triaging issues
* **Reviewer**
  * All reviewers are members
  * Prerequisite: Proven track record of high-quality reviews to WG Subprojects
  * Responsible for reviewing pull requests
* **Approver**
  * All approvers are reviewers
  * Prerequisite: Proven track record of high-quality contributions and reviews to WG Subprojects
  * Responsible for approving and merging pull requests
  * Responsible for vetting and accepting new projects into the Working Group
* **Lead**
  * TSC member or their delegate
  * Responsible for organizing and moderating working group meetings
  * Responsible for posting meeting materials (minutes, recordings, etc.)
  * Responsible for breaking ties

To become a member or change role, create an issue in this repository using the appropriate issue template.
Such applications are accepted upon unanimous agreement from Approvers, and are typically based on the applicant's history with the subprojects of the Working Group.
The Lead role cannot be applied for, as it is an appointee of the ROS 2 TSC.

### Modifying this governance document

Changes to this document will be made via Pull Request.
The PR will be merged on unanimous agreement from Approvers.

# List of Active Participants
* [Ramon Roche](https://twitter.com/@mrpollo) - [Dronecode Foundation](https://www.dronecode.org/)
* Kimberly McGuire - Bitcraze AB
* [Miguel Fernandez-Cortizas](https://github.com/miferco97) - CVAR-UPM
* Mark West - TelemeThing
* Aarsh Thakker - Laboratoire des signaux et systèmes
* [Ryan Friedman](https://github.com/Ryanf55) - ArduPilot
* [Ganapathi Naayagam](https://github.com/SGN-047) - [Aviators International](https://teamaviatorsinternational.in/#/)
