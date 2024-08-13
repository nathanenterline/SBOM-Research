# SBOM-Research Paper 
by Nathan Enterline
3/3/2024

## Abstract
  The intent of this paper is to summarize the purpose of the Software Bill of Materials (SBOM)
and its benefit and use for cybersecurity professionals and consumers of software components.
This paper will cover the general history of the SBOM, how the SBOM has evolved since its
inception, and how the cybersecurity and software industry would be affected by the global and
universal acceptance and mandate of the SBOM. This paper will discuss the regulations and
standards for the SBOM and how organizations can generate one. This paper will examine real
world scenarios of cyber-attacks and will deliberate on whether an SBOM would provide
advantages for that scenario. This paper will also discuss the current challenges facing the
SBOM and the additional research and adjustments needed for global implementation of the
SBOM across the software industry

## Global Implementation of the Software Bill of Materials
  As new software continues to be developed, it is inevitable that new vulnerabilities will
emerge in that software which is then likely to affect all devices and users who are using that
specific form of software. One issue that occurs when a vulnerability is discovered within a
software component is tracing all systems and applications that use that vulnerable software
component. For example, if a third party software company distributes software to multiple
organizations for use, then how would the organization purchasing the software know whether or
not a vulnerability exists within coding and the development process of the software? And how
would there be any traceability to discover all systems that use that vulnerable software after it has been distributed? And how would a consumer or organization know if they are using a
vulnerable software component? These questions are some of the main problems that the SBOM
is attempting to solve. And answering these questions is a main reason for the creation and
continual development of the SBOM.
  It can be stated that the history of the SBOM formally began when guidelines for how
companies can draft an SBOM were established by the National Telecommunications and
Information Administration (NITA). “Starting in 2018… NITA began helping industries develop
SBOMs by defining them and identifying existing standards that can be used to automatically
convey SBOM data” (Thryft, 2021). Since the establishment of these guidelines, the SBOM is
still in continual development and refinement. The Cybersecurity and Infrastructure Security
Agency (CISA) hosts regular community driven workstreams to assist in improving the
development of the SBOM which are, “intended to enhance the software and security
communities’ understanding of SBOM creation, use, and implementation across the broader technology ecosystem” (CISA, n.d.). The development of the SBOM hopes to assist in solving
the issue presented by open-source software that is provided by third parties.

## SBOM and Open-Source Software
  In the current digital landscape, much of software used by consumers comes from an
open source. In fact, according to Crane (2022), open-source software makes up around 75% of
codebases. The SBOM was created to provide traceability of software products and allow a
consumer of software to inspect the software to ensure it is secure and clean to use for their own implementation; “An SBOM is a formal, structured record that not only details the components
of a software product, but also describes their supply chain relationship” (Fruhlinger, 2022). This means that consumers of software components are able to verify that their open-sourced software is credible. An SBOM requires suppliers of software to, “document third-party software
components embedded in their products, including open-sourced and commercial code” (Thryft,
2021). With full transparency, other developers can examine components and assess the risk and
their vulnerabilities. Consumers would also have transparency to view the potential vulnerability
that exists within the systems they are using. And because of its detailing of software components, the SBOM can be likened to food packaging and labeling. An SBOM would tell the consumer all the components that make up the software similar to how a food label will inform the consumer of the list of ingredients in the product that they are intending to purchase. An SBOM will help the consumer of the software identify if the software they are consuming contains a known vulnerability and if it is up to date.
  The SBOM can also be likened to a product recall, such as the recall of automotive parts. For
example, in the automotive industry, if a window is found to be defective it would then
commonly be recalled by the manufacturer who was responsible for distributing that vehicle with the malfunctioning window to the consumer. This is typically done to ensure that the
manufacturer does not face any lawsuits. The manufacturer will then locate all vehicles affected
by the defective window and inform the owner of that vehicle that they are using a vehicle with a
defective window and that there is a recall, and the vehicle will then usually be repaired. The
SBOM has the ability to operate in a similar manner to the scenario described. If a manufacturer
discovers that a component of their software has a vulnerability, then an SBOM will allow them
to locate all systems that are affected by that vulnerable component. The manufacture of the
vulnerable component would then have the capability to inform all users of that vulnerable
component that a vulnerability has been discovered. The manufacturer could then provide
mediation to the consumer through the use of a software update.

## SolarWinds Case Review
  As previously mentioned, because the majority of software is open source, this presents
an opportunity for a malicious attacker to infiltrate the supply chain process of the open-sourced code. If an attacker is able to infiltrate the supply chain distribution process of software, thenthey would have the capability to affect multiple organizations. One recent example of a software supply chain attack is the hack on SolarWinds. SolarWinds (2016) is a large-scale corporation that provides services and much of the software products used by other organizations such as Amazon, Apple, Google, Walmart, and McDonalds. They also provide software and services for the federal government.
  One particular platform they provide is known as their Orion Platform; “The SolarWinds
Orion Platform is a powerful, scalable infrastructure monitoring and management platform
designed to simplify IT administration for on-premises, hybrid, and software as a service (SaaS)
environment” (SolarWinds, 2016). This is a powerful platform that many organizations, such as the ones previously described, benefit from. However, a team of hackers were successfully able
to exploit a vulnerability in this platform.
  Keith Barker, from CBT Nuggets (2020), explains that attackers were able to inject
malware into the Orion Platform. And due to the software supply chain process, this malware
was able to affect all of the customers using the Orion Platform from SolarWinds. Keith Barker
from CBT Nuggets (2020) continues to explain that customers of SolarWinds were affected by
this malware due to software updates that SolarWinds sent to its customers. In short, hackers
planted malicious code in the Orion Platform as SolarWinds were preparing to distribute
software updates, that malware went unnoticed by SolarWinds and was eventually distributed to
all organizations using SolarWinds Orion Platform. When the customers of SolarWinds accepted
their software update, they unknowingly infected their system with malicious code. As reported
by Zetter (2023), the attackers were able to hack into SolarWinds by exposing a vulnerability
within their authentication process. Rangari (2023) reports that it has been speculated that the
attack on SolarWinds was targeted to specifically affect the U.S. government and was carried out
by a team of Russian attackers. This speculation has raised a great deal of awareness across
federal agencies to increase their cybersecurity framework.

## SBOM Regulations & Standards
  Not long after the discovery of the SolarWinds incident, in May of 2021, President Biden
issued executive order number 14028. This action was created to, “identify, deter, protect
against, detect, and respond to these actions and actors” (Biden, 2021). This order directed the
NIST to develop draft guidelines for organizations to follow to create an SBOM for federal
procurement. The NIST also defined a set of minimal elements that should be included in an
SBOM which include, “package name, version, unique identifier, licensing information, dependencies, known security vulnerabilities and software hash” (Rangari, 2023). Using the
guidelines established by NITA, third party software providers working for the federal
government must meet the standards of proper formation of an SBOM. Table 1 shows the three
minimal elements required for an SBOM and was adopted by NITA (2021).

### Table 1: Minimum Elements for SBOM
|  Name:  |  Description |
| ---------- | ---------- |
|  Data Fields   | "Document baseline information about component" |
| Automation Support  | "Support automation... to allow for scaling across the software ecosystem" |
|  Practices and Processes  | "Define the operations of SBOM requests generation and use" |

  Note: From "The Minimum Elements for an SBOM," by (NITA, 2021)

  However, these standards are not universal and required outside of the U.S. federal
government. It should be noted that other foreign agencies have their own set of guidelines for
drafting SBOMs outside the United States. According to Rangari (2023), other cyber agencies
include, The EU Agency for Cybersecurity (ENISA), The UK National Cyber Security Centre
(NCSC), The Australian Cyber Security Centre (ACSC), and The Canadian Communications
Security Establishment (CSE). Again, these agencies have their own set of guidelines created for
companies to follow to develop SBOMs.

## Types of SBOMs

  If an organization plans to develop and generate an SBOM, CISA has established six
different types of SBOMs that an organization is able to generate. Spiewak (2023), notes that the six different SBOM types include “Design,” “Source,” “Build,” “Analyzed,” “Deployed,” and
“Runtime.” Each type of SBOM has its own purpose and definition. Table 2 is adopted from
Spiewak (2023) and lists the six types of SBOMs that can be gendered along with a brief
description for how they are generated.

### Table 2: CISA's SBOM Types
|  Name:  |  Description  |
| ---------- | ---------- |
|  Design  | "Derived from a design specification, PRP, or inital concept" |
|  Source  | "Generated from software composition analysis (SCA) tooling" |
|  Build  | "Generated as part of the process of building the software" |
|  Analyzed  | "Generated through analysis of artifacts by 3rd party tooling" |
|  Deployed  | "Generated by recording the SBOMs and configuration information of artifacts that have been installed on systems" |
|  Runtime  | "Generated from tooling interacting with system to record the artifacts present in a running environment" |

  Note: From "CISA's 6 SBOM Types," by (Spiewak, 2023)

  All the listed SBOMs can be generated by organizations to assist in satisfying a consumer's
request for a SBOM and all of the six generation methods will provide the requester with a
different SBOM. But it should be noted that if an organization is required to generate an SBOM
to meet the minimal elements required that were established by NITA, then Synopsys (n.d.) would recommend using the Build and Analyzed methods for generating an SBOM. This is because these two methods of generation will generate a SBOM that complies with the minimal elements required to be included on an SBOM.

## SBOM Challenges

  Although guidelines and resources exist for organizations to generate and provide
SBOMs to consumers, the SBOM is still not universally required, and security professionals are
currently having conversations to correct underlying issues. In fact, Xia et al. (2023) published a study in 2023 where they interviewed and surveyed security professionals and SBOM
practitioners on their opinion on the current state of SBOMs. This study helps to illustrate the
general opinion of the SBOM from security professionals and some of the specific problems
facing the SBOM today from software industry adaptation.
  Toomey (2023) notes that more than 80% of respondents felt that adaptation for the
SBOM across the software industry is lagging. A key reason as to why the SBOM is not globally
adopted is because there is a lack of consensus on what an SBOM is required to include.
Although there are many guidelines and recommendations for organizations to generate an
SBOM, “63% of respondents agreed that in practice, generated SBOMs don’t always meet the
minimum bar” (Toomey, 2023). As previously mentioned, multiple federal agencies have their
own set of recommendations for what an SBOM should include. The respondents in the study
from Xia et al. (2023) believe that the software industry is struggling to provide SBOMs because
there is no universally accepted standard for what to include on an SBOM.
  Another hurdle facing the SBOM is a lack of mature tooling for generation; “The
majority of respondents (65%) agreed that SBOM tools can be hard to use due to various
reasons” (Toomey, 2023). Because tools to generate an SBOM can be challenging to use in situations, the organization may not be able to produce and provide a proper SBOM. This means
that the tools for generating SBOMs must be accurate and easy to use by organizations to
generate an SBOM.
  Another key finding in the study by Xia et al. (2023), is that the majority of respondents
felt that there is a lack of strategic vulnerability management; “While vulnerabilities should be
uncovered, not all vulnerabilities are exploitable, so vulnerability management needs to be
strategic” (Toomey, 2023). CISA has created a document called “Vulnerability Exploitability
eXchange (VEX).” The purpose of VEX, “is to allow a software supplier or other parties to
assert the status of specific vulnerabilities in a particular product” (CISA, 2022). This is
beneficial for organizations because if multiple vulnerabilities are discovered, they can use a
VEX document to focus their time on mitigating the vulnerabilities that pose the highest security
risk. However, this research study from Xia et al. (2023) found that the respondents are skeptical on the reliability of VEX. In fact, one respondent is quoted by saying, “I don’t agree that the ones defined as less exploitable are not valuable. I used to be on the attacker’s side … Hackers can take their time, and they can find a way to put together a lot of things that look very not exploitable, and… find themselves with very easy and exploitable access” (Xia et al., 2023). Based on the research study of Xia et al. (2023), it is apparent that the SBOM needs continual development and refinement in order to be easily accepted and adapted within the software supply industry.

## Conclustion

  The developers of the SBOM have established a clear goal and intention of enhancing the
transparency of software components provided to consumers from third parties. Since its
inception, the SBOM has become, “a key building block in software security and software supply chain risk management” (CISA, n.d.). Because the SBOM functions by providing a list of
all software components, it has the benefit to cybersecurity professionals and consumers by
providing valuable information of all the components within the software which would include
any potential vulnerabilities. As aforementioned in this paper, because of the challenges facing
the SBOM, the SBOM is in continual development and refinement. The SBOM is not currently a
perfect solution and challenges such as lack of universal standard, mature generating tools, and
vulnerability management are only a specified set of challenges for the SBOM to reach a state of
universal acceptance and adaptation. CISA (n.d) plans to advance the SBOM with community
engagement with hopes of solving the issues mentioned, giving hopes for the SBOM to become a
standard and globally accepted across the software supply chain industry.

## References

Improving the Nation’s Cybersecurity, no. 14028, White House (2021).
CBT Nuggets. (2020). The SolarWinds Hack Explained | Cybersecurity Advice [YouTube
Video]. In YouTube. https://www.youtube.com/watch?v=jD02Q3RStaM
CISA. (n.d.). Software Bill of Materials | CISA. Www.cisa.gov. https://www.cisa.gov/sbom
CISA. (2022). Vulnerability Exploitablility eXchange (VEX) - Use Cases.
https://www.cisa.gov/sites/default/files/publications/VEX_Use_Cases_Document_508c.p
df
Crane, D. (2022, September 29). Why The US Government Is Mandating Software Bill Of
Materials (SBOM). ActiveState. https://www.activestate.com/blog/why-the-us-
government-is-mandating-software-bill-of-materials-sbom/
Fruhlinger, J. (2022, July 19). What is an SBOM? Software bill of materials explained. CSO
Online. https://www.csoonline.com/article/573185/what-is-an-sbom-software-bill-of-
materials-explained.html
NITA. (2021). The Minimum Elements For a Software Bill of Materials (SBOM) Pursuant to
Executive Order 14028 on Improving the Nation’s Cybersecurity.
https://www.ntia.doc.gov/files/ntia/publications/sbom_minimum_elements_report.pdf
Rangari, S. (2023, March 6). Why Are Regulations Demanding SBOM Adoption. ISACA.
https://www.isaca.org/resources/news-and-trends/industry-news/2023/why-are-
regulations-demanding-sbom-adoption
SolarWinds. (2016). IT Management Software & Monitoring Tools | SolarWinds.
Solarwinds.com. https://www.solarwinds.com/
Spiewak, R. (2023, July 18). CISA’s SBOM Minimums: Breaking Down the 6 Types. Cybellum.
https://cybellum.com/blog/6-sboms-breaking-down-cisas-new-sbom-minimums/
Synopsys. (n.d.). Which of CISA’s Six Types of SBOMs Are Right for You?
https://www.synopsys.com/content/dam/synopsys/sig-assets/guides/gd-sbom-types.pdf
Thryft, A. R. (2021, June 21). SolarWinds Fallout: Are SBOMs The Answer? EE Times.
https://www.eetimes.com/solarwinds-fallout-are-sboms-the-answer/
Toomey, M. (2023, March 21). SBOMs: 5 Major Challenges In Implementation.
Www.leanix.net. https://www.leanix.net/en/blog/5-major-sbom-challenges
Xia, B., Bi, T., Lu, Q., & Zhu, L. (2023). An Empirical Study on Software Bill of Materials:
Where We Stand and the Road Ahead.
Zetter, K. (2023, May 2). The Untold Story of the Boldest Supply-Chain Hack Ever. Wired.
https://www.wired.com/story/the-untold-story-of-solarwinds-the-boldest-supply-chain-
hack-ever/
