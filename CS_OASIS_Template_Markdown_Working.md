\<

# **OASIS Open Specification Template Instructions**

## **General Template Instructions**

**Template Instructions:** All template instructions are included within angle brackets and need to be deleted prior to publication. This includes these five pages.

**Square Brackets**: Nearly all text within square brackets need to be updated or replaced, except for any reference tokens that also use square brackets. For formats that support it, this text will be highlighted in yellow.  

## **Formatting Instructions**

The following formatting instructions are applicable to formats that can support them. For formats like Markdown, the editors **SHOULD** be mindful of these instructions and use them when they can. Document formats that use styles (like HTML or XHTML) **MUST** embed their own formatting characteristics in their document. Separate CSS stylesheets are deprecated and **MUST NOT** be used.  

**Margins:** The top margin **SHOULD** be 0.75 inches, the left and right margins **SHOULD** be 0.7 inches, and the bottom margin **SHOULD** be 1.0 inch, when used in formats that support actual pages (paginated formats), aka Google Docs, Word, PDF, etc.

**Font Face and Size**: Documents **SHOULD** use one of the following fonts throughout the document: Helvetica Neue, Cambria, Arial, Times New Roman, Liberation Serif, or Liberation Sans. Consolas, Cambria Math, and Symbols **MAY** be used for specialized text. Unless otherwise specified, all text **SHOULD** be in 10-point font with a color of \#000000. 

**Font Line Spacing**: The line spacing **SHOULD** be 1.15 with an additional 0 points before and 0 points after. Figures, tables, and equations may use other point sizes as needed.

**Paragraph Spacing**: There **SHOULD** be a single empty line between paragraphs. In some cases, editors may add additional spacing to improve readability and the cosmetic look of the section, especially around figures, tables, and charts.

**Quotes:** Straight "quotes" **SHOULD** be used, not “smart quotes” or curly quotes. This can be set as a persistent preference in most writing tools.

**Document Title and Subtitle:** The title of the document **SHOULD** be written in title case, meaning all words that have four or more letters **SHOULD** be capitalized. The title **SHOULD** be in 14-point bolded font with a color of \#0b5394. If a subtitle is needed or desired, then it **SHOULD** also be written in title case, in 11-point bolded font, and with a color of \#0b5394. Please note that the sections in the front matter of the specification use the Subtitle format.

**Headings**: While various editors and formats support up to 6 levels of nested headers it is generally advised to structure the document to minimize the number of nested sections. A best practice is to try and keep nesting to no greater than 3 levels of headings. All headings **SHOULD** be written in title case, meaning all words that have four or more letters **SHOULD** be capitalized. 

**Heading Level 1**: **SHOULD** be in 16-point bolded font with a color of \#0b5394 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 0 points before and 6 points after.

**Heading Level 2**: **SHOULD** be in 14-point bolded font with a color of \#0b5394 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 14 points before and 6 points after.

**Heading Level 3**: **SHOULD** be in 13-point bolded font with a color of \#0b5394 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 10 points before and 4 points after.

**Heading Level 4**: **SHOULD** be in 12-point non-bolded font with a color of \#0b5394 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 6 points before and 4 points after.

**Heading Level 5**: **SHOULD** be in 11-point non-bolded font with a color of \#0b5394 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 6 points before and 4 points after.

**Heading Level 6**: **SHOULD** be in 10-point non-bolded font with a color of \#000000 and prefixed with a number without an ending period. The line spacing **SHOULD** be 1.15 with an additional 6 points before and 4 points after.

**Tables**: Text presented in tables **SHOULD** be no smaller in font size than the body copy text.

**Pagination**: If the document format supports fixed pages / pagination, then it is best practice to include a page break before each H1 heading section and its horizontal line. In this template, this is only done for "Section 1 Scope" as an example. It is not done for other H1 sections so as to shorten the length of the template. 

**Page Numbers**: Document formats that support fixed pages / pagination **SHOULD** include a page number in the footer. Formats that do not support fixed pages / pagination **SHOULD** omit page number references in the Table of Contents but **MUST** retain a Table of Contents / index of headings just without the page numbers.

**Headers and Footers**: Other than page numbers in the footer, no other information **SHOULD** appear in the headers or footers.

**Mathematical Syntax and Equations:** Editors **SHOULD** consider using either the Google Docs Equation Editor or the Wiris MathType plugin to create mathematical representations. All equations, listings, code snippets, figures (Fig. 1), tables (Table 1), etc., need to be referenced in the text (preferably before their appearance). 

**Equations:** All equations **MUST** be numbered, **MAY** use a section number dot code equation number (see example below) to track the equations within a particular section, and **SHOULD** be numbered consecutively where the number is in parentheses and right margin flushed. All symbols in the equation **SHOULD** be defined before the equation appears in the text. When referring to an equation or formula, use for example "Eq. 1.1".

					        y2 \= x3 \+ ax \+ b 	       				(Eq. 1.1)

**Listings:** All algorithms and pseudo code **MUST** be numbered, **MAY** use a section number dot listing number (see example below) to track the listing within a particular section, **SHOULD** be numbered consecutively, and **SHOULD** include a short title forming a header. There **SHOULD** be a line above and below the header and a line at the bottom of the algorithm. The text of the header **SHOULD** be indented approximately 0.1 inches and **SHOULD** have a line spacing of single (1.00) with an additional 0 points before and 0 points after. Figures, tables, and equations may use other point sizes as needed.

---

	**Listing 1.1** Sample Title  
---

    currentMax ← A\[0\]  
        for i ← 1 to n \-1 do  
            if A\[i\] \> currentMax then  
                currentMax ← A\[i\]  
        { increment counter i }  
        return currentMax  
---

**Code Snippets**: Actual code samples and snippets **MUST** be numbered, **MAY** use a section number followed by a dot which is then followed by a code sample number (see example below) to track the code samples within a particular section, **SHOULD** be numbered consecutively, and **SHOULD** include a short title forming a header. There **SHOULD** be a line above and below the header. The text of the header **SHOULD** be indented approximately 0.1 inches and **SHOULD** have a line spacing of single (1.00) with an additional 0 points before and 0 points after. A single header **MAY** be used for multiple code samples in a block, but in this case, each sample **SHOULD** individually be numbered as shown below. The code itself **SHOULD** use the Markdown style code snippet syntax. Meaning that the first code line will start with three back tick characters (\`\`\`) followed by the language (e.g., json, yaml, cpp, go, etc) and the last line starts with three back tick characters (\`\`\`).

---

	**Code 1.1** Sample Title  
---

*Some subheading (e.g., Example 1.1.1 \- Some example code)*  
\`\`\`json  
{  
  "Some key": "some value"  
}  
\`\`\`

*Some subheading (e.g., Example 1.1.2 \- Some other example code)*  
\`\`\`json  
{  
  "Some other key": "some other value"  
}  
\`\`\`

**Referring to Figures and Tables**: All figures **MUST** be numbered and **MAY** use a section number followed by a hyphen which is then followed by a figure number (see example below) to track the figures within a particular section. When referencing a figure or table please use the abbreviation "Fig." for figures and "Table" for tables. Tables **SHOULD** be numbered with Roman numerals.

Figure 2-1  
![][image1]  
**Fig. 2-1.** This is a sample of a figure caption.

Table I  
This is a Sample of a Table Title

| Name | \#1 | \#2 | \#3 | \#4 | \#5 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **AB** | 3 | 3 | 6 | 11 | 9 |
| **BC** | 7 | 7 | 4 | 12 | 9 |
| **CD** | 10 | 3 | 3 | 9 | 7 |
| **DE** | 3 | 7 | 10 | 5 | 6 |
| **DF** | 7 | 1 | 12 | 1 | 3 |
| **ZZ** | 5 | 12 | 11 | 9 | 8 |

**Table I:** This table contains information about x and y and z.

**References:** OASIS uses the IEEE Reference format for citations. However, unlike the IEEE Reference format the in-line tokens can be either named or a number, in either case they are enclosed in square braces. Editors **SHOULD** be consistent in the body of the specification and use either named tokens "\[RFC2119\]" or numbered "\[1\]" tokens, but not both. Any named tokens that are used in the template front matter do not impact the decision about named or numbered in the body of the document. All other rules about in-line use and style **MUST** follows the IEEE Reference format found here: [https://journals.ieeeauthorcenter.ieee.org/wp-content/uploads/sites/7/IEEE\_Reference\_Guide.pdf](https://journals.ieeeauthorcenter.ieee.org/wp-content/uploads/sites/7/IEEE_Reference_Guide.pdf)

**Definitions and Terms:** It is generally more consistent to refer to an existing official definition in other open standards or readily-available nonproprietary reference documents, rather than to redefine a term. It is a best practice to refer to the specific version or date of the source document for a definition, either explicitly or by a reference link to the specific version (not a ‘current version’ link). Normally, terms defined elsewhere will simply refer to the defining document. In certain cases, it may be desirable to quote the definition to allow for a stand-alone document. Before defining a new term, verify whether it has already been defined in an official document elsewhere such as in another OASIS Standards, the ITU terminology database ([https://www.itu.int/br\_tsb\_terms/\#/](https://www.itu.int/br_tsb_terms/#/)), ISO terms ([https://www.iso.org/obp/ui](https://www.iso.org/obp/ui)), IEEE/IEC electropedia ([https://www.electropedia.org/IEEE](https://www.electropedia.org/IEEE)), IETF, CEN/CENELEC, or NIST ([https://csrc.nist.gov/glossary](https://csrc.nist.gov/glossary)).

**Annex vs Appendix:** An annex is considered normative, meaning that it **MUST** be included with the specification and its contents form an integral part of the Specification. Whereas an Appendix is purely informational content and is not required to be included with the document.

Under the heading of each Annex the following text **MUST** be present:  
(This annex forms an integral part of this Specification.)

Under the heading of each Appendix the following text **MUST** be present:  
(This appendix does not form an integral part of this Specification and is informational.)

Annex A **MUST** be the License, Document Status and Notices information.  
Annex B **MUST** be the References information.  
Annex C **MUST** be the Safety, Security and Privacy Considerations information.  
Annex D+ can be whatever is needed  
Appendix 1 **MUST** be the Acknowledgments information  
Appendix 2 **MUST** be the Revision History information  
Appendix 3+ can be whatever is needed

\>![][image2]  
---

# **\[ DOCUMENT NAME \] Version \#.\#**

## **Committee Specification \[ Draft \] \#\#**

## **\[ DD \] \[ Month \] \[ YYYY \]**

## **​This version**

* \[ link to authoritative version of the published document \] (Authoritative)  
* \[ links to one or more other versions of the published document (e.g., MD, PDF, Word, HTML) \] 

## **Previous version**

* \[ link to authoritative version of the published document \] (Authoritative)  
* \[ links to one or more other versions of the published document (e.g., MD, PDF, Word, HTML) \] 

## **Latest version**

* \[ link to authoritative version of the published document \] (Authoritative)  
* \[ links to one or more other versions of the published document (e.g., MD, PDF, Word, HTML) \] 

## **Technical Committee**

\[ The full name of the technical committee linked to their landing page \]

## **Chair(s)**

* \[ First Name Last Name (email), Company \]   
* \[ First Name Last Name (email), Company \] 

## **Editor(s)**

* \[ First Name Last Name (email), Company \]   
* \[ First Name Last Name (email), Company \] 

## **Abstract**

\[ Document abstract \]

## **Citation Format**

When referencing this document, the following citation format should be used:

* \[ The full reference for this document in IEEE reference format \] 

## **Related Work**

This document replaces or supersedes:

* \[ The full reference to the related document in IEEE reference format \] 

This document is related to:

* \[ The full reference to the related document in IEEE reference format \] 

## **License, Document Status, and Notices**

Copyright © OASIS Open 202\[ 5 \]. All Rights Reserved.  For license and copyright information, and complete status, please see Annex A which contains the License, Document Status and Notices.

---

**Table of Contents**

[**1 Scope	9**](#1-scope)

[**2 Definitions and Acronyms	9**](#2-definitions-and-acronyms)

[2.1 Definitions	9](#2.1-definitions)

[2.1.1 Terms Defined Elsewhere	9](#2.1.1-terms-defined-elsewhere)

[2.1.2 Terms Defined in this Document	9](#2.1.2-terms-defined-in-this-document)

[2.2 Abbreviations and Acronyms	9](#2.2-abbreviations-and-acronyms)

[**3 Document Conventions	10**](#3-document-conventions)

[3.1 Key Words	10](#3.1-key-words)

[3.2 Typographical Conventions	10](#3.2-typographical-conventions)

[**4 Introduction	10**](#4-introduction)

[4.1 Any Additional Introduction Subsections That are Needed	10](#4.1-any-additional-introduction-subsections-that-are-needed)

[4.2 Changes From the Previous Version	10](#4.2-changes-from-the-previous-version)

[**5 Level 1 Section Header	10**](#5-level-1-section-header)

[5.1 Level 2 Section Header	10](#5.1-level-2-section-header)

[5.1.1 Level 3 Section Header	10](#5.1.1-level-3-section-header)

[5.1.1.1 Level 4 Section Header	10](#5.1.1.1-level-4-section-header)

[5.1.1.1.1 Level 5 Section Header	10](#5.1.1.1.1-level-5-section-header)

[5.1.1.1.1.1 Level 6 Section Header	10](#5.1.1.1.1.1-level-6-section-header)

[**6 Additional Sections as Needed	11**](#6-additional-sections-as-needed)

[**7 Conformance	11**](#7-conformance)

[**Annex A License, Document Status and Notices	12**](#annex-a-license,-document-status-and-notices)

[A.1 Document Status	12](#a.1-document-status)

[A.2 License and Notices	12](#a.2-license-and-notices)

[**Annex B References	14**](#annex-b-references)

[B.1 Normative References	14](#b.1-normative-references)

[B.2 Informative References	14](#b.2-informative-references)

[**Annex C Security and Privacy Considerations	15**](#annex-c-security-and-privacy-considerations)

[**Annex D Additional Annex as Needed	16**](#annex-d-additional-annex-as-needed)

[D.1 Subsection Title	16](#d.1-subsection-title)

[D.1.1 Sub-subsection	16](#d.1.1-sub-subsection)

[**Appendix 1 Acknowledgments	17**](#appendix-1-acknowledgments)

[Leadership	17](#leadership)

[Special Thanks	17](#special-thanks)

[Participants	17](#participants)

[**Appendix 2 Revision History	18**](#appendix-2-revision-history)

[**Appendix 3 Additional Appendix as Needed	19**](#appendix-3-additional-appendix-as-needed)

[Subsection Title	19](#subsection-title)

[Sub-subsection	19](#sub-subsection)

---

# **1 Scope** {#1-scope}

\<   
What is the purpose and scope of this document?   
Best practices: 

* Expect this text to be reused in multiple other places to explain the specification in summary form.  
* This is not the TC or OP scope (which is an IPR and rules boundary);  rather, this section is the summary intended purpose of this specification.  
* Short is better; four paragraphs or less is recommended.  
* If use of this spec is deliberately created to rely on or complement another standard, consider briefly mentioning that here as context.  
* To the extent that discussion of the larger context of the spec, or its history, or the circumstances that led to its creation or revision, are necessary, they belong in the Introduction, not here. 

\>

---

# **2 Definitions and Acronyms** {#2-definitions-and-acronyms}

## **2.1 Definitions** {#2.1-definitions}

### **2.1.1 Terms Defined Elsewhere** {#2.1.1-terms-defined-elsewhere}

This document uses the following terms defined elsewhere:

* Term 1: \[Reference\]: optional quoted definition.  
* Term 2: \[Reference\]: optional quoted definition.  
* etc

### **2.1.2 Terms Defined in this Document** {#2.1.2-terms-defined-in-this-document}

This document defines the following terms:

* Term 1: some definition.  
* Term 2: some definition.  
* etc

## **2.2 Abbreviations and Acronyms** {#2.2-abbreviations-and-acronyms}

This document uses the following abbreviations and acronyms:

* Term 1: expanded form.  
* Term 2: expanded form.  
* etc

---

# **3 Document Conventions** {#3-document-conventions}

## **3.1 Key Words** {#3.1-key-words}

The key words "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**", "**SHOULD**", "**SHOULD NOT**", "**RECOMMENDED**", "**NOT RECOMMENDED**", "**MAY**", and "**OPTIONAL**" in this document are to be interpreted as described in BCP 14 \[RFC2119\] \[RFC8174\] when, and only when, they appear in all capitals, as shown here.

## **3.2 Typographical Conventions** {#3.2-typographical-conventions}

\< Describe any standards or typographical conventions that were followed when writing this document, such as fonts or highlighting that have special significance. If there are no typographical conventions than one is to put "None". \>

---

# **4 Introduction** {#4-introduction}

\< Any introductory text that is needed to explain this document \>

## **4.1 Any Additional Introduction Subsections That are Needed** {#4.1-any-additional-introduction-subsections-that-are-needed}

\< Any needed text \>

## **4.2 Changes From the Previous Version** {#4.2-changes-from-the-previous-version}

\< Any explanatory text about the reason for this version. All major changes **SHOULD** be in a bulleted list so that reviewers and implementers can easily understand what they need to know. This subsection is **REQUIRED** and **MUST** be the last numbered subsection in the introduction. If there are no changes then one is to put "None." \>

* Change 1  
* Change 2

---

# **5 Level 1 Section Header** {#5-level-1-section-header}

## **5.1 Level 2 Section Header** {#5.1-level-2-section-header}

### **5.1.1 Level 3 Section Header** {#5.1.1-level-3-section-header}

#### 5.1.1.1 Level 4 Section Header {#5.1.1.1-level-4-section-header}

##### 5.1.1.1.1 Level 5 Section Header {#5.1.1.1.1-level-5-section-header}

###### 5.1.1.1.1.1 Level 6 Section Header {#5.1.1.1.1.1-level-6-section-header}

---

# **6 Additional Sections as Needed** {#6-additional-sections-as-needed}

---

# **7 Conformance** {#7-conformance}

\< This section is **REQUIRED** and **MUST** be the last numbered section in the document. \>

---

# **Annex A License, Document Status and Notices** {#annex-a-license,-document-status-and-notices}

(This annex forms an integral part of this Specification.)

## **A.1 Document Status** {#a.1-document-status}

This document was last revised or approved by the \[ full proj name e.g., OASIS Collaborative Automated Course of Action Operations (CACAO) for Cyber Security TC \] on the above date. The level of approval is also listed above. Check the "Latest version" location noted above for possible later revisions of this document. Any other numbered Versions and other technical work produced by the Technical Committee (TC) are listed at \[ proj publication page e.g., https://www.oasis-open.org/committees/tc\_home.php?wg\_abbrev=cacao\#technical \].

TC members should send comments on this document to the TC's email list. Others should send comments to the TC's public comment list, after subscribing to it by following the instructions at the "Send A Comment" button on the TC's web page at \[ proj home page e.g., https://www.oasis-open.org/committees/cacao/ \].

Note that any machine-readable content (Computer Language Definitions) declared Normative for this Work Product is provided in separate plain text files. In the event of a discrepancy between any such plain text file and display content in the Work Product's prose narrative document(s), the content in the separate plain text file prevails.

## **A.2 License and Notices** {#a.2-license-and-notices}

Copyright © OASIS Open 202\[ 5 \]. All Rights Reserved.

All capitalized terms in the following text have the meanings assigned to them in the OASIS Intellectual Property Rights Policy (the "OASIS IPR Policy"). The full Policy, which governs the licensure of this document, may be found at the OASIS website: \[[https://www.oasis-open.org/policies-guidelines/ipr/](https://www.oasis-open.org/policies-guidelines/ipr/)\]

This document and translations of it may be copied and furnished to others, and derivative works that comment on or otherwise explain it or assist in its implementation may be prepared, copied, published, and distributed, in whole or in part, without restriction of any kind, provided that the above copyright notice and this section are included on all such copies and derivative works. However, this document itself may not be modified in any way, including by removing the copyright notice or references to OASIS, except as needed for the purpose of developing any document or deliverable produced by an OASIS Technical Committee (in which case the rules applicable to copyrights, as set forth in the OASIS IPR Policy, must be followed) or as required to translate it into languages other than English.

The limited permissions granted above are perpetual and will not be revoked by OASIS or its successors or assigns, as provided in the OASIS IPR Policy.

This document is provided under the \[ IPR mode or applicable FOSS license e.g., [Non-Assertion](https://www.oasis-open.org/policies-guidelines/ipr/#Non-Assertion-Mode) Mode of the [OASIS IPR Policy](https://www.oasis-open.org/policies-guidelines/ipr/) \], the license mode chosen when the project was established. For information on whether any patents have been disclosed that may be essential to implementing this document, and any offers of patent licensing terms, please refer to the Intellectual Property Rights section of the project’s web page ( \[ e.g., [https://www.oasis-open.org/committees/cacao/ipr.php](https://www.oasis-open.org/committees/cacao/ipr.php) \] ).

This document and the information contained herein is provided on an "AS IS" basis and OASIS DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION HEREIN WILL NOT INFRINGE ANY OWNERSHIP RIGHTS OR ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. OASIS AND ITS MEMBERS WILL NOT BE LIABLE FOR ANY DIRECT, INDIRECT, SPECIAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF ANY USE OF THIS DOCUMENT OR ANY PART THEREOF.

As stated in the OASIS IPR Policy, the following three paragraphs in brackets apply to OASIS Standards Final Deliverable documents (Committee Specifications, OASIS Standards, or Approved Errata).

OASIS requests that any OASIS Party or any other party that believes it has patent claims that would necessarily be infringed by implementations of this OASIS Standards Final Deliverable, to notify OASIS TC Administrator and provide an indication of its willingness to grant patent licenses to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this deliverable.

OASIS invites any party to contact the OASIS TC Administrator if it is aware of a claim of ownership of any patent claims that would necessarily be infringed by implementations of this OASIS Standards Final Deliverable by a patent holder that is not willing to provide a license to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this OASIS Standards Final Deliverable. OASIS may include such claims on its website, but disclaims any obligation to do so.

OASIS takes no position regarding the validity or scope of any intellectual property or other rights that might be claimed to pertain to the implementation or use of the technology described in this OASIS Standards Final Deliverable or the extent to which any license under such rights might or might not be available; neither does it represent that it has made any effort to identify any such rights. Information on OASIS' procedures with respect to rights in any document or deliverable produced by an OASIS Technical Committee can be found on the OASIS website. Copies of claims of rights made available for publication and any assurances of licenses to be made available, or the result of an attempt made to obtain a general license or permission for the use of such proprietary rights by implementers or users of this OASIS Standards Final Deliverable, can be obtained from the OASIS TC Administrator. OASIS makes no representation that any information or list of intellectual property rights will at any time be complete, or that any claims in such list are, in fact, Essential Claims.

The name "OASIS" is a trademark of OASIS, the owner and developer of this document, and should be used only to refer to the organization and its official outputs. OASIS welcomes reference to, and implementation and use of, its documents, while reserving the right to enforce its marks against misleading uses. Please see [https://www.oasis-open.org/policies-guidelines/trademark/](https://www.oasis-open.org/policies-guidelines/trademark/) for guidance.

---

# **Annex B References** {#annex-b-references}

(This annex forms an integral part of this Specification.)

This section contains the normative and informative references along with specific terms, abbreviations, and acronyms that are used in this document. 

Normative references are specific (identified by date of publication and/or edition number or version number) and Informative references are either specific or non-specific. For specific references, only the cited version applies. For non-specific references, the latest version of the reference document (including any amendments) applies. While any hyperlinks included in this section were valid at the time of publication, OASIS cannot guarantee their long term validity.

## **B.1 Normative References** {#b.1-normative-references}

The following documents are referenced in such a way that some or all of their content constitutes requirements of this document.

**\[RFC2119\]** *Key Words for Use in RFCs to Indicate Requirement Levels*, BCP 14, RFC 2119, March 1997\. \[Online\]. Available: https://www.rfc-editor.org/info/rfc2119

**\[RFC8174\]** *Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words*, BCP 14, RFC 8174, May 2017\. \[Online\]. Available: https://www.rfc-editor.org/info/rfc8174

**\[Reference 1\]** Reference Details

**\[Reference 2\]** Reference Details

## **B.2 Informative References** {#b.2-informative-references}

The following referenced documents are not required for the application of this document but may assist the reader with regard to a particular subject area.

**\[Reference 1\]** Reference Details

**\[Reference 2\]** Reference Details

---

# **Annex C Security and Privacy Considerations** {#annex-c-security-and-privacy-considerations}

(This annex forms an integral part of this Specification.)

\< Information about safety, security, data protection, and privacy considerations. These can be divided up into separate subsections as desired. This Annex is **REQUIRED** and all documents **SHOULD** have at least a security and privacy considerations section, and otherwise **MUST** have a blank Annex C indicating “None.” Any other considerations **MAY** also be added in this Annex. Any specification that will need to register something with IANA or has plans to go on to ITU/ISO **MUST** have this section filled out. For an example please see the following section in the CACAO specification here [https://docs.oasis-open.org/cacao/security-playbooks/v2.0/cs01/security-playbooks-v2.0-cs01.html\#\_Toc152256574](https://docs.oasis-open.org/cacao/security-playbooks/v2.0/cs01/security-playbooks-v2.0-cs01.html#_Toc152256574) \>

---

# **Annex D Additional Annex as Needed** {#annex-d-additional-annex-as-needed}

(This annex forms an integral part of this Specification.)

## **D.1 Subsection Title** {#d.1-subsection-title}

### **D.1.1 Sub-subsection** {#d.1.1-sub-subsection}

---

# **Appendix 1 Acknowledgments** {#appendix-1-acknowledgments}

(This appendix does not form an integral part of this Specification and is informational.)

\< All parts in this appendix are optional to the TC. Individuals or companies, past or present, may request that their name and/or affiliation is not included in this list. \>

## **Leadership** {#leadership}

The following individuals have had significant leadership positions during the development of this specification, not just this version of the specification, and they are gratefully acknowledged:

\< This section **SHOULD** include the leadership of this specification, and not just this version of the specification, even if they are no longer members of the TC. \>

* \< List of the chairs, sub committees chairs, secretaries, editors, etc. Note that there are rules about confirming the use of the names of persons by giving them an one-time opt-out opportunity, via the TC’s official channels, prior to publication. \>  
* Chairs  
  * Position, First Name Last Name, Company, \[optional time frames\]  
* Secretaries  
  * Position, First Name Last Name, Company, \[optional time frames\]  
* Editors  
  * Position, First Name Last Name, Company, \[optional time frames\]

## **Special Thanks** {#special-thanks}

The following individuals have made substantial contributions to this specification, not just this version of the specification, and their contributions are gratefully acknowledged:

\< This section **SHOULD** include individuals that have made significant contributions to this specification, and not just this version of the specification, even if they are no longer members of the TC or were never members of the TC, but sent in a contribution through one of the public comment methods. \>

* First Name Last Name, Company

## **Participants** {#participants}

The following individuals were members of this committee during the creation of this specification, not just this version of the specification, and their contributions are gratefully acknowledged:

* First Name Last Name, Company

---

# **Appendix 2 Revision History** {#appendix-2-revision-history}

(This appendix does not form an integral part of this Specification and is informational.)

* \< Revision number \>, \< Date yyyy-mm-dd \>, \< Editor(s) \>  
  * \< Changes Made \>  
* \< Revision number \>, \< Date yyyy-mm-dd \>, \< Editor(s) \>  
  * \< Changes Made \>

---

# **Appendix 3 Additional Appendix as Needed** {#appendix-3-additional-appendix-as-needed}

(This appendix does not form an integral part of this Specification and is informational.)

## **Subsection Title** {#subsection-title}

### **Sub-subsection** {#sub-subsection}

\< The following centered line represents the end of the document \>  
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,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>