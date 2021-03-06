September 21, 2018

|The official seal of the Department of Veterans Affairs.|

    **Office of Information and Technology, Enterprise Program
    Management Office, Transition, Release & Support, Health Product
    Support
     **

**
**

Introduction to the VA Monograph
--------------------------------

    This U.S. Department of Veterans Affairs (VA) Monograph provides an
    overview of the Veterans Health Information Systems and Technology
    Architecture (VistA) and non-VistA applications used by the Veterans
    Health Administration (VHA) in serving America’s veterans. The
    collection serves as an introduction and resource to VHA software.

    Each application entry in the monograph contains the VA Module Name,
    Version, Namespace, Business Function Framework Line(s) of Business
    and Functions(s), Business Owner, and mapping and linkage to `VA
    Systems Inventory
    (VASI) <http://vaww.ea.oit.va.gov/enterprise-architecture/va-systems-inventory/>`__
    and `VistA Documentation Library
    (VDL) <https://www.va.gov/vdl/section.asp?secid=2>`__.

VistA Development Historical Overview
-------------------------------------

 

Providing a development and historical overview of VistA, VistA had its
origins in the collaboration of VA clinicians and programmers, who
capitalized on emerging technology capabilities to create a
better-informed way to serve Veterans. Clinical and Information
Technology (IT) specialists working at various VA medical facilities
deployed locally developed computer applications to enhance patient care
with a focus on clinician needs. The software platform that resulted was
unique because it represented a combination of modules developed by a
distributed team and was a precursor to the distributed “open source”
development style popular today.

VistA applications are written in Massachusetts General Hospital Utility
Multi-Programming System (MUMPS), the language more recently known as
“M”, which remains prevalent in the health care arena and is the
backbone of other well-known Electronic Health (EHR)’s. The decision to
rely on MUMPS made it possible for local development teams to integrate
diverse applications, leading to the forerunner of VistA, previously
known as the Decentralized Hospital Computer Program (DHCP), in 1982.
DHCP grew rapidly and was implemented by many private and public
healthcare facilities throughout the U.S. and the world.

In 1996, the Chief Information Office introduced VistA. VistA
incorporates all the benefits of DHCP as well as including the rich
array of other information resources that are becoming vital to the
day-to-day operations at VA medical facilities. It represents the
culmination of DHCP's evolution and metamorphosis into a new, open
system, client-server based environment that takes full advantage of
commercial solutions, including those provided by Internet technologies

VistA is built on a client-server architecture, which ties together
workstations and personal computers with graphical user interfaces at
Veterans Health Administration (VHA) facilities, as well as software
developed by local medical facility staff. VistA also includes the links
that allow commercial off-the-shelf software and products to be used
with existing and future technologies. The Decision Support System (DSS)
and other national databases that might be derived from locally
generated data lie outside the scope of VistA.

This also included the development and deployment of Computerized
Patient Record System (CPRS). CPRS is a VistA computer application. CPRS
enables you to enter, review, and continuously update all the
information connected with any patient. With CPRS, you can order lab
tests, medications, diets, radiology tests and procedures, record a
patient’s allergies or adverse reactions to medications, request and
track consults, enter progress notes, diagnoses, and treatments for each
encounter, and enter discharge summaries. In addition, CPRS supports
clinical decision-making and enables you to review and analyze patient
data. CPRS was designed to run in both the Microsoft Windows operating
environment and on text-based terminals. This rich, automated
environment supports day-to-day operations at local Department of
Veterans Affairs (VA) health care facilities.

VistA has been widely recognized as a premier, tightly integrated
computerized physician order entry system. VistA represents the joint
achievement of thousands of clinicians and professional systems experts.

As the implementation of Electronic Health Records (EHR) increases, VHA
can claim to have pioneered many aspects of the enterprise-wide
discipline. VistA’s patient-centric focus embodies the clinical workflow
processes that support VA’s models of care, and VistA has led to
measurable improvements in patient health.

Why a VA Monograph? 
--------------------

The purpose of the VA Monograph is to present a brief and user-friendly
overview of the VistA applications. It also provides additional
resources for technical information and identifies the VA offices that
maintain the Monograph.

 

Where can I find the VA Monograph? 
-----------------------------------

The VA Monograph is available at the following VA website:
http://www.va.gov/vista_monograph/

What is VistA?
--------------

VistA is a comprehensive, full-featured Health Information System and
Electronic Health Record. The software must be properly configured at
each healthcare setting by individuals knowledgeable about the software
before the system is used to support healthcare delivery. VistA does not
self-install.

VistA supports a large variety of clinical settings. Facilities range
from small clinics that provide solely outpatient care to large medical
centers with significant inpatient populations and their associated
specialties. The VistA applications focus on clinically relevant record
keeping that improves patient care by improving clinical and
administrative decision making.

VistA is deployed across VHA at more than 1,500 sites of care, including
each Veterans Affairs Medical Center (VAMC), Community Based Outpatient
Clinics (CBOC) and Community Living Centers (CLC), as well as at nearly
300 VA Vet Centers. VistA serves America’s Veterans by supporting
exceptional-quality health care.

VistA Brief Technical Overview
------------------------------

 

VistA is an integrated Electronic Health Record system with applications
that share a common data store and common internal services. The data
store is a built-in database native to the M language.

The Kernel software component of VistA acts as the middle-man between
the operating system and the applications, making VistA portable to
different operating systems. VistA integrates its own applications with
each other as well as with non-VistA systems. It uses application
programming interfaces (APIs), remote procedure calls (RPCs), and Health
Level 7 (HL7) messaging to communicate with commercial off-the-shelf
software, selected information technology systems of other federal
agencies, and health information exchange networks.

VistA encompasses many distinct applications, thousands of routines, and
millions of lines of computer code.

Where is VistA used within VHA?
-------------------------------

VistA is deployed universally across VHA at more than 1,500 care sites,
including each Veterans Affairs Medical Center (VAMC), Community Based
Outpatient Clinic (CBOC), Community Living Center (CLC), and nearly 300
VA Vet Centers.

 

How do I request changes to VistA?
----------------------------------

    VHA customers can propose enhancements to VistA through the
    `Requirements Development &
    Management <https://vaww.vashare.vha.va.gov/sites/RDM/SitePages/Home.aspx>`__
    (RDM) `New Service Request Database
    (NSRD) <https://vaww.vashare.vha.va.gov/sites/RDM/Pages/NewServiceRequests.aspx>`__
    portal.

I am not in VHA; may I obtain VistA for my use?
-----------------------------------------------

VistA software applications can be obtained through the Freedom of
Information Act (FOIA). FOIA requests should be directed to:

Department of Veterans Affairs

FOIA Services (10P2C1) 810 Vermont Avenue, NW

Washington, DC 20420

Electronic requests can be sent to VACOFOIASERVICE@VA.GOV

VA is committed to the Open Source community and was instrumental in
establishing the Open Source Electronic Health Record Agent (OSEHRA) and
has contributed VistA code to the OSEHRA effort.

VistA is a comprehensive, full-featured Health Information System (HIS)
and EHR. The software must be properly installed and configured for each
healthcare setting by individuals knowledgeable about the software
before the system can support healthcare delivery.

How do I recommend changes to or ask questions about the VA Monograph? 
-----------------------------------------------------------------------

Comments and suggestions for changes to the VA Monograph are welcomed
and should be forwarded via email to the OIT EPMO Product Support
Monograph mail group:

OITPDProductSupportMonograph@va.gov

The VistA Modules
-----------------

The Monographs, arranged alphabetically, describe each VistA software
application. Examples of heavily used core modules are
Admission/Discharge/Transfer, Clinic Scheduling, Laboratory, Pharmacy,
and Radiology. There are approximately 200 VistA modules, including
applications designed for more specific uses, such as QA monitoring,
Registries, and Methicillin-Resistant Staphylococcus Aureus (MRSA)
tracking.

Monograph template format includes:

-  **VistA Module -** the name of the module being described.

-  **Version -** provides the number of the most recent version (i.e.,
   major release or significant re-release) of the module being
   described.

-  **Namespace -** a shorthand abbreviation for VA-specific nomenclature
   used to rapidly identify the programming domain for the module being
   described.

-  **Business Function Framework Line(s) of Business** and **Function(s)
   -** the Business Function Framework (BFF) is a hierarchical
   decomposition of the business functions maintained by VHA’s Business
   Architecture team. Inclusion of these elements here allows for a
   “line of sight” connection between VHA business functions and the
   VistA modules supporting their execution.

-  **Business Owner -** refers to the office or organization within VHA
   with primary business responsibility for the module, this information
   changes over time and can be checked real-time by using the VASI link
   provided.

-  **VASI ID** and **VASI ID link -** The VASI ID is the unique ID
   assigned to a system and the VASI ID is a direct link to that entry
   which contains information in addition to information contained
   within this Monograph.

-  **VDL link -** The VDL link will take you to the VDL folder that
   contains all documentation on nationally released products.

-  

   1. .. rubric:: Accounts Receivable
         :name: accounts-receivable

**Version**: 4.5

**Namespace:** PRCA

**Brief Description:** The Accounts Receivable (AR) package is a system
of accounting and receivables management. The AR package automates the
debt collection process and a billing module is available to create
statements for non-medical care debts. Functionality is available to
establish, follow-up on, collect against and track all medical facility
debts.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Provide Financial
Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO Revenue Operations

**VASI ID:** 1777

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123314/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=55

**Full Description and Features:** Some of the debts owed to a VA
facility may include patient care covered by health insurance companies,
veteran co-payments, pharmacy prescription co-payments, employee salary
overpayments, lost or damaged property, vendor collectibles, benefit
overpayments, and services provided under a sharing agreement with
another institution.

-  Provides a generic billing system used to generate standardized bills

-  Receives patient and third party billing information passed
   automatically from the Integrated Billing (IB) package

-  Sends electronic transmissions to the Consolidated Copayment
   Processing Center (CCPC) in Austin, TX to generate patient statements

-  Automatically processes first party payments received from the
   Lockbox Bank

-  Calculates interest and administrative charges

-  Records, processes, and tracks payment information from patients,
   vendors, insurance companies, employees, and institutions

-  Records and tracks credit balances if debtors have overpaid their
   accounts, and processes refunds as appropriate

-  Updates Financial Management System (FMS) with Accounts Receivable
   data

-  Tracks and forwards eligible delinquent patient, vendor, and employee
   debts to the Treasury Program for offset

-  Tracks delinquent debts for Regional Counsel and Department of
   Justice for enforced collection

-  Provides the ability to set up repayment plans

-  Provides reports and inquiries for the follow-up and maintenance of
   outstanding receivables

-  Provides for transmission of certain AR bills over 90 days old to be
   referred to the Debt Management Center (DMC) for collection action

-  Automatically processes electronic payments and explanation of
   benefits documents received from third party insurance carriers
   through the Electronic Data Interchange (EDI) Lockbox bank

-  Allows modifications to locate 3rd Party claims with Electronic
   Explanation of Benefit (EEOB’s)

-  Provides corrections to the printed EDI Lockbox reports

-  Provides corrections to the Daily Activity Report and the Claims
   Matching report

-  Allows VistA to receive, process and display data from Finacial
   Service Center (FSC) in HIPAA 5010 compatible format

-  Provides a change in revenue reconciliation from deposits to comply
   with the Treasury mandate to accept new deposit numbers from the
   Treasury contracted bank

-  Provides modification to the Third Party Joint Inquiry option to
   allow up to 10 characters of an inactive claim number to display

-  Modifies the Full Account Profile option to allow up to 10 characters
   of an inactive claim number to display

-  Creates the processes to support the receipt, storage and display of
   Medical deductible information from Trailblazer Health Care
   Enterprise

-  Creates a new option called Medicare Deductible Alert Worklist from
   which users can view Medicare deductible information

-  Provides modifications to AR routines to accommodate a longer 12
   digit Electronic Claims Management Engine (ECME) number

-  Provides modifications to the EDI Lockbox menu to allow VistA to
   receive, process and display ERA, Electronic Fund Transfter (EFT) and
   EEOB data from FSC in HIPPA 5010 compatible format

-  Provides automation of the current ePayments processes to improve
   productivity of Accounts Receivable staff and increase accuracy of
   the revenue operation with these changes including Auto-Posting

-  Modifies the EDI Lockbox Parameters option to allow maintenance of
   new parameter values for the new automatic processing and posting
   prevention functionality

-  Creates a new option called EDI Lockbox Parameter Report which
   displays the parameter settings

-  Creates a new option called EDI Lockbox Exclusion Audit Report which
   reports changes made to the excluded payer parameters

-  Creates a new option called EDI Lockbox Parameters Audit Report which
   reports chances made to other parameters.

-  Modifies the EDI Lockbox Reports Menu to include new ad-hoc reports
   of Auto-posting and Auto-decrease activit

-  Modifies the EDI Lockbox menu to include a new Auto-posting Awaiting
   Resolution option which allows for claim lines rejected by the
   nightly Auto-posting process to be reviewed and resubmitted for
   Auto-posting

-  Creates a new option called Unposted EFT Override which allows user
   with the new RCDPE AGED PMT security key to override posting
   prevention in the ERA Worklist.

-  Modification to the 90-day DMC debt referral process

-  TOPS modification exclude first party bills from the TOP process
   unless the date the bill became active is prior to the Activation
   Date. Do not exclude bills from the TOP process that are identified
   as referred to TOP

-  Monthly Patient Statements - Bills Referred to Cross-Servicing will
   exclude the value of bills that have been referred to Cross-Servicing
   from the 'Previous Balance' and 'Balance' block on the monthly
   patient statement

-  Monthly Patient Statements- Bills Not Referred to Cross-Servicing
   will include the value of bills in the 'Previous Balance' and
   'Balance' block on the monthly patient statement when a bill is no
   longer referred to Cross-Servicing

-  Bulletin will be generated by VistA when there is eligible debt for
   Cross-Servicing and a third collection letter has not been sent. The
   bulletin will contain the debtor's name and bill number(s)

-  Updates estimated copayment amount displayed within AR's Payment
   Processing to reflect correct amount

-  Ensures Tier Rate decreases do not flag non Tier Rate charges as
   duplicate

-  Modifies purging criteria for the weekly TCSP batch run

-  Modifies purging criteria for the weekly TOP batch run

-  Modifies TOP bills foreign address handling

-  Updated the Revenue Source Code Report option (PRCA FMS RSC REPORT)
   to properly display the new revenue

-  Updates to the Deposit Reconciliation Report option (PRCA DEPOSIT
   RECON REPORT) to include the new fund

-  Updates to the Bad Debt Report option (PRCA NR BAD DEBT ACCR REPORT)
   to include the new fund

-  Modified the display to correct reject descriptions on Bill Profile
   screens

-  Updates to the Calculate Revenue Source Code For a Bill option (PRCA
   FMS RSC CALCULATE) to include the new source codes

-  Corrects the Write-Off/Contract Adjustment (WR) document data when
   being sent to Financial Management Systems (FMS)

-  A new option, TCSP Flag Control [RCDP TCSP FLAG CONTROL], was created
   to correct debtor/bill for Treasury

-  Cross Service as seen when viewing the same debtor/bill on the
   Treasury System or from the monthly TCSP reconciliation report

-  A new security key, RCDP TCSP FLAG, was created to allow users to
   edit the TCSP flag on Debtor and/or Bill. This Security Key, RCDP
   TCSP FLAG, should ONLY be allocated by CPAC IT and given ONLY to
   Veteran Services Supervisors and/or Veteran Services Leads (One, Two
   or Three)

-  Modifications made to the TCSP weekly batch run to bypass any debtors
   that are not defined correctly in the AR DEBTOR (#340) file

-  Modifications made to remove the inactive email address
   'OGCNASRI@MAIL.VA.GOV^OGCRegion8DeathNotification@mail.va.gov' from
   the routines

-  Modifications made to the TCSP weekly batch run to ensure that the
   correct country, state and zip code are set when a veteran address is
   outside the United States

-  A new report option ARDC Monthly Reconciliation [PRCA ARDC MONTHLY
   REPORT] was added to both the AR - Accounts Receivable Menu [PRCAT
   USER] and the Reconciliation Reports [PRCAD RECONCILE MENU] menus

-  The collection of historical ARDC data will be retained for the
   current month and two prior months only. Then it will be
   automatically purged once the next AR accounting month starts
   processing

-  Improves revenue operation functionality related to repayment plans,
   late charge capture, bill suspension reasons, the billing of
   deactivated providers, and the display of appeal rights and
   responsibilities on the Veterans Beneficiary Travel Bill of
   Collections form

-  Repaired the Excel output of the Claims Matching Report and fixed
   device handling issues.

-  Provides the infrastructure foundation for electronic exchange of
   claim payment information and promotes an interoperable system

-  Reduces the time elapsed between receipt of the EDI 835 Electronic
   Remittance Advice Transaction and receipt of the Cash Concentration
   or Disbursement transactions

-  Ensures that trace numbers between payments and remittances can be
   used by VA, reducing the level of open accounts receivable, allow
   claim denials to be more quickly addressed, and standardizes
   Electronic Funds Transfer (EFT) & ERA enrollment to reduce workload
   burden on VA staff

-  Increases timely and accurate processing of payments for electronic
   claims in compliance with Health Insurance Portability and
   Accountability Act

-  Repairs made to the 5B record in the Cross-Servicing file that
   reports veteran debt to the Treasury Cross Servicing Program

-  Repairs made to the Reconciliation Report - Cross-Servicing [RCTCSP
   RECONCIL REPORT] and to the Enter/Edit Re-payment Plan option [PRCAC
   ENTER EDIT REPAYMENT]

-  Corrects some reported out-of-balance discrepancy issues

-  The old columns "AMOUNT PAID" and AMOUNT OF FEES" on the
   Reconciliation Re-port - Cross-Servicing [RCTCSP RECONCIL RE-PORT]
   were inaccurate

-  The header modified for the Recall Date in the Microsoft Excel output
   of the Reconciliation Report

-  The heading was changed from SSN to PT ID. Leading zeroes of the SSN
   were lost in the Excel output of the Reconciliation Report. Corrects
   the handler control variable IOP was being misused in the
   Reconciliation Report

-  Corrects the Enter/Edit Repayment Plan [PRCAC ENTER EDIT REPAYMENT]

-  New Cross-Servicing transaction types were also added into the
   monthly AR Data Collection (ARDC) and FMS transmission processes so
   that the new transaction types which have dollar amounts are included

-  Adds notifications for changes to auto-post, auto-decrease, payer,
   and CARC site parameters

-  Adds the ability to see who manually marked an ERA for auto-post in
   the Auto-Posted Receipt Report, Receipt Profile, List of Receipts
   Report, and Transaction Profile

-  Adds 'matched date’ to the ERA Worklist and Daily Activity Report

-  Adds a unique EFT identifier to the following reports: Daily Activity
   Report, EFT Unmatched Report, Unapplied EFT Report, EFT Audit Report,
   and Manual Match Report

-  Adds display of ‘Percent Collected on Claims’ to the ‘Claim Level Pay
   Status’ section of the EP Report (ERA/835 Action)

-  Updates display language in the Link Payment Report and adds ability
   to filter by receipt number on Link Payment Report

-  Allows user to generate Auto-Post Report by payer TIN

-  Restricts unbalanced ERAs to be auto-post candidates

-  Renames the Payer Exclusion Report to the Payer Implementation Report

-  Modified the 'Distribute Adj Amts' action on the ERA Worklist to
   allow for negative distributions to claim lines which do not have a
   valid claim

-  Adds FMS Document Status to bill/claim profile screens and reports

-  Provides fix to Pharmacy Data Exception Filter on the 3rd Party
   Exceptions Worklist Scratch Pad

-  Provides fix to error in the ERA Worklist Manual Match Action

-  Adds an ERA Partial Post Indicator

-  Rewrites auto-posting logic to determine if the ERA is actually
   matched to an EFT

-  Changes prompt wording of Worklist Delete

-  Removes auto-decrease limit and adds new maximum parameter

-  Adds the ability to auto-decrease zero or no-pays

-  Adds the ability to view all ERA verify lines information on EEOBs

-  Adds the capability to filter all 3rd Party EDI Lockbox reports and
   options by Tricare/ChampVA

-  Adds fee claims to Auto-Audit (5287.13) Rate type = Fee

-  Allows AM Clerk access to the Admin Cost Adjustment option

-  Fixes duplicate EFT deposits in the Audit Report

-  Adds Administrative Cost Adjustment option to allow adjustment to
   balance and for it to be recognized

   1. .. rubric:: 
         Admission, Discharge, Transfer (ADT)/Registration
         :name: admission-discharge-transfer-adtregistration

**Version**: 5.3

**Namespace:** DG

**Brief Description:** The Admission, Discharge, Transfer (ADT) module
provides a comprehensive range of software dedicated to the support of
administrative functions related to patient admission, discharge,
transfer, and registration. The functions of this package apply
throughout a patient's inpatient and/or outpatient stay, from
registration, eligibility determination and Means Testing through
discharge with on-line transmission of Patient Treatment File (PTF) data
to the Austin Information Technology Center (AITC).

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Provide Health Care

**Business Function Framework Function(s):** Provide Member Access,
Perform Hospital Administration, Utilize Information Services

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Community Care (OCC) - Member Services

**VASI ID:** 1778

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123315/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=55

**Full Description and Features:** The ADT software also aids in
recovery of cost of care by supplying comprehensive PTF and Means Test
software. The ADT module functions as the focal collection point of
patient information, encompassing demographic, employment, insurance,
and medical history data. Many other modules, such as Laboratory,
Pharmacy, Radiology, Nursing, and Dietetics, utilize information
gathered through the various ADT options. Several features have been
designed to maximize efficiency and maintain control over user access of
specified sensitive patient records. The Patient Sensitivity function
allows a level of security to be assigned to certain records within the
database (i.e., records of employees, government officials, etc.) in
order to maintain control over unauthorized user access. The Patient
Lookup function screens user access of these records. It also provides
for efficient and faster retrieval of patient records and identified
potential duplicate patient entries. The ADT module allows for efficient
and accurate collection, maintenance, and output of patient data, thus
enhancing a health care facility’s ability to provide quality care to
its patients. The functions within ADT currently fall into five major
categories: Application Processing (registration), Bed Control
(inpatient movements), Inpatient Care Grouping (DRG), Data Transmission
to National Database (PTF), Supervisor Functions (system setup and
maintenance), and Local/National Management Reporting.

-  Provides on-line patient registration and disposition of applications
   for medical care

-  Tracks patient movements during inpatient stays

-  Provides up-to-date on-line patient information

-  Generates numerous managerial and statistical reports

-  Performs patient data consistency checks

-  Supports the flagging and monitoring of patient/missing patient
   records deemed to be sensitive

-  Enrolls patients in the VA Patient Enrollment System during the
   registration process.

-  Uses industry standard International Classification of Diseases
   (ICD)/Current Procedural Terminology (CPT) codes

-  Aids in cost recovery of care by supplying comprehensive PTF, Means
   Test, and pharmacy co-pay software

-  Allows support for newborn claims

-  Assignment of a patient to Veteran Transportation Services in VistA
   scheduling service

-  Veterans Health Identification Card (VHIC)

-  Elimination of the annual financial means test

-  ICD-10 code compliant

-  Fugitive Felon Program Public Law 107-103 section 505 compliant,
   which prohibits federal agencies from providing certain benefits to
   persons who are fugitive felons

-  Military Sexual Trauma (MST) compliant with the VHA Directive in
   providing appropriate care and counseling to veterans determined to
   have been a victim of sexual trauma while the veteran was serving on
   active duty

   1. .. rubric:: 
         Fugitive Felon Program
         :name: fugitive-felon-program

**Version**: 1.0

**Namespace:** DGFFP

**Brief Description:** The Fugitive Felon functionality in VistA and via
the Health Eligibility Center (HEC) is designed to identify veterans who
are fugitive felons receiving VA medical care.

**Business Function Framework Line(s) of Business:** Provide Access to
Healthcare, Provide Health Care Administration, Manage Business Enabling
Services

**Business Function Framework Function(s):** Provide Member Access,
Perform Hospital Administration, Manage VHA-wide Administration Services

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Chief Business Office

**VASI ID:** 1291

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122947/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=150

**Full Description and Features:** Public Law (PL) 107-103, Section 505,
prohibits provision of certain benefits to veterans or their dependents
that are classified as fugitive felons. This law requires VA to provide
current address information, upon written request, to any Federal,
State, or local law enforcement official, if s/he: provides information
required to fully identify the person, identifies the person as being a
fugitive felon, or certifies that apprehending such person is within the
official duties of such official. This project software provides the
following functionality for VHA implementation: adds several fields to
the VistA Patient File to store the Fugitive Felon Flag and track when
the flag was entered and removed, creates a new security key to control
access to the Fugitive Felon Flag and the associated menu options,
provides menu options that allow users to set and clear the Fugitive
Felon Flag, and to print the various reports associated with the new
fields, and displays user alert from Scheduling and Registration
options.

-  VistA Changes

-  Security Controls

-  Functionality

-  Reports

-  Issues

   1. .. rubric:: Anticoagulation Management Tool
         :name: anticoagulation-management-tool

**Version**: 1.0

**Namespace:** OR

**Brief Description:** The Anticoagulation Management Tool (AMT) was
developed at the Portland VA Medical Center to help simplify the
complex, time consuming processes required to manage patients on
anticoagulation medication. The tool enables the user to enter, review,
and continuously update all information connected with patient
anticoagulation management.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Deliver Health Care

**Business Function Framework Function(s):** Provide Member Access,
Provide Medical Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=188

**Full Description and Features:** With the Anticoagulation Management
Tool (AMT), one can order lab tests, enter outside lab results and
graphically review lab data, enter notes, complete encounter data,
complete the consults if consults are used to initiate entry into the
Anticoagulation clinic, and print a variety of patient letters. Upon
exiting, all activities within the program are recorded on an
Anticoagulation flow sheet maintained on the Computerized Patient Record
System (CPRS) Reports tab. AMT provides clinic staff a mechanism of
ensuring continuous patient monitoring with a built-in mechanism that
alerts staff when patients have not been monitored in a timely period. A
"Lost to Follow-up" list is maintained to ensure that staff knows of
patients who need attention.

Automated Information Collection System (AICS)
----------------------------------------------

**Version**: 3.0

**Namespace:** IBD

**Brief Description:** The Automated Information Collection System
(AICS) software supports outpatient clinical efforts through the
creation and printing of encounter forms that display relevant clinical
information, and provides for the entry of clinical encounter data for
local and national needs.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Ancillary Services,
Manage Health Records

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Public Health

**VASI ID:** 1780

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123317/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=30

**Full Description and Features:** The AICS encounter forms are used to
display relevant patient data for use during the appointment (e.g.,
demographics, allergies, clinical reminders, and problems) and to
collect data about the appointment (e.g., procedures, providers, and
diagnoses), thus providing an organized method of data collection
through scanning or data entry. Many of the lists that a user sees in
Computerized Patient Record System (CPRS) for input of outpatient
encounter data are based on lists created when designing encounter forms
for clinics.A form generator is included, which allows sites to design
forms that meet local medical facility needs. There is enough
flexibility in the software so sites can build forms that meet their
individual clinical, billing, and resource requirements. The encounter
form may be filed in the clinical record. A print manager is included
that allows sites to define reports to print in conjunction with the
encounter form and any supplemental forms for each appointment. Reports
can be defined to print at the division, clinic group, or clinic level.
Utilities are available to manage when and where forms may print.Data
from encounter forms can be input into VistA in one of two ways. Forms
can be scanned on client workstations with the data automatically
transmitted to the VistA server, or clerks can key in data from forms.

Provides a form design utility that allows creation of attractive and
easy to use forms for each clinic

-  Allows forms to be designed to print with patient data displayed,
   such as patient demographics, insurance information, allergies, and
   clinical reminders that are due and active problems

-  Allows for the creation of forms to collect data such as procedures,
   diagnoses, problems, providers, progress notes, vital signs, and
   Patient Care Encounter (PCE)-related data such as exams, health
   factors, patient education, skin tests, and immunizations

-  Provides a print manager that allows all clinic-specific forms to
   print with the encounter form for an appointment. The print manager
   also provides a setup system that, once accomplished, no longer
   requires daily user intervention

-  Provides an import/export utility that makes it easier for sites to
   exchange forms they have already created

-  Provides forms tracking to ensure that each form printed is processed
   or accounted for.

-  Manual data entry options are available to allow data to be key
   entered by a clerk and passed to PCE to be stored

-  Updated in June, 2014 to support ICD-10 functionality

-  Updated in January 2015. APIs called to retrieve encounter form
   information for CPRS were optimized and streamlined to improve timely
   displays and performance

-  Updated in December 2015. DD change for Type of Visit File: A request
   was made to update the SHORT NAME (#.015) field in the TYPE OF VISIT
   (#357.69) file. This field is computed using a pointer to the SHORT
   NAME (#2) field in the CPT (#81) file; a field that was removed by
   patch ICPT\*6.0\*46. This patch redefined the computed expression
   used in the SHORT NAME (#.015) field to use an API to populate the
   SHORT NAME data. The value of the SHORT NAME (#.015) computed
   expression was changed to use the CPT^ICPTCOD API which will populate
   the correct SHORT NAME data.

   1. .. rubric:: 
         Automated Medical Information Exchange (AMIE)
         :name: automated-medical-information-exchange-amie

**Version**: 2.7

**Namespace:** DVBA

**Brief Description:** The Automated Medical Information Exchange (AMIE)
module facilitates the electronic interchange of veteran information
between Veteran Benefits Administration (VBA) Regional Offices (ROs) and
VA medical facilities.

**Business Function Framework Line(s) of Business:** N/A

**Business Function Framework Function(s):** N/A

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1031

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122709/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=31

**Full Description and Features:** This comprehensive module provides an
accurate audit trail to track most requests for information. The module
is composed of two components: Facility administrative options
(7131/7132) and VBA Regional Office options (2507 Compensation and
Pension). Each area has individual items to maintain daily, and its own
reports to print. RO staff access VA medical facility computers through
VA national telecommunications network, and exercise their options on
each local medical facility’s system as necessary.

-  Provides access to local databases for identification of a veteran’s
   admission, discharge, outpatient treatment, patient care, and other
   information that may require adjudicative actions

-  Reduces overpayments previously caused by lost, misrouted, or
   improperly processed admission notifications

-  Provides on-line status determinations of pending compensation and
   pension examinations (requesting, scheduling, tracking, and updating
   results)

-  Provides RO on-line access to the local databases for the
   confirmation of the propriety of payments based on hospitalization

-  Improves timeliness of the RO benefits adjustment processing

-  Allows medical centers to electronically access sections of the
   Physicians Guide for Disability Evaluation Examinations

-  Provides tracking of insufficiently completed compensation and
   pension examinations

   1. .. rubric:: 
         Bed Management Solution (BMS)
         :name: bed-management-solution-bms

**Version**: 2.3

**Namespace:** WEBB

**Brief Description:** The Bed Management Solution (BMS) project
addresses the Department of Veterans Affairs (VA) need to optimize the
flow of patients from admission through discharge, and to improve
patients’ safety, quality of care, and customer satisfaction. BMS
provides the capability to manage bed availability at the facility, VISN
and national levels and provides national data for bed availability
during a disaster.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Provide Access to Health Care, Provide Health Care Administration

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Systems Redesign

**VASI ID:** 1052

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123501/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=205

**Full Description and Features:** Bed Management Solution (BMS)
provides real-time, user friendly, web-based VistA interface to track
patient movements and determine bed availability. It provides
performance information that can be used to measure and improve patient
flow as it occurs within and between VAMCs. BMS enhances safety, quality
of care, patient/staff satisfaction and improves patient flow for
process and outcome improvements. BMS, the automated Bed Management
Solution, allows administrative and clinical staff to record, manage and
report on the planning, patient-movement, patient occupancy, and other
activities related to management of beds. All patient admission,
discharge, and transfer movements are pulled directly from VistA to BMS
resulting in minimal manual data entry.

-  Track current and pending bed availability and patient movement
   through the system

-  Plan, prepare, and manage patient flow; identify and anticipate peak
   demands facilitation of Real- Time Demand and Capacity Management

-  Reduce non-VA care ("fee basis") days and associated costs

-  Display bed occupancy status for all beds in the facility (VAMC)
   and/or VISN

-  Provide visibility of bed availability within all VAMCs for emergency
   management purposes

-  Automate request and assignment of beds

-  Reduce cycle times for bed cleaning and readiness

-  Display and facilitate timely discharge appointments; anticipate and
   track patient discharges

-  Provide links for entry and retrieval of Bed Management events

-  Provide links for access and updating Bed Management Data, with
   respect to processes and retrieval of data that is not in any other
   system

-  Store patient, operational, and transaction data, as needed to
   support and report on bed management, throughput events and cycle
   time data

-  Provide the ability for utilization in a multidivisional, integrated
   site environment with the ability to produce multi-site reports

-  Facilitate efficient flow operations at multiple levels and provides
   reports on the performance of bed management activities, thus
   enabling VAMCs and VISNs to track key performance indicators and to
   impact performance on Deputy Under Secretary for Health (DUSH)
   monitors and guidelines

   1. .. rubric:: 
         Blind Rehabilitation
         :name: blind-rehabilitation

**Version**: 5.1

**Namespace:** ANRV

**Brief Description:** The Blind Rehabilitation Service program consists
of the following four elements: VA Headquarters, Blind Rehab Centers
(BRC), Visual Impairment Service Teams (VIST), and Blind Rehabilitation
Outpatient Specialists (BROS).

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Care Management, Provide Ancillary Services, Manage
Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Rehabilitation and Prosthetic Services

**VASI ID:** 1064

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122723/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=164

**Full Description and Features:** The Blind Rehabilitation application
provides enhanced tracking and reporting of the blind rehabilitation
services provided to veterans by:

-  Visual Impairment Service Teams (VIST) Coordinators

-  Blind Rehabilitation Centers (BRCs)

-  Blind Rehabilitation Outpatient Specialists (BROS)

-  Visual Impairment Services Outpatient Rehabilitation (VISOR) Programs

-  Visual Impairment Center to Optimize Remaining Sight (VICTORS)

In addition to providing the base functionality of the BR 4.0 system, BR
5.1 provides a web-enabled GUI through which users can access enhanced
capabilities intended for VIST Coordinators, new functionality for BROS,
BRC personnel and waiting times and waiting list.The Blind
Rehabilitation 5.1 application provides entirely new functionality that
encompasses and integrates all five segments of the Blind Rehabilitation
Services including waiting times and waiting list.

-  Complies with VistA Architecture

-  Complies with 508 regulations, using W3C standards

-  Accessible web based application, via a web browser

-  Supports the OI Single Sign-on initiative

-  User authentication via role based permissions

-  User friendly

-  Seamless continuum of care

-  Minimum user disruption

-  Simplified data entry

-  Better identification and treatment of veterans

-  Consolidates data

-  Enables system driven waiting times and waiting list tracking and
   reporting capabilities

-  Enables users to receive comprehensive views of a patient’s BR
   Services across institutions

-  Facilitates data tracking and auditing capabilities

-  Improves accountability

-  Enhanced reporting features

-  Provides Data Standardization which improves and provides
   consolidated data reporting

-  Improved blind services tracking

-  Enables Research and Provides Outcomes tracking and reporting
   capabilities

-  Improves VHA organizational communication

-  Transmits to the Health Data Repository (HDR)

   1. .. rubric:: 
         Clinical Case Registries (CCR)
         :name: clinical-case-registries-ccr

**Version**: 1.5

**Namespace:** ROR

**Brief Description:** The Clinical Case Registries (CCR) application
obtains demographic and clinical data on VHA patients with specific
clinical conditions. CCR is designed to search and provide reports on
patient data in multiple registries. This aides clinical staff in
supporting a variety of clinical conditions or disease states in VHA
patients.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** VHA Population Health Services

**VASI ID:** 1113

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122821/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=126

**Full Description and Features:** CCR uses a pre-defined set of
selection rules to identify patients with registry-specific conditions,
such as a disease-related ICD-9/ICD-10 code or a positive result on an
antibody test. The CCR package then adds these patients to the
appropriate local registry in a pending state. Pending patients are
reviewed by the registry coordinator at the VAMC and if the data
confirms the diagnosis, the registry coordinator confirms the patient
for that registry.

CCR reporting accesses VistA files that contain clinical data on the
registry patient including additional diagnoses, prescriptions, surgical
procedures, laboratory tests, radiology exams, patient demographics,
hospital admissions, and clinical visits. This access allows identified
clinical staff to take advantage of the wealth of data supported through
VistA when managing specific patient populations in a single focused
application.

Data from the registries can be used for both clinical and
administrative reporting. Each facility can produce local reports
containing information related to patients treated in their system.

Two national registries are also included in CCR. They will be discussed
separately.

-  Automates the development of a local list of patients with a specific
   condition

-  Automatically transmits patient data from the local registry to a
   national database

-  Provides robust reporting functions

-  Facilitates the tracking of patient outcomes relative to treatment

-  Identifies and tracks important trends in treatment response, adverse
   events, and time on therapy

-  Monitors quality of care using both process and patient outcome
   measures

   1. .. rubric:: 
         Hepatitis C (HepC)
         :name: hepatitis-c-hepc

**Version**: 1.5

**Namespace:** ROR

**Brief Description:** The Hepatitis C Case Registry contains important
demographic and clinical data on VA patients identified with Hepatitis C
infection.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** VHA Population Health Services

**VASI ID:** 1327

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122886/c/56/nt/-1?id=1578

**VDL Link:**
https://www.va.gov/vdl/documents/Clinical/Lab-Emerging_Pathogens_Initiative/lab_epi_hepc_tech_user_guide.pdf

**Full Description and Features:** This registry is specifically written
for patients who have Hepatitis C ICD-9 or ICD-10 codes entered as
diagnostic codes in VistA. Patients are also identified by having a
positive result to specific Hepatitis C laboratory tests.

The registry extracts VistA data across various applications like
pharmacy, laboratory, demographic, radiology, etc.. On a nightly basis
the data is extracted and transmitted to a national database in Austin.
Data from the Hepatitis C Case Registry is used on a national, regional,
and local level to track and optimize clinical care of Hepatitis C
infected veterans served by VA. National summary information (without
personal identifiers) will be available to VA Central Office for overall
program management, as well as to inform Veterans Service Organizations,
Congress, and other federal public health and health care agencies.

-  Automatically develops a list of patients with Hepatitis C infection

-  Provides a Graphical User Interface (GUI) interface that allows
   select local facility staff to add to and/or edit the list

-  Identifies patients who are receiving investigational class drugs for
   Hepatitis C

-  Transmits patient data to a national database, including patient
   demographic information, the reason(s) patients were added to the
   registry, pharmacy utilization information, radiology testresults,
   and a limited set of laboratory test results

**Generates the following local reports:**

-  A report that lists the patients currently on the registry. Users can
   filter this report to display a subset of patients based on the date
   range they were added to the registry

-  A report that lists patients who have received Hepatitis C therapy
   within a user-selected date range

-  A report that displays local software activity and error report
   information

**Technical improvements include:**

-  Automatic nightly updates to the national registry list

-  Use of a uniform M (formerly MUMPS) program backbone that can be used
   for other disease case registries

-  The transformation of VistA data into standard Health Level Seven
   (HL7) formatted messages for transmission, including limited
   validation checks, error messaging, etc.

   1. .. rubric:: 
         Human Immunodeficiency Virus (HIV)
         :name: human-immunodeficiency-virus-hiv

**Version**: 1.5

**Namespace:** ROR

**Brief Description:** The Human Immunodeficiency Virus (HIV) Case
Registry contains important demographic and clinical data on VHA
patients identified with HIV infection.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** VHA Population Health Services

**VASI ID:** NA

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** Clinical Case Registries-HIV is the
second specifically created registry which is designed to search for
patients in the VistA database who have had specific diagnostic codes
(ICD-9 or ICD-10) entered in the VistA database. In addition to the
diagnostic codes, patents can be added to the registry if they have a
positive result specific HIV lab tests.

The CCR-HIV application also accesses several other VistA files that
contain information regarding diagnoses, prescriptions, surgical
procedures, laboratory tests, radiology exams, patient demographics,
hospital admissions, and clinical visits. This access allows identified
clinical staff to take advantage of the wealth of data supported through
VistA.

The key capabilities provided by the CCR:HIV to VA facilities that
provide care and treatment to patients with HIV infection include the
clinical categorization of patients, generation of the Center for
Disease Control (CDC) case report form, clinical reports, and automatic
transmission of data to the Corporate Data Center Operations (CDCO).
Data from the CCR:HIV are used on the national, regional, and local
level to track and optimize clinical care of HIV infected veterans
served by VA. The capabilities of the CCR software has been further
enhanced by the automation of the data collection system. The current
version, referred to as CCR: HIV, is a clinically relevant tool for
patient management.

-  Improved graphical user interface (GUI)

-  Robust reporting capability, using both process and patient outcome
   measures, that allows for tailored local level reporting and
   divisional level reporting to help monitor the quality of patient
   care

-  Ability to export report data to spreadsheet applications

-  Tracking of patient outcomes related to antiretroviral drug treatment

-  Partial automation of HIV case identification

-  Identifies and tracks important trends in treatment response, adverse
   events, and time on therapy

-  Matches resources to clinical needs and utilization at local, VISN,
   and national levels

-  Verifies workload for VERA reimbursement

-  Automates notification to HIV coordinators that data was sent to and
   received by the national database

-  Automates extraction of data to the national registry

   1. .. rubric:: 
         Traumatic Brain Injury Registry (TBI)
         :name: traumatic-brain-injury-registry-tbi

**Version**: 2.0

**Namespace:** TBI

**Brief Description:** Traumatic Brain Injury (TBI) Registry allows
identification and tracking of Veterans who sustained head injuries
during active duty.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** VHA

**VASI ID:** 1630

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123076/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Veterans Health Administration
(VHA) is charged with supporting the Presidential Task Force on
Returning Global War on Terror Heroes. The Task Force has stated in the
Global War on Terror (GWOT) report (recommendation P-7) that the
Department of Veterans Affairs (VA) shall “create a ‘Traumatic Brain
Injury’ Surveillance Center and Registry to monitor returning service
members who have possibly sustained head injury and thus may potentially
have a traumatic brain injury in order to provide early medical
intervention.”

The Traumatic Brain Injury (TBI) Registry software applications collect
data on the population of Veterans who participated in Operation
Enduring Freedom/Operation Iraqi Freedom (OEF/OIF). These individuals
need to be seen within 30 days for a comprehensive evaluation. Each
facility can produce local reports (information related to patients
evaluated and treated in their system).

The TBI Instruments are a set of comprehensive evaluation questionnaires
(initial and follow up) designed to provide rehabilitation professionals
with a vehicle by which they can assess patients and collect patient
information. The information collected from these instruments is
electronically transferred and stored in the form of a medical progress
note in the patient’s electronic record. This progress note can be
retrieved through the Computerized Patient Record System (CPRS).

The set of TBI Instruments include the Comprehensive TBI Evaluation, TBI
Follow-Up Assessment, The Mayo-Portland Adaptability Inventory (MPAI),
and the Rehabilitation and Reintegration Plan.

-  Allows capture of injury centric patient information for analysis and
   targeted treatment.

-  Participation assessment with Recombined Tools

-  Mayo-Portland Adaptability Inventory

-  JFK Coma Recovery Scale

-  Oswestry Low Back Pain Disability Questionnaire

-  Timed Up and Go

-  Generalized Anxiety Disorder Scale

-  Post-Traumatic Stress Disorder Checklist

-  Patient Health Questionnaire

-  Supervision Rating Scale

-  Insomnia Severity Index

-  Pain Outcomes Questionnaire for Intake, Discharge, and Follow-up

-  World Health Organization Disability Assessment Schedule

   1. .. rubric:: 
         Clinical Information Support System (CISS)
         :name: clinical-information-support-system-ciss

**Version**: 1.0

**Namespace:** CISS

**Brief Description:** The Clinical Information Support System (CISS) is
a web-based portal application that provides a framework of services for
the VA enterprise and supplies an integration point for its partner
systems. The initial CISS partner system is the Occupational Health
Record-keeping System (OHRS), a web-based application that enables
occupational health staff to create, maintain, and monitor medical
records for VA employees and generate national, VISN, and site-specific
reports.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Occupational Health

**VASI ID:** 1904

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123477/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=185

**Full Description and Features:** The focus of OHRS is to collect
clinical data for wellness, medical surveillance, and appropriate
treatment of work-based injury or illness. OHRS will capture and store
information on patient encounters, such as encounter type, purpose,
status, provider, and other pertinent clinical data obtained during the
patient visit. Users with appropriate security privileges are allowed to
add and sign or co-sign the encounter and if needed, and perform
scheduled and unscheduled reporting on items such as vaccination rates,
vaccination and immunity statuses.

The OHRS application does not share patient-specific data, but will
collect data elements limited to information deemed critical to the
Occupational Health delivery of care processes in the OHRS database.
Employee data is obtained from the central Personnel and Accounting
Integrated Data System (PAID) while volunteer information is obtained
from the Voluntary Service System (VSS). Other Non-Paid and non-VSS data
is collected by direct data entry into OHRS at the time of the patient
encounter.

The CISS Portal hosts one of its premier partner systems, Occupational
Health Record-keeping Systems (OHRS), and has been available for use by
VHA field clinicians and clinical support staff involved with employee
health and safety since September 2009.

Other candidate legacy applications that are planned for modernization
to further leverage the CISS portal are:

-  Automated Safety Incident Surveillance and Tracking System (ASISTS)

-  Workers Compensation/Occupational Safety and Health Management
   Information System (WC/OSH MIS (WC/OSH-MIS)

   1. .. rubric:: 
         Clinical Monitoring System
         :name: clinical-monitoring-system

**Version**: 1.0

**Namespace:** QAM

**Brief Description:** The heart of the Clinical Monitoring System
package is in building monitors using conditions and groups for patient
auto enrollment. The main function of this software is to capture data
for patients meeting specified conditions. All monitors within the
framework of this software are ultimately based upon patient data.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1785

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123321/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=32

**Full Description and Features:** To capture data, monitors are created
to run nightly. The monitors capture data elements such as ward,
treating specialty, SSN, age, etc. The data elements available for
capture vary depending on the conditions selected when building
monitors. The conditions are provided within the Clinical Monitoring
System package. Some conditions require a group be defined, such as a
group of wards, drug classes, MAS movement types, etc. Monitors are
easily created through menu options and can be queued to run manually or
nightly.

-  Provides the user with the ability to design a monitor that will auto
   enroll cases that meet the user's defined criteria/conditions from
   VistA

-  Allows the user to set time frames for computing percentages and
   tracking findings between time frames

-  Has the ability to alert users when important thresholds or dates are
   met

-  Provides a mechanism to add site-developed conditions and data
   elements and routines such as site-designed worksheets to the
   software. MUMPS programming is a required part of site-specific
   enhancement

-  Provides mechanisms for controlling the disk space and CPU time
   resources used by the Clinical Monitoring System

-  Allows the user to manually enter cases

   1. .. rubric:: 
         Clinical Procedures
         :name: clinical-procedures

**Version**: 1.0

**Namespace:** MD

**Brief Description:** Clinical Procedures (CP) passes final patient
results, using Health Level 7 (HL7) messaging, between vendor clinical
information systems (CIS) and VistA. Patients’ test results or reports
are displayed through the Computerized Patient Record System (CPRS).

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1787

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123323/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=139

**Full Description and Features:** Clinical Procedures (CP) passes final
patient results, using Health Level 7 (HL7) messaging, between vendor
clinical information systems (CIS) and VistA. Patients’ test results or
reports are displayed through the Computerized Patient Record System
(CPRS). The report data is stored on the Imaging Redundant Array of
Independent Disks (RAID) and, in some instances; discrete data is stored
in the Medicine package generated by medical devices. There are no
specific procedures tracked through this application, nor are management
workload reports generated. Links to DSS and other databases through PCE
are supported through CP works with the Consult/Request Tracking, Text
Integration Utility (TIU), CPRS, Patient Care Encounter (PCE), and VistA
Imaging packages. In conjunction with CPRS, CP also provides a method
for clinicians to document findings and to complete final procedure
reports via existing pathways in appropriate VistA applications. The CP
functionality is not available in the List Manager (LM) version of CPRS.
CP provides features that can be used across clinical specialties such
as Medicine, Women's Health, Surgery, Dental, Rehabilitation Medicine,
and Neurology. Its functionality supports clinical practice in all
patient care settings including clinics, Home Based Primary Care (HBPC),
and in-patient units.

-  Allows clinicians to enter, review, interpret, and sign CP orders
   through one application, CPRS

-  Accepts a variety of file types for result report files

-  Allows images to be acquired, processed, stored, transmitted, and
   displayed by the VistA Imaging package

-  Defines the Hospital Location where the procedure is performed. This
   location determines which Encounter Form is presented to the end user

-  Allows electronic transfer of patient reports from medical devices to
   VistA

-  Provides Bi-directional interface capabilities

-  Provides easy to use user interfaces, including CP Console, CP User,
   CP Hemodialysis, CP Flowsheets and CP Gateway

-  Affords improved internal communication between the procedural list
   and the primary care physician

-  Improve patient education through use of reports

-  Improves medical record keeping

MD\*1.0\*16 patch release provides:

-  Interface for collection of patient observational data from
   monitoring devices

-  Standardized terminology with VA Unique Identifiers (VUIDs)

-  GUI, locally-customizable flow sheets to view, enter and edit patient
   data

-  Admission Discharge and Transfer (ADT) Health Level 7 (HL7) message
   feed

-  Publication of data to CPRS (CliO service architecture and Text
   Integration Utilities notes)

-  User-friendly Clinical Procedures Console, configurable by user

-  ICD-10 code compliant

   1. .. rubric:: 
         Compensation and Pension Record Interchange (CAPRI)
         :name: compensation-and-pension-record-interchange-capri

**Version**: 2.7

**Namespace:** DVBA

**Brief Description:** Compensation and Pension Record Interchange
(CAPRI) is an information technology initiative to improve service to
disabled veterans by promoting efficient communications between the
Veterans Health Administration (VHA) and Veterans Benefits
Administration (VBA).

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Member Access,
Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** ​VHA Office of Disability and OIT Medical Assessment
and VBA Compensation

**VASI ID:** 1130

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122840/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=133

**Full Description and Features:** Online access to medical data
enhances the timeliness of the benefits determination. The CAPRI
software acts as a bridge between the VBA and VHA information systems.
It offers VBA Rating Veteran Service Representatives and Decision Review
Officers help in building the rating decision documentation through
online access to medical data. It offers VHA Compensation & Pension
(C&P) staff an easy, standardized way of reporting C&P Examination
results.

Using CAPRI, VBA employees have a standardized, user-friendly method to
rapidly access veterans' electronic medical records throughout the VA.
Initially developed specifically for VBA, the utility of CAPRI has been
expanded to other user groups that include VHA, Office of the Medical
Inspector, OI, Research, Veteran Service Officers, and others. One of
the primary features of CAPRI is the Compensation and Pension Worksheet
Module (CPWM) which is used by VHA C&P providers and staff. CPWM
provides clinical users access to exam templates and tools that are used
to document C&P examinations.

-  Demographics

-  Ability to save template work in progress and finish later

-  Load new patients into VistA system

-  View patient demographics

-  Report patient address changes to VHA

-  C&P Examination Functionality

-  Add/Edit C&P exam request

-  Create an insufficient exam request

-  Individual and cumulative pending exam tracking

-  Request VAF 7131 information

-  VA Regional Office reports

-  Automatic Mailman bulletins to AMIE mail groups

-  Automatic sending of completed exam Requests

-  Ability for site to review exams before releasing it to VBA

-  Multiple templates can be merged into a single a single exam

-  Patient Records Navigation

-  View health summaries

-  View appointment lists

-  View progress notes

-  View discharge summaries

-  View consult requests and results

-  View cumulative vital

-  View active medications.

-  View lab reports

-  View imaging

-  View procedures

-  View FHIE/DoD data, if available

   1. .. rubric:: 
         Consolidated Mail Output Pharmacy (CMOP)
         :name: consolidated-mail-output-pharmacy-cmop

**Version**: 2.0

**Namespace:** PSX

**Brief Description:** The Consolidated Mail Outpatient Pharmacy (CMOP)
package provides a regional system resource to expedite the distribution
of mail-out prescriptions to veteran patients.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Access to
Self-Services, Provide Clinical Decision Support, Provide Ancillary
Services, Utilize Information Technology Services, Provide Enterprise
Reporting

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Patient Care Services

**VASI ID:** 1788

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123324/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=85

**Full Description and Features:** CMOP host facilities, regionally
located, receive data from medical centers within the area of service.
Current CMOPs are designed to handle the dispensing and mailing of
between 20,000 and 40,000 prescriptions in an 8-hour workday.

-  Patients submit medication requests via telephone, mail, or in person
   at each medical facility. When necessary, pharmacy personnel enter
   the orders into the patient database

-  Each area CMOP host facility establishes a schedule for the
   electronic transmission of the prescription data

-  Prescriptions are transmitted electronically from the medical
   facility to the automated prescription dispensing equipment, checked
   by a pharmacist, mailed to the patient, and information on the
   prescription filled is returned to update the medical center database

-  The process is highly integrated with the Outpatient Pharmacy
   software and requires no additional processing by pharmacy personnel
   responsible for entering the prescription

-  All prescriptions are automatically screened by the CMOP software and
   set for transmission if appropriate

   1. .. rubric:: 
         Computerized Patient Record System (CPRS)
         :name: computerized-patient-record-system-cprs

      1. .. rubric:: Adverse Reaction Tracking (ART)
            :name: adverse-reaction-tracking-art

**Version**: 4.0

**Namespace:** GMRA

**Brief Description:** The Adverse Reaction Tracking (ART) program
provides a common and consistent data structure for adverse reaction
data. This module has options for data entry and validation, supported
references for use by external software modules, and the ability to
report adverse drug reaction data to the Food and Drug Administration
(FDA).

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Managing Business Enabling Services

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Manage Health Records, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Pharmacy Benefits Management (PBM)

**VASI ID:** 1779

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123316/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=57

**Full Description and Features:** The Adverse Reaction Tracking (ART)
program provides a common and consistent data structure for adverse
reaction data. This module has options for data entry and validation,
supported references for use by external software modules, and the
ability to report adverse drug reaction data to the Food and Drug
Administration (FDA).

Combined with Remote Data Interoperability (RDI), it includes remote
allergy data when determining drug-allergy order checks.

-  Documents patient allergy and adverse drug reaction data

-  Provides the functionality for other VistA modules to extract and add
   patient reaction data

-  Provides a reporting mechanism that supports VHA Directive 10-92-070
   which specifies reporting of adverse drug reactions to the FDA

-  Includes ART event points in an Application Programmers Interface
   (API) allowing other VistA packages to know when specific ART events
   take place so package tasks can be performed

-  Alerts the Pharmacy and Therapeutics Committee each time the
   signs/symptoms are modified for a patient reaction

-  Generates progress notes. Displays all information at the time of an
   ART event on the Progress Notes API and allows editing of the note
   prior to sign off

-  Allows the site to track whether the patient has been asked if he/she
   has allergies

-  Electronic health record is automatically updated with allergy or
   adverse drug reaction as soon as they are entered

-  Tracks when the patient ID bands have been marked indicating a
   particular reaction.

-  Differentiates between historical and observed reaction

-  Tracks the particular signs/symptoms for a reaction.

-  Allows for configuration of allergy files

-  Allows for editing and verification of reaction data

-  Allows for the addition of comments for each reaction to ensure
   completeness in reporting

-  Contains extensive reporting capabilities

-  Contains an online reference guide

   1. .. rubric:: 
         Authorization/Subscription (ASU)
         :name: authorizationsubscription-asu

**Version**: 1.0

**Namespace:** USR

**Brief Description:** The Authorization/Subscription Utility (ASU)
provides a method for identifying who is authorized to perform various
actions on clinical documents. These actions include signing, co-signing
and amending.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Managing Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services, Conduct Supply Chain
Operations, Manage Fixed Assets

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA HIM

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=58

**Full Description and Features:** The Authorization/Subscription
Utility (ASU) implements a User Class Hierarchy which is useful for
identifying the roles that different users fulfill with the hospital. It
also provides tools for creating business rules that apply to documents
used by members of such groups. ASU provides a method for identifying
who is AUTHORIZED to do something (for example, sign, co-sign or amend).
ASU originated in response to a long-recognized demand for a means of
implementing the "Scope of Practice" model, but the driving force behind
its development was the complexity of Text Integration Utilities' (TIUs)
document definition needs. Current security key capabilities were unable
to efficiently manage the needs of clinical documentation (Discharge
Summaries, Progress Notes, Operation Reports, etc.).

-  Defines, populates, and retrieves information about user classes.
   User classes can be defined hospital-wide or more narrowly for a
   specific service ans can be used across VistA to replace and/or
   complement keys

-  Allows linkage of user classes with Document Definitions and document
   events

-  Allows sites to maintain membership of users in User Classes and to
   distribute such maintenance tasks.

-  Membership in classes may be schedule for automatic transition to
   other classes.

-  Lists class members as active or inactive

-  Allows infinite hierarchies of subclasses

   1. .. rubric:: 
         Clinical Reminders
         :name: clinical-reminders

**Version**: 2.0

**Namespace:** PXRM

**Brief Description:** Clinical Reminders may be used for both clinical
and administrative purposes. However, the primary goal is to provide
relevant information to providers at the point of care, for improving
care for veterans. The package benefits clinicians by providing
pertinent data for clinical decision-making, reducing duplicate
documenting activities, assisting in targeting patients with particular
diagnoses and procedures or site-defined criteria, and assisting in
compliance with VHA performance measures and with Health Promotion and
Disease Prevention guidelines.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Care Management, Provide Medical Services, Manage
Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA HI/CMIO

**VASI ID:** 1183

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122774/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=60

**Full Description and Features:** Version 2 of Clinical Reminders
contains many enhancements to improve processing and management of
reminders. Performance has been enhanced through the creation of an
index of all clinical data used in reminder findings. All enhancements
are intended to help the Reminders functionality smoothly transition to
CPRS reengineering.

-  Inform clinicians when a patient is due to receive clinical activity

-  Target the clinicians who can manage and resolve the clinical
   activity most appropriately

-  Identify patients to whom a reminder applies, based on VistA patient
   data

-  Identify the clinical activities that resolve or satisfy reminders

-  Summarize pertinent patient information to help clinicians determine
   appropriate follow-up activities

-  Allow clinicians to resolve reminders through CPRS

-  Provide aggregate reports that assist clinicians in managing their
   entire patient caseload

-  Support national clinical practice guidelines

-  ICD-10 code compliant

   1. .. rubric:: 
         Consult/Request Tracking
         :name: consultrequest-tracking

**Version**: 3.0

**Namespace:** GMRC

**Brief Description:** The Consult/Request Tracking package provides an
efficient way for clinicians to order consultations andprocedures from
other providers or services within the VHA system, at their own facility
or another facility. It also provides a framework for tracking consults
and procedures and reporting the results. It uses a patient's
computerized patient record to store information about consult and
procedure requests and results.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Medical Services Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Patient Care Systems

**VASI ID:** 1789

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123325/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=62

**Full Description and Features:** Consult Request Tracking package
interfaces with the Computerized Patient Record System (CPRS) to provide
an efficient mechanism for clinicians to order consults and procedure
requests. It provides the consulting services with the ability to update
and track the progress of a consult/procedure request from the point of
receipt through its final resolution. It also provides results reporting
that include's doctor's progress notes and comments entered during the
tracking process.

-  Allows direct access to Consults functions through menu options in
   CPRS

-  Uses Consults' own menu options for managing the system, generating
   reports, tracking consults, or entering results for an existing
   consult request

-  Allows staff to set up consults as CPRS Quick Orders, streamlining
   the ordering process

-  Integrates with Prosthetics to track Home Oxygen, Eyeglasses, Contact
   Lenses, and other Prosthetic services

-  Produces a permanent record of the request and resolution for
   patient's medical record

-  Allows all relevant parties to see the consult report in the context
   of the patient's record

-  Allows use of TIU templates and boilerplates to report findings

-  Allows display of Consult reports through TIU and CPRS

-  Enables clinicians to order an inter-facility consult to another VA
   Healthcare System

-  ICD-10 code compliant

-  Clinically Indicated Date is provided for consults that need to be in
   the future

-  Allows HL7 communication between the consult system and the
   Healthcare Claims Processing System (HPCS)

   1. .. rubric:: 
         Group Notes
         :name: group-notes

**Version**: 1.0

**Namespace:** OR

**Brief Description:** This program was designed to assist providers in
documenting group therapy sessions and events such as immunization
clinics.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Patient Care Services

**VASI ID:** 1306

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122959/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=142

**Full Description and Features:** Group Notes allows the easy assembly
of patient groups based on Clinics, Specialties, Wards, Teams, or
Provider lists. It then allows the note author to specify parts of a
note that apply to the entire group and parts that apply to individuals.
It does the same with encounter data. After the note and encounter
information is complete, it provides for a single signature for the
entire group.

Health Summary
--------------

**Version**: 2.7

**Namespace:** GMTS

**Brief Description:** A Health Summary is a clinically oriented and
structured report that extracts many kinds of data from VistA and and
displays it in a defined and standard format.

**Business Function Framework Line(s) of Business:** Deliver Healthcare

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Patient Care Services

**VASI ID:** 1800

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123334/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=63

**Full Description and Features:** Health summaries can be printed or
displayed for individual patients or for groups of patients. The data
displayed covers a wide range of health related information such as
demographic data, allergies, current active medical problems, laboratory
results, progress notes, clinical reminder data, visits, pharmacy data,
radiological data, surgeries and more. Health summaries can be viewed
through CPRS GUI or through VistA menu options.

Health Summary integrates data from the following packages:

-  Admission Discharge Transfer (ADT)/Registration

-  Clinical Procedures/Medicine

-  Compensation Pension Records Interchange (CAPRI)/Automated Medical
   Information Exchange (AMIE)

-  Adverse Reaction Tracking (ART)

-  Clinical Reminders

-  Consults/Request Tracking

-  Problem List

-  Text Integration Utility (TIU)

-  Laboratory

-  Mental Health

-  Nursing

-  Nutrition and Food Service (NFS)

-  Patient Care Encounter (PCE)

-  Pharmacy: Bar Code Medication Administration (BCMA)

-  Pharmacy: Inpatient Medications

-  Pharmacy: Outpatient Pharmacy

-  Radiology

-  Scheduling

-  Social Work

-  Spinal Cord Dysfunction

-  Surgery

-  VistA Imaging System

-  Allows users to print an Outpatient Pharmacy Action Profile with bar
   codes in tandem with a health summary

-  Exports components that allow staff to view remote patient data
   through CPRS. Additionally, remote clinical data can be viewed using
   any Health Summary Type that has an identically named Health Summary
   Type installed at both the local and remote sites

-  Clinical Reminders work with Health Summary to furnish providers with
   timely information about their patient's health maintenance schedules

-  Health Summary components "Progress Notes" and "Selected Progress
   Notes" will display interdisciplinary progress notes and all of the
   entries associated with the interdisciplinary notes

   1. .. rubric:: 
         Problem List
         :name: problem-list

**Version**: 2.0

**Namespace:** GMPL

**Brief Description:** The Problem List application is used to document
and track a patient’s problems. It provides the clinician with a current
and historical view of patient's health care problems, and allows each
identified problem to be traced in terms of treatment, test results, and
outcome.

**Business Function Framework Line(s) of Business:** Deliver Healthcare

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Patient Care Systems

**VASI ID:** 1494

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123066/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=64

**Full Description and Features:** This application supports care
givers, such as physicians, nurses, social workers, and others, in
inpatient and outpatient settings. It is also designed to be used by
medical and coding clerks. A variety of different data entry methods are
possible with this application. Use of Problem List varies from site to
site, depending on the data entry method a facility has chosen. Sites
use Encounter Forms which are generated from patient data in the system
and added to or modified by clinicians. Problem list can be linked to
other sections of the medical record, such as CPRS and Health Summary.
The application supports import of problem information from other
clinical settings outside the immediate medical facility.

-  Allows one problem list for a given patient

-  Requires minimal data entry

-  Linked to other sections of the medical record, such as CPRS and
   Health Summary

-  Supports display of problem information from other clinical settings
   outside the immediate VAMC, i.e., DOD and Remote Data

-  Supports a variety of data entry methods: direct clinician entries,
   clerk entry, encounter forms

-  Uses a common language of terminology, the Lexicon Utility. Each term
   is well-defined and understandable. A user, site, or application may
   substitute a preferred synonym

-  Allows reformulation of a problem

-  Can be interfaced with a customized encounter form

-  Accommodates the user of the Systematic Nomenclature of Medicine -
   Clinical Terms (SNOMED CT) for selection of Patient Problems

-  Works with Standard Data Service (SDS) to implement SNOMED CT on both
   the Enterprise Terminal Server and the Clinical Lexicon, using the
   New Term Rapid Turnaround (NTRT) strategy for vetting and deployment
   of novel clinical expressions

-  Problem List display and print option render the diagnostic codes as
   either ICD-9-CM or ICD-10-CM, depending upon the date when the code
   for the problem was last edited

   1. .. rubric:: 
         Text Integration Utilities (TIU)
         :name: text-integration-utilities-tiu

**Version**: 1.0

**Namespace:** TIU

**Brief Description:** Text Integration Utilities (TIU) simplifies the
use and management of clinical documents for both clinical and
administrative medical facility personnel. Along with
Authorization/Subscription Utility (ASU), a facility can set up policies
and practices for determining who is responsible or has the privilege
for performing various actions on required documents.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Patient Care Systems

**VASI ID:** 1159

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122753/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=65

**Full Description and Features:** TIU interfaces with the Computerized
Patient Record System (CPRS) and allows the user to utilize the template
utilities in the GUI version of CPRS to allow users speedy
point-and-click composition of notes, consults, and summaries. Templates
can be set up for specific types of documents for specific clinical
needs. The application also interfaces with Problem List, Automated
Information Capture System (AICS), Patient Care Encounter (PCE),
Authorization/Subscription Utility (ASU), Incomplete Record Tracking
(IRT), Health Summary (HS), Clinical Procedures (CP), VistA Imaging
(MAG), Clinical Reminders and Visit Tracking. TIU uses standardized and
common user interface, which allows clinicians and other to retrieve
many kinds of documents from a single source.

TIU allows users to link TIU documents to all types of clinical images
such as X-rays, MRIs and CAT scans. The package permits document input
from a variety of data capture methodologies such as transcription,
direct entry through CPRS or the TIU package, voice recognition
software, or upload of ASCII formatted documents into VistA.

TIU follows HL7 interface and other communication standards.

-  Interfaces with the Computerized Patient Record System (CPRS)
   template utilities in the GUI version of CPRS allowing speedy
   point-and-click composition of notes, consults, and summaries

-  Templates can be set up for specific types of documents for specific
   clinical needs.

-  Interfaces with Problem List, Automated Information Capture System
   (AICS), Patient Care Encounter (PCE), Authorization/Subscription
   Utility (ASU), Incomplete Record Tracking (IRT), Health Summary (HS),
   VistA Imaging (MAG), Clinical Reminders and Visit Tracking

-  Uses a standardized and common user interface, which allows
   clinicians and other to retrieve many kinds of documents from a
   single source

-  Enables health care practitioners to enter interdisciplinary notes
   regarding a single episode of care for a patient. This is
   accomplished through the addition of a level to the tree structure
   where a note can have children (subordinate entries) and each of the
   children can have a different author. This provides for more complete
   patient records and facilitates input from a variety of practitioners
   regarding a single episode of care

-  Interfaces with VistA Imaging which allows users to link TIU
   documents to all types of clinical images such as X-rays, MRIs and
   CAT scans

-  Uses integrated database, which lets clinicians, quality management
   staff, researchers, and management search for and retrieve clinical
   documents more efficiently because documents reside in a single
   location within the database

-  Permits document input from a variety of data capture methodologies
   such as transcription, direct entry through CPRS or the TIU packages,
   voice recognition software, or upload of ASCII formatted documents
   into VistA

-  Uses a uniform file structure for storage of documents and management
   of document types

-  Uses a consistent file structure for defining elements and parameters
   of a document.

-  Allows a variety of user actions, such as entry, edit, electronic
   signature, addenda, deletion/retraction, browse, notifications, etc

-  Allows a variety of management functions, including amendment,
   deletion/retraction, and identification of signature surrogate,
   re-assignment, and administrative authentication

-  Allows for the set up of Crisis, Warning, Allergies, and/or Adverse
   Reactions, and Advance Directives (CWAD)/Postings Auto-Demotion. CWAD
   is a section of CPRS used for posting progress notes which are more
   important than standard level notes. These progress notes are made
   more easily available throughout CPRS. The postings dialog box can
   become full of CWAD notes, resulting in important notes from being
   easily distinguishable from less important notes. Auto-demotion set
   up allows previously designated notes from the CWAD postings to be
   changed to a regular note status based on various criteria, such as
   the passage of time or a new note of a particular title being written
   which supersedes the existing CWAD note

-  Allows the set up of TIU Text alerts which sends a TIU alert to the
   appropriate service provider(s) immediately after a staff member
   screens a patient and signs the associated notes. Set up includes
   defining words or phrases that will be searched for in a TIU document
   (progress note, consult, etc.). If the words or phrase are found in
   the TIU document, then an alert is sent to the team(s) specified in
   the TIU text events file

   1. .. rubric:: 
         Cross Application Integration Protocol (CAIP)
         :name: cross-application-integration-protocol-caip

**Version**:

**Namespace: **

**Brief Description:** The CAIP specification introduces a structure for
defining, providing, and accessing services as shared resources within
the VHA.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Common Services

**Business Owner: **

**VASI ID:** NA

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** The CAIP specification introduces a
structure for defining, providing, and accessing services as shared
resources within the VHA. It is structured around a service-oriented
and/or service-based architectural objective which promotes good
software development practices, such as loose coupling between
applications, and is centered on the concepts of Services and
Capabilities.

The CAIP framework is an implementation of the CAIP Specification.

The framework provides:

-  Business Delegate interfaces for use by the Service Provider when
   developing Business Delegates for their services

-  Consumer-Side/Technology Adaptation to the Service Facades of the
   service

-  Implementation of the Business Delegate Factory, which uses the
   Service Locator to find service information from the Naming and
   Directory Service

   1. .. rubric:: 
         Decision Support System (DSS) Extracts
         :name: decision-support-system-dss-extracts

**Version**: 3.0

**Namespace:** ECX

**Brief Description:** The VistA Decision Support System (DSS) Extracts
software provides a means of exporting data from selected VistA software
modules and transmitting it to a Decision Support System (DSS) resident
at the Austin Information Technology Center (AITC). This transfer is
accomplished through a set of extract routines, intermediate files,
audit reports, transmission, and purge routines.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** Managerial Cost Accounting Office (MCAO)

**VASI ID:** 1214

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122872/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=35

**Full Description and Features:** Data from VistA packages is stored by
the extract routines in the intermediate files, where it is temporarily
available for local use and auditing. The data is then transmitted to
the AITC where it is formatted and uploaded into commercial software.
After the data has been successfully uploaded into the commercial
software, it is purged from the intermediate files.

Extracts consist of the following functions: implementation of extract
processes; scheduling extracts, verifying extracts against other VistA
reports, transmission of extracts to the commercial software,
verification of transmission, and purging extracts.

Data is extracted from the following Medical Records Extract Files:

-  Admissions (ADM) - 727.802 – ADMISSION EXTRACT (ADM) File Data
   Definition

-  Bar Code Medication Administration (BCMA) - 727.833 – BCMA EXTRACT
   (BCM) File Data Definition

-  Clinic (CLI) - CLINIC EXTRACT (CLI) File Data Definition

-  Quality: Audiology and Speech Pathology Audit & Review (QUASAR) (ECQ)
   - 727.825 – QUASAR EXTRACT (ECQ) File Data Definition

-  Event Capture System Local (ECS) - 727.815 – EVENT CAPTURE LOCAL
   EXTRACT (ECS) File Data Definition

-  IV Detail (IVP) - 727.819 – IV DETAIL EXTRACT (IVP) File Data
   Definition

-  Laboratory (LAB) - 727.813 – LABORATORY EXTRACT (LAB) File Data
   Definition

-  Lab Results (LAR) - 727.824 – LAB RESULTS EXTRACT (LAR) File Data
   Definition

-  Lab Blood Bank (LBB) - 727.829 – BLOOD BANK EXTRACT (LBB) File Data
   Definition

-  Physical Movement (MOV) - 727.808 – PHYSICAL MOVEMENT EXTRACT (MOV)
   File Data Definition

-  Prescription (PRE) - 727.81 – PRESCRIPTION EXTRACT (PRE) File Data
   Definition

-  Prosthetics (PRO) - 727.826 – PROSTHETICS EXTRACT (PRO) File Data
   Definition

-  Radiology (RAD) - 727.814 – RADIOLOGY EXTRACT (RAD) File Data
   Definition

-  Surgery (SUR) - 727.811 – SURGERY EXTRACT (SUR) File Data Definition

-  Treating Specialty Change (TRT) - 727.817 – TREATING SPECIALTY CHANGE
   EXTRACT (TRT) File Data Definition

-  Unit Dose Local (UDP) - 727.809 – UNIT DOSE LOCAL EXTRACT (UDP) File
   Data Definition

-  Uses a roll-and-scroll format that allows users to perform the
   various functions by selecting the appropriate menu options

-  Uses VA Mailman to transmit data to commercial software resident at
   the AITC

   1. .. rubric:: 
         Diagnostic Related Grouper (DRG)
         :name: diagnostic-related-grouper-drg

**Version**: 18.0

**Namespace:** ICD

**Brief Description:** The Diagnostic Related Grouper (DRG) is based on
the Medicare Group requirements as defined by the Centers for Medicaid
and Medicare Services (CMS) and as reported in the Federal Register.
Each DRG represents a class of patients who are deemed medically
comparable and who require approximately equal amounts of health care
resources.

**Business Function Framework Line(s) of Business:** Manage Public
Health, Deliver Healthcare, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Epidemiological
Assessments, Manage Health Records, Utilize Information Technology
Services, Provide Financial Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Office of Informatics and Analytics

**VASI ID:** 1185

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122775/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=36

**Full Description and Features:** The module groups diagnostic and
operation/procedure codes into the DRGs based on the combination of
codes, age, sex, discharge status, and occurrence of death.

-  Provides annual updates that conform to the latest release of the
   commercial grouper

-  Functions within or apart from other modules

-  Supplies detailed descriptions of DRGs, diagnostic codes, and
   operation/procedure codes

-  Accepts one primary diagnosis and multiple secondary diagnostic codes
   and operation/procedure codes. Displays weighted work unit values as
   well as national and local high and low trim point values for each
   DRG

   1. .. rubric:: 
         Duplicate Record Merge
         :name: duplicate-record-merge

**Version**: 7.3

**Namespace:** XDR

**Brief Description:** Duplicate Patient Merge provides an automated
method to combine duplicate patient records into a single record within
the VistA database. It was released under the Duplicate Resolution
System menu as part of the Kernel Toolkit.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=2

**Full Description and Features:** The overall process is broken down
into these phases:

1. Duplicate patient records are identified by the VAMC staff or by a
   separate system interfaced with the Master Patient Index

2. VAMC staff review/verify the pairs and approve the pair

3. VAMC IT or expert users schedule and monitor merges of the pairs

Initial search and identification of potential duplicate records is
accomplished by performing comparisons on key patient traits in the
centralized Person Service Identify Management (PSIM) database. It is
the goal of PSIM to provide an authoritative source for persons’
identity traits throughout the Veterans Health Administration (VHA).

The review/verification phase of the patient merge process consists of
two levels of review before verification. The primary reviewer performs
a review of patient demographic information and determines if the pair
is a duplicate record, then selects the record that will be merged into
the other record, which is known as the merge direction. When data from
ancillary services is present, a notification (via Mailman message or
alert or both) is sent to the designated ancillary reviewers.

All reviewers determine whether the record pair is a duplicate, not a
duplicate, or unable to determine the status. If all reviewers conclude
that the pairs are duplicates and need to be merged, the record pair is
designated as a verified duplicate available for merge approval. For
those pairs determined not to be duplicates, the processing stops and
the status indicates they are verified as non-duplicates. If status
cannot be determined, the record pair remains in the DUPLICATE RECORD
file and processing ends unless the Healthcare Identity Management and
Data Quality (HC IdM) team can assist and determine the resolution.

The next phase is the merge of the record pairs. A wait time may be
configured between verification and merge. The merge is a non-reversible
process. Once the pair of records is merged, there is no automated way
of undoing the process. The application has been written to support
multiple parallel jobs (threads - as specified by the site) during the
merge process, and multiple pairs can be merged in a single process.
However, only one merge process should be running at once.

Although the software was designed with potential to merge New Person
records, this capability is not included in the released version.

Electronic Claims Management Engine (ECME) (AKA: ePharmacy)
-----------------------------------------------------------

**Version**: 1.0

**Namespace:** BPS

**Brief Description:** The Electronic Claims Management Engine (ECME)
package provides the ability to create and distribute electronic
Outpatient Pharmacy claims to insurance companies on behalf of VHA
Pharmacy prescription beneficiaries in a real-time environment. The
application does not impact first party co-payments and minimizes the
impact on legacy pharmacy workflow.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Provice Financial Management

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Chief Business Office

**VASI ID:** 1205

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122865/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=141

**Full Description and Features:** This system meets the Health
Insurance Portability and Accountability Act (HIPAA) of 1996 mandate,
specific to the Electronic Transactions and Code Sets rule regarding
compliance with submitting claims electronically to insurance companies
via the National Council for Prescription Drug Programs (NCPDP) standard
transmission format. ECME receives a billing determination by Integrated
Billing (IB) if an Outpatient Pharmacy order is billable. If so, ECME
builds a NCPDP electronic claim transaction using data required by the
insurance company for claim adjudication, as defined within the
company’s individual payer sheet. Claims are submitted during the
Outpatient Pharmacy finish process, and again during the Outpatient
Pharmacy release process if the claim was initially rejected. If any
additional edits or other events occur to the prescription, such as a
return to stock, ECME generates additional electronic claims to payers
updating them on the prescription billable status and updates IB with
any claim specific information.

The ECME application provides the following features:

-  Creation of outpatient pharmacy electronic claims for real-time
   submission to third party insurance companies for adjudication
   utilizing billing activities within the VHA prescription fill process

-  Utilization of information provided by a subscription with a vendor
   to create electronic claims

-  Support and integrated functionality for TRICARE/CHAMPUS, ChampVA,
   and itemized charging methods for prescription pricing

-  Enhancements to VHA revenue cycle management by submitting claims at
   the point of service while building claim segments using
   payer-provided transaction formats compliant with the NCPDP standard

-  Collection and presentation of DUR information to application users
   based on information received from payer claim responses

-  Reporting and on-line work list presentation formats supporting VHA
   claims adjudication requirements

-  Integration with VistA IB for prescription billing determination and
   claims tracking

-  Integration with VistA Pharmacy applications when creating claims
   based on Pharmacy workflow

-  Communication with the VistA Health Level Seven (HL7) application and
   messaging software solution to store and forward electronic pharmacy
   claims for third party insurance adjudication

-  Enhanced in February 2014 to support Health Plan Identifier (HPID)
   that implements a new national standard of having a single identifier
   to use on electronic transmissions pertaining to health care. All
   entities that are financially responsible for care are assigned a
   HPID or Other Entity Identifier (OEID), used for entities that aren't
   traditional health plans. This new standard increases
   interoperability by replacing clearinghouse-specific identifiers for
   health plans

-  Enhanced in May 2015 to improve matching the ECME number on incoming
   pharmacy Electronic Remittance Advice (ERA) claim lines to the claim
   numbers in VistA

-  Enhanced in February 2016 to extend the capabilities of the
   electronic pharmacy (ePharmacy) billing system to support the
   ePharmacy NCPDP continuous maintenance standards. This included
   ePharmacy system modifications to support new data elements for NCPDP
   versions E.0 through E.6, changes to the Close Claim [CLO] action on
   the ECME User Screen [BPS USER SCREEN], the Rx Not Processed for Site
   bulletin was modified to direct the user to the correct ECME option
   in order to get more information on the reject, the Rx Not Processed
   for Site bulletin was modified to include the associated ECME number,
   if it exists, the he Claim Results and Status [BPS MENU RPT CLAIM
   STATUS] menu was modified to include a new Non-Billable Status Report
   [BPS RPT NON-BILLABLE REPORT] option, and the if a TRICARE or CHAMPVA
   inpatient claim is reversed by the inpatient auto reversal process of
   the BPS NIGHTLY BACKGROUND JOB, the transaction will be filed in the
   PSO AUDIT LOG (#52.87) file as a bypass prescription so that it will
   be displayed on the TRICARE-CHAMPVA Bypass/Override Report, which is
   part of the Outpatient Pharmacy application

-  Enhanced in August 2016 to extend the capabilities of the electronic
   pharmacy (ePharmacy) billing system. This included about 12 changes
   to the ECME User Screen [BPS USER SCREEN], a new Security Key called
   BPS SUPERVISOR which is required for anyone accessing the OPECC
   Productivity Report [BPS OPECC PRODUCTIVITY REPORT], several reports
   changes to include the Closed Claims Report [BPS RPT CLOSED CLAIMS]
   which will display the billed amount in the Excel download format,
   the Potential TRICARE Claims Report [BPS COB RPT TRICARE CLAIMS] will
   have new functionality and be renamed to Potential Claims Report for
   Dual Eligible [BPS POTENTIAL CLAIMS RPT DUAL], and a new report
   called OPECC Productivity Report [BPS OPECC PRODUCTIVITY REPORT].
   Also, the system will now support new and modified data elements and
   fields for NCPDP Telecommunications version E7 according to the
   October 2015 NCPDP release. Support for new and modified reject codes
   through this release is also included. Enhancements include HL7
   transmissions for ePharmacy plans, processors, and PBMs (PHARMACY
   BENEFITS MANAGER) from FSC re-directed to use the ePharmacy HL7 link
   on EPHARM OUT instead of IIV EC, and the Vitria Interface Version was
   updated to version 5 and a new registration message will be sent to
   AITC to communicate that updates have occurred

-  Enhanced in September 2017 to extend the capabilities of the
   electronic pharmacy (ePharmacy) billing system to include updating
   the ECME User Screen [BPS USER SCREEN] and changing the system so it
   can support new and modified data elements and fields for NCPDP
   Telecommunications versions published on/after January 2016. It also
   included "RED" Resubmit Claims w/EDITS hidden action under the ECME
   User Screen [BPS USER SCREEN] will no longer allow an OPECC to enter
   or edit a Submission Clarification Code if the reject is pending on
   the pharmacist's reject worklist or if the most recent transaction is
   resolved or unresolved for reject codes 79 Refill Too Soon and code
   88 Drug Utilization review (DUR), and changing the main screen of the
   ECME User Screen [BPS USER SCREEN] to display a comment for only the
   most current transaction. Comments for previous Transaction(s) will
   continue to be available when accessing the CMT Add/View Comments
   action from the ECME User Screen (current functionality)

-  Enhanced in November 2017 to extend the capabilities of the
   electronic pharmacy (ePharmacy) billing system to include the new VER
   (View ePharmacy Rx) option, and to update the CV (Change View) action
   on the ECME User Screen and the ECME AUTO-REVERSAL PROCESS email
   bulletin. The system was also updated to support new data elements
   and fields for NCPDP Telecommunications versions published through
   October 2016. The Claim Log and the Claim Response Inquiry was
   updated to include the Facility ID Qualifier and the Reconciliation
   ID, and Option PHAR (Edit ECME Pharmacy Data) was updated to require
   entry for the prompt AUTO-REVERSAL PARAMETER. Finally, this release
   rectified an ongoing problem in which some TRICARE and CHAMPVA
   prescriptions on the CMOP queue would be left on the queue during
   CMOP processing because claim responses would not be received by
   VistA in a timely manner. This release modifies the claim submission
   process and the CMOP process so that certain checks will no longer be
   performed prematurely, allowing sufficient time for the claim
   responses to come back

-  Enhanced in August 2018 to extend the capabilities of the electronic
   pharmacy (ePharmacy) billing system. Several filters on the Change
   View (CV) action of ECME User Screen are being updated to allow the
   user to select one, many, or all. The user will also now be able to
   select a specific date range. The Rejected Claims Report is being
   modified to include three new filter questions, and several of the
   existing filter questions are being modified to allow selection of
   one, many, or all. The excel report is being modified to add new
   fields, truncate some fields, and delete other fields to prevent
   wrapping to another line. The Prescriber filter question is being
   modified to default to "A". The system is being updated to support
   new and modified External Code Lists (ECLs) for the NCPDP
   Telecommunications versions published through October 2017. The
   ePharmacy Medication Profile is being added as an action to VER View
   ePharmacy Rx. The system is being updated to allow for the new HIPAA
   regulatory requirements that increase the length of the following
   fields: Name of Insured, Group Number, Group Name and Subscriber ID.
   When the system builds an outgoing claim request, it includes on the
   claim only those fields appearing on the payer sheet provided by the
   payer. With this enhancement, the user will now be able to send
   additional fields not on the payer sheet via the RED Action from the
   ECME User Screen. This enhancement adds logic to transmit the
   appropriate values on secondary claims when the three fields are
   included on the payer sheet. Logic added to fields: Other Payer
   Patient Responsibility Amount, Amount Qualifier, and Amount Count

   1. .. rubric:: 
         Electronic Error and Enhancement Reporting (E3R)
         :name: electronic-error-and-enhancement-reporting-e3r

**Version**: 1.0

**Namespace:** NTSE

**Brief Description:** Electronic Error and Enhancement Reporting (E3R)
package is designed for storing, reporting, and tracking the requests
for changes in VistA applications.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Monitor Clinical
Performance, Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1210

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122869/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=3

**Full Description and Features:** Anyone in VHA may propose an
enhancement using E3R. The individual making the proposal specifies
which package (module) in VistA he/she believes needs the enhancement.
The enhancement request is sent to a user group associated with the
package. The members of that mail group exchange messages on their view
of the enhancement request. The proposal, along with all of the feedback
from the mail group, is sent to the package's development program
director for a final decision. E3R tracks and logs the entire discussion
process on these enhancement proposals. Provides for submitter to
initiate, modify, view or cancel a request. Assigns a suspense date and
a status category to all submitted E3Rs. The status category informs all
users of the request's current state in the processing cycle. Generates
a mail message containing the text of the request whenever an E3R is
generated. The message is sent to the submitter, the package developer
and members of the mail group associated with the package. Tracks
package developer's response to each E3R request. Developer can deny or
accept the request, enter comments on it, and refer a request to an
arbitrator if he feels the request should not be assigned to a package.
Permits an arbitrator to enter comments, to reassign the request to the
appropriate package, and, along with the package developer, to accept or
deny the request. Produces several reports available to both users and
developers.

• Tracking, storing, reporting requests for changes in VistA

Electronic Signature (Esig)
---------------------------

**Version**: 1.0

**Namespace:** XOBE

**Brief Description:** The Electronic Signature (ESig) service provides
an interim solution for the use of electronic codes during certain VistA
security infrastructure and architecture evolutions.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1791

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123327/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=171

**Full Description and Features:** The service duplicates for Java
applications Java 2 Enterprise Editiion (J2EE) or Java 2 Standard
Edition (J2SE) the Kernel V.8.0 electronic signature functionality
currently used by VistA/M applications. ESig furnishes a standard,
consistent set of APIs that VistA developers can use to provide users
access to electronic signature data stored on VistA/M systems.

ESig APIs make calls from Java applications to VistA/M systems to
retrieve, validate, and store electronic signature codes and signature
block information (name, title, office phone, etc.). Additional Java
APIs provide encoding/decoding, hash, and checksum calculation
utilities, but do not interact with the VistA/M system.

Applications that implement the ESig service must provide a user
interface (UI) to prompt users for their secret codes when authorizing
orders, prescriptions, financial transactions, or other business
processes. Users may also need the UI to create or modify their code or
signature block data.

-  Provides applications access to Kernel electronic signature APIs

-  Supports J2EE and J2SE implementations

-  Requires ESIG KIDS build installation on VistA/M server

-  VistA application provides any necessary user interfaces

-  Distributed with feature-complete sample applications (J2SE and J2EE)

-  Sample J2EE application can be deployed to admin/managed
   servers/clusters

Electronic Signature security features are based on the following
requirements:

-  VistA Esig applications are required to authorize and authenticate
   their users

-  Infrastructure tools such as Kernel Authentication and Authorization
   for J2EE (KAAJEE) and FatKAAT (rich-client Kernel Authentication and
   Authorization) are mandated for use in indicated VistA Web-based and
   rich-client applications, respectively

   1. .. rubric:: 
         Emergency Department Integration Software (EDIS)
         :name: emergency-department-integration-software-edis

**Version**: 2.1

**Namespace:** EDP

**Brief Description:** Emergency Department Integration Software (EDIS)
incorporates several Web-based views that extend the current
Computerized Patient Record System (CPRS) to help healthcare
professionals track and manage the flow of patient care in the emergency
department setting.

**Business Function Framework Line(s) of Business:** Provide Healthcare
Administration, Deliver Healthcare, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Disaster
Preparedness Programs, Provide Nursing, Provide Medical Services, Manage
Health Records, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Systems Redesign

**VASI ID:** 1792

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123328/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=179

**Full Description and Features:** EDIS views are based on an
application originally developed in VISN 2. Most views are
site-configurable.

-  Addition of emergency department patients to the application’s
   display board

-  Viewing of information about patients on the display board

-  Editing of Patient Information and configuring the display board

-  Removal of patients from the display board/entering of patient
   dispositions

-  Creation of administrative reports

-  Provides role-based access to specific functionality sets with views
   disabled based on these role-based access protocols

   1. .. rubric:: 
         Engineering (AEM/MERS)
         :name: engineering-aemmers

**Version**: 7.0

**Namespace:** EN

**Brief Description:** Engineering, also known as Automated Engineering
Management System/Medical Equipment Reporting System (AEMS/MERS),
facilitates the management of information needed to effectively
discharge key operational responsibilities normally assigned to VA
engineering organizations, such as Work Orders, Equipment Management,
Program Management and Space/Facility Management.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Manage VHA-wide Administrative Services, Conduct Supply
Chain Operations, Provide Financial Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Procurement and Logistics Office (PLO)

**VASI ID:** 1996

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123379/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=37

**Full Description and Features:** The Engineering package was designed
as a resource that can be shared by medical center administrative staff.
Safeguards against unauthorized editing of key data elements of non-
expendable (NX) equipment records have been designed into the system.
Engineering maintains integration agreements with Integrated Funds
Distribution, Control Point Activity, Accounting and Procurement (IFCAP)
such that the status of work orders is automatically updated on the
basis of orders for parts or service. The Engineering package is the
VA's official record of inventory for capitalized personal property.

-  Manages electronic work orders. Staff throughout a facility can
   electronically enter work requests. These requests are promptly
   reviewed by Engineering personnel and assigned to theappropriate
   maintenance shop

-  Tracks and controls work orders, maintaining annotated repair
   histories for medical and non- medical equipment. There is a separate
   menu option for display of incomplete work orders

-  Uses bar codes for equipment inventory and preventive maintenance.
   Completed work orders are automatically posted to equipment histories

-  The Project Tracking module is used to record significant events
   during construction and non- recurring maintenance projects when the
   management of such a project has been delegated to the facility

-  The Equipment Management module contains building features (square
   footage, floor coverings, window types, etc.) and keeps track of
   locks and keys. Provides capitalized personal property data to the
   Fixed Assets subsystem (FAP) of the Financial Management System (FMS)

   1. .. rubric:: 
         Enrollment Application System
         :name: enrollment-application-system

**Version**: 1.0

**Namespace:** EAS

**Brief Description:** The Enrollment Application System (EAS) package
supports the mandate for collection of Long Term Care (LTC) copayments,
as required by Public Law 106-117. In addition to the LTC functionality,
the EAS package provides support for Health Level 7 (HL7) for processing
of HL7 messages between VistA, the enterprise Enrollment System (ES) and
data matching with the Internal Revenue Service (IRS) / Social Security
Administration (SSA).

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care

**Business Function Framework Function(s):** Provide Member Access

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Systems Management Chief Business Office

**VASI ID:** 1244

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122798/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=121

**Full Description and Features:** The 1010EZ functionality was replaced
by the Veterans' Online Application (VOA) hosted on vets.gov. These
applications have a direct interface with the national Enrollment System
(ES). This application originally generated letters notifying veterans
subject to means testing of yearly Means Test (MT) expiration, but that
feature is obsolete. With patch DG\*5.3\*858 in March 2014, annual MT
renewal was discontinued and a Veterans Financial Assessment (VFA) Start
Date of 1/1/13 was put into place. A non-exempt veteran is required to
have only one MT less than one year old as of 1/1/13, and that MT should
remain valid permanently. Now, a non-exempt veteran is required to have
only one MT that was less than one year old as of 1/1/13, and that MT
should remain valid throughout the future. Local means test reminder
letters were discontinued by patch EAS\*1\*106 as part of the
DG\*5.3\*858 build.

The Veterans Millennium Health Care and Benefits Act, Public Law
106-117, Sec. 101, mandates the application of copayments for veterans
receiving Long Term Care (LTC) services. The LTC Copayment software is
designed to work in conjunction with software currently in place for
determining veteran medical and pharmacy copayment obligations and
benefit eligibility based on military history, service-connected
disabilities, and financial input.

Phase 1 introduced the following LTC Copayment functionality.

-  Allows users to enter, edit, store and print financial information
   given by the veteran on VA Form 10-10EC, Application for Extended
   Care Services

-  Allows users to designate a veteran who is exempt from the LTC
   copayments and the reason for the exemption

-  Using the financial information entered from the VA Form 10-10EC,
   Application for Extended Care Services, automatically calculates and
   displays or prints an estimate of the LTC copayments that the veteran
   will be obligated to pay for the next twelve months

-  Provides Integrated Billing with a veteran's copayment amount via an
   API

Phase 2 added the following functionality.

-  Automated eligibility exemptions

-  Adds the LTC Copayment Exemption Test submenu and associated user
   options

-  Provides spend-down calculations

Phase 3 added the following new functionality.

-  Allows users who have the appropriate security key to delete a LTC
   Copayment Test (10-10EC)

-  Phase 3 added the following enhancements to previously existing
   functionality.

-  Allows users who have the appropriate security key to edit the date
   of a LTC Copayment Test

-  Allows users to add a new LTC Copayment Test for the veteran at any
   time, including multiple tests within the same year

-  Allows users to enter burial and funeral expenses for single veterans

-  Allows users to enter expenses greater than total income on the input
   screen for the LTC Copayment Test (10-10EC)

-  Displays the veteran’s LTC copayment status and last test date when
   using the following Registration user options: Load/Edit, Patient
   Inquiry, and Register a Patient

-  If the veteran did not agree to pay the copayments display a message
   that indicates that the veteran is ineligible for LTC services

-  Prevents the entry of a LTC Copayment Test for a patient who is not a
   veteran

-  Corrects the display of the DECLINES TO PROVIDE FINANCIAL INFORMATION
   field to include both the “YES” and “NO” responses when the LTC
   Copayment Test is displayed

-  Modifies the Calculated LTC Copayments report to correctly display
   the maximum copayment amounts for veterans who refuse to pay the
   copayment

-  Corrects the determination of the LTC Copayment status when a
   veteran’s income is $0. The LTC Copayment status will be EXEMPT

Phase 4 adds the following new functionality.

-  Adds a new menu option, Expiring or Expired LTC Copayment Tests, to
   the LTC Copayments menu. It allows users to print a report listing
   veterans whose LTC Copayment Tests have already expired or are about
   to expire

Phase 4 adds the following enhancements to previously existing
functionality.

-  Modifies VA Form 10-10EC, Application for Extended Care

   -  Adds Item 9 (Current Marital Status) to Page 1, Section III

   -  Modifies Page 2, Section IV, Fixed Assets, and Section V, Liquid
      Assets, to provide separate columns for veteran and spouse

   -  Modifies Page 2, Section V, Liquid Assets to have 2 categories of
      assets instead of 3

   -  Modifies Page 2, Section VI, Current Gross Income of Veteran and
      Spouse, to have 3 categories of income instead of 14

   -  Modifies Page 2 to include all financial items

   -  Reserves Page 3 for signatures (consent for assignment of
      benefits, consent and agreement to make copayments)

-  Modifies the financial data screens to reflect the format changes
   made to the VA Form 10-10EC, Application for Extended Care paper form

-  Replaces the ELIGIBILITY STATUS DATA, SCREEN <2> with the INSURANCE
   DATA, SCREEN <5> from the Registration options

-  Modifies the Add a New LTC Copayment Test and Edit an Existing LTC
   Copayment Test options to enable the user to indicate that the
   veteran is exempt from LTC copayments (for a reason other than low
   income) and complete the LTC Copayment Test without having to go
   through all of the financial screens

-  Supports the display and printing of the LTC Copayment Tests in
   either the old or new 10-10EC format, depending on which one is used
   to complete the test

-  Modifies the MARITAL STATUS/DEPENDENTS, SCREEN <3> to allow users to
   indicate if a veteran is legally separated; if so, the copayments
   will be calculated using the rules for an unmarried veteran

-  Modifies the FIXED AND LIQUID ASSETS, SCREEN <4> to provide separate
   columns for veteran and spouse, combine fields in Field 4 (Cash,
   Stocks, Mutual Funds), and provide modified help text for Field 5
   (Other Liquid Assets)

-  Modifies the CURRENT CALENDAR YEAR GROSS INCOME, SCREEN <5> by
   reducing the number of data groups from fourteen (14) to three (3)
   and provides modified help text for the three new fields

-  Modifies the format of the Calculated LTC Copayments report

   -  Separates out Institutional and Non-institutional

   -  Modifies Institutional to prompt for a LTC admission date

   -  Prints 12 months of copayments starting with a user-specified
      month and year

Allows entry of a future date as the start date to see the spend d

**Background functionality**:

Health Level 7 (HL7) message processing of Internal Revenue Service
(IRS) income verification matching (Z06 messages). This functionality
will transition to the enterprise Enrollment System (ES) at some future
date.

The EAS package provides all protocols utilized by HL7 for processing of
HL7 messages between VistA and the enterprise Enrollment System (ES).

Enrollment System
-----------------

**Version**: 5.2.4

**Namespace:** N/A

**Brief Description:** The Enrollment System is VHA’s System of Record
(SOR) for managing enrollment and eligibility information. The
Enrollment System collects and verifies the enrollment and eligibility
information, which is used to determine services a Veteran and other VHA
health care beneficiaries are entitled to receive.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Provide Access to Health Care, Provide Health Care Administration

**Business Function Framework Function(s):** Provide Member Access and
Perform Hospital Administration

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Systems Management Chief Business Office

**VASI ID:** 1231

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123188/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=121

**Full Description and Features:** Enrollment System (ES) 5.2.4 is the
replacement system for the decommissioned product known as HEC (Health
Eligibility Center, Atlanta) Legacy. It is both a re-host of HEC Legacy
and in some instances (use cases/features), a re-engineering. ES allows
staff at the HEC to work more efficiently and determine patient
eligibility in a timelier manner. Messaging with the VAMC (Department of
Veterans Affairs Medical Centers) allows updates to the enterprise
enrollment system to be shared with the field in close to real-time. It
is one component of the "system of systems" needed to implement the
HealtheVet REE (Registration, Eligibility and Enrollment) environment.

The two main functions are:

-  Expert System (Messaging) The messaging subsystem provides a seamless
   bi-directional interface with external Veterans Health Administration
   (VHA) and non-VHA systems for data exchange of Veterans’ information.
   Work Flow (Case Management)

-  The case management subsystem provides authorized VHA case
   representatives at the HEC with a web interface to easily track,
   maintain, and manage cases associated with Veteran benefits

HEC staff utilizes ES to manage these "cases" to completion so that
verified E&E can be determined.

Expert System (Messaging) - The messaging subsystem provides a seamless
bi-directional interface with external Veterans Health Administration
(VHA) and non-VHA systems for data exchange of Veterans’ information.

Work Flow (Case Management) - The case management subsystem provides
authorized VHA case representatives at the HEC with a web interface to
easily track, maintain, and manage cases associated with Veteran
benefits. HEC staff utilizes ES to manage these "cases" to completion so
that verified E&E can be determined.

Enterprise Exception Log Services (EELS)
----------------------------------------

**Version**: 3.0

**Namespace:** SVE

**Brief Description:** The Enterprise Exception Log Service (EELS)
provides for the consolidation and analysis of exception logs generated
by VistA components and services, as well as other logs generated by
infrastructure components.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=177

**Full Description and Features:** Enterprise Exception Log Service is a
web-based application responsible for collecting error logs of
applications, databases and systems. It is a suite of software
applications that collects and stores exception information generated by
client VA software applications. It incorporates exception logging
analysis and reporting capabilities into the VistA environment to
monitor services and information assets across the enterprise. It
provides an enterprise exception logging service and associated
infrastructure that enables the retrieval of exception logs from any
VistA component in the VistA shared service architecture environment,
and their transportation to a central repository, where that information
is available for analysis and reporting purposes. It improves
organizational support structures and processes to address the needs of
application modernization.

-  Collects error log data

-  Provides robust capacity to facilitate event information activity
   from indicated locations

-  Organizes the errors from numerous locations into one database

-  Provides Analysis and Reporting functionality

   1. .. rubric:: 
         Equipment /Turn-In Request
         :name: equipment-turn-in-request

**Version**: 1.0

**Namespace:** PRCN

**Brief Description:** The Equipment/Turn-In Request software provides
additional functionality within the Integrated Funds Distribution,
Control Point Activity, Accounting and Procurement (IFCAP) package,
including the ability to enter an electronic request for new,
non-expendable equipment and replacement equipment.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling

**Business Function Framework Function(s):** Conduct Supply Chain
Operations

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Procurement and Logistics Office (PLO)

**VASI ID:** 1794

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123329/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=113

**Full Description and Features:** The Equipment/Turn-In Request
software adds the functionality for tracking the request through the
many stages of review, prior to its approval and becoming a permanent
transaction. Users are allowed to turn in old equipment currently
tracked in the Equipment Inventory file, generate an Engineering work
order, and track its movement to its final disposition and removal from
the inventory list. The Equipment/Turn-In Request serves as a records
maintenance system, allowing the user to record important events
throughout the ordering process. Such records can be printed in report
format as supporting documentation about the equipment lifecycle.

-  The CMR official is ultimately responsible for new and existing
   equipment located at the medical facilities

-  A requester can enter an electronic request for new or replacement
   equipment via VistA

-  A requester can enter an electronic request to dispose of obsolete
   equipment

-  The CMR official can approve, edit, or cancel an equipment request

-  Engineering work orders can be generated for initial, additional, and
   replacement equipment

The Equipment/Turn-In Request module has several organizational elements
that use different omponents of the software.

Non-expendable equipment must go through several approval steps before
it can be ordered:

-  Requestor

-  Consolidated Memorandum of Receipt (CMR) Official

-  Personal Property Manager (PPM)

-  Equipment Committee

-  Engineering

-  Other Concurring Officials

Turning in non-expendable equipment also requires several approval
steps:

-  Requestor

-  Consolidated Memorandum of Receipt (CMR) Official

-  Personal Property Manager (PPM)

-  Engineering

-  Warehouse

   1. .. rubric:: 
         Event Capture System
         :name: event-capture-system

**Version**: 2.0

**Namespace:** EC

**Brief Description:** The Event Capture System (ECS) provides a
mechanism to track and account for procedures and delivered services
that are not handled in any other VistA package. The procedures and
services tracked through Event Capture are associated with (1) the
patient to whom they were delivered, (2) the provider requesting the
service or procedure and (3) the Decision Support System (DSS) Unit
responsible for delivering the service.

**Business Function Framework Line(s) of Business:** N/A

**Business Function Framework Function(s):** N/A

**VHA Portfolio:** Business Informatics

**Business Owner:** Managerial Cost Accounting Office (MCAO)

**VASI ID:** 1795

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123330/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=39

**Full Description and Features:** The Event Capture software provides a
mechanism to track and account for procedures and delivered services
that other Veterans Health Information Systems and Technology
Architecture (VistA) packages do not handle. The procedures and services
tracked through Event Capture are associated with the following:

-  The patient to whom they were delivered

-  The provider requesting the service or procedure

-  The Decision Support System (DSS) Unit responsible for delivering the
   service

DSS Units typically represent the smallest identifiable work unit in a
clinical service at a medical center. Veterans Affairs Medical Centers
(VAMCs) define the DSS Units. A DSS Unit can represent any of the
following:

-  An entire service

-  A section of a service

-  A small section within a section

-  A medical equipment item used in patient procedures

-  When creating or editing DSS Units, users choose what (if any) data
   is sent to Patient Care Encounter (PCE). The advantage of using Event
   Capture to send data to PCE is that it eliminates the duplicate
   effort of entering the same workload data in the Scheduling software,
   then transmitting to PCE

   -  When creating or editing DSS Units, users choose what (if any)
      data is sent to Patient Care Encounter (PCE). The advantage of
      using Event Capture to send data to PCE is that it eliminates the
      duplicate effort of entering the same workload data in the
      Scheduling software, then transmitting to PCE

   -  Allows each VAMC to utilize the software for its own
      resource/costing needs

   -  Implements DSS Units

   -  Assigns user access to all or specific DSS Units

   -  Sets up Event Code Screens to define relevant procedures for a DSS
      Unit

   -  Allows single and batch data entry for patient procedures

   -  Generates reports for workload and other statistical tracking

   -  Provides a Graphical User Interface to the ECS application

   -  Allows user to upload patient encounter data to Event Capture from
      a spreadsheet

   -  Files encounter records in PCE for DSS Units defined to send data
      to PCE

   -  ICD-10 code compliant

   1. .. rubric:: 
         Fat Client Kernel Authentication and Authorization (FatKAAT)
         :name: fat-client-kernel-authentication-and-authorization-fatkaat

**Version**:

**Namespace:** XU

**Brief Description:** A common service and a project of HealtheVet
Security Services, Fat Client Kernel Authentication and Authorization
(FatKAAT) provides user authentication and authorization for J2EE
applications with a rich client user interface.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1257

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122913/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=152

**Full Description and Features:** A common service and a project of
HealtheVet Security Services, Fat Client Kernel Authentication and
Authorization (FatKAAT) provides user authentication and authorization
for J2EE applications with a rich client user interface.

As a HealtheVet Security Service project, FatKAAT provides a framework
for information security services that ensures the confidentiality,
integrity, and availability of veteran’s health information through VHA
systems, and provides security services to HealtheVet applications.

-  Supports authentication and authorization for a J2EE application with
   a rich client front end Supports WebLogic v9.2/10.x

-  FatKAAT addresses the Authentication and Authorization (AA) needs of
   HealtheVet-VistA rich client-based applications in the J2EE
   environment. In particular, it provides an
   authentication/authorization solution that works in an environment
   where a single enterprise user repository has not been finalized, by
   leveraging the aggregate of the individual user repositories on the
   various VistA/M systems

Ongoing initiatives to provide an enterprise user repository, enterprise
single sign on, authentication and authorization using commercial off
the shelf products may render FatKAAT unnecessary in the future.

-  Kernel (i.e., Kernel Patch XU\*8.0\*376) is the designated custodial
   software package of FatKAAT; however, FatKAAT comprises multiple
   patches and software releases from several HealtheVet-VistA
   applications:

-  Programming Language: MUMPS, Java

-  Deployment Environment/Application Server Software: BEA WebLogic
   V.8.1 (SP4 or higher: VistALink V.1.5, FatKAAT: V.1.0.0.110 (J2EE
   Software Distribution Zip File)

-  VistA M Server Test Patches (listed in patch number order): Kernel:
   XU\*8.0\*265 (RELEASED), Kernel: XU\*8.0\*337 (RELEASED), Kernel:
   XU\*8.0\*361 (RELEASED), Kernel: XU\*8.0\*376 (TEST), Kernel:
   XU\*8.0\*395 (RELEASED), RPC Broker: XWB\*1.1\*35 (RELEASED), Client
   Software: FatKAAT: V.1.0.0.110 (J2EE Software Distribution Zip File)

-  Depends On: VistA 1.0 (FileMan, Kernel, Kernel Toolkit, RPC Broker,
   VistALink)

-  The following packages depend on FatKAAT: VistA 1.0 (CPRS:
   Authorization Subscription Utility (ASU)), VistA 1.5 (My HealtheVet),
   Department Of Defense (DOD) Information Sharing (Clinical Data
   Repository / Health Data Repository (CHDR))

   1. .. rubric:: 
         Fee Basis
         :name: fee-basis

**Version**: 3.5

**Namespace:** FB

**Brief Description:** The Fee Basis package supports VHA’s Fee for
Service program, which is care authorized for veterans who are legally
eligible and are in need of care that cannot feasibly be provided by a
VA facility.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Provide Financial
Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Chief Business Office (CBO) - Purchased Care

**VASI ID:** 1796

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123331/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=40

**Full Description and Features:** A VA facility unable to meet the
patient care requirements of a veteran may authorize fee basis services
for short-term care, ongoing outpatient care, or home health care from
non-VA health care facilities. Bills for service are then submitted to
the authorizing VA facility. The bill is reviewed by the facility and
certified for payment through VA’s payment center in Austin, Texas.

The Fee Basis package provides for more efficient and accurate operation
of the fee for service program with reduction of paperwork, savings in
staff hours, minimization of errors, and by allowing medical facilities
to have greater control over disbursement of fee medical, pharmacy, and
travel monies.

-  Performs entire fee for service process, both authorized and
   unauthorized, for Outpatient Medical Fee, Civilian Hospital,
   Community Nursing Home, and Pharmacy Fee

-  Automatically sends vendor updates from the central system to keep
   all files accurate and up- to-date

-  Provides money management for all payments through the interface with
   the Financial Management System

-  Automatically receives payment confirmations from the U.S. Department
   of the Treasury, populating payment histories with check numbers and
   payment dates.

-  Updated October, 2014 to support ICD-10 functionality

-  Per the Newborn Claims Processing Enhancement Project for Public Law
   111-163, the Caregiver and Veterans Omnibus Health Services Act of
   2010, the VA will provide health care services to a newborn child of
   a Woman Veteran who is receiving maternity care at the VA for not
   more than seven days after the birth of the child, and the software
   will capture information on healthcare services provided to include
   eligibility determination, enrollment and registration, documentation
   of referrals and authorization for care, claims processing, and
   payment. Functionality was added in December 2013

-  As part of the VistA Fee Separation of Duties project, software was
   enhanced in October, 2014 to retain historical data for selected
   fields in order to maintain complete records on actions for
   accounting, information integrity and control by documenting date and
   time of the change, the old value, the new value, and the person that
   made the change

-  Reject flags from old payments, removes old payments with payment
   confirmation or cancellation data from in-process batches, and
   enhances the Print Rejected Payment Items report option

-  Three new security keys are implemented: FBAA LEVEL 1 AUTH, FBAA
   LEVEL 1 PMT, FBAA LEVEL 2

Outpatient Medical Fee:

-  Authorizes Fee Basis treatment

-  Enters fee providers and payments

-  Creates, closes out, and releases batches of invoices

-  Records travel payment

Civilian Hospital:

-  Provides the ability to perform complete payment process, from
   entering patient authorizations to transmitting completed batch data
   (including the calculation of Medicare reimbursement)

Community Nursing Home:

-  Provides the ability to perform complete payment process

Pharmacy Fee:

-  Provides the means to administer the Hometown Pharmacy

-  Provides payment for medications furnished Veterans on an emergency
   basis

-  Facilitates the quick completion of previously repetitive actions and
   gives quick, accurate access to patient payment history

State Home:

-  Provides the ability to track veterans receiving care provided by a
   state home facility

-  Enhanced in December 2014 to support The Intra-governmental Payment
   and Collection System (IPAC) which provides a standardized
   inter-agency fund transfer mechanism for Federal Program Agencies
   (FPA). It facilitates the intra-governmental transfer of funds, with
   descriptive data, from one FPA to another. Processing payments
   through IPAC provides the Financial Management Service (FMS) with the
   ability to meet its statutory requirements for accounting and
   reporting

-  Updated in February 2015 to allow the Diagnosis to be stored when
   entering payments

   1. .. rubric:: 
         FileMan Delphi Components (FDMC)
         :name: fileman-delphi-components-fdmc

**Version**: 1.0

**Namespace:** FMDC

**Brief Description:** VA FileMan is Veterans Health Information Systems
and Technology Architecture’s (VistA) database management system (DBMS).
It runs in any American National Standards Institute (ANSI) environment.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=6

**Full Description and Features:** The majority of Veterans Health
Administration (VHA) clinical data is stored in VA FileMan files and is
retrieved and accessed through VA FileMan Application Program Interfaces
(API) and user interfaces.

For Users:

-  Standalone user interface for adding, editing, printing, and
   searching data

-  Form-based editing (ScreenMan)

-  Easy terminal-based editing of word processing database fields
   (Screen Editor)

-  Flexible, extensive report module

-  Scrollable onscreen output of any report (Browser device)

-  Data interchange with outside applications such as PC spreadsheets
   and databases (Import and Export Tools)

For Developers:

-  Full support for forms-based interfaces to the database (ScreenMan
   API, Form Editor)

-  Full database access for client-server applications (Database Server
   API)

-  Easy scrolling-mode interfaces to the database (Classic API)

-  Full database access in Delphi-based applications via FileMan Delphi
   Components

-  Data archiving and transport tools

-  Comprehensive file creation and management utilities

-  SQL Interface (SQLI) projects all of the information needed by
   M-to-SQL vendors to access VA FileMan through M-to-SQL products

-  Supports Keys and compound cross-references (Indexes)

-  Performance: M and VA FileMan provide fast database performance and
   high utilization of our computer systems

-  Portability - Portable, platform-independent database services
   provided to applications by VA FileMan, combined with the operating
   system portability layer of Kernel, allow VHA to upgrade its hospital
   computing platforms without significant changes to application code

-  Openness - VA FileMan is open; it facilitates data access from
   outside applications. The Database Server (DBS) API enables
   client/server access to VA FileMan data. The FileMan Delphi
   Components take advantage of the DBS API to encapsulate the details
   of retrieving, validating, and updating VA FileMan data

Functional Independence Measures (FIM)
--------------------------------------

**Version**: 1.0

**Namespace:** RMIM

**Brief Description:** The Functional Independence Measures (FIM)
Version 1.0 provides an integration of FIM assessments into the
Computerized Patient Record System (CPRS) and into the Functional Status
and Outcomes Database (FSOD) at the VA Austin Information Technology
Center (AITC). The FIM is an 18-item, 7-level functional assessment
designed to evaluate the amount of assistance required by a person with
a disability to perform basic life activities safely and effectively.

**Business Function Framework Line(s) of Business:** Manage Public
Health, Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Registry
Service, Provide Care Management, Provide Medical Services, Provide
Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1292

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122948/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=134

**Full Description and Features:** There are five types of FIM
assessments: admission, goals, interim, discharge, and follow-up. The
FIM assessments are used clinically to monitor the outcomes of
rehabilitative care as required by the Joint Commission (TJC) and the
Commission on the Accreditation of Rehabilitative Facilities (CARF).
According to VHA Directive 2000-16 series, medical centers are mandated
to measure and track rehabilitation outcomes on all new stroke,
lower-extremity amputees, and traumatic brain injury (TBI) patients
using the FIM.

-  Functional Independence Measurement (FIM) Graphical User Interface
   (GUI) front-end programmed in Delphi to allow multiple clinicians to
   input FIM data for a given patient

-  FIM GUI uses Two Factor Authentication (2FA)

-  Visibility in CPRS of FIM documentation as a progress note with
   addendums and/or a completed consults

-  Eliminating the need for the clinician search of VistA for the
   information and re-enter for FIM

-  FIM data placement in a VistA FileMan file for Health Level Seven
   (HL7) transmission to the Functional Status and Outcome Database
   (FSOD) at Austin Information Technology Center (AITC)

   1. .. rubric:: 
         Generic Code Sheet
         :name: generic-code-sheet

**Version**: 2.0

**Namespace:** GEC

**Brief Description:** The Generic Code Sheet module allows code sheet
data to be entered and transmitted electronically from the medical
facility service level to the national database.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Provide Financial Management

**VHA Portfolio:** Business Informatics

**Business Owner:** Chief Business Office (CBO) - Member Services

**VASI ID:** 1799

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123333/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=7

**Full Description and Features:** Security features prohibit
unauthorized access to code sheets. Data can easily be entered and
edited via VA FileMan. Reports are available which help manage the code
sheets from creation through batching and transmission and tools are
included within the module to aid in the development of new code sheets
at the local or national level.

-  Contains approximately 250 automated code sheets

-  Allows new code sheets to be automated and included within the module

-  Allows easy on-line input of code sheet data from a VA FileMan or
   word processing format

-  Eliminates keypunch and typing errors

-  Provides code sheet security at the medical facility service or
   module level

-  Allows code sheets to be batched and transmitted to any domain
   connected to the VA network

-  Allows easy on-line editing and modifications to code sheets and
   batche

-  Provides purge capabilities consistent with current regulations that
   require code sheet retention for seven years

-  Generates reports that detail the status of a code sheet or batch and
   prints the data contained within a code sheet or batch

   1. .. rubric:: 
         Health Data Informatics
         :name: health-data-informatics

**Version**: 1.0

**Namespace:** HDI

**Brief Description:** The Health Data Informatics (HDI) package
provides a basic method for seeding VHA Unique Identifiers (VUIDs) for
reference data in existing VistA applications.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** Health Data Governance

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=148

**Full Description and Features:** The Health Data Informatics (HDI)
package provides a basic method for seeding VHA Unique Identifiers
(VUIDs) for reference data in existing VistA applications. A VUID is a
meaningless number, which is automatically assigned to concepts,
properties, and relationships in a terminology to facilitate their
access and manipulation by computers.

The HDI package will be used by each VistA site to seed VUIDs in their
existing global files that contain reference data, such as drug names,
names of known allergens, and so forth. These files have been grouped
into domains, and each domain will be standardized separately. As each
domain’s files are originally standardized, the HDI package is used to
assign a VUID to each term or concept in the file. Subsequent
standardization updates and maintenance on these files will be handled
separately by the New Term Rapid Turnaround (NTRT) program.

Health Information Technology Sharing (HITS): Bi-Directional Health Information Exchange (BHIE) and Legacy Viewer Sustainment (LVS)
-----------------------------------------------------------------------------------------------------------------------------------

**Version**: 1.0

**Namespace: **

**Brief Description:** The ability to share data across agencies and
facilities is an important component in providing the complete
information necessary for clinical decision-making and high-quality
veteran care. BHIE supported data sharing between the VA and DoD and
that functionality has now been consumed by LVS.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA

**VASI ID:** 1899

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123473/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** BHIE was deployed to all VA
facilities in October 2004. BHIE expanded on FHIE technology by allowing
textual reports to flow from DoD to VA as well as from VA to DoD. DoD
implemented BHIE at 25 host sites that supported 15 medical centers, 18
hospitals and more than 190 clinics, including Europe, Hawaii and
Alaska.

Historically, data exchanged through BHIE included Drug and Food
Allergies, Admission/Discharge/Transfer (ADT) data, Consults, Inpatient
Discharge Summaries and Notes (including Pre/Post Deployment Health
Assessments), Medications, Radiology, Laboratory (Orders, Chemistry &
Hematology, Cytology, Microbiology, and Surgical Pathology), Outpatient
Encounters and the Standard Ambulatory Data Record (SADR).

In September 2016 LVS was deployed and now provides DoD legacy data to
VA clinicians via CPRS RDV and VistAWeb utilizing Fast Healthcare
Interoperability Resources (FHIR). This allowed for the sunset of BHIE
functionality. Remaining features of BHIE functionality still include
support for PDHA’s utilizing the FHIE repository via the DoD.

Health Information Technology Sharing (HITS): Clinical Health Data Repository (CHDR)
------------------------------------------------------------------------------------

**Version**: 1.0

**Namespace:** CHDR

**Brief Description:** The ability to share data across agencies and
facilities is an important component in providing the complete
information necessary for clinical decision-making and high-quality
veteran care. CHDR provides a mediation service for the exchange of
standardized outpatient prescriptions and allergy information.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA

**VASI ID:** 1115

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122823/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** Clinical Health Data Repository
(CHDR) shares computable health record data elements between DoD’s
Clinical Data Repository (CDR) and VA’s Health Data Repository (HDR).
Data are exchanged for patients identified and matched as Active Dual
Consumers (ADCs) of both VA and DoD health care. VA and DoD conducted
the first successful test of CHDR in a live patient environment in June
2006, and have since expanded.

One of the key features of CHDR is the exchange of standardized,
computable (as opposed to textual) data. This "semantic
interoperability" provides data that each agency can use with its own
electronic decision support tools. In April 2007, VA released a program
called Remote Data Interoperability (RDI), which extended the existing
local Drug-Drug, and Drug-Allergy order checks to include data from all
VA and DoD facilities at which a patient has been treated. This
significantly increases patient safety by ensuring electronic decision
support tools are based on all available electronic patient health
record information rather than data from just one VistA computer system.

Health Information Technology Sharing (HITS): Federal Health Information Exchange (FHIE)
----------------------------------------------------------------------------------------

**Version**: 1.0

**Namespace:** Multiple Namespace

**Brief Description:** The ability to share data across agencies and
facilities is an important component in providing the complete
information necessary for clinical decision-making and high-quality
veteran care. FHIE enables information on separating service members
from DoD to VA on a monthly basis.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA

**VASI ID:** 1261

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122916/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Federal Health Information
Exchange (FHIE) Program is an interagency information technology
initiative between the Departments of Veterans Affairs (VA) and Defense
(DoD) that enables a secure, one-way transmission of protected
electronic health information from DoD to VA. FHIE offers authorized VA
clinicians, including those involved in claims adjudication, immediate
access to DoD clinical data about service members who separate from the
Armed Forces. FHIE supports DoD's and VA's goal of ensuring a smooth
transition for Veterans from active military service to civilian life.

FHIE was deployed to all VA facilities in 2002, and supports the
uni-directional exchange of health record data from the Department of
Defense (DoD) to the Department of Veterans Affairs (VA). The data
exchange is in the form of textual reports via a secure shared data
repository.

VHA clinicians and VBA claims staff access this data in the repository
through Compensation and Pension Records Interchange (CAPRI).
Information available through FHIE includes outpatient pharmacy
(government and retail), allergy, laboratory (chemistry, hematology,
anatomic pathology, surgical pathology, and cytology), radiology
reports, consults, admission, discharge, transfer (ADT), and ambulatory
coding data. DoD also has made pre-and post-deployment health assessment
and post deployment health reassessment data available for viewing by VA
through the FHIE framework.

See also Bidirectional Health Information Exchange (BHIE) Initiative.

FHIE supports the one-way transfer of historical data on separated and
retired military personnel from DoD's Composite Health Care System to
the FHIE Data Repository for use in VA clinical encounters, and
potential future use for aggregate analysis. This data includes patient
demographics, laboratory results, radiology reports, outpatient
government and retail pharmacy information, admission discharge transfer
(ADT) data, discharge summaries, consults reports, allergies and data
from the DoD Standard Ambulatory Data Record. FHIE also supports the
secure transfer of these FHIE data to Veterans Benefits Administration
(VBA) claims adjudicators for use in claims processing.

Health Information Technology Sharing (HITS): Global War on Terror
------------------------------------------------------------------

**Version**: 1.0

**Namespace:** Multiple Namespace

**Brief Description:** The ability to share data across agencies and
facilities is an important component in providing the complete
information necessary for clinical decision-making and high-quality
veteran care. This functionality, referred to as "Big 7" provided
information exchange and interoperability across 7 critical parameters.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** The Global War on Terror (GWOT) led
to the develop of the "Big 7" projects to facilitate a smooth transition
between DoD and VA for veterans and to expedite transfer and improve the
management of high-risk patients such as those with polytrauma and
Traumatic Brain Injury (TBI).

The "Big 7" included:

-  OIF/OEF Combat Veteran Identifier. Provides visual representation in
   the Computerized Patient Record System (CPRS) to indicate the patient
   has served in combat in either Operation Iraqi Freedom (OIF) or
   Operation Enduring Freedom (OEF)

-  Traumatic Brain Injury (TBI) Database. Supports tracking, monitoring
   of care quality, trend analysis and performance improvement for
   patients with TBI

Polytrauma Marker:

-  Updates the Functional Independence Measure

-  Addresses special needs of polytrauma patients

-  Provides alerts and reminders and supports consistent management,
   reporting, and displaying of important patient characteristics

-  DoD/VA BHIE-CDR (Theater) Interface

-  Provides an interface to OIF/OEF data stored in DoD’s Theater Medical
   Data System (TMDS) using the BHIE framework

-  ICD-10 code compliant

Joint Patient Tracking Application (JPTA) / Veterans Tracking
Application (VTA):

-  Gives VA providers access to critical patient information from the
   theater of operations in DoD’s JPTA system

-  Establishes a link to Veterans Tracking Application (VTA) from within
   CPRS and VA’s VistAWeb

Clinical Transfer Form:

-  DoD and VA nurse developed Situation, Background, Assessment,
   Recommendations (S- BAR) document that is a nursing patient hand-off
   used when patients are transferred between agencies

-  DoD Scanning Interface: provides scanned patient record that is
   transmitted as a bookmarked file to a Clinical Document Note is
   created and the scanned file attached. The Clinical Document Note is
   accessible across the VA

.

Health Information Technology Sharing (HITS): Laboratory Data Sharing and Interoperability (LDSI)
-------------------------------------------------------------------------------------------------

**Version**: 5.2

**Namespace:** LR

**Brief Description:** The Laboratory Data Sharing Interoperability
(LDSI) project supports the electronic order entry and real-time lab
results exchange between the Department of Defense (DoD) and the
Department of Veterans Affairs (VA).

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA

**VASI ID:** 1382

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123038/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=75

**Full Description and Features:** LDSI provides laboratory order
portability between selected DoD/VA sites that have local sharing
agreements for laboratory services.

The goals of the project are:

-  To share/coordinate resources to reduce costs and redundancies while
   increasing efficiencies within the two organizations

-  Facilitate electronic exchange of patient information between DoD and
   VA to enhance patient care/delivery

LDSI provides interagency messaging between VA/DoD sites that have a
local sharing agreement for laboratory services (with either VA or DoD
serving as the performing laboratory). LDSI Phase 1 enabled electronic
ordering and results retrieval of chemistry and hematology laboratory
tests between VA and DoD. Phase 2 extends the exchange of ordering and
results data exchange to include anatomic pathology and microbiology
laboratory tests between VA and DoD.

Health Level 7 (HL7) (VistA Messaging)
--------------------------------------

**Version**: 1.6

**Namespace:** HL

**Brief Description:** Health Level Seven (HL7) is an American National
Standards Institute (ANSI) standard messaging protocol that specifies
the set of transactions and encoding rules for electronic data exchange
between health care computer systems.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=8

**Full Description and Features:** In today's health care environment,
computer systems from multiple vendors and at geographically dispersed
sites are used in conjunction with core facility computer systems to
create integrated delivery of information to the end-user. Linking such
systems to exchange data and work together is a non-trivial task,
particularly given the complexity of health care data.

Health Level Seven (HL7) is an American National Standards Institute
(ANSI) standard messaging protocol that specifies the set of
transactions and encoding rules for electronic data exchange between
health care computer systems. HL7 provides an open, standards-based
framework that computer systems can use to exchange health care data
with each other. The HL7 standards development group is directly focused
on health care informatics standards, and cooperates closely with
developers of other standards.

The Veterans Health Information Systems and Technology Architecture
(VistA) HL7 package enables M- based (VistA) applications running on
core facility computer systems to exchange health care information with
other computer systems. It provides messaging services and a single
toolset for M- based VistA applications to create, send, receive, and
process HL7 messages.

Many VistA applications use VistA HL7 to exchange data in HL7 format
with other facilities and/or applications, including Anesthesiology,
Master Veteran Index/Patient Demographics (MVI/PD), Laboratory,
Outpatient Pharmacy, Patient Management System (PMS), Radiology, and
Veteran ID Card (VIC). The VistA HL7 package is also used to integrate
commercial off-the-shelf (COTS) health care applications with M-based
core facility computer systems.

-  Communication: Facilitates Point-to-Point and Publish-and-Subscribe
   messaging between two or more applications; and provides the
   transport mechanism using HL7-supported lower level transmission
   protocols (e.g., Hybrid Lower Level Protocol [HLLP], X3.28, or
   Minimum Lower Level Protocol [MLLP] over Transmission Control
   Protocol / Internet Protocol [TCP/IP]), which provide error detection
   and session control; provides dynamic routing of messages

-  Processing: Queues incoming and outgoing messages for reliable
   messaging; validates HL7 Message Header (MSH) information for all
   incoming messages; and sends HL7 acknowledgment (ACK) messages back
   to sending applications upon message receipt

-  Message Administration: Provides functionality to assist the
   application developer in setting up HL7 interfaces by hiding the
   complex lower level communication; monitors message transmissions
   statuses; and provides reports on pending transmissions and those
   with errors

-  Programming Utilities: Provides the developer with a rich collection
   of Application Program Interfaces (API) to facilitate the creation,
   exchange, and transmission of messages; provides a set of predefined
   variables to use for building HL7 messages/segments; automatically
   creates all HL7 Message Header (MSH) segments; and invokes the
   appropriate application routine to process message data when a
   message is received

   1. .. rubric:: 
         Health Level Seven Optimized (HLO) (VistA Messaging)
         :name: health-level-seven-optimized-hlo-vista-messaging

**Version**: 1.6

**Namespace:** HL

**Brief Description:** Health Level Seven (HL7) is an American National
Standards Institute (ANSI) standard messaging protocol that specifies
the set of transactions and encoding rules for electronic data exchange
between health care computer systems.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=8

**Full Description and Features:** The first released version of VistA
HL7 was 1.5, which supported simple point-to-point HL7 transactions
between VistA and a local commercial off-the-shelf (COTS) system using
Hybrid Lower Layer Protocol (HLLP), and to other VA facilities using VA
MailMan. The initial release of version 1.6 added the ability to
"broadcast" a message to multiple recipients, and provide support for
the X3.28 LLP. A continuing increased demand for additional messaging
services was addressed through enhancements to HL 1.6, released through
patches, which included more complex message routing (dynamic
addressing), and messaging using Minimal Lower Layer Protocol (MLLP)
over Transmission Control Protocol (TCP).

The current release of HLO is a substantial redesign of HL 1.6, is
designed to operate alongside HL 1.6, and provides significantly higher
operating efficiency and the ability to operate with a substantially
decreased system load. In addition, HLO has some enhancements.

Previous applications supported simple point-to-point HL7 transactions
between VistA and a local commercial-off-the-shelf (COTS) system using
Hybrid Lower Layer Protocol (HLLP), which then required transmission to
other VA facilities using VA Mailman. This release added the ability to
"broadcast" a message to multiple recipients, and provide support for
the X3.28 LLP, and additional subsequent patches to this release
addressed continuing increased demand for additional messaging services
through enhancements which included more complex message routing
(dynamic addressing), and messaging using Minimal Lower Layer Protocol
(MLLP) over Transmission Control Protocol (TCP).

Home Based Primary Care (HBPC)
------------------------------

**Version**: 1.0

**Namespace:** HBH

**Brief Description:** The Home Based Primary Care (HBPC) module is
designed to allow for the local entry and verification and data
management of HBPC patient-related data. HBPC was previously referred to
as Hospital Based Home Care (HBHC).

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health

Care

**Business Function Framework Function(s):** Manage Remote Care
Services, Provide Patient Self- Management Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Office of Geriatrics and Extended Care

**VASI ID:** 1330

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122888/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=68

**Full Description and Features:** This local database structure gives
the HBPC program greater accountability for the integrity of its data,
and eliminates the correction cycle previously required to correct data
entry errors at the central database. Each site can now transmit
complete records of HBPC patient information monthly to the Austin
Information Technology Center (AITC) for processing. The AITC will
continue to generate the same quarterly reports - only the source of the
data has changed. This system eliminates the paper reporting system
between medical centers and the AITC database.

-  Provides for the entry and editing of patient evaluations and
   admission/discharge data

-  Provides automatic transmission of data to the central database

-  Allows data validation and correction to be completed at the
   individual medical center prior to transmission to the central
   database

-  Allows for medical center control over the site's HBPC database

-  Enables medical facilities to generate a wide variety of reports
   covering:

-  Visit, admission and discharge data

-  Length of stay

-  Rejections

-  Procedures

-  Census for program, team, case manager, and/or provider

-  Enables the HBPC program manager to control and assess the staff
   workload and organizational characteristics

-  ICD-10 code compliant

-  An additional feature, Medical Foster Care, has been added to HBPC.
   Medical Foster Home (MFH) combines adult foster care in a privately
   owned residence located in the community with Home Based Primary Care
   (HBPC) or Spinal Cord Injury Home Care (SCI-HC). MFH offers an
   alternative to nursing home placement, merging personal care in a
   private home with medical & rehabilitation support from specialized
   VA home care programs. Veterans placed in MFH meet nursing home
   admission criteria and are responsible for MFH charges

   1. .. rubric:: 
         Home Telehealth/Integrated Home Telehealth (IHTA)
         :name: home-telehealthintegrated-home-telehealth-ihta

**Version**: DG V.5.3, WEBI V.11.5

**Namespace:** DGHT, WEBI

**Brief Description:** The goal of the Home Telehealth IT program is to
integrate vendor-supported Home Telehealth services into the VistA
medical information infrastructure. The Home Telehealth program builds
on the excellent existing and evolving VistA system.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Remote Care
Services, Provide Patient Self- Management Services, Provide Ancillary
Services, Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** VHA Telehealth

**VASI ID:** 1359

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123024/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features: **

-  The patient screening process starts with a VistA Consult.

-  The Consult is completed through the standard VistA Progress Note.

-  Patient sign-up is done through a VistA Patient Information
   Management System (PIMS) interface. The care coordinator selects the
   patient name, the supporting vendor, the consult type, the care
   coordinator’s name, and then submits the request. VistA extracts all
   the pertinent patient data and sends a Health Level Seven (HL7)
   Sign-Up • The Consult is completed through the standard VistA
   Progress Note.

-  Patient sign-up is done through a VistA Patient Information
   Management System (PIMS) interface. The care coordinator selects the
   patient name, the supporting vendor, the consult type, the care
   coordinator’s name, and then submits the request. VistA extracts all
   the pertinent patient data and sends a Health Level Seven (HL7)
   Sign-Up message to the vendor server.

-  The care coordinator then uses the vendor software to associate the
   home device with the patient record on the vendor system.

-  Measurement data gathered by devices in the veteran’s home are stored
   in the vendor server and available for review, and are sent to the
   VA’s Health Data Repository (HDR) using HL7 messages sent through the
   VistA Interface Engine (VIE) Infrastructure.

-  The Home Telehealth data in the HDR along with VistA data from
   facility VistA systems is viewed using VistAWeb, which is available
   through the Computerized Patient Records System (CPRS) by using the
   Remote Data View (RDV) function.

-  Monthly, vendor servers send HL7 messages to the Sign-Up VistA
   facility for the Care Coordinator to review draft progress notes
   summarizing patient activity from the previous month.

This functionality involves components on the vendor servers as well as
several VistA packages including Consults, PIMS for sign up, Progress
Notes, TIU, VIE, Master Veteran Index (MVI), HDR, Clinical Data Services
(CDS), Clinical Context Object Workgroup (CCOW) for patient context,
VistAWeb, and CPRS. Network connectivity must be available to allow
these various components to operate and communicate. VistAWeb, MVI, HDR,
and CDS reside at the national level. The rest of the components are
installed at the facility level.

-  Activate patient for HT care

-  Reports available in VHA Support Service Center (VSSC)

-  Reports available in IHTA website

   1. .. rubric:: 
         Homeless Management Information (HMIS)
         :name: homeless-management-information-hmis

**Version**: 1.0

**Namespace: **

**Brief Description:** Homeless Management Information System (HMIS)
collects and stores longitudinal, person-level information about persons
who access the Department’s homeless service system.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1333

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122890/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** Homeless Management Information
System (HMIS) is a software application designed as part of the 13 Major
Initiatives to record and store client-level information on the
characteristics and service needs of homeless persons. HMIS is a
web-based software application that homeless assistance providers use to
coordinate care, manage their operations, and better serve their
clients.

-  HMIS implementation presents communities with an opportunity to
   re-examine how homeless services are provided in their community, and
   to make informed decisions, and develop appropriate action steps

-  The implementation of HMIS systems varies from community to
   community, examples of local implementation covering the community
   planning process, software selection and implementation are available
   from a variety of communities

   1. .. rubric:: 
         Hospital Inquiry (HINQ)
         :name: hospital-inquiry-hinq

**Version**: 4.0

**Namespace:** DVB

**Brief Description:** The Hospital Inquiry (HINQ) module provides the
capability to request and obtain veteran eligibility data via the VA
National Telecommunications Network. Individual or group requests are
sent from a local computer to a remote Veterans Benefits Administration
(VBA) computer where veteran information is stored. The VBA network that
supports HINQ is composed of four computer systems located in regional
VA payment centers.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care

**Business Function Framework Function(s):** Provide Member Access

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Chief Business Office

**VASI ID:** 1860

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123280/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=41

**Full Description and Features:** HINQ interfaces with other modules to
allow users to make eligibility requests. An on-line suspense file
stores requests for later transmission and records HINQ responses, thus
creating a log of HINQ activity.The HINQ module provides facilities with
the ability to obtain veteran eligibility information quickly,
accurately, and efficiently, allowing medical center personnel to act
expeditiously on patient requests for medical treatment and other
benefits. Additionally, returned HINQ data may be loaded directly into
the local Patient file through various screens. The screens display both
the data in the HINQ message and what is currently in the Patient file
for comparison.

-  Sends on-line requests individually and forwards multiple requests in
   a batch mode

-  Tracks and updates various requests from customer

-  Establishes ‘real-time’ links between VHA and VBA computers to
   service time-of-the-essence requests

-  Processes routine requests in background, allowing the requester to
   perform other tasks

-  Alerts the requester when responses are received from VBA computers

-  Alerts the requester when there is a discrepancy found between the
   returned HINQ information and what is in the Patient file

-  Provides the capability to update returned HINQ data directly into
   the Patient file

   1. .. rubric:: 
         Identity Management (IdM) Service
         :name: identity-management-idm-service

**Version**: 1.0

**Namespace:** N/A

**Brief Description:** The Identity Management (IdM) Service Program
provides technical support and development for the management of the
identity of persons for the Department of Veterans Affairs.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1510

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122981/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=181

**Full Description and Features:** Identity Management Service (IdMS)
comprises Organization Service (OS) and Person Service (PS) and its
peripheral applications and services, Person Service Identity Management
(PSIM), Person Service Demographics (PSD), Person Service Lookup (PSL),
and Identity Management Data Quality Toolkit (IMDQ TK). Identity
Management provides the ability to effectively maintain and share unique
identifiers across the enterprise to improve health care delivery and
data, as well as eliminate inappropriate merges of patient data.

Organization Service (OS) is the authoritative source for organizations,
location, and medical device information for VistA. Currently, Common
Services/Organization Service (CS/OS) v3.0 builds on CS/OS v1 .0 and
v2.0 functionality for the enumeration of medical facilities for Health
Insurance Portability and Accountability Act (HIPAA), and development of
the following architecturally significant features:

-  Enumeration, Relationship, and Point-In-Time Management

-  Graphical User Interface

-  Common Services/Person Service (CS/PS) provides a consistent
   interface for accessing and maintenance of crosscutting person
   administrative information to a trusted set of client applications
   and services. In doing so, CS/PS is the authoritative source for
   person identification in the Veterans Health Administration (VHA)
   domain

-  The sub-services of Common Services/Person Service include:

   -  Person Service Identity Management (PSIM)

   -  Identity Management Data Quality Toolkit (IMDQ TK)

   -  PS Demographics (PSD)

   -  Person Service Construct (PSC)

   -  Person Service Lookup (PSL)

   1. .. rubric:: 
         Income Verification Match (IVM)
         :name: income-verification-match-ivm

**Version**: 2.0

**Namespace:** IVM

**Brief Description:** The Income Verification Match (IVM) module is
designed to extract patient-reported data and transmit it to the
Enrollment System (ES). IVM allows the Veterans Health Administration
(VHA) to accurately assess a patient’s eligibility for health care and
other benefits to which they are entitled.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care

**Business Function Framework Function(s):** Provide Member Access

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1964

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123382/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=44

**Full Description and Features:** IVM provides all of the functionality
required to complete the eligibility verification process at an
enterprise level. The IVM application provides the necessary interface
to allow the exchange of data between the VA Medical Centers (VAMCs) in
near real-time.

-  Transmits data for basic demographics, next-of-kin, income, temporary
   address, eligibility, guardian, military service, and employer
   information to the HEC for patients who are entered into the VAMC
   database

   -  Automatically transmits an updated message if this information is
      changed

-  Allows the HEC to query the medical facility for the most up-to-date
   patient information

-  Allows a VA Medical Center (VAMC) to query ES for the most up-to-date
   data

-  Allows updated demographic and insurance information from the HEC to
   be uploaded into the patient’s record

-  Automatically loads updated income information from the HEC
   (including IVM Converted financial tests) and updates the veteran’s
   eligibility for health care

-  Allows generation of status inquiries, statistical Means Test and
   data transmission reports

   1. .. rubric:: 
         Incomplete Records Tracking (IRT)
         :name: incomplete-records-tracking-irt

**Version**: 1.0

**Namespace:** DGJ

**Brief Description:** The Incomplete Records Tracking (IRT) package
provides the medical center the ability to monitor incomplete records.
Interim summaries, discharge summaries, and both inpatient and
outpatient operation reports are tracked. Records may be incomplete or
deficient for one or more of the following reasons - not dictated, not
transcribed, not signed, or not reviewed.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Director, HIM

**VASI ID:** 1804

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123210/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** A list of the deficiencies each site
will track is distributed with the software. These deficiency names and
categories are highlighted on the screen display and are not editable.
Sites may add new deficiencies. Deficiencies that are entered by the
site are not highlighted on the screen display and can be edited.

-  Provides the ability to enter a new or edit an existing incomplete
   record in the IRT tracking system, edit a completed IRT record, and
   delete an IRT entry

-  Allows each site to establish and edit site-specific IRT parameters

-  Produces a variety of statistical reports for a specified date range

   1. .. rubric:: 
         Intake and Output
         :name: intake-and-output

**Version**: 4.0

**Namespace:** GMRY

**Brief Description:** The Intake and Output (I&O) application is
designed to store, in the patient's electronic health record, all
patient intake and output information associated with a hospital stay or
outpatient visit.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** ONS (Office of Nursing Service)

**VASI ID:** 1356

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123022/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=70

**Full Description and Features:** The Intake and Output (I&O) package
is designed to allow entry and storage, in the patient's electronic
health record, all patient intake and output information associated with
a hospital stay or outpatient visit. This application is not

service specific and is currently interfaced with the PIMS, Nursing and
Pharmacy applications.

-  The I&O package allows users to users electronically document patient
   intake (e.g., oral fluids, tube feedings, intravenous fluids,
   irrigations, and other types of intake defined by the facility) and
   patient output (e.g., excreted patient material such as urine,
   nasogastric secretions, emesis, drainage, liquid feces/stool, and
   other types of output defined by the facility)

-  Intake data can be entered through either a quick or detailed route.
   The quick route documents the total fluid consumed. Detailed
   information request the user to enter specific types of fluid intake
   (e.g., orange juice, water, soup) along with the quantity absorbed

-  The Start/Add/DC IV and Maintenance option contains nine protocols
   associated with intravenous therapy:

1. Start IV - Start a new IV line or heparin/saline lock/port

2. Solution: Replace/DC/Convert/Finish Solution - DC current solution
   then replace a new solution to the selected IV line or convert the IV
   according to the user's choice

3. Replace Same Solution - Replace the same solution to a selected IV

4. D/C IV Lock/Port and Site - Remove IV/lock/port from a selected IV
   site

5. Care/Maintenance/Flush - Check site condition, dressing change, tube
   change and flush

6. Add Additional Solution(s) - Add additional solution(s) without
   discontinuing an existing one

7. Restart DC'd IV - Restart an IV with was DC'd due to infiltration or
   other reasons

8. Adjust Infusion Rate - Adjust infusion rate for a selected IV

9. Flush - Flush all IV line(s) for a selected infusion site

-  The software supports documentation of intravenous intake both single
   and multi-lumen catheters

-  The software is interfaced with the IV module of the Pharmacy
   software

-  The following reports are included:

1. Print I/O Summary by Patient (by Shift and Day(s))

2. Print I/O Summary (Midnight to Present)

3. Print I/O Summary (48 Hrs)

4. 24 Hours Itemized Shift Report

5. Intravenous Infusion Flow Sheet

-  The last four reports can be printed for all patients on a ward, for
   patients in selected rooms on a ward, and for an individual patient

-  Patient Intake and Output information is printed on the following
   Nursing application reports:

1. End of Shift Report

2. Vital Signs Record

-  This version of Intake and Output is not interfaced with Health
   Summary or the Order Entry/Results Reporting applications though
   display of the 24 Hour Summary of both Intake and Output displays on
   the coversheet of the CPRS GUI in the Vital Signs box

   1. .. rubric:: 
         Integrated Billing (IB)
         :name: integrated-billing-ib

**Version**: 2.0

**Namespace:** IB

**Brief Description:** The Integrated Billing (IB) software provides all
the features necessary to create first party (patient) and third party
(insurance carriers/Medicare) bills.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage

Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1806

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123212/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=45

**Full Description and Features:** IB allows for the capture,
maintenance, and storage of insurance data including policy information
and related benefits. It provides the ability to electronically transmit
bills to payers with the data required by HIPAA. It also provides the
ability to receive and store electronic 835 Health Care Claim
Payment/Advice. It includes the ability to create printed bills which
can then be mailed to payers who are unable to accept an electronic
claim. A Claims Tracking feature is available to assist utilization
review staff in tracking episodes of care, completing
pre-certifications, completing continued stay reviews, and processing
appeals and denials.

An Automated Biller module provides a process that automatically creates
bills for billable events which can then be finished and authorized by
the billing staff. The IB software also provides many reporting features
that support the billing staff by providing statistics, tracking and
historical information.

This software is highly integrated with other VistA packages. It is
dependent on data from Registration, Scheduling, Outpatient Pharmacy,
Patient Care Encounter (PCE), and Prosthetics to determine billable
events. Bills and charges created in IB are passed to Accounts
Receivable for processing.

-  Tracks events requiring insurance company reviews from the time of
   the actual event until final payment is resolved

-  Provides the ability to setup insurance companies and insurance plans
   and to store all Relevant data associated with each of the group or
   individual plans

-  Modifies made to the Third Party Joint Inquiry option which include
   an Auto-Post Status indicator after the Electronic Remittance Advice
   (ERA) on the TPJI Bill Charges screen

-  Modifies made to the Third Party Joint Inquiry option which include
   detail of an Electronic Explanation of Benefits (EEOB) Deletion on
   the Bill Charges and the Comment History

-  Newly created Subscriber screen will display a side-by-side
   comparison of the Insurance Verification Processor buffer information
   against the patient's Subscriber information found in either the
   Patient File or the Income Person File depending on what the user
   selects at the "Patient Relationship to Subscriber" prompt

-  Newly created Annual Benefits screen will allow the user to
   View/Edit/Save the patient annual benefits found within Annual
   Benefits File

-  A newly created Coverage Limitations screen will allow the user to
   View/Edit/Save the patient coverage limitations data found within
   Plan Coverage Limitations File

-  Modification made to the Type of Plans file to add Master Type of
   Plan file and Master Type of field. The new MASTER TYPE OF PLAN file
   contains the Public Health Data Standards Consortium (PHDSC) Source
   of Payment code. The new MASTER TYPE OF PLAN field provides a method
   of associating TYPE OF PLAN file entries to the national PHDSC
   standard code set

-  A new Copays on Hold List Manager screen will display the copay that
   are on hold based on the filters selected by the user. Functionality
   has also been added to release a copay when the patient does not have
   billable I insurance as well as a copay on hold when the buffer file
   entry has been processed

-  Medical Care Collections Fund (MCCF) Third Party billing and
   collections applications in the VistA information system do not
   segregate the Non-VA care claims from those claims for service
   rendered at Veterans Health Administration (VHA) healthcare
   facilities. Transfer of data from VistA Fee to Integrated Billing
   will improve. It will record Non-VA revenue in a new fund 5287-13 to
   allow separate tracking of these revenues

-  Modification made to the IB package to create proprietary 837 dental
   claims with the data necessary to send FSC a transaction it can map
   to a X12N/005010X224 Health Care Claim (837D) when a user authorizes
   a dental claim. Dental claims will only be Transmitted electronically
   and cannot be printed at this time. This enhancement touched all
   aspects of the claims billing process.

-  Modifications to prevent Outpatient visit copayment charges from
   being created/charged for patients with the national HRfS flag active
   on the date of service.

-  Modifications to the menu option IB CANCEL/EDIT/ADD CHARGES to
   prevent Outpatient visit copayment charges from being added manually
   for patients with the national HRfS flag active on the date of
   service.

-  Modifications to prorate Rx copay amounts paid by patients with the
   national HRfS flag active on the date of service if the supply is for
   less than 30 days.

-  Modification to the menu option IB CANCEL/EDIT/ADD CHARGES for the
   manual process of adding Rx charges to support prorated amounts for
   Rx

   1. .. rubric:: 
         Joint Legacy Viewer (JLV)
         :name: joint-legacy-viewer-jlv

**Version**: 2.3

**Namespace:** JLV

**Brief Description:** The Joint Legacy Viewer (JLV) is a graphical user
interface (GUI) that links the Veteran Affairs (VA) electronic medical
record (EMR) systems with the Department of Defense (DoD) EMR systems.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Common Services

**Business Owner:** Latricia Facundus /Rod Laster

**VASI ID:** 2057

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/150483/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=224

**Full Description and Features:** The Joint Legacy Viewer (JLV) is a
graphical user interface (GUI) that links the Veteran Affairs (VA)
electronic medical record (EMR) systems with the Department of Defense
(DoD) EMR systems. The interface is a front-end web application that
provides a common data view of view-only, real-time patient information
from separate and distinct EMR Systems.

The common data view combines similar data from each health information
system and displays them chronologically on a single screen, eliminating
the need for you to access two separate applications to obtain complete
patient information. All VA/DoD patient data is collated and combined
onto single screens.

As a VA or DoD clinician, you can view patient records through the Joint
Legacy Viewer, which provides all authorized DoD Composite Health Care
System (CHCS) users and VA VistA users with a combined view of DoD/VA
patient record data.

-  Customizable User interface

-  Date Ranges can be modified and saved by user

-  Web based, easy to use interface

-  Requires PIV card

-  JLV access is reviewed and approved by the JLV coordination team

   1. .. rubric:: 
         VistA Infrastructure
         :name: vista-infrastructure

      1. .. rubric:: Capacity Management Tools
            :name: capacity-management-tools

**Version**: 3.0

**Namespace:** KMPD

**Brief Description:** The Capacity Management (CM) Tools software is a
fully automated support tool developed by Capacity Planning (CP)
Service. CM Tools are designed for Information Resource Management (IRM)
and system administrators responsible for the capacity planning
functions at their site, as well as (VistA) software developers.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT

**VASI ID:** 1783

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123319/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=129

**Full Description and Features:** The CM Tools are used to measure
system performance, data growth, Computerized Patient Record System
(CPRS) coversheet load times, option and protocol execution, and provide
various data reports. There are also tools for developers: global
lister, error lister, routine search, and evaluate M code. CM Tools
entails the capture of all Veterans Health Information Systems and
Technology Architecture (VistA) Health Level Seven (HL7) workload
specifics from participating sites. This HL7 workload data is then
summarized on a weekly basis and is automatically transferred via
network mail (i.e., VistA Mailman) to the Capacity Planning (CP)
National Database.The Department of Veterans Affairs (VA) developed the
Capacity Management Tools software in order to obtain more accurate
information regarding the current and future VistA HL7 workload data at
VA sites.On a nightly basis, the CM Tools Background Driver option
automatically compresses the information contained within the CP TIMING
file (#8973.2) into daily statistics. These daily statistics are
converted into an electronic mail message that is automatically
transferred via network mail (i.e., VistA Mailman) and merged into a
Capacity Planning National Database where this data is used for
evaluation purposes.

IRM staff utilizes the options that are available at the site to manage
this software. IRM staff responsible for capacity planning tasks at the
site can use these options to review system workload trends.
Additionally, the IRM staff can review specific VistA HL7 workload data.

-  Provides access to local databases for identification of a veteran’s
   admission, discharge, outpatient treatment, patient care, and other
   information that may require adjudicative actions

-  Reduces overpayments previously caused by lost, misrouted, or
   improperly processed admission notifications

-  Provides on-line status determinations of pending compensation and
   pension examinations (requesting, scheduling, tracking, and updating
   results)

-  Provides RO on-line access to the local databases for the
   confirmation of the propriety of payments based on hospitalization

-  Improves timeliness of the RO benefits adjustment processing

-  Allows medical centers to electronically access sections of the
   Physicians Guide for Disability Evaluation Examinations.Provides
   tracking of insufficiently completed compensation and pension
   examinations

   1. .. rubric:: Clinical Context Object Workgroup
         :name: clinical-context-object-workgroup

**Version**: 4.3

**Namespace:** XWB

**Brief Description:** The Veterans Health Administration uses CCOW to
share patient and user context between applications. Clinical Context
Management is a method used to synchronize multiple GUI clinical
computer applications to one subject, for example, the same patient.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA OHI

**VASI ID:** 1114

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122822/c/56/nt/-1?id=1578

**VDL Link:**
https://www.va.gov/vdl/documents/Clinical/Pharm-Bar_Code_Med_Admin_(BCMA)/psb_3_um_appendixc_ccow_r0806.pdf

**Full Description and Features:** Clinical Content Object Workgroup
(CCOW), more commonly known as Clinical Context Management, enables the
clinical end-user to experience the simplicity of interacting with one
system, when in reality he or she may be using multiple independent
applications through varying interfaces.

Clinical Context Management is a method used to synchronize multiple GUI
clinical computer applications to one subject, for example, the same
patient. Standard subjects include Patient, User, Encounter,
Observation, and DICOM (Digital Imaging Communications in Medicine)
type.

CCOW ensures secure and consistent access to patient data from varied
sources. Benefits include applications that are easier to use,
utilization of electronically available information, and an increase in
patient safety. CCOW support for secure context management provides for
HIPAA compliant communications and patient coordination.

Kernel
------

**Version**: 8.0

**Namespace:** XU

**Brief Description:** Kernel provides a portability layer between the
underlying operating system and application code.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=10

**Full Description and Features:** Kernel provides a portability layer
between the underlying operating system and application code. This
results in the entire Veterans Health Information Systems and Technology
Architecture (VistA) system being portable among different computers,
operating systems, and M implementations. This, together with the
database portability provided by VA FileMan, eliminates the cost of
application conversions each time VHA changes its computing platforms.
Kernel also offers shared services for VistA applications, resulting in
reduced development costs and a common user interface, and provides
system management tools for managing VistA computer systems. Integrated
Single Sign-on: The RPC Broker supports a single sign-on point from a
client workstation to the server. Users need only sign on once when
accessing multiple VistA applications on the same workstation.

-  **ZOSF/ZOSV Operating System Interface:** The core of Kernel’s
   portability layer. Insulates applications from being tied to any
   particular hardware platform, operating system, or M implementation

-  **Sign-on and Security Management:** Controls user access by device,
   time, and day of week; controls user access to programs, menus,
   files, fields, and devices; audits by user, device, program, file,
   and field; and provides electronic signature capability

-  **Menu Manager:** Manages all application menus to provide a standard
   user environment; customizes menus for individual users; shares or
   restricts menus to a user or a set of users; provides secure
   delegation of menu management authority; and delivers priority system
   alerts

-  **Error Processing:** Provides a consistent method for recording and
   processing application errors

-  **Device Handler:** Defines generic terminal types to reuse for
   similar peripherals; supports host files in layered operating system
   environments; insulates programmers from device- and operating
   system-specific coding; and provides standard user device selection
   across different environments

-  **Task Manager:** Provides flexible background job scheduling; allows
   users to control their own tasks; and permits specification of
   device, priority, and time of execution

-  **Kernel Installation and Distribution System (KIDS, namespace
   XPD):** Provides a mechanism to create a distribution of packages and
   patches; allows distribution via a Mailman message or a host file;
   and allows queuing the installation of a distribution for off- hours

-  **Library Functions:** Provides Date, String, Mathematical,
   Hyperbolic Trigonometric Measurement and Utility functions

-  **Domain Name Resolution:** Provides an Application Program Interface
   (API) to resolve domain names into an Internet Protocol (IP) address

-  **Kernel Delphi Components (KDC):** Provides developers with the
   capability to develop VistA client/server software. These
   Delphi-based components enable client applications to communicate and
   exchange Kernel-related data with VistA M Servers (e.g. alerts and
   date/time)

   1. .. rubric:: 
         Kernel Authentication & Authorization for Java 2 Enterprise
         Edition (KAAJEE)
         :name: kernel-authentication-authorization-for-java-2-enterprise-edition-kaajee

**Version**: 1.1

**Namespace:** XU

**Brief Description:** Kernel Authentication & Authorization for Java 2
Enterprise Edition (KAAJEE) addresses the Authentication and
Authorization (AA) needs of VistA Web-based applications in the J2EE
environment.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=151

**Full Description and Features:** Kernel Authentication & Authorization
for Java 2 Enterprise Edition (KAAJEE) for Web-based HealtheVet
applications on WebLogic 9.2 and higher, such as Pharmacy Re-Engineering
(PRE), provides user authentication to grant access to applications, and
retrieves VistA security keys for application authorization. KAAJEE
takes advantage of the current user store in VistA to authenticate users
in new HealtheVet applications. Considered an interim solution, KAAJEE
will be enhanced to provide the connection to the VA Enterprise user
authentication (signon) system in the future. KAAJEE and FatKAAT use
VistALink as a connectivity solution from J2EE applications to M/VistA.

Like KAAJEE 1.0, KAAJEE 1.1 provides a custom Authentication Provider
"plug-in" for BEA WebLogic J2EE servers, including a set of web forms
for web applications that allow web applications to authenticate and
authorize an end-user using a Kernel system as the source of
authentication and authorization.

Kernel Delphi Components (KDC)
------------------------------

**Version**: 1.0

**Namespace:** KDC

**Brief Description:** This version of the Kernel Delphi Components
provides programmers with the capability to develop and deploy new VistA
client/server software using the Kernel Delphi Components in the 32-bit
environment.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=127

**Full Description and Features:** Version 1.0 of the Kernel Delphi
Components (KDC) provides programmers with the capability to develop new
VistA client/server software using the various Kernel Delphi Components
in the 32-bit environment.

-  Client-side Delphi Components for Kernel

-  Programming Language: MUMPS, Delphi.

-  Deployment Infrastructure: Varies by location.

-  Depends On: VistA 1.0 (FileMan, FileMan Delphi Components (FMDC),
   Kernel, Kernel Toolkit, Remote Procedure Call (RPC) Broker)

   1. .. rubric:: 
         Kernel Toolkit
         :name: kernel-toolkit

**Version**: 7.3

**Namespace:** XT

**Brief Description:** Kernel Toolkit (also referred to as "Toolkit")
supplements the Kernel software package. It provides Development and
Quality Assessment Tools and System Management Utilities.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1626

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123247/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=12

**Full Description and Features:** Kernel Toolkit (also referred to as
"Toolkit" supplements the Kernel software package. It provides
Development and Quality Assessment Tools and System Management
Utilities.

Development and Quality Assessment Tools

-  Promote standard programmer interfaces

-  Provide programmer and systems management

-  Provide a portable routine and global editor

-  Check adherence to programming standards and correct syntax with the
   XINDEX tool

-  Provide support for data standardization

-  Provide standard error trapping, storing, and reporting

-  Support quality assessment tools for the comparison of routines and
   data dictionaries

-  Provide software project management utilities

-  Provide tools to work with data in Extensible Markup Language (XML)

-  System Management Utilities

-  Customize and tune site parameters for local requirements

-  Provide a Multi-Term Lookup Utility for enhanced VA FileMan lookups

-  Provide PARAMETERS file (#8989.5) for user-specific to system-level
   tracking of parameter values

   1. .. rubric:: 
         Kernel Unwinder
         :name: kernel-unwinder

**Version**: 7.1

**Namespace:** XQOR

**Brief Description:** The Kernel Unwinder is a utility that is used in
conjunction with the Protocol file (#101) to create modular building
blocks for applications.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=13

**Full Description and Features:** The Unwinder is a utility that is
used in conjunction with the Protocol file (#101) to create modular
building blocks for applications.

The Unwinder allows hierarchical traversing of menus, as found in Menu
Management, and also the structuring of order protocols into
independent, reusable modules. Each node becomes a "building block" from
which more sophisticated modules may be built. For instance, the node
"Order Shirt" may have as sub-items, "Get Size," "Get Color," "Get
Style," and "Get Delivery Date." Each of these sub-items may, in turn,
be used to build other modules.

-  Provisions have been made to allow additional building blocks to be
   placed at the item level of the node. Their purpose is to allow
   modifying actions to be executed and thus increase the flexibility of
   each module.

   1. .. rubric:: List Manager
         :name: list-manager

**Version**: 1.0

**Namespace:** VALM

**Brief Description:** The List Manager was developed to provide an
efficient way for applications to present a list of items to the user
for action.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=14

**Full Description and Features:** The List Manager was developed to
provide an efficient way for applications to present a list of items to
the user for action. It is a developmental tool that enables programmers
to:

• Display a list of items to the user.

• Allow the user to browse back and forth through the items one at a
time or by screen.

• Allow the user to select items from the list.

• Specify the actions that can be applied to selected items from the
list.

• Call List Manager again as part of an action.

Protocols are the "actions" that users can take against items on the
list. A number of standard protocols come as part of the List Manager
utility. Most of these are actions that allow the user to browse the
list of items. The List Manager contains the Workbench programmer
utility, which allows the development of a List Manager application
without having to move from one development tool to another.

Mailman
-------

**Version**: 8.0

**Namespace:** XM

**Brief Description:** The VistA Mailman software is designed to allow
users to send and receive mail from individuals or groups electronically
through communication lines, modems, and other networks.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA and OIT Infrastructure and Security Services
(ISS)

**VASI ID:** 1817

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123288/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=15

**Full Description and Features:** The VistA Mailman software is
designed to allow users to send and receive mail from individuals or
groups electronically through communication lines, modems, and other
networks. These electronic mail messages (i.e., e-mail) can range from
personal letters to formal bulletins extracting data from VA FileMan.
Mailman is an electronic messaging system that transmits messages,
computer programs, data dictionaries, and data between users and
applications located at the same or at different facilities. Network
Mailman disseminates information across any communications medium.When
Mailman is integrated into an application, it notifies individuals and
groups about important events. From VA FileMan, a change in the value of
a field can trigger a message called a bulletin. Mailman is easy for the
user to learn and to use and provides extensive online help. There is
also an extensive set of Mailman Application Program Interfaces (API)
for the developer.

-  Delivery options set by user (e.g., individuals, mail groups,
   devices; staggered delivery)

-  Chained responses, managed automatically and available for review by
   all recipients

-  Configurable interface

-  Mail basket organization

-  Mail filtering

-  Search capabilities

-  Reminders and notifications

-  Secure messages

-  Surrogate capability

-  Software message processing

-  Software code transport (Whole modules and patches for installation
   at remote sites are sent in Kernel Installation and Distribution
   [KIDS] PackMan messages.)

-  Network transmissions over TCP/IP (Transmission Control
   Protocol/Internet Protocol) channels to any Simple Mail Transfer
   Protocol (SMTP)-compatible mail system

-  Statistics Collection

-  Domain Name Service (DNS) (creates automatic replication of IP
   address changes to every VistA Mailman system)

   1. .. rubric:: M-to-M Broker
         :name: m-to-m-broker

**Version**:

**Namespace:** XWB

**Brief Description:** This software broker allows M (also known as
"MUMPS") computer program instances on different servers to communicate
with each other to transfer data and business rules.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT Health Systems Design & Development
(HSD&D), Infrastructure & Security Services (ISS)

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=128

**Full Description and Features:** The VistA M-to-M Broker is a new
implementation aspect of the RPC (Remote Procedure Call) Broker offering
Client/Server functionality resident solely within a VistA non-Graphical
User Interface (non-GUI) environment. It enables the exchange of VistA
M-based data and business rules between two VistA M servers, where both
servers reside on local and/or remote VistA systems:

-  The requesting server functions in the capacity of a Client

-  The server receiving that request functions in the capacity of a
   Server

The Client/Server roles of each server can vary depending on what point
in time each VistA M server is making the request for data from its
counterpart VistA M server.

Note: Also see Remote Procedure Call Broker (RPC).

National Patch Module (NPM)
---------------------------

**Version**: 2.3

**Namespace:** A1AE

**Brief Description:** The National Patch Module Guide describes the
purpose, roles, responsibilities, and steps for the initiation,
development, and entry of patches to VHA Information Systems and
Technology Architecture (VistA) products via the National Patch Module
(NPM).

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA Release Board and OIT

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=20

**Full Description and Features:** The National Patch Module (NPM)
software provides a database for the distribution of software patches
and updates to Veterans Health Information Systems and Technology
Architecture (VistA).

Options are provided for:

-  Systematic entry and review of patches by developers

-  Review and completion of patches by Software Quality Assurance (SQA)

-  Review and release of patches by Health Product Support (HPS)

-  Display and distribution of the verified/released patches to the
   users in the field

Once a problem is identified and a solution found or an enhancement is
requested in VistA software, a developer enters a patch in the NPM. The
patch is identified by software namespace, version, and a patch number.
At this point, the patch entry has a status of "UNDER DEVELOPMENT" and
is accessible only by other developers of the software. Once the
developer has finished coding the patch and it's ready for review, SQA
reviews the patch. Once SQA has reviewed the patch and no changes are
required, SQA changes the status to "COMPLETED/UNVERIFIED." After the
patch is completed, EVS reviews the patch. Once EVS makes the
determination that it is ready for release, application
coordinators/release agent change the status to "VERIFIED."

The patch is then automatically distributed and becomes available for
users in the field.

Creates a patch mail message with text and installable routines that is
delivered to all the sites via network mail. It allows entry of
associated (dependent) patches (i.e., those patches that must be
reviewed and installed prior to the current patch).

Provides flags to:

-  Identify which routines in a patch have previous patches

-  Hold verification/release of a patch until a certain date

-  Force sequential verification/release of associated patches

Provides numerous reports including:

-  Verified patches and summaries

-  Completed/unverified patches for a selected package

-  Under development patches for a selected package

-  Provides automatic notification of new released patches

-  Provides ability to copy information from an existing patch into a
   new patch

   1. .. rubric:: Resource Usage Monitor (RUM)
         :name: resource-usage-monitor-rum

**Version**: 2.0

**Namespace:** KMPR

**Brief Description:** The Resource Usage Monitor (RUM) software is
intended for use by staff responsible for the capacity planning
functions at their respective facilities. RUM software provides Veterans
Health Information Systems and Technology Architecture (VistA) option
workload information.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=130

**Full Description and Features:** Menus and options are provided
locally at the respective sites to allow staff to accomplish and monitor
workload/usage information. Data collection activities in RUM obtain
system and VistA option information from the each site and automatically
transfer this data via network mail to the Capacity Planning National
Database. RUM provides information regarding current and future VistA
workload at VA sites.

Single Sign On/User Context (SSO/UC)
------------------------------------

**Version**:

**Namespace:** XU

**Brief Description:** Single sign-on (SSO) service with interfaces to
VistA and non-VistA systems.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Techonolgy Services

**VHA Portfolio:** Common Services

**Business Owner:** OIT & VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=162

**Full Description and Features:** The goal of the Single Sign-on/User
Context (SSO/UC) Project is to provide secure single sign-on
architecture. This architecture allows users to authenticate and sign on
to multiple applications that are Clinical Content Object Workgroup
(CCOWenabled and SSO/UC-aware using a single set of credentials, which
will reduce the need for multiple IDs and passwords in the VistA
clinician desktop environment. SSO capability is implemented within the
framework of the HL7 CCOW User Context standard.

The CCOW User Context standard:

-  Is a standard of the HL7 standards body

-  Provides coordination among client healthcare applications, allowing
   them to synchronize around several CCOW subjects and share context
   (e.g., Patient, Encounter, and User Context)

-  Ensures secure and consistent context management

   1. .. rubric:: 
         SQL Interface (SQLI)
         :name: sql-interface-sqli

**Version**:

**Namespace:** DI

**Brief Description:** SQL Interface (SQLI) projects all of the
information needed by M-to-SQL vendors to access VA FileMan through
M-to-SQL products.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=25

**Full Description and Features:** Recommend removal of this as it is a
part of VA Fileman, if we feel it needs to say I recommend we add as
either sub-section of VA Fileman or simply add some level of detail on
this to VA Fileman entry.

-  Programming Language: MUMPS

-  Deployment Infrastructure: Varies by location

-  Depends on: VistA 1.0, Kernel, Kernel Taskman, Fileman

-  The following packages depend on SQL Interface (SQLI): VistA 1.0,
   Medical Domain Web Services (MDWS)

   1. .. rubric:: Statistical Analysis of Global Growth (SAGG)
         :name: statistical-analysis-of-global-growth-sagg

**Version**: 2.0

**Namespace:** KMPS

**Brief Description:** The Veterans Health Administration (VHA)
developed the Statistical Analysis of Global Growth (SAGG) software in
order to obtain more accurate information regarding the current and
future Veterans Health Information Systems and Technology Architecture
(VistA) database growth rates at the VA Medical Centers (VAMCs).

**Business Function Framework Line(s) of Business:** Managing Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=115

**Full Description and Features:** The Statistical Analysis of Global
Growth (SAGG) software in order to obtain more accurate information
regarding the current and future Veterans Health Information Systems and
Technology Architecture (VistA) database growth rates at the VA Medical
Centers (VAMCs).

The Statistical Analysis of Global Growth (SAGG) software is intended to
be used by Information Resource Management (IRM) staff responsible for
the capacity management functions at their facility. The SAGG software
allows the facility to review database, software, and file size
information.

-  The collection task obtains information on the production global,
   software, and file information from the site and automatically
   transfers this data via network mail to the Capacity Planning (CP)
   National Database

-  The information in the CP National Database is fully accessible by
   all sites through the national FORUM system. Menus and options are
   provided nationally giving the site the ability to review the growth
   trends of their database, software, and files

   1. .. rubric:: VA FileMan
         :name: va-fileman

**Version**: 22.2

**Namespace:** DI

**Brief Description:** VA FileMan is the VistA database management
system (DBMS). It runs in any American National Standards Institute
(ANSI) environment. The majority of VHA clinical data is stored in VA
FileMan files and is retrieved and accessed through VA FileMan
Application Program Interfaces (API) and user interfaces.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1786

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123322/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=5

**Full Description and Features:** VA FileMan is the database management
system for the Veterans Health Information Systems and Technology
Architecture (VistA) environment.

For users:

• Standalone user interface for adding, editing, printing, and searching
data

• Form-based editing

• Flexible, extensive report module

• Data interchange with outside applications (import and export tools)

For developers:

• Full support for forms-based interfaces to the database

• Full database access for client-server operations

• Easy scrolling-mode interfaces to the database and full database
access

• Data archiving and transport tools

• Supports keys and compound cross-references

• Performance yielded by the use of M and VA FileMan

• Portability

• Openness

• Native support for Keys and compound cross references

VistA Data Extraction Framework (VDEF)
--------------------------------------

**Version**: 1.0

**Namespace:** VDEF

**Brief Description:** VistA Data Extraction Framework (VDEF) is a VistA
package that uses hard-coded M routines to create and deliver Health
Level 7 (HL7) messages.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=144

**Full Description and Features:** VistA Data Extraction Framework
(VDEF) is a VistA package that uses hard-coded MUMPS (M) routines to
create and deliver Health Level 7 (HL7) messages. The VDEF package
supports queuing requests for messages, control of the timing of message
creation, monitoring of the request queue, and recording of errors
encountered during message creation. The hard-coded programs are M
programs belonging to an application’s namespace. Messages are delivered
using the VistA HL7 package.

The VDEF package supports queuing requests for messages, controls the
timing of message creation, monitors the request queue, and records
errors encountered during message creation. The hard-coded programs are
M programs belonging to an application’s namespace. Messages are
delivered using the VistA HL7 package.

VistALink
---------

**Version**: 1.6

**Namespace:** XOBV

**Brief Description:** VistALink enables applications to communicate
with VistA/M systems. It provides a synchronous communication mechanism
from Java-based applications to M.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1844

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123414/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=163

**Full Description and Features:** VistALink consists of an M-side
listener and Java-side adapter libraries compliant with the J2EE
Connectors specification for Enterprise Information System (EIS)
adapters. VistALink comports to system architecture requirements, and
supplements other alternatives for communication between M-based and
JAVA-based applications, including Remote Procedure Call (RPC) Broke,
HL7 interface messaging software, and Web Services.

-  Client/Server connectivity from Java client to M

-  J2EE Application Server connectivity to M—Supports applications and
   services running on a J2EE application server, enabling them to
   initiate a call to an M server and execute RPCs.

-  Implements the Java 2 Enterprise Edition (J2EE) Connectors
   specification

-  Supports VistA modules requiring this communication capability,
   including Patient Advocate Tracking System (PATS), Veterans Personal
   Finance System (VPFS) and Blind Rehabilitation

   1. .. rubric:: XML Parser
         :name: xml-parser

**Version**: 1.1

**Namespace:** MXML

**Brief Description:** The VistA Extensible Markup Language (XML) Parser
is a full-featured, validating XML parser designed to interface with the
VistA suite of M-based applications. It is not a standalone product.
Rather, it acts as a server application that can provide XML parsing
capabilities to any client application that subscribes to the XML Parser
application programmer interface (API) implementations.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1871

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123352/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=137

**Full Description and Features:** The VistA Extensible Markup Language
(XML) Parser is a full-featured, validating XML parser written in the M
programming language and designed to interface with the VistA suite of
M-based applications. It is not a standalone product. Rather, it acts as
a server application that can provide XML parsing capabilities to any
client application that subscribes to the application programmer
interface (API) specification detailed in this document.

The VistA XML Parser employs two very different API implementations. The
first is an event-driven interface that is modeled after the widely used
Simple API for XML (SAX) interface specification. In this
implementation, a client application provides a special handler for each
parsing event of interest. When the client invokes the parser, it
conveys not only the document to be parsed, but also the entry points
for each of its event handlers. As the parser progresses through the
document, it invokes the client’s handlers for each parsing event for
which a handler has been registered.

The second API implementation is based on the World Wide Web Consortium
(W3C’s) Document Object Model (DOM) specification. This API, which is
actually built on top of the event-driven interface, first constructs an
in-memory model of the fully parsed document. It then provides methods
to navigate through and extract information from the parsed document.

Programming Language: MUMPS

Deployment Infrastructure: Varies by location

Depends On: VistA 1.0, FileMan, Kernel, Kernel Toolkit

The following packages depend on XML Parser:

-  Clinical Case Registries

-  Compensation Pension Records Interchange (CAPRI)/Automated Medical
   Information Exchange (AMIE)

-  Health Data Informatics

-  Oncology

-  Data Management (PDM)

-  Remote Procedure Call (RPC) Broker

-  VistALink

-  VistA Blood Establishment Computer Software (VBECS)

   1. .. rubric:: 
         VistA Laboratory
         :name: vista-laboratory

      1. .. rubric:: Laboratory
            :name: laboratory

**Version**: 5.2

**Namespace:** LR and LA

**Brief Description:** The VistA Laboratory module is a clinically
oriented system designed to provide lab data to health care personnel.
It assists the Pathology and Laboratory Medicine Service (P&LMS) in
managing and automating the workload and reporting process.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Provide Ancillary Services, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1381

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123037/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=71

**Full Description and Features:** The Laboratory module supports the
following areas: General Laboratory, Microbiology, Histology, Cytology
Autopsy and Electron Microscopy. Additionally, activity-specific VistA
applications exist for the following Laboratory areas, and they are
explained in more detail in individual write-ups immediately following
this one:

-  Anatomic Pathology (including Surgical Pathology, and Electron
   Microscopy)

-  Electronic Data Interchange (LEDI)

-  Emerging Pathogens Initiative (EPI)

-  HOWDY Computerized Login Process

-  National Laboratory Tests (NLT) Documents and LOINC coding for lab
   tests

-  Point of Care (POC)

-  Universal Interface (UI)

-  VistA Blood Establishment Computer Software (VBECS)

Phlebotomy/Ordering

-  Interfaces with Computerized Patient Record System (CPRS)

-  Supports ward order entry

-  Prints collection lists and labels and supports barcode printing

-  Provides maximum ordering frequency (e.g., daily, user-defined
   limits)

-  Supports immediate request for blood specimen collection

Processing

-  Provides work lists by urgency and accession number
   (instrument-specific)

-  Produces lists of incomplete, workload/data capture reports, and
   lists for verification of data

-  Supports uni-directional and bi-directional Instrument interfac

-  Supports automatic download to automated instruments including Point
   of Care devices

-  Supports via Laboratory Electronic Data Interchange (LEDI) a
   bidirectional interface that allows for ordering and processing of
   laboratory tests "VA to VA", "VA to DoD", and "VA to Commercial
   Reference Laboratory" for all areas of the clinical laboratory
   (excepting Blood Bank)

Verification/Release of Data

-  Provides Delta Checks, flagging high/low/critical results

-  Presents critical values to the technologist in reverse video

-  Supports review/verification by group or individual accessions

-  Provides various on-screen alerts

-  Automated electronic result message generation via LEDI

Reports

-  Produces supervisory management, audit trail, data integrity, quality
   management and utilization review reports

-  Provides searches for specific antibiotic with defined antimicrobial
   patterns

-  Supports automatic transmission of verified data to the ordering
   location

-  Provides quality control/search capabilities (e.g., critical values,
   high/low values and Systemized Nomenclature of Medicine—Clinical
   Terms [SNOMED CT®])

-  Produces reports for Laboratory Management Information Program

-  Produces and transmits roll-up reports to national LMIP database

-  Produces site-customized management reports

Data Extracts Capabilities for External Databases:

-  Laboratory Management Index Program workload data

-  Laboratory Workload for Decision Support System

-  Hepatitis C clinical information

-  Emerging Pathogen clinical data, antimicrobial trend, infection
   control, and Health Department reports

-  CPT codes are passed to Patient Care Encounter (PCE) for outpatient
   workload

-  LEDI messages to remote Laboratory Information Systems (LIS)

-  ICD-10 code compliant

   1. .. rubric:: 
         Anatomic Pathology (AP)
         :name: anatomic-pathology-ap

**Version**: 5.2

**Namespace:** LR

**Brief Description:** The VistA Laboratory Anatomic Pathology module
automates record keeping and reporting for all areas of Anatomic
Pathology (i.e., Surgical Pathology (SP), Cytopathology, Electron
Microscopy (EM), and Autopsy).

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Provide Ancillary Services, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1810

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123215/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=72

**Full Description and Features:** The module provides valuable quality
management features, increases productivity, provides comprehensive
search and reporting capabilities, and facilitates the gathering of
workload statistics.

Provides quality management features, including:

-  Access to historical pathology data during microscopic examination of
   current specimens

-  Lists of incomplete cytopathology, surgical pathology, EM, and
   autopsy reports

-  Turnaround time reports for all anatomic pathology sections

-  Generation of defined groups of cases requiring additional review, as
   defined by the accrediting agencies

-  Compilation of all information (e.g., special stains,
   immunopathology, or electron microscopy studies) in a single
   cumulative patient summary

-  On-command printing of laboratory test results of specified tests

-  Tracking outcomes of Quality Management review

Increases productivity through:

-  On-line access to historical anatomic pathology data (diagnosis and
   Systemized Nomenclature of Medicine: Clinical Terms SNOMED CT®] codes
   only)

-  Immediate availability of information regarding surgical pathology,
   cytology, electron microscopy specimens, and autopsy

-  Access to verified/released reports by non-laboratory personnel

-  Generation of labels for both specimens and slides

-  Interface with Voice Recognition Systems

Provides comprehensive searching/reporting capabilities, including:

-  Final pathology, autopsy, cytology, and EM reports

-  A log of all specimens accessioned, including final diagnoses

A variety of reports based on morphology, procedure, and etiology
disease field entries, including:

-  List of patients with a particular diagnosis.

-  List of specimens from a particular site.

-  List of specimens from a particular procedure (e.g., biopsies, frozen
   sections).

Provides workload statistics for:

-  Number of specimens accessioned by area

-  Number of blocks, slides, and stains prepared

   1. .. rubric:: 
         Blood Bank
         :name: blood-bank

**Version**: 5.2

**Namespace:** LR

**Brief Description:** Maintains and supports VHA Blood Bank medical
devices that are compliant with Food and Drug Administration (FDA)
Quality System Regulations and manufacturing Code of Federal Regulations
(CFR). Oversight and compliance with Blood Bank business needs as
pertains to supporting the software system.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Ancillary Services,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1811

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123216/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=74

**Full Description and Features:** This module is DISABLED FOR NEW DATA
ENTRY.

Legacy transfusion records however are available for review.

VistA Blood Establishment Computer Software (VBECS) replaces and
supersedes VistA Blood Bank v5.2 for blood bank operations. VistA Blood
Bank v5.2 blood unit records remaining after the transfer of patient
information to VBECS are available for reference only and are not
editable.

Emerging Pathogens Initiative (EPI)
-----------------------------------

**Version**: 5.2

**Namespace:** LR

**Brief Description:** Under the auspices of the Program Office for
Infectious Diseases VAHQ , the Laboratory Emerging Pathogens Initiative
(EPI) software package allows the Department of Veterans Affairs (DVA)
to track Emerging Pathogens on a national level without the necessity
for additional local data entry.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1221

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122901/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=118

**Full Description and Features:** Using this objective information,
plans can be formulated on the national level for intervention
strategies and resource needs. Results of aggregate data can also be
shared with appropriate public health authorities for planning on the
national level for the non-VA and private health care sectors.

The Laboratory EPI program is designed to automatically provide data on
emerging pathogens to Veterans Affairs Headquarters (VAHQ) without
additional individual data entry at the site level. The data will be
sent to Austin Information Technology Center (AITC) for initial
processing and coupling with denominator data related to workload. VAHQ
data retrieval and analysis can then be accomplished.

-  Identify Emerging Pathogens

-  Extract specific data associated with the Emerging Pathogen

-  Transmit data to AITC

-  Create national SAS data sets for Infectious Diseases Program Office
   access

   1. .. rubric:: 
         HOWDY Computerized Login Process
         :name: howdy-computerized-login-process

**Version**: 5.2

**Namespace:** LR

**Brief Description:** Howdy is a Class 3 to Class 1 which introduced a
computerized phlebotomy login process called "howdy" as an automated
laboratory check-in application which can be used within the VistA
Laboratory module.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=194

**Full Description and Features:** This software performs the following
functions:

Allows the veteran patient to slip his/her ID card via a card reader and
the software identifies the patient, Welcomes them, and pulls up the
patient orders do be drawn. The Orders are accessioned, labels are
printed and the patient is drawn reducing the wait times for our
veterans in the clinic.

-  Howdy automates laboratory check-in, accessioning of orders, and
   printing of specimen labels

-  Howdy captures collection process times and provides the information
   required to create phlebotomy performance reports

-  Howdy eliminates the need for a hand-written log book for sign-in
   where the patient's name and SSN can be compromised

-  Howdy can utilize bar code technology to assist in the process of
   patient and specimen identification

   1. .. rubric:: 
         Laboratory Electronic Data Interchange (LEDI)
         :name: laboratory-electronic-data-interchange-ledi

**Version**: 5.2

**Namespace:** LR

**Brief Description:** Laboratory Electronic Data Interchange (LEDI)
supports the electronic order entry and real-time laboratory results
retrieval between VA, DoD, and commercial reference laboratories.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1383

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123039/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=75

**Full Description and Features:** LEDI uses HL7 messaging providing
communication between VA, DoD, and commercial labs that have a local
sharing agreement for laboratory services. VAMC and DOD facilities can
be identified as either a HOST site or a COLLECTION site. Reference labs
are always a HOST site.

LEDI has enabled electronic ordering and results retrieval of general
laboratory tests between VA and DoD. It also provides reference labs to
transmit data back to the VAMC. Microbiology data can also be sent and
received. Anatomic Pathology can only transmit orders via a manifest.

-  Software was demonstrated in El Paso (El Paso Veterans Affairs
   Healthcare System/William Beaumont Army Medical Center) and San
   Antonio (South Texas VA Healthcare System/Wilford Hall Medical
   Center, Brooke Army Medical Center) and is available to the VA
   Enterprise.

-  Phase 2 extends the exchange of ordering and results retrieval data
   to microbiology laboratory tests between VA and DoD (with either VA
   or DoD serving as the performing laboratory). Anatomic Pathology
   orders only can be sent to the host facility.

   1. .. rubric:: 
         National Laboratory Tests (NLT) Documents and LOINC® Request
         Form
         :name: national-laboratory-tests-nlt-documents-and-loinc-request-form

**Version**: 5.2

**Namespace:** LR

**Brief Description:** The National Laboratory Test Documents establish
a standard coding across documents in an effort to unite laboratory
records.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1822

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123293/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=119

**Full Description and Features:** The benefit of this mapping effort is
to provide a way to support multiple normal ranges based on test,
method, specimen, sex, and patient age. The structure will allow
multiple normal ranges within the same laboratory with differing
equipment or methods for doing the same procedure. The final product
(the normal range, critical high, critical low, reporting units, and
method) will be stored with each individual result. Creation of new Data
Names for normal range change will be eliminated.benefit of this mapping
effort is to provide a way to support multiple normal ranges based on
test, method, specimen, sex, and patient age. The structure will allow
multiple normal ranges within the same laboratory with differing
equipment or methods for doing the same procedure. The final product
(the normal range, critical high, critical low, reporting units, and
method) will be stored with each individual result. Creation of new Data
Names for normal range change will be eliminated.

Point of Care (POC)
-------------------

**Version**: 5.2

**Namespace:** LR

**Brief Description:** The VistA Laboratory Point of Care (POC) supports
the Laboratory Health Level 7 (HL7) Point of Care (POC) interface. Point
of Care systems usually consist of a POC device, a docking station and a
server which is configured to connect to VistA.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1812

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123217/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=149

**Full Description and Features:** POC utilizes existing functionality
provided by Laboratory Universal Interface (UI) and Laboratory
Electronic Data Interchange (LEDI) software. The software supports the
transmission, processing and storing of POC TEST RESULTS in the VistA
Laboratory package. The ability of POC interfaces to subscribe to VistA
HL7 Admissions, Discharge, Transfer (ADT) messages for patient
demographics and location information is provided as needed. Support for
5 separate POC interfaces is provided. Additional interfaces can be
added locally when naming of additional interfaces are in conformance to
name spacing instructions. POC is a type of interface that downloads and
stores results for a bed side analyzer/device or any instrument that
performs laboratory testing at the site of care (examination, treatment,
diagnosis, etc.). The accession and verification procedures are modified
to accommodate POC type of data storage. POC results are not verified by
the traditional laboratory methods.

-  Identifies testing facility’s name and address for every POC test on
   the laboratory report

-  Tags each result to identify the person performing the testing on the
   laboratory report

-  Enhances Laboratory Supervisor Summary reports to also display the
   name of the POC operator who generated the results. This will
   eliminate the need to store this information as comments

-  Stores the Equipment Instance Identifier (EII) will with the results

-  Expands business rules for laboratory orders to facilitate detection
   of discrepancies by the provider responsible for the patient’s care

   1. .. rubric:: 
         Universal Interface
         :name: universal-interface

**Version**: 2.0

**Namespace:** LA

**Brief Description:** The Laboratory Universal Interface (UI) is
designed to make the process of interfacing automated instruments
easier, faster, and more reliable.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Heath Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1813

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123285/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=120

**Full Description and Features:** Laboratory UI uses the standard
messaging protocol Health Level Seven (HL7) to communicate with all
instruments. HL7 is a standard developed by health care information
systems professionals to simplify the communications between computer
systems that must exchange information. HL7 was adopted by Decentralized
Hospital Computer Program (DHCP) as the primary communications protocol
for messaging between systems and even between applications on the same
system. The laboratory technologist sees very little change between the
Laboratory UI and the traditional interface system. After the Laboratory
Information Manager (LIM) or ADPAC sets up the files and installs the
new hardware, the technologist can accession, build Load/Work lists,
download, and verify the results as usual. The benefit of using the
Laboratory UI is that almost any instrument by any manufacturer can be
interfaced quickly and dependably, in unidirectional or bidirectional
mode. Interfacing is only subject to the limitations of the instrument.

VistA Blood Establishment Computer Software (VBECS)
---------------------------------------------------

**Version**: 1.0

**Namespace:** VBEC

**Brief Description:** The main purpose of VBECS is to automate the
daily processing of blood inventory and patient transfusions in a
hospital transfusion service. VBECS facilitates ongoing compliance with
Food and Drug Administration (FDA) standards for medical devices and
enhances the VA Veterans Health Administration’s (VHA’s) ability to
produce high-quality blood products and services to veterans. The system
follows blood bank standards, standards of national accrediting
agencies, FDA regulations, and VA policies. VBECS is the replacement for
the VistA Blood Bank application.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Ancillary Services,
Manage Health Records, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pathology and Laboratory Medicine Service (P&LMS)

**VASI ID:** 1525

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123502/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=182

**Full Description and Features:** VistA Blood Establishment Computer
Software (VBECS) is the Blood Bank System which replaced the previous
blood bank software (VistA Blood Bank v5.2) at the Department of
Veterans Affairs (VA). The system follows blood bank standards,
standards of national accrediting agencies, FDA regulations, and VA
policies. VBECS is considered a medical device by the FDA (Food and Drug
Administration), which places OI/PD/the Blood Bank Team in the role of
"manufacturer."

VBECS supersedes VistA Blood Bank v5.2 for blood bank operations. VistA
Blood Bank v5.2 blood unit records remaining after the transfer of
patient information to VBECS are available for reference-only and cannot
be edited. VistA Blood Bank v5.2 validation records must be maintained
for five years after the last of the blood unit records is transferred
to VBECS.

-  Interfaces with BCE-PPI Transfusion Verification, VistA Laboratory,
   CPRS order dialog and reports, DSS, and ADT

-  Provides direct data entry user interface supported by business rules
   and truth tables for transfusion related testing

-  Alerts users to testing conflicts, potential contraindications for
   testing and unit selection, and overrides from standard entries
   (requiring explanation to proceed)

-  Provides barcode scanning capability for patient safety and
   technologist efficiency

   1. .. rubric:: 
         Lexicon Utility
         :name: lexicon-utility

**Version**: 2.0

**Namespace:** LEX

**Brief Description:** The VistA Lexicon Utility Version 2.0 is a
dictionary of medical terms which can be used by all clinical areas. It
provides the basis for a common language of terminology so that all
members of a health care team may communicate with each other. It
provides a variety of coding schemes and the ability to update these
coding systems.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** Health Information Management

**VASI ID:** 1814

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123286/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=76

**Full Description and Features:** The Lexicon is a standardized
reference for clinical terminology across VHA that enables clinical
information to be recorded, transmitted, retrieved, and analyzed in a
precise and consistent manner independent of clinic or medical
center.The Lexicon provides a comprehensive Application Program
Interface (API) that enables any application that needs to use
standardized terminology to be able to interface.

At its inception in the early 1990s, the scope of the Lexicon was
limited to expressing diagnostic clinical problems in easy-to-understand
terminology and associating terms to coding systems such as
International Classification of Diseases (ICD), Clinical Modification
(ICD-9-CM), Diagnostic and Statistical Manual of Mental Disorders (DSM),
and the North American Nursing Diagnosis Association (NANDA), and now
includes Clinical Modifications (ICD-10-CM). Over the years, this scope
broadened to provide a general-purpose utility that serves the
terminology needs of many packages, including Problem List (standardized
using SNOMED CT®), Encounter Forms, Text Integration Utility (TIU),
Event Capture, Federal Health Information Exchange (FHIE), and the
Laboratory Data Sharing Interoperability (LDSI) project.

In addition to providing terminology, the Lexicon provides a coding
system update deployment mechanism. A large number of applications,
packages, and services (VistA and external) are now dependent on the
quarterly updates including:

-  Integrated Billing

-  Fee Basis

-  Automated Information Collection System (AICS)

-  Laboratory

-  Dental

-  Prosthetics

-  Mental Health

-  Radiology

-  Surgery

-  Registration

-  Patient Care Encounter (PCE)

-  Event Capture

-  Quality Audiology and Speech Analysis and Reporting (QUASAR)

-  Home Based Primary Care

-  Clinical Reminders

-  Text Integration Utility (TIU)

-  Laboratory Data Sharing Interoperability (LDSI)

-  Problem List

   1. .. rubric:: 
         Master Patient Index (MPI)
         :name: master-patient-index-mpi

**Version**: 1.0

**Namespace:** MPIF

**Brief Description:** The Master Veteran Index (MVI) database (formerly
known as the Master Patient Index [MPI]) is the primary vehicle for
assigning and maintaining unique patient identifiers. A gateway in VistA
establishes connectivity between VA Medical Center (VAMC) systems and
patient registration processes and links to the MVI for message
processing and patient identification. The MVI was created to support
maintenance of a unique patient identifier and a single master index of
all Veterans Health Administration (VHA) patients and to allow messaging
of patient information among the institutional partners [i.e., VHA,
Veterans Benefits Administration (VBA), Board of Veterans Appeals (BVA),
National Cemetery Service (NCS), and Department of Defense (DoD).] MVI
creates an index that uniquely identifies each active patient treated by
the Veterans Administration, identifies the sites where a patient is
receiving care, and supports crucial sharing of Veteran patient
information across sites.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services, Provide Enterprise Reporting

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1406

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123015/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=16

**Full Description and Features:** The MVI maintains a central index to
correctly identify each patient and track the sites of interest. MVI
data is maintained in a centralized, dynamic database that is available
to meet multiple information needs across many applications and systems.
The MVI central database, located at VA Austin Information Technology
Center, is composed of a unique list of patients and a current list of
systems to which each patient entry is correlated. This enables the
sharing of patient data between operationally diverse systems. Each
record (or index entry) in the MVI contains a small amount of identity
and demographic data used to identify individual entries.

It is primarily used by VistA applications that need to enumerate unique
patients at their facilities. The MVI assigns each patient a unique
patient identifier (Integration Control Number, or ICN). Each index
entry in the MVI also contains the patient's identifying information
(e.g., name, SSN, date of birth, gender) and a current list of
facilities where the patient has been seen. The MVI is updated as new
patients are added or demographic information is updated at the
correlated system.

Changes and updates to patient identity information are accepted based
on an algorithm that determines level of confidence. The Master Veteran
Index Patient Index/Patient Demographics (MVI/PD) was developed to
initialize active patients to the Master Patient Index (MPI) and to
establish the framework for the sharing of patient information between
sites. (The original Master Patient Index VistA (MPI) and Patient
Demographics (PD) software packages were distributed and installed
together.

This software enables sites to:

-  Request an ICN assignment

-  Query the MVI for known data

-  Update the MVI when changes occur to demographic fields stored on the
   index itself or to other facilities and systems of interest

-  Obtain a Treating Facility List of sites where the patient is also
   known by this ICN (Each site becomes part of the network of sites
   that share key demographic data for patients via HL7 messaging

   1. .. rubric:: 
         Maximo (Max)
         :name: maximo-max

**Version**: 7.6.0.9

**Namespace: **

**Brief Description:** The Service Oriented Architecture Research and
Development (SOARD) Maximo Project is a multi-year effort to replace
VA’s existing asset and service management system (AEMS/MERS) with a
single web-based, integrated, enterprise-level system. Maximo provides
life cycle management support for all asset types on a single platform.
It is used to help maximize the value of critical business and IT assets
by enforcing best practices that yield benefits for users of all types
of assets.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Manage VHA-wide Administrative Services, Conduct Supply
Chain Operations, Provide Financial Management

**VHA Portfolio:** Business information

**Business Owner:** VHA Procurement and Logistics Office (PLO)

**VASI ID:** 2065

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/151645/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Maximo system provides the
Veterans Health Administration (VHA) a modernized and integrated asset
management capability. This capability includes the ability to perform
requisitioning, work order management, inventory management, facilities
management, equipment management, and related workforce management. This
capability enhances the VHA's ability to serve Veterans by creating and
maintaining an effective, integrated, administration-wide management
capability to make data-driven decisions, allocate resources, and manage
results.

The Service Oriented Architecture Research and Development (SOARD)
project is deploying IBM's Maximo Enterprise Asset Management Commercial
Off-the-Shelf (COTS) solution. The software is an intranet web-based
application that is entirely contained within the VA Wide Area Network
(WAN). The Maximo product delivers Out of the box (OOB) capabilities,
and only cosmetic changes to screen layout have been tailored to VA
preference. The underlying Oracle database easily accommodates new data
fields, and has been expanded to include relevant VA data fields unique
to our mission (e.g., EIL, CMR, VA MDNS, etc.). Maximo will replace the
textually based “menu tree” navigation in VistA.

Medicine
--------

**Version**: 2.3

**Namespace:** MC

**Brief Description:** The Medicine module serves clinical services and
maximizes the use of the data within VistA VAMC database. The module
allows entry, edit, and viewing of data for many medical tests and
procedures.

**Business Function Framework Line(s) of Business:** Deliver Healthcare

**Business Function Framework Function(s):** Provide Nursing, Provide
Medical Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Clinical Services

**VASI ID:** 1818

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123289/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=77

**Full Description and Features:** The Summary of Patient Procedures
allows the clinician to view a two-line summary of all medical
procedures for each patient. These summaries are most often presented in
descending order from most recent to oldest. Details of the procedures
can be viewed by selecting the summary of interest. Medicine components
include: Cardiology, Pulmonary, Gastrointestinal, Hematology, Pacemaker,
Rheumatology, and Generalized Procedure.

-  Provides a Summary of Patient Procedures for all procedures performed
   on a particular patient with simple drill downs for further
   information. Reports for all procedures are menu options

-  Provides both scroll mode and screen entry features for all
   components and provides word processing-based consult software for
   all procedures

-  Features an extensive screen entry system for Cardiac Catheterization
   Lab, Holter, Electrophysiology, Exercise Tolerance Test, Echo, and
   Electrocardiogram. Standards-based electronic transfer of ECG and
   Holter data to VistA is available

-  Allows the entry and edit of Esophageal Gastroduodenoscopy (EGD),
   Endoscopic Retrograde Cholangiogram and Pancreatogram (ERCP),
   Colonoscopy, and Laparoscopy findings or data

-  Allows the entry, edit, and printing of endoscopic data and Pulmonary
   Function test data

-  Contains a diagnosis filter that allows the separation of primary and
   secondary diagnoses, a consult component, and an
   automatically-generated recall list within both the Gastrointestinal
   and Pulmonary components

-  Allows data entry and edit for Generator and Lead implants, and
   follow-up surveillance within the Pacemaker component. The software
   also permits the direct electronic transfer of a report to the
   National Pacemaker Centers using VA network mail

-  Permits data entry and edit of Bone Marrow Aspirates (BMA) and Bone
   Marrow Biopsies (BMB)

-  Allows the tracking of Rheumatology visits and is based on standards
   developed by the American Rheumatology Associations Medical
   Information System (ARAMIS)

-  ICD-10 code compliant

   1. .. rubric:: 
         Mental Health
         :name: mental-health

**Version**: 5.01

**Namespace:** YS

**Brief Description:** The Mental Health module provides computer
support for both clinical and administrative patient care activities
associated with mental health care.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Medical Services, Manage Health Records, Utilize
Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Mental Health

**VASI ID:** 2172

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/2430185/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=78

**Full Description and Features:** Psychiatrists and psychologists have
directed this VistA module’s design with active input from all health
care disciplines, guided by the principle of creating software that
makes the clinician’s job easier and leads to better patient care. A
by-product of this approach has been the creation of a clinical
database, which is useful to mental health program managers in many
ways, including evaluating clinical productivity, monitoring and
improving the quality of care, and trending various patient care events.
This clinical database package is comprehensive and accessible from
workstations throughout medical facilities.

Provides a mini clinical record that includes:

-  A patient profile with demographic information and a brief index of
   the clinical database, including physical examinations, psychological
   tests, and clinical interviews, problem list, and diagnoses

-  Diagnostic and Statistical Manual of Mental Disorders (DSM-IV) and
   International Classification of Diseases (ICD-9 & ICD-10) diagnoses.
   Psychological test and interview results, reviews of systems, past
   medical histories, crisis notes, clinical patient messages, and
   progress notes

-  A Global Assessment of Functioning (GAF) Case Finder Report, which
   lists all patients that have not been given a GAF score within the
   last 90 days

-  The ability for patients to undergo psychological tests and clinical
   interviews at a workstation, saving considerable clinician time.
   Psychological tests are automatically scored for retrieval, with
   access governed by the guidelines of the American Psychological
   Association

-  VistA Mental Health (MH) Addiction Severity Index Multimedia Version
   (ASI-MV):

-  Provides functionality required to run associated
   commercial-off-the-shelf (COTS) software

-  Allows clinicians and patients to enter demographics and
   self-administered interviews via a workstation using video and audio
   technology

-  Provides the patients with privacy and appropriate time to complete
   an interview

VistA Mental Health Assistant (MHA) Graphical User Interface (GUI):

-  Provides a crash recovery file

-  Displays patient demographics data, which can be printed, copied to
   the Windows clipboard, or saved to a text file

-  Context-sensitive help is available for most items, with suggestions
   for test administration and interpretations

-  Provides a user-friendly interface for entering interview data

-  Enhances the ability of both staff and patients to enter
   psychological test data

-  Creates reports and graphical displays of complex tests by
   sub-category or scales

-  Creates psychological test order windows that display tests that can
   be ordered based on the provider privileges

-  Provides a text report of selected tests and graphs of numeric scores

-  Helps clarify diagnoses and provides empirical measures for treatment
   outcomes

 
-

Methicillin Resistant Staphylococcus Aureus Program Tools (MRSA-PT)
-------------------------------------------------------------------

**Version**: 1.0

**Namespace:** MMRS

**Brief Description:** The MRSA Program Tools (MRSA-PT) application
provides a method to extract data related to MRSA Nares screening,
clinical cultures, and patient movements within the selected facility.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Provide Ancillary Services, Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Office of Primary Care Operations

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=189

**Full Description and Features:** MRSA-PT contains reports that will
extract and consolidate required data for entry into the Inpatient
Evaluation Center (IPEC). Reports can also be generated to display
real-time patient specific information, and can be used to identify
patients that have a selected multi-drug resistant organism (MDRO) and
to identify patients who did or did not receive a MRSA Nares screen upon
admission to the unit. Supporting the VHA MRSA Prevention Initiative
directives, this module, once configured at the local VAMC level
provides the following reports which can be used to monitor MRSA:MRSA
IPEC Report: This option allows the user to print the MRSA IPEC Report.
The report can be run for all the locations in a Division or a specific
location.

The report can be run for either Admission (prevalence measures) or
Discharge/Transmission (transmission measures).Isolation Report (Census
List and MDRO History): This option allows the user to print the
Isolation Report for each unit. The Isolation Report includes MDROs
selected in the initial setup and the historical time frame to search
for the last positive result. If sites utilize Isolation Orders, these
will also print on the reportNares Screen Compliance List: This option
allows the user to print a report to capture real-time patient
information on a unit at a specified time to determine if a Nares screen
was obtained upon admission to the unit. This report allows the unit to
determine patients that received (or did not receive) a Nares screen
upon admission.

Mobile Electronic Documentation
-------------------------------

**Version**: 2.3

**Namespace: **

**Brief Description:** Allows staff to access a patient's previously
downloaded electronic medical record information when not connected to
the VA network.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Office of Geriatrics and Extended Care (GEC)

**VASI ID:** NA

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=190

**Full Description and Features:** Mobile Electronic Documentation (MED)
2.3 is a Veterans Health Information Systems and Technology Architecture
(VistA) software application. It enables Department of Veterans Affairs
(VA) staff to access a patient's previously downloaded electronic
medical record information when not connected to the VA network. MED is
designed to work in tandem with the Computerized Patient Record System
(CPRS) as temporary storage of patient notes. This includes the ability
to enter notes using CPRS exported Templates (.txml). MED promotes user
satisfaction and efficiency in the login and documentation process by
allowing access to CPRS at the point of care (POC) and avoiding the
duplicate process of charting handwritten notes at the end of the day.

My HealtheVet
-------------

**Version**: 1.0

**Namespace:** MHV

**Brief Description:** My HealtheVet (MHV) (www.myhealth.va.gov) is VA’s
award-winning Personal Health Record (PHR) online portal. The mission of
MHV is to transform the delivery of health and health care for all
Veterans, independent of where they receive care, by providing one-stop,
online access to better manage their overall health, make informed
health decisions, and record and store important health and military
history information.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Member Access,
Provide Communication and Outreach, Provide Access to Self-Services,
Provide Patient Self-Management Services, Provide Care Management,
Provide Medical Services, Provide Ancillary Services, Manage Health
Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Theresa Hancock

**VASI ID:** 1820

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123291/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=153

**Full Description and Features:** MHV provides access to VA health care
and information 24/7 through web-based tools that empower Veterans to
become active partners in their health care. MHV allows VA patients to
request and receive VA prescription refills and provides a blended
history of VA and self-entered medications. Registrants with an upgraded
Premium account (whose personal identities have been authenticated) can
access copies of key portions of their VA Electronic Health Records,
including VA Appointments, Chemistry/Hematology Lab Results, Allergies
and Wellness Reminders. MHV registrants use the VA "Blue Button" on the
website to view, print or download their available personal health
information.

For VA patients with a Premium My HealtheVet account, this can include
both self-entered information as well as information from the VA
Electronic Health Record (such as VA Notes, lab test results, Problem
List, Allergies, Immunizations, Admissions and Discharge Summaries,
Pathology Reports, etc.), and Military Service Information from the
Department of Defense. Veterans can choose to share their information
with other providers, caregivers, family members or job advocates. VA
patients with a Premium account can also communicate electronically with
their VA health care team using Secure Messaging. All site visitors can
access health education resources, health screening tools, special
mental health resources, and feature articles. My HealtheVet combines
essential health record information enhanced by online health resources.

The online environment maps closely to existing clinical business
practices and extends management and delivery of care. These features
enable and encourage consumer empowerment, patient engagement, and
patient/clinician collaboration. The My HealtheVet system consists of a
national system housed at the Austin information Technology Center
(AITC), and the My HealtheVet Veteran Information System Technology
Architecture (VistA) package. The My HealtheVet system extracts data
from various VistA applications including Laboratory, Outpatient
Pharmacy, Scheduling, Adverse Reaction Tracking, and Clinical Reminders.

National Provider Identifier (NPI)
----------------------------------

**Version**:

**Namespace:** XU

**Brief Description:** The National Provider Identifier (NPI) project
began in 2006 to develop software to support NPI enumeration and
taxonomy codes within the Veterans Health Administration (VHA). The work
supported Public Law 104-191, the Health Insurance Portability and
Accountability Act (HIPAA) of 1996.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Common Services

**Business Owner:** VHA CBO

**VASI ID: **

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** Maintained by Centers for Medicare
and Medicaid Services (CMS), NPI serves as the standard unique health
identifier for health care providers. A ten-position, numeric identifier
used to universally identify trained, licensed individual and
organizational providers of health care services and supplies, NPIs must
be obtained by health care providers who are covered entities. Taxonomy
codes are national specialty codes used by providers to indicate their
specialty at the claim level.

The HIPAA NPI Final Rule requires that covered entities (i.e. health
plans, health care clearinghouses, and those health care providers who
transmit any health information in electronic form in connection with a
transaction for which the Secretary of the Department of Health and
Human Services [HHS] has adopted a standard) use NPIs in standard
transactions by the compliance date of May 23, 2007 for large payers,
and May 23, 2008 for small payers.

Fee Basis

-  The addition of a Referring provider prompt to the user entry and
   edit of fee authorizations

-  Allow display and printing of the Referring provider name on VA
   10-7078 and 10-7079 Authorization Forms and the Referring provider
   NPI on the same forms, given the provider’s permission to disclose it
   to non-VA entities for business reasons.

Integrated Billing

-  Authorization checks, as of May 23, 2008, will not flag an error on a
   claim, preventing it from being submitted, due to a missing taxonomy
   code associated with Attending, Rendering, and Referring providers on
   the claim

-  Allow a given provider’s NPI to be active in both the NEW PERSON file
   (#200) and the IB NON/OTHER VA BILLING PROVIDER file (#355.93) at the
   same time (from Integrated Billing’s Provider ID Maintenance option)

Accounts Receivable

-  Modifications to the 835 message from Austin to VistA. This includes
   the addition of rendering/servicing provider’s name and NPI, and the
   billing provider’s NPI to the Account Receivables’ Electronic
   Explanation of Benefits (EEOB) Work list

Kernel

-  Allow a given provider’s NPI to be active in both the NEW PERSON file
   (#200) and the IB NON/OTHER VA BILLING PROVIDER file (#355.93) at the
   same time (from Kernel’s Add/Edit NPI Values for Providers option)

-  Implement a flag to capture a provider’s permission to share his or
   her NPI with non- VA entities for business purposes other than those
   covered in currently established Routine Use provisions

-  Improvements to the reports generated by the List of NPI data for CBO
   option and the Print Local NPI Reports option

-  As of December 15, 2010 The Chief Business Office schedules an NPI
   Crosswalk Extract report periodically (typically once a month) from
   all Veteran's Administration provider sites. The scheduling of this
   report is done via the VA NPI Crosswalk Extract -Administration web
   site using HL7 messages. The NPI Crosswalk Extract process is
   automated and runs in the background at each site

   1. .. rubric:: 
         National Utilization Management Integration (NUMI)
         :name: national-utilization-management-integration-numi

**Version**: 1.1.14.3

**Namespace:** WEBN

**Brief Description:** The National Utilization Management Integration
(NUMI) application is a web-based Quality Assurance (QA) application
that allows QA nurses to assess and document the effectiveness of
inpatient care for each inpatient on a daily basis. NUMI integrates a
commercial-off-the-shelf (COTS) software application [Care Enhancement
Management Enterprise (CERMe)] with additional NUMI features specific to
VAMC's, and admission/transfer/discharge data retrieved from VistA.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Monitor Clinical
Performance, Provide Financial Management, Provide Enterprise Reporting

**VHA Portfolio: **

**Business Owner:** Office of Quality, Safety, and Value

**VASI ID:** 1453

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122967/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=184

**Full Description and Features:** NUMI provides electronic access to
evidence-based criteria that assists hospital staff in the management of
inpatient admissions. The NUMI application retrieves data directly from
VistA, eliminating redundancy and errors from re-entering patient
records and information. NUMI was established to meet a specific
business need of the Office of Quality, Safety and Value (OQSV) to
provide automated support to field Utilization Management nurses who
perform reviews of clinical care activities. These utilization reviews
are considered core procedures to support both quality improvement and
business/compliance functions central to VA’s mission. Utilization
Management and Utilization Review staff review multiple significant
events in a patient’s care (admission, transfer, discharge, major
procedures), assessing such patient management decisions against
established clinical guidelines.

The NUMI application provides the capability for local, regional and
national documenting of the following utilization review activities:

• Place patient in the most appropriate level of care

• Identify and remove system barriers to providing the right care at the
right time, and at the right cost

• Automate the retrieval of patient information for the UM review
process

• Modify the initial acceptance criteria

• Create a log with information about events in a patient record

• Display a list of patient records with filters and search features for
each review

• Provide reasons for meeting or not meeting (UM) criteria

• Enter information ("reminders") about actions to be performed in the
future

• Provide the acceptable reports to comply with VSSC reporting
requirements

• Maintain the data such as Facility, Provider Outcomes, and Reason
codes

NUMI is deployed at the Austin Information Technology Center (AITC).

Network Health Exchange (NHE)
-----------------------------

**Version**: 5.1

**Namespace:** AFJX

**Brief Description:** Network Health Exchange (NHE) is a Veterans
Health Information Systems and Technology Architecture (VistA) module
that provides clinicians quick and easy access to patients' information
from any VA medical facility where a patients has received care.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Manage Health Records

**VHA Portfolio:** Common Services

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=79

**Full Description and Features:** The NHE package accesses information
concerning clinic visits, diagnoses, prescriptions, laboratory tests,
radiology exams, and hospital admissions. It enables clinicians to
request medical or pharmacy records for a patient from a single site or
several sites. NHE obtains Health Summary information through an
interface with the Health Summary VistA module. NHE uses predefined
formats, thus requiring less input by the user and resulting in simpler,
faster access to patient data. Patient data is displayed in a format
similar to that of Health Summary and can be viewed on-screen or
printed.

-  Simple User Interface: Users simply select the data type (Clinical or
   only Pharmacy data) and the amount of patient data they would like
   returned (all data or 12 months only), and then enter the patient’s
   name or Social Security Number to initiate the request for data from
   another VA facility

-  Retrieval and Printing of Patient Data: Retrieved patient data
   (Clinical Record or Pharmacy information, either a comprehensive
   history or activity only within the last 12 months) can be printed or
   viewed on-screen

-  Quick Response: NHE is fully automated and user requests are
   generally fulfilled in a matter of minutes

-  Data Returned in Health Summary Format: Patient data is returned in
   an NHE mail message, formatted similarly to the Health Summary,
   beginning with patient demographics, followed by categorized medical
   information, and indicating the name of the VA facility where the
   data resides

-  User Notification with Alerts: The user requesting patient data via
   NHE is notified of data receipt through an alert that appears within
   the menu system

-  Purging Retrieved Patient Data: To allow sites to control disk space
   usage, NHE provides an option to purge the retrieved patient data
   messages nightly

-  Special Security Features: This system is intended for use by health
   professionals who have direct patient care responsibilities and have
   need for clinical information. NHE generates a bulletin if data is
   requested from a sensitive patient record. The bulletin is directed
   to the same user group that currently reviews notices about access to
   sensitive patient records

-  Package Management: The availability of NHE options is based on the
   level of menu access granted to each user

   1. .. rubric:: 
         Nursing
         :name: nursing

**Version**: 4.0

**Namespace:** NUR

**Brief Description:** The Nursing application is a component of the
Department of Veterans Affairs VistA program. It is comprised of
multiple modules (i.e., Administration, Clinical, Education, Performance
Improvement, and Research).

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver HealthCare, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Maintain Care Practitioners and Providers Information,
Monitor Clinical Performance, Provide Patient and Family Care Education,
Provide Clinical Decision Support, Provide Care Management, Manage Human
Resources

**VHA Portfolio:** Health Provider Systems

**Business Owner:** ONS (Office of Nursing Service)

**VASI ID:** 1465

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122978/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=80

**Full Description and Features:** Nursing is comprised of multiple
modules (Administration, Clinical, Education, Performance Improvement,
andResearch).

**Administration:**

1. Personnel management information (demographic and professional data
   of nursing staff)

2. Resource management/analysis tracking for reports on budgeting DRGs,
   overtime usage, patient care hours, supply equipment projections, and
   staffing hours

3. Mandatory reports (i.e., AMIS 1106, AMIS 1106a, Annual Report)

-  Tracks staff information including: personal/demographic data,
   previous professional experience, work assignments, grade, licensure,
   certification, professional education, end of probationary period,
   and military reserve status

-  Uses a Position Control file to monitor past, current, and future
   nursing positions, future vacancies, reason for vacancy, start/stop
   dates for the position, and the level of employee filing the
   position. When a registered nurse's assignment is changed, the
   professional experience in the staff record is automatically updated

-  Generates management reports on employees including: academic and
   professional degrees, grade statistics, age trends, gender trends,
   license renewals, certification statistics, active reservist lists,
   LPN and RN NPSB tracking, and proficiency tracking

-  Provides resource management reports on ward/service FTEE statistics
   as well as ward and bed section workload/variance reports. The option
   which prints current workload reports can generate data on both the
   current and next tours of duty

-  Accumulates daily statistics on the number of patients treated in the
   following bed sections: hemodialysis, drug/alcohol patients, recovery
   room and domiciliary

-  Generate daily, monthly, quarterly, and yearly AMIS Reports: 1106b
   (FTEE Budgeted/Actual), 1106 (Patient Classification), and 1106a
   (Manhours)

-  Provides a workload statistics based on AMIS data

-  Provides a telephone list of employees by service or location

-  Provides miscellaneous patient acuity report

**Clinical:**

1. Patient classification

2. Patient assessment

3. Nursing care plans which are system focused and contain both nursing
   problems and medical diagnoses

4. Patient care assignments

5. Clinical protocols/guidelines for care

6. Patient education material

7. Discharge planning

8. Other patient related medical record data

-  Contains a patient classification system which generates reports by
   bed section and ward

-  Includes nationally developed standard nursing care plans for
   initiating patient care plan generation

-  Allows nurses to generate a patient care plan based on patient
   problems, identified goals, and specified nursing interventions. The
   software accommodates evaluation and resolution dates for problems,
   identifies target and met dates for goals, and discontinuation dates
   for interventions/orders

-  Produces two types of assignment worksheets for each patient (brief
   and complete). The brief worksheet does not display selected care
   plan information

-  Contains an option for printing a ward census by room and provides
   information on current patient location

-  Generates reports for unclassified patients and provides a function
   for classifying unclassified patients only

-  Allows a staff nurse to update a patient's nursing ward location
   and/or nursing AMIS bed section to insure accurate patient
   classification entries

-  Allows users to generate a Health Summary Report by patient or ward

**Education:**

1. Education reports (i.e., mandatory inservice attendance, continuing
   education attendance, authorized absence/funding analysis

2. Student affiliation information (i.e., scheduling of student clinical
   labs, affiliation agreements)

-  Tracks employee continuing education data

-  Prints AA/Funding Requests Reports which indicate money authorized
   for C.E. attendance by specified year

-  Tracks mandatory inservice information for multiple years.
   Information on program attendance can be provided by last attendance
   date or for three full fiscal years. Deficiency reports are available
   for the current or past three fiscal year

**Performance Improvement:**

1. QA problem tracking system

2. Infection control trends

3. Patient incident analysis

4. Employee accident analysis

5. Continuous care monitors (clinical data)

6. Administrative monitors (e.g., safety equipment)

-  Contains options for reviewing patient classification and tracking
   errors

-  Allows QA staff and ADP coordinators to revise erroneous AMIS data

-  Tracks units with no manhours data

**Research:**

1. Resource listing of VA nurse researchers

2. Additional functionalities as defined by the Nursing Focus Group

**Package Management:**

-  Allows sites to modify data (e.g., service positions, salary,
   grade/step codes, mandatory inservices, certifications, nursing
   locations, tour of duty) in specified nursing files

-  Accommodates additional site-specific standard care plans

-  Provides special ADP Coordinator functions for executing nursing
   options which affect patient acuity, manhours, FTEE status, etc.,
   when TaskMan is off-line

-  Provides ADP Coordinator options for
   admitting/transferring/discharging patient within the Nursing system
   when the MAS System is off-line. This feature ensure that patient
   information will be updated and available to nursing providers. When
   the package is off-line due to the installation of a new version, the
   software will automatically update the patient in the Nursing system
   by admitting and discharging patients before the system is made
   available to the user

   1. .. rubric:: 
         Nutrition and Food Service (N&FS)
         :name: nutrition-and-food-service-nfs

**Version**: 5.5

**Namespace:** FH

**Brief Description:** The Nutrition and Food Service (N&FS) software
integrates the automation of many Clinical Nutrition, Food Management,
and Management Reports functions. The Clinical N&FS activities of
Nutrition Screening, Nutrition Assessment, Diet Order Entry, Tube
Feeding and Supplemental Feeding Orders, Patient Food Preferences,
Specific Diet Pattern Calculations, Nutrient Analysis of meals, Consult
Reporting, Encounter Tracking, and Quality Care Monitoring are all
available in this program.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care

**Business Function Framework Function(s):** Manage Health Care Costs
and Administrative Efficiency, Provide Clinical Decision Support,
Provide Medical Services, Provide Ancillary Services, Manage Health
Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Nutrition and Food Service

**VASI ID:** 1466

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122979/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=67

**Full Description and Features:** The Food Management function has
complete automation of food production activities; Service and
Distribution, Inventory and Cost Management, Recipe Expansion, Menu and
Recipe Nutrient Analysis, Meal and Diet Pattern Development and
Implementation, Diet Card and Tray Ticket Printing and Quality Service
Tracking are available. The Management Reports include the Served Meals,
Additional Meals, Cost per Meal, Tube Feeding Cost, Supplemental Feeding
Cost, Staffing Data, Encounter Data, and Annual Management Reports.

-  Allows the building of a site-specific listing of patient food
   preferences that can be incorporated in meal production calculations
   and the printed diet card and tray tickets programs

-  Manages patients' requests or dietary requirements for specific food
   items or utensils, allowing the selection of standing orders for any
   patient, for any meal or quantity.

-  Controls all aspects of ingredient usage

-  Develops a list of site-specific recipes that includes portion size,
   preparation area and time,equipment and serving utensils, recipe
   category, ingredients, and directions for preparation. Recipes can be
   quickly analyzed for their nutrient value

-  Creates multiple meals and menu cycles. Meals can be used in
   different patterns by creating menu cycles or by creating special
   holiday dates within a cycle. It allows for the nutrient analysis of
   meals or daily/weekly menus

-  Controls quantities produced in the Food Management program. Specific
   patient diet orders are reorganized into production diets and diet
   patterns that reflect the foods to be served. This information is
   used along with data from the meal file to generate production
   reports, diet cards and/or tray tickets. A forecasting tool also
   exists in the section that allows the manager to anticipate, by
   percentage of total census, the type and quantity of various
   production diets that will be needed by any selected service point

-  Allows the entry of information required by the Annual Report that is
   not automatically retrieved from the program

-  Prints a patient-specific record of all diet order entry information.

-  Controls the order entry activity

-  Manages food items and their nutrients using the latest USDA data,
   food items from sources such as Bowes and Church, and additional data
   from research

-  Handles N&FS consults and allows the reassignment of active consults
   from one staff member to another

-  Manages the supplemental feeding food items and menus. A supplemental
   feeding menu automatically goes into effect at the time of diet order
   entry and changes automatically with new orders

   1. .. rubric:: 
         Occupational Health Recordkeeping System (OHRS)
         :name: occupational-health-recordkeeping-system-ohrs

**Version**: 1.4

**Namespace:** OHRS

**Brief Description:** VA built the web-based Occupational Health
Recordkeeping System (OHRS) to electronically document, track and report
health information on VA employees, volunteers and others who work in VA
facilities, and to document care provided to other Federal agency
employees.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1467

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123152/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=186

**Full Description and Features:** OHRS enables occupational health
staff to create, maintain, and monitor medical records for VA employees
and generate national, VISN, and site-specific reports.

VA clinical staff involved in administering seasonal and H1N1 flu
vaccine to VA staff and other Federal agency employees must use OHRS to:

• Document vaccination administration

• Track persons who need vaccinations

• Report on vaccination and immunity status

VA staff can access OHRS through the VA Clinical Information Support
System (CISS) portal. OHRS is locally hosted within the Clinical
Information Support System (CISS) application. Hence, it is hosted
nationally at Austin Automation Center. Ongoing OHRS work covers
requirements, deployment, architecting, data portioning, and technology.

Occurrence Screen
-----------------

**Version**: 3.0

**Namespace:** QAO

**Brief Description:** The Occurrence Screen module supports VHA policy
by identifying patients' clinical events requiring follow-up review. It
generates worksheets used by clinical, peer, management, and
committee-level reviewers and identifies practitioner, systems, and
equipment- related problems and results.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration

**Business Function Framework Function(s):** Perform Hospital
Administration

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Patient Care Services

**VASI ID:** 1826

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123296/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=49

**Full Description and Features:** The Occurrence Screen (OS)
application is a component of the Quality/Risk Management subsystem
within the Veterans Health Information Systems and Technology
Architecture (VistA) system. It is designed to be used as a tool to
automate the gathering of Occurrence Screen data. This is accomplished
by a nightly run of the automatic enrollment program, which captures
patients meeting criteria for screens 101.1, 102, and 107. The
identified data is called "fallout".

OS automates the creation of clinical, peer, management, and committee
worksheets. The findings and/or actions of the previous review levels
can be printed. It facilitates tracking of occurrences through various
reports, including a Semi-Annual Summary of Occurrence Screening. An ad
hoc report feature is included for use in trend analysis.

The Occurrence Screen software gathers and manipulates data for the
following nationally released screens:

A. Readmission within 10 days (Screen 101.1)

Justified exceptions excluded by the software:

-  Scheduled readmission

-  Prior discharge AMA (against medical advice) or Irregular

-  Readmission to CLC, Intermediate Medicine, or Domiciliary

Justified exceptions that cannot be excluded by the software:

-  Readmission for alcohol or drug abuse, chemotherapy, or radiation
   therapy

-  Condition precipitating readmission didn't exist at time of prior
   admission

A. Admission within 3 days following unscheduled Ambulatory Care visit
   (Screen 102)

Justified exceptions excluded by the software:

-  Scheduled admission

-  Admission same day as visit

-  Admission to Psychiatry Service, CLC, Intermediate Medicine, or
   Domiciliary

C. Return to OR in same admission (Screen 107)

Justified exceptions excluded by the software:

-  Two operations separated by more than 7 days

-  Second procedure unrelated to first

-  Planned multiple stage procedure documented prior to first surgery
   (when the case is scheduled prior to the first surgery)

Justified exceptions that cannot be excluded by the software:

-  Planned multiple stage procedure documented prior to first surgery
   (when the case is not scheduled prior to the first surgery)

-  Second operation in response to findings from first procedure

-  Provisions exist for the addition of other hospital-specific screens
   to be created locally, but manual identification and data entry are
   needed to maintain them. National screens that were discontinued
   through policy changes are listed in the package as "Inactive" but
   may be made "Local" to reactivate them.

-  A nightly data screening program looks back over the last 24 hours of
   patient activity and identifies patient events that meet criteria in
   screens 101.1, 102 and 107. The events found are called "fallout"
   data and a report is generated.

-  Allows configuration of hospital-specific screens. Fallout must be
   identified and entered manually for locally-created screens.

-  Automates the creation of clinical, peer, management, and committee
   worksheets. The findings and/or actions of the previous review levels
   can be printed.

-  Facilitates the tracking of occurrences by various tracking reports.
   An ad hoc report feature is included for use in trend analysis.

-  Produces the Semi-Annual Summary of Occurrence Screening.

   1. .. rubric:: 
         Oncology
         :name: oncology

**Version**: 2.2

**Namespace:** ONC

**Brief Description:** The Oncology module automates the tumor registry
and supports tumor registrars in abstracting cancer cases, following up
on cancer patients and producing the Hospital Annual Report. Functions
are grouped according to order of use: Case Finding and Suspense;
Abstracting, Printing and Quality Management; Follow-up; Registry Lists;
Annual Reports; Statistical Reports; and Utilities.

**Business Function Framework Line(s) of Business:** Manage Public
Health, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Epidemiological
Assessments, Provide Medical Registry Service, Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Office of Patient Care Services

**VASI ID:** 1716

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123220/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=81

**Full Description and Features:** The Oncology application functions in
accordance with the current editions of American College of Surgeons
(ACOS) guidance. It contains required data standards and data sets
necessary to bring the tumor registry module into compliance with the
Facility Oncology Registry Data Standards (FORDS) 2011 specifications
approved by the Commission on Cancer (COC); Surveillance, Epidemiology,
and End Results Reporting (SEER) Extent of Disease for site-specific
surgery; International Classification of Disease: Oncology 3rd Edition;
and American Joint Commission on Cancer (AJCC) Manual for the Staging of
Cancer, 1st through 7th Editions.

-  The software supports multi-divisional sites

-  The program automatically finds cases by searching the database from
   Anatomical Pathology (Surgery, Cytology, Electron Microscopy, and
   Autopsy), Radiology, and Patient Treatment File (PTF)). Cases can be
   entered into the Suspense File by date of diagnosis, and chart
   request pull lists can be printed

-  Demographics are drawn directly from Patient Information Management
   System (PIMS) patient file and stored permanently. Cancer
   identification data is obtained from the local database (e.g.,
   laboratory and radiology test results)

-  The program accessions and abstracts with extensive on-line help and
   stages the extent of disease automatically

-  It produces a wide range of follow-up lists and registry lists needed
   for accreditation and allows entry of contacts directly into Oncology
   Contact File

-  Professional letters covering diverse situations and customization of
   letters are available

-  Predefined annual reports can be generated and the user can create
   specialized reports using VA FileMan

-  Reports to the ACOS can be generated using special routines that
   extract data onto floppy disk

-  The same functionality is available for state reporting

-  The database can be customized to suit the individual hospital

-  The full set of TNM codes is included from the appropriate edition of
   the AJCC Manual on Staging of Cancer

-  The program allows on-line completion of Patient Care Evaluations
   (PCEs) during the abstracting function if the case being abstracted
   fulfills the selection criteria for the PCE

   1. .. rubric:: 
         Order Entry/Results Reporting (CPRS)
         :name: order-entryresults-reporting-cprs

**Version**: 3.0

**Namespace:** OR

**Brief Description:** The Computerized Patient Record System V. 1.0
(CPRS) is a Veterans Health Information Systems and Technology
Architecture (VistA) computer application. CPRS enables you to enter,
review, and continuously update allinformation connected with any
patient.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Medical Services and manage health records.

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA HI/CMIO

**VASI ID:** 1828

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123298/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=61

**Full Description and Features:** CPRS allows the user to order lab
tests, medications, diets, radiology tests and procedures, record a
patient’s allergies or adverse reactions to medications, request and
track consults, enter progress notes, diagnoses, and treatments for each
encounter, and enter discharge summaries. CPRS not only allows you to
keep comprehensive patient records, it enables you to review and analyze
the data gathered on any patient in a way that directly supports
clinical decision-making.

OE/RR core module. All basic CPRS tasks occur within the M environment.
Tasks relegated to the GUI workstation include those necessary to
communicate with the server and to present and obtain data.

Specific components of the core M module for OE/RR include:

-  Order processing and storage

-  A mechanism for clinical orderable items

-  Flagged orders

-  Electronic signature

-  Encounter management

-  Patient selection

GUI Interface - Clinical workstations in the Windows environment access
CPRS through a Delphi-based Graphical User Interface (GUI). Based on
years of prototyping, usability studies, and actual clinical use, the
CPRS GUI is a full implementation of results reporting and order entry.
It communicates with CPRS server processes through the Kernel Broker
client-server utility. Data is exchanged via an extensive list of remote
procedure calls.

VAMC Parameters and Defaults - Every VAMC has specialized needs
regarding CPRS functionality and processing. To allow variation and
modification among VAMCs, CPRS provides a hierarchically structured set
of parameters. Each parameter can have a user, team, service/section,
patient location, division, system, and package value.

Patient Care Encounter (PCE)
----------------------------

**Version**: 1.0

**Namespace:** PX

**Brief Description:** Patient Care Encounter (PCE) captures clinical
data resulting from ambulatory care patient encounters. The data
includes captured clinical data documents ("encounters") and related
encounter information, problems treated during the encounter, procedures
done, immunizations, patient education, service connection, and skin
tests.

**Business Function Framework Line(s) of Business:** Deliver Healthcare,
Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records, Provide Enterprise Reporting

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA OIA Health Information Governance

**VASI ID:** 1829

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123299/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=82

**Full Description and Features:** PCE provides a data repository for
long-term clinical data. A goal of PCE is to support many data capture
methods for integrating clinical data from many environments. Pilot
efforts included population of the PCE clinical repository via scanner
technologies and workstations. The key users are clinicians, management,
and quality management personnel. PCE also captures classification
information such as Service Connected (SC) condition, Agent Orange
Exposure, Military Sexual Trauma, Shipboard Hazard and Defense (SHAD),
etc., as these pertain to the specific patient. PCE is vital in
collecting Current Procedural Terminology (CPT) and International
Classification of Diseases (ICD-10) information during patient care
episodes.

-  Acts as VA’s long-term clinical repository, documenting encounters
   from local and non-VA facilities.

-  Provides a primary and secondary clinical visit management utility
   based on appointments and related services.

-  Interfaces with the Health Summary package to provide components
   based on data captured and stored in the PCE clinical repository.

-  Supports capture of outpatient encounter data. Data collection
   methods include:

   -  Interface between scanner/workstation and clinical repository.

   -  On-line data capture using List Manager user interface.

   -  Historical load utilities for lab and outpatient pharmacy.

   1. .. rubric:: 
         Patient Centered Management Module (PCMM Web)
         :name: patient-centered-management-module-pcmm-web

**Version**: 1.19

**Namespace:** WEBP

**Brief Description:** The Patient Centered Management Module (PCMM Web)
allows users to create, manage, and define teams and assign staff to
these teams. This function helps in maintaining accurate listings for
primary care teams and panels.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration

**Business Function Framework Function(s):** Perform Hospital
Administration

**VHA Portfolio: **

**Business Owner:** VHA

**VASI ID:** 1530

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123113/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=211

**Full Description and Features:** The mission of the Department of
Veterans Affairs (VA), the Office of Information and Technology (OIT),
and the Veteran Heath Administration (VHA) is to provide benefits and
services to Veterans of the United States. In meeting these goals, OIT
strives to provide high-quality, effective, and efficient Information
Technology (IT) services to those responsible for providing care to the
Veterans at the point-of-care as well as throughout all the points of
the Veterans’ health care in an effective, timely, and compassionate
manner.

VHA has developed a Primary Care (PC) system that balances productivity
with quality, access, and patient service. Management of patient panels
in PC through mandatory and consistent use of the Patient-Centered
Management Module (PCMM) has supported this system redesign. In a PC
setting and in the Patient-Aligned Care Team (PACT) model, patients are
assigned a Primary Care Provider (PCP) who is responsible for delivering
essential health care, coordinating all health care services, and
serving as the point of access for VA care. The PCP works together with
a team of professionals which includes nurses, pharmacists, social
workers, health care professions, trainees, clerks, and more.

The PCMM Web software is considered to be an important component in
measuring patient demand and PCP capacity to meet that demand, as well
as reduce wait times. It allows users to set up and define treatment
teams, assign positions to the team, assign staff to positions, assign
patients to the team, and assign patients to a PCP. PCMM Web was
developed to assist VA facilities in implementing PC. PCMM Web supports
both PC and non-PC teams. Teams are groups of staff members organized
for a certain purpose.

The PCMM software will be referred to as PCMM Web. It is a National
website and contains data for all sites. It will replace the current
PCMM software accessible on the user’s desktop. An integral part of PCMM
Web is the Data Migration that migrates the data from Legacy PCMM to
PCMM Web. It is accessed via the VA intranet by users who have been
trained and granted access. The main users of PCMM Web are PCMM
Coordinators, Mental Health Treatment Coordinators, Transition and Care
Management Coordinators, and Travelling Veteran Coordinators. PCMM Web
retrieves provider and patient data from VistA via VistALink and
interfaces with the Master Veteran Index via HL7 and Java to validate
each patient’s national identity. PCMM Web synchronizes data back to the
VistA PCMM files so it can continue to be accessed by existing software
that currently utilizes it.

-  Enables a team to be formed based on specific Care Type (i.e.,
   Primary Care, Mental Health) and aligned around a patient, including
   providers across multiple VA sites and in non-VA settings for
   efficient care coordination and communication. Team and Patient
   management is possible through interactive screens with navigation
   links, expandable sections, and actions icons, providing an overall
   view of care coverage and maintenance capabilities.

-  Identifies team members and specialists (VA and non-VA) involved in
   the care of the patient, as well as their contact information and
   provide modalities to facilitate provider-to-provider communication.

-  Enables users to set up and define a healthcare team, assign staff
   and health professionals to positions within the team, assign
   patients to the team, and assign patients to practitioners, including
   trainees. Teams can be grouped together for a larger collaborative
   team.

-  Quickly generates a team based on a modeled configuration for a
   specific team care type with team positions included, eliminating the
   need to manually create each team and position.

-  Supports automated data collection for management metrics and
   analysis related to access, workload, and panel management for
   Multiple PACT functionality at the team level.

-  Patients assigned to Primary Care teams are assigned as “Pending”
   until a Primary Care encounter is verified by a Primary or Secondary
   Provider, who is also a teamlet of the assigned team. The assignment
   then changes to “Active”. If there is an Active assignment and a
   Pending assignment for a patient at the same site and when a
   qualifying PC encounter is detected for the Pending assignment, an
   intra-facility transfer will be executed by the System. The Active
   assignment will be inactivated and the Pending assignment will be
   Activated. The patient can be assigned to the “Team” (i.e., the
   Primary Care Provider and the teamlet inherits the assignment) or to
   the “Associate Provider” that has a valid preceptor relationship
   established.

-  Patient assignments to Primary Care teams are interrogated nightly to
   verify for Automatic Inactivation. An established assignment without
   activity for 24 months is automatically inactivated due to
   inactivity. A new assignment without activity for 12 months is
   automatically inactivated due to inactivity. The PCMM user is
   notified of the pending inactivation three months prior to the
   automatic inactivation. Reports are also available.

-  Identifies and tracks patient assignments across stations. A Multiple
   PACT request enables a patient to be assigned to multiple PACT teams
   as required for care coverage across VA systems. This request
   requires an approval or a denial from all involved stations. Multiple
   assignment requests for the same patient for different stations are
   allowed, but there can only be one active assignment per patient, per
   station at a time.

-  Patients assigned to non-primary care teams (i.e., Mental Health or
   specialty) must be assigned to specific providers within the team.

-  Search capabilities enable a user to quickly search for a patient,
   team, room, group, or staff member for assignment/unassignment
   management through interactive screens and menu options. To expand a
   search outside of PCMM Web, a user can search for a patient through
   VistA.

-  Quickly assign or reassign one or more patient to and from a team or
   a position using a batch process, instead of manually performing the
   tasks one-by-one.

-  Enables clinical reviews and approvals to reinforce status activity
   and assignment management.

-  One or more users at each physical site (i.e., hospital, clinic) in
   the VA hold roles within the PCMM Web application (such as PCMM
   Coordinator, Traveling Veteran Coordinator, VISN Coordinator, and
   National Administrator). Each role has associated access privileges
   which enables the user to perform functions within PCMM Web.

-  Eligible preceptor relationships are managed through team position
   profiles.

-  Manage how reference data displays in PCMM Web by enabling the
   definition of your own reference values.

-  Summarizes alert notifications per station for a user to quickly
   identify alert types and act accordingly.

-  Defines the appropriate team members to receive notifications (i.e.,
   MailMan messages) concerning patient assignments. Notifications are
   sent to all team patients, positions, or preceptors or set as “Do Not
   Send”, indicating no notifications are sent.

-  PCMM Web utilizes Microsoft SQL Report Server for its reporting
   capabilities. Canned and AdHoc reports are available.

   1. .. rubric:: 
         Patient Data Exchange (PDX)
         :name: patient-data-exchange-pdx

**Version**: 1.5

**Namespace:** VAQ

**Brief Description:** Patient Data Exchange (PDX) is a VistA module
designed to electronically request and receive patient demographics,
episodes of care, medications, and diagnostic evaluations from other VA
facilities. Data is retrieved from files at the remote site and is
assembled into a coherent, composite record, greatly enhancing the
quality of care provided for the patient.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1463

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122976/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=22

**Full Description and Features:** PDX allows configuration of a work
group of selected facilities that agree to an automatic data exchange.
For facilities in the work group, data is returned automatically, within
minutes after a request is entered. There are exceptions, however, such
as records that have been flagged as sensitive. Any record that does not
meet the criteria for automatic processing is reviewed and processed
manually.

Once the request is processed, the patient’s record is forwarded to the
requesting facility. The requests and data are moved from one facility
to another using Mailman, VA’s electronic mail utility. The requesting
facility receives administrative, pharmaceutical, and clinical
information that is stored in its files and is available for display or
printing.

-  Electronic data requests for selected patient from other
   facility(ies)

-  Automatic processing, and allows for manual processing for certain
   records, e.g., those flagged as sensitive

-  Capability to send data to a remote site without first receiving a
   request

-  Display/print capability for data received from other facility(ies)

-  Encryption of site-specific patient information

-  Send/request capability for a patient from multiple sites for
   multiple segments

-  Status check on results

-  Display of demographic data received from a remote site, and
   capability to load/edit select demographic data into the local site
   file

   1. .. rubric:: 
         Patient Record Flags (PRF)
         :name: patient-record-flags-prf

**Version**: 1.0

**Namespace:** DGPF

**Brief Description:** The Patient Record Flags (PRF) software provides
users with the ability to create, assign, inactivate, and edit flags,
produce reports, and view patient record flag alerts.

**Business Function Framework Line(s) of Business:** Managing Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems/Business Informatics

**Business Owner:** VHA Chief Business Office (CBO)

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=156

**Full Description and Features:** This VistA module provides the
ability to create, assign, inactivate, edit, produce reports on, and
view patient record flag alerts. Patient record flags are used to alert
VHA medical staff and employees of patients whose behavior, medical
status, or characteristics may pose a threat either to their safety, the
safety of other patients or employees, or which may otherwise compromise
the delivery of quality safe health care.

The use of patient record flags must be strictly controlled and
implemented following VA Directives. Patient record flags are divided
into Category I (national) and Category II (local) flags. Category I
flags are nationally approved and distributed by VHA nationally released
software for implementation by all facilities. Category I flags are
shared across all known treating facilities for the patient utilizing
VistA HL7 messaging, and can only changed or deactivated by the owning
facility. Category II flags are locally established by individual VISNs
or facilities and are not shared between facilities.

-  Flags missing or wandering patients

-  Flags patients with behavioral risks

-  Flags patients who are a threat to themselves or others, or for whom
   delivery of safe health care is compromised

-  Flags patients who are at risk for harm

-  The "owning" facility transmits the flag to other facilities where
   the patient has been treated

-  Flag reviewers belong to a mail group and review incoming Category I
   flag messages, and can continue, inactivate, or delete existing flags

-  Interfaces with Text Integration Utility (TIU) progress notes through
   TIU document definitions specifically related to Patient Record Flags

   1. .. rubric:: 
         Patient Representative
         :name: patient-representative

**Version**: 2.0

**Namespace:** QAC

**Brief Description:** The purpose of the Patient Representative module
is to ensure that VA medical facilities respond to patient needs. The
software tracks and trends compliments and complaints and measures the
facility’s types of complaints as they relate to the Customer Services
Standards and the National Patient Satisfaction Survey.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Provide Health Care Administration , Manage Business
Enabling Services

**Business Function Framework Function(s):** Provide Communications and
Outreach, Manage Customer Relations, Utilize Information Technology
Services , Provide Enterprise Reporting

**VHA Portfolio:** Business Informatics

**Business Owner:** National Veteran Service and Advocacy Program
(NVSAP)

**VASI ID:** 1464

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122977/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=50

**Full Description and Features:** This package supports the Patient
Advocate with the collection and categorization of complaints and
compliments that give the medical center an opportunity to meet and
exceed the customer’s expectations. The issue codes provide the
opportunity to track types of complaints and provide trends of specific
complaints. Included within the issue codes are the Customer Service
Standards.A recent reliability study of the codes has revealed an
exceptionally high reliability in the selection of appropriate codes. To
help with improving perceptions, the tracking program can also extract
data specific for women veterans by eras of service (i.e., Gulf War,
Vietnam) as well as clinic, product line, or services.

-  Entering and editing contact information

-  Sending Reports of Contact via the Alert system

-  Tracking contacts that have responses due

-  Printing various lists, statistical reports, and ad hoc reports

   1. .. rubric:: 
         Pharmacy
         :name: pharmacy

      1. .. rubric:: Automatic Replenishment/Ward Stock (AR/WS)
            :name: automatic-replenishmentward-stock-arws

**Version**: 2.3

**Namespace:** PSGW

**Brief Description:** The Automatic Replenishment/Ward Stock (AR/WS)
package provides a method to track drug distribution and inventory
management within a medical center.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care

**Business Function Framework Function(s):** Conduct Disaster
Preparedness Programs, Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1515

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123252/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=83

**Full Description and Features:** The Automatic Replenishment/Ward
Stock (AR/WS) package provides a method to track drug distribution and
inventory management within a medical center. The AR/WS module is
designed to allow each medical center to adapt the system to its own
needs.

The AR/WS Package:

-  Provides inventory management capabilities for clinical care
   locations and drug crash carts.

-  Allows easy drug item inactivation for inventory locations.

-  Provides tools to develop medication storage areas with lists of
   drugs to be maintained in that area. Drugs are classified by
   inventory type and assigned storage location and stock level.

-  Groups medication storage areas together by inventory group name.
   Grouping may be by location, date (time or frequency of inventory),
   or inventory type.

-  Provides tools to conduct inventory: prints inventory sheets and/or
   pick lists to determine stock to be replenished in medication storage
   areas and, by a selected method, replaces needed inventory items.

-  Maintains backorder totals if a physical inventory is conducted and
   entered into AR/WS software.

-  Provides inventory management reporting capabilities for clinical
   care locations and drug crash carts.

-  Provides ability to select by inventory group on all reports.

-  Supplies a report to fill on-demand requests for out-of-stock items
   or items not part of the standard inventory.

-  Provides various printouts as well as several management statistical
   reports for the creation and maintenance of the system.

   1. .. rubric:: 
         Bar Code Medication Administration (BCMA)
         :name: bar-code-medication-administration-bcma

**Version**: 3.0

**Namespace:** PSB

**Brief Description:** Bar Code Medication Administration (BCMA)
software provides a real-time, point-of- care solution for validating
the administration of Unit Dose (UD) and Intravenous (IV) medications to
inpatients and outpatients in Veterans Administration Medical Centers
(VAMCs).

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver HealthCare, Manage Business Enabling Services.

**Business Function Framework Function(s):** Perform Hospital
Administration, Provide Clinical Decision Support, Provide Medical
Services, Provide Ancillary Services, Manage Health Records,
UtilizeInformation Technology Services.

**VHA Portfolio:** Health Provider Systems

**Business Owner:** OIA/BCMA and PBM

**VASI ID:** 1047

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122714/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=84

**Full Description and Features:** Bar Code Medication Administration
(BCMA) software provides a real-time, point-of- care solution for
validating the administration of Unit Dose (UD) and Intravenous (IV)
medications to inpatients and outpatients in Veterans Administration
Medical Centers (VAMCs). Compiles reports by Patient, Ward or Clinic for
Nursing, Pharmacy, and Information Resources Management (IRM). Reports
available for printing include: Medication Administration History,
Medication Log, Missed Medications, Missing Dose Request, PRN
Effectiveness Log, Medication Due List, Medication History, Medication
Variance Report, Cumulative Vitals/Measurement Report, and
Administration TimesReport.

The BCMA software provides the following features:

-  Medication Tabs on a patient’s Virtual Due List (VDL) are designed
   for separating and viewing the different types of active Unit Dose,
   IV Push, IV Piggyback, and large-volume IV medication orders. Each
   Tab provides an "alert" light, which turns green only when the
   patient has active medication orders for that Tab

-  • Patient safety tools include a Missed Medications Report, an alert
   when due medications are not administered, a notification when a
   patient is transferred, and an alert light to indicate that a
   medication order exists for the Schedule Type and Start/Stop Date and
   Time selected on the VDL. Other tools include a listing of Allergies
   and Adverse Drug Reactions (ADRs) that are documented for a patient
   in the Allergy/Adverse Reaction Tracking (ART) package

-  A Computerized Patient Record System (CPRS) Med Order Button (or "Hot
   Button") on the BCMA Tool Bar streamlines the workflow in ICU-type
   environments. This button link nurses directly to CPRS for
   electronically ordering, documenting, reviewing, signing verbal,
   telephone STAT and NOW (One-Time) medication orders already
   administered to patients

-  BCMA increases the amount and type of information available to nurses
   at point of care, it also improves communications between Nursing and
   Pharmacy staff, records Missing Doses for patients, sends an
   electronic Missing Dose Request to the Pharmacy, and supports Health
   Level Seven (HL7) messaging

-  • Management and accountability tools identify PRN entries that
   require effectiveness comment and pain scores, list medications that
   were not scanned as administered during an administration time
   window, list early/late administration variances, and allow nurses to
   set site-specific parameters and defaults on their systems

-  • Compiles reports by Patient or by Ward for Nursing, Pharmacy, and
   Information Resources Management (IRM). Reports available for
   printing include: Medication Administration History, Medication Log,
   Missed Medications, Missing Dose Request, PRN Effectiveness Log,
   Medication Due List, Medication History, Medication Variance Re port,
   Cumulative Vitals/Measurement Report, and Administration Times Report

-  Either VA or HIS Operational Environment is recognized and
   appropriate patient identifier displayed

-  Section 508 enhancements are in place to ensure enhanced
   accessibility

-  Additions to the BCMA Order Detail report include CPRS Order Checks,
   Provider override reasons, Pharmacist intervention information, and a
   "hover-over" feature displays visuals indicator when
   override/intervention reasons exist

-  Automated reporting method of bar code scanning failures (both
   patient wristbands and medication bar code labels) shorten resolution
   times, and allow for proactive analysis of failure information to
   prevent future scanning failures

-  Creation of a record within Patient Care Encounter (PCE) for
   medications marked as given in BCMA that have been identified as
   immunizations

   1. .. rubric:: 
         Bar Code Medication Administration (BCMA) Backup Utility
         :name: bar-code-medication-administration-bcma-backup-utility

**Version**: 3.0

**Namespace:** PSB or BCBU

**Brief Description:** Bar Code Medication Backup Utility (BCBU) allows
compliance with Automated Information Systems (AIS) security directives
requiring all facilities to be responsible for the development,
maintenance, and annual testing of individual AIS contingencies. BCBU
maintains a current copy on the designated workstation of all inpatient
pharmacy activities, including the inpatient medication orders,
medication administrations, and allergies that are included on a
Pharmacy Medication Administration Record (MAR).

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Provide Clinical Decision Support, Provide Medical
Services, Provide Ancillary Services, Manage Health Records, Utilize
Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** OIA/BCMA and PBM

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=84

**Full Description and Features:** Bar Code Medication Backup Utility
(BCBU) allows compliance with Automated Information Systems (AIS)
security directives requiring all facilities to be responsible for the
development, maintenance, and annual testing of individual AIS
contingencies. BCBU maintains a current copy on the designated
workstation of all inpatient pharmacy activities, including the
inpatient medication orders, medication administrations, and allergies
that are included on a Pharmacy Medication Administration Record (MAR).
Designated workstation(s) will contain current information regarding
inpatient medication orders (Unit Dose and IV), medication
administration record (MAR), medication administration history (MAH) and
patient allergies. Workstations are updated using the HL7 package. These
workstations are available for use according to local policies
concerning VistA, BCMA, or network contingencies.

-  PSB BCBU Errors Mail group notifies responsible users of potential
   problems with sending information to the Contingency Workstations

-  Active inpatient data are kept

-  Menu options on workstations allow users to generate reports if VistA
   is unavailable

-  BCMA allows outpatient clinic orders; BCBU was updated to support
   outpatient clinic orders

   1. .. rubric:: 
         Controlled Substances
         :name: controlled-substances

**Version**: 3.0

**Namespace:** PSD

**Brief Description:** The Controlled Substances package provides
functionality to monitor and track the receipt, inventory, and
dispensing of all controlled substances.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1190

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122930/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=86

**Full Description and Features:** The Controlled Substances package
provides functionality to monitor and track the receipt, inventory, and
dispensing of all medications which are controlled substances. This
software provides the pharmacy with the capability to define a
controlled substance location and a list of controlled substances to
maintain a perpetual inventory. The capability for Pharmacy personnel to
receive a controlled substance order, which automatically updates the
quantity on hand and receipt history, is also available. Nursing
personnel can request orders for controlled substances via on-demand
requests, and receive these orders when delivered from Pharmacy.
Pharmacy may dispense controlled substances, using the automated VA
forms 10-2321 and 10-2638, to complete an order request.

-  Monitors/tracks the receipt, inventory, and dispensing of controlled
   substances

-  Allows management inspections to automatically identify discrepancies
   in stock levels

-  Allows nursing to place orders for controlled substances via
   on-demand requests

-  Provides AMIS and cost reporting data

-  Maintains perpetual vault inventory balances

-  Provides the functionality to return to stock, transfer between
   locations, cancel orders, and log outpatient prescriptions

-  Automates current inventory requirements that allow medical
   facilities to detect discrepancies or diversions of controlled
   substances, thereby improving overall drug accountability

-  Provides a Controlled Substance Inspector Menu that allows access to
   several specialized reports used in the inspection process

-  Interfaces with the Outpatient Pharmacy package to provide updates to
   inventory upon Return to Stock activity

-  Provides tracking for controlled substances being held for
   destruction and allows for the documentation of destruction

-  Provides an HL7 interface to Narcotic Dispensing Equipment systems

   1. .. rubric:: 
         Drug Accountability/Inventory Interface
         :name: drug-accountabilityinventory-interface

**Version**: 3.0

**Namespace:** PSA

**Brief Description:** The Drug Accountability/Inventory Interface works
toward perpetual inventory for each VA medical facility pharmacy by
tracking all drugs through pharmacy locations.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1790

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123326/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=87

**Full Description and Features:** The Drug Accountability/Inventory
Interface works toward perpetual inventory for each VA medical facility
pharmacy by tracking all drugs through pharmacy locations. Drugs are
added to the appropriate pharmacy locations as they are received from
the Prime Vendor. This allows sites to receive invoice information
containing data for confirmed orders. With the prime vendor, the data is
uploaded into VistA using a Graphical User Interface to perform the
upload. The files are uploaded into Drug Accountability, processed, and
upon verification, the pharmacy locations or master vaults are updated.
Dispensing data is collected from pharmacy packages to decrement
balances. Drug Accountability also provides the capability for Pharmacy
personnel to display or print procurement history, drug balance
adjustments, and order data.

There are two primary methods of receiving invoice data into Drug
Accountability:

-  Prime Vendor Data

-  IFCAP Data

Both methods involve having the user place the invoice orders with the
appropriate company. With the prime vendor, the data is uploaded into
VistA using a Graphical User Interface to perform the upload. With
IFCAP, the data is automatically shipped to VistA upon receipt at the
warehouse.

The Prime Vendor Interface includes the following features:

-  It automatically updates the Drug Accountability pharmacy locations
   based on dispensing and receiving information, and it also updates
   master vaults based on receiving information.

-  Drugs are added as the invoice data is received.

-  If the invoiced drug’s order unit and dispense units per order unit
   are the same as the information currently contained in the local DRUG
   file, the NDC field in the DRUG file is overwritten with the most
   recent National Drug Code (NDC) number.

-  The reorder quantities for the pharmacy locations and master vaults
   are provided on a daily basis by way of a mail message Generic
   Inventory Package

The IFCAP Interface includes the following features:

-  When a pharmacy order invoice is received and entered into the IFCAP
   purchasing system, the receipt data will be collected and compiled to
   an Health Level Seven (HL7) message and transmitted ‘real time’ to
   VistA Drug Accountability.

-  Upon receiving the message, the receipt data will be stored in a
   temporary global, and Drug Accountability will alert the user about
   the Pharmacy receipt.

-  After receiving invoice data into the warehouse, the transmission
   from IFCAP will place data into a temporary global.

-  When Pharmacy personnel sign into the Drug Accountability package,
   the program will check for the existence of orders to process.

-  If the orders exist, and the user has the proper security key, the
   data can then be received into Drug Accountability.

-  Each Purchase Order received will be for a specific pharmacy
   location. If items are to be shipped/received at different pharmacy
   locations, a different purchase order will be created/shipped for
   each location

Both Interfaces include the following features:

-  Vendor-specific information and procurement history is displayed for
   a selected drug

-  Pharmacy locations are established and populated

-  A purge capability with scheduling queuing is provided

-  Support is provided for NDC code set and pricing for Electronic
   Claims Management Engine pharmacy electronic billing

   1. .. rubric:: 
         Inpatient Medications
         :name: inpatient-medications

**Version**: 5.0

**Namespace:** PSJ

**Brief Description:** The Inpatient Medications package integrates
functions from the Intravenous (IV) and Unit Dose (UD) modules.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Disaster
Preparedness Programs, Provide Clinical Decision Support, Provide
Medical Services, Provide Ancillary Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1965

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123383/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=88

**Full Description and Features:** The Inpatient Medications package
integrates functions from the Intravenous (IV) and Unit Dose (UD)
modules. This integration provides a comprehensive record of medications
utilized during hospitalization of the veteran, the functionality for
clinician order entry through Computerized Patient Record System (CPRS),
and tailors processes by facility, user, and/or medication. Inpatient
Medications also facilitates BCMA, Barcode Medication Administration,
function and record of all medication administration to patients.
Inpatient also includes PADE, Pharmacy Automated Dispensing Equipment,
perpetual inventory interfaces to the inpatient drug dispensing
cabinets.

Integrated software allows these features, via the List Manager
interface, for both IV and Unit Dose. This provides the user the
capability to:

-  Browse through a list of orders and take action(s) against those
   items

-  Print 7-day, 14-day, and 24-hour Medical Administration Records
   (MARs), labels, and profiles from within the options

-  Select a detailed allergy report, document new allergies or adverse
   drug reactions

-  Update the Patient’s Record from within List Manager

-  Provides Drug/Drug Interaction, Drug/Class Interaction, Duplicate
   Drug, and Duplicate Class Order checks

-  Allows easier drug selection using Orderable Item

-  Provides on-line order maintenance (for example: edit, renewal,
   cancellation) and marks orders that need attention

-  Provides on-line order entry with an integrity check for each order
   type

-  Generates labels containing order and patient information upon the
   entry/maintenance of an order

-  Provides on-line or printed patient profiles that include a history
   of medication orders for the current or last medical center visit

-  Displays patient order information and histories of all actions taken
   on active orders

-  Provides an Action Profile of patient medication orders for use by
   physicians to cancel or continue medications

-  Provides a Stop Order Notice report to notify users of orders near
   expiration

-  Cancels/holds medication orders for patients transferred between
   wards and/or services

-  Provides dispensing cost reports by patient, ward, service, drug, and
   providers

-  Provides reports and forms by patient, ward, and selected groups of
   wards

-  Allows electronic entry and inpatient processing of medication orders
   for an outpatient receiving treatment via a clinic or ancillary
   service

-  Maximum single dosage order check

-  Implements Maximum Single Dose Order Check for simple and complex
   orders in Outpatient Pharmacy and Inpatient Medications applications
   and CPRS

-  Provides error messages with reasons at the order level when a
   Maximum Single Dose Order Check cannot be performed for Pharmacy
   users

-  Integrates with BCMA, Barcode Medication Administration, function and
   record of all medication administration to patients

-  Includes PADE, Pharmacy Automated Dispensing Equipment, perpetual
   inventory interfaces to the inpatient drug dispensing cabinets

   1. .. rubric:: 
         Inpatient Medications - Intravenous (IV)
         :name: inpatient-medications---intravenous-iv

**Version**: 5.0

**Namespace:** PSJ

**Brief Description:** Inpatient Medications’ Intravenous (IV) module
provides pharmacists and their staffs with IV labels, manufacturing
worksheets, ward lists for order updates, and management reports. It
permits the Pharmacy staff to track the manufacture of IV formulas with
greater control than manual procedures allow.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Disaster
Preparedness Programs, Provide Clincal Decision Support, Provide Medical
Services, Provide Ancillary Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1965

**VASI ID Link:** https://www.va.gov/vdl/application.asp?appid=88

**VDL Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123383/c/56/nt/-1?id=1578

**Full Description and Features:** Inpatient Medications’ Intravenous
(IV) module provides pharmacists and their staffs with IV labels,
manufacturing worksheets, ward lists for order updates, and management
reports. It permits the Pharmacy staff to track the manufacture of IV
formulas with greater control than manual procedures allow. Through
order entry and ward list updating, the staff can easily establish and
maintain an accurate and timely data set of IV orders. A carefully
designed set of checks and balances has been incorporated to ensure that
the patient is supplied IV solutions quickly and accurately.

-  Generates Manufacturing Lists to facilitate maximum efficiency in the
   preparation and delivery of IV products

-  Generates IV labels containing all necessary patient, drug, and
   schedule information Labels provide a bar-coded identifier which when
   used in conjunction with Bar Code Med Administration greatly enhances
   patient safety

-  Generates management reports designed to track drug costs and
   workload by ward, provider, IV room, and patien

-  Provides on-line generation of production reports such as renewal
   lists, active order lists, and formulary drug reports

-  Discontinues/holds orders for patients transferred between wards
   and/or services

-  Allows electronic entry and inpatient processing of medication orders
   for an outpatient receiving treatment via a clinic or ancillary
   service

-  Implements Maximum Single Dose Order Check for simple and complex
   orders in Outpatient Pharmacy and Inpatient Medications applications
   and CPRS

-  Provides error messages with reasons at the order level when a
   Maximum Single Dose Order Check cannot be performed for Pharmacy
   users

   1. .. rubric:: 
         Inpatient Medications - Unit Dose (UD)
         :name: inpatient-medications---unit-dose-ud

**Version**: 5.0

**Namespace:** PSJ

**Brief Description:** The Unit Dose (UD) module of Inpatient
Medications provides a standard computerized system for dispensing and
managing inpatient medications. Timely, accurate, accessible, and
up-to-date patient medication information is available from any terminal
within the facility. Computer-generated working forms allow personnel to
dedicate more time to patient care.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Conduct Disaster
Preparedness Programs, Provide Clinical Decision Support, Provide
Medical Services, Provide Ancillary Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1965

**VASI ID Link:** https://www.va.gov/vdl/application.asp?appid=88

**VDL Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123383/c/56/nt/-1?id=1578

**Full Description and Features:** The Unit Dose (UD) module of
Inpatient Medications provides a standard computerized system for
dispensing and managing inpatient medications. Timely, accurate,
accessible, and up-to-date patient medication information is available
from any terminal within the facility. Computer-generated working forms
allow personnel to dedicate more time to patient care.

-  Allows immediate entry of pre-defined sets of unit dose orders

-  Provides computerized pick lists, which include pre-calculated doses
   for pharmacists

-  Provides an interface to automated dispensing equipment

-  Implements Maximum Single Dose Order Check for simple and complex
   orders in Outpatient Pharmacy and Inpatient Medications applications
   and CPRS

-  Provides error messages with reasons at the order level when a
   Maximum Single Dose Order Check cannot be performed for Pharmacy
   users

   1. .. rubric:: 
         Pharmacy Reengineering (PRE)
         :name: pharmacy-reengineering-pre

      1. .. rubric:: Enterprise Customization System (PECS)
            :name: enterprise-customization-system-pecs

**Version**: 5

**Namespace:** PREC

**Brief Description:** PECS allows users to customize the contents of a
number of pharmacy-related information sets.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1588

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123093/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=204

**Full Description and Features:** Pharmacy Enterprise Customization
System (PECS) is a Java 2 Enterprise Edition (J2EE) application used to
research, review, report, and manage customized drug information from
First Data Bank's (FDB) MedKnowledge Framework (formerly Drug
Information Framework (DIF)), which is a Commercial-off-the-Shelf (COTS)
product, used in the enhanced order checking process.

The PECS application, through a web-based Graphical User Interface
(GUI), allows VHA pharmacists and clinicians to research and request
custom changes to Drug-Drug Interaction, Drug Pairs, Dose Range,
Duplicate Therapy, and Professional Monograph records, controlling
access through a role based authorization. VHA Pharmacy Benefits
Management (PBM)

periodically (as needed in support of VA procedures and priorities)
prepare, review and approve the customizations, which result in VA
Custom drug data, which will supersede or enhance the industry standard
FDB-drug

data.

The advantages to the VA for using PECS are as follows:

-  All customizations will be performed at the National level to provide
   consistent order checks between facilities

-  Use of First Databank for drug interaction, duplicate therapy, and
   dosing data

-  More specificity in drug interaction order checks with the ability to
   include or exclude dose route

-  More specificity in duplicate therapy order checks with FDB data

-  Weekly FDB updates with monthly customization updates

-  More frequent customization updates when needed

PECS does the following:

-  Allows users to customize the FDB standard reference tables used in
   the enhanced order checking that will be used by the Pharmacy
   Benefits Management (PBM) group, Pharmacy Informaticist, and National
   Drug File (NDF) managers or designees to enter and update the custom
   table values

-  Allows users to do the following customizations:

-  A custom drug-drug interaction, and any important attributes for that
   interaction

-  Drug pairs associated with a custom drug-drug interaction

-  A custom Professional Monograph for a drug-drug interaction,
   including any important attributes

-  A custom duplication allowance value for a duplicate therapy class

-  Custom values for attributes associated with a custom dose range
   check table

-  Provides a Searching capability for a user to see Drug-Drug
   Interaction, Duplicate Therapy, or Professional Monograph information
   separately or together, for chosen drugs

-  Provides the following reports:

-  History of custom changes for each of the five concepts

-  Exportable FDB or Custom Data - Individual query data can be exported
   from the five FDB-DIF or Custom tables. The available format is Excel

-  FDB Comparison Reports to compare incoming updated FDB data against
   VA customized data to help determine if the VA customized data needs
   to be modified

-  Provides a process via File Transfer Protocol (FTP) to transfer
   Custom data from a National server to all local/regional instances
   servers

-  Leverages the existing FDB data loader utility at each site that is
   used to update the FDB-DIF databases

Custom table content distribution involves using an automated utility,
Data Update (DATUP). The distribution method supports the following data
content scenarios:

-  Only FDB standard reference table data

-  FDB standard reference table data and Custom table data

-  Only Custom table data

Custom table content distribution supports both periodic and as-needed
releases.

Medication Order Check Healthcare Application (MOCHA)
-----------------------------------------------------

**Version**: 3.0

**Namespace:** PREM

**Brief Description:** Medication Order Checks for Healthcare
Applications (MOCHA) provides enhanced order checking functionality in
the Computerized Patient Record System (CPRS) and in the Veterans Health
Information Systems and Technology Architecture (VistA) Pharmacy
packages.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Medical Services, Provice Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1414

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123105/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=201

**Full Description and Features:** Medication Order Checks for
Healthcare Applications (MOCHA) provides enhanced order checking
functionality in the Computerized Patient Record System (CPRS) and in
the Veterans Health Information Systems and Technology Architecture
(VistA) Pharmacy packages. This functionality includes providing easy
access to Drug Monograph information, enhanced drug-drug interaction
order checking which displays clinical information, and improved drug
interaction and duplicate therapy by therapeutic classification. Changes
made to the order check display sequence will improve efficiency and
consistency between Inpatient and Outpatient Pharmacy packages.

MOCHA v2.0 implemented the first increment of dosage checks and
introduced the Maximum Single Dose Check for simple and complex orders
for Computerized Patient Record System (CPRS), Outpatient Pharmacy and
Inpatient Medications applications.

MOCCHA v2.1 implemented Max Daily Dose Order Checks for simple
medication orders

entered through Computerized Patient Record System (CPRS),
InpatientMedications, and Outpatient Pharmacy. If the Daily Dose exceeds
the First Databank (FDB) recommended Max Daily Dose, a warning shall be
displayed to the user. If the Max Daily Dose Order Check cannot be
performed, an error message will be displayed to the user, along with
general dosing information for the drug in most cases.

-  Implements Maximum Single Dose Order Check for simple and complex
   orders in Outpatient Pharmacy and Inpatient Medications applications
   and CPRS

-  Provides error messages with reasons at the order level when a
   Maximum Single Dose Order Check cannot be performed for Pharmacy
   users

-  Provides a generic error message at the order level when a Maximum
   Single Dose Order Check cannot be performed for CPRS users

-  Supports the ability to exclude a schedule from all Dosing Order
   Checks

-  Creates a new PDM option called Lookup Dosing Check Info for Drug
   [PSS DRUG DOSING LOOKUP] so that a user can view all data that can
   affect Dosing Order Checks for a drug

-  Creates and auto enables a new DOSING\_INFO web service

-  Provides an option to enable/disable Dosing Order Checks called
   Enable/Disable Dosing Order Checks [PSS DOSING ORDER CHECKS], which
   also includes generation of a notification and an audit trail

-  Implement Dose Range Checking with a Max Daily Dose limit for simple
   medication orders entered through Outpatient Pharmacy, Inpatient
   Medication, and CPRS

-  Display a generic error message when the Max Daily Dose Order Check
   cannot be performed in CPRS

-  Display an error message when the Max Daily Dose Order Check cannot
   be performed in CPRS with a detailed reason when height and/or weight
   is required, but does not exist in the Vitals application for the
   patient

-  Display an error message when the Max Daily Dose Order Check cannot
   be performed in Pharmacy with a detailed reason

-  Create a General Dosing Information message to be displayed when
   Dosing Checks cannot be performed

-  Correct identified daily dose errors due to frequency failure

-  Resolve miscellaneous frequency issues with incorporation of new
   dosing check frequency fields

-  Apply Daily Dose Check exclusion for schedule to medication orders
   entered through Outpatient Pharmacy, Inpatient Medications, and CPRS.

-  Apply advisory note to high dose warnings and General Dosing
   Guidelines for medication administered through eye, ear, or nose

-  Create a customized frequency message

-  Create a Max Daily Dose Warning message for the calculated Daily Dose

-  Add FDB data elements from Dosing Order Check call to VistA side of
   interface

-  Modifications to the ‘Available Dosage(s)’ list when a screen break
   occurs during order entry through the Outpatient Pharmacy application

-  Modifications to the accompanying dialog for the ‘Available
   Dosage(s)’ list displayed during order entry through the Outpatient
   Pharmacy application

-  Modification to display the most recent Serum Creatinine value and
   date resulted if available, even if the CrCL cannot be calculated on
   the pharmacy patient demographic header

-  Display BSA and CrCL information in the headers on all Outpatient
   Pharmacy medication order detail screens and all Inpatient
   Medications and Outpatient Pharmacy patient information screens that
   are currently missing this information

-  Display one warning if Maximum Single Dose and Max Daily Dose Order
   Check warning texts are identical

-  Adjustment to the Daily Dose if a Single Dose Adjustment is made for
   an IV order when performing Dosing Order Checks

-  Notify user when an Old Schedule Name is used for an order during
   Inpatient

-  Medications backdoor order entry for finish, verify, copy, and renew
   actions

-  Modify entries to the DOSE UNITS File (#51.24), see Section 4 for
   details

-  Modify entries to the DOSE UNIT CONVERSION File (#51.25), see Section
   4 for details

-  Update Check PEPS Services Setup [PSS CHECK PEPS SERVICES SETUP]
   option to perform the Max Daily Dose Order Check instead of the Daily
   Dose Range Order Check

-  Enhance lookup functionality when entering a schedule for an
   outpatient medication order through the pharmacy backdoor

   1. .. rubric:: Pharmacy Product System - National (PPS-N)
         :name: pharmacy-product-system---national-pps-n

**Version**: 1.0

**Namespace: **

**Brief Description:** The Pharmacy Product System - National (PPS-N) is
a Web-based application that allows select members of the Department of
Veterans Affairs (VA) Pharmacy Benefits Management (PBM) Services to
create and revise pharmacy drug information.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Ancillary Services,
Manage Health Records, Utilize Information Technology Services, Provide
Enterprise Reporting

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1518

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123255/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=202

**Full Description and Features:** The PPS-N and the PPS-L Migration
projects provide two distinct capabilities that are included in the same
application which is part of Pharmacy Re-Engineering (PRE) initiatives
within VHA. The Pharmacy Product System (PPS) is intended to improve the
VA’s formulary processes. PPS is envisioned as two distinct processes.
The first process covers PPS at the national level (called PPS-N). The
PPS-N environment provides for the ability to manage pharmacy-specific
data across the enterprise, ensuring that all facilities are using the
same base data for their operations. The second process encompasses PPS
processes at the local level (called PPS-L). The PPS-L application
environment will provide services that enact business logic for the
daily operations of pharmacy users at the VA’s medical centers and
clinics.

The PPS-N application allows national VA personnel to more easily,
quickly and safely manage the VA National Formulary which directs which
products, such as medications and supplies, are to be purchased and used
by the VA hospital system.The key capabilities are:

-  Provide a means for users to manage the National VA Formulary items.
   This includes being able to request the addition and update of items,
   and then approve these requests

-  Provide a means to synchronize PPS-N data with NDFMS

-  Provide a means to interface with a third-party
   commercial-off-the-shelf (COTS) drug data source

-  Via this interface PPS-N:

-  Provides a means for users to manage additions and changes made in
   the COTS drug data source, including synchronization of this data
   with the PPS-N Enterprise Product List (EPL)

-  Provides a means for users to search for data within the COTS drug
   data source

-  Provides a means for users to manage the mapping of VA concepts to
   COTS concepts

-  Provides a means for users to perform reports on items added by the
   COTS drug data source

-  Provide a means for users to perform various simple and advanced
   searches for item data contained within PPS-N

-  Provide a means for users to perform reports on the item data
   contained within PPS-N.

-  Provide a means to retrieve pricing information from the Federal
   Supply Schedule (FSS) system, and then to display this information to
   the PPS-N users

-  Provide a means to retrieve Standard Medication Route information
   from the VA Enterprise Terminology System (VETS), and then to manage
   this data within PPS-N

-  Provide a process executed on the legacy NDFMS system to support data
   synchronization with the PPS-N database

   1. .. rubric:: 
         National Drug File (NDF)
         :name: national-drug-file-ndf

**Version**: 4.0

**Namespace:** PSN

**Brief Description:** The National Drug File (NDF) package provides
standardization of the local drug files in all VA medical facilities.
Standardization includes the adoption of new drug nomenclature and drug
classification, as well as linking the local drug file entries to data
in the National Drug files.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Provide Ancillary Services, Manage Health Records, Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1821

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123292/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=89

**Full Description and Features:** The National Drug File (NDF) package
provides standardization of the local drug files in all VA medical
facilities. Standardization includes the adoption of new drug
nomenclature and drug classification, as well as linking the local drug
file entries to data in the National Drug files. For drugs approved by
the Food and Drug Administration (FDA), NDF provides VA medical
facilities with the ability to access information concerning dosage
form, strength and unit, package size and type, manufacturer’s trade
name, and National Drug Code (NDC) information. The NDF software also
lays the foundation for sharing prescription information among medical
facilities.

-  Standardizes drug file information

-  Standardizes drug classifications

-  Adopts standard nomenclature

-  Provides up-to-date prescription and over-the-counter information

-  Provides available sources for drugs manufactured and approved by the
   FDA

-  Provides a base for implementation of drug inventory control and
   management throughout VA (i.e., Consolidated Mail Outpatient Pharmacy
   and Pharmacy Benefits Management)

-  Allows file access by NDC, manufacturer’s trade name, ingredient,
   dosage form, dosage strength, route of administration, and VA drug
   classification

-  Allows management of drug information, including reports on drugs by
   classification, ingredient, NDC, trade name, and/or active/inactive
   status

-  Matches additions to medical center drug files with the national drug
   database

-  Provides an ingredient file that is an integral component of the
   Allergy Tracking and Outpatient Pharmacy (drug-drug interactions)
   modules

-  Provides an enhanced formulary report listing local, VISN, and
   National Formulary information

-  Includes the Patient Medication Information Sheets that feature the
   following:

   -  An explanation of how and why to take a medication and the
      possible side effects.

   -  Information supplied by commercial sources.

   -  Information that is copyrighted and periodically updated.

-  Utilizes data provided and standardized by contract for point of sale
   electronic billing using Electronic Claims Management Engine (ECME)

-  Manage FDA Medication Guides

   1. .. rubric:: 
         Outpatient Pharmacy
         :name: outpatient-pharmacy

**Version**: 7.0

**Namespace:** PSO

**Brief Description:** Outpatient Pharmacy provides a method for
managing the medications given to Veterans who have visited a clinic or
who have received prescriptions upon discharge from the hospital.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Conduct Disaster Preparedness Programs, Provide Medical
Services, Provide Clinical Decision Support, Provide Medical Services,
Provide Ancillary Services, Manage Health Records, Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1972

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123458/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=90

**Full Description and Features:** Outpatient Pharmacy provides a method
for managing the medications given to Veterans who have visited a clinic
or who have received prescriptions upon discharge from the hospital.
Prescription labels, refill request forms, FDA Med Guides and PMI sheets
can be generated. Medication histories are kept online to permit checks
for potential interactions. Profiles can be generated to assist the
clinician in managing the patient’s medication regimen. Management
reports aid the pharmacy in controlling inventory and costs.

-  Allows the Action Profile to be used as a quick renew/cancel request
   form by clinic providers when electronic notifications are not
   available or the site is not fully automated

-  Transfer outpatient controlled substances prescriptions dispensing
   information to the respective State Board of Pharmacy in accordance
   with Controlled Substances Sate Prescription Monitoring Program

-  Allow the ability to utilize Outpatient Pharmacy Automation Interface
   (OPAI) for automated dispensing and release of prescriptions by the
   Automated Robots

-  Implements Maximum Single Dose Order Check for simple and complex
   orders in Outpatient Pharmacy and Inpatient Medications applications
   and CPRS

-  Implements Dose Range Checking with a Max Daily Dose limit for simple
   medication orders entered through Outpatient Pharmacy, Inpatient
   Medications and CPRS

-  Provides error messages with reasons at the order level when a
   Maximum Single Dose Order Check cannot be performed for Pharmacy
   users

-  Provides error messages when Max Daily Dose Order Check cannot be
   performed in CPRS and Pharmacy applications

-  Checks new prescriptions against existing prescriptions (for the same
   medication, therapeutic class, reported allergies, reactions, or drug
   interactions)

-  Allows pharmacists to verify data entered by technicians prior to the
   printing of labels.

-  Allows for the renewal of prescriptions that have no remaining
   refills. Prints labels for new,renewed and refilled prescriptions

-  Auto-cancels individual prescriptions for a patient after admission
   for inpatient treatment

-  Creates medication profiles for patient charts to meet the Joint
   Commission on Accreditation of Healthcare Organizations (JCAHO)
   requirements for a current medication list. Profiles are suitable for
   counseling patients

-  Allows the Action Profile to be used as a quick renew/cancel request
   form by clinic providers,which allows for rapid entry of request by
   Pharmacy staff

-  Provides the Screen Profile for review at several points in the
   order/entry process

-  Provides basic Drug Use Evaluation (DUE) template generator

-  Provides necessary laboratory checks and reports to meet national
   requirements for Clozapine dispensing

-  Provides finishing of orders entered through CPRS

-  Provides information for billing any applicable medication co-payment
   when the prescription is released

-  Allows the user to select a different action without leaving an
   option

Uses List Manager features to allow:

1. Pharmacist or technician to browse through a list of actions

2. Pharmacist or technician to take action against those items

3. User to select an action that displays an action or informational
   profile

-  Works with Integrated Billing (IB) and Electronic Claims Management
   Engine (ECME) to enable and manage point of sale billing supporting
   the Healthcare Insurance Portability and Accountability Act (HIPAA)
   Electronic Claims and Code set congressional mandate

-  Allows prescription labels and Prescription Medication Information
   (PMI) sheets to be printed in another language if the system has the
   other language fields populated in Pharmacy Data Management and the
   individual patient is identified with the other language preference
   flag

-  Allows the ability to print a microchip-embedded label for a
   prescription. This label can then be read by ScripTalk®, thus
   improving patient safety for visually impaired veterans

-  Provides display of Herbal, over the counter (OTC), and Non-VA
   medications documented through CPRS. The data will be used for
   screening of Drug-Herbal and Drug-Drug Interactions with prescribed
   medications in VistA

-  A maximum single dosage order check

-  State Prescription Monitoring Program - The pharmacies comply with
   Mandatory Reporting to State Controlled Substance Rx Databases
   required by Consolidated Appropriations Act, 2012,PL 112-74

-  Titration/Maintenance Rx functionality

-  OneVA Pharmacy - Provides Pharmacists the capability to dispense
   prescriptions that originated in other VistA host sites

   1. .. rubric:: 
         Pharmacy Benefits Management (PBM)
         :name: pharmacy-benefits-management-pbm

**Version**: 4.0

**Namespace:** PSU

**Brief Description:** The Pharmacy Benefits Management (PBM) package
extracts medication dispensing data elements from numerous locations and
makes reports available allowing projections of local drug usage and
identification of potential accountability problem areas. The extracted
data is transmitted to the PBM using VA Mailman. The Pharmacy Benefits
Management (PBM) database that collects information on medication
dispensed to both inpatient and outpatient veterans who receive care
from the VA is housed at the Hines Information Technology Center (HITC).

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Services,
Provide Ancillary Services, Utilize Information Technology Services,
Provide Enterprise Reporting

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1832

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123403/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=91

**Full Description and Features:** The Pharmacy Benefits Management
(PBM) package replaced the Drug and Pharmaceutical Products management
(D&PPM) application. The software extracts medication dispensing data
elements from the Outpatient Pharmacy, Inpatient Medications IV and Unit
Dose, Automatic Replenishment/Ward Stock, and Controlled Substance
modules; it also extracts procurement information from Drug
Accountability, Integrated Funds Control, Accounting and Procurement
(IFCAP), and a limited amount of Laboratory data on a monthly basis.

The software makes data extraction reports available at Veterans Affairs
Medical Centers (VAMCs) and allows local management to use the data to
project local drug usage and identify potential drug accountability
problem areas. The Pharmacy Benefits Management Strategic Health Group
(PBM) is able to provide information on local facility, Veterans
Integrated Service Network (VISN) and national product use on monthly,
quarterly, and annual intervals.

The extracted data is transmitted to the PBM using VA Mailman. The
Mailman message headers display how many messages were sent for a
particular module along with the facility name and number from which the
data was extracted. The header easily identifies the module from which
the data was extracted, and confirmation messages include the number of
Mailman messages generated for each module.

-  Breakout of Inpatient Medications IV and Unit Dose, Outpatient
   Pharmacy, and Controlled Substance modules by dispensing occurrence

-  Breakout of procurement information by line item from Drug
   Accountability, Integrated Funds Control, Account and Procurement
   (IFCAP) and a limited amount of Laboratory data

-  Collection of the Prime Vendor Procurement Information (requires
   implementation of Drug Accountability V 3.0), Pharmacy AMIS data,
   Laboratory data, and Patient and Provider information

-  Capture of controlled substance dispensing to patients if electronic
   Controlled Substance Administration Record (CSAR) is implemented with
   Controlled Substance Version 3.0

-  Extraction of data and generation of drug and statistical data
   summary reports by inpatient division or outpatient site whenever
   possible

-  Inclusion of National Formulary Indicator and Restriction

-  Mechanism to monitor the successful completion of the automatic
   monthly extraction job and to notify users if a problem exists

-  Extraction of data to the PBM national database on a monthly basis

   1. .. rubric:: 
         Pharmacy Data Management (PDM)
         :name: pharmacy-data-management-pdm

**Version**: 1.0

**Namespace:** PSS

**Brief Description:** The Pharmacy Data Management (PDM) package
provides tools for managing site configurable data in pharmacy files.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Medical Services, Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Pharmacy Benefits Management (PBM)

**VASI ID:** 1833

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123404/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=93

**Full Description and Features:** Pharmacy Data Management (PDM)
provides tools for managing Pharmacy data. It includes tools for
creating Pharmacy Orderable Items and maintaining files necessary for
the Computerized Patient Record System (CPRS). PDM consolidates tools
for managing the various Pharmacy software products. It provides
Pharmacy Supervisors, in one location, the capability to enter and edit
data for the local DRUG file (#50) for all Pharmacy related packages.
PDM now allows users to enter medication instruction components (e.g.,
dosage, noun, verb, expansion) in a language other than English.
However, at this time, the Patient Medication Information Sheets only
allow patient data to be in English or Spanish.

Prosthetics
-----------

**Version**: 3.0

**Namespace:** RMPR

**Brief Description:** The VistA Prosthetics package automates
purchasing. The Prosthetics module enhances patient care by determining
what prosthetic services and devices have been provided to the Veteran
in the past, and decreasing the time required for the order, delivery,
and/or repair of devices.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Prosthetics and
Sensory Aids

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Office of Patient Care Services Programs

**VASI ID:** 1836

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123407/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=96

**Full Description and Features:** The Prosthetics package automates
purchasing. The Prosthetics module enhances patient care by determining
what prosthetic services and devices have been provided to the veteran
in the past, and decreasing the time required for the order, delivery,
and/or repair of devices. The Prosthetics package provides control,
inventory, auditing of expenditures and generates management reports.
The Record of Prosthetics Service, VAF 10-2319, and the appropriate
IFCAP obligation, are updated at the time of purchase (entry into the
computer) of the item or service provided to the veteran. This update is
accomplished through direct links to IFCAP and the Electronic Patient
VAF 10-2319.

-  The Purchasing module interfaces with IFCAP (Integrated Funds,
   Distribution, Control Point Activity, Accounting and Procurement).
   Users enter requests to purchase and repair items or services using
   online VA forms or Purchase Card that allows tracking of the
   transactions. The Purchasing module uses a Prosthetics VistA Suite
   Graphical User Interface (GUI) application

-  The Electronic Record of Prosthetic Services (VAF 10-2319) tracks
   demographics, disability codes, new purchases, repairs/replacements,
   service cards, clothing allowance, automobile adaptive equipment, and
   Home Improvement Structural Alterations (HISA). This module is
   accessible using the Prosthetic VistA Suite GUI

-  The Lab module has Orthotic Lab, Restoration Lab, Shoe Last Clinics,
   Wheelchair Repair Shops, and the Denver Distribution Center. This
   module is accessible using a Prosthetics VistA Suite GUI

-  The Home Oxygen module manages vendor billing and current
   prescriptions. Sites have the ability to update various information
   for billing (vendor, PSAS HCPCS, Fund Control Point, Item and Unit
   Cost) as appropriate

-  The Inventory module tracks quantities of prosthetic items that
   facilities have in stock.

-  The Suspense module tracks patient requests for prosthetic appliances
   or services through Prosthetics or sent electronically from the
   Computerized Patient Record System (CPRS) via Consult/Request
   Tracking

-  The National Prosthetics Patient Database (NPPD) module captures
   medical center Prosthetic patient transaction data. The NPPD Detail
   Display Report is accessible using a Prosthetics VistA Suite GUI

-  The Delayed Order Report (DOR) functionality is also available
   through the Prosthetic VistA Suite GUI

   1. .. rubric:: 
         Quality Audiology and Speech Analysis and Reporting (QUASAR)
         :name: quality-audiology-and-speech-analysis-and-reporting-quasar

**Version**: 3.0

**Namespace:** ACKQ

**Brief Description:** Quality Audiology and Speech Analysis and
Reporting (QUASAR) is a VistA software package written for the Audiology
and Speech Pathology Service. QUASAR is used to enter, edit, and
retrieve data for each episode of care.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Audiology and Speech Pathology

**VASI ID:** 1506

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123096/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features: **

-  Provides automatic transmission of visit data to the Patient Care
   Encounter (PCE) program in order to incorporate QUASAR visit data in
   Ambulatory Care Reporting Program (ACRP) and in the Decision Support
   System (DSS)

-  Produces a variety of reports useful to local managers, medical
   center management, and central planners

-  Allows for Generation of customized reports

-  Produces an automated Cost Distribution Report (CDR) RCS-10-01 41

-  Generates and processes Audiology compensation and pension visits
   through an agreement with the Automated Medical Information Exchange
   (AMIE) package

-  Allows input of a patient's audiogram and display of audiometric data
   in graphical or tabular format. The audiogram may then be signed and
   transmitted to the VA Denver Distribution Center (DDC) for inclusion
   in a patient's hearing aid order. (The audiogram will also be
   recorded in the DDC's national database of audiometric data.)

-  ICD-10 code compliant

   1. .. rubric:: 
         Quality Management Integration Module
         :name: quality-management-integration-module

**Version**: 1.7

**Namespace:** QAQ

**Brief Description:** The QM Integration Module, (previously "Quality
Assurance Integration") contains utilities that are common to some or
all of the QM software packages. Configuration is part of the
installation for all QM packages (via the Combined Site Parameters Edit
option.)

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Deliver Health Care

**Business Function Framework Function(s):** Provide Member Access,
Provide Medical Services, Manage Health Records

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1947

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123400/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=117

**Full Description and Features:** The QM Integration Module links the
QM software applications through a QM Manager menu.

**Date Selector:** The date selector is found within many of the reports
options. It lets the user choose the date range that is needed for the
report.

**Group Selector:** The group selector is a sort process that provides
the ability to select a list of records. It lets the user select more
than one item to print or view at a time. This reduces the number of key
strokes needed to produce a specific outcome.

**AD Hoc Report Generator:** The Ad Hoc Report Generator uses basic VA
FileMan sort and print modifiers and adds the capability of building
macros (often termed templates) for those reports that are routinely
required.

**Audit File:** The audit file builds an audit trail for each record in
the QM packages. You can see the contents of the audit file in the
Occurrence Screen software by using the Audit File Inquiry option. In
other software, the audit trail is accessible to the IRM staff through
VA FileMan.

Radiology/Nuclear Medicine
--------------------------

**Version**: 5.0

**Namespace:** RA

**Brief Description:** Radiology/Nuclear Medicine is a comprehensive
software package designed to assist with the functions related to
processing patients for imaging examinations.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Deliver Health Care

**Business Function Framework Function(s):** Provide Member Access,
Provide Medical Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1837

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123408/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=98

**Full Description and Features:** The Radiology/Nuclear Medicine
package automates the entire range of diagnostic functions performed in
imaging departments, including order entry of requests, registration of
patients for exams, processing of exams, recording of reports/results,
verification of reports on-line, displaying/printing results for
clinical staff, automatic tracking of requests/exams/reports, and
generation of management statistics/reports, both recurring and ad hoc.

-  Functionality is screened by Imaging Type to make it look as if there
   are separate sub-packages. Many options are also screened by or allow
   selection by division and/or imaging location

-  There is on-line patient registration for exams, automatic printing
   of Radiology orders and transcription of patient radiological/nuclear
   medicine reports

-  Management reports include workload, complications and ad hoc
   summaries, daily activity logs, examination statistics, and
   performance indicators

-  Health Level 7 (HL7) (e.g., voice-to-text and PACS equipment)
   standard for interfacing with non-VistA computer systems is supported
   for the exchange of radiology/nuclear medicine results

-  There is on-line physician verification of radiological/nuclear
   medicine exam reports using electronic signatures

-  Stop codes and procedures associated with a radiological/nuclear
   medicine exam are automatically credited for reimbursement purposes

-  It interfaces with the Computerized Patient Record System module for
   entry of radiology/nuclear medicine requests and display of results
   to clinical staff

-  It interfaces with the Adverse Reaction Tracking (ART) module by
   allowing users to add contrast media reactions to ART via the
   Radiology/Nuclear Medicine package

-  It interfaces with the Women's Health module by automatically adding
   mammogram and ultrasound procedures for female patients to the
   Women's Health database

-  It supports entry of multiple diagnostic codes and multiple
   interpreting by residents and staff

-  There is a single combined report for a set of related procedures.
   This is a "print set" mechanism for entering a single report for all
   descendent cases registered from a parent order

-  It provides the ability to enter and edit information specific to
   radiopharmaceuticals for Nuclear Medicine

-  It allows on-line verification of "STAT" category requests

-  It allows for the selection and printing of multiple reports

-  Patient-specific radiation dosage aggregation

-  Secondary diagnosis allowed from studies that are imported into VistA

   1. .. rubric:: 
         Record Tracking
         :name: record-tracking

**Version**: 2.0

**Namespace:** RT

**Brief Description:** The Record Tracking module provides for the
maintenance and control of hardcopy health records and x-ray films to
facilitate availability to a variety of users. The system offers a wide
range of individual site-definable parameters so that it may be
custom-tailored to specific needs and used in any type of file setting.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Ancillary Services,
Manage Health Records

**VHA Portfolio:** Business Informatics

**Business Owner:** Director, HIM

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=53

**Full Description and Features:** The Record Tracking module is
integrated with patient administrative and clinical modules. The module
supports requisitioning activities for individual records within a
facility and between facilities, and automates file room functions in
support of the following activities:

-  Creation of new records/volumes

-  Charge-out/check-in of records

-  Inactivation/reactivation and deletion of records

-  Printing of bar code labels

-  Transfer of records to other facilities

-  Recharging records to other borrowers

-  Flagging a record as missing

-  Record retirements

-  Uses bar code technology, prints bar code labels for the charts, and
   uses bar code equipment to charge records

-  Displays informational bulletins when a record is checked into a file
   room

-  Bulletins may include the following information: pending requests for
   the record, the record has previously been flagged as missing, loose
   filing exists, the patient is currently an inpatient, or the record
   is being checked into a file room other than its home

-  Offers a complete system for maintenance and control of records that
   may be used with ease in any type of file setting

-  Produces a variety of reports associated with the module that may be
   used to assist management in workload analysis and control of records

-  Creates pull lists to provide requests for records in conjunction
   with clinic scheduling and record retirement

   1. .. rubric:: 
         Remote Order Entry System (ROES)
         :name: remote-order-entry-system-roes

**Version**: 3.0

**Namespace:** RMPF

**Brief Description:** The Remote Order Entry System (ROES) is the
front-end of the Denver Acquisition & Logistics Center (DALC) supply
chain/order fulfillment production system. ROES is used by Department of
Veterans Affairs (VA) clinicians to place orders for certain types of
medical products and services that are maintained under contract by the
DDC.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Manage VHA-wide
Administrative Services, Conduct Supply Chain Operations

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1838

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123409/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The most substantial product line
handled through ROES is custom hearing aids. As implied by the name,
custom hearing aids are highly specialized devices custom made for
individual Veteran patients. Other product lines handled through ROES
include stock hearing aids, hearing aid accessories and batteries,
prosthetic items, aids for the visually impaired and assistive devices.
The hearing aid repair is a line of service provided by the DALC and
facilitated by ROES. The ROES application and database integrates the
DDC enterprise business functions of contracting/acquisition management,
order fulfillment, distribution management, finance, and product life
cycle support. Extensive order tracking, serialized device registration,
patient/device history, and sales/financial reporting are also supported
by the database.

-  ROES uses advanced technologies and practices in software design,
   supporting hardware platform, database management, and network
   integration

-  ROES also integrates Web-based application architecture with a VistA
   environment, obtaining an optimum mix of decentralized VistA
   interfacing with centralized data management

-  The database is optimized for the DALC’s progressive procurement and
   distribution practices, advanced general business practices, and
   current VA regulations

   1. .. rubric:: 
         Remote Procedure Call Broker (RPC)
         :name: remote-procedure-call-broker-rpc

**Version**: 1.1

**Namespace:** XWB

**Brief Description:** RPC enables for Veterans Health Information
Systems and Technology Architecture (VistA) providing Windows-based
graphical user interface (GUI) software applications.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA & OIT

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=23

**Full Description and Features:** This type of software application
typically runs as a client in a client/server environment. One of the
challenges in creating such applications is establishing communication
between the client workstation and VistA's M-based servers. In a secure
manner over a Transmission Control Protocol/Internet Protocol (TCP/IP)
network, users need to be able to log onto a server, initiate activities
on the server, and retrieve and update data on the server. VistA's
Remote Procedure Call (RPC) Broker software provides functionality so
that

GUI developers can:

-  Establish a connection from a client workstation to a VistA M Server

-  Run RPCs on the VistA M Server

-  Return data to the client workstation

The VistA M Server continuously runs an RPC Broker listener process
whose purpose is to establish connections with clients. When the
listener process receives a connection request from a client, it spawns
a separate handler process, which then handles all communications with
the client. Once connected, the client can execute Remote Procedure
Calls on the VistA M Server. RPCs are written in M and accessed through
the VistA M Server's REMOTE PROCEDURE file (#8994).

-  Broker Developer Kit (BDK)

-  Dynamic Link Library

-  Client/Server security

-  Integrated Single Sign-On

-  Silent Sign-On

-  Shared Broker

-  Non-callback connection

-  CCOW-enabled

-  M-to-M Broker

-  Broker Security Enhancement (BSE)

   1. .. rubric:: 
         Repositories
         :name: repositories

      1. .. rubric:: Administrative Data Repository (ADR)
            :name: administrative-data-repository-adr

**Version**:

**Namespace:** Multiple Namespace

**Brief Description:** The ADR is a transactional data repository which
serves as the authoritative source for selected VistA demographic and
eligibility/enrollment information for all persons. The ADR houses
information migrated from the Health Eligibility Center and Master
Veteran Index.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Use Information Technology
Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** OIA

**VASI ID:** 1006

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/121873/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Administrative Data Repository
(ADR) was established to provide support for the administrative data
elements relative to multiple categories of a person entity such as
demographic and eligibility information. Although initially focused on
the computing needs of the Veterans Health Administration, the ADR is
positioned to provide identity management and demographics support for
all IT systems within the Department of Veterans Affairs.

The ADR Project primarily supports the Enrollment System (ES) and Person
Service applications and may support several additional VistA
re-engineering projects. ADR incorporates standard administrative
reference data from Standards & Terminology Services (STS).

Information in the system of records is used to:

-  Update, verify and validate Veteran eligibility

-  Conduct income testing and verification activities

-  Validate social security numbers of Veterans and spouses of those
   Veterans receiving VA health care benefits

-  Ensure accuracy of Veterans' eligibility information for medical care
   benefits

-  Operate an annual enrollment system

-  Update Veteran eligibility

-  Provide enrollment materials to educate Veterans on enrollment

-  Respond to Veteran and non-Veteran inquiries on enrollment and
   eligibility

-  Compile management reports

   1. .. rubric:: 
         Clinical Data Repository/Health Data Repository (CHDR)
         :name: clinical-data-repositoryhealth-data-repository-chdr

**Version**: 2.1.2

**Namespace:** CHDR

**Brief Description:** The Clinical Health Data Repository (CHDR) shares
computable health record data elements between DoD’s Clinical Data
Repository (CDR) and VA’s Health Data Repository (HDR).

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Clinical Decision
Support, Provide Ancillary Services, Manage Health Records, Utilize
Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** OIA HI

**VASI ID:** 1115

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122823/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The CHDR generates standards-based,
computable electronic health record (EHR) data elements between DoD’s
Clinical Data Repository (CDR) and VA’s Health Data Repository (HDR) for
patients identified and matched as Active Dual Consumers (ADCs) of both
VA and DoD health care.

Clinical data for these "dual consumers" (patients receiving healthcare
or expected to receive healthcare at both VA and DoD medical
facilities.) Data for patients is stored at each agency’s local
healthcare systems: at DoD this occurs in the Clinical Data Repository
(CDR), a component of the Armed Forces Health Longitudinal Technology
Application (AHLTA). At VA, the Health Data Repository (HDR) stores the
CHDR data.

The CHDR system is the link between the two repositories, and once the
patient is marked "active," the data exchange is enabled. Most patients
marked active are so marked by the DoD automated process. At VA,
patients can be marked "active" manually, using the CHDR Administration
Application Interface (CHDR Admin GUI.)

After the computed data is exchanged, it can be used by each agency’s
native healthcare information system. At VA, the integrated data can be
viewed through VistAWeb while triggered Drug/Drug and/or Drug Allergy
alerts will manifest in the Computerized Patient Record System (CPRS.)

Health Data Repository (HDR) Data Warehouse (DW)
------------------------------------------------

**Version**: 3.21

**Namespace:** HDS

**Brief Description:** HDR is a national, clinical data storehouse that
supports integrated, computable and/or viewable access to the patient’s
longitudinal health record. The HDR serves as the authoritative source
for data from DoD Clinical Data Repository and for the Home TeleHealth
program.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** OIA

**VASI ID: **

**VASI ID Link: **

**VDL Link: **

**Full Description and Features: **

The Repositories Program supports storage of enterprise-wide,
Veteran-centric clinical and administrative data via the Health Data
Repository (HDR) and Administrative Data Repository (ADR) products. HDR,
a relational database that stores discrete data rather than messages,
enables provider to obtain integrated data views and acquire
patient-specific clinical information to support treatment decisions.

HDR provides clinical data from VistA in a computable and/or viewable
access form to user interfaces such as RDI, CHDR, and VistAWeb. The HDR
Data Warehouse (DW) meets the data needs of the VA research and analysis
community without impacting database performance for the end-users.

Resident Assessment Instrument/Minimum Data Set (RAI/MDS)
---------------------------------------------------------

**Version**:

**Namespace:** DGRU

**Brief Description:** The Resident Assessment Instrument/Minimum Data
Set (RAI/MDS) provides a standardized assessment tool in support of
long-term patient care assessment and serves as the basis for
development of a patient’s plan of care. RAI/MDS is used in data
collection from VA long-term care facilities.

**Business Function Framework Line(s) of Business:** N/A

**Business Function Framework Function(s):** N/A

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA HQ Geriatrics and Extended Care

**VASI ID:** 1571

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123146/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=125

**Full Description and Features: **

The Resident Assessment Instrument/Minimum Data Set (RAI/MDS) provides a
standardized assessment tool supporting the completion of a
comprehensive, accurate, and reproducible patient assessment, and serves
as the basis for developing the patient’s plan of care. The RAI/MDS
aligns the VA’s data collection processes with private sector skilled
nursing facilities. The Centers for Medicare and Medicaid Services (CMS)
and the States require that long-term care facilities implement RAI/MDS
to receive Medicare and/or Medicaid reimbursement. Use of RAI/MDS in VA
long-term and Nursing Home Care Unit programs provides a structure for
meeting JCAHO long-term care accreditation standards. It also provides
opportunities for comparison of patient outcomes within and across VA
and with non-VA long-term care and/or nursing home programs. The VA
contracts for Caribou, which has been implemented nationally, with a
gateway interface to import patient data from VistA. Data is
electronically transmitted to the national database at the Austin
Information Technology Center (AITC). The AITC in turn uses the MDS to
produce Resource Utilization Groups (RUG-III) and Quality Indicator
reports. In addition, it provides the basis for the unannounced survey
program.

-  Admissions module with demographic and patient movement information
   interfaced from VistA

-  Assessments module based on the MDS, a core set of preliminary
   screening and assessment elements including common definitions and
   coding categories

-  Resident care lan and report modules

-  Electronic transmission of assessments to AITC

   1. .. rubric:: 
         Scheduling
         :name: scheduling

**Version**: 5.3

**Namespace:** SD, SC

**Brief Description:** The Scheduling module automates all aspects of
the outpatient appointment process, including the ability to check
in/check out patients, clinic set-up and maintenance,
enrollment/scheduling/discharge of patients to and from various clinics,
and the generation of managerial reports, statistical reports, patient
letters, and workload reporting. It provides for multiple-appointment
booking, which enables the user to schedule, at one time, numerous
appointments on a consecutive day/week basis.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Provide Health Care Administration

**Business Function Framework Function(s):** Provide Member Access,
Perform Hospital Administration, Manage Health Records, Perform
Financial Management, Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Veterans Access to Care (OVAC)

**VASI ID:** 1840

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123410/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=100

**Full Description and Features:** The system may display numerous
messages when an appointment is scheduled depending on the availability
of the slot requested. These include notification that the appointment
is an overbook, the patient already has an appointment scheduled for
that date and time, or the appointment cannot be made due to previous
inactivation of the designated clinic. In addition, certain
classification questions are prompted during the check-out process (if
applicable) to determine if treatment rendered was connected to special
circumstances (such as Agent Orange, Ionizing Radiation, Persian Gulf,
etc.).

If an appointment cannot be scheduled because of limitations, the user
is prompted to add the appointment information to a Wait List for future
scheduling.

Ambulatory Care data meeting specified criteria are transmitted to the
Austin Information Technology Center (AITC). Subsequent transmissions
will update the National Database. This additional data supplements the
existing Clinic Appointment Wait Time extracts.

The functions within Scheduling currently fall into four major
categories: Appointment Scheduling, Local Reporting (outputs), National
Data Collection, and Module Set-Up and Maintenance.

-  Creates fixed or variable length clinic patterns

-  Provides on-line clinic availability and system identification of
   conditions such as first available appointment

-  Interacts with the Record Tracking module allowing chart request at
   the time of appointment scheduling

-  Generates cancellation, no-show, and pre-appointment letters

-  Transmission of pertinent visit information to the national database
   at AITC

-  ICD-10 code compliant

Ambulatory Care Reporting Project (ACRP)

-  Provides clinical, diagnostic, and administrative data to assist in
   determination of resource utilization, corporate costs, forecasting,
   and healthcare planning. Identifies date, time, and provider of
   services provided, patient demographic data, and transmission of
   workload credit data to the National Patient Care Database (NPCDB)

-  VistA transmissions, error-handling and reporting options, and NPCDB
   are scheduled for decommission Oct 1 2018. Corporate Data Warehouse
   (CDWS) will store ambulatory care data and replace the error-handling
   features

Automated Service Connected Designation (ASCD)

-  Automates Service Connected (SC) or Non-Service Connected (NSC)
   designation based upon clinician input (e.g., ICD or Related
   Disability Codes) during encounter processing

-  Lists potential billable and non-billable encounters

-  Dual eligibility encounters require additional human intervention

Electronic Wait List (EWL)

-  Automatically places patients on a Wait List or multiple Wait Lists
   for a Primary Care team or position, scheduling service/specialty, or
   specific clinic

-  Provides reporting capabilities

-  Places patients on wait lists as needed when appointments are
   cancelled by the clinic

Primary Care Management Module (PCMM)

-  Assists in maintaining accurate patient listings for primary care
   teams and panels, providing a Graphical User Interface (GUI) for
   creating positions and assigning staff to teams, as well as for
   assigning/un-assigning patients to primary care teams and providers’
   positions

-  PCMMR is being implemented as a web-based replacement for PCMM

Recall Reminder

-  Provides prompts to clinic staff for patients requiring return
   appointments when those appointments are greater than 90-120 days in
   the future

-  Produces clinic recall letters or cards for patients to encourage
   them to schedule appointments

VistA Scheduling Enhancement (VSE)

-  VSE is a Graphical User Interface (GUI) software module that allows
   schedulers to make appointments quickly by viewing multiple
   appointment request types and multiple clinics in one screen

-  A scheduler can easily view patient requests for service, find the
   next available open appointment, view the provider’s availability in
   multiple clinics, and track a patient’s appointment process

   1. .. rubric:: 
         Shift Handoff Tool
         :name: shift-handoff-tool

**Version**: 1.0

**Namespace:** CRHD

**Brief Description:** The Shift Handoff Tool standardizes information
exchanged between clinicians as they transfer patient care
responsibilities incidental to changes of shifts.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Services,
Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Patient Care Services (PCS)

**VASI ID:** 1591

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123224/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=175

**Full Description and Features:** The Shift Handoff Tool had its
beginnings in the "CAIRO" product originally developed by the
Indianapolis VAMC Development Group. Shift Handoff Tool provides
standard data elements such as Do Not Resuscitate, Allergies,
Medications, Problems, History and Physical, Admitting Diagnosis, Labs,
and Consults as part of the information elements routinely communicated
between Clinicians (e.g., Physicians, Nurses, Pharmacists) at shift
handoff.

This multidisciplinary tool yields clear, readable and
standardized-format communications that enhance patient safety and
efficacy of care. The tool allows for information to be updated and
shared electronically.

Standards and Terminology Services (STS)
----------------------------------------

**Version**: 1.0

**Namespace:** Multiple Namespace

**Brief Description:** STS is the authoritative source for clinical and
administrative data standards for the VHA.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utlize Information
Technology Services

**VHA Portfolio:** Health Data Systems

**Business Owner:** OIA

**VASI ID:** 1610

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123235/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=191

**Full Description and Features:** In 2003, Enterprise Terminology
Services (ETS) was formed as a subproject of the Health Data Repository
(HDR) project to help standardize the terminology reference files that
are used by Veterans Health Information Systems and Technology
Architecture (VistA) applications through the Veterans Health
Administration (VHA). In FY06, ETS merged with the Data Standardization
(DS) and Standard Data Service (SDS) project teams into one team,
becoming Standards & Terminology Services (STS).

Historically, VistA applications were developed in a decentralized
manner and could be specialized in response to the needs of individual
medical centers. As a result, VistA terminologies were not always
standardized. Today, there is a shift toward enterprise-wide terminology
standards, which are essential to establish consistency in meaning of
data within VHA as a whole. The shift from dispersed, non-standard
terminologies to a controlled, centralized terminology helps VHA meet
requirements for an authoritative, longitudinal, accessible, and
portable electronic health record (EHR).

STS has worked closely with VHA stakeholders and partners to develop and
maintain both the Enterprise Reference Terminology (ERT) content and VHA
Enterprise Terminology Services (VETS) application and runtime services.
STS software includes databases and tools that are used to maintain
terminology content. ERT content ranges from simple lists of
standardized terms to reference terminologies with fully populated
semantics such as the National Drug File Reference Terminology (NDF-RT).

VETS software includes the databases and services that provide the
terminology content to STS stakeholders. VETS includes deployment and
application runtime services that will provide common access to ERT
content in both the current VistA and future My HealtheVet VistA
environments. STS has created and documented a Terminology Model, which
will be used internally to structure ERT data and to provide services to
VHA clinical applications. The model also supports data interchange
within VHA and with various government and commercial partners.

The VETS applications are:

**NTRT (New Term Rapid Turnaround)**

A web application that is has two groups of users: external request
submitters and internal

terminologists. Clinicians from the VA Medical Centers obtain an NTRT
login (provided by STS) that enables them to request new terms to be
added to the standardized VistA packages (Allergies, Vitals, TIU,
Pharmacy). When a request is submitted, STS terminologists then use the
NTRT application to track the request through a review process to
determine if the request is valid.

**TDS (Terminology Deployment Services)**

A web application that only STS terminologists use to version and deploy
standardized VHAT

(VHA Terminology) content and Map Sets. NTRT requests that are approved
are versioned in

TDS and after a rigorous testing process are deployed to all 129 VistA
production sites using TDS.

**Terminology Browser**

A web application that is available to the entire VA enterprise. This
tool allows users to browse

Standard Code Systems (SCS) like SNOMED or ICD-9, Map Sets that contain
mappings, and

VHAT terminology by domain (e.g. Allergies) or subset (e.g. Reactions).
This tool was published in VETS v9.

**TED (Terminology Editor)**

A web application that allows STS terminologists to author new Map Sets
that contain mappings. This is a Graphical User Interface editor tool
that was created to replace importing content using XML files. This is
new for VETS v10.

**VUID (VHA Unique Identifier Service)**

A web application that allows users that have a valid login (both
internal and external to STS) to

request one or more VUIDs to use for terminology standardization
purposes.

See Also - Health Data Informatics, Lexicon Utility.

See additional VDL links below to STS applications:

• `Standards & Terminology Services
(STS) <https://www.va.gov/vdl/application.asp?appid=191>`__

• `Current Procedural Terminology
(CPT) <https://www.va.gov/vdl/application.asp?appid=33>`__

• `Enterprise Terminology Services
(ETS) <https://www.va.gov/vdl/application.asp?appid=226>`__

• `Lexicon Utility <https://www.va.gov/vdl/application.asp?appid=76>`__

• `Health Data Informatics
(HDI) <https://www.va.gov/vdl/application.asp?appid=148>`__

• `ICD-9-CM <https://www.va.gov/vdl/application.asp?appid=136>`__

-  Provides an overall terminology model for VHA that supports clinical
   data entry, retrieval, aggregation, and processing.

-  Supports information processing for decision support systems.

-  Supports concept mediation, mappings, and translation between code
   systems using Health Information Technology Standards Panel (HITSP)
   and other standards.

-  Supports the use, maintenance, versioning, and updating of code
   systems from standards development organizations (SDOs) that are
   required by statute, mandated by an oversight body, or required by
   VHA business needs.

-  Provides a concept based, controlled medical vocabulary for VHA.

-  Supports VHA Health Information Models, including detailed models
   that are used by specific applications and their terminologies.

-  Supports semantic comparisons between concepts.

-  Supports the deployment of standardized reference files to VistA
   sites as VistA patches or VETS deployment sets.

-  Implements the New Term Rapid Turnaround (NTRT) process to facilitate
   timely updates to standardized reference files after they are
   deployed on a domain-by-domain basis.

   1. .. rubric:: 
         Surgery
         :name: surgery

**Version**: 3.0

**Namespace:** SR

**Brief Description:** The Surgery package is designed to be used by
Surgeons, Surgical Residents, Anesthetists, Operating Room Nurses and
other surgical staff. The Surgery package is part of the patient
information system that stores data on the Department of Veterans
Affairs (VA) patients who have, or are about to undergo, surgical
procedures. This package integrates booking, clinical, and patient data
to provide a variety of administrative and clinical reports.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Deliver Health Care

**Business Function Framework Function(s):** Perform Hospital
Administration, Monitor Clinical Performance, Provide Medical Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** National Surgery Office

**VASI ID:** 1046

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122750/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=103

**Full Description and Features: **

In the operating room, the software provides on-line access to the
clinical record and automatically generates post-operative reports,
including the Nurse Intraoperative Report. Automated scheduling provides
better operating room utilization and greater ease in distributing the
operating room schedule, and the software generates monthly, quarterly,
and annual surgical reports, thus reducing the amount of clinical
overhead associated with the management of the Surgical Service. The
Surgery software facilitates morbidity and mortality tracking and other
complications, providing vital information to the Chief of Surgery and
to VA Central Office.

-  Allows a surgeon to generate requests for surgical procedures

-  Allows operating room scheduling managers to assign operating rooms
   and time slots and generates operating room schedules

-  Allows for the rescheduling or cancellation of operative procedures

-  Facilitates entry of information specific to an individual surgical
   case (e.g., staff, times, diagnoses, complications, anesthesia)

-  Provides for on-line entry of data inside the operating room during
   the actual operative procedure

-  Generates patient records and nurse reports

-  Produces management reports (e.g., Annual Report of Surgical
   Procedures, Attending Surgeons Report, Nurse Staffing Report, and
   Anesthesia Management)

-  Produces quarterly and annual reports for VA Central Office

-  Provides secured access to lists of cancellations and the Morbidity
   and Mortality Report

-  Extracts data necessary to monitor risk management issues

-  Provides additional checks for Transfusion Error Risk Management

-  Includes a generic Health Level Seven (HL7) interface for use with
   commercial Automated Anesthesia Information Systems

-  Includes an interface to the Patient Care Encounters (PCE) software
   that allows ambulatory procedure workload information to be
   transmitted to the National Patient Care Database (NPCD) at AITC

-  Allows for on-line electronic signature of the Nurse Intraoperative
   Report and the Anesthesia Report

-  ICD-10 code compliant

   Risk Assessment

-  Provides tracking mechanism for both surgical risk and
   observed-to-expected (O/E) risk- adjusted outcomes across facilities
   for all surgeries for eight major sub-specialties and for cardiac
   surgery

-  Provides for entry of non-cardiac assessment information including
   pre-operative information, laboratory test results, operation
   information, and intraoperative and post- operative occurrences

-  Provides for entry of cardiac assessment information, including
   clinical information, cardiac catheterization and angiographic data,
   operative risk summary data, cardiac procedures requiring
   cardio-pulmonary bypass, and intraoperative and post-operative
   occurrences

-  Creates a Surgery Risk Assessment on each patient assessed and lists
   these by categories including complete, incomplete, and transmitted
   assessments, as well as list of major surgical cases and all surgical
   cases

-  Generates monthly Surgical Case Workload Report

-  Prints follow-up letters to patients 30 days after a procedure

   1. .. rubric:: 
         Survey Generator
         :name: survey-generator

**Version**: 2.0

**Namespace:** QAP

**Brief Description:** The Survey Generator is a software package which
allows creation and maintenance of computerized survey forms.

**Business Function Framework Line(s) of Business:** Provide Healthcare
Administration

**Business Function Framework Function(s):** Manage Customer Relations,
Utilize Information Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** VHA

**VASI ID:** 1842

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123412/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=27

**Full Description and Features: **

The Survey Generator is a software package which allows creation and
maintenance of computerized survey forms. It also provides for entry of
any respondents answers via computer terminal or a hard copy filled out
and then entered by any designated person. In addition, it provides
useful statistical information by survey alone or by demographic data
items.

This package is designed with both the survey author and the respondent
in mind. It is simple to use and straightforward in operation and does
not require any exceptional skills on the user's part.

Veterans Crisis Line (VCL)
--------------------------

**Version**: 1.0

**Namespace:** VCL

**Brief Description:** The Veterans Crisis Line (VCL) Application
replaces the manual call log (paper log documents) using a web-based
application and allows for a seamless transition from VA Suicide
Prevention Hotline to Suicide Prevention Coordinator (SPC).

**Business Function Framework Line(s) of Business:** Suicide Prevention

**Business Function Framework Function(s):** Suicide Prevention

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Mental Health

**VASI ID:** 1619

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123242/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=78

**Full Description and Features:** Mental Health Services (MHS) is
currently managing a web-based application (herein referred to as the
Veterans Crisis Line Application (VCL)) utilized by their confidential,
free 24-hours hotline staff to make referrals to the appropriate
field-based Suicide Prevention Coordinators (SPCs).

History: VCL Project is an important function to support recent suicide
prevention legislation. The Department of Veterans Affairs (VA) has
begun operation of the national suicide prevention hotline (now called
VCL) to ensure that veterans with emotional crises have round-the-clock
access to trained professionals. The VA is partnering with the Substance
Abuse and Mental Health Services Administration (SAMHSA) of the
Department of Health and Human Services (HHS) and the National Suicide
Prevention Lifeline to operate the national hotline. Veterans can call
1-800-273-TALK (8255) and press "1" to reach the VA hotline, which is
staffed by mental health professionals 24/7/365 in Canandaigua, N.Y. who
work closely with the callers’ local VA Suicide Prevention Coordinators
and mental health providers to help the callers.

Legislation has been passed requiring VHA to take specific actions in
the effort to prevent Veteran suicides. On November 6, 2007, President
Bush signed into law the Joshua Omvig Veterans Suicide Prevention Act.
It’s named after a soldier who committed suicide in Grundy County, Iowa,
in December 2005, after serving an 11-month tour in Iraq. The bill
requires the Department of Veterans Affairs to meet deadlines in
providing the following services:

• Train VA staff on suicide prevention and mental health care

• Staff each VA medical facility with a suicide prevention counselor

• Screen soldiers who seek care through the VA for mental health needs

• Support outreach and education for veterans and their families

• Research the most effective strategies for suicide prevention

• Create a peer support counseling program so veterans can help other
veterans

However, while the bill requires the VA to provide these services, it
provides no funding.

On February 6, 2008, Representative Leonard Boswell (D-IA) and
Representative Robin Hayes (R-NC) introduced the Armed Forces Suicide
Prevention Act (H.R. 5223). This bill is focused on Department of
Defense implementing a comprehensive suicide prevention program within
all branches in the military, including National Guard and the Reserves.
The Air Force implemented a suicide prevention program in the 1990’s. By
2002, the suicide rate had declined by 33% and researchers found a
decrease in violent crime and family violence after program
implementation. This bill is designed to help the VA and Department of
Defense deal with the increase in mental health needs of Iraq and
Afghanistan service personnel. Both VA Central Office and Congress want
periodic reports relating to Veteran suicide and suicide prevention
efforts.

Tracking cases may also allow for best practice identification. The
Suicide Prevention Hotline Web Application went live, nationwide, on
6/9/2009 and the first update was put into production on
11/22/2010.Description of Current VCL Application: The VCL application
provides an electronic version of the call log via a web-based
application. VCL also stores information from hotline calls, which
provides the ability to retrieve and view call information as needed.

The VCL application has three components:

-  Log Application used at the VA Suicide Prevention Hotline by Health
   Services Specialist (HSS) to log calls

-  Response Application used at VA facilities by Suicide Prevention
   Coordinators (SPCs) to document referrals and save them in the
   Computerized Patient Record System (CPRS) as Progress Notes

-  Admin Component which is nested with the Health Techs (HT)
   application. This component is used by hotline administrators and
   Social Services Assistants (SSA) to audit and administer the system

   -  In the Admin view, the Log Application stores call information
      that can later be used for data collection and reporting purposes.

   -  In the Admin view, the Log Application provides a mechanism for
      hotline staff to view Veteran demographic information. The
      application also provides the risk assessment module and the
      ability to identify the VA Medical Center (VAMC) closest to the
      caller’s physical location.

   -  In the admin view, the Log Application provides a means to refer a
      caller to a VAMC for follow-up care. The referral is directed to
      the VA Medical Center’s SPC in real time.

   -  The SPC Response Application allows the ability to document the
      hotline referral in CPRS in the form of a Text Integration Utility
      (TIU) Progress Note.

   -  The SPC Response Application ensures all progress notes have a
      common note title.

   -  The SPC Application is automatically updated when a SPC completes
      the referral process.

   1. .. rubric:: 
         Veterans Health Identification Card (VHIC)
         :name: veterans-health-identification-card-vhic

**Version**: 4.8

**Namespace:** WEBC

**Brief Description:** The VHIC serves as an identification mechanism
for Veterans that are enrolled in the VA Healthcare system and supports
efficiencies at VA medical facilities throughout the United States.
Although not required by Veterans to receive medical care at a VA
facility, it does enable Veterans to check in for VA appointments more
quickly. The VHIC system is a web-based application that VHIC Associates
use to issue VHICs to enrolled Veterans.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Provide Health Care Administration, Deliver Healthcare

**Business Function Framework Function(s):** Provide Member Access,
Perform Hospital Administration, Manage Health Records

**VHA Portfolio:** Business Informatics

**Business Owner:** CBO

**VASI ID:** 1710

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123177/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=140

**Full Description and Features:** The VHIC displays a color photograph
of the veteran and the veteran’s name, as well as other information
about the veteran such as branch of service, service connected, medal of
honor, purple heart, and former POW. VHIC system, which is a web based
application, allows the user to take a color photograph of the veteran
through a web browser. Identity proofing of the veteran is required, and
this service is provided by the Identity Access Management system.

Once the Health Eligibility Center (HEC) has verified the patient’s
eligibility and the veteran has been assigned an appropriate enrollment
status, the veteran's photograph and data are transmitted to the
external card print vendor using secure protocols. The external card
print vendor creates the VHIC card and mails it to the veteran.

The VHIC can show the following information on the card as applicable to
the Veteran:

-  Veteran's name

-  Veteran's photograph

-  Service connected

-  Medal of Honor

-  Purple Heart

-  Prisoner of War

-  Branch of Service

-  Other information on the card is the Veteran's Member ID number and
   Plan ID number

   1. .. rubric:: 
         Veterans Personal Finance System (VPFS)
         :name: veterans-personal-finance-system-vpfs

**Version**: 1.1.3

**Namespace:** VPFS

**Brief Description:** The Integrated Patient Funds software automates
the "bank-like" functionality that VA provides for patients to manage
their personal funds while hospitalized in a VA medical facility.

**Business Function Framework Line(s) of Business:** Provide Healthcare
Administration

**Business Function Framework Function(s):** Perform Hospital
Administration

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1751

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123428/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=170

**Full Description and Features: **

VPFS replaces the Personal Funds of Patients (PFOP) system that was used
previously. VPFS looks different from PFOP because it is a web-based
application; however, its design and functionality are modeled after
PFOP. You can perform all of the functions in VPFS that were available
in PFOP, with the exception of a few functions that are no longer needed
because of the new built-in security controls. One of the major changes
is that VPFS is a centralized system. With PFOP, each site used a
stand-alone copy of the software and there were differences between
local versions, such as data structures, business rules, etc. With VPFS,
all sites access the same centralized application using a web browser
over the VHA secure Intranet. VPFS stores all data for all sites in one
centralized database. Access to the data in the database is controlled
by security software that limits access according to VistA site and user
role.

Veterans Point of Service
-------------------------

**Version**: 1.0

**Namespace:** VPS

**Brief Description:** Point of Service supports the VHA’s
implementation of interactive kiosks which allow Veterans and VA staff
to perform a variety of administrative, financial and clinical tasks.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Business Informatics

**Business Owner:** CBO

**VASI ID:** 1752

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123429/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=209

**Full Description and Features: **

The VA's vision for the VETLINK VA Point of Service (VPS) kiosk is to
streamline and improve patient clinical and administrative processes
across the VA healthcare network and to provide standard, easy- to-use
capabilities for patients and employees to access and update information
and perform business transactions through incremental releases. The VA’s
vision includes a modular and configurable solution that may be tailored
to fit each facility's individual needs. The VETLINK VPS Kiosk
Application Server uses the RPC BROKER to make calls to the Remote
Procedures (RPCs) residing on the VistA host.

-  VPS KIOSK INTERFACE: This broker type option contains the RPCs that
   support the VPS Kiosk system. The VETLINK VPS Kiosk system will call
   upon these RPCs for specific events triggered by the kiosk machine
   accessed by a patient (e.g., at check-in) or by VAMC staff. The
   following remote procedures are attached to this menu

-  VPS GET PATIENT DEMOGRAPHIC: This RPC will accept patient SSN as
   input then retrieve patient demographic data from VistA

-  VPS GET CLINIC: This RPC will accept a partial or full Clinic Name as
   input then retrieves Clinic IEN, Clinic Name, Clinic Physical
   Location from VistA based on the matching Clinic Name characters from
   the INPUT String

-  XWB GET VARIABLE VALUE: This pre-existing RPC BROKER RPC accepts the
   name of a variable that will be evaluated and its value returned to
   the server. For example, this RPC may be called with a parameter like
   DUZ that will be returned as 123456

-  ORWPT FULLSSN: This pre-existing OE/RR RPC accepts an SSN in the
   format 999999999(P), and returns a list of matching patients

-  ORWPT LAST5: This pre-existing OE/RR RPC returns a list of patients
   matching the string of Last Name Initial Last 4 SSN (Initial/Last 4
   look-up to PATIENT file)

-  ORWPT LIST ALL: This pre-existing OR/RR RPC returns a set of patient
   names for use with a long list box

-  CONNECT,VPS: VPS connector proxy account that is added to the NEW
   PERSON file (#200) that is used to configure the VETLINK VPS Kiosk

-  VPS RETRIEVE PATIENT VITALS: This RPC will retrieve and display
   patient vitals data read from the VistA Vitals package

-  VPS STORE VITALS: This RPC provides the capability for consuming
   application user interfaces to enter patient vitals data
   (temperature, blood pressure, pulse) into the VistA Vitals package

-  VPS ENHANCED GET PATIENT DEMO: This RPC retrieves patient health
   factors and inpatient status

-  VPS GET2 PATIENT DEMOGRAPHICS: This RPC retrieves the patient
   demographic data from the given patient SSN, DFN, ICN or VIC/CAC

-  VPS SAVE CLINICAL SURVEY: This RPC provides the capability to enter,
   store and view patient Clinical Screening Questionnaires through the
   consuming application interface

-  VPS GET SURVEY DATA: This RPC retrieves a patient's clinical survey
   questionnaire information

-  VPS EDIT PATIENT DEMOGRAPHIC: This RPC receives the data request to
   make edits to the patient record in the PATIENT file (#2)

-  VPS PATIENT CHECK-IN: This RPC submits the check-in that is entered
   by VAMC staff or by self checking-in using a VIC card via the VETLINK
   VPS Kios

-  VPS PATIENT PRE-REGISTRATION: This RPC will accept the
   pre-registration request submitted by the VETLINK VPS kiosk

-  VPS GET SITES: This RPC will return the list of facilities at which
   the veteran was treated

-  VPS GET DFN: This RPC will return the patient DFN

-  VPS FULLSSN: This RPC returns a list of patients with associated SSNs
   that match the value stored in ID

-  VPS LAST5: This RPC returns a list of patients matching
   LastNameInitial\_Last4SSN based on Restricted Patient List

-  VPS LIST ALL: This RPC returns a list of patients matching input
   value if "NAME" or “IEN^NAME"

-  VPS WRITE MRAR PDO: This RPC retrieves patient's MRAR instance data
   values that is used to create the patient's MRAR PDO

-  VPS WRITE KIOSK PARAMETERS: This RPC retrieves and stores outpatient
   clinic kiosk configuration parameters used to define clinic kiosk
   functionality and device

-  VPS GET MRAR PDO: This RPC retrieves the patient's MRAR clinical data
   to provide PDO output

-  VPS GET LAST MRAR: This RPC retrieves an identified patient's MRAR
   clinical data

-  VPS UPDATE LAST MRAR TIU IEN: This RPC updates an identified
   patient's most recent MRAR clinical data with applicable TIU document
   internal entry number (IEN)

-  VPS PRINT PATIENT LABEL: This RPC prints the patient label using the
   standard VistA print patient label routine (DGPLBL)

-  VPS GET CLINICAL REMINDERS: This RPC retrieves clinical reminder
   applicable to a patient and "Due Now"

-  VPS PATIENT WRISTBAND PRINT: This RPC prints a patient wristband with
   barcode to a VistA printer in a secure area. This RPC requires the
   printer device name, patient identifier type, and a patient
   identifier of the specified type

-  VPS GET PRINTERS: This RPC works with common application program
   interfaces (APIs) to support VPS printing functionality

-  VPS GET ALL CLINICS: This RPC retrieves a list of hospital locations
   defined in the HOSPITAL LOCATION file (#44)

-  VPS GET APPOINTMENTS: This RPC retrieves all appointments for a
   patient in a given date range

-  VPS GET CHANGED APPOINTMENTS: This RPC retrieves the appointments
   that have changed since the last execution of the VPS GET APPOINMENTS
   RPC

   1. .. rubric:: 
         Virtual Electronic eHealth Exchange (VLER)
         :name: virtual-electronic-ehealth-exchange-vler

**Version**: 6.0.1.3

**Namespace:** NHIN

**Brief Description:** The Virtual Lifetime Electronic Record (VLER)
Health Program allows VA, non-VA health care providers, and Veterans to
securely share certain health information from a Veteran’s health record
electronically.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=195

**Full Description and Features:** The VA eHealth Exchange program will
ensure that appropriate medical information is shared through secure and
interoperable information management systems, making the necessary
information available to those who need it, when they need it, and in a
form that is suited to the stakeholders’ needs.

The Department of Veterans Affairs (VA), Department of Defense (DoD),
and other partners also understand that there is a compelling need to
promote the sharing of health information not only with other government
agencies but also with private sector healthcare entities to provide for
the continuity and quality care of all veterans. eHealth Exchange is
designed to give both VA clinicians as well as external eHealth Exchange
partners immediate access to vital Veteran health record information at
the point of care, either within a VA facility or at a participating
partner facility, and therefore has the potential to improve the quality
of care for all Veterans.

eHealth Exchange is a query-based exchange where a clinician from one
organization can request, receive and display health information from
other participating organizations that know the patient. The health
information exchanged is primarily a health summary document knows as a
Continuity of Care Document (CCD or C32) and associated clinical notes.

Virtual Patient Record (VPR)
----------------------------

**Version**: 1.0

**Namespace:** VPR

**Brief Description:** Virtual Patient Record (VPR) is a foundation
software package component of the Health Management Platform
architecture. This architecture is part of the scope of the Health
Informatics Initiative and Healthshare.   The Joint Legacy Viewer is
highly dependent on the payloads from the VPR routines.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Dr. Margaret Donahue

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=197

**Full Description and Features:** VPR extracts patient data from
domains at local and remote VistA sites to provide a cached view of
patient charts. It provides normalized fields with common field names
and data structures across domains. VPR includes four remote procedure
calls (RPCs), which extract data from VistA in different formats (JSON,
XML) and returns the current version number for VPR. Software has
patient record JSON data export capability.

VistA Imaging System
--------------------

**Version**: 3.0

**Namespace:** MAG

**Brief Description:** VistA Imaging facilitates medical decision-making
by delivering complete multimedia patient information to the clinician’s
desktop in an integrated manner. Windows-based workstations, which are
interfaced to the main hospital system in a client-server architecture,
make images and associated text data available at all times anywhere in
the hospital or across VA.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Ancillary Services,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Chief Consultant, Diagnostic Services

**VASI ID:** 1328

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122887/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=105

**Full Description and Features:** VistA Imaging handles high quality
image data from many specialties, including cardiology, dermatology,
ophthalmology, pulmonary and gastrointestinal medicine, pathology,
radiology, hematology, and nuclear medicine. VistA Imaging can also
provide text reports from the hospital information system, scanned
documents, and electrocardiograms. VistA Imaging is integrated with the
Computerized Patient Record System ((CPRS), Joint Legacy Viewer (JLV),
Joint Legacy Viewer-Community Viewer (JLV-CV), MyHealthEVet (Blue
Button), Image Viewer Service (IVS-Mobile Apps), Embedded Fragment
Registry (EFR), DocRef, and After Visit Summary (AWS), to provide a
comprehensive electronic patient record with access to images from
across VA as well as DoD, and provides VA images to DoD as well. VistA
Imaging’s diagnostic display software (VistARad) can be used when a
commercial Picture Archiving and Communication System (PACS) is
unavailable for the filmless interpretation of radiology studies and for
workflow management.

VistA Imaging is made up of the following components:

-  Core Infrastructure

-  Document and Ancillary Imaging

-  Filmless Radiology

-  Telemedicine

-  Provides capture, display, manipulation, and management functions for
   a wide variety of medical images such as radiographs, sonograms, EKG
   tracings, gastroenterology studies, pulmonary bronchoscope exams,
   podiatry, dermatology, and ophthalmology images. VistA Imaging can
   store and display any sort of multimedia data, including digital
   images, motion video clips, graphics, scanned documents, and audio
   files

-  Integrated with CPRS, Joint Legacy Viewer (JLV), Joint Legacy
   Viewer-Community Viewer (JLV-CV), MyHealthEVet (Blue Button), Image
   Viewer Service (IVS-Mobile Apps), Embedded Fragment Registry (EFR),
   DocRef, and After Visit Summary (AWS), allowing users to view images
   automatically for a selected patient. When a user views a radiology
   report, consult, or progress note in CPRS, the associated images are
   easily available

-  Provides a standard interface between VistA and commercial PACS

-  Automatically acquires complete studies from DICOM-compliant
   modalities (CT, MRI, digital X-ray, ultrasound, etc.), associates the
   studies with the correct patient and report, and stores the studies
   in VistA Imaging for inclusion in the electronic patient record

-  Provides image file storage, management, and retrieval from magnetic
   and optical disk servers and supports data capture, storage, and
   retrieval over a local or wide area network (LAN/WAN)

-  Provides access to electronic medical records from remote VA medical
   facilities over the VA intranet

-  Has the ability to track and report the cumulative dose of radiation
   received per patient during specific radiological imaging procedures

-  Track and report cumulative radiation dose per patient during
   specific procedures

-  Supports multiple modality work list capability for different
   clinical subspecialties

-  Allows for DICOM storage commitment

-  Enables transmission of HL7 messages for CPRS consult request
   tracking orders and reports and Admission, Discharge, Transfer (ADT
   and patient tracking to be transmitted to external systems, like
   Cardiology PACS and Eye Care PACS

-  Provides a VistA Imaging Release of Information (ROI) disclosure
   service that runs on the local VIX server

-  Enables a telepathology solution that includes the VistA Imaging
   Telepathology Applications (VITA). This includes the VistA Imaging
   Telepathlogy Worklist and VistA Imaging Telepathology Configurator.
   The VITA provides a graphical user interface that pathologists can
   use to view daily workload at their sites. for Surgical Pathology
   (SP), Cytopathology (CY) and Electron Microscopy cases (EM). At this
   time the applications will not be in support of autopsy cases. It
   also provides a graphical interface that site administrators can use
   to set some configuration parameters for the VistA Imaging
   Telepathology Work list and to view the VITA and the system logs

-  Provides Zero footprint HTML5 based image viewer to support viewing
   images in VA Web Applications such as JLV, JLV-CV, MyHealthEVet (Blue
   Button), and the like. The Zero Footprint image viewer can be invoked
   by client software interacting with any VIX instance

**Core Infrastructure**

-  Includes the components used to capture, store, and display all types
   of images. Images can be captured using video cameras, digital
   cameras, document scanners, x-ray scanners, and imported files
   created electronically by commercial systems. Images can also be
   directly acquired from DICOM-compliant devices such as CT scanners,
   MR scanners and digital x-ray machines. Components include:

   -  DICOM text gateways, which provide patient and order information
      to medical devices (such as CT scanners and digital radiography
      systems), allowing selection of the examination to be performed.
      The data provided by DICOM text gateways complies with the DICOM
      Modality Work list standard.

   -  DICOM image gateways, which allow VistA Imaging to receive images
      from PACS or acquisition devices. Image gateways can also be used
      to transfer images from the VistA system to any DICOM-compliant
      devices for display, printing, or teleradiology, and telemedicine
      purposes.

   -  Windows-based workstation software for clinical image display and
      capture.

   -  The Background Processor, which manages image storage on various
      network devices, including magnetic storage (RAID) and optical
      storage (jukebox/archive appliance/storage grid) as a long-term
      archive.

   -  The VistA Imaging database, which manages image information and
      the relationship between images and study data.

   -  The commercially available equipment required by VistA Imaging,
      including magnetic servers, optical disk jukeboxes, archive
      appliances, and utility workstations.

Features of the Core Imaging Infrastructure:

-  Acquires images and multimedia data

-  Stores images to allow immediate access and long-term permanent
   storage

-  Communicates and displays images in a timely manner

-  Processes various types of images from multiple specialties

-  Links images to the VistA integrated patient record so that they can
   be retrieved by patient or study/progress note

-  Protects security and privacy of images, and prevents alteration of
   images after capture.

-  Provides access to available DoD images

-  Enables remote viewing and capture of images

-  Automatically acquires complete studies from DICOM-compliant
   modalities (CT, MRI, digital x-ray, ultrasound, etc.), associates the
   studies with the correct patient and report, and stores the studies
   in VistA Imaging for inclusion in the electronic patient record

-  Provides image file storage, management, and retrieval from magnetic
   and optical disk servers and supports data capture, storage, and
   retrieval over a local or wide area network (LAN/WAN)

-  Provides access to electronic medical records from remote VA medical
   facilities over the VA intranet

-  Provides access to available DoD images

Document and Ancillary Imaging provides document imaging and management
and integration to the medical record.

DOCUMENT IMAGING allows scanned and electronically generated documents
to be associated with the online patient record and displayed on
clinical workstations.

Benefits and features include:

-  Online availability of all information in the electronic patient
   record, including handwritten papers, drawings, signed documents, and
   medical correspondence

-  Linkage of paper-based patient information to the electronic patient
   record, making all patient information quickly available and easily
   retrievable through a single workstation

-  Immediate availability of critical documents, such as advance
   directives and informed consent forms, at the time they are needed

-  Elimination of lost or misfiled medical chart information

-  Interfaces to commercial document scanning systems and systems that
   generate documents electronically

-  Scanning and indexing of black-and-white, grayscale, and color
   documents, including: signed advance directives, consent forms,
   annotated drawings, external medical records documents, and
   administrative documents such as Means Test forms

-  Ability to annotate standard online diagrams and save the annotated
   diagrams with a progress note

-  Document image storage in short- and long term- storage devices

-  Display and printing of document images for clinical and
   administrative purposes

ANCILLARY IMAGING captures, stores, and displays images for a particular
service or specialty. This may be accomplished using the Clinical
Capture workstation or by interfaces to commercial systems.

Features include:

-  Interfaces to commercial EKG systems for display of
   electrocardiograms on clinical workstations. Supports automatic DICOM
   interfaces for capture of specialty images from compliant systems
   (DICOM Modality Worklist Conformance Requirements are provided to
   sites purchasing specialty equipment)

-  Processes various types of images from multiple specialties. DICOM
   and Clinical Workstation support for ophthalmology, dental,
   endoscopy, pathology, cardiology, and other specialties is provided

-  Links images to the VistA integrated patient record so that they can
   be retrieved by patient or study/progress note

-  Protects the security and privacy of images, and prevents alteration
   of images after capture

Filmless Radiology uses high-resolution workstations and high-speed
servers to allow radiology departments to operate without generating
x-ray film when a commercial Picture Archiving and Communication System
(PACS) is unavailable. Workstations running VistARAD, VistA Imaging’s
diagnostic image display software, are used by radiologists for the
online interpretation of images acquired by CR, CT, MRI, and other
modalities.

Features include:

-  Highly customizable hanging protocols

-  User-specific profiles that are applied regardless of login location

-  Integration with voice dictation systems

-  Automatic data integrity checks and notifications

-  Easy access to image review, analysis, and manipulation tools

-  Optional on-demand routing for telemedicine/teleradiology

-  Direct access to requisitions, reports, and health summary data

-  Compliant with HIPAA, the Federal Privacy Act, and VA security
   policies

-  Key image identification and saved annotations

-  A ‘ReadList’ function that allows a user to update the status of an
   open exam and immediately and display the next unread exam in a
   single step

-  Site-configurable exam lists

-  Supports viewing of available DoD radiology images

Telemedicine VistA Imaging Telemedicine provides immediate access to
images from anywhere in the VHA, including imported images and reports.
Functionality includes remote viewing and access to images during
disaster situations. This “Remote Image Views” capability allows access
to the complete electronic health care record no matter where the
patient is within the VA healthcare network.

Features include:

-  Immediate access to images from any other point on the VHA healthcare
   network without contacting the other facility

-  Avoidance of redundant testing that is often done in urgent
   situations if images and reports are not readily available

-  Reduction of patient wait times because all information is
   immediately available.

-  More informed decision making because all images and reports can be
   reviewed, providing a clear picture of the patient’s care in the past
   and of the treatment the patient has been receiving

-  No need to make hard copy of images or films to send with the patient
   for a referral visit to another VAMC

-  Images and reports from studies done at hospitals outside the VA
   network, once imported into VistA Imaging, are available immediately
   everywhere

-  Patients can view their own images with their clinician, even if
   those images are stored at another facility

-  Clinicians can access all images and scanned documents locally at the
   site or from remote clinics/locations

In case of disasters, the images of displaced patients are available at
other VA facilities.

Visual Impairment Service Team
------------------------------

**Version**: 4.0

**Namespace:** ANRV

**Brief Description:** The Visual Impairment Service Team (VIST) module
enhances the efficiency of the Visual Impairment Service Team programs
within the Department of Veterans Affairs (VA).

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Care Management,
Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=106

**Full Description and Features:** With this program, Visual Impairment
Service Teams are able to easily manage and track activities and
services provided to blind Veterans in their service area. This program
integrates several fields of patient data to produce a variety of
reports. The VIST patient record printout can be used in place of VA
Form (10-1371) and is a more versatile document than the card. Semi-
annual Automated Management Information System (AMIS) reports can be run
and Veterans can be added or deleted from the rolls as indicated.

-  Enhances the efficiency of the Visual Impairment Service Team
   programs

-  Provides a way to easily track and manage activities and services
   provided to blinded veterans

-  Provides a wide variety of reports based on patient data. Blinded
   veterans can be quickly added or deleted from the rolls

   1. .. rubric:: 
         Vitals/Measurements
         :name: vitalsmeasurements

**Version**: 5.0

**Namespace:** GMRV

**Brief Description:** The Vitals/Measurements application is designed
to store, in the patient's electronic health record, all vital signs and
various measurements associated with a patient's hospital stay or
outpatient clinic visit. Data entered can be accessed by several VistA
(Veterans Health Information Systems and Technology Architecture)
applications (e.g., Health Summary) that interface with the
Vitals/Measurements application.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Patient Care Services (PCS)

**VASI ID:** 1854

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123335/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=107

**Full Description and Features:** The Vitals application is composed of
two modules: Vitals and Vitals Manager. Each module is accessed
separatelythrough the GUI executable icons on the user's desktop. The
Vitals module is used to enter patient data, and isassigned to clinical
staff. The Vitals Manager module is used to manage the Vitals templates
and abnormal valuesranges, and is assigned to the Clinical Application
Coordinator, package coordinator, and Information ResouceManagement
Service (IRMS) staff.

-  Provides a Graphical User Interface (GUI) to make collecting and
   viewing of data easier

-  Supports documentation of a patient's vital signs (e.g., temperature,
   pulse, and respiration)

-  Tracks a patient's height, weight, central venous pressure (CVP),
   circumference/girth, and oxygen saturation via oximetry with
   supplemental oxygen information

-  Supports documentation of detailed or positional blood pressure for a
   patient (for example, bilateral blood pressures taken in a sitting
   position)

-  Displays latest information on all of the patient's
   vitals/measurements in both metric equivalents and U.S. customary
   units (when appropriate) along with the date/time the information was
   obtained and the name of the user who entered the information

-  Allows facilities to establish hospital-wide high and low values for
   most vital signs and measurements. Identifies abnormal values, those
   values outside the high and low range on vitals/measurements reports

-  Allows user to record a reason for the omission of a patient's
   vitals/measurements (such as Patient on Pass)

-  Associates qualifiers (alpha characters appended to the measurement's
   numeric value) to provide a more detailed description of the
   patient's vitals/measurements

-  Contains online help windows to assist users

-  Displays graphic reports on workstation monitors, and provides a
   variety of printable reports. Reports can be printed for an
   individual patient or for multiple patients

-  Provides APIs that pass patient vitals/measurements information
   within a specific date range to the other VistA applications

-  Provides compliance with the Clinical Context Object Workgroup (CCOW)
   standard. The CCOW standard provides a way for applications to know
   which other applications are currently running, and which patients
   are selected in those applications

-  Supports an interface to vital signs monitor connected to the
   workstation

-  Allows the site to configure the ORWT TOOLS MENU in the CPRS GUI to
   access the application

   1. .. rubric:: 
         Voluntary Service System
         :name: voluntary-service-system

**Version**: 5.3

**Namespace:** VSS

**Brief Description:** VSS is a national-level application replacing the
site-based Voluntary Timekeeping System (VTK); it is used to track and
manage the hours of service contributed by volunteers and volunteer
organizations at VA facilities.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Manage Human Resources

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Office of Voluntary Service Programs

**VASI ID:** 1483

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123058/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=135

**Full Description and Features:** The VSS application helps voluntary
staff accomplish their tasks more easily through a Web-based graphical
user interface. Users at the local and national level are able to
generate a wider array of reports about volunteers and sponsoring
organizations. In addition, volunteers are able to log their own hours
and print meal tickets themselves at secure log-in "kiosks." VSS users
interact directly with a national, centralized database, and
consolidated national reporting no longer requires data transmissions
back and forth between sites and the Austin Information Technology
Center (AITC). Direct access to data provides instantaneous updates and
up-to-minute reporting for all users. Central Office administrators and
voluntary staff thus have broader and more reliable data for managing
volunteer services.

-  Provides multi-lingual interaction with volunteers during log-in

-  Supports and enhances security for multiple division facilitie

-  Displays/prints entire master record for a single volunteer

-  Provides local printing of address labels and telephone lists

-  Reduces workload required to input mass award code changes

-  Prints individual meal ticket for volunteer after Auto Log-in

-  Provides real-time national reporting of data for all stations

   1. .. rubric:: 
         Women's Health
         :name: womens-health

**Version**: 1.0

**Namespace:** WV

**Brief Description:** The Women's Health (WH) application provides
tracking functionality for procedures of particular interest to women

patients (e.g., screening mammogram). The application provides a full
range of breast and gynecologic cancer

screening and tracking functions.

**Business Function Framework Line(s) of Business:** Manage Public
Health, Deliver Health Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Medical Registry
Service, Provice Medical Services, Utilize Information Technology
Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** Women's Health Services

**VASI ID:** 1846

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123416/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=109

**Full Description and Features:** Women's Health application is a
patient management tool for tracking the breast and gynecologic
treatment needsof women, the procedures they receive, and the
communications between healthcare staff and women regardingtheir
treatment and follow-up. The application also provides some program-wide
epidemiological reports whichare of use to clinicians and program
administrators.

The Women's Health software is composed of three main modules:

-  Patient Management

-  Management Reports

-  Manager's Functions

Patient Management is the portion of the software used to manage
individual patient care, that is, their procedures, due dates and
correspondence. Under the Patient Management menu it is possible to
maintain patient data such as the date of the next PAP smear, colposcopy
or mammogram, the patient's pregnancy and her EDC (due date), as well as
the patient's current PAP regiment. It is also possible to track the
patient's individual procedures: the date performed, the provider and
clinic, the results or diagnosis, etc. Notifications (letters and phone
calls) may also be tracked. A file of form letters has been included in
the software, and these letters may be edited and personalized for a
clinic's particular needs. Reminder letters can be queued months in
advance of a future appointment, then printed and mailed out shortly
before the tentative appointment.

Management Reports is the portion of the software used to print
epidemiological reports such as the number of women who received a
mammogram for the selected time period, or the number of patients having
abnormal PAP results during a selected time period. Under the Management
Reports menu it is possible to produce lists of patients who are past
their due dates for follow-up procedures. It is also possible to store
program statistics by date for later comparison of program trends and
progress.

Manager's Functions is that portion of the software that provides the
ADPAC with a set of utilities for configuring the software to the
specific needs of the site. It also provides utilities for other program
needs such as customizing tables, making special edits to patient data
(e.g., pregnancy log, PAP regiment log), printing notification letters,
running error reports, and documenting laboratory results. By using the
File Maintenance options under the Manager's Functions menu, it is
possible to maintain site specific parameters such as the text of form
letters, the types of notifications and their synonyms, how and when
letters get printed, and several defaults relating to dates.

Wounded, Injured and Ill Warriors
---------------------------------

**Version**: 1.0

**Namespace:** WII

**Brief Description:** Wounded Injured and Ill Warriors (WII) module was
developed as a tool to provide accurate and timely personnel and health
related data to the Department of Defense/Defense Finance and Accounting
Service (DoD/DFAS) supporting adequate maintenance of pay and
entitlements for all wounded warriors.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Services,
Provide Ancillary Services

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA

**VASI ID:** 1847

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123417/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=178

**Full Description and Features:** Through a collaborative effort
between VHA and DoD/DFAS, a Memorandum of Understanding (MOU) was
reached to provide defined data elements to DFAS for tracking of active
duty service members who were admitted to VA inpatient facilities. The
MOU established the authorities and agreement for the exchange of
information relating to admissions and discharges from VA inpatient
facilities of active duty personnel. There is a weekly collection
process of admissions and discharges for active duty service members at
each VA inpatient facility. This collection and consolidation of data
into a single repository is reviewed and transmitted to DFAS to a
central data collection point. Each facility runs the weekly background
job which collects data based on admissions and discharges for patients
with a Primary or Other Eligibility of TRICARE, SHARING AGREEMENT or
OTHER FEDERAL AGENCY. Upon completion of the background job, VistA will
send an email message to the local WII ADT REVIEWER mail group alerting
facility staff on whether there are entries requiring approval. The
message indicates either potential or no potential active duty
admissions/discharges for the past week. If there were potential
admissions/discharges, then the message will state there are active duty
admissions, reflect the number of potential active duty admissions or
discharges needing review, the record count, and the time period of the
report. Staff will review and process those potential active duty cases.

1. .. rubric:: 
      On-going/Completed Application Decommissioning
      :name: on-goingcompleted-application-decommissioning

   1. .. rubric:: Automated Safety Incident Surveillance Tracking System
         (ASISTS)
         :name: automated-safety-incident-surveillance-tracking-system-asists

**Version**: 2.0

**Namespace:** OOPS

**Brief Description:** Automated Safety Incident Surveillance Tracking
System (ASISTS) was designed to manage the data from all employee
accidents, create a Report of Accident (VA Form 2162) from the data, and
produce both the Office of Worker's Compensation Programs Form CA-1
(Instructions for Completing Employee's Notice of Traumatic Injury and
Claim for Continuation of Pay/Compensation) and Form CA-2 (Federal
Employee's Notice of Occupational Disease and Claim for Compensation).

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business

**Business Function Framework Function(s):** Perform Hospital
Administration, Manage Human Resources

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Public Health

**VASI ID:** 1037

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/122741/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=56

**Full Description and Features:** Improving tracking and management of
employee accidents, in general, and exposures to blood borne pathogens
from needle sticks and sharps, in particular, is a high priority of VHA.
Consequently, the package contains fields that are specific to needle
stick, sharps, and bodily fluid exposures. The data collected from
ASISTS is electronically transferred to a national database and used to
identify system-wide problems and opportunities for focused education
and to conduct research. The electronic submission of workers’
compensation claims to the Department of Labor is improving submission
rates and reducing duplicate data collection and data entry.

Note: This product has been identified for decommissioning and will not
appear in future versions of the Monograph.

-  Electronic signature is used extensively throughout this program. All
   three forms (VA Form 2162, CA-1, and CA-2) require appropriate
   signatures including that of the employee for the CA-1 and CA-2,
   which is used when electronically transferring the date to the
   Department of Labor

-  Bulletins alert employee health and infection control of any
   exposures to blood borne pathogens. The employee's supervisor, the
   safety officer, Human Resources Management, and union representatives
   are notified of every incident. Electronic signatures trigger
   bulletins from the employee to the supervisor and union
   representatives and from the supervisor to the safety officer,
   alerting the recipient of action that should be taken

-  Every medical center employee has access to a menu structured
   specifically to the level of his/her involvement in the process:
   employee health, supervisor, safety officer, union representative,
   workers’ compensation personnel, and employee

-  The graphical user interface (GUI) for ASISTS facilitates the input
   and processing of accident reports and claims and improves the
   reporting functionality, including a revised OSHA and Needle stick
   log and graphical representation of the incident reports

-  Future versions will include a comprehensive employee health module
   for tracking and following numerous health issues

   1. .. rubric:: 
         Beneficiary Travel
         :name: beneficiary-travel

**Version**: 1.0

**Namespace:** DGBT

**Brief Description:** The Beneficiary Travel module provides the
ability to perform the functions involved in issuing beneficiary travel
pay. Travel reimbursement is provided to specified categories of
eligible veterans. It is also provided to non-employee attendants who
are eligible for such reimbursement. These attendants will be issued
travel pay under the veteran's name.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Manage Business

**Business Function Framework Function(s):** Facilitate Patient Travel
to Points of Care, Provide Financial Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Chief Business Office

**VASI ID:** 1781

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123318/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=123

**Full Description and Features:** The Beneficiary Travel options
provide the ability to perform the functions involved in issuing
beneficiary travel pay. Travel reimbursement is provided to specified
categories of eligible veterans. Issuance of travel pay to the veterans
in some of these categories is subject to a deductible per visit and per
month. The deduction requirement may be waived for any veteran who meets
specific criteria subject to the approval of the local medical center
director or designee. Some of the categories have income limitations. An
income certification form is completed and signed yearly by the veteran.
Cash reimbursement is paid on VAF 70-3542d, Voucher for Cash
Reimbursement of Beneficiary Travel Expenses. Non-employee attendants
who are eligible for travel reimbursement will be issued travel pay
under the veteran's name in the computer. Payment for travel by special
mode (ambulance, hired car, handicapped van, etc.) may be authorized
under certain conditions. The amount payable is computed from factors
such as account type, parameter set up of deductible amount per visit
and per month, one-way or round-trip mileage, and applied costs. The
amount payable for claims with an account type of Compensation and
Pension (C&P) will also be computed by the system.

The Beneficiary Travel Dashboard (BT Dashboard) web application was
released in 2012 as an accessory to the existing VistA Beneficiary
Travel application. Travel clerks use BT Dashboard concurrently with the
VistA BT claims functionality, usually on side-by-side screens, to
calculate mileage with Bing™ Maps.

Note: This product has been identified for decommissioning and will not
appear in future versions of the Monograph.

-  Automatically computes the amount payable for claims with an account
   type of Compensation and Pension

-  Allows each site to define and edit site-specific beneficiary travel
   parameters

-  Produces a variety of statistical reports for a specified date range

-  Provides the ability to reprint the standard pre-formatted
   beneficiary travel form for cash reimbursement

   1. .. rubric:: 
         Care Management
         :name: care-management

**Version**: 1.0

**Namespace:** ORRC

**Brief Description:** Care Management is the first application to offer
a convenient way for health care providers to view on a single screen,
pertinent information about multiple patients.

**Business Function Framework Line(s) of Business:** Provide Healthcare
Administration, Deliver Healthcare

**Business Function Framework Function(s):** Perform Hospital
Administration, Provide Medical Services, Manage Health Records

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Primary Care

**VASI ID:** 1784

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123320/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=138

**Full Description and Features:** With Care Management, users can see
at a glance multiple patients for whom they have items that require
attention. The current distribution of Care Management offers the
following four perspectives (which are similar to applications):

Clinician Dashboard: Provides an easy-to-read table of patients for whom
clinicians have unacknowledged results or event notifications (such as
hospital admissions, discharges, or unscheduled clinic visits), unsigned
documents, or uncompleted tasks.

**Nurse Dashboard:** Provides an easy-to-read table of patients for whom
nurses have unacknowledged results, unviewed events, uncompleted tasks
or text orders, unverified orders, or recent vitals.

**Query Tool:** Enables authorized users to create reports based on the
most current patient data available. The Query Tool offers five
pre-defined reports and enables users to create their own customized
reports.

**Sign List:** Enables users to sign multiple items for multiple
patients. For example, using the Sign List, a clinician can sign a
discharge summary for John Smith and notes for Jane Smith
simultaneously. This distribution of Care Management also includes the
Task Editor, which enables users to create patient-related tasks.

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

Care Management comprises an extensive set of features designed to
simplify and improve patient care.

These features include (but are not limited to) the following:

-  Colored-coded icons that indicate the priority status of dashboard
   items

-  A default patient list that is based on users’ Computerized Patient
   Record System (CPRS) default patient list

-  A dynamically generated, user-based patient list

-  Custom patient lists

-  Checkboxes for acknowledging and verifying individual or multiple
   dashboard items

-  The ability to set date ranges for dashboard items

-  The ability to link tasks to other tasks or to events

-  The ability to prioritize, edit, and delete tasks

-  Text boxes that expand to provide detailed information about
   dashboard items

A variety of predefined reports, including the following:

-  Abnormal Results

-  Consult Status

-  Incomplete Orders

-  Recent Activity

-  Scheduled/Due Activity

Custom reports with a wide selection of criteria, including (but not
limited to) the following:

-  Screen by Inpatient, Outpatient, or Pharmacy Visits

-  Screen by Primary Outpatient Provider

-  Orders/Results

-  Consults/Procedures

-  The ability to print and export reports

Care Management is tightly integrated with CPRS. As a result, from
within CareManagement, users can:

-  Go directly to a patient’s chart in CPRS

-  Clear selected result notifications in CPRS, including notifications
   in the following categories: Events, Results, Actions

Care Management’s intuitive Graphical User Interface (GUI) includes an
extensive selection of clickable items from which users can:

-  Select a default perspective

-  Select dashboard preferences

-  View demographic information for individual patients

-  View details about specific action items

   1. .. rubric:: 
         Enterprise Health Management Platform
         :name: enterprise-health-management-platform

**Version**: 2

**Namespace:** HMP

**Brief Description:** eHMP was a read-only version which has been
slated to replace VistAWeb. The system will provide enhanced
presentations of clinical data that will range from trend views that
provide a quick snapshot of easily understandable data, to detailed
views that provide the user with a full range of options for examining
longitudinal patient medical records. the EHMP project was shut down in
early 2018.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 2052

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/150347/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=219

**Full Description and Features:** The Enterprise Health Management
Platform (eHMP) project is a multi-year (starting year 2016) effort to
evolve a modern, service-oriented platform which provides a web-based
user interface (UI), clinical data services (CDS), and assembles patient
clinical data from federated Veterans Health Information Systems and
Technology Architecture (VistA) repositories, Department of Defense
(DoD), and private partner data sources, reflective of each location
providing care to the patient. This federated data is aggregated into an
enterprise patient record. eHMP service components will span all
application layers, including presentation, business and core services,
and data access.

Release 1.2 introduces critical viewer edition enhancements to provide
new capabilities to the Department of Veterans Affairs (VA) beyond what
is available today via Computerized Patient Record System (CPRS), Joint
Legacy Viewer (JLV), and VistAWeb. The system will provide enhanced
presentations of clinical data that will range from trend views that
provide a quick snapshot of easily understandable data, to detailed
views that provide the user with a full range of options for examining
longitudinal patient medical records. Users will be able to configure
these views into a limitless number of custom workspaces in order to
support a variety of clinical workflows. There will also be multiple
pre-configured workspaces available to the user, which are filtered for
specific conditions. The workspaces will provide the appropriate
clinical information for a selected condition (e.g., COPD, Diabetes).
Further enhancements will include improved text search and online
application help screens.

**Note:** This product has been decommissioned and will not appear in
future versions of the Monograph.

Incident Reporting
------------------

**Version**: 2.0

**Namespace:** QAN

**Brief Description:** The Incident Reporting module supports VHA policy
by compiling data on patient incidents. It organizes the data into
defined categories for reporting and tracking at medical facility level
and for transmission to the National Quality Assurance Database for
Headquarters review and tracking.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Perform Hospital
Administration, Utilize Information Technology Services

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Office of Quality, Safety and Value

**VASI ID:** 1963

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123381/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=43

**Full Description and Features:** Incident Reporting allows for the
entry of all required incident information plus descriptive data and
actions taken on all reportable and/or locally defined incidents.

-  Prints out a Pseudo 10-2633 Incident Worksheet

Provides an ad hoc reporting mechanism that uses VA FileMan modifiers
for sorting or printing the following data fields:

-  Patient Type of Death

-  Patient ID Level of Review

-  Date of Admission

-  Date of Incident

-  Patient Type Incident Case Status

-  Ward/Clinic Severity Level

-  Treating Specialty Fall Assessment Score

-  Service Person Reporting the Incident

-  Responsible Service Patient Diagnosis

-  Medication Errors Medical Center Action

-  Case Number Incident Description

-  Incident Pertinent Information

-  Incident Location National Case Status

**Note:** This product has been identified for decommissioning (with
patch QAN\*2\*34) and will not appear in future versions of the
Monograph.

Integrated Funds Distribution, Control Point Activity, Accounting and Procurement (IFCAP)
-----------------------------------------------------------------------------------------

**Version**: 5.1

**Namespace:** PRC

**Brief Description:** Integrated Funds Distribution, Control Point
Activity, Accounting and Procurement (IFCAP) module automates a spectrum
of VA financial activities. VA employees use IFCAP to manage budgets,
order goods and services, maintain records of available funds, determine
the status of a request, compare vendors and items to determine the best
purchase, record the receipt of items into the warehouse, and pay
vendors.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Manage Fixed Assets,
Conduct Supply Chain Operations, Provide Financial Management

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA Procurement and Logistics Office

**VASI ID:** 1807

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123213/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=42

**Full Description and Features:** IFCAP automates the written
regulations and policy for VA funds and procurement, which define the
actions taken on requests for goods and services as formal transactions,
orders, and payments.

-  Allows users in different services to view the same document
   on-screen

-  Automates funds distribution, request for goods and services,
   purchase order, funds obligation, and the receipt process

-  Standardizes funds management. Automatically generates yearly budget
   elements for IFCAP control points

-  Maintains year-to-date balance for control points. Integrates
   service-level requisitions and facility administrative activities,
   and updates service-level records

-  Shares vendor and item master data to eliminate duplicate input and
   promote user accuracy

-  Affixes processing status to each request at each step in the
   ordering cycle

-  Enhances security with the use of a unique electronic signature code
   for each user required to authorize an action

-  Sets an encoded value based on key fields from each record signed

-  Transmits financial and inventory data to VA central accounting and
   inventory systems.

-  Updates IFCAP records automatically with central accounting system
   data

-  • Provides various reports that give the current status of any
   request, a service fund balance, and data required for budget
   analysis, and a listing of requests sorted according to control point
   specifications

-  Enables electronic transmission of purchase orders to vendors through
   Electronic Data Interchange (EDI) and updates purchase order status
   automatically

-  Enables authorized users to purchase goods using Electronic Data
   Interchange (EDI) process for total electronic processing between
   vendor and buyer

-  Supports the ordering of goods under contract from specific vendors
   via delivery orders

-  Supports the payment for goods/services via the government purchase
   card and the subsequent on-line reconciliation

-  Transmits Federal Procurement Data System (FPDS) data to the Austin
   Information Technology Center (AITC) to support enterprise level
   tracking of procurement history

-  Supports monthly management analysis activities by transmitting
   inventory and purchase order activity data to the Clinical Logistics
   Report Server at AITC

-  Supports, via a graphical tool, the reviewing of purchase order
   activity and other logistical data within IFCAP; and the export of
   that data to MS Excel spreadsheets for further analysis

-  Supports both the identification of items by their National Item File
   number (NIF #) and the standardized naming of Items through an
   interface between IFCAP and the National Item File

-  Transmits inventory and purchase order activity data to the Clinical
   Logistics Report Server (CLRS) on a monthly basis for management
   analysis

-  Provides numerous Inventory management features including desired
   stock levels, automatically generated (autogen) replenishment orders,
   identification via bar code technology, and numerous reporting
   mechanisms

-  Supports the identification and tracking of on-demand items at the
   primary and the secondary level

-  Enforces the separation of duties. Controls are implemented with
   respect to Requestors, Approving Official and Obligators

-  Provides bi-directional communication between IFCAP and the
   commercial Electronic Contracting Management System (eCMS) location
   at the (AITC) in Austin, TX

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

Library
-------

**Version**: 2.5

**Namespace:** LBR

**Brief Description:** Patch LBR\*2.5\*15 retired the Library (LBR)
version 2.5 package. All national components associated with the Library
package were removed as of compliance date, May 3, 2018.

The Library module is designed to automate the entire serials management
process in VA Library Services.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio:** Business Informatics

**Business Owner:** OIA Patient Care Services

**VASI ID:** 1815

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123287/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=47

**Full Description and Features:** Patch LBR\*2.5\*15 retired the
Library (LBR) version 2.5 package. All national components associated
with the Library package were removed as of compliance date, May 3,
2018.

The Serials Control module has three components. The Serials Management
component creates the local library’s serials database, along with
retrospective holdings and purchasing information and copy information,
such as location and category. The module is designed so that access to
this component may be restricted, if desired, to the serials expert on
the library staff, usually a medical librarian or the Chief. Access to
the Serials Control component where daily actions are managed (e.g.,
check-ins, routing, and generation of reports) may be given to other
Library Service staff members. A minor component of the module, Library
Site Parameters, allows for the initialization of the module. A
centrally produced Title Authority file, a database of over 9,477
serials titles owned by VALNET (VA Library Network) libraries, was
preloaded with standard bibliographic data and provided as a part of
this module.Library makes it possible for local sites to carry only
locally active entries in their local database. When new entries are
needed, they can be downloaded automatically from the national database
into a site’s local database.

-  Creates a local serials database

-  Provides acquisition and retention information

-  Provides purchasing and vendor information

-  Provides holdings information and shelving location information

-  Categorizes by type and subject

-  Provides check-in with next issue prediction

-  Generates routing slips

-  Tracks materials returned from routing

-  Displays check-in history

-  Generates 20 management reports (e.g., listings, monthly check-in
   statistics, monthly routing statistics, tracking of unreturned routed
   issues, missing issue reports for claiming replacements or reports,
   etc.)

**Note:** This product has been decommissioned and will not appear in
future versions of the Monograph.

Medical Domain Web Services (MDWS)
----------------------------------

**Version**: 1.0

**Namespace:** MWSV

**Brief Description:** Medical Domain Web Services (MDWS) (pronounced
"meadows") is a suite of Service Oriented Architecture (SOA) middle-tier
web services that exposes medical domain functionality.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Utilize Information
Technology Services

**VHA Portfolio:** Common Services

**Business Owner:** OIA HI HI2

**VASI ID:** 2000

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123367/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=192

**Full Description and Features:** Medical Domain Web Services (MDWS)
(pronounced "meadows") is a suite of Service Oriented Architecture (SOA)
middle-tier web services that exposes medical domain functionality,
Medical Domain Objects (MDO). MDWS is equipped with the capacity to
virtualize any legacy Veterans Health Information Systems and Technology
Architecture (VistA) Remote Procedure Call (RPC) as a web service. A web
service is an Application Programming Interface (API), which uses Simple
Object Access Protocol (SOAP), the standardized protocol to communicate
with subscribed client applications.

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

Patient Advocate Tracking System (PATS)
---------------------------------------

**Version**: 1.0.2

**Namespace:** QACV (QAC for patch designation)

**Brief Description:** The Patient Advocate Tracking System (PATS) is a
web-based application with a centralized database and notification
function (email) for tracking patient-related issues and is designed to
work on various operating systems.

**Business Function Framework Line(s) of Business:** Provide Access to
Health Care, Provide Health Care

Administration, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Communications and
Outreach, Manage Customer Relations, Utilize Information Technology
Services

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Patient Advocacy

**VASI ID:** 1492

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123064/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=172

**Full Description and Features:** PATS is a centralized, JEE
light-client application, used by Patient Advocates via a browser, at
each VA healthcare facility, to manage, record and resolve veteran
(patient) compliments and complaints, regarding the veteran’s care and
interactions at the facility serving them, so that issues are addressed
in a convenient and timely manner.

In 2007, PATS, as part of the VistA application reengineering effort,
replaced the legacy VistA Patient Representative application which had
been used at VA Medical Centers (VAMC) in prior years by Patient
Representatives for this purpose. Use of PATS was originally mandated as
the VA's System of Record for patient (veteran) concerns, through the
National Veterans Service & Advocacy Program and VHA Support Service
Center, in VHA Directive 1003, and was, in 2011, brought under business
ownership of the Office of Patient Advocacy Veterans Experience Program,
within the Deputy Under Secretary for Health for Ops and Mgt (DUSHOM),
with continuation of its recognition as System-of-Record.

Patient Advocates use a cooperative effort with the patient, health care
providers, and other employees at the healthcare facility, to facilitate
expression and resolution of the patient’s concerns. These patient
encounters, created, recorded and managed by Patient Advocates in PATS
as Reports of Contact (ROCs), may originate from a variety of sources
including the patient, family members, congressional members and
Veterans service organizations on behalf of the Veterans receiving care
at VA facilities, by direct contact with Patient Advocates or via the
Inquiry Routing and Information System (IRIS), after inquirers contact
the IRIS Agents.

Besides its function of assisting in resolving patient-centered
concerns, PATS also provides reports capabilities for assessment of
complaint trends based on its data, providing trending feedback to the
healthcare facility healthcare providers, customer care, and quality
control managers, for recognition of and improvement of quality of care,
and for adherence to best practices.

The patient-centered activity, Patient Advocate interactions,
recordation of these ROCs in the PATS database, and trending for quality
management, are all in alignment with the System-of-Record recognition
of PATS in the Federal Register, visible directly at:
https://www.gpo.gov/fdsys/pkg/FR-2009-06-03/pdf/E9-12954.pdf, or by
publications search from that page:
`http://www.gpo.gov/fdsys <http://www.gpo.gov/fdsys%20>`__ ’patient
advocate tracking system’.

DUSHOM’s Office of Patient Advocacy Veterans Experience Program
Leadership, use metrics and trending information from PATS Reports of
Contact data, in their mission of oversight, national guidance,
technical support, and education efforts for Patient Advocate staff
within the broader context of the enhancement of the Veteran experience
and patient centered care.

PATS is accessed, via https secure socket connections, through a
browser, by Patient Advocates, to document, track, and report
patient-related issues. Interoperating technologies include this Java
Enterprise Edition (J2EE) application, running within the Weblogic
application suite, which is running on servers at the hosting facility,
with backup/disaster recovery servers located at another standby hosting
facility. This Java application interoperates, via jdbc, with the Oracle
database running on the database server, for dynamic transaction-based
database updates. PATS also interoperates with each of the 100+ VistA
legacy systems (VAMCs) for user authentication and authorization and
employee/patient lookup, via connections known as VistALink Services,
which use VistALink transport layer protocol for networked
communication. For reporting and trending purposes, new transactions are
migrated nightly, to the PATS-Reports database on the PATS-Reports
server. This feature of PATS is directly available to Patient Advocates,
during normal login sessions in the PATS user interface. In development
are new PIV-managed processes with Two-Factor Authentication-single
signon functionality, such that the role-use of PATS features is managed
by the Role Based Access Control authorization process:

-  The user opens PATS login page in their browser (also known as
   Application landing).

-  They select that station into-which they intend to start a PATS
   session.

-  The PATS application, running in WebLogic at the host in Hines,
   receives their click.

-  PATS retrieves the Security Assertion Markup Language (SAML) xml
   token for this user, from the identity provider (IDP) identity
   repository. This token is validated at the target VistA environment,
   allowing the user roles to be retrieved by subsequent calls to the
   corresponding VistA RPCs.

-  The PATS application validates this SAML token, authorizing the user
   for access to PATS.

-  The user's PATS session object is constructed, enabling use of the
   role-based PATS features.

-  The user interface is presented to the user.

Reports are available within PATS, showing detailed transaction data of
the ROCs for detail reports, and counting reports used for trending.
Patient Advocates generate site-specific reports, revealing ROC counts,
types and occurrences of issue codes (some issue codes are identified
and distinguishable also as ‘customer service standards’) assigned in
ROCs, and other patterns, for a fiscal year or date range, for review by
Facility Administrators, Quality managers and Service managers. Veterans
Integrated Service Network (VISN) Patient Advocate Coordinators generate
similar VISN-scoped reports for review by VISN Directors. Central Office
and National Program Office PATS managers generate national-scope
reports, revealing usage patterns, to help the PATS National Director
oversee the mission and usefulness of the PATS application, and to
discover national VA-wide patterns of activity to aid in the mission of
the VHA Office of Patient Advocacy to enhance the Veteran's experience.
These reports provide feedback to aid in pattern assessment for quality
management to facilitate best practice and care for the Veterans. Some
transaction data is also transmitted weekly to the VHA Support Service
Center (VSSC) which provides additional report views.

PATS is supported by the VA's multi-tiered support network, including
the national Health Product Support PATS team, and regional, VISN and
local IT support teams. When the Health Product Support PATS team
requires Developer or infrastructure consultation, they consult with
Developers from the Tier 3 Sustainment Administrative team, and other
infrastructure and common-services teams such as Database Administrators
from the Administrative Data Repository in Austin, DBAs from the VA IT
Engineering Enterprise Health Solutions at Hines, and Server
Administrators at the Capital Regional Data Center in Martinsburg WV.

PATS enables users to perform the following tasks:

-  Add a Report of Contact (ROC) which details a Veteran’s issue
   (compliment or complaint)

-  Edit, close, reopen, and delete an ROC

-  Send Informational Notifications to communicate an issue to an
   employee involved in a Report of Contact and/or the employee’s
   supervisor

-  Send Action Request Notifications, which require a response from the
   individual regarding action to be taken or next steps

-  Generate site-specific and National reports

-  Create ad hoc reports

-  Display reports online and save them in a variety of formats (Word,
   Excel, PDF files)

Enhanced in April 2013 to introduce the Inquiry Routing and Information
System (IRIS) functionality. A new feature allows the IRIS Agent to
transmit an IRIS inquiry to PATS, as a new ROC. PATS automatically rolls
up data to the VISN Support Service Center to provide additional
National reports. The PATS application is deployed at the Capital Region
Readiness Center in Martinsburg WV, and is managed by the Health Systems
Implementation, Training, and Enterprise Support team.

**Note:** This product has been identified for replacement and
subsequent decommissioning and will not appear in future versions of the
Monograph.

Personnel and Accounting Integrated Data (PAID)
-----------------------------------------------

**Version**: 4.0

**Namespace:** PRS

**Brief Description:** PAID is comprised of the Enhanced Time and
Attendance system and the Education Tracking system.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Manage Human Resources

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Financial Management

**VASI ID:** 1830

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123300/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=51

**Full Description and Features:** Education Tracking documents employee
and student participation at mandatory and ward in-services, continuing
education programs, and all other employee training. Training
information is protected with varying levels of access.

-  Creates a class database with pertinent class information including
   class name, presenter, location, contact hours, accrediting
   organizations, etc.

-  Contains a class registration component that limits class registrants
   by number or service

-  Credits class participation to individual attendee records

-  Provides site-configurable mandatory training groups, accrediting
   organizations, presentation media, and class purpose

-  Contains a variety of reports including registration roster and
   employee training reports

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

Personnel and Accounting Integrated Data (PAID): Enhanced Time and Attendance (ETA)
-----------------------------------------------------------------------------------

**Version**: 4.0

**Namespace:** PRS

**Brief Description:** PAID is comprised of the Enhanced Time and
Attendance system and the Education Tracking system.

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Manage Human Resources

**VHA Portfolio:** Business Informatics

**Business Owner:** Office of Financial Management, Payroll and HR
Systems Service

**VASI ID:** 1887

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123509/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=51

**Full Description and Features:** The Enhanced Time and Attendance
System (ETA) automates time and attendance for employees, timekeepers,
payroll, and supervisors. It provides employees the ability to request
leave and display both the status of pending requests and leave balances
and allows payroll to manage time and leave (T&L) units and tours of
duty. It provides timekeeping, supervisory certification, and overtime
management.

-  Timekeepers can enter and edit employee data and view time card
   status

-  Payroll can view processing status of T&Ls, locate
   uncertified/incomplete timecards

-  Payroll can manage T&L units by multiple elements including
   supervisors, timekeepers and employees

-  Payroll supervisor transmits all payroll data to Central PAID in
   Austin and monitors transmission status

-  PAID builds and updates employee records with Central PAID

-  Employees may submit electronic leave requests, and also view request
   status, leave balances, and service records

-  Supervisors can approve electronic requests and timecards and view
   employee leave reports.

**Note:** This product has been identified for replacement (by the
Veterans Affairs Time and Attendance System (VATAS) scheduled for
completion by July 2018) and subsequent decommissioning and will not
appear in future versions of the Monograph.

Primary Care Management Module
------------------------------

**Version**: 1.0

**Namespace:** PCMM

**Brief Description:** Legacy Primary Care Management Module (PCMM GUI)
is no longer in use and has been replaced by Patient Centered Management
Module (PCMM Web).PCMM allows users to create, manage, and define teams
and assign staff to these teams. This funtion helps in maintaining
accurate listings for primary care teams and panels.

**Business Function Framework Line(s) of Business:** Provide Health Care
Administration

**Business Function Framework Function(s):** Perform Hospital
Administration

**VHA Portfolio: **

**Business Owner:** VHA

**VASI ID:** 1530

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123113/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=95

**Full Description and Features:** In the outpatient setting, patients
are assigned a primary care team and provider who are responsible for
delivering essential health care, coordinating all health care services,
and serving as the point of access for specialty care. Associate Primary
Care Providers (APs) provide primary care to patients under the
supervision of the Primary Care Provider (PCP). PCMM supports both
primary and non-primary care teams such as OIF/OEF and Mental Health
Treatment teams. The software allows users to create, manage, and define
teams; create, manage and assign positions to the teams; assign staff to
the positions; and assign patients to positions.

In PCMM, primary care providers have an assigned "number of patients
allowed" which is compared with the "number of patients actual" to
determine if more patients may be assigned to the provider. PCMM
functionality assists in maintaining accurate, active patient listings
for primary care teams and panels. By unassigning patients who have not
seen their primary care providers in a specified amount of time, new
patients may be assigned. Unassigned patients may be readily reassigned
to their previous primary care team and provider if they return for
care. When the maximum number of patients is reached, sites may override
the maximum number allowed or add the patient to the Electronic Wait
List. PCMM Wait List reports assist in the management of patients
awaiting a primary care team or provider assignment.

PCMM allows entry of the providers FTEE to track the amount of time the
APs and PCPs spend providing direct primary care and measures the
capacity of each institution (and VHA as a whole) to provide outpatient
primary care. PCMM also screens staff assignments to PCP and AP
positions to assure the data on providers is correct.

The primary care patient, provider, and team information captured in
PCMM is sent to the Austin Information Technology Center (AITC) and the
National Patient Care Database. Some PCMM information is available on
the VHA Support Service Center (VSSC) website. Additionally, the Office
of Performance and Quality Measures utilizes PCMM data for national
reporting and performance measures.

-  Uses a graphical user interface (GUI) for creating teams and provider
   positions as well as assigning staff to the provider positions

-  Ability to assign/unassign patients to primary care and non-primary
   care teams and providers both in GUI and VistA roll-and-scroll

-  Automates patient unassignment from primary care teams and providers
   if the patient has not seen their primary care provider for a
   specified time or when a patient’s date of death is entered

-  Screens assignments to PCP and AP positions based on provider type
   and person class.

-  Produces patient-oriented, practitioner-oriented, and team-oriented
   reports

-  Transmits data for primary care teams, providers, and patients to
   Austin in Health Level Seven (HL7) message format and provides the
   ability to receive/process transmission errors

-  Ability to control transmission of MailMan messages to team positions

**Note:** This product has been replaced by Patient Centered Management
Module Web (PCMM Web) and will not appear in future versions of the
Monograph.

SlotMaster (Kernel ZSLOT)
-------------------------

**Version**: 8.0

**Namespace:** ZSL

**Brief Description:** SlotMaster is a quick login utility for VMS
systems. SlotMaster saves user time by letting the user connect directly
to an active M partition. This saves users from sitting through VMS
process creation and loading an M partition, allowing them to log in to
VistA directly.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1596

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123227/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=24

**Full Description and Features:** SlotMaster is a quick login utility
for VMS systems. SlotMaster saves user time by letting the user connect
directly to an active M partition. This saves users from sitting through
VMS process creation and loading an M partition, allowing them to log in
to DHCP directly.

SlotMaster also conserves system resources by re-using the same VMS
process for new users, rather than creating a new process for each new
user.

**Note:** Product has been decommissioned and will not appear in future
monographs!

-  Programming Language: MUMPS

-  Deployment Infrastructure: Varies by location

-  Depends on: Kernel

   1. .. rubric:: 
         Social Work
         :name: social-work

**Version**: 3.0

**Namespace:** SOW

**Brief Description:** The Social Work package is designed to facilitate
the Social Work Service functions within a medical facility and is
composed of Case Management, Clinical Assessment, and Community
Resource.

**Business Function Framework Line(s) of Business:** Deliver Health Care

**Business Function Framework Function(s):** Provide Care Management,
Provide Ancillary Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1841

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123411/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=101

**Full Description and Features:** Within the Social Work module, the
Case Management software is used for managing social work cases (e.g.,
opening and closing cases, recording problems and outcomes, storing
referrals) and for generation of reports that are transmitted quarterly
to VA Central Office. The Clinical Assessment software provides a method
of identifying, upon admission, patients most likely to require social
work assistance before or after discharge. The hospital stay may be
minimized with the anticipation of patients’ domestic or social needs
prior to discharge. The Community Resource software allows the social
worker to build a network of local community agencies that can serve the
veteran. The network enables the worker to expediently match the needs
of the client to the existing community resources, thereby increasing
productivity and viable referrals.

-  Automatic screening that uses predetermined and site-specific
   criteria (e.g., Veteran with no permanent address) to determine if a
   patient needs the services of Social Work Service prior to discharge

-  Creates networks of local community agencies (e.g., alcohol
   treatment, housing, health) that can serve Veterans

-  Compiles a list of community resources by user-selected category
   (e.g., name, town, type, zip code)

-  Identifies local residential care homes and maintains detailed
   information on the homes (e.g., rates, vacancies, residents, date
   home assessed by a VA social worker)

-  Allows workers to track patients and homes in the residential care
   home program by home and patient registry printouts

-  Facilitates mailings to residential care home sponsors by printing
   address labels.

-  Tracks caseloads by recording the openings and closings of cases

-  Compiles and produces monthly and quarterly reports and transmits
   data electronically module

-  Provides patient teaching and monitoring necessary for VHA-wide
   system of coordination/care management services

-  Provides for standardized Psychosocial Database/Assessment for
   inclusion in patient health records. Also, provides mechanism for
   entering progress notes

-  Provides for automated quality management monitors and reviews

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

Spinal Cord Injury and Disorders Outcomes (SCIDO)
-------------------------------------------------

**Version**: 3.0

**Namespace:** SPN

**Brief Description:** The Spinal Cord Injury and Disorders Outcomes
(SCIDO) 3.0 application converts the Spinal Cord Dysfunction (SCD)
Registry from a legacy command line system to a client server platform
with a graphical user interface (GUI) and enhanced capabilities.

**Business Function Framework Line(s) of Business:** Manage Public
Health, Deliver Health Care

**Business Function Framework Function(s):** Provide Medical Registry
Service, Provide Care Management

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1605

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123231/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=196

**Full Description and Features:** The Spinal Cord Injury and Disorders
Outcomes (SCIDO) application is a system for compiling spinal cord
injury and disorders information. The SCIDO application accesses several
other Veterans Health Information Systems and Technology Architecture
(VistA) programs that contain information regarding diagnoses,
prescriptions, surgical procedures, laboratory tests, radiological
exams, patient demographics, hospital admissions, and clinical visits.
This access allows clinical staff to take advantage of the data
supported by VistA. Information can be summarized at three levels: local
medical center, SCI region, or national research access.

**Note:** This product has been decommissioned and will not appear in
future versions of the Monograph.

VistAWeb
--------

**Version**: 1.0 (SEE NOTE)

**Namespace:** WEBV

**Brief Description:** VistAWeb is a read-only intranet web application.
It delivers to the client a uniform, well-defined suite of objects from
the medical domain, including objects such as patient, provider,
progress note, lab results, prescriptions, allergies, and imaging.

NOTE: VistAWeb is Version 16.0 and 16.1.5 for the server version in
Austin; in FORUM it is Version 1.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Manage Health Records,
Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA

**VASI ID:** 1853

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123423/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=147

**Full Description and Features:** VistAWeb enables VA clinicians to
view VistA data generated from their own as well as remote Veterans
Affairs Medical Centers (VAMCs) as well as information from the
Department of Defense (DoD). With significant ease of use, flexibility,
and reliability, VistAWeb is a preferred method for remotely accessing
such information, and it is used, in addition, for reviewing remote
patient information found in VistA, the Bidirectional Health Information
Exchange (BHIE) system, the Health Data Repository II (HDR II)
databases, and the eHealth Exchange. This capability with the eHealth
Exchange renders VistAWeb a key component of Virtual Lifetime Electronic
Record (VLER) electronic health information exchange.VistAWeb reflects
the reports behavior of the Computerized Patient Record System (CPRS)
and Remote Data View (RDV), and affords robust and timely retrieval of
remote-site patient data, supplementing CPRS/RDV.

**Note:** This product has been identified for decommissioning and will
not appear in future versions of the Monograph.

1. .. rubric:: 
      DSS Inc. Commercial-off-the-Shelf (COTS) VistA Integrations
      :name: dss-inc.-commercial-off-the-shelf-cots-vista-integrations

   1. .. rubric:: Above PAR (APAR)
         :name: above-par-apar

**Version**:

**Namespace:** DSIY

**Brief Description:** APAT helps facilities to manage their prosthetics
procurement process with an easy-to-use module. APAT is an Electronic
Document Management Software (EDMS) system to electronically store and
manage all documentation throughout the prosthetics department.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1893

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123370/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** APAT helps facilities to manage their
prosthetics procurement process with an easy-to-use module. APAT is an
Electronic Document Management Software (EDMS) system to electronically
store and manage all documentation throughout the prosthetics
department.

Note: This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/above-par/

-  All-electronic bid process and purchase order management

-  Full-color graphical user interface (GUI)

-  Comprehensive workflow tracking

-  Standard and ad-hoc reporting capabilities

-  Secure electronic document management

-  Fully scalable, customizable and flexible

   1. .. rubric:: 
         Advanced Prosthetics Acquisition Tool (APAT)
         :name: advanced-prosthetics-acquisition-tool-apat

**Version**:

**Namespace:** DSIVA

**Brief Description: **

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** APAT helps facilities to manage their
prosthetics procurement process with an easy-to-use module. APAT is an
Electronic Document Management Software (EDMS) system to electronically
store and manage all documentation throughout the prosthetics
department.

Note: This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/advanced-prosthetics-acquisition-tool-apat/

-  All-electronic bid process and purchase order management

-  Graphical user interface (GUI)

-  Comprehensive workflow tracking

-  Standard and ad-hoc reporting capabilities

-  Secure electronic document management

-  Fully scalable, customizable and flexible

   1. .. rubric:: 
         Caribou Community Living Care (CLC) Suite (Caribou)
         :name: caribou-community-living-care-clc-suite-caribou

**Version**:

**Namespace:** DSIB

**Brief Description:** The Caribou CLC Suite to automate resident care
workflow processes for Community Living Centers through integration with
The Veterans Health Information Systems and Technology Architecture
(VistA).

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 2290

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/2505103/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Caribou CLC Suite a COTS
integration with VistA to provide an automated tool that provides a
comprehensive and standardized assessment of each resident’s functional
capabilities. It helps VHA CLC staff identify health problems with
real-time access to resident medical information, develop individualized
care plans, and evaluate the quality of care.

Additionally, the software allows the capture of admission, discharge
and transfer (ADT) movement via the use of tracking forms. Information
will be recorded and updated by clinicians and shared securely with
decision makers in a timely and effective manner. The software will also
provide reporting functionality for local, Veterans Integrated Service
Network (VISN), and national users. The use of this solution helps VHA
remain in compliance with Centers of Medicare and Medicaid Services
(CMS) requirements, provide accurate Resource Utilization Groups (RUG),
assist with the calculations of Veterans Equitable Resource Allocation
(VERA), document Quality Measures (QM) for long-term care surveys, and
improve the ability to assess CLC residents’ quality of life.

This software solution was developed replace the CLC Accu-care tool and
provides the functionality found in the legacy VA RAI/MDS software,
ensure accuracy with respective VA RAI/MDS technical documentation
requirements while maintaining regulatory compliance with current CMS
standards and regulations which can be found at the following URL:
http://www.cms.gov/Medicare/Quality-Initiatives-Patient-Assessment-Instruments/NursingHomeQualityInits/MDS30RAIManual.html

Note: This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/integrated-clinical-products/caribou-community-living-care-suite/

-  Decrease the risk of errors

-  Reduce double entry of data

-  Shorten workflow processes for providers

-  Improve overall delivery of residential care

   1. .. rubric:: 
         Dental Record Manager (DRM) Plus
         :name: dental-record-manager-drm-plus

**Version**: 6.9

**Namespace:** DENT

**Brief Description:** The original Dental Record Manager (DRM)
software, installed in all VA dental clinics by the end of FY 2001,
provided a customized user-friendly Windows interface for entering
clinical encounter information and assisted with the assessment of
ongoing care using current patient data for completed procedures.

**Business Function Framework Line(s) of Business:** Deliver Health
Care, Manage Business Enabling Services

**Business Function Framework Function(s):** Provide Care Management,
Provide Dentistry, Provide Medical Services, Manage Health Records,
Provide Financial Management, Utilize Information Technology Services

**VHA Portfolio:** Health Provider Systems

**Business Owner:** VHA Dental

**VASI ID: **

**VASI ID Link: **

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=66

**Full Description and Features:** DRM Plus brings significant graphical
interface (GUI) entry and display enhancements to the original DRM
version. DRM Plus records diagnostic findings, including head and neck
lesions, restorative and periodontal charting, and sequenced treatment
planning. DRM Plus helps assure quality care, patient safety, and staff
communication in an environment that is fully integrated with the VA
electronic health record.

The DRM Project also replaces the Dental Activity System (DAS) national
and local reporting structure with the new Dental Encounter System
(DES).

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/integrated-clinical-products/dental-record-manager-plus/

-  **Chart/Treatment:** This tab replaces the DRM Encounter Note tab and
   features the Treatment & Exam and the Periodontal Chart views.
   Features include head and neck findings, advanced graphics, and
   sequencing.

-  **Treatment & Exam:** This screen is used to record and display oral
   and maxillofacial diagnostic examination findings, including
   restorative findings. Certain diagnoses, such as implants, impacted
   teeth, retained roots and teeth flagged for observation, appear
   graphically on all screens.

-  **Periodontal Chart:** This screen records and measures various types
   of periodontal conditions. Periodontal charting icons are
   condition-specific, allowing a graphic charting display as well as
   the identification of critical elements in periodontal report tables.
   -Critical elements charted include pocket depth, bleeding, delayed
   bleeding, FGM, MGJ, suppuration, mobility, and furcation involvement.
   Treatment Plan: This screen allows the provider to enter and sequence
   a plan of care. Color is used to differentiate the status of various
   conditions. Some items appear graphically on all screens.

-  **Completed Care:** This screen is used to enter procedures completed
   during the current visit. Certain completed care procedures, entered
   from the Completed Care Screen, appear graphically on all screens.

**Clinical Benefits**

-  Improves communication among treating dental providers for patient
   oral and maxillofacial findings and for plan of care, including
   sequencing.

-  Easily captures oral and maxillofacial diagnostic findings in a
   graphical and transaction-oriented format.

-  Offers the provider the flexibility to enter only completed
   procedures or to enter the full range of findings, planned care, and
   completed procedures for each patient.

-  Provides tracking of head and neck lesions entered by multiple dental
   providers.

-  Captures periodontal findings in a graphical charting display that
   includes reports.

-  Provides a dynamic interface for multiple dental providers to
   sequence the patient plan of care.

-  Offers a visual display of most transactions, including implants and
   prostheses.

-  Offers additional administrative and management tools for tracking
   workload and individual patient treatment plans.

-  Provides for integration of medical CPT codes into the software.

-  Interfaces with the new Dental Encounter System (DES) local and
   national database.

-  Provides a dental history file that includes all completed procedures
   for each patient. Integrates dental information within the VA
   electronic health record environment with a user-friendlygraphical
   user interface (GUI)

   1. .. rubric:: 
         DocManager
         :name: docmanager

**Version**:

**Namespace:** DSIV

**Brief Description:** DocManager is a COTS integration with VistA to
provide enterprise-wide software solution that automates the document
management process – from scanning, indexing, storing and sending
mission-critical information to generating reports needed to perform
system audits and workload analytics. The solution enables facilities
burdened with paperwork bottlenecks to enter more documents in less time
using fewer staff.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID: **

**VASI ID Link: **

**VDL Link: **

**Full Description and Features:** DocManager is a COTS integration with
VistA to provide enterprise-wide software solution that automates the
document management process – from scanning, indexing, storing and
sending mission-critical information to generating reports needed to
perform system audits and workload analytics. The solution enables
facilities burdened with paperwork bottlenecks to enter more documents
in less time using fewer staff.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/document-manager/

-  Scan, index, view and notate clinical, administrative and financial
   documents

-  Manage multiple workflows within a single, secure environment

-  Index images to the Computerized Patient Record System (CPRS)/Text
   Integration Utility (TIU) quickly and accurately

-  Complete consults and send CPRS notifications to providers

-  Generate workload and audit reports

-  Integrated with VistA and Computerized Patient Record System (CPRS)

   1. .. rubric:: 
         Encoder Product Suite (EPS)
         :name: encoder-product-suite-eps

**Version**:

**Namespace:** DSIP

**Brief Description:** EPS is a COTS integration with VistA to provide
an end-to-end revenue cycle management solution that helps streamline
inpatient reporting, auditing compliance and coding compliance
workflows.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 2087

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/835859/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Encoder Product Suite (ENCODER)
includes Microsoft (MS) Windows graphical user interface (GUI) modules
that include coding, compliance, billing, and auditing functionality.
This technology includes coding modules that aligns hospital and
physician coding, reimbursement, and compliance tools to ensure data and
coding consistency between physician and facility encounters. This
technology provides the following functionality:

-  Auditing and monitoring capabilities with VA-specific Veterans
   Equitable Resource Allocation (VERA) tools

-  Coding knowledge with real-time error indicators

-  Identifies high-risk coding practices

-  Reduces claim denial with Centers for Medicare and Medicaid Services
   (CMS) 1500 and Uniform Billing (UB)-04 claim scrubbing

-  Screening capability for claims and encounters

-  Reporting capabilities with an ad hoc report builder.

EPS includes four modules:

-  VIP Director: A flexible inpatient reporting management tool

-  VIP Workplace: A single platform that captures inpatient coding
   activity and performs real-time coding compliance checks for all
   inpatient encounters

-  Audit Compliance: A robust auditing tool with functionality for
   generating coding, billing, accounts receivable, compliance and VERA
   reports

-  Coding Compliance: A suite of coding tools, including nCoder, E&M
   Calculator and Billing and more, contained within a single interface
   for making edits in real time

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/encoder-product-suite-eps/

-  Streamlines billing, coding and auditing workflows

-  Provides a single point of access to all coding resources

-  Reduces coding errors and potential revenue losses

-  Enables coders to self-review work in real time

   1. .. rubric:: 
         Fee Basis Claims System (FBCS)
         :name: fee-basis-claims-system-fbcs

**Version**: 4.0

**Namespace:** DSIF

**Brief Description:** The Fee Basis Claims System (FBCS) is a claims
management system. FBCS is designed to be used in the Fee Basis
Departments of the Veteran Affairs Medical Centers (VAMCs).

**Business Function Framework Line(s) of Business:** Manage Business
Enabling Services

**Business Function Framework Function(s):** Provide Financial
Management

**VHA Portfolio:** VHA Chief Business Office (CBO) - Purchased Care

**Business Owner:** Document Storage Systems (DSS)

**VASI ID:** 2085

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/835602/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** The Fee Basis Claims System (FBCS) is
a claims management system. FBCS is designed to be used in the Fee Basis
Departments of the Veteran Affairs Medical Centers (VAMCs). The VA Fee
Basis medical program provides payment authorization for eligible
Veterans to obtain routine medical treatment services through non-VA
health care providers. FBCS is an auditing system which provides
instructional prompts designed to interface with the VistA package to
track report and analyze fee claim data. FBCS is comprised of several
modules: The Authorization module, Administrative modules and Claims
Management Modules. Together these modules ensure collection of data for
tracking purposes, increase quality assurance, and promote consistency
and efficiency to maintain standards.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/fee-basis-claims-systems/

-  Updates the functionality at time of scanning to identify individual
   CMS-1500 (HFCA) claim forms that need to be consolidated to create
   one Claim ID record

-  Allows all lines between forms to be reviewed, edited, priced and
   processed together

-  Creates rejection of payment line items by Central Fee will be
   transmitted to VistA Fee Basis via new transactions that update VistA
   automatically

-  Creates new transaction will replace all use of 994 sheets in IFCAP

-  Automates the methods of sending, receiving, tracking, and managing
   claims scored by the VAs Program Integrity Tool (PIT) to communicate
   with Austin Information Technology Center (AITC) with a GUI, SQL, and
   workstation update

-  Creates new interfaces between FBCS and VistA Imaging, allowing
   improved capture of non-VA claims processing information via the
   scanning and indexing of Fee medical records

-  Identifies potential payments not in compliance with VHA policies and
   procedures by alerting claims processing clerks of potential payments
   to be made on behalf of ineligible beneficiaries and of claims
   requiring a secondary review or action before a payments may be made

-  Creates an added automatic encryption of all passwords and
   access/verify codes by allowing the user to hold the Ctrl key and
   clicking the OK button on the main screen

-  Updates the service to ensure when the PIT scoring functionality is
   off the service may continue to run to pick up or deliver pre-patch
   feed files and claims to score feed files for new entries will
   display 0 claims

-  Creates an added SQL password decryption

-  Updates functionality to accommodate the revised 02/12 version of the
   NUCC CMS 1500 form for current ICD-9 and future ICD-10 code based
   data

-  Creates new code to set the SQL transaction isolation level to
   Snapshot Isolation for reporting

-  Redesigns the FBCS Home Screen to display new Consult information for
   authorizations

-  Removes the need to utilize CPRS to view or print consuls for Fee
   authorizations

-  New components hosted in a web application. Contains web-GUI,
   middle-tier (API), and SQL updates

-  Updates to the current FBCS system to accept and transmit necessary
   EDI claim information between HAC, FBCS and VistA Fee to support
   compliance with current EDI mandates, provide increased data tracking
   and reporting to support care in the community/CHOICE efforts and
   legislation and increase data integrity, add additional business
   rules to reduce improper payments and improve automated processes

-  FBCS DSIF\*4.0\*0 introduces a web-based version of FBCS as a
   centralized data and operations claims processing system, focusing on
   front-end claims activities and establishing integration points with
   HAC, Alpha II and existing instances. This release contains new
   components hosted in a web application. Contains web-GUI, middle-tier
   (API), and SQL updates. These updates will be installed by a
   centralized host provider and not at individual sites

   1. .. rubric:: 
         Insurance Capture Buffer
         :name: insurance-capture-buffer

**Version**: 2.2

**Namespace:** DSIV

**Brief Description:** The Insurance Capture Buffer (ICB) module is an
insurance card scanning and VistA Buffer File update management system
designed to enhance the insurance data collection and verification
processes for Veterans Affairs Medical Centers.

**Business Function Framework Line(s) of Business:** N/A

**Business Function Framework Function(s):** N/A

**VHA Portfolio:** Business Informatics

**Business Owner:** VHA CBO

**VASI ID:** 1882

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123363/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** ICB is integrated with several VistA
components such as, Appointment Scheduling and the Patient’s Insurance
File. ICB provides an electronic list of veterans with scheduled
appointments whose insurance needs to be verified. The "Patient Update"
List is used by check-in and registration clerks to scan insurance cards
for those identified. Scanned images are stored and are immediately
accessible to verification clerks via the "Insurance Buffer Entries"
list. Data from the image can be compared with existing insurance data
within VistA. By using advanced Optical Character Recognition (OCR)
technology, insurance-related text can be entered directly from the
digital image and saved to the VistA Insurance Buffer. A reporting
utility is available to Business Office Managers to ensure compliance of
check-in and verification clerks.

By expediting the data collection process at check-in, ICB helps a VA
facility improve the patient check- in experience and customer
satisfaction. It also increases insurance data accuracy and allows for
standardization of the verification process.​

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/insurance-capture-buffer/

-  Paperless Work Flow

-  Reduce Insurance Buffer File Errors

-  Audit functionality by categories including Patients, Clerks and Date

-  Identify the patient by appointment and location

-  Alerts entry clerks to update insurance information

-  Scan the insurance card with a small desktop scanner

-  Saves the image for the insurance verification clerk

-  Comprehensive and Accurate Process for Verification Clerks

-  View work list of patients with recently scanned cards

-  Compare existing VistA data against scanned insurance card image

-  OCR to capture data directly from insurance card image

-  Save updated data to VistA Insurance Buffer File

-  Save updated data image to VistA Imaging

-  View buffer from non IB sources

-  VetLink Kiosk support

   1. .. rubric:: 
         Mental Health Suite (MHS)
         :name: mental-health-suite-mhs

**Version**:

**Namespace:** DSIU

**Brief Description:** DSS Inc. COTS integration for managing and
documenting the care and treatment of mental health patients.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner:** Office of the Assistant Deputy Under Secretary for
Health for Patient Care Services (Dr. Lysell)

**VASI ID:** 1528

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123263/c/56/nt/27619?id=1578

**VDL Link: **

**Full Description and Features:** MH Suite is a COTS software tool used
to support the development and documentation of multidisciplinary
treatment plans. MH Suite facilitates development of care plans that
meet accreditation requirements in behavioral health settings, including
multidisciplinary input from all care team members contributing to the
plan, supporting one umbrella plan for all behavioral healthcare, and
providing a mechanism for updating plans as problems are resolved.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/integrated-clinical-products/mental-health-suite-mhs/

-  Graphical user interface with standardized and customizable patient
   data and provider notes entry capabilities

-  Advanced editing tools

-  Patient-centric focus of documentation includes all required elements
   of mental health treatment plan, supporting compliance with Joint
   Commission and CARF accreditation standards

-  Consistent with DSM-5 format

-  Integrated reporting module

-  Plan renewal capabilities

-  Comprehensive risk identification and prevention tools

   1. .. rubric:: 
         Release of Information (ROI)
         :name: release-of-information-roi

**Version**:

**Namespace:** DSIR

**Brief Description:** COTS integration with VistA Release of
Information (ROI) is designed to expedite ROI requests and reduce costs,
Release of Information integrates seamlessly with vxVistA and the
Computerized Patient Record System (CPRS) and supports the tracking,
fulfilling and releasing of ROI requests electronically.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1564

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123140/c/56/nt/-1?id=1578

**VDL Link:** https://www.va.gov/vdl/application.asp?appid=132

**Full Description and Features:** The ROI Manager is a COTS application
integration with VistA that uses RPC Broker technology that permits the
facility users to retrieve clinical data within the VistA System. The
user can work offline of VistA and only administrator functions will be
active. The ROI Manager Encounter System database is linked to the VistA
System database that stores registered patient documentation. These
databases are in sync with each other and reduce data entry time because
certain data fields are automatically populated (or filled-in) ensuring
data accuracy.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/dss-vista-integrated-administrative-products/release-of-information/

-  Prevent ROI request backlogs

-  Track ROI requests by patient and/or requestor

-  Automatically print notice and reply letters

-  Set reporting status as open, closed, pending or denied

-  Generate reports

-  Set and apply automated billing rules

-  Track paper and imaged documents not found in CPRS database

-  Comply with HIPAA requirements

   1. .. rubric:: 
         Telecare Record Manager (TRM)
         :name: telecare-record-manager-trm

**Version**:

**Namespace:** DSIT

**Brief Description:** DSS TeleCare Record Manager is a COTS integration
with VistA that provides a complete telephone liaison care management
system.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1805

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123211/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** DSS TeleCare Record Manager is a COTS
integration with VistA that provides a complete telephone liaison care
management system that provides an easy and efficient way for you to
access telephone treatment protocols and update and organize information
from different categories of patient calls.

DSS TeleCare Record Manager (TRM) Plus is a HIPAA-compliant,
URAC-certified telephone liaison care management solution that provides
easy and efficient access to telephone treatment protocols. The solution
also enables users to update and organize information based on patient
call category.

TRM Plus integrates seamlessly with VistA and DSHI Veterans Health
Gateway (VHG), which enhances telephone triage decision-making by
helping nurses accurately assess patient symptoms and quickly determine
the proper course of action for treatment.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/integrated-clinical-products/telecare-record-manager/

-  Integrates with VistA and DSHI Veterans Health Gateway (VHG) triage
   solution

-  Enables the automatic creation of Text Integration Utility (TIU)
   notes in CPRS

-  Supports call history, management and workload reporting

-  Provides direct access to patient information in VistA

   1. .. rubric:: 
         VistA Chemotherapy Manager (VCM)
         :name: vista-chemotherapy-manager-vcm

**Version**:

**Namespace:** DSIQ

**Brief Description:** VistA Chemotherapy Manager (VCM) automates the
entire chemotherapy treatment process, from therapy assignment to dose
calculation to documentation of care.

**Business Function Framework Line(s) of Business: **

**Business Function Framework Function(s): **

**VHA Portfolio: **

**Business Owner: **

**VASI ID:** 1883

**VASI ID Link:**
https://vaausdarapp41.aac.dva.va.gov/ee/request/folder/e/123364/c/56/nt/-1?id=1578

**VDL Link: **

**Full Description and Features:** VistA Chemotherapy Manager (VCM) is a
COTS integration with VistA for computerizing the administration of
chemotherapy for cancer care. It automates the clinical practice of
Oncology from the assignment of therapy to the calculation of
chemotherapy doses, all the way through to the documentation of care. It
combines a complete range of automation, safety features and flexibility
that Oncology practices demand.

Provides the full range of automated chemotherapy administration and
advanced safety features required by oncology providers, nurses and
pharmacists.

**Note:** This application is a DSS COTS integration with VistA, more
information can be found at
https://www.dssinc.com/products/integrated-clinical-products/vista-chemotherapy-manager/

-  Integrates with VistA/CPRS

-  Automates dose calculations and modifications

-  Enables treatment plans to be assigned and reviewed electronically

-  Transmits chemotherapy orders without disrupting pharmacy workflows

-  Includes a comprehensive database of standardized chemotherapy
   regimens

-  Supports treatment plan cancellations

-  Sends drug interaction alerts

Resources
---------

 

**VA Monograph**: The Monograph is a collection of descriptions of all
VistA applications.

http://www.va.gov/vista_monograph/

**VA Software Documentation Library**: This library contains a
collection of documentation for VA applications. All documents can be
viewed, downloaded, and printed.

 

http://www.va.gov/vdl

 

**VHA Enterprise Architecture**: VHA developed an Enterprise
Architecture that provides a technical framework to promote a
one-technology vision across the Department so that all systems are
interoperable.

http://www.ea.oit.va.gov/index.asp

.. |The official seal of the Department of Veterans Affairs.| image:: media/image1.jpg
   :width: 2.08194in
   :height: 2.08194in
