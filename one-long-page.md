# Governance and Maintenance of mobilityDCAT-AP

- Version: 1.0
- Date: 2024-04-12
- Status
  - [ ] To be revised by partners involved in the preparation of the document
  - [ ] For review/ approval by the Core Alignment Team and Peer Reviewers
  - [ ] For approval by the NAPCORE Steering Committee
  - [x] Final
  - [ ] Updated/revised final version (e.g. when a second version of Milestone is published)

**Legal disclaimer**

The sole responsibility for the content of this document lies with the authors.
It does not necessarily reflect the opinion of the European Union.
The European Commission is not responsible for any use that may be made of the information contained therein.
All images are provided by the respective partners (unless otherwise noted) and are approved for reproduction in this publication.

**Document information**

- Project
  - Acronym: NAPCORE
  - Full title: National Access Point Coordination Organisation for Europe
- Grant Agreement No.: MOVE/B4/SUB/2020-123/SI2.852232
- Activity:
  - number: Work Item 4.4.3.1
  - title Governance & maintenance structures
- Author(s):
  - Ed Ooms, NL, National Access Point for Mobility Data
- Co-author(s):
  - Peter Lubrich, DE, BASt
  - Petr Bureš, CZ, University of Prague;
  - Rodolfo da Silva, CY, KIOS Research and Innovation Center of Excellence
- Milestones:
  - Related to Milestone no.: M4.4.2
  - External Milestone: no

## Changelog

### [v0.1] - 2024-03-27

#### Added

- Initial document (by Ed Ooms)

### [v0.9] - 2024-04-09

#### Modifications

- Revisions (by Peter Lubrich, Petr Bureš, Rodolfo Da Silva)

### [v1.0] - 2024-04-12

#### Modifications

- Finalisation (by Ed Ooms)

## Abstract

After in October 2023, the first version of mobilityDCAT-AP was launched, there is a need for a document about Governance and Maintenance.

**Abbreviations**

| Abbreviation | Meaning                                                    |
| ------------ | ---------------------------------------------------------- |
| EC           | European Commission                                        |
| CAT          | Core Alignment Team                                        |
| NAP          | National Access Point                                      |
| NAPCORE      | National Access Point Coordination Organisation for Europe |
| SC, SCOM     | Steering Committee                                         |
| SCS          | Steering Committee Support                                 |
| SWG          | Sub-working Group                                          |
| WG           | Working Group                                              |
| WP           | Working Programme                                          |

## Table of contents

[1 Introduction [4](#introduction)](#introduction)

[2 The DCAT-AP reference
[4](#the-dcat-ap-reference)](#the-dcat-ap-reference)

[2 Tools and Processes [5](#tools-and-processes)](#tools-and-processes)

[**2.1 Issue handling** [5](#issue-handling)](#issue-handling)

[**2.2 Release cycle of mobilityDCAT-AP**
[6](#release-cycle-of-mobilitydcat-ap)](#release-cycle-of-mobilitydcat-ap)

[**2.3 Versioning of mobilityDCAT-AP releases**
[6](#versioning-of-mobilitydcat-ap-releases)](#versioning-of-mobilitydcat-ap-releases)

[**2.4 Maintenance of mobiltyDCAT-AP vs. Controlled Vocabularies**
[6](#maintenance-of-mobiltydcat-ap-vs.-controlled-vocabularies)](#maintenance-of-mobiltydcat-ap-vs.-controlled-vocabularies)

[3 Outlook [7](#outlook)](#outlook)

[**3.1 Challenges and Future**
[7](#challenges-and-future)](#challenges-and-future)

# 1 Introduction

This report presents a concept for governance and maintenance structures for the mobilityDCAT-AP metadata specification.
It imposes the formalities, tools and methods for taking care of the future progress of mobilityDCAT-AP.
The concept is based on best practices on governance and maintenance in other metadata specifications, in particular DCAT-AP.
The concept addresses the following questions:

- What organisational and technical structure should be established? (e.g., who are the maintainers?; what is the technical solution for issue tracking?)
- How to receive, store and process incoming issues and comments about mobilityDCAT-AP?
- What are the workflows to discuss and approve resolutions?

# 2 The DCAT-AP reference

DCAT-AP[^1] is a DCAT profile for sharing information about Catalogues
containing Datasets and Data Services descriptions in Europe, under
maintenance by the SEMIC action, Interoperable Europe[^2].

Interoperable Europe, within its mission to stimulate data interoperability in Europe, manages this specification on the metadata agreements for sharing dataset descriptions between data portals.
The governance is taken care of by the SEMIC action within Interoperable Europe.
Initially, the scope of the specification was the exchange between Open Data Portals in Europe.
Although this is still at the core of the specification, DCAT-AP is not limited to public accessible Open Data but can be applied to any kind of datasets.
In the past decade, DCAT-AP has grown from a single specification to a whole ecosystem of related and interconnected specifications.

Based on DCAT-AP, there are several extensions available for various sectors, for example, the geoDCAT-AP for the geodata sector.
Within the NAPCORE SWG4.4, there is made a new extension for the mobility sector, called mobilityDCAT-AP.

In October 2023 the first version of mobilityDCAT-AP was launched[^3].
Hereafter, there is a need for a concept about Governance and Maintenance.

As far as possible, the same approach is used for the governance and maintenance as in the overarching working method of DCAT-AP.
The DCAT-AP approach is published under the "Change and Release Management Policy for DCAT-AP"[^4].
This represents a standardised approach to achieve a consistent European-level methodology for the management of DCAT-AP implementations and is applied as the main reference for this concept, as explained next.

# 2 Tools and Processes

## **2.1 Issue handling**

Issue handling is considered part of the ongoing efforts of the NAPCORE Metadata Group (SWG 4.4) to establish and curate the new metadata specification mobilityDCAT-AP.
There is an extra work item and milestone related to this, with the working title "napDCAT-AP[^5] Back Office".
Thus, during the project lifetime of NAPCORE, SWG4.4 will take care of the issues on mobilityDCAT-AP, which are managed by different repositories established by SWG 4.4.

On the other side, issue handling as part of a follow-up of NAPCORE needs to be further concretised in the future, see Chapter 3.

Issues can be questions, problems encountered or remarks about former mobilityDCAT-AP releases; or proposals for changes or new functionalities for future releases.
Such changes might be additions, changes or removals of definitions in the mobiltyDCAT-AP data model (including vocabulary terms, ranges, cardinalities and usage notes).
There might be also changes in overarching topics, such as generic management structures.

Any issues can be submitted as issues on the mobilityDCAT-AP repository on GitHub[^6], including issues for the Controlled Vocabularies[^7].
Issues that touch on model elements derived from the DCAT-AP model will be forwarded to the DCAT-AP working group.

It is noted that DCAT-AP has established various roles for the maintenance: among others, there is a "management team", "operational team", and "working group".
However, under the current set-up of SWG 4.4., there is no such separation of maintainers.
I.e., any active SWG member can propose, manage and moderate any issue.
Further, interested parties outside the SWG will be invited to collaborate via GitHub and discuss relevant issues with the SWG.

It is agreed that current issues are regularly discussed at SWG meetings.
Such meeting will be held every two months.
Part of the agenda will be a discussion on the issue backlog.
If a submitter of the issue is outside the SWG, he or she will be invited to the sub-working group\'s meeting to discuss the solution.

For each issue, the submitter of the issue or a SWG member may propose a resolution.
The SWG will then decide to accept a proposal, deny it, or direct it for further discussion.
The acceptance might also include conditions, e.g. "accepted for next minor release / major release ...".

Any resolution will imply a decision to be made in the sub-working group.
In general, a consensus is sought for such decisions.

Similar to processes at DCAT-AP and geoDCAT-AP, concensus-building is organised depending on the impact of the related resolutions:

- Minor resolutions with a lower impact will be proposed by SGW 4.4. members in advance of a SWG meeting.
  They will be considered accepted when there is no opposition at the latest 2 weeks after the SWG 4.4 meeting, where the issue was presented.
- Major resolutions might involve a voting procedure.
  Depending on the severity, the voting might be done during the SWG 4.4 meeting.
  The meeting leader will explain the voting options and let participants vote instantly.
  To reach a consensus, a two-thirds majority of the participants in the meeting is required.
  In more severe cases, a more formal voting involving Member States (representing the NAPCORE community) is required.
  In such cases, each Member State gets one vote, regardless of the number of participants from that Member State.

Decisions are documented on the GitHub repository, where also the issues are managed.

## 2.2 Release cycle of mobilityDCAT-AP

3 different types of changes are foreseen:

- Bugfixes
- Minor semantic changes
- Major semantic changes

**Bugfixes** are corrections of errors or consistencies in the specification.
These will not affect the operability of mobilityDCAT-AP.
Bugfixes will be published in a six-month schedule if they are not combined with other types of release.
For example, every October and April.

**Minor semantic changes** are changes that may affect the interoperability, but only in a non-disruptive way.
Examples are the addition of optional properties or 'deprecation of unused, optional properties.
These changes will be published on a yearly schedule.
For example, every October.

**Major semantic changes** are changes that have (more) serious consequences for interoperability, for example, the addition of mandatory properties or the mandatory controlled vocabulary.
Changes will be published every two years.

## 2.3 Versioning of mobilityDCAT-AP releases

For releases of mobilityDCAT-AP, the following scheme is used:

- Bug fix releases: **X.Y.(Z+1)**, e.g. 1.0.1, 1.0.2, etc.
- Minor semantic releases: **X.(Y+1).0**, e.g. 1.1.0, 1.2.0, etc.
- Major semantic releases: **(X+1).0.0**, e.g. 2.0.0, 3.0.0, etc.

## 2.4 Maintenance of mobiltyDCAT-AP vs. Controlled Vocabularies

SWG 4.4 elaborates two independent products:

- The mobilityDCAT-AP specification as such
- A set of Controlled Vocabularies (which are cited by the mobilityDCAT-AP specification)

Both products are handled by separate GitHub repositories, as explained above.
It is agreed that, in terms of issue tracking and versioning, these two products will remain independent, meaning that mobilityDCAT-AP and the Controlled Vocabularies can be updated independently.
However, the procedures for maintenance, issue tracking, resolutions etc. can be the same.

The reason is that there might be a different pace of evolution for mobilityDCAT-AP vs. the Controlled Vocabularies.
Keeping both independent has the following benefits:

- We can do updates of the Controlled Vocabularies, without \"waiting\" for updates of mobilityDCAT-AP, or vice versa.
- Users have the freedom to deploy ANY version of mobilityDCAT-AP in combination with ANY version of the Controlled Vocabularies.

# 3 Outlook

The presented concept intends to establish maintenance and governance structures supporting mobilityDCAT-AP, in order to make it more sustainable and efficient in a long run.
This is true both for the maintenance of the metadata model itself, and the accompanying Controlled Vocabularies.

This concept is related to a very early stage of mobilityDCAT-AP.
The related SWG in NAPCORE has invested much of its resources into the mobilityDCAT-AP conceptualisation, its initial public release in October 2023, and support actions for early adopters.
In contrast, a proper maintenance and governance routine has not been established yet, including several update cycles or similar.
Thus, this report presents a rather pragmatic and low-tech approach for maintenance and governance, by defining some basic tools and processes for short-term maintenance and governance (within the NAPCORE runtime)

In this scenario,
Thus, the concept needs to be concretised, whenever mobilityDCAT-AP is handed over to a follow-up organization. administrative, management and technical tasks related to maintenance and governance need to be further bundled and institutionalised.
In other words, a proper mobilityDCAT-AP maintenance organization needs to be established with pre-defined tasks and resources.

## **3.1 Challenges and Future**

In merging the discussions on governance and maintenance from the mobilityDCAT-AP extension, several critical considerations emerge, paving the way for addressing challenges and envisioning the future trajectory of the standard.

This includes that the **Issue Handling** is described in greater detail and the maintainers group is clearly identified.
Potential questions for issue tracking to be addressed are:

- Is there any first response to an issue?
- Is somebody preprocessing the issue, dispatching it towards specific maintainers?
- Is there a prepared resolution of the issue before the meeting?
- Is there some core maintainers group and some larger group for e.g. major fixes?

Another strategic challenge might be **under which Organisational Umbrella** the maintenance should happen in the future.
In contrast to (time-limited) projects like NAPCORE, it might be better to look at long-lasting structures, for example at the SEMIC/DCAT-AP umbrella (as already done for geoDCAT-AP and some other extensions).
However, such an organisational setup would have major implications, so further analyses and talks are needed with the EC, SEMIC and the NAP community.

Also, the **Community Engagement and Sustainability** are essential for the success of this extension.
Alike to experiences encountered with GeoDCAT-AP, sustaining active participation from maintainers poses a significant challenge.
Addressing this necessitates devising strategies to foster ongoing engagement and mitigate attrition, ensuring continuity in efforts and investments over time.

Another challenge to consider will be **Interoperability and Standard Compliance**.
The evolving landscape of regulatory frameworks, such as the ITS Delegated Regulations, underscores the importance of interoperability for mobilityDCAT-AP.
Anticipating challenges arising from revisions to regulations or updates to the DCAT-AP standard itself is essential for maintaining alignment and compatibility.

Finally, the **Adoption and Implementation Barriers** challenge should also be considered.
Perceived costs and efforts associated with adoption may deter Member States and organizations from embracing mobilityDCAT-AP.
Overcoming these barriers requires proactive measures to demonstrate the value proposition and streamline implementation processes, thereby preventing the standard from being sidelined.

Altogether, further details on maintenance and governance will be elaborated at a later stage, looking for a successful future of mobilityDCAT-AP.

[^1]: <https://op.europa.eu/nl/web/eu-vocabularies/dcat-ap>

[^2]: <https://joinup.ec.europa.eu/interoperable-europe>

[^3]: <https://napcore.eu/release-of-the-mobilitydcat-ap/>

[^4]: <https://joinup.ec.europa.eu/collection/semic-support-centre/solution/dcat-application-profile-data-portals-europe/document/change-and-release-management-policy-dcat-ap>

[^5]: napDCAT-AP is he predecessor name of mobilityDCAT-AP.

[^6]: <https://github.com/mobilityDCAT-AP/mobilityDCAT-AP//issues>

[^7]: <https://github.com/mobilityDCAT-AP/controlled-vocabularies/issues>
