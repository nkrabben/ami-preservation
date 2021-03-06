---
title: PAMI Overview
layout: default
nav_order: 2
---

# Overview of PAMI Unit
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Staff
#### Rhony Dostaly, Media Preservation Engineer - Moving Image
{: .no_toc }
Carries out the preservation assessment, treatment, and reformatting of video recordings held in the Library’s permanent research collections.

#### Fran Dougherty, Media Preservation Engineer - Moving Image
{: .no_toc }
Carries out the preservation assessment, treatment, and reformatting of video recordings held in the Library’s permanent research collections. Processes include: media stabilization/cleaning/repair, signal extraction, and creation of high quality digital files.

#### Ryan Marino, Media Preservation Assistant
{: .no_toc }
Assists with the coordination, evaluation, and implementation of specifications and workflows for digital asset quality control and film assessment.

#### Genevieve Havemeyer-King, Media Preservation Coordinator
{: .no_toc }
Coordinates, implements, and documents workflows and specifications for contract digitization, digital asset quality control, and film assessment; trains and supervises Media Preservation Assistants.

#### Rebecca Holte, Manager of Audio and Moving Image Preservation
{: .no_toc }
Manages overall AMI preservation program, recommends and develops preservation priorities, technology solutions, and workflows. Develops and manages donor and grant funds, vendor contracts, and mass digitization projects. Provides support for acquisitions and emergency response.

#### Jeff Willens, Media Preservation Engineer - Audio
{: .no_toc }
Carries out the preservation assessment, treatment, and reformatting of audio recordings held in the Library’s permanent research collections.

#### Seth Winner, Media Preservation Engineer - Audio
{: .no_toc }
Carries out the preservation assessment, treatment, and reformatting of audio recordings held in the Library’s permanent research collections.

#### Andy Theodorou, Media Preservation Engineer - Audio
{: .no_toc }
Carries out the preservation assessment, treatment, and reformatting of audio recordings held in the Library’s permanent research collections.

#### Benjamin Turkus, Assistant Manager of Audio and Moving Image Preservation
{: .no_toc }
Provides oversight for all in-house media preservation lab operations, and manages Media Preservation Engineers. Develops workflows, documents processes, and pursues open source solutions.

## Project Structure
### Projects
Within PAMI, a project describes reformatting activity on a batch of media, initiated by either on-going the AMI Initiative or Public Orders (patron or donor requests).

### Work Orders
Work Orders are a subdivision of a project, but a project may consist of one or many Work Order (many in-house Projects consist of only one Work Order, but most Contract / Vendor projects consist of multiple Work Orders due to the high-volume of media).

### Deliverables
Deliverable requirements for in-house vs. contract reformatting work vary slightly.
* Vendor deliverable requirements are defined on the [ami-specifications](https://github.com/NYPL/ami-specifications/) repo.
* In-house deliverable requirements documentation is pending.

# Project tracking
## [PAMI Database](pami-database)
* The PAMI Database is used to establish project IDs, track deliverables, and generate statistics and metadata for AMI digitization projects.

## Vendor Shipments
* Upon arrival, all deliverables (hard drive or network-based shipments) are logged in the [AMI Vendor Project Tracking sheet](https://docs.google.com/spreadsheets/d/1ZeF6vGE1TqLnKaNjZFSIvjyKhYBt38nBcZDHyD_saPo/edit#gid=1908905860) document.

## Trello
[Trello](https://trello.com/nyplamipreservationlabs) cards are used to manage digitization and quality control of in-house and vendor work orders.
* Boards:
  * [NYPL AMI Labs](https://trello.com/b/cbbd5QgE/nypl-ami-labs)
  * [NYPL AMI Quality Control and Ingest](https://trello.com/b/CBLrQvG1/nypl-ami-quality-control-and-ingest)
  * [NYPL AMI Vendor Labs](https://trello.com/b/F57dfPzd/nypl-ami-vendor-labs)

## Google Drive
* AMI Google Team Drive is used for storing and sharing internal documents related to AMI work (specific folders are shared as needed with staff).

# Project Close-Out
## Project Summaries
* Compiling Manifests & Reports
  * **Capture Issues:** Find & delete the following characters in the vendor's DNC reports & HDmanifests
    - vertical tab ```\v```
    - tab ```\t```
    - carriage return ```\r```
    - new line [similar to carriage return but they both appeared separately] ```\n```

* DNC object management
  * Separate the items by original project fund (pami work orders should at a minimum be separated by project fund). Example: Slifka, Mellon. No need to separate by unit or research center.
  * Manager will forward the DNC list separately, and you can review to identify what should be sent to PAMI. Manager will pull objects and box-up according to project fund. On return, media goes back into they're original boxes.
  * For PAMI metadata, pull  item records from the original metadata inventory from initial project and create internal db records (remembering to change the cms project code).
  CMS:
    * CMS project code: PAMI
    * CMS title / description: DNC - [fund name]
  ....EXAMPLE: dnc - mellon
  CMS batch #:... next available sequential ## (can we put a placeholder in PAMI work orders until this is ready?)
