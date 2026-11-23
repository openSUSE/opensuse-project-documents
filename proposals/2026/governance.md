# openSUSE Governance Proposal 20261123.0

## Introduction and Purpose

The openSUSE Project has grown into a broad and diverse ecosystem: a rolling distribution, multiple downstreams and derivatives, shared infrastructure, and a global contributor community with many different perspectives. This diversity is one of openSUSE's greatest strengths. At the same time, it has exposed a structural weakness in how the project makes decisions.

Today, many important technical and strategic questions are resolved informally. Outcomes often depend on who has the most time, the loudest voice, or the greatest persistence, rather than on a clearly defined decision-making process. This has led to prolonged deadlocks, unclear stewardship of cross-cutting decisions, contributor fatigue, and difficulty coordinating larger changes that span multiple areas of the project.

This document proposes a governance framework intended to address those issues while preserving the open, contributor-driven nature of openSUSE. Its goal is not to centralize power or impose predetermined technical outcomes, but to establish legitimate, transparent structures so that decisions can be made fairly, predictably, and in the open.


The openSUSE Board retains its current composition and core roles in organizational stewardship and the project's relationships with its legal and financial stewards. The proposal adds oversight and appeal functions over the [TSC](#technical-steering-committee) and [CMC](#community--marketing-committee).


## Guiding Principles

This proposal is grounded in several core principles.

First, technical leadership should be earned through contribution and trust, but exercised with accountability. Authority should be explicit, scoped, and subject to clear processes rather than emerging implicitly through social dynamics.

Second, transparency should be the default. Decisions, rationales, and outcomes should be visible to the community, except where legal or personal-safety concerns require otherwise.

Third, the project should always seek consensus, but consensus cannot be allowed to become paralysis. When agreement cannot be reached, there must be a legitimate and accepted mechanism for arbitration.

Fourth, predictability matters. Clear decision points and deadlines are more valuable than endlessly deferring decisions in pursuit of an ideal solution.

Finally, governance exists to empower contributors, not to replace them. Maintainer autonomy, open participation, and community elections remain foundational to the project.


## Governance Structure Overview

Under this proposal, the openSUSE Project operates through three complementary governance bodies.

The [openSUSE Board](#the-opensuse-board) continues in its current role as defined by the [Board's governing documents](#the-opensuse-board), with responsibility for organizational stewardship and the project's relationships with its legal and financial stewards.

The [Technical Steering Committee](#technical-steering-committee) (TSC) is responsible for technical direction, coordination, and arbitration of technical disputes.

The [Community & Marketing Committee](#community--marketing-committee) (CMC) is responsible for community growth, outreach, onboarding, external messaging, and the health of community spaces, including the Code of Conduct and moderation functions.

Each body has a deliberately limited and well-defined mandate in order to reduce overlap, ambiguity, and informal power structures.


## The openSUSE Board

In this document, "the Board's governing documents" means the [openSUSE Guiding Principles](https://en.opensuse.org/openSUSE:Guiding_principles#Governance) and the [Board election rules](https://en.opensuse.org/openSUSE:Board_election_rules), as in effect on the date this proposal is put to a vote.

The [openSUSE Board](https://en.opensuse.org/Board) remains the top-level governing body of the project. Its responsibilities include acting as the project's point of contact with SUSE (as trademark holder) and the Geeko Foundation (in financial matters), formal representation of the project, ratification of governance changes, and resolution of conflicts that span or involve governance bodies themselves.

The Board does not set detailed technical direction, arbitrate routine technical disputes, or manage release engineering. Where appropriate, it may delegate authority to committees while retaining ultimate oversight consistent with the Board's governing documents.


## Provisions Common to Both Committees

The following provisions apply equally to the [Technical Steering Committee](#technical-steering-committee) and the [Community & Marketing Committee](#community--marketing-committee).

### Composition

Each committee consists of five voting members unless adjusted under the [committee-size provision](#committee-size) below.

Members of a committee may serve on other committees or working groups, but may not simultaneously sit on the openSUSE Board as voting members.

### Elections

Committee members are elected by openSUSE members, using the same electorate and eligibility rules as openSUSE [Board elections](https://en.opensuse.org/openSUSE:Board_election_rules), and administered by the openSUSE Election Committee as part of the regular election cycle.

Members serve two-year terms. No member may serve more than two consecutive terms; a member becomes eligible again after one full term out of office.

Terms are staggered so that approximately half of each committee's seats are elected each year. In the first election held for a committee under the [Transitional Plan](#transitional-plan), the candidates receiving the highest number of votes, up to a majority of the committee's seats, receive two-year terms; the remaining elected candidates receive one-year terms. A tie at the boundary between a two-year and a one-year term is resolved under the tie-breaking rules used for Board elections. Terms end at the conclusion of the regular election cycle in the year they expire, regardless of when the first election was held. A one-year term served by a member elected in the first election does not count as a term for the purposes of the consecutive-terms limit. Thereafter all terms are two years.

### Committee Size

The Board may, by a two-thirds vote of its voting members, set the size of a committee to any odd number between three and nine. A change in size:

- (a) takes effect only at that committee's next regular election;
- (b) does not shorten the term of any sitting member — a reduction is implemented by filling fewer seats at the elections where terms expire, until the committee reaches its new size, never by removal;
- (c) must be published with a written rationale at least sixty days before nominations open for that election; and
- (d) may not be changed again for that committee until the following regular election.

### Chair

At its first meeting after each regular election, the committee elects a chair by majority vote of its voting members, to serve until the next regular election. If the chair's seat becomes vacant or the chair steps down, the committee elects a replacement to serve for the remainder of that period. The chair is responsible for the agenda of committee meetings, attends openSUSE Board meetings as a standing non-voting observer with speaking rights, and reports to the Board on the committee's activities. The chair may designate another committee member to attend a Board meeting in their place, with written notice to the Board.

### Meetings, Quorum, and Voting

Each committee meets at least monthly and publishes a meeting schedule. Quorum is a majority of filled seats. Decisions require the affirmative vote of a majority of the committee's filled voting seats, not merely of those present. A committee with fewer than three filled seats makes no decisions other than filling vacancies. A member discloses any direct personal or employer interest in a matter before the committee.

### Resignation and Vacancies

A member may resign at any time by written notice to the committee and the Board, effective immediately or on a stated future date. A member who misses three or more consecutive scheduled meetings without notice is treated as having resigned, unless a majority of the remaining voting members votes to retain them.

The Board may remove a member for serious misconduct or for persistent failure to perform the duties of the office, by a two-thirds vote of its voting members, after giving the member written notice of the grounds and an opportunity to respond. The Board publishes its reasons, subject to the confidentiality provisions of the [Transparency](#transparency) section.

When a seat becomes vacant, the committee appoints a replacement by majority vote of its remaining voting members, subject to ratification by the Board. The appointee serves until the next regular election, at which point the seat is filled by election for the remainder of the original term.

### Dissolution

The Board may dissolve a committee and call a full election of all its seats only by a two-thirds vote of its voting members, after:

- (a) publishing written findings that the committee has failed to meet for ninety days, or has materially failed to fulfill its mandate;
- (b) giving the committee thirty days to respond publicly to those findings; and
- (c) a further public notice period of at least thirty days before the election.

This power may be exercised at most once per committee in any two-year period. Dissolution is not a finding of misconduct against any member, and all members may stand again. The committee continues to serve until the members elected in the full election take their seats.

### Transparency

Each committee operates transparently. Agendas, meeting notes, decisions, votes, and dissenting opinions are published. Each committee publishes an annual retrospective of its activities.

Material may be withheld or redacted where legal, security, or personal-safety concerns require, including matters involving the Code of Conduct, undisclosed security vulnerabilities, and privileged legal advice.

### Operating Procedures

Each committee adopts and publishes its own operating procedures, consistent with this document. Changes to operating procedures are decided by the committee and do not require the [governance-change process](#evolution-of-governance) described below.


## Community & Marketing Committee

### Role and Mandate

The Community & Marketing Committee is responsible for growing and sustaining the openSUSE community. Its focus includes outreach, onboarding, contributor retention, advocacy, events, external messaging, and the overall health of community interaction spaces.

The CMC is the steward of the project's community-facing communication environments. The existing Code of Conduct team and moderation teams for project-sanctioned platforms operate under the CMC. The CMC maintains the Code of Conduct and community participation standards, supports and coordinates moderators, and provides escalation paths and consistency across platforms.

The CMC's role in this area is facilitative and supportive rather than punitive. Day-to-day moderation is handled by designated moderators familiar with each space; the committee provides guidance, escalation, and consistency.

Complaints about the conduct of a CMC member are referred to the Board, and the member takes no part in the CMC's handling of them.

The committee does not set technical direction or override technical decisions.

### Composition

The CMC should collectively represent a mix of backgrounds, including documentation, advocacy, design, events, and communications.

### Transparency and Accountability

In addition to the common transparency requirements, the CMC publishes goals and metrics related to community growth and engagement.

### Review of Decisions

A decision of the CMC, or of the Code of Conduct or moderation teams, may be appealed to the Board on the same terms as a TSC decision under "[Appeal](#appeal)," once any appeal process within those teams has been completed, and subject to the provisions of the [Transparency](#transparency) section.

## Technical Steering Committee

### Role and Mandate

The Technical Steering Committee provides clear technical leadership for the openSUSE Project. Its role is to help the project set and maintain coherent technical direction, particularly where decisions span multiple subsystems, products, or contributor groups.

The TSC develops and maintains project-level technical roadmaps and serves as the final technical arbitrator when consensus cannot be reached through normal discussion. It is explicitly empowered to define, modify, or retire project-level coordination mechanisms intended to improve predictability and alignment across the project. These may include milestones, checkpoints, planning cycles, or other coordination constructs proposed by the community. The specific form, cadence, and criteria of any such mechanisms are decisions of the TSC, made under the [Decision-Making](#decision-making) provisions below, and are not prescribed by this document. The TSC reviews each mechanism at least annually and publishes whether it will continue, change, or be retired.

The TSC's role is strategic and coordinative rather than operational. It does not manage day-to-day implementation work and does not micromanage individual packages.

### Scope and Binding Effect of Decisions

TSC decisions are binding on project-level resources and processes: distribution-wide policies, release processes and schedules, shared build and integration tooling, and coordination mechanisms that span multiple packages or subsystems. For shared build and integration tooling, a TSC decision sets project-level requirements and priorities. It does not direct the operation of services run by the openSUSE Heroes or by SUSE IT, and it takes effect for those services only through the process described in "[Relationship to Other Governance Bodies](#relationship-to-other-governance-bodies)."

TSC decisions do not compel individual maintainers to perform work. Maintainers retain stewardship and day-to-day control of their packages. Where a maintainer declines to implement a TSC decision, the TSC's role is to ensure the project is not indefinitely blocked, through the following steps in order:

1. The decision and its rationale are published, and the maintainer is given the opportunity to explain concerns or constraints.
2. A non-blocking path forward is identified: delegating the work to other contributors, sharing maintainership, or the maintainer stepping back from the affected area.
3. If necessary, the TSC may authorize parallel or alternative implementations, replacements or variants, or migration paths that allow the project to progress without action by the unwilling maintainer.
4. Only where a maintainer has declined, after the steps above, to hand off, delegate, or share the affected work, and the project remains blocked, may changes to maintainership or package status be considered. Such steps require written findings, are not punitive, and may be appealed to the Board on the terms described in "[Appeal](#appeal)."

### Composition

TSC members must have demonstrated, sustained technical contributions to openSUSE. Collectively, the committee should represent a broad range of experience, including distribution engineering, release engineering, infrastructure and tooling, and both desktop and server perspectives.

### Decision-Making

Proposals must be discussed publicly and include a clear problem statement and rationale. The committee always seeks consensus first. When consensus cannot be achieved, the TSC decides by vote under the [common voting rules](#meetings-quorum-and-voting). Decisions, votes, and minority opinions are documented and published so the community can understand both the outcome and the reasoning.

### Appeal

A TSC decision may be appealed to the openSUSE Board within thirty days of publication. An appeal does not suspend the decision unless the Board so decides. The Board decides within thirty days of receiving the appeal, reviewing only whether the TSC followed its published procedures and acted within its mandate; it does not review the technical merits. If the Board finds a procedural defect, it returns the decision to the TSC for reconsideration, and the reconsidered decision may be appealed again only on new procedural grounds.


## Infrastructure Stewardship

### Role and Scope

The openSUSE Project depends on substantial infrastructure, including build systems, mirrors, authentication services, collaboration platforms, and other critical services. Much of this infrastructure is designed, operated, and maintained by a volunteer group commonly known as the openSUSE Heroes. Their work is essential to the project's success and has historically been organized through trust, expertise, and informal coordination.

This proposal does not change the fundamental nature of that work. Infrastructure stewardship remains primarily volunteer-driven and grounded in contribution and responsibility rather than formal authority. This section introduces clearer visibility, reporting, and escalation paths for infrastructure concerns, particularly where those concerns have project-wide impact or span both volunteer-managed and SUSE-operated environments.

### Responsibilities

Infrastructure stewards are responsible for the reliable operation and evolution of project infrastructure, including routine maintenance, incident response, capacity planning, and coordinating changes that may affect contributors or users. When infrastructure changes or incidents have broader impact, stewards communicate that impact clearly so the project understands what is happening and why.

### Reporting and Coordination

The infrastructure team designates, by its own internal process, a primary point of contact and notifies the Board of the designation. The point of contact serves as the interface between infrastructure maintainers and the project's governance bodies, and reports to the Board at least quarterly on infrastructure status, incidents with project-wide impact, and issues that cross organizational boundaries — particularly between volunteer-managed infrastructure and infrastructure operated or funded by SUSE.

### Escalation

Most infrastructure issues are resolved within the infrastructure team. Escalation is appropriate only when an issue materially affects the broader project, cannot be resolved through normal operational channels, or requires coordination beyond the infrastructure team. In such cases, matters may be brought to the openSUSE Board, which retains responsibility for resolving cross-cutting organizational concerns and coordinating with SUSE where necessary.

### Relationship to Other Governance Bodies

Infrastructure stewardship is operational in nature and does not set technical direction or community policy. Where a TSC decision would affect infrastructure, the TSC consults with the relevant infrastructure team before deciding, and publishes the team's response with the decision. Infrastructure operators remain responsible for how and when changes are implemented, and may decline or defer requirements that cannot be safely or practically met, stating their reasons publicly. Where infrastructure issues affect community platforms or contributor experience, coordination with the CMC may be appropriate. The Board is the escalation path if the TSC and infrastructure team find themselves in a stalemate.


## Working Groups

Both the TSC and CMC may charter working groups to address specific, well-scoped problems. Working groups are time-bound, operate under a clear written mandate, and dissolve once their objectives are met or their mandate expires. They report to their sponsoring committee.


## Conflict Resolution

Conflicts are resolved at the lowest reasonable level. Issues are first addressed within the relevant community or working group, then escalated to the appropriate committee. Conflicts that are unresolved, cross-cutting, or involve governance bodies themselves may be escalated to the openSUSE Board. All stages of resolution are documented.


## Evolution of Governance

This document is intended to evolve. Any openSUSE member, committee, or the Board may make a public proposal to change it. Changes require a minimum thirty-day discussion period and ratification by the openSUSE Board, except as provided below.

Changes to the following provisions additionally require approval by openSUSE members in a ballot, by the same threshold required to adopt this proposal: [Elections](#elections), [Committee Size](#committee-size), [Resignation and Vacancies](#resignation-and-vacancies), [Dissolution](#dissolution) under the common provisions, [Scope and Binding Effect of Decisions](#scope-and-binding-effect-of-decisions), [Relationship to Existing Governance Documents](#relationship-to-existing-governance-documents), and [this section](#evolution-of-governance). The Board may not ratify such changes until members have approved them. A change that would have the effect of changing one of these provisions is treated as a change to that provision.

Committee operating procedures are governed by the [provision above](#operating-procedures) and are not subject to this process.


## Relationship to Existing Governance Documents

This document supplements the [Board's governing documents](#the-opensuse-board). Where conflicts exist, this document controls, but only on the matters it expressly addresses. In particular, it amends, under the [Guiding Principles](https://en.opensuse.org/openSUSE:Guiding_principles#Governance), the Board's role in conflict resolution and facilitation of decision making, to the extent described in "[Role and Mandate](#role-and-mandate-1)" under the TSC, "[Conflict Resolution](#conflict-resolution)," and "[Appeal](#appeal)." On any other matters, the Board's governing documents continue unchanged.

## Transitional Plan

Upon ratification, the Board appoints interim members of the Technical Steering Committee and the Community & Marketing Committee. Interim bodies operate under this document for a period not exceeding six months, during which election procedures and initial operating practices are finalized. Formal elections are held at or before the end of the interim period. If elections have not been held by then, the interim period is extended once, by up to ninety days, and the Board will publish the reason for the delay and the revised election date. During an extension, the interim bodies will continue to serve, but will not adopt new project-level coordination mechanisms or make changes to maintainership or package status. If elections have not occurred before the end of the extension, the Board will direct the Election Committee to hold an emergency election within sixty days. The interim members will serve until their successors are elected.

Interim service does not count toward term limits.

The existing moderation teams continue with their current members and records, which remain confidential, and come under the CMC upon ratification. Any change to their membership or processes is made afterward through the CMC's operating procedures.


## Ratification

This proposal is submitted to openSUSE members as a ballot question in the next regular election. It is adopted if approved by a simple majority of votes cast. Upon adoption, the Board ratifies this document and the [Transitional Plan](#transitional-plan) takes effect. This proposal does not amend the [Board election rules](https://en.opensuse.org/openSUSE:Board_election_rules), but extends them to committee elections; its only effect on Board eligibility is that a person may not hold voting seats on both the Board and a committee concurrently. If not adopted, the current governance arrangements continue unchanged.


## Appendix: Frequently Asked Questions

This appendix is explanatory and is not part of the operative text of this proposal. If there are any conflicts with the sections above, the sections above take precedence.

### What happens if the TSC agrees on a direction, but a package maintainer disagrees or refuses to implement it?

Disagreement with a TSC decision is not, by itself, a problem. Maintainers are not employees, and the TSC does not compel unpaid labor or force individual contributors to implement changes they do not support. The process is defined in "[Scope and Binding Effect of Decisions](#scope-and-binding-effect-of-decisions)" above.

In short: **the TSC does not force maintainers to act, but it does ensure that the project is not indefinitely blocked from acting.**


### Is this an attempt by SUSE (or any other company) to take control of openSUSE?

No. This proposal grants no special authority to employers, vendors, or sponsors. All committee members are elected by openSUSE members, serve limited terms, and operate transparently. Decisions, votes, and rationales are public.

The openSUSE Board already exists under its governing documents, and this proposal does not change its core role. It does enumerate a small set of new oversight powers over the committees (resizing, removing members for misconduct, dissolving committees, and hearing appeals of those committees' decisions), each subject to the limits described above, published rationale, and notice periods.


### Does this mean maintainers lose control over their packages?

No. Maintainers retain stewardship and day-to-day control of their packages. The TSC does not micromanage packages, assign work, or force changes.

What changes is that when a decision affects the project as a whole and consensus cannot be reached, there is a legitimate process to decide a direction and enable progress without relying on informal pressure or stalemates.


### Why create new committees instead of expanding the openSUSE Board?

The Board's established responsibilities focus on organizational stewardship and the project's relationships with its legal and financial stewards. Adding detailed technical arbitration or community growth responsibilities to the Board would overload it and blur accountability.

Separating technical direction, community growth, and organizational stewardship allows each area to be handled by contributors with the appropriate expertise, while keeping mandates clear and limited.


### Why is this being proposed now?

This proposal reflects issues that have been discussed within the community for several years, including at recent openSUSE conferences. It is not a reaction to a single incident, but an attempt to address recurring patterns: prolonged deadlocks, unclear stewardship of cross-cutting decisions, and contributor burnout.

The goal is to move from governance by volume or persistence to governance by legitimacy and process.


### Can the Board use the resize or dissolution powers to control a committee?

Both powers are deliberately constrained. A resize takes effect only at the next election, cannot remove a sitting member, requires sixty days' public notice with a rationale, and cannot be repeated until the following election. Dissolution requires a two-thirds Board vote, published findings, a thirty-day response window for the committee, and a further thirty days' notice, and may be used at most once per committee in two years. Neither power allows the Board to select committee members; resizing affects only the next election, and dissolution is followed by a full election. Interim and vacancy appointments are limited and described in the [Transitional Plan](#transitional-plan) and the [vacancy provisions](#resignation-and-vacancies).

### Does this proposal change how openSUSE infrastructure is run?

No. Infrastructure remains volunteer-driven, as it is today. The proposal adds a designated point of contact, who reports to the Board at least quarterly, and an escalation path for issues with project-wide impact, or that span volunteer-run and SUSE-operated systems. The TSC consults the infrastructure teams before making decisions that affect it, and operators decide how and when changes are implemented. See "[Infrastructure Stewardship](#infrastructure-stewardship)" above.

### What if this governance model does not work?

This document includes an explicit process for change and revision. If parts of the model are ineffective or have unintended consequences, the community can propose and ratify changes through the same transparent process.

Governance is a tool, not an end state.


### Does this proposal give the CMC power to censor or police community discussions?

No. The CMC's role with respect to communication platforms is stewardship and support, not centralized enforcement.

The CMC maintains shared community standards, supports and coordinates volunteer moderators and the Code of Conduct team, and provides escalation paths when issues span multiple project-sanctioned platforms. Day-to-day moderation remains with local moderators familiar with the context and norms of their respective spaces.

The intent is to promote consistency, fairness, and healthy discourse across the project, reduce burnout among moderators, and ensure contributors know where to turn when problems arise. The CMC does not exist to suppress disagreement or control technical debate.
