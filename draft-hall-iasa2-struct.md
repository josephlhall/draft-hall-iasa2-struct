---

title: Proposed Structure of the IETF Administrative Support Activity (IASA), Version 2.0 (for Discussion)
abbrev: IASA 2.0
docname: draft-hall-iasa2-struct-01
category: info

ipr: trust200902
area: General
keyword: Internet-Draft

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
    email: Jason_Livingood@comcast.com

informative:
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

--- abstract

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization, the IETF Adminstration Limited Liability Corporation ("LLC"). Under the proposal, the Internet Administrative Oversight Committee (IAOC) will be eliminated, and its oversight and advising functions transferred to the new LLC Board.

--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization, the IETF Administration Limited Liability Corporation ("LLC"). Under the proposal, the Internet Administrative Oversight Committee (IAOC) will be eliminated, and its oversight and advising functions transferred to the new LLC Board. This document explores all of the details involved in the proposal.

{{?I-D.haberman-iasa20dt-recs}} discusses the challenges facing the current structure as well as several options for reorganizing the IETF's administration under different legal structures. This document outlines how such an organization will be structured and describes how the organization will fit together with existing and new IETF community structures.

This document outlines some details of a potential "IASA 2.0" arrangement. Some of the details of the organizational structure are dependent on the choice of legal structure, but others are not. The point of this document is to solicit community input about how to address the challenges identified in {{?I-D.haberman-iasa20dt-recs}}. Ultimately, if the IETF community decides to make changes to IASA, those changes will subsequently be documented in a replacement of RFC 4071 (BCP 101) and RFC 4371.

The proposal in this document is to transfer most of the responsibilities that RFC 4071 currently assigns to the Internet Administrative Director (IAD) and Internet Society (ISOC) to the newly created LLC. The IAOC would be eliminated, and its oversight and advising functions transferred to the LLC Board. It would be the job of LLC to meet the administrative needs of the IETF and ensure that LLC and IASA 2.0 is meeting the needs of the IETF community.

Eliminating the IAOC means that there will need to be another way for trustees to be appointed for the IETF Trust. The details of how this is done are outlined in (PLACEHOLDER: FILL IN WITH I-D NAME IN FUTURE UPDATE).

The proposal in this document is depicted visually in {{Diagrams}} showing the IETF Trust and {{Diagrams-no-trust}} not showing the IETF Trust. (NOTE: DIAGRAMS WILL BE UPDATED AS CONSENSUS FURTHER DEVELOPS, IN A FUTURE UPDATE)


# Scope Limitation

The document does not propose any changes to anything related to the oversight or steering of the standards process as currently conducted by the Internet Engineering Steering Group (IESG) and Internet Architecture Board (IAB), the appeals chain, the confirming bodies for existing IETF and IAB appointments, the Internet Research Task Force (IRTF), or ISOC's memberships in or support of other organizations.

If the community decides to make changes to IASA along the lines sketched out in this document, normative changes to IETF processes will need to be documented in an RFC. Additional legal documents (e.g., articles of incorporation, bylaws, operating agreements) relating to the legal entity would provide the official, legal definitions of processes, roles, etc. {{transition-considerations}} sketches some initial thoughts about transition; publishing a detailed transition plan would likely also be useful.

## Operating Agreement with the Internet Society
The Operating Agreement (OA) is also out of scope for this document. The OA will be developed between the IETF and ISOC and is expected to include all critical terms, while still enabling maximum unilateral flexibility for the LLC Board. Thus, it is anticipated that the OA will include only basic details about how the Board manages itself or manages LLC staff, so that the LLC Board has flexibility to make changes without amending the OA. The LLC Board can independently develop policy or procedures documents that fill gaps.

# Key Differences from the IASA 1.0 Structure

* The IAOC and IAD roles defined in RFC 4071 are eliminated. (NOTE: ONE WG TASK IS TO REPLACE RFC 4071)

* The ISOC and IAD responsibilities described in RFC 4071 are assigned to a new organization, IETF Administration LLC.

* The board of directors of the LLC will assume the oversight responsibilities of the IAOC.


# IETF Administration LLC

## General LLC Responsibilities {#responsibilities}

The LLC will be established to provide administrative support to the IETF. It will have no authority over the standards development activities of the IETF.

The proposed responsibilities of the LLC, and thus the LLC Board, are listed below. Whether these responsibilities will be carried out by staff, contractors, community volunteers, or a mix will be at the discretion of the Executive Director and their staff (see {{staffing}}). The responsibilities of the LLC are:

* Operations. The LLC is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The LLC is responsible for managing the IETF's finances and budget.

* Fundraising. The LLC is responsible for raising money on behalf of the IETF.

Organizing these responsibilities under the LLC is intended to address the problems described in Sections 3.1.1., 3.1.2, and 3.1.3 of {{?I-D.haberman-iasa20dt-recs}}. Specifically, this is intended to bring greater clarity around roles, responsibilities, representation, decision-making, and authority. By having the LLC manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds will be eliminated. Having the LLC reside in a legal entity and take responsibility for operations will allow the organization to execute its own contracts without the need for review and approval by ISOC.

The LLC will be expected to conduct its work according to the following principles:

* Transparency. The LLC will keep the IETF community informed about its work and will engage with the community to obtain community input.

* Responsiveness to the community. The LLC will act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and adapt its decisions in response to community feedback.

* Diligence. The LLC will act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. The LLC Board will need to work with the IETF community and LLC's Executive Director to strike the appropriate balance between the community's need for information and the need to keep some business and personnel data confidential. One of the first tasks of the LLC Board is to document how the LLC will engage with the community, share information, ensure openness to feedback, and to vet this proposal with the community.


## LLC Board Responsibilities

The LLC Board will be responsible for conducting oversight of LLC's execution of its responsibilities, as described in {{responsibilities}}.  This includes the responsibility to:

* provide strategic direction for the LLC and to the Executive Director;

* hire, supervise, and manage the employment of the role of the Executive Director of LLC, including tasks such as hiring, termination, performance review, amendment of employment terms, the award of compensation and other requisite employment benefits or decisions;

* adopting any employee benefit plans;

* approving any changes to the LLC governance structure;

* exercising a fiduciary duty to ensure that LLC has the financial and business stability that it needs to be able to meet the needs of the IETF, including adopting an annual budget, and as necessary incurring any debt or using making other financial arrangements;

* approving or entering into agreements that that meet a significant materiality threshold (NOTE: TBD later by the LLC Board);

* exercising a legal duty to ensure that the LLC complies with any applicable tax and other laws;

* ensuring that LLC is run in a manner that is transparent and accountable to the IETF community.

The board will be an oversight body, with responsibilities limited to those listed above. It will not directly conduct any of the IETF's administrative work, which is the day-to-day job of the Executive Director at their team.

The role of the LLC Board will be to ensure that the strategy and conduct of LLC is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The board is not intended to directly define the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus-based RFCs (e.g., as the community is aiming to do in {{?I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via consultations with the LLC Board (such as takes place on email discussion lists or at IETF meetings).

The description below outlines the composition of the LLC Board, selection of trustees, and related details.

## Board Composition

The structure of the Board of Directors of the LLC shall be as follows:

(NOTE: TBD BASED ON WG CONSENSUS)

The goal of this structure is to balance the need for the LLC to be accountable to the IETF community with the need for this board to have the expertise necessary to oversee a small corporation.  (TO BE MODIFIED LATER: The first X seats listed above are all selected by the IETF community, via the NOMCOM (NOTE: X-REF NEEDED).)

The Board is smaller than the current IAOC and the other leadership bodies of the IETF. Part of the motivation for keeping the Board relatively small is to keep the board focused on its rather limited set of tasks.

## Board Design Goals

This board structure, together with the staffing proposal below, is designed to overcome the challenges described in Section 3.1.4 of {{?I-D.haberman-iasa20dt-recs}} concerning oversight. It establishes a clear line of oversight over staff performance: the Board oversees the Executive Director's performance and has actual legal authority to remove a non-performing Executive Director. The Executive Director is responsible for the performance of the LLC.

Finally, the board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}}. As with the LLC, the Board would need to establish how it would fulfill this commitment and how and when it would inform the IETF community about its actions.  These commitments and procedures embodying them could be encoded in the board's governing documents (e.g., bylaws).

Note also that the Board formation rules of LLC would be defined in its corporate documents, e.g., its articles of incorporation and bylaws.

## Trustee Term Length and Limit

Term length shall be three years in length, with the possible exception of the terms for the first full formation of the LLC Board in order to establish staggered terms.

(NOTE: THIS PART IS TBD BASED ON WG CONSENSUS) Trustees may serve no more than X consecutive years on the Board. This is to ensure a healthy introduction of new trustees, new ideas, and new energy onto the Board and to mitigate any potential long-term risk of ossification or conflict.

(NOTE: WE ALSO NEED TO DETERMINE WITH THE WG HOW PARTIAL TERMS AND REMOVAL MAY WORK - LESS IMPORTANT FOR NOW THAN DIRECTOR SOURCES AS THE 1ST ORDER OF BUSINESS.)

## Initial Board Formation

The options for the initial formation for the Board include:

(TBD)

## First Full Board

Following the initial formation of the LLC Board, and at each subsequent annual meeting of the LLC Board, they shall select by a majority vote of the LLC Board someone serve in each of the following roles:

* Board Chair, from among the Trustees

* Secretary

* Treasurer, from among the Trustees

The Board shall also form committees of the Board of Trustees and/or define other roles for Trustees as they see fit.

## Staffing

The LLC shall be led by an Executive Director chosen by the board. The Executive Director will determine what other staff and contractors are required by the LLC. Allowing for the division of responsibilities among multiple staff members and contractors should hopefully address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{?I-D.haberman-iasa20dt-recs}}.

Based on the amount of work currently undertaken by the IAD and others involved in the IETF administration who are not currently in contracted roles, it is anticipated that the Executive Director would hire multiple additional staff members. For example, there will likely be a need for dedicated staff to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications.

The IETF currently benefits from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). The IETF budget currently reflects specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors will be at the discretion of the Executive Director and his or her staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the EDU and Mentoring Directorate. The LLC staff would be expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the LLC to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists (see {{transition-considerations}}).

# Transition Considerations

Conducting a transition as envisioned in this document would encompass many different aspects and would require action from the IETF community, the IAOC, the IAD, ISOC, a newly hired LLC Executive Director and staff, and newly appointed LLC Board members. This document sketches some thoughts on the subset of tasks that would entail some IETF community involvement or review (as opposed to, say, the transfer of administrative assets).

There are a number of tasks under this proposal that would require an initial bootstrap:

* Defining the articles of incorporation and the bylaws of the LLC, including provisions about how those documents may be amended in the future.

* Populating the LLC Board.  The initial board for an organization is usually specified in its founding documents (e.g., articles of incorporation), along with a mechanism for replacing the initial board.  The current IETF Chair can be included in this initial set, and the other members can be seated as the appointing bodies are able.  It remains to determine how to select the initial board-selected members.

* Hiring the Executive Director.  This would presumably be undertaken by the LLC Board once its membership is sufficiently well established.

* Defining the operating procedures and administrative support for the board. The board will need to have processes defined for selecting a chair and conducting its work. The board will also need to define how it would fulfill its transparency obligations to the community.

Once the Executive Director and any additional staff are hired, it would be expected for LLC to:

* Document how it will fulfill its commitment to transparency and how it will engage with the IETF community.

* Do a thorough review of existing contracts, community volunteer arrangements, and administrative assets to determine the need for initial changes.

At the same time, there may be areas where the IETF community needs to document its consensus, e.g., expectations about community involvement in NOC or tools efforts.

# Acknowledgments

Thanks to Jari Arkko, Richard Barnes, Alissa Cooper, Brian Haberman, Sean Turner and the IASA 2.0 Working Group for discussions of possible structures, and to the attorneys of Morgan Lewis and Brad Biddle for legal advice.
