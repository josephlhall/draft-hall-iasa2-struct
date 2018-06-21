---

title: Proposed Structure of the IETF Administrative Support Activity (IASA), Version 2.0 (for Discussion)
abbrev: IASA 2.0
docname: draft-ietf-iasa2-struct-00
category: info

ipr: trust200902
area: General
keyword: Internet-Draft
wg: IASA2

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
  -
    ins: B. Haberman
    name: Brian Haberman
    organization: Johns Hopkins University
    email: brian@innovationslab.net
  -
    ins: J. Hall
    name: Joseph Lorenzo Hall
    organization: CDT
    email: joe@cdt.org
  -
    ins: J. Livingood
    name: Jason Livingood
    organization: Comcast
    email: jason_livingood@comcast.com

informative:
  RFC2119:
  author: Scott Bradner
  org: Harvard University
  date: 1997-03
  target: https://www.ietf.org/rfc/rfc2119.txt

  RFC7437:
  author: Murray Kucherawy
  date: 2015-07
  target: https://tools.ietf.org/html/rfc7437

  ML-memo:
    title: Options for New Organization to Conduct IETF Administrative Support Activities
    author:
      org: Morgan Lewis
    date: 2018-02
    target: https://mailarchive.ietf.org/arch/msg/iasa20/XT_3vfd3OWVFCW335mRrvWuusaI/

  Diagrams:
    title: IASA 2.0 Strawman Diagram
    author:
      name: Richard Barnes
      ins: R. Barnes
    dates: 2018-02-16
    target: https://ipv.sx/iasa2.0/IASA-Strawman.pdf

  Diagrams-no-trust:
    title: IASA 2.0 Strawman Diagram, IETF Trust Not Shown
    author:
      name: Richard Barnes
      ins: R. Barnes
    dates: 2018-02-16
    target: https://ipv.sx/iasa2.0/IASA-Strawman-NoTrust.pdf

  ietf101-slides:
    title: IASA 2.0 IETF-101 Slides
    author:
      name: Joe Lorenzo Hall
      ins: J.L. Hall
    dates: 2018-03-20
    target: https://datatracker.ietf.org/meeting/101/materials/slides-101-iasa20-dt-iasa-slides-00

--- abstract

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization, the IETF Administration Limited Liability Corporation ("LLC"). Under the proposal, the Internet Administrative Oversight Committee (IAOC) will be eliminated, and its oversight and advising functions transferred to the new LLC Board.

--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization, the IETF Administration Limited Liability Corporation ("LLC"). Under the proposal, the Internet Administrative Oversight Committee (IAOC) will be eliminated, and its oversight and advising functions transferred to the new LLC Board. This document explores all of the details involved in the proposal.

{{?I-D.haberman-iasa20dt-recs}} discusses the challenges facing the current structure as well as several options for reorganizing the IETF's administration under different legal structures. This document outlines how such an organization will be structured and describes how the organization will fit together with existing and new IETF community structures.

This document outlines some details of a potential "IASA 2.0" arrangement. Some of the details of the organizational structure are dependent on the choice of legal structure, but others are not. The point of this document is to solicit community input about how to address the challenges identified in {{?I-D.haberman-iasa20dt-recs}}. Ultimately, if the IETF community decides to make changes to IASA, those changes will subsequently be documented in a replacement of RFC 4071 (BCP 101) and RFC 4371.

The proposal in this document is to transfer most of the responsibilities that RFC 4071 currently assigns to the Internet Administrative Director (IAD) and Internet Society (ISOC) to the newly created LLC. The IAOC would be eliminated, and its oversight and advising functions transferred to the LLC Board. It would be the job of LLC to meet the administrative needs of the IETF and ensure that LLC and IASA 2.0 is meeting the needs of the IETF community.

Eliminating the IAOC means that there will need to be another way for trustees to be appointed for the IETF Trust. The details of how this is done are outlined in (PLACEHOLDER: FILL IN WITH I-D NAME IN FUTURE UPDATE).

The proposal in this document is depicted visually in {{Diagrams}} showing the IETF Trust and {{Diagrams-no-trust}} not showing the IETF Trust. (NOTE: DIAGRAMS WILL BE UPDATED AS CONSENSUS FURTHER DEVELOPS, IN A FUTURE UPDATE)


# Scope Limitation

The document does not propose any changes to anything related to the oversight or steering of the standards process as currently conducted by the Internet Engineering Steering Group (IESG) and Internet Architecture Board (IAB), the appeals chain, the process for making and organizations involved in confirming IETF and IAB appointments, the IETF Nominations Committee (NomCom), the Internet Research Task Force (IRTF), or ISOC's memberships in or support of other organizations.

If the community decides to make changes to IASA along the lines sketched out in this document, normative changes to IETF processes will need to be documented in an RFC. Additional legal documents (e.g., certificate of formation, operating agreement, transition and shared services agreement) relating to the legal entity would provide the official, legal definitions of processes, roles, etc. {{transition-considerations}} sketches some initial thoughts about transition; publishing a detailed transition plan would likely also be useful.

## Operating Agreement with the Internet Society
The Operating Agreement (OA) is also out of scope for this document. The OA will be developed between the IETF and ISOC and is expected to include all critical terms, while still enabling maximum unilateral flexibility for the LLC Board. Thus, it is anticipated that the OA will include only basic details about how the Board manages itself or manages LLC staff, so that the LLC Board has flexibility to make changes without amending the OA. The LLC Board can independently develop policy or procedures documents that fill gaps.


# Key Differences from the IASA 1.0 Structure

* The IAOC and IAD roles defined in RFC 4071 are eliminated. (NOTE: ONE WG TASK IS TO REPLACE RFC 4071)

* The ISOC and IAD responsibilities described in RFC 4071 are assigned to a new organization, IETF Administration LLC.

* The Board of Directors of the LLC -- formerly a multi-member "manager" of the LLC on behalf of ISOC -- will assume the oversight responsibilities of the IAOC.

* The Board of the LLC shall be more focused on strategy and oversight, with the Executive Director and their team in charge of day-to-day operations.


# IETF Administration LLC

## General LLC Responsibilities {#llc-responsibilities}

The LLC will be established to provide administrative support to the IETF. It will have no authority over the standards development activities of the IETF.

The proposed responsibilities of the LLC are:

* Operations. The LLC is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The LLC is responsible for managing the IETF's finances and budget.

* Fundraising. The LLC is responsible for raising money on behalf of the IETF.

* Compliance. The LLC is responsible for establishing and enforcing policies to ensure compliance with applicable laws, regulations, and rules.

The manner by which these responsibilities under the LLC are organized is intended to address the problems described in Sections 3.1.1., 3.1.2, and 3.1.3 of {{?I-D.haberman-iasa20dt-recs}}. Specifically, this is intended to bring greater clarity around roles, responsibilities, representation, decision-making, and authority.

In addition, by having the LLC manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds will be eliminated. Finally, having the LLC reside in a defined, distinct legal entity, and taking responsibility for operations, will enable the organization to execute its own contracts without the need for review and approval by ISOC.

## LLC Working Principles {#principles}

The LLC will be expected to conduct its work according to the following proposed principles:

* Transparency. The LLC will keep the IETF community reasonably informed about its work and will engage with the community to obtain consensus-based community input on key issues and otherwise as needed. As discusses in {{ietf101-slides}}, whatever doesn't have a specific justification for being kept confidential, should be made public. There must exist a public list of confidential items, describing the nature of the information and the reason for confidentiality.

* Responsiveness to the community. The LLC will act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and adapt its decisions in response to consensus-based community feedback.

* Diligence. The LLC will act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole, such as financial risks.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. The issue of increased transparency was important throughout the IASA 2.0 process, with little to no dissent.  It was recognized that there will naturally be a confidentiality requirement about some aspects of hotel contracting, personnel matters, and other narrow areas.

## LLC Board Responsibilities {#board-responsibilities}

The LLC Board will be responsible for conducting oversight of LLC's execution of its responsibilities, as described in {{llc-responsibilities}}.  They have duties of loyalty, care, and good faith. This includes the responsibility to:

* provide strategic direction for the LLC and to the Executive Director;

* hire, supervise, and manage the employment of the role of the Executive Director of LLC, including tasks such as hiring, termination, performance review, amendment of employment terms, the award of compensation and other requisite employment benefits or decisions;

* adopting any employee benefit plans;

* approving any changes to the LLC governance structure;

* exercising a fiduciary duty to ensure that LLC has the financial and business stability that it needs to be able to meet the needs of the IETF, including adopting an annual budget, and as necessary incurring any debt or making other financial arrangements;

* approving or entering into agreements that that meet a significant materiality threshold;

* exercising a legal duty to ensure that the LLC complies with any applicable tax and other laws;

* ensuring that LLC is run in a manner that is transparent and accountable to the IETF community;

* recruit new Directors, for consideration in all of the various appointment processes.

The Board will be an oversight body, with responsibilities limited to those listed above. It will not directly conduct any of the IETF's administrative work, which is the day-to-day job of the Executive Director at their team.

The role of the LLC Board will be to ensure that the strategy and conduct of LLC is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The Board is not intended to directly define the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus-based RFCs (e.g., as the community is aiming to do in {{?I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via consultations with the LLC Board (such as takes place on email discussion lists or at IETF meetings).

As part of the responsibilities outlined above, some of which is outlined further in (TODO: reference board-policies document) the Board shall work to ensure that LLC will:

* Act consistently with ISOC’s 501(c)(3) status;

* Provide accurate financial statements to ISOC on a timely basis;

* Prepare its financial reports in accordance with generally accepted accounting principles;

* Provide assistance to help facilitate ISOC’s tax compliance, including but not limited to assistance related to preparing the Form 990 and responding to any IRS questions and audits;

* Obtain appropriate insurance, including commercial general liability insurance with appropriate limits;

* Implement risk management and compliance processes in a manner consistent with industry norms.

The description below outlines the composition of the LLC Board, selection of LLC Board Directors, and related details.

## Executive Director and Staff Responsibilities {#staff-responsibilities}

The LLC shall be led by an Executive Director chosen by the Board. The Executive Director will be responsible for managing the day-to-day operations of the LLC, including hiring staff to perform various operational functions. The Executive Director and any staff may be employees or independent contractors.

Allowing for the division of responsibilities among multiple staff members and contractors should hopefully address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{?I-D.haberman-iasa20dt-recs}}.

Based on the amount of work currently undertaken by the IAD and others involved in the IETF administration who are not currently in contracted roles, it is anticipated that the Executive Director may need to hire multiple additional staff members. For example, there will likely be a need for resources to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications.

The IETF currently benefits from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). The IETF budget currently reflects specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors will be at the discretion of the Executive Director and his or her staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the EDU and Mentoring Directorate. The LLC staff would be expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the LLC to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists (see {{transition-considerations}}).

In summary, the LLC Executive Director, with support from the team that they alone direct and lead, will be responsible for:
* Developing and refining an annual budget and other strategic financial planning documents at the direction of the LLC Board.
* Executing on the annual budget, including reporting to the LLC Board regularly with forecasts and actual performance to budget.
* Hiring and/or contracting the necessary resources to meet their goals, within the defined limits of their authority and within the approved budget. This includes managing and leading any such resources, including performing regular performance reviews.
* Following the pre-approval guidelines set forth by the LLC Board for contracts or other decisions that have financial costs that exceed a certain threshold of significance. Such threshold will be set reasonably high so that the need for such approvals is infrequent and only occurs when something is truly significant or otherwise exceptional. It is important to ensure that the Executive Director is sufficiently empowered to perform their job on a day to day basis, being held accountable for meeting high level goals rather than micromanaged.
* Regularly updating the LLC Board on operations and other notable issues as reasonable and appropriate.
* Ensuring that all staff and/or other resources comply with any applicable policies established or approved by the LLC Board, such as ethics guidelines and/or a code of conduct.

## Board Design Goals {#board-design-goals}

A goal of this proposed Board composition is to balance the need for the LLC to be accountable to the IETF community with the need for this Board to have the expertise necessary to oversee a small non-profit corporation. The Board is smaller than the current IAOC and the other leadership bodies of the IETF, in part to keep the Board focused on its rather limited set of strategic responsibilities as noted in {{board-responsibilities}}.

This board structure, with limited strategic responsibilities noted in {{board-responsibilities}} and limited size, together with the staff responsibilities noted in {{staff-responsibilities}}, is designed to overcome the challenges described in Section 3.1.4 of {{?I-D.haberman-iasa20dt-recs}} concerning oversight. This establishes a clear line of oversight over staff performance: the Board oversees the Executive Director's performance and has actual legal authority to remove a non-performing Executive Director. The Executive Director is responsible for the day-to-day operation of the LLC.

Finally, the Board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}}. The default transparency rule arrived at during the IASA 2.0 design process is detailed above in in {{principles}}. The Board will need to establish how it will meet that commitment.


## Board Composition {#board-composition}

The structure of the Board of Directors of the LLC shall be composed of up to seven people as follows:

* 4 Appointed by the IETF NomCom, confirmed by the IESG

* 1 IETF Chair ex officio or other person selected by the IESG

* 1 Appointed by the ISOC Board of Trustees

* 1 Appointed by the LLC Board itself, confirmed by IAB

## Recruiting LLC Board Directors {#director-recruitment}

The LLC Board itself, as well as the community as a whole, should take an active role in recruiting potential new Directors, regardless of the process that may be used to appoint them. In particular, the NomCom is primarily focused on considering requirements expressed by the Board and others, reviewing community feedback on candidates, conducting candidate interviews, and ultimately appointing Directors. The LLC Board and others can recruit potential Directors and get them into the consideration process of the NomCom or other appointing bodies.

## LLC Board Director Term Length {#term-length}

The term length for a Director shall be three years in length. The exceptions to this guideline will be for the terms for some Directors during the first full formation of the LLC Board in order to establish staggered terms and for any appointments to fill a vacancy. The final exception is if a Director role is occupied by the IETF Chair ex officio, since that person’s term length is governed instead by the term lengths established in RFC 7437, Section 3.4.

## LLC Board Director Limit {#term-limit}

A director may serve no more than two consecutive terms, with at least one full term prior to the start of any additional terms. The only exception is if a Director role is occupied by the IETF Chair ex officio, since that person’s service is governed instead by the term lengths established in {{RFC7437}}, Section 3.4.

The only exception to the two consecutive term rule is for an LLC-appointed Director. For such a Director, they may serve only one term via this appointment method, after which any subsequent terms would be occur via other appointment processes (such as via the NomCom process).

The limit on consecutive terms supports the healthy regular introduction of new ideas and energy into the Board and mitigates potential long-term risk of ossification or conflict, without adversely impacting the potential pool of director candidates over time.

## Staggered Terms {#staggered-terms}
ISOC, the IESG, the Nominating Committee, and the Board shall coordinate with each other to ensure that collectively their appointment processes provide for no more than three Directors’ terms concluding in the same year.

## LLC Board Director Removal {#director-removal}

Directors may be removed with or without cause. A vote in favor of removal must be no fewer than the number of Directors less two. Directors may also be removed via the IETF recall process defined in {{RFC7437}}, Section 7. So for example, if there are seven directors, then five votes are required. Directors may also be removed via the IETF recall process defined in {{RFC7437}}, Section 7.

## Filling a LLC Board Director Vacancy {#director-vacancy}

It shall be the responsibility of each respective body that appointed a Director that vacates the Board to appoint a new Director to fill the vacancy. For example, if a Director appointed by the NomCom departs the Board prior to the end of their term for whatever reason, then it is the responsibility of the NomCom as the original appointing body to designate a replacement that will serve out the remainder of the term of the departed Director.

## Interim Board {#interim-board}

An initial interim Board will be necessary in order to legally form and bootstrap the LLC. As a result, an  interim Board will be formed on a temporary basis until the first full board is constituted.

The interim Board shall be comprised of:

* The current IETF chair, ex officio
* The current ISOC chair, ex officio
* The current IAOC chair, ex officio
* The current IAB chair, ex officio

## First Full Board {#first-full-board}

A minimum of five Directors must be seated in order for the Board to be constituted, and the Interim Board to be dissolved. The first full board MUST be formed no later than the end of the first quarter of 2019. Accordingly, the following steps must take place to ensure that this occurs as soon as possible:

* The IESG shall make their appointment no later than December 31, 2018.
* ISOC shall make their appointment no later than December 31, 2018.
* The NomCom shall make their appointments no later than December 31, 2018.
* These initial LLC Board members shall make their appointment(s) before the end of March 2019.

## Board Positions {#board-positions}

Following the formation of the first full LLC Board, and at each subsequent annual meeting of the LLC Board, the Directors shall elect by a majority vote of the LLC Board a Director to serve as Board Chair. The Board may also form committees of the Board and/or define other roles for LLC Board Directors as necessary.

# LLC Policies {#llc-policies}

The Board shall develop policies as necessary to achieve the goals of the LLC, meet transparency expectations of the community, comply with applicable laws or regulations, or for other reasons as appropriate. All policies should be developed with input from the IETF community. Some policies of ISOC may provide a good starting point from which the Board can begin.

## Conflict of Interest Policy {#conflict-of-interest}

The Board shall develop a Conflict of Interest policy for the LLC. While the details shall be determined by the Board, at a minimum such policy will include the following:

* The IETF, ISOC, IAB, IRTF chair cannot be chair of this LLC Board.

* A Director cannot be a paid consultant or employee of the Executive Director or their sub-contractors, nor a paid consultant or employee of ISOC.

## Other Policies {#other-policies}

The Board shall develop additional policies for the LLC as necessary, covering Directors, employees, and contractors, concerning issues such as:

* Acceptance of gifts and other non-cash compensation;

* Travel and expense reimbursement;

* Anti-bribery;

* Code of conduct;

* Anti-harassment;

* Non-discrimination;

* Whistleblower;

* Document retention;

* Export controls;

* Anti-terrorism sanctions;

* Data protection and privacy;

* Social media

## Compliance {#compliance}

The LLC shall develop and implement a compliance program to ensure its compliance with all applicable laws, rules and regulations, including without limitation laws governing bribery, anti-terrorism sanctions, export controls, data protection/privacy, as well as other applicable policies noted in {{llc-policies}}. In addition, actions and activities of the LLC must be consistent with 501(c)(3) purposes.

The LLC shall report to ISOC on the implementation of its compliance plan on an annual basis.

# Board Voting {#voting}

The Board can hold votes during synchronous live meetings of the Board (including telephonic and video) or via asynchronous written (including electronic) means. Decisions on regular LLC matters shall be made by a 2/3 majority vote in favor, with the exception of removal of a Director as specified in {{director-removal}}. Absentee voting and voting by proxy shall not be permitted.

## Quorum {#quorum}

At all meetings of the Board, at least 2/3 of the Directors then in office shall constitute a quorum for the transaction of business. If a quorum shall not be present at any meeting of the Board, the Directors present thereat may adjourn the meeting without notice other than announcement at the meeting, until a quorum shall be present.

# Fundraising Practices {#fundraising-practices}

When the LLC conducts fundraising, it will substantiate charitable contributions on behalf of ISOC. The LLC will evaluate and facilitate state, federal, and other applicable law and regulatory compliance for ISOC and/or the LLC with respect to such fundraising activities. In addition, the LLC shall ensure that all fundraising activities are conducted in compliance with any policies developed by the LLC, including but not limited to those noted in {{llc-policies}}.

# Transition Considerations {#transition-considerations}

Conducting a transition as envisioned in this document will encompass many different work activities and will require action, involvement, support, and/or feedback from groups and individuals across the IETF community. The transition is likely to proceed in these steps but the community should remain flexible and adapt this plan as changes occur and complications inevitably arise.

Phase 1: LLC Formation
* The LLC is formed with an Interim Board (see {#interim-board})
* The IAOC continues to operate as usual, such as reviewing and approving the IETF's FY2019 budget
* The NomCom is given instructions by the IETF chair to not recruit for 2019 IAOC positions, and instead recruit for LLC Board Directors
* An update of RFC 7437 is started, reflecting this change

Phase 2: Transition from IAOC to LLC
* The LLC's Interim Board and IAOC shall agree to a transition schedule to transition IAOC responsibilities one-by-one to the LLC
* This phase MUST conclude prior to the expiration of IAOC member terms in 1Q2019

Phase 3: Transition Complete
* First full board is seated (see {#first-full-board})
* All responsibilities of the IAOC have been assumed by the LLC
* The IAOC can then be shut down

## Initial Tasks of the LLC Board

The initial tasks of the LLC Board should be prioritized according to legal necessity and relative importance. Below are suggested priorities to consider as and after the LLC is formed.

High priority for the Interim Board:
1 – Form the LLC legally
2 – Setup a bank account so that funds can be moved over
3 – Transfer all necessary contracts from ISOC/IAOC to the LLC
4 – Establish & implement a process to pay any employees or contractors, as necessary
5 - Agree to a transition schedule with the IAOC
6 - Secure any necessary insurance such as Commercial General Liability and other appropriate insurance policies, with appropriate coverage limits

Medium Priority for the Interim Board:
1 – Create a job description for the IETF Executive Director
2 - Initiate the process of beginning to search for an IETF Executive Director and/or outline a process to do so and defer it to the first full board, as appropriate

Low Priority for the Interim Board / First Tasks of the Full Board:
1 – Develop all necessary LLC policies
2 – Develop all necesssary Board operating procedures and bylaws
3 – Determine the employee benefits/salary framework and/or make associated staffing decisions
4 – Interview and hire an IETF Executive Director (targeting 1H2019)

The first full Board will also need to focus on the following tasks:
* Selecting a chair and other positions as necessary
* Define and document how the Board will fulfill its transparency obligations to the IETF community
* Defining the "significant materiality threshold", above which the Board must approve any contracts, expenditures, or other commitments.

Once the Executive Director and any additional staff are hired, it would be expected for LLC to:
* Do a thorough review of existing contracts, community volunteer arrangements, and administrative assets to determine the need for initial changes.
* Assess areas where the IETF community needs to document its consensus, e.g., expectations about community involvement in NOC or tools efforts.

# Acknowledgments

Thanks to Jari Arkko, Richard Barnes, Alissa Cooper, Sean Turner and the IASA 2.0 Working Group for discussions of possible structures, and to the attorneys of Morgan Lewis and Brad Biddle for legal advice.
