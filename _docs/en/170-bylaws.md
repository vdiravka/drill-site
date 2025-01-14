---
title: "Project Bylaws"
slug: "Project Bylaws"
---
## Introduction

This document defines the bylaws under which the Apache Drill project
operates. It defines the roles and responsibilities of the project, who may
vote, how voting works, how conflicts are resolved, etc.

Drill is a project of the [Apache Software
Foundation](http://www.apache.org/foundation/). The foundation holds the
copyright on Apache code including the code in the Drill codebase. The
[foundation FAQ](http://www.apache.org/foundation/faq.html) explains the
operation and background of the foundation.

Drill is typical of Apache projects in that it operates under a set of
principles, known collectively as the _Apache Way_. If you are new to Apache
development, please refer to the [Incubator
project](http://incubator.apache.org/) for more information on how Apache
projects operate.

## Roles and Responsibilities

Apache projects define a set of roles with associated rights and
responsibilities. These roles govern what tasks an individual may perform
within the project. The roles are defined in the following sections.

### Users

The most important participants in the project are people who use our
software. The majority of our contributors start out as users and guide their
development efforts from the user's perspective.

Users contribute to the Apache projects by providing feedback to contributors
in the form of bug reports and feature suggestions. As well, users participate
in the Apache community by helping other users on mailing lists and user
support forums.

### Contributors

All of the volunteers who are contributing time, code, documentation, or
resources to the Drill Project. A contributor that makes sustained, welcome
contributions to the project may be invited to become a committer, though the
exact timing of such invitations depends on many factors.

### Committers

The project's committers are responsible for the project's technical
management. Committers have access to a specified set of subproject's code
repositories. Committers on subprojects may cast binding votes on any
technical discussion regarding that subproject.

Committer access is by invitation only and must be approved by lazy consensus
of the active PMC members. A Committer is considered _emeritus_ by his or her
own declaration or by not contributing in any form to the project for over six
months. An emeritus committer may request reinstatement of commit access from
the PMC which will be sufficient to restore him or her to active committer
status.

Commit access can be revoked by a unanimous vote of all the active PMC members
(except the committer in question if he or she is also a PMC member).

All Apache committers are required to have a signed [Contributor License
Agreement (CLA)](http://www.apache.org/licenses/icla.txt) on file with the
Apache Software Foundation. There is a [Committer
FAQ](http://www.apache.org/dev/committers.html) which provides more details on
the requirements for committers.

A committer who makes a sustained contribution to the project may be invited
to become a member of the PMC. The form of contribution is not limited to
code. It can also include code review, helping out users on the mailing lists,
documentation, etc.

### Project Management Committee

The PMC is responsible to the board and the ASF for the management and
oversight of the Apache Drill codebase. The responsibilities of the PMC
include

  * Deciding what is distributed as products of the Apache Drill project. In particular all releases must be approved by the PMC.
  * Maintaining the project's shared resources, including the codebase repository, mailing lists, websites.
  * Speaking on behalf of the project.
  * Resolving license disputes regarding products of the project.
  * Nominating new PMC members and committers.
  * Maintaining these bylaws and other guidelines of the project.

Membership of the PMC is by invitation only and must be approved by a lazy
consensus of active PMC members. A PMC member is considered _emeritus_ by his
or her own declaration or by not contributing in any form to the project for
over six months. An emeritus member may request reinstatement to the PMC,
which will be sufficient to restore him or her to active PMC member.

Membership of the PMC can be revoked by an unanimous vote of all the active
PMC members other than the member in question.

The chair of the PMC is appointed by the ASF board. The chair is an office
holder of the Apache Software Foundation (Vice President, Apache Drill) and
has primary responsibility to the board for the management of the projects
within the scope of the Drill PMC. The chair reports to the board quarterly on
developments within the Drill project.

The term of the chair is one year. When the current chair's term is up or if
the chair resigns before the end of his or her term, the PMC votes to
recommend a new chair using lazy consensus, but the decision must be ratified
by the Apache board.

## Decision Making

Within the Drill project, different types of decisions require different forms
of approval. For example, the previous section describes several decisions
which require 'lazy consensus' approval. This section defines how voting is
performed, the types of approvals, and which types of decision require which
type of approval.

### Voting

Decisions regarding the project are made by votes on the primary project
development mailing list
_[dev@drill.apache.org](mailto:dev@drill.apache.org)_. Where necessary, PMC
voting may take place on the private Drill PMC mailing list
[private@drill.apache.org](mailto:private@drill.apache.org). Votes are clearly
indicated by subject line starting with [VOTE]. Votes may contain multiple
items for approval and these should be clearly separated. Voting is carried
out by replying to the vote mail. Voting may take four flavors.

 <table ><tbody><tr><td valign="top" >Vote</td><td valign="top" > </td></tr><tr><td valign="top" >+1</td><td valign="top" >'Yes,' 'Agree,' or 'the action should be performed.' In general, this vote also indicates a willingness on the behalf of the voter in 'making it happen'.</td></tr><tr><td valign="top" >+0</td><td valign="top" >This vote indicates a willingness for the action under consideration to go ahead. The voter, however will not be able to help.</td></tr><tr><td valign="top" >-0</td><td valign="top" >This vote indicates that the voter does not, in general, agree with the proposed action but is not concerned enough to prevent the action going ahead.</td></tr><tr><td valign="top" >-1</td><td valign="top" >This is a negative vote. On issues where consensus is required, this vote counts as a <strong>veto</strong>. All vetoes must contain an explanation of why the veto is appropriate. Vetoes with no explanation are void. It may also be appropriate for a -1 vote to include an alternative course of action.</td></tr></tbody></table>
  
All participants in the Drill project are encouraged to show their agreement
with or against a particular action by voting. For technical decisions, only
the votes of active committers are binding. Non binding votes are still useful
for those with binding votes to understand the perception of an action in the
wider Drill community. For PMC decisions, only the votes of PMC members are
binding.

Voting can also be applied to changes already made to the Drill codebase.
These typically take the form of a veto (-1) in reply to the commit message
sent when the commit is made. Note that this should be a rare occurrence. All
efforts should be made to discuss issues when they are still patches before
the code is committed.

### Approvals

These are the types of approvals that can be sought. Different actions require
different types of approvals.

<table ><tbody><tr><td valign="top" >Approval Type</td><td valign="top" > </td></tr><tr><td valign="top" >Consensus</td><td valign="top" >For this to pass, all voters with binding votes must vote and there can be no binding vetoes (-1). Consensus votes are rarely required due to the impracticality of getting all eligible voters to cast a vote.</td></tr><tr><td valign="top" >Lazy Consensus</td><td valign="top" >Lazy consensus requires 3 binding +1 votes and no binding vetoes.</td></tr><tr><td valign="top" >Lazy Majority</td><td valign="top" >A lazy majority vote requires 3 binding +1 votes and more binding +1 votes that -1 votes.</td></tr><tr><td valign="top" >Lazy Approval</td><td valign="top" >An action with lazy approval is implicitly allowed unless a -1 vote is received, at which time, depending on the type of action, either lazy majority or lazy consensus approval must be obtained.</td></tr></tbody></table>  
  
### Vetoes

A valid, binding veto cannot be overruled. If a veto is cast, it must be
accompanied by a valid reason explaining the reasons for the veto. The
validity of a veto, if challenged, can be confirmed by anyone who has a
binding vote. This does not necessarily signify agreement with the veto -
merely that the veto is valid.

If you disagree with a valid veto, you must lobby the person casting the veto
to withdraw his or her veto. If a veto is not withdrawn, the action that has
been vetoed must be reversed in a timely manner.

### Actions

This section describes the various actions which are undertaken within the
project, the corresponding approval required for that action and those who
have binding votes over the action. It also specifies the minimum length of
time that a vote must remain open, measured in business days. In general votes
should not be called at times when it is known that interested members of the
project will be unavailable.

<table ><tbody><tr><td valign="top" >Action</td><td valign="top" >Description</td><td valign="top" >Approval</td><td valign="top" >Binding Votes</td><td valign="top" >Minimum Length</td></tr><tr><td valign="top" >Code Change</td><td valign="top" >A change made to a codebase of the project and committed by a committer. This includes source code, documentation, website content, etc.</td><td valign="top" >Consensus approval of active committers, with a minimum of one +1. The code can be committed after the first +1</td><td valign="top" >Active committers</td><td valign="top" >1</td></tr><tr><td valign="top" >Release Plan</td><td valign="top" >Defines the timetable and actions for a release. The plan also nominates a Release Manager.</td><td valign="top" >Lazy majority</td><td valign="top" >Active committers</td><td valign="top" >3</td></tr><tr><td valign="top" >Product Release</td><td valign="top" >When a release of one of the project's products is ready, a vote is required to accept the release as an official release of the project.</td><td valign="top" >Lazy Majority</td><td valign="top" >Active PMC members</td><td valign="top" >3</td></tr><tr><td valign="top" >Adoption of New Codebase</td><td valign="top" >When the codebase for an existing, released product is to be replaced with an alternative codebase. If such a vote fails to gain approval, the existing code base will continue. This also covers the creation of new sub-projects within the project.</td><td valign="top" >2/3 majority</td><td valign="top" >Active PMC members</td><td valign="top" >6</td></tr><tr><td valign="top" >New Committer</td><td valign="top" >When a new committer is proposed for the project.</td><td valign="top" >Lazy consensus</td><td valign="top" >Active PMC members</td><td valign="top" >3</td></tr><tr><td valign="top" >New PMC Member</td><td valign="top" >When a committer is proposed for the PMC.</td><td valign="top" >Lazy consensus</td><td valign="top" >Active PMC members</td><td valign="top" >3</td></tr><tr><td valign="top" >Committer Removal</td><td valign="top" >When removal of commit privileges is sought. <em>Note: Such actions will also be referred to the ASF board by the PMC chair.</em></td><td valign="top" >Consensus</td><td valign="top" >Active PMC members (excluding the committer in question if a member of the PMC).</td><td valign="top" >6</td></tr><tr><td valign="top" >PMC Member Removal</td><td valign="top" >When removal of a PMC member is sought. <em>Note: Such actions will also be referred to the ASF board by the PMC chair.</em></td><td valign="top" >Consensus</td><td valign="top" >Active PMC members (excluding the member in question).</td><td valign="top" >6</td></tr><tr><td valign="top" >Modifying Bylaws</td><td valign="top" >Modifying this document.</td><td valign="top" >2/3 majority</td><td valign="top" >Active PMC members</td><td valign="top" >6</td></tr></tbody></table>

