---

title: Proposed Structure of the IETF Administrative Support Activity (IASA), Version 2.0 (for Discussion)
abbrev: IASA 2.0
docname: draft-hall-iasa2-struct
category: info

ipr: trust200902
area: General
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
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
      ins: Morgan Lewis
    date: 2018-02
    target: https://mailarchive.ietf.org/arch/msg/iasa20/XT_3vfd3OWVFCW335mRrvWuusaI/


--- abstract

The IETF Administrative Support Activity (IASA) was originally established in 2005.  In the intervening years, the needs of the IETF have evolved in ways that require changes to its administrative structure.  The purpose of this document is to spur discussion by outlining some details of what an "IASA 2.0" arrangement could look like. The proposal is for the execution of the IETF's administrative and fundraising tasks to be conducted by a new administrative organization ("IETFAdminOrg"). The IAOC would be eliminated, and its oversight and advising functions transferred to the IETFAdminOrg board and a new IETF Administrative Advisory Council, respectively.


--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally established in 2005 {{!RFC4071}}.  In the intervening years, the needs of the IETF have evolved in ways that require changes to its administrative structure. {{?I-D.haberman-iasa20dt-recs}} discusses the challenges facing the current structure as well as several options for reorganizing the IETF's administration under different legal structures. {{ML-memo}} further outlines the legal details of various options, including three options -- an independent 501(c)(3) organization, a 501(c)(3) Type 1 supporting organization of ISOC, and an LLC that is a disregarded entity of ISOC -- that would entail setting up a new organization to house the administration of the IETF. This document outlines one way that such an organization could be structured and describes how the organization could fit together with existing and new IETF community structures. In this document the new administrative organization is known as IETFAdminOrg.

The purpose of this document is to spur discussion by outlining some details of what an "IASA 2.0" arrangement could look like. Some of the details of the organizational structure are dependent on the choice of legal structure, but others are not. While community discussion of the legal structure continues, the point of this document is to get community input about organizational approaches to solving some of the challenges identified in {{?I-D.haberman-iasa20dt-recs}}. Ultimately, if the IETF community decides to make changes to IASA, those changes will need to be documented in an update to or replacement of RFC 4071.

In brief, the proposal in this document is to transfer most of the responsibilities that RFC 4071 currently assigns to the IAD and ISOC to the newly created IETFAdminOrg. The IAOC would be eliminated, and its oversight and advising functions transferred to the IETFAdminOrg board and a new IETF Administrative Advisory Council ("the AC"), respectively. It would be the job of IETFAdminOrg to meet the administrative needs of the IETF. It would be the job of the AC to provide any advice that the IETFAdminOrg needs from an IETF community perspective. And it would be the job of the IETFAdminOrg board to ensure that IETFAdminOrg is meeting the needs of the IETF community.

Eliminating the IAOC means that there will need to be another way for trustees to be appointed for the IETF Trust. While the details of how this is done are for further work, the main principles are covered in this document.

The document does not propose any changes to anything related to the oversight or steering of the standards process as currently conducted by the IESG and IAB, the appeal chain, the confirming bodies for existing IETF and IAB appointments, or the IRTF.

If the community decides to make changes to IASA along the lines sketched out in this document, normative changes to IETF processes will need to be documented in an RFC. Additional legal documents (e.g., articles of incorporation, bylaws, operating agreements) relating to the legal entity would provide the official, legal definitions of processes, roles, etc. {{transition-considerations}} sketches some initial thoughts about transition; publishing a detailed transition plan would likely also be useful.


# Differences from IASA 1.0

* The IAOC and IAD roles defined in RFC 4071 would be eliminated.

* The ISOC and IAD responsibilities described in RFC 4071 would be assigned to a new organization, "IETFAdminOrg." The legal structure of this entity is to be determined.

* The corporate board of IETFAdminOrg would assume the oversight responsibilities of the IAOC.

* A new IETF Administrative Advisory Council ("the AC") would be established, which would assume the advisory responsibilities of the IAOC.


# IETFAdminOrg

## Responsibilities

IETFAdminOrg would be established to provide administrative support to the IETF. It would have no authority over standards development activities.

The proposed responsibilities of the IETFAdminOrg are listed below. Whether these responsibilities would be carried out by staff, contractors, community volunteers, or a mix would be at the discretion of the Executive Director and his or her staff (see {{staffing}}). The responsibilities are:

* Operations. The IETFAdminOrg is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The IETFAdminOrg is responsible for managing the IETF's finances and budget.

* Fundraising. The IETFAdminOrg is responsible for raising money on behalf of the IETF.

Housing these responsibilities at IETFAdminOrg is designed to address the problems described in Sections 3.1.1., 3.1.2, and 3.1.3 of {{?I-D.haberman-iasa20dt-recs}} concerning lack of clarity around responsibility, representation, and authority. By having IETFAdminOrg manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds could be reduced or eliminated. Having IETFAdminOrg reside in a legal entity and take responsibility for operations would allow the org to execute its own contracts without the need for further approvals from ISOC.

The IETFAdminOrg would be expected to conduct its work according to the following principles:

* Transparency. The IETFAdminOrg would be expected to keep the IETF community informed about its work and to engage the community and/or the AC, as appropriate, to obtain community input.

* Responsiveness to the community. The IETFAdminOrg would be expected to act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and to adapt its decisions in response to community feedback.

* Diligence. The IETFAdminOrg would be expected to act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. There is a need for agreement between the IETF community and the IETFAdminOrg about the where to draw the line between community's need for information and the need to keep some business and personnel data confidential. The devil here is in the details and it would be expected that one of the first tasks for the IETFAdminOrg Executive Director would be to document how IETFAdminOrg would engage with the community and to vet that proposal with the community.


## Board Formation and Responsibilities

The IETFAdminOrg board would be responsible for conducting oversight of IETFAdminOrg's execution of its responsibilities, as described in {{responsibilities}}.  This responsibility entails a number of concrete functions analogous to those currently preformed by the IAOC:

* To hire, fire, and review the performance of the Executive Director of IETFAdminOrg.

* To provide high-level direction for the Executive Director's work.

* To ensure that IETFAdminOrg has the financial and business stability that it needs to be able to meet the needs of the IETF, including approving an annual budget proposed by the Executive Director.

* To ensure that IETFAdminOrg is run in a manner that is transparent and accountable to the IETF community.

The board would be purely an oversight body. Its responsibilities would be limited to those listed above. It would not conduct any of the IETF's administrative work.

The role of the IETFAdminOrg board would be to ensure that the strategic orientation of IETFAdminOrg is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The board is not intended to represent the IETF community in defining the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus RFCs (e.g., as the community is aiming to do in {{?I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via the Advisory Council.

The description below outlines one way in which the board of IETFAdminOrg could be populated. The specific details are less important than the goals motivating this particular formulation, discussed below. Depending on the legal structure of IETFAdminOrg, some or all board seats may need to be appointments made formally by ISOC {{ML-memo}}, however it may be possible to encourage or require ISOC to appoint people on the basis of recommendations from the IETF by establishing an operational agreement between IETFAdminOrg and ISOC. Thus the details of any proposed board structure may be refined depending on the legal structure that is chosen; the proposal below could just as easily be a framework for having the IETF recommend board members as it could be for having the IETF actually appoint them.

The proposed structure of the board of IETFAdminOrg consists of seven people:

* The IETF Chair

* One member selected by the IETF NOMCOM

* One member selected by the ISOC board of trustees from among the ISOC trustees appointed by the IAB

* Two members selected by the board itself

The goal of this structure is to balance the need for IETFAdminOrg to be accountable to the IETF community with the need for this board to have the expertise necessary to oversee a small corporation.  The first three seats listed above are all selected by the IETF community, via NOMCOM and the IAB.  The two board-selected seats are there so that the board can bring in members with specific experience or skills in non-profit management and finance needed to complement the IETF-selected members.

The board is smaller than the current IAOC and the other leadership bodies of the IETF. Part of the motivation for keeping the board small is to keep the board focused on its rather limited set of tasks.

This board structure, together with the staffing proposal below, is designed to overcome the challenges described in Section 3.1.4 of {{?I-D.haberman-iasa20dt-recs}} concerning oversight. It establishes a clear line of oversight over staff performance: the board oversees the Executive Director's performance and has actual legal authority to remove a non-performing Executive Director. The Executive Director is responsible for the performance of the IETFAdminOrg.

Finally, the board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}}. As with the IETFAdminOrg, the board would need to establish up front how it would fulfill this commitment and how and when it would inform the IETF community about its actions.  These commitments and procedures embodying them could be encoded in the board's governing documents (e.g., bylaws).

Note also that the board formation rules of IETFAdminOrg would be defined in its corporate documents, e.g., its articles of incorporation and bylaws.

On a small board, board member term lengths and appointment cycles need some careful thought to ensure some continuity on the board and to account for external term limits and appointment cycles of the IETF Chair and the ISOC trustees. One way to arrange this would be to have the IETF Nomcom-appointed member’s term be two years and shifted a year from IETF Chair’s term. Setting the term for the ISOC trustees-selected member to two years would provide some additional continuity. The two members appointed by the board itself should have terms that are not both ending at the same time.


## Staffing

IETFAdminOrg would be led by an Executive Director chosen by the board. The Executive Director would determine what other staff and contractors are required by IETFAdminOrg. Allowing for the division of responsibilities among multiple staff members and contractors should hopefully address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{?I-D.haberman-iasa20dt-recs}}.

Based on the amount of work currently undertaken by the IAD and others involved in the IETF administration who are not currently in contracted roles, it is anticipated that the Executive Director would hire multiple additional staff members. For example, there will likely be a need for dedicated staff to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications.

The IETF currently benefits from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). The IETF budget currently reflects specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors would be at the discretion of the Executive Director and his or her staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the EDU and Mentoring Directorate. The IETFAdminOrg staff would be expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the IETFAdminOrg to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists (see {{transition-considerations}}).



# IETF Administrative Advisory Council (AC)

The AC is proposed to advise the staff of IETFAdminOrg about how their work can best support the IETF. If the staff and contractors find it desirable, the AC may also advise the contractors.

The AC is conceptualized as a body of IETF community members who can serve as a sounding board in situations where the IETFAdminOrg staff or contractors need to gauge community opinion or have questions about how administrative decisions might be viewed by the IETF community. For major administrative decisions, the IETFAdminOrg could be required to consult with the AC to gauge community opinion prior to deciding. Major administrative decisions might include the selection of a meeting venue or the award of a contract in excess of a certain fraction of the annual IETF budget.

The AC would not have decisional authority, but the process for the IETFAdminOrg to engage the AC would be documented, and the IETFAdminOrg would be expected to inform the community about how AC input was incorporated into its decision-making.  A requirement to provide this kind of information could be included in the IETFAdminOrg bylaws. The oversight responsibilities of the IETFAdminOrg board would include ensuring that the IETFAdminOrg was complying with documented processes, and generally maintaining an appropriate level of engagement with the AC and the broader community.

For other more minor administrative decisions, there would be no requirement that the staff consult the AC about any particular decision, but there would be the expectation that the staff could consult the AC whenever they felt it necessary.

The virtue of the AC would be that for matters where the staff feels confident that they understand the community's desires and direction, they could execute their tasks without additional delays or approvals. For matters where they are unsure, they could seek opinions from the AC before proceeding. And for major decisions there would be a well-defined process for the IETFAdminOrg to understand a community perspective. The AC could also provide advice about situations where bringing a proposal or decision to the full IETF community for discussion would be warranted. It would be the staff's responsibility to bring those proposals to the community and manage those discussions, however.

(TODO - How is it formed? And how to deal with the likely need for the AC to review confidential information?)


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

# Acknowledgements

Thanks to Sean Turner, Richard Barnes, and Alissa Cooper for discussions of possible structures, and to the attorneys of Morgan Lewis for their advice on possible legal impacts.
