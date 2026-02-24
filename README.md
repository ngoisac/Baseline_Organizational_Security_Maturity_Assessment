# Organizational Security Assessment Survey

## About
This assessment tool is meant to help organizations identify where their most critical security needs lie.

This Security assessment is an adaptation of the [Organizational Security Assessment Tool COVID-19 Edition](https://0xacab.org/iecology/orgsec-assessment/) and the [Digital Security Readiness Assessment Tool](https://0xacab.org/iecology/security-checklists) created by Jonah Silas Sheridan, Lisa Jervis for [Information Ecology](https://iecology.org/).

## Deploying this survey content yourself
This repository only contains the adaptations NGO-ISAC made to the source content. It does not include any code to deploy this content as a survey.

## Outcome Scores
Outcome Scores measure an organization based on how they evaluate themselves against a series of Outcome statements. These, when added together, show the organizations ability to achieve each Maturity Objective. Outcome statements reflect the intermediate, tangible and intangible behavioral or systemic changes resulting from an organizations information security related efforts. By focusing on outcomes (instead of the maturity of your processes) this assessment aims to help you assess if an organizations efforts are having the intended changes, effects, or benefits.

## How Evaluation is done
A respondent evaluates if their organizations is accomplishing an Outcome by choosing one item on the following scale.
- Never
- Rarely
- Most the time
- Always
- I don't know

"I don't know" should be the default answer to make the assessment a quicker process and identify areas that an organization can prioritize building their understanding of.

*NOTE:* For the initial release of the survey an additional "I don't understand" item will be added to the Outcome scale to allow members to flag items which they think are confusing or misleading.

## Outcome Statement Types

There are two general categories of outcome statements included in the survey. "BASELINE," outcome statements that show that the short-term baseline functionality has been accomplished. "CARE," outcome statements that reflect an organizations commitment to ensure the safety and well-being of employees and others.

### BASELINE Outcomes
"BASELINE," outcome statements aim to show that the short-term baseline functionality has been accomplished. If these outcomes are not achieved the Objective is not being met.

### CARE Outcomes Themes
"CARE," outcome statements reflect an organizations commitment to ensure the safety and well-being of employees and others. These outcomes reflect practices which improve the impact or ensure the efficacy of an organizations security readiness efforts.

Many, but not all, of the CARE outcomes reflect one or more of the following thematic areas of security program best practices.

#### Multi-Level Leadership

WHAT: Leadership for technology, operations, and security within your organization can and should come from all levels.

WHY: Junior staff and younger "digital natives" on staff often use or are open to using more technology in their work so can be motivated to participate in the planning and deployment of information systems and promote uptake among peers. Of course, demonstrations of support for and engagement with technology initiatives from management are also powerful motivators for staff. Visible participation by executive leadership in training on and use of official organizational tools is a powerful modeling of preferred behavior and critical to changing organizational habits and culture.

##### References
- TODO: Civil Society Security Champion Literature (DDP & Others)
- Security Culture Maturity Roadmap - Security Awareness Champions: https://www.ivoryware.com/Security-Culture-Maturity-Roadmap-821fe093d6ba4d499e232c7a0e5fbff9?p=839224968f7e4758b25ac9f767448552&pm=s&pvs=31

#### Security Collaboration
WHAT: Is the organization effectively utilizing security collaboration with other organizations and groups who have similar contexts, processes, technologies, and/or goals. Security collaboration is when group(s) of organizations act together to achieve common objectives or address shared challenges. Some examples of what this may look like include sharing information on relevant incidents and risks, pooling resources, expertise, and efforts to achieve common objectives or address shared challenges,  and/or developing individual and collective security plans which protect critical shared infrastructure (people, efforts, technologies, or organizations) whose disruption would cause significant damage to the ability for group member's to operate or achieve their missions.

WHY: Effective security collaboration acts as a capacity multiplier for organizations of all sizes. The ability to share and collaboratively develop security information and support is especially critical for smaller organizations as they can allow them to overcome common operational and resource challenges without needing to develop large formal internal technology and security structures.

##### References:
- NGO Security Collaboration Guide: https://gisf.ngo/long-read/ngo-security-collaboration-guide/
- A Critical Approach to Collective Protection: Taking Stock of Protection International’s Experience:
  https://www.protectioninternational.org/researchpublications/collective-protection/

#### Holistic Risk Management
WHAT: The organization takes a holistic approach to risk management that integrates the management of safety, security, well-being, and operational risks (physical, digital, psycho‑social, legal, financial, reputational, and other dimensions) as part of a jointly owned and coordinated approach.

WHY: When safety, wellness, security, and operational risks are being assessed and addressed in a continuous and coordinated manner, an organization can manage risks to its mission and operations and to safeguard the safety, security, and wellbeing of all staff and other individuals affected by its activities. A holistic approach to risk management allows an organization to ensure that their risk management efforts are streamlined, strategic, agile, and resilient. Managing risks holistically optimizes resource allocation by removing redundant ad-hoc controls and increases operational efficiency by eliminating onerous security processes that impede the work and mission. Integrated approaches will not only produce a far more accurate understandings of the impacts of risks as they cascade across different domains; it exposes how the interplay of mitigation and contingency measures can have unintended negative consequences for risk-management efforts in other domains.

##### References
- "Duty of Care Maturity Model" - cinfo in collaboration with EISF -  https://dutyofcare.cinfo.ch/ -
- Study "Duty of Care under Swiss Law"  - https://www.cinfo.ch/sites/default/files/documents/2018_doc_study.pdf

#### Informed Consent
WHAT: All staff, constituents, participants, and beneficiaries are informed about relevant risks, acceptable risk levels, mitigation procedures, and contingency plans if things go wrong, including their individual roles and responsibilities. And have accepted these risks after the organization has clarified both their right to withdraw and the level of risk the organization has identified as acceptable.

WHY: (TODO)
- informed consent helps ensure security controls are implemented (by staff, partners in coalition, donors, etc) by making them real and connected to reasonable threats.
- informed consent ensures that relevant stakeholders inform you of unique circumstances that change the likelihood/impact of risks or the efficacy of mitigations. (SeeL Inclusive Security)

##### References
- "Duty of Care Maturity Model" - cinfo in collaboration with EISF -  https://dutyofcare.cinfo.ch/ -
- Study "Duty of Care under Swiss Law"  - https://www.cinfo.ch/sites/default/files/documents/2018_doc_study.pdf


#### Inclusive Security
WHAT: Staff, constituent, participant, and beneficiary security, safety, and wellbeing are impacted by the interplay between where they are, the work they do, who they are, and their association with the organization and its activities. Inclusive security risk management approaches look to protect those involved with their work from foreseeable risks, including those that emerge due to their personal characteristics – for example, biological sex, gender, ethnicity, socio‑economic status, cognitive and physical abilities, or sexual orientation.

WHY: Not understanding how context and personal profile characteristics impact personal security and well-being can have implications for the security of those individuals, the goals they are working towards, and the organization as a whole.  An individuals unique profile or circumstances can (sometimes dramatically) change the actual likelihood/impact of risks or the efficacy of identified mitigations. (For example, risk management around staff BYOD devices often only consider the employee as a user on those devices. But, parents who cannot afford a separate computer for their child regularly share their personal computers. Sharing a device with a child dramatically increases the likelihood that the device becomes infected with malware. An inclusive security approach establishes processes to identify and respond to this type of individual profile/context with appropriate mitigations.) Beyond the immediate impacts on individuals, the unidentified flaws created by not considering how the diverse profiles and contexts of key stakeholders impact the accuracy of an organizations risk management efforts can lead to serious security, legal and reputational issues for an organization.

##### References
- Managing the Security of Aid Workers with Diverse Profiles: https://gisf.ngo/resource/managing-the-security-of-aid-workers-with-diverse-profiles/
- Toward Inclusive Security Risk Management: the impact of 'race', ethnicity and nationality on aid workers' security: https://gisf.ngo/wp-content/uploads/2025/03/Toward-Inclusive-Security-Risk-Management.pdf


# Terms used in this survey
- Systems: This refers to any technologies/tools, systems, or online services which are used to carry out work. This includes physical devices (laptops, phones, tablets), software on those devices, hosted and online services, third-party applications, etc.
- Processes: This is the way your work is done. This includes any standard operating procedures, specific workflows, security practices, etc.
- Security Practices/Controls: these are any processes that are specifically used to mitigate security risks. (i.e. Use of security tools like two-factor or password managers, data collection/minimization standards, secure communications protocols, etc.)
- Appropriate systems or processes: Appropriate systems or processes (including security controls) are those that the organization has identified as allowing it to safety and effectively carry out the organizations work.
- Inappropriate systems or processes: Inappropriate systems or processes (including security controls) are those that create unacceptable obstacles to efficient, secure operations, have excessive costs, or has unacceptable impacts on risk management efforts.
- Broader Risks: The full range of interconnected risks facing an organization and the people it serves; spanning physical, digital, psychosocial, legal, financial, reputational, operational, and other dimensions. When used in this assessment, it signals that the risks being described extend beyond pure information security risks to risks with impacts on mission effectiveness, individual safety or wellbeing, or organizational operations.
- Critical Functions: The activities, processes, and data the organization has determined it cannot afford to lose, pause, or be denied access to without serious harm to its mission, its staff, or the people it serves.
- Incidents and Disruptions: Used together in this assessment to describe the full range of events that can interrupt or harm an organization's operations, data, staff, or constituents. A security incident typically refers to an event involving unauthorized access, data exposure, or deliberate attack. An operational disruption refers more broadly to any event — including natural disasters, infrastructure failure, or political instability — that prevents the organization from carrying out its work. Many response and recovery practices apply to both.
