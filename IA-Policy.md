# Identification and authentication policy

See [CIO 2100.1L – GSA IT Security Policy](https://www.gsa.gov/cdnstatic/CIO_2100_1L_CHGE_1_CC040905_signed_PDF_version_7-15-2019.pdf) Chapter 5, _Policy on Technical Controls_, which covers:

* Access Control (AC)
* Audit and Accountability (AU)
* Identification and Authentication (IA)
* System and Communications Protection (SC)

The latest version can be found on the [GSA IT Security Policies](https://www.gsa.gov/about-us/organization/office-of-the-chief-information-officer/chief-information-security-officer-ciso/it-security-policies) page.

## Purpose

Balance restrictions designed to prevent unauthorized access against the need to provide unhindered access to informational assets.

## Scope

See the **_Applicability_** section of the GSA IT Security Policy.

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among organizational entities, compliance, reviews, and updates please see the [Technology Transformation Service's (TTS) Common Control Policy](https://github.com/cloud-gov/cg-compliance-docs/blob/master/TTS-Common-Control-Policy.md).

## Procedures

Identity and authentication in cloud.gov is entirely gated by cloud.gov's User Account and Authentication (UAA) Servers and their integration with GSA SecureAuth. Authentication to the underlying Amazon Web Service (AWS) is through the AWS Identity and Access Management (IAM).

For both UAA and IAM endpoints, user accounts are coupled to their federal government identities, represented by their personal identity verification (PIV) card, and all of the verification that process entails. UAA and IAM require multi-factor authentication (MFA) across the board. MFA devices are segmented between the two services, helping to ensure security through diversity. Further, cloud.gov adopts a "zero-trust" network posture - no networks are trusted, unless valid credentials (inclusive of MFA) are authenticated.

See IA-2, IA-2(1), IA-2(2), IA-2(3), IA-2(5), IA-2(8), IA-2(11), IA-2(12), IA-3, IA-4, IA-4(4), IA-5, IA-5(1), IA-5(2), IA-5(3), IA-5(4), IA-5(6), IA-5(7), IA-5(11), IA-6.

As a result of implementing easy integration with customer enterprise identity systems, cloud.gov helps agencies centrally manage identities and supports the use of PIV-card enabled systems, if applicable.

IA-8, IA-8(1), IA-8(2), IA-8(3), IA-8(4).
