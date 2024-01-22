# Aerial Robotics Working Group

*Community-driven*

The goal of the aerial robotics working group is to gather aerial robotics enthusiasts within the ROS community and facilitate the sharing of ideas and discussion of issues regarding autonomous robotic platforms operating in the air. The initial focus of the group is to create an overview of the landscape of aerial robotics, including autonomy stacks, communication standards, and simulation, through the establishment of regular meetings, a website, and a literature review. The long-term roadmap of the group involves investigating standards for communication, simulation, and autonomy, and establishing a standard aerial robotics autonomy stack for ROS.

The working group aims to focus on any (autonomous) robotic platform that operates in the air. The group plans to create a starting portal for anyone starting out in aerial robotics, like a website that describes the landscape of all things aerial robotics, like autonomy stacks, communication standards, and simulators. We also aim to gather information about existing Aerial Robotics autonomy stacks, to investigate which features are currently missing in the ROS ecosystem to properly facilitate aerial robotics. The group will investigate what is missing with the current communication standard messaging or alternative communication protocols, and see if these also can be improved for swarm broadcasting. Also, we will keep oversight of aerial robotic simulation possibilities and investigate the implementation of propulsion and aerodynamics and realistic weather conditions. Moreover, as the learning curve is high in aerial robotics, providing tutorials on how to get started with Aerial robotics and ROS will be the focus as well if these have not been made available yet. 

Meetings information can be [found here](meetings.md).

A list of active participants can be [found here](#list-of-active-participants).

For a list of subprojects and committees can be [found here](#subprojects).

## Subprojects

This Working Group owns and maintains the following Subprojects.
Its meetings and membership are largely focused on the direction, design, and work on the projects.

### Documentation and overview
There is currently a lot of documentation and projects related to aerial robotics. The current effort will therefore be to collect all of these in an overview of the landscape of all aerial robotic projects going on. 

Please go to the [Robotic Aerial Landscape repository](https://github.com/ROS-Aerial/aerial_robotic_landscape). 

### Active Subprojects
Here is a list of subprojects that are active right now:
* [3D outdoor planning](subprojects/outdoor_3d_planning.md)

### Proposed subproject list

The working groups are just starting. Here is a list of potential topics that could be created as subprojects in the future:
* 3D indoor navigation
* Simulation
* Standard development/research drone
* Communication standards
* Documentation (Aerial landscape)
* Content and tutorial
* Safety

### Standards for subprojects

Since the Aerial Robotics working group is community driven we will not follow the normal standards for subprojects but some other defined ones.

The subprojects should at least have:
* A github project about the topic that needs to be updated with the latest important issues and PRs
* At least two people should be interested in working on this topic
* A document about the topic should exist in /subprojects/ folder

These are the criteria that official working group assigned by the TSC must follow:
_Subprojects must meet the following criteria (and the WG agrees to maintain them upon adoption)._

* _Build passes against ROS 2 master_
* _The ROS 2 standard linter set is enabled and adhered to_
* _If packages are part of nightly builds on the ROS build farm, there are no reported warnings or test failures_
* _Quality builds are green (address sanitizer, thread sanitizer, clang thread safety analysis)_
* _Test suite passes_
* _Code coverage is measured, and non-decreasing level is enforced in PRs_
* _Issues and pull requests receive prompt responses_
* _Releases go out regularly when bugfixes or new features are introduced_
* _The backlog is maintained, avoiding longstanding stale issues_

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

* Regular WG Meeting: Biweekly meetings, typically at 3 pm UTC
  * The meetings will be announced on discourse at least a week in advance
  * Recordings and meeting notes will be made available after each recording
  * These announcements will be done on [the official ROS discourse with the wg-aerial-robotics tag](https://discourse.ros.org/tag/wg-aerial-robotics)

### Communication Channels

Any news to be shared, meeting announcements or discussion points should be on the [Aerial Vehicles category on ROS discourse](https://discourse.ros.org/c/aerial-vehicles/).

Quick chats, meeting reminders, subcommittee communication or just for fun sharing is on the [#cwg-aerial channel in the ROS discord Server](https://discord.com/channels/1077825543698927656/1141902822254850128)


### Backlog Management

[Github Projects](https://github.com/ROS-Aerial/community/projects?query=is%3Aopen)

### Membership, Roles and Organization Management

Since the ROS Aerial working group is community-driven, it will not follow the official guidelines. Currently of now we just have the following roles:
- Facilitators/Leads: Organize and moderating meetings. Setup facilitation of the subcommittees
- Members: Joining the meetings, participate with discussions. Although not necessary to be a member, they can also propose and/or join subcommitteers


These rules are for the official TSC assigned working group here for reference:
_Working Group members may act in one or more of the following roles:_

_* **Member**_
  _* Prerequisite: Attend at least one out of the last three Working Group meetings_
  _* Responsible for triaging issues_
_* **Reviewer**_
  _* All reviewers are members_
  _* Prerequisite: Proven track record of high-quality reviews to WG Subprojects_
  _* Responsible for reviewing pull requests_
_* **Approver**_
  _* All approvers are reviewers_
  _* Prerequisite: Proven track record of high-quality contributions and reviews to WG Subprojects_
  _* Responsible for approving and merging pull requests_
  _* Responsible for vetting and accepting new projects into the Working Group_
_* **Lead**
  _* TSC member or their delegate_
  _* Responsible for organizing and moderating working group meetings_
  _* Responsible for posting meeting materials (minutes, recordings, etc.)_
  _* Responsible for breaking ties_

_To become a member or change role, create an issue in this repository using the appropriate issue template.
Such applications are accepted upon unanimous agreement from Approvers, and are typically based on the applicant's history with the subprojects of the Working Group.
The Lead role cannot be applied for, as it is an appointee of the ROS 2 TSC._

### Modifying this governance document

Changes to this document will be made via Pull Request.
The PR will be merged on unanimous agreement from Approvers.

# List of Active Participants
* [Ramon Roche](https://twitter.com/@mrpollo) - [Dronecode Foundation](https://www.dronecode.org/)
* [Kimberly McGuire](https://github.com/knmcguire) - [Bitcraze AB](https://www.bitcraze.io/)
* [Miguel Fernandez-Cortizas](https://github.com/miferco97) - CVAR-UPM
* Mark West - TelemeThing
* Aarsh Thakker - Laboratoire des signaux et systèmes
* [Ryan Friedman](https://github.com/Ryanf55) - ArduPilot
* [Ganapathi Naayagam](https://github.com/SGN-047) - [Aviators International](https://teamaviatorsinternational.in/#/)
* [Bonolo Mathibela](https://twitter.com/@bonolomathibela) - Spacetime Consulting
* [Mayank Joneja](https://github.com/botmayank) - [Vimaan.ai](https://vimaan.ai/)

