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

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization ("IETFAdminOrg"). Under the proposal, the IAOC will be eliminated, and its oversight and advising functions transferred to a new IETFAdminOrg board.

--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the 13 years from 2005 to 2018, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to outline a proposed new "IASA 2.0" structure. The proposal is for the work of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization ("IETFAdminOrg"). Under the proposal, the Internet Administrative Oversight Committee (IAOC) will be eliminated, and its oversight and advising functions transferred to a new IETFAdminOrg board. This document explores all of the details involved in the proposal.

{{?I-D.haberman-iasa20dt-recs}} discusses the challenges facing the current structure as well as several options for reorganizing the IETF's administration under different legal structures. {{ML-memo}} further outlines the legal details of various options, including three options -- an independent 501(c)(3) organization, a 501(c)(3) Type 1 supporting organization of ISOC, and an LLC that is a disregarded entity of ISOC -- that would entail setting up a new organization to house the administration of the IETF. This document outlines one way that such an organization could be structured and describes how the organization could fit together with existing and new IETF community structures. In this document the new administrative organization is known as IETFAdminOrg.

This document outlines some details of what a potential "IASA 2.0" arrangement. Some of the details of the organizational structure are dependent on the choice of legal structure, but others are not. The point of this document is to solicit community input about various organizational approaches to solving some of the challenges identified in {{?I-D.haberman-iasa20dt-recs}}. Ultimately, if the IETF community decides to make changes to IASA, those changes will subsequently be documented in a replacement of RFC 4071, RFC 4371, and update of BCP 101.

The proposal in this document is to transfer most of the responsibilities that RFC 4071 currently assigns to the Internet Administrative Director (IAD) and Internet Sociecty (ISOC) to the newly created IETFAdminOrg. The IAOC would be eliminated, and its oversight and advising functions transferred to the IETFAdminOrg board. It would be the job of IETFAdminOrg to meet the administrative needs of the IETF and ensure that IETFAdminOrg and IASA 2.0 is meeting the needs of the IETF community.

Eliminating the IAOC means that there will need to be another way for trustees to be appointed for the IETF Trust. The details of how this is done are outlined in (PLACEHOLDER-FILL-IN-WITH-I-D-NAME-SOON).

The proposal in this document is depicted visually in {{Diagrams}} showing the IETF Trust and {{Diagrams-no-trust}} not showing the IETF Trust.


# Scope Limitation

The document does not propose any changes to anything related to the oversight or steering of the standards process as currently conducted by the Internet Engineering Steering Group (IESG) and Internet Architecture Board (IAB), the appeals chain, the confirming bodies for existing IETF and IAB appointments, or the Internet Research Task Force (IRTF).

If the community decides to make changes to IASA along the lines sketched out in this document, normative changes to IETF processes will need to be documented in an RFC. Additional legal documents (e.g., articles of incorporation, bylaws, operating agreements) relating to the legal entity would provide the official, legal definitions of processes, roles, etc. {{transition-considerations}} sketches some initial thoughts about transition; publishing a detailed transition plan would likely also be useful.


# Key Differences from the IASA 1.0 Structure

* The IAOC and IAD roles defined in RFC 4071 are eliminated.

* The ISOC and IAD responsibilities described in RFC 4071 are assigned to a new organization, "IETFAdminOrg." 

* The board of trustees of IETFAdminOrg will assume the oversight responsibilities of the IAOC.


# IETFAdminOrg

## Responsibilities

IETFAdminOrg will be established to provide administrative support to the IETF. It will have no authority over the standards development activities of the IETF.

The proposed responsibilities of the IETFAdminOrg are listed below. Whether these responsibilities will be carried out by staff, contractors, community volunteers, or a mix will be at the discretion of the Executive Director and their staff (see {{staffing}}). The responsibilities are:

* Operations. The IETFAdminOrg is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The IETFAdminOrg is responsible for managing the IETF's finances and budget.

* Fundraising. The IETFAdminOrg is responsible for raising money on behalf of the IETF.

Organizing these responsibilities under the IETFAdminOrg is intended to address the problems described in Sections 3.1.1., 3.1.2, and 3.1.3 of {{?I-D.haberman-iasa20dt-recs}}. Specifically, this is intended to bring greater clarity around roles, responsibilities, representation, decision-making, and authority. By having IETFAdminOrg manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds will be eliminated. Having IETFAdminOrg reside in a legal entity and take responsibility for operations wilkl allow the organization to execute its own contracts without the need for review and approval by ISOC.

The IETFAdminOrg will be expected to conduct its work according to the following principles:

* Transparency. The IETFAdminOrg will keep the IETF community informed about its work and will engage with the community to obtain community input.

* Responsiveness to the community. The IETFAdminOrg will act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and adapt its decisions in response to community feedback.

* Diligence. The IETFAdminOrg will act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. The IETFAdminOrg will need to work with the IETF community and IETFAdminOrg Executive Director to strike the appropriate balance between the community's need for information and the need to keep some business and personnel data confidential. One of the first tasks of the IETFAdminOrg is to document how the IETFAdminOrg will engage with the community, share information, ensure openness to feedback, and to vet this proposal with the community.


## Board Responsibilities

The IETFAdminOrg board will be responsible for conducting oversight of IETFAdminOrg's execution of its responsibilities, as described in {{responsibilities}}.  This includes the responsibility to:

* manage the employment of the role of the Executive Director of IETFAdminOrg, including tasks such as hiring, termination, performance review, and the award of compensation and other requisite employment benefits;

* provide strategic direction to the Executive Director; 

* exercise a fiduciary duty to ensure that IETFAdminOrg has the financial and business stability that it needs to be able to meet the needs of the IETF, including approving an annual budget;

* exercise a legal duty to ensure that the IETFAdminOrg complies with any applicable tax and other laws;

* ensure that IETFAdminOrg is run in a manner that is transparent and accountable to the IETF community.

The board will be an oversight body, with responsibilities limited to those listed above. It will not directly conduct any of the IETF's administrative work, which is the day-to-day job of the Executive Director at their team.

The role of the IETFAdminOrg board will be to ensure that the strategy and conduct of IETFAdminOrg is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The board is not intended to  directly define the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus-based RFCs (e.g., as the community is aiming to do in {{?I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via consulations with the IETFAdminOrg board (such as takes place on email discussion lists or at IETF meetings).

The description below outlines the composition of the IETFAdminOrg board, selection of trustees, and related details. 

## Board Composition

The Board of Trustees of the IETFAdminOrg shall be comprised of seven people as follows:

* One trustee, who is serving as the current IETF Chair

* One trustee, selected by the ISOC Board of Trustees from among those ISOC trustees appointed by the IAB

* Two trustee, selected by the IETF Nominating Committee (NOMCOM)

* Three trustee, selected by the board itself

The goal of this structure is to balance the need for the IETFAdminOrg to be accountable to the IETF community with the need for this board to have the expertise necessary to oversee a small corporation.  The first four seats listed above are all selected by the IETF community, via the NOMCOM and the IAB.  The three board-selected trustees are there so that the board can bring in trustees with specific experience or skills in non-profit management and finance needed to complement the IETF-selected trustees.

The board is smaller than the current IAOC and the other leadership bodies of the IETF. Part of the motivation for keeping the board small is to keep the board focused on its rather limited set of tasks.

## Board Design Goals

This board structure, together with the staffing proposal below, is designed to overcome the challenges described in Section 3.1.4 of {{?I-D.haberman-iasa20dt-recs}} concerning oversight. It establishes a clear line of oversight over staff performance: the board oversees the Executive Director's performance and has actual legal authority to remove a non-performing Executive Director. The Executive Director is responsible for the performance of the IETFAdminOrg.

Finally, the board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}}. As with the IETFAdminOrg, the board would need to establish up front how it would fulfill this commitment and how and when it would inform the IETF community about its actions.  These commitments and procedures embodying them could be encoded in the board's governing documents (e.g., bylaws).

Note also that the board formation rules of IETFAdminOrg would be defined in its corporate documents, e.g., its articles of incorporation and bylaws.

## Trustee Term Length and Limit

On a small board, trustee term lengths and appointment cycles need some careful thought to ensure some continuity on the board and to account for external term limits and appointment cycles of the IETF Chair and the ISOC trustees. One way to arrange this would be to have the IETF Nomcom-appointed member’s term be two years and shifted a year from IETF Chair’s term. Setting the term for the ISOC trustees-selected member to two years would provide some additional continuity. The trustees appointed by the board itself should have terms that do not both end at the same time.

Trustees may serve no more than ten consecutive years on the Board. This is in following board best practices to ensure a healthy introduction of new trustees, new ideas, and new energy onto the Board and to mitigate any potential long-term risk of ossification or conflict.

## Initial Board Formation

The options for the initial formation for the Board include:

* The Board of Trustees of the IETFAdminOrg shall be comprised initially of four people, given that three people must then be selected by the Board itself. The Board will appoint those three trustees within 90 calendar days of the initial formation of the IETFAdminOrg. Thus, in the first 90 days there will be four trustees and no later that the 91st day there will be seven trustees.

* The Board of Trustees of the IETFAdminOrg shall be comprised initially of seven people. For the initial formation, since no Board of Trustees is extant, the three trustees that would otherwise be selected by the Board will instead be selected by the IETF NomCom. The initial term of those three trustees shall be one year.

Following the initial formation of the Board, and at each annual meeting of the Board, a Trustee shall be appointed to serve in each of the following roles:

* Board Chair

* Secretary

* Treasurer

The Board shall also form committees of the Board of Trustees as they see fit, and/or define other roles for Trustees.

## Conflict of Interest and Expectations for Behavior

The Board of Trustees shall develop, with community feedback, and establish a Conflict of Interest policy, according to best practices. Individual trustees shall file a conflict of interest form annually or more frequently as their potential conflicts change. The Board shall publish these forms annually, and if a Trustee does a subsquent update shall publish that within 30 days of the update.

In addition, the Board shall similarly develop a Code of Ethics and Code of Conduct, and establish any necessary travel or other policies.

No member of the Board of Trustees shall be permitted to operate as a paid consultant to the IETF, the IETFAdminOrg Executive Director, IAB, IESG, or ISOC. In addition, prospective Trustees shall be asked to complete a conflict of interest form during the period of their consideration for board service, such as during the NomCom cycle. For those board members being selected by the IAB, the IETF NomCom or the IETFAdminOrg Board, the prospective trustee shall document any paid consultant or customer relationships with members of their respective selection group (e.g. IAB, IETF NomCom, IETFAdminOrg Board).


## Staffing

IETFAdminOrg would be led by an Executive Director chosen by the board. The Executive Director would determine what other staff and contractors are required by IETFAdminOrg. Allowing for the division of responsibilities among multiple staff members and contractors should hopefully address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{?I-D.haberman-iasa20dt-recs}}.

Based on the amount of work currently undertaken by the IAD and others involved in the IETF administration who are not currently in contracted roles, it is anticipated that the Executive Director would hire multiple additional staff members. For example, there will likely be a need for dedicated staff to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications.

The IETF currently benefits from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). The IETF budget currently reflects specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors would be at the discretion of the Executive Director and his or her staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the EDU and Mentoring Directorate. The IETFAdminOrg staff would be expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the IETFAdminOrg to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists (see {{transition-considerations}}).

# Transition Considerations

Conducting a transition as envisioned in this document would encompass many different aspects and would require action from the IETF community, the IAOC, the IAD, ISOC, the newly hired IETFAdminOrg Executive Director and staff, and newly appointed IETFAdminOrg board members. This document sketches some thoughts on the subset of tasks that would entail some IETF community involvement or review (as opposed to, say, the transfer of administrative assets).

There are a number of tasks under this proposal that would require an initial bootstrap:

* Defining the articles of incorporation and the bylaws of IETFAdminOrg, including provisions about how those documents may be amended in the future.

* Populating the IETFAdminOrg board.  The initial board for an organization is usually specified in its founding documents (e.g., articles of incorporation), along with a mechanism for replacing the initial board.  The current IETF Chair can be included in this initial set, and the NOMCOM-appointed and ISOC-board-appointed members can be seated as the appointing bodies are able.  It remains to determine how to select the initial board-selected members.

* Hiring the Executive Director.  This would presumably be undertaken by the IETFAdminOrg board once its membership is sufficiently well established.

* Defining the operating procedures and administrative support for the board. The board would need to have processes defined for selecting a chair and conducting its work. The board would also need to define how it would fulfill its transparency obligations to the community.

* Defining the operating procedures and administrative support for the AC. The AC would need to have processes defined for selecting a chair and engaging with the IETFAdminOrg.

Once the Executive Director and any additional staff are hired, it would be expected for IETFAdminOrg to:

* Document how it will fulfill its commitment to transparency and how it will engage with the IETF community.

* Do a thorough review of existing contracts, community volunteer arrangements, and administrative assets to determine the need for initial changes.

At the same time, there may be areas where the IETF community needs to document its consensus, e.g., expectations about community involvement in NOC or tools efforts.

(TODO: Document how to unwind the existing structures.)

# Acknowledgments

Thanks to Jari Arkko, Richard Barnes, Alissa Cooper, Brian Haberman, and Sean Turner for discussions of possible structures, and to the attorneys of Morgan Lewis for their advice on possible legal impacts.
