# Notifications Panel Charter

The mission of the Notifications Panel as part of the W3C Solid Community Group is to extend or define technical protocols and vocabularies to facilitate notification exchange on the Open Web Platform.

* Start date: 2021-09-13
* End date: 2022-12-31
* Charter extension: The charter extension history is documented in "About this charter".
* Confidentiality: Proceedings are Public
* Chair: Sarven Capadisli (Inrupt)
* Team Contact: Solid Editors
* Usual Meeting Schedule: Teleconferences: Weekly, although the chair may call for topic-specific calls in addition when needed and may change working mode as work progresses.

## Goals

The Notifications Panel will create technical reports that standardise protocols and vocabularies for exchanging information as notifications. This should allow Web application developers to embed and facilitate access to social communication on the Web. The panel will explore use cases and requirements pertaining to activities in the Solid ecosystem; identify how existing specifications, including their specialisations and extensions, can be reused; as well as develop new specifications. The work will be driven and refined by implementation experience. The panel will collaborate with other Solid panels and may take on or pass on challenges.

There are a number of use cases that the work of this panel will enable, including but not limited to:

* User control of personal data: Some users would like to have autonomous control over their own social data, and share their data selectively across various systems.
* Activity subscriptions: Actors in the system may want information sent to them about particular data or when certain events or activities take place.
* Resource Access: Access to resources or services to request permission (in order to perform operations).
* Service Actions: Such as activate services, create resources, create/update/delete user accounts, migrate pods, archive pods, or delegate agents to perform tasks.


## Scope

The panel within the framework of the W3C Solid CG and the Solid Project will determine the use cases that derive the requirements for the deliverables. Features that are not implemented due to time constraints can be put into a non-normative "roadmap" document for future work. The scope will include:

* A transfer syntax for data such as activities should include at least the ability to describe the data using URIs in an extensible manner, time-stamping, and a serialization compatible with the RDF language.

* A protocol for exchanging social data should include at least the ability to share notifications using the transfer syntax developed by the Notifications Panel or extend syntaxes such as Activity Streams 2.0. This protocol may allow the capture of new data, the verification of data using techniques such as as digital signatures, server to server interactions, and the use of groups with some form of access control or capabilities.

* Documentation detailing upgrade paths for existing technical reports or notes, including, but not limited to, upgrading deprecated insecure WebSockets to secured WebSockets.

Other components necessary for building federated/decentralized social Web systems are in scope but will not lead to a recommendation without re-chartering, and should be discussed in the Notifications Panel.

### Success Criteria

In order to advance to technical report, the specification is expected to have two independent interoperable implementations of each feature defined in the specification. Independent implementations are developed by different parties and cannot share, reuse, or be derived from code of another qualifying implementation which is directly pertinent to the implementation of this specification.

## Deliverables

### Normative Deliverables

The panel will deliver the following to fulfill its goals, subject to discussion in the Solid CG:

* Notification Protocol
* Notification Syntax

Each of these technologies should not be tightly-coupled but can allow general purpose use. Each specification must contain a section detailing any known security and privacy implications for implementers, Web authors, and end users. The Notifications Panel will actively seek an open security and privacy review for every normative deliverable.

### Other Deliverables

The panel will deliver other non-normative documents, such as the following:

* A Use Cases and Requirements document defining how features in each specification relate to concrete use-cases.
* Test Suites for normative deliverables.
* Upgrade Notes

The panel may also deliver the following:

* Primer or Best Practice documents to support Web developers when designing Solid applications.

### Milestones

The production of the deliverables depends upon the resources available, and will change as new information and implementation experience is reported to the group. The most up-to-date timeline is available from the Solid CG page.

| Specification | ~FPWD   | ~LC     | ~CR     | ~PR     | ~Rec    |
|---------------|---------|---------|---------|---------|---------|
| x             | 2021-Q4 | 2022-Q1 | 2022-Q2 | 2022-Q3 | 2022-Q4 |

Note: The Notifications Panel as part of the W3C Solid CG does not publish technical reports under the W3C Recommendation track. Thus, the milestones in the table above that are prefixed with "~" only communicate rough equivalence in maturity level of the technical reports according to section 6.2.1 of the W3C Process.

## Coordination

Technical coordination with the following Groups may be required:

### W3C Groups

* [Consent CG](https://www.w3.org/groups/cg/consent)
* [Credentials CG](https://www.w3.org/groups/cg/credentials)
* [JSON-LD WG](https://www.w3.org/groups/wg/json-ld)
* [Privacy CG](https://www.w3.org/groups/cg/privacycg)
* [RDF-DEV CG](https://www.w3.org/groups/cg/rdf-dev)
* [Social Web Incubator CG](https://www.w3.org/groups/cg/socialcg)
* [Web Applications WG](https://www.w3.org/groups/wg/webapps)

Furthermore, the Notifications Panel expects to follow the following W3C Recommendations, Guidelines, and Notes, and, if necessary, to liaise with the communities behind them:

* [Architecture of the World Wide Web, Volume I](https://www.w3.org/TR/webarch/)
* [Internationalization Technical Reports and Notes](http://www.w3.org/International/publications)
* [QA Framework: Specification Guidelines](http://www.w3.org/TR/qaframe-spec/)

### External Groups

* TBD

## Participation

Membership in the W3C Solid CG is required to participate in the Notifications Panel. All work and communication within the Solid CG is covered by the [Solid Code of Conduct](https://github.com/solid/process/blob/main/code-of-conduct.md) as well as the [Positive Work Environment at W3C: Code of Ethics and Professional Conduct](https://www.w3.org/Consortium/cepc/).

To be successful, the Notifications Panel is expected to have 10 or more active participants for its duration and to have the participation of industry leaders in fields relevant to the specifications it produces. The Chairs and specification Editors are expected to contribute one to two days per week towards the Panel. The Chair may call occasional meetings consistent with the W3C Process requirements for meetings. There is no minimum requirement for other Participants.

The Notifications Panel will also allocate the necessary resources for building test suites for each specification.

The group encourages questions and comments on its project repository, as described in Communication.

## Communication

Most Notifications Panel Teleconferences will be conducted on an as-needed basis. Normally, at least one teleconference will be held per week.

Most of the technical work of the panel will be done through:

* Repository: https://github.com/solid/notifications-panel
* Discussions: https://gitter.im/solid/notifications-panel

Information about the panel (for example, details about deliverables, issues, actions, status, and participants) will be available from the Notifications Panel repository.

## Decision Policy

As explained in the W3C Process Document (section 3.3), this group will seek to make decisions when there is consensus and with due process. The expectation is that typically, an Editor or other participant makes an initial proposal, which is then refined in discussion with members of the group and other reviewers, and consensus emerges with little formal voting being required. However, if a decision is necessary for timely progress, but consensus is not achieved after careful consideration of the range of views presented, the Chairs should put a question out for voting within the group (allowing for remote asynchronous participation -- using, for example, chat channel or panel repository) and record a decision, along with any objections. The matter should then be considered resolved unless and until new information becomes available.

This charter is written in accordance with Section 3.4, Votes of the W3C Process Document and includes no voting procedures beyond what the Process Document requires.

## Licensing

The panel will use the MIT license for all its deliverables.

## Patent Policy

This W3C Solid Community Group operates under the W3C Community Contributor License Agreement (CLA).

## About this Charter

This charter for the Notifications Panel has been created according to section 5.2 of the W3C Process Document. In the event of a conflict between this document or the provisions of any charter and the W3C Process, the W3C Process shall take precedence.

### Charter History

The following table lists details of all changes from the initial charter, per the W3C Process Document (section 5.2.3):

| Charter Period  | Start Date | End Date   | Changes    |
|-----------------|------------|------------|------------|
| Initial Charter | 2019-08-23 | 2021-09-12 |            |
