STANDARDIZATION AND CERTIFICATION COMMITTEE

**DECADE-X**

**STANDARDIZATION STRUCTURE PROPOSAL**  
**V1**

**FEBRUARY 2026**

[**PRELIMINARIES	2**](#preliminaries)

[Foreword	2](#foreword)

[Revision and Update	2](#revision-and-update)

[**LEGAL NOTICE	3**](#legal-notice)

[a. Copyright & Trademarks	3](#copyright-&-trademarks)

[b. Disclaimer & Liability	3](#disclaimer-&-liability)

[**ABSTRACT (Optional)	5**](#abstract-\(optional\))

[**1\. SCOPE	5**](#scope)

[1.1. General Scope	5](#general-scope)

[1.2. Conformance and Notations	5](#conformance-and-notations)

[**2\. NORMATIVE REFERENCES	6**](#normative-references)

[**3\. TERMS AND DEFINITIONS	6**](#terms-and-definitions)

[**4\. MAIN CONTENT	7**](#main-content)

[**4.1. Business Context	7**](#business-context)

[**4.2. Technical architecture	8**](#technical-architecture)

[**4.3. Data models and semantic	9**](#data-models-and-semantic)

[**4.4. Legal & Regulatory framework	10**](#legal-&-regulatory-framework)

[**5\. CONFORMITY ASSESSMENT	11**](#conformity-assessment)

[5.1. Proof of conformity	11](#proof-of-conformity)

[5.2. Testing And Validation (Optional)	11](#testing-and-validation-\(optional\))

[**6\. ANNEX	12**](#annex)

[6.1. Normative Annex (Optional)	12](#normative-annex-\(optional\))

[6.2. Informative Annex (Optional)	12](#informative-annex-\(optional\))

[**7\. BIBLIOGRAPHY (Optional)	12**](#bibliography-\(optional\))

# 

# **PRELIMINARIES**  {#preliminaries}

This section is non-normative

## **Foreword** {#foreword}

***Description:**  This section provides purely administrative and historical information regarding the creation of the document. It must identify the specific DECADE-X committee or working group responsible for drafting the standard, specify its edition status (e.g., "This is the first edition" or "This edition cancels and replaces version 1.0"), and provide contact information for feedback.*

*Example: This document was prepared by the DECADE-X Standardization & Certification committee. This is the first edition of this standard. Any feedback or questions should be directed to the DECADE-X Standardization committee.*

## **Revision and Update**  {#revision-and-update}

| Version | Date | Working group | Summary of change |
| :---- | :---- | :---- | :---- |
| 0.1 | 02.26 | Standardization Committee | Creation of the document |
| 0.2 | 03.26 | Standardization Committee | Review of the document and validation of the structure |
| 1.0 | 03.26 | Standardization Committee | Document approved by the Standardization Committee |

# **LEGAL NOTICE** {#legal-notice}

1. ## **Copyright & Trademarks** {#copyright-&-trademarks}

Any and all rights to the present document or parts of it, including but not limited under copyright law, are owned by DECADE-X and its licensors.

The contents of this document shall not be copied, modified, distributed, displayed, made publicly available or otherwise be publicly communicated, in whole or in part, for any purposes, without the prior authorization by DECADE-X, and nothing herein confers any right or license to do so.

The present document may include trademarks or trade names which are registered by their owners. DECADE-X claims no ownership of these except for any which are indicated as being the property of DECADE-X, and conveys no right to use or reproduce any such trademark or trade name contained herein. Mention of any third-party trademarks in the present document does not constitute an endorsement by DECADE-X of products, services or organizations associated with those trademarks.

“DECADE-X” is a trademark owned by DECADE-X registered for its benefit and the benefit of its members. Using or reproducing this trademark or the trade name of DECADE-X is expressly prohibited. No express or implied license to any intellectual property rights in the present document or parts thereof, or relating to the use of its contents, or mentioned in the present document is granted herein.

The copyright and the foregoing restrictions extend to reproduction in all media.

2. ## **Disclaimer & Liability** {#disclaimer-&-liability}

The present document and its contents are provided “AS-IS” with no warranties whatsoever.

The information contained in this document is believed to be accurate and complete as of the date of publication, but may contain errors, mistakes or omissions.

DECADE-X makes no express or implied warranty with respect to the present document and its contents, including any warranty of title, ownership, merchantability, or fitness for a particular purpose or use. In particular, DECADE-X does not make any representation or warranty, and does not assume any liability, that the contents of the document or their use: 

(i) are technically accurate or sufficient  
(ii) conform to any law, regulation and/or regulatory requirement, or   
(iii) do not infringe third-party intellectual property or other rights.

No investigation regarding the essentiality of any patents or other intellectual property rights has been carried out by DECADE-X or its members, and DECADE-X does not make any representation or warranty, and does not assume any liability, as to the non-infringement of any intellectual property rights which are, or may be, or may become, essential to the use of the present document or its contents.

DECADE-X and its members are subject to the IP Regulations of the Association DECADE-X. which govern the handling of intellectual property rights in relation to the creation, exploitation and publication of technical documentation, specifications, and standards by DECADE-X.

Neither DECADE-X nor any of its members will be liable for any errors or omissions in this document, or for any damages resulting from use of the document or its contents, or reliance on its accuracy or completeness. In no event shall DECADE-X or any of its members be held liable for any indirect, incidental or consequential damages, including loss of profits. Any liability of DECADE-X or any of its members, including liability for any intellectual property rights or for non-compliance with laws or regulations, relating to the use of the document or its contents, is expressly disclaimed. 

# **ABSTRACT (Optional)** {#abstract-(optional)}

This section is informative

***Description:** Provide a high-level executive summary of the standard. Explain the macro-level industry problem this standard aims to solve and the general approach taken by DECADE-X.*

1. #  **SCOPE** {#scope}

This section is normative

1. ## **General Scope** {#general-scope}

***Description:** The Scope clearly defines the subject of the document and the aspects covered, thereby indicating the limits of applicability of the document or particular parts of it.*  
*This section acts as the **legal boundary** of the document. Do not describe the business workflow here. Focus on the technical artifact.*

***What is covered:***   
*What is the technical object defined in the document?*   
*(ex: This document specifies the Data Model and API for…)*

***Applicability:***   
*To which system of interfaces does it apply?*   
*(Applies to the interface between the business app and…)*

***Target Audience:***   
*Who is expected to read the document and implement the standard?*   
*(IT Architect, DevOps, …) **Do not list or describe business roles here***

***Out of Scope:***   
*What is explicitly excluded?*

2. ## **Conformance and Notations** {#conformance-and-notations}

If sections are marked as non-normative, all authoring guidelines, diagrams, examples, and notes in these sections are non-normative. Everything else in this specification is normative.

The key words MAY, MUST, MUST NOT, OPTIONAL, RECOMMENDED, REQUIRED, SHOULD and SHOULD NOT in this document are to be interpreted as described in \[[BCP 14](https://www.rfc-editor.org/info/bcp14)\],  \[[RFC2119](https://www.w3.org/TR/did-1.0/#bib-rfc2119)\], \[[RFC8174](https://www.w3.org/TR/did-1.0/#bib-rfc8174)\] when, and only when, they appear in all capitals, as shown here.

2. #  **NORMATIVE REFERENCES** {#normative-references}

This section is normative

***Description**: List here all the external documents that are indispensable for the application of this document. If a document is listed here, it becomes part of the law of your standard.*  
*If this document references a specific semantic model external to DECADE-X (ex: a specific version of a BAMM/SAMM model), it MUST be listed here.*

***Expected content: (Not exhaustive)***

* ***Official standards** (ex: ISO 27001, ISO 9001, …)*  
* ***Laws and Regulations:** (GDPR, EASA Part 21, ITAR,...) if current standards relies on precise legal definitions*  
* ***Semantic models**: If the model is stored on an external Github repository, the Github link serves as a normative reference*  
* ***Others DECADE-X Standards***

*Format: **\[Reference ID\]** \- \[“Title”\] \- \[Version, Date, Link\]*

The following documents are referred to in the text in such a way that some or all of their content constitutes requirements of this document.

**\[RFC2119**\] Bradner, S., \["Key words for use in RFCs to Indicate Requirement Levels"\], BCP 14, RFC 2119, March 1997\. [https://www.rfc-editor.org/info/rfc2119](https://www.rfc-editor.org/info/rfc2119)

**\[RFC8174\]** Leiba, B., "Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words", BCP 14, RFC 8174, May 2017\. [https://www.rfc-editor.org/info/rfc8174](https://www.rfc-editor.org/info/rfc8174)

3. #  **TERMS AND DEFINITIONS** {#terms-and-definitions}

This section is normative

***Description:** Define the specific vocabulary and necessary definitions to avoid ambiguity and provide a clear comprehension in the document.*

*In order to avoid the unnecessary proliferation of terminological variants, it is recommended to use existing terminological entries from International Standards. Search for suitable terms existing in the terminology databases of ISO and IEC:*  
[*https://www.iso.org/obp/ui*](https://www.iso.org/obp/ui)  
[*https://www.electropedia.org/*](https://www.electropedia.org/)

*Format: **Term:** Definition*

4. # **MAIN CONTENT** {#main-content}

   1. ## **Business Context**  {#business-context}

   This section is mixed

***Description:** This section explains the “**WHO”**,the **“WHY”**, and the **“WHEN”** of the standard. It helps to connect the industrial world with the digital space. It provides the operational context for the needs, the expected result and who is going to be impacted.*  
*This section provides also a description of the process workflow for a better understanding and implementation of the standard among organizations.*  
***Do not include code here***  
*This section is discussed before the **”HOW”** that will be defined later in the section “Technical Aspect”.*

*Suggested sub-chapter structure:*

1.  **Personae**

***Description:** Define the key actors (the **“WHO”)** that are part of the process and the interaction between them in the supply chain. (ex: “The supplier who ships a material”, “The Customer who receive it”)*  
*It’s mandatory to map these Business Roles to the Technical System Roles (ex: The Supplier acts as the Data Provider)*  
*By identifying the business and technical roles impacted during the standard creation process, once standard published we will be able to:*

* *Have a clear definition of the business role impacted, thanks to a common definition for each organization, and the interaction between them*  
* *Identify quickly the right business role in the organization to define the access policies*

  2. **Value creation**

***Description:**  Identify and provide a description of the **value** during the information exchange. This subchapter allows the reader  to understand the business or human needs clearly before defining and diving into the technical solution. This section explains the “**WHY”.***

*Format:*   
***AS A** \[Business Role\] (The position with a need)*  
***I WANT TO** \[Business Action\] (Definition of the needs during the process)*  
***SO THAT** \[Benefits of the solution\] (Why it’s important to achieve this goal? Security, Compliance, …)*

*Exemple:*   
***AS A** Quality Manager in logistics*  
***I WANT TO** automatically verify the material certificate immediately after scanning the incoming shipment box*  
***SO THAT** I prevent non-compliant parts from entering the warehouse inventory*

3. **Process flow**

***Description:** While the previous chapters were providing context and value of the exchange, this section will explain the operational view of the process provided by the user story and its execution.This chapter provides a logical chronologic sequence of events that leads to a data exchange: from the physical operation to a digital response. This section explains the “**WHEN”.***

*This section is expected  to be completed as follows:*

* *Initialization: The specific events that launch the process*  
* *Prerequisites: List all technical/business aspects necessary to comply before the process starts*  
* *Process: Step-by-Step workflow between the data provider and the data consumer*

**Visual representation:** *Represent the business workflow using **BPMN***

4.  **Business Rules**

***Description:** This section defines the logical constraints, operational requirements, and decision-making rules that govern the business process execution. While the Process Flow (4.1.3) defines **when** actions occur, Business Rules define **what** is allowed or required under specific conditions.*

2. ## **Technical architecture** {#technical-architecture}

   This section is mixed

***Description:** This section defines the technical architecture and protocols required to implement the business process defined in the previous section. It explains the **“HOW”**.*  
*It must provide sufficient details for a system architect to configure their system and connectors to be compliant with the DECADE-X ecosystem.*  
*A Component Diagram showing the interaction between the Consumer, Provider, and Registry is mandatory in this section.UML Sequence diagrams must be provided to detail technical processes.*  
*This section is not focused on the data flowing inside the technical infrastructure, which belongs to the next section “Data and Semantic Model”.*

*Example of structure:*  
*4.2.1.	Global Architecture*  
*4.2.2.	Application programming interfaces*  
*4.2.3.	Technical processes*

3. ## **Data models and semantic** {#data-models-and-semantic}

   This section is mixed

   

***Description:** This section defines the structure of the data that will be exchanged through the technical architecture defined in the previous section. It provides the syntax and the semantics of the data*  
*This section explains the **“WHAT”.***

*Suggested sub-chapter structure:*  
*4.3.1.	Semantic model (Reference to the semantic standard used, URI in the Semantic hub)*  
*4.3.2   Data dictionary (Provide a list of attributes (ex: Name, Type, Description, …)*  
*4.3.3   Data Format*   
*4.34	Code (Provide the code to be implemented)*

* *If the code is short, it can be added directly in the section*  
* *If the code is too long, it can be added in the Annex and referred here*

*4.3.5. Data Products*

***Description:** This section defines how Data Products serve as curated, governed data asset that packages data, metadata, and logic for immediate, trustworthy consumption within the ecosystem. It acts as the functional unit of exchange, ensuring that data is not merely "raw" but is delivered as a value-added product that adheres to the **Six Axes of Quality**: Accuracy, Completeness, Consistency, Timeliness, Validity, and Uniqueness. Within the federated architecture, these products remain under the control of the provider and are exchanged peer-to-peer via **Eclipse Dataspace Connectors (EDC)**.*

***4.3.5.1. Main Data Product*** 

*The **Main Data Product** (MDP) serves as the comprehensive **"toolkit"** or master definition for a specific use case. It represents the total theoretical scope of data attributes, semantic structures, and logic required to support a business domain's requirements.*

*The MDP must undergo the formal **D-X Standardization Governance** lifecycle, progressing from proposal to a "Standardized" status endorsed by the Project Management Committee (?). Because the MDP is the foundation for all derived exchanges, it must satisfy all technical validation and business validation standards defined by the underlying **Data Product Governance.** It contains the full set of potential attributes available for that specific use case, serving as the "blueprint" from which specific operational views are derived.*

***4.3.5.2. Data Product Contexts***

*While the MDP is the universal toolkit, a Data Product Context (DPC) is defined to adapt that broad scope to specific operational realities. This is achieved through a Data Product Context, which is a tailored, de-scoped subset of the MDP.*

*Example – Aircraft Program Segmentation: If the MDP defines all possible maintenance data for an engine type, a specific Context might be restricted to a single aircraft program (e.g., the A350 series) or a specific product series.*

*\- The Rationale for Contextualization: By narrowing the scope to a specific program context, participants can apply "De-Pollution" techniques—such as filtering out sensitive pollutants or reducing data precision—to lower the overall classification of the exchange.*

*\- Risk of "Sensitivity Pollution": If an exchange is not restricted to a specific context and instead utilizes the full breadth of the MDP, the entire transaction may inherit the highest level of restriction found in any single attribute (e.g., National Security or Export Control).*

*\- Operational Impact: Failure to define a narrow context would mandate the implementation of intensive "Hard" and "Soft" rules across the entire exchange. This includes:*

   *\- Accreditations: Requirement for participants to hold specific security or industrial accreditations.*

   *\- Secured Platforms: Mandatory use of hardened infrastructure and specialized EDC configurations.*

   *\- Governance & Audits: Specific training for Use Case Managers and manual oversight to ensure compliance with non-technical "Soft Rules".*

*By defining a precise context, participants ensure Data Minimization, allowing for a more resilient and less friction-heavy exchange process*

4. ## **Legal & Regulatory framework** {#legal-&-regulatory-framework}

This section is mixed

***Description:** This section defines the specific legal obligations, regulations, or compliance requirements that drive or constrain this use case. It answers the question: “Are there laws or specific contractual frameworks governing this data exchange?”*

***Expected Content: (Example)***

* ***Regulatory drivers:** Cite the specific regulations*  
* ***Data sovereignty & Export Control:** Mention if data is subject to export restriction or specific residency requirements*  
* ***Antitrust/Competition***  
* ***Data rights:** Clarify who owns the data (ex: The Manufacturer retains the ownership, The customer gets a usage licence only)*

5. # **CONFORMITY ASSESSMENT** {#conformity-assessment}

This section is mixed

***Description:** This section defines the rules and procedures to verify if the implemented solution complies with the requirement defined in this standard. Later, this section will be used as an authoritative guide for **CAB** (Conformity Assessment Body) to certify newcomers to join the ecosystem.*  
*It will also be used by developers to perform a self-assessment before asking to join the ecosystem.* 

1. ## **Proof of conformity** {#proof-of-conformity}

This section is normative

***Description:*** *Provide a consolidated checklist of criteria that determines if the implementation of the solution is compliant or not. This section is presented as a summary of normative rules defined in section **4**, organized for an auditor.*  
*The checklist of criteria must be presented as bullet point with a binary outcome with a clear Outcome: Pass/Fail*  
*Avoid subjective criteria like “The system must be fast”. Choose “The system respond in less than 500ms as defined in Section 5.x”*

***Format:*** \[ \] *\[Specific criteria approving the correct implementation of the solution\] as defined\* in Section X.X*

2. ## **Testing And Validation *(Optional)*** {#testing-and-validation-(optional)}

This section is informative

***Description**: Define the specific Test or Scenario to be executed to demonstrate the criteria in Section 5.1.*  
*Each test or scenario executed here must have been presented in the previous section. Do not introduce new technical requirements here. This section is only designed to test what was already defined. The objective here is to define the user journey by presenting the script of the test and the outcome expected.*  
*Each test must be linked to an acceptance criteria defined in 5.1.*

6. # **ANNEX** {#annex}

This section is mixed

***Description:** Annexes are used to provide additional information to the main body of the document and are developed for several reasons, for example:*  
*• when the information or table is very long and including it in the main body of the document would distract the user;*  
*• to set apart special types of information (e.g. software, example forms, results of interlaboratory tests, alternative test methods, tables, lists, data);*  
*• to present information regarding a particular application of the document.*

1. ## **Normative Annex *(Optional)*** {#normative-annex-(optional)}

   This section is normative

***Description:** Provide here all documentation or links that are legally part of the standard.*  
*This section is normative and must be taken into account when implementing the solution.*

*Example: Official repository, Code, …* 

2. ## **Informative Annex *(Optional)*** {#informative-annex-(optional)}

   This section is informative

***Description:** Informative annexes provide additional information intended to assist the understanding or use of the document. Informative annexes may contain optional requirements. For example, a test method that is optional may contain requirements but it is not necessary to follow these requirements to claim conformance with the document.*

7. # **BIBLIOGRAPHY *(Optional)*** {#bibliography-(optional)}

This section is informative

***Description:** The Bibliography lists, for information, those documents which are cited informatively in the document, as well as other information resources. The Bibliography is an informative element. It shall not contain requirements, permissions or recommendations.*