# FERPA Compliance Checklist

A comprehensive compliance checklist and implementation guide for educational institutions, EdTech vendors, and service providers that must comply with the Family Educational Rights and Privacy Act (FERPA). This resource covers student data privacy requirements, the school official exception, directory information policies, and practical steps for protecting education records.

Last Reviewed: March 2026

## Table of Contents

- [What Is FERPA?](#what-is-ferpa)
- [Who Must Comply with FERPA?](#who-must-comply-with-ferpa)
- [Key FERPA Requirements](#key-ferpa-requirements)
- [Education Records Defined](#education-records-defined)
- [The School Official Exception](#the-school-official-exception)
- [Directory Information](#directory-information)
- [FERPA and EdTech Vendors](#ferpa-and-edtech-vendors)
- [How FERPA Relates to NIST SP 800-53](#how-ferpa-relates-to-nist-sp-800-53)
- [FERPA vs. Other Privacy Laws](#ferpa-vs-other-privacy-laws)
- [Compliance Checklist Summary](#compliance-checklist-summary)
- [Common Pitfalls and How to Avoid Them](#common-pitfalls-and-how-to-avoid-them)
- [Frequently Asked Questions](#frequently-asked-questions)
- [About Petronella Technology Group](#about-petronella-technology-group)
- [Additional Resources](#additional-resources)

## What Is FERPA?

The Family Educational Rights and Privacy Act (FERPA), codified at 20 U.S.C. Section 1232g and its implementing regulations at 34 CFR Part 99, is a federal law that protects the privacy of student education records. Enacted in 1974 (also known as the Buckley Amendment), FERPA gives parents and eligible students (those aged 18 or older, or attending a postsecondary institution at any age) specific rights regarding their education records and places restrictions on how educational agencies and institutions may disclose those records.

FERPA applies to all educational agencies and institutions that receive funding from programs administered by the U.S. Department of Education. This includes virtually every public K-12 school district, public and private college, and university in the United States. The penalty for non-compliance is severe: the U.S. Department of Education can withdraw all federal funding from an institution found in violation of FERPA.

FERPA is administered and enforced by the Student Privacy Policy Office (SPPO) within the U.S. Department of Education. While FERPA does not provide a private right of action (meaning individuals cannot sue institutions directly for FERPA violations), the Department of Education investigates complaints and can impose sanctions.

In the modern educational technology landscape, FERPA compliance has become significantly more complex. The proliferation of cloud-based learning management systems, student information systems, educational apps, and AI-powered learning tools means that student data now flows through dozens or hundreds of third-party systems. Each of these data flows must be evaluated for FERPA compliance.

FERPA's requirements have taken on heightened importance as data breaches affecting educational institutions have increased dramatically. The K-12 Cybersecurity Resource Center tracked over 1,600 publicly disclosed cyber incidents affecting U.S. K-12 school districts between 2016 and 2024. Each of these incidents potentially involves the unauthorized disclosure of education records protected by FERPA.

## Who Must Comply with FERPA?

**K-12 public school districts** are the most common FERPA-covered entities. Every public school district in the United States receives federal funding and must comply with FERPA.

**Public colleges and universities** that receive any form of federal funding, including institutions where students receive federal financial aid (Pell Grants, Stafford Loans, etc.).

**Private colleges and universities** that participate in federal student financial aid programs. This includes virtually all accredited private institutions.

**State education agencies** that receive federal education funding, including state departments of education.

**EdTech vendors and service providers** that receive education records from covered institutions. While FERPA does not directly regulate vendors, institutions must ensure their vendor agreements meet FERPA requirements, and vendors are bound by contractual obligations regarding student data.

**Researchers** who receive education records for studies conducted on behalf of educational institutions. Research use is permitted under specific FERPA exceptions but requires strict data protection measures.

**Contractors and consultants** performing institutional functions that require access to education records, such as enrollment management firms, student success platforms, and financial aid servicers.

**Charter schools** that receive federal funding, either directly or through their authorizing district.

Note that private K-12 schools that do not receive any federal funding (directly or through their students) are not covered by FERPA. However, many states have enacted their own student privacy laws that apply to private schools.

## Key FERPA Requirements

FERPA establishes several core requirements that institutions must meet:

### Right of Access
Parents (for students under 18) and eligible students have the right to inspect and review their education records. Institutions must provide access within 45 days of receiving a request. Institutions may not charge for searching and retrieving records, though they may charge for copies.

### Right to Request Amendment
Parents and eligible students have the right to request that inaccurate or misleading records be amended. If the institution refuses, the parent or student has the right to a formal hearing. If the hearing upholds the institution's decision, the parent or student may place a statement in the record contesting the information.

### Right to Consent to Disclosure
Institutions must obtain written consent from the parent or eligible student before disclosing personally identifiable information (PII) from education records, except under specific exceptions outlined in the law. These exceptions include disclosures to school officials with legitimate educational interests, disclosures to other schools where the student seeks enrollment, disclosures in connection with financial aid, and disclosures to comply with a judicial order or subpoena.

### Right to File a Complaint
Parents and eligible students have the right to file a complaint with the U.S. Department of Education's Student Privacy Policy Office if they believe an institution has violated FERPA.

### Annual Notification
Institutions must annually notify parents and eligible students of their FERPA rights. This notification must include information about the right to inspect records, the right to request amendment, the right to consent to disclosure, and the right to file a complaint. Institutions must also notify parents and students of what they designate as directory information and provide an opt-out mechanism.

## Education Records Defined

Under FERPA, "education records" means records that are (1) directly related to a student and (2) maintained by an educational agency or institution, or by a party acting for the agency or institution. This definition is broad and includes:

**Records that ARE education records:**
- Grades, transcripts, and GPA
- Class schedules and enrollment information
- Student financial records (financial aid, billing)
- Disciplinary records
- Special education records (IEPs, 504 plans)
- Student email and electronic communications maintained by the institution
- Records in student information systems (SIS)
- Learning management system (LMS) data (submissions, grades, participation)
- Student photographs when maintained as part of student records
- Health records maintained by the school (not covered by HIPAA when maintained by a FERPA-covered institution)

**Records that are NOT education records:**
- Sole possession records (personal notes kept by a single staff member, not shared)
- Law enforcement unit records maintained solely by campus police
- Employment records (when the student is employed by the institution in a capacity not related to student status)
- Records made or maintained by a physician, psychiatrist, or psychologist for treatment purposes (treatment records)
- Alumni records (records created after the individual is no longer a student)
- Peer-graded papers before they are collected by a teacher

## The School Official Exception

The school official exception (34 CFR 99.31(a)(1)) is one of the most frequently used FERPA exceptions and is critical for institutions that work with EdTech vendors and third-party service providers. Under this exception, an institution may disclose education records without consent to "school officials" who have a "legitimate educational interest" in the records.

A school official can include:
- Teachers, professors, and instructors
- Administrators, supervisors, and support staff
- Board members
- Contractors, consultants, and volunteers performing institutional services or functions

For a third party (such as an EdTech vendor) to qualify as a "school official," the institution must ensure that the vendor:

1. **Performs an institutional service or function** for which the institution would otherwise use its own employees
2. **Is under the direct control of the institution** with respect to the use and maintenance of education records
3. **Uses education records only for the purposes specified** in its agreement with the institution
4. **Meets the criteria in the institution's annual FERPA notification** for who qualifies as a school official

This exception is the legal basis for most institutional use of EdTech platforms, cloud services, and student-facing applications. However, institutions must carefully document their use of this exception in vendor agreements.

## Directory Information

FERPA allows institutions to designate certain student information as "directory information" that may be disclosed without consent. Common directory information includes:

- Student name
- Address
- Telephone number
- Email address
- Date and place of birth
- Major field of study
- Dates of attendance
- Enrollment status (full-time, part-time)
- Degrees and awards received
- Most recent previous institution attended
- Participation in officially recognized activities and sports
- Weight and height of athletic team members
- Photograph

Institutions must:
1. Define what they consider directory information in their FERPA policy
2. Provide annual notification to parents/eligible students
3. Allow a reasonable period for parents/students to opt out of directory information disclosure
4. Honor opt-out requests

Schools should be cautious with directory information designations. Overly broad designations increase privacy risk. Many institutions now limit directory information to the minimum necessary for legitimate institutional purposes.

## FERPA and EdTech Vendors

The relationship between educational institutions and EdTech vendors is one of the most complex areas of FERPA compliance. As institutions adopt more technology platforms, the number of third parties with access to education records has grown exponentially.

**Key requirements for EdTech vendor agreements:**

1. The agreement must establish the vendor as a "school official" under FERPA
2. The agreement must specify the legitimate educational interest(s) the vendor serves
3. The vendor must agree to use education records only for the purposes specified
4. The vendor must be under the institution's direct control regarding use of records
5. The agreement must prohibit the vendor from re-disclosing records without authorization
6. The agreement should address data security requirements, breach notification, and data retention/destruction

**Data minimization.** Institutions should provide vendors with only the minimum education record data necessary to perform the contracted service. Vendors should not have access to records beyond what is needed for their function.

**Student consent for non-institutional purposes.** If a vendor wants to use student data for purposes beyond the institutional service (such as product improvement, marketing, or research), the institution cannot authorize this under the school official exception. Separate student consent is required.

**De-identified data.** FERPA allows the disclosure of de-identified data (data from which all personally identifiable information has been removed, and that is not reasonably identifiable). Institutions may share de-identified data without consent, but must apply reasonable de-identification methods and not release data that could be re-identified through combination with other available information.

## How FERPA Relates to NIST SP 800-53

FERPA itself does not prescribe specific technical security controls. The law requires institutions to use "reasonable methods" to ensure that school officials access only those education records in which they have a legitimate educational interest (34 CFR 99.31(a)(1)(ii)). The definition of "reasonable methods" is left to the institution's discretion, but the U.S. Department of Education has increasingly referenced NIST frameworks as the standard for what constitutes reasonable security.

The relationship between FERPA and NIST SP 800-53 is practical rather than regulatory:

**Access Control (AC family).** FERPA's requirement for institutions to use reasonable methods to control access to education records maps directly to NIST SP 800-53 Access Control controls. AC-2 (Account Management), AC-3 (Access Enforcement), AC-5 (Separation of Duties), and AC-6 (Least Privilege) are all directly relevant to FERPA's access requirements.

**Audit and Accountability (AU family).** FERPA requires institutions to maintain a record of each request for access to and each disclosure of education records. This maps to NIST SP 800-53 AU-2 (Event Logging), AU-3 (Content of Audit Records), AU-6 (Audit Record Review), and AU-11 (Audit Record Retention).

**Identification and Authentication (IA family).** FERPA's requirement to verify the identity of parties requesting access to education records maps to NIST SP 800-53 IA controls, particularly IA-2 (Identification and Authentication) and IA-5 (Authenticator Management).

**System and Communications Protection (SC family).** While FERPA does not mandate encryption, protecting education records in transit and at rest using controls from the SC family (SC-8 Transmission Confidentiality and Integrity, SC-28 Protection of Information at Rest) is considered a best practice for FERPA compliance.

**Incident Response (IR family).** While FERPA does not include a federal breach notification requirement, many states have enacted student data breach notification laws. NIST SP 800-53 IR controls (IR-1 through IR-8) provide a framework for incident response that satisfies both FERPA expectations and state breach notification requirements.

**Personnel Security (PS family).** FERPA's requirement that only authorized school officials access education records aligns with NIST SP 800-53 PS controls for personnel screening (PS-3), access agreements (PS-6), and personnel termination (PS-4).

Organizations that implement NIST SP 800-53 Moderate baseline controls will establish a security posture that substantially exceeds FERPA's minimum requirements and demonstrates the "reasonable methods" standard.

## FERPA vs. Other Privacy Laws

Understanding how FERPA interacts with other privacy laws is essential for educational institutions:

**FERPA vs. HIPAA.** When a school maintains health records as part of education records, those records are covered by FERPA, not HIPAA. The HIPAA Privacy Rule explicitly excludes education records covered by FERPA. However, a school-affiliated hospital or clinic that serves non-students may be covered by HIPAA for those records.

**FERPA vs. COPPA.** The Children's Online Privacy Protection Act (COPPA) applies to commercial websites and online services directed at children under 13. When a school directs students to use an online service, the school may consent on behalf of parents for the collection of student data, provided the data is used solely for school purposes.

**FERPA vs. State Student Privacy Laws.** Many states have enacted student privacy laws that go beyond FERPA. For example, California's Student Online Personal Information Protection Act (SOPIPA), New York Education Law 2-d, and Colorado's Student Data Transparency and Security Act impose additional requirements on EdTech vendors and institutions. Institutions must comply with both FERPA and applicable state laws.

**FERPA vs. CCPA/CPRA.** The California Consumer Privacy Act exempts information collected pursuant to FERPA. However, data about students collected by vendors for non-educational purposes may be subject to CCPA/CPRA.

**FERPA vs. GDPR.** For institutions with international students or programs, GDPR may apply in addition to FERPA when processing personal data of EU residents. GDPR's requirements are generally more stringent than FERPA, so compliance with GDPR will typically satisfy FERPA requirements.

## Compliance Checklist Summary

The detailed compliance checklist is available in [compliance-checklist.md](compliance-checklist.md). At a high level, FERPA compliance involves the following areas:

### Administrative Compliance
- Designate a FERPA compliance officer
- Develop and publish FERPA policies
- Issue annual FERPA notification to parents and eligible students
- Establish procedures for records access requests
- Establish procedures for amendment requests and hearings
- Train all staff with access to education records

### Technical Safeguards
- Implement role-based access controls for student information systems
- Enforce authentication requirements for all systems containing education records
- Enable audit logging for all access to and disclosure of education records
- Encrypt education records in transit and at rest
- Implement data loss prevention (DLP) controls
- Conduct regular security assessments of systems containing education records

### Vendor Management
- Inventory all vendors with access to education records
- Execute compliant agreements with all vendors (school official designation)
- Review vendor security practices and certifications
- Monitor vendor compliance on an ongoing basis
- Establish vendor data retention and destruction requirements
- Implement a process for vendor incident notification

### Incident Response
- Develop a breach response plan specific to education records
- Know your state's student data breach notification requirements
- Establish a process for notifying affected parents and students
- Document all incidents involving education records
- Report violations to the SPPO as appropriate

## Common Pitfalls and How to Avoid Them

**Shadow IT.** Teachers and staff often adopt technology tools without going through institutional procurement or IT review. Each of these tools may access education records without proper FERPA safeguards. Implement a technology vetting process and educate staff about the risks of unauthorized technology use.

**Oversharing via email.** Education records are frequently shared via unencrypted email, including grade reports, disciplinary information, and student health data. Implement email encryption and train staff to use secure methods for sharing student information.

**Inadequate vendor agreements.** Many institutions use vendors without formal agreements that address FERPA requirements. Every vendor with access to education records needs a compliant agreement in place before receiving data.

**Failure to honor opt-outs.** Institutions that designate directory information must provide an opt-out mechanism and honor opt-out requests consistently across all disclosures. Maintaining a central opt-out list and integrating it with all disclosure processes is essential.

**Confusing FERPA with HIPAA.** School nurses, counselors, and health staff sometimes apply HIPAA rules to student health records. In a FERPA-covered institution, student health records maintained by the school are education records governed by FERPA, not HIPAA. Training must clarify this distinction.

**Neglecting de-identification standards.** Institutions that share data for research or reporting must ensure proper de-identification. Simply removing names is not sufficient. Institutions must ensure that remaining data elements cannot be combined to re-identify students, particularly in small populations.

**Records retention confusion.** FERPA does not specify how long institutions must retain education records, but it does require that institutions maintain a record of disclosures for as long as the education records themselves are maintained. Many states have specific records retention requirements for student data.

## Frequently Asked Questions

**Q: Does FERPA apply to private K-12 schools?**
A: FERPA applies only to educational agencies and institutions that receive funding from programs administered by the U.S. Department of Education. Most private K-12 schools that do not receive direct federal funding and whose students do not receive federal financial aid are not covered. However, many states have separate student privacy laws that apply to private schools.

**Q: When do FERPA rights transfer from parents to students?**
A: FERPA rights transfer to the student when the student turns 18 or enrolls in a postsecondary institution at any age. At that point, the student becomes an "eligible student" and controls access to their education records. Parents of eligible students may still access records if the student is claimed as a dependent for tax purposes, but the student's consent is generally required.

**Q: Can a parent access their college student's grades without the student's consent?**
A: Generally, no. Once a student enrolls in a postsecondary institution, FERPA rights belong to the student. However, institutions may disclose education records to parents of dependent students (as defined by the IRS) without the student's consent, and they may notify parents of students under 21 regarding violations of alcohol or drug policies.

**Q: Does FERPA require encryption of student data?**
A: FERPA does not explicitly require encryption. However, encryption is widely considered part of the "reasonable methods" institutions must use to protect education records. State student privacy laws may impose specific encryption requirements.

**Q: How does FERPA handle subpoenas for student records?**
A: FERPA allows disclosure of education records in response to a lawfully issued subpoena or court order. The institution must make a reasonable effort to notify the parent or eligible student before complying, unless the court or issuing entity has ordered that the student not be notified.

**Q: Can teachers share student grades publicly (e.g., posting grades by student ID)?**
A: No. FERPA prohibits the public posting of grades in a personally identifiable manner. Posting grades by student ID number, Social Security number, or any other identifier that is linked or linkable to a specific student violates FERPA. Using randomly assigned codes known only to the student and instructor is permissible.

**Q: What happens if an institution violates FERPA?**
A: The U.S. Department of Education investigates FERPA complaints through the Student Privacy Policy Office. Remedies include requiring the institution to come into compliance, imposing conditions on future funding, and in extreme cases, withdrawing federal funding. There is no private right of action under FERPA; individuals cannot sue institutions for FERPA violations in federal court.

**Q: Does FERPA apply to student data in AI and machine learning systems?**
A: Yes. When AI systems process education records (for predictive analytics, adaptive learning, early warning systems, etc.), FERPA applies to that data. Institutions must ensure that AI vendors qualify as school officials, that data use is limited to educational purposes, and that automated decision-making is transparent and consistent with FERPA's access and amendment rights.

## About Petronella Technology Group

This checklist is maintained by **Craig Petronella** and the compliance team at **Petronella Technology Group, Inc. (PTG)**.

**Craig Petronella's credentials:**
- CMMC Registered Practitioner
- Licensed Digital Forensic Examiner #604180
- Cisco CCNA, CWNE
- MIT Artificial Intelligence Certificate
- Amazon #1 Best-Selling Author of 14+ cybersecurity books
- 23+ years in cybersecurity

PTG helps educational institutions and EdTech vendors implement robust student data privacy programs that meet FERPA requirements and exceed industry best practices. PTG uses its own private AI fleet, including on-premise LLMs and custom GPU infrastructure, to accelerate compliance assessments and automate security monitoring. PTG's patented technology stack provides the kind of enterprise-grade security that SMBs in the education sector need but often cannot access through traditional consulting firms. When a breach occurs, PTG's Licensed Digital Forensic Examiner can investigate, preserve evidence, and support legal proceedings.

**Contact PTG:**
- Phone: 919-348-4912
- Web: [https://petronellatech.com/compliance/ferpa/](https://petronellatech.com/compliance/ferpa/)
- Address: 5540 Centerview Dr. Suite 200, Raleigh, NC 27606

Call 919-348-4912 or visit [https://petronellatech.com/compliance/ferpa/](https://petronellatech.com/compliance/ferpa/) to schedule a free FERPA compliance assessment.

## Additional Resources

- [FERPA Statute (20 U.S.C. 1232g)](https://www.law.cornell.edu/uscode/text/20/1232g)
- [FERPA Regulations (34 CFR Part 99)](https://www.ecfr.gov/current/title-34/subtitle-A/part-99)
- [U.S. Department of Education Student Privacy Policy Office](https://studentprivacy.ed.gov/)
- [PTAC (Privacy Technical Assistance Center) Resources](https://studentprivacy.ed.gov/resources)
- [NIST SP 800-53 Rev. 5 Control Catalog](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [PTG Compliance Services](https://petronellatech.com/compliance/)
- [PTG HIPAA Compliance](https://petronellatech.com/hipaa/)
- [PTG NIST Compliance Hub](https://petronellatech.com/nist/)
- [PTG AI Services](https://petronellatech.com/ai/)
- [PTG Cybersecurity Services](https://petronellatech.com/cybersecurity/)
- [PTG Compliance Packages](https://petronellatech.com/compliance/packages/)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
