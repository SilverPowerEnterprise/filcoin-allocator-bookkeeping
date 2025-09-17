# Filecoin Plus DataCap Allocator - Client Applications

Welcome to the GitHub repository dedicated to managing the Lifecycle Data Notations (LDN) Applications for a specific Filecoin Plus DataCap allocator team. This repository serves as a public ledger for DataCap allocation requests and tracking, facilitating transparency and efficiency in the process.

## Overview

Filecoin Plus (Fil+) enhances the utility of Filecoin by not just storing data, but also verifying the usefulness of the data being stored. DataCap is allocated to clients based on their storage needs and the value their data brings to the Filecoin network. Our team, operating under a shared multisig wallet, acts as an allocator of DataCap, assessing and verifying client requests.

## How It Works

Instead of a traditional code repository, this GitHub repo functions as a structured ledger to handle DataCap requests through Client Applications. Each application's lifecycle, from request to allocation, is publicly documented here.

### Requesting DataCap

1. **Open an Issue:** Clients looking to request DataCap must open a new issue in this repository. The issue should include detailed information about the project requiring DataCap. Essential information includes but is not limited to:
   - Project name and description
   - Amount of DataCap requested
   - Justification for the DataCap amount
   - Information about the data owner for KYC

2. **Filling the Application Template:** An issue template will guide clients through submitting the necessary information for their DataCap request.

### Review and Allocation Process

1. **Initial Review:** Once an issue is opened, our allocator team will conduct an initial review to ensure all necessary information is provided.
2. **Discussion & Clarification:** The team may engage in discussions within the issue thread for clarifications or additional information.
3. **Decision:** The allocator team will make a decision on the DataCap request. If approved, the process moves to the allocation phase.

### Managing the Client Application Lifecycle

- Each Client Application's lifecycle is tracked through a `.json` file in this repository, uniquely associated with the client's issue.
- The `.json` file is created when an application is initially approved for allocation and is updated through pull requests as more DataCap is allocated or as the application status changes.
- This structured approach ensures transparency and traceability for both clients and the allocator team.

## Code of Conduct

This repository operates under a Code of Conduct to ensure a respectful and productive environment for all participants. By participating in this project, you agree to abide by its terms.

---

We look forward to facilitating an efficient and transparent process for DataCap allocations within the Filecoin Plus program. Thank you for your interest and participation.


### Pathway 
SilverPower is a manual pathway, we will go through manual due diligence case by case.

### Contact info
mail: chenzhuo@sliverpower.cn ; sp@sliverpower.cn 
Slack: @zhuo

### Policy  &  risk mitigation
As a new allocator, we choose manual pathway that means more careful due diligence is needed.
Based on the application submitted , first I will verify the authentication of the existing information about the client. Then I will ask additional information or ask for explanation for the discrepancy part if necessary. If the information in application is not clear enough, then more questions will be posted for further investigation:
1.can you send the screenshot of business license to allocator’s mail address(for new client); can you share the previous link of application for verification(for old client)
2.Can you provide any proof of data size?
3.Are you a data preparer? If yes, can you describe the process and the tooling used for data preparation in details. If not, how will choose a data preparer to make sure the data is processed in a standardized way.
4.How much do you know IPNI? How much do you know about Spark retrieval?
5.How can you assure the retrieval rate is above the bar of 75%? If SPs selected can not meet the standard, as expected, what will you do?
6. how will deal with CID sharing problem if occurred?
7. how long will you finish sealing for one round？
8. Is VPN allowed for SP?
Ideally, all the back-and-forth messages between allocator and client will be performed directly on github publicly. If any privacy involved, like ID doc, proof of address etc., then those highly-sensitive audit proof will sent to governance team by email. Any discrepancy arises from the approval process, a meeting can be scheduled for clarification.

### Dispute resolution
All the commnucation will be made open to the public, once any dispute occurred, then raise an issue in fil+ governance repo to have a discussion, fil+  governance officials may be invited to have a say.

### Audit plans
I will provide the back-and-forth communication screenshots between allocator and client, including reasonable explanation and CID checker report improvement proof, retrieval results screenshot etc.
