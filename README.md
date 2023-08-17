# Database design for Real Estate Management Company
Conceptual and logical database design based on a business case for a real estate management company

This database design was part of an assignment and it was to create a Chen's notation and a crows foot notation ERD for a business case. The business case is split into two parts the first ERD which is the Chen's notation ERD is based on part one. The second ERD which is the crows foot notation ERD is based on part 2 and part 1. 

Any assumptions are stated with highlighted text. The full SVG's for the database can be downloaded from this repository.

## The case

### Part 1:
A real estate management company manages many residences across Auckland. It has many agents who handle the day-to-day operations of running the show. An agent has a badge number showing their name and phone number. While the company records an agent's full name (a first, last and an optional middle name), the display name on the badge is abbreviated to show the first letter of the first name followed by the last name (e.g., Elizabeth Ann Taylor shows as E. Taylor). Depending on their preferences, agents may choose to work on weekday or weekend shifts. These agents may hold accreditations, usually from local councils or national organisations. Since most agents use a vehicle to visit the properties, the company assigns them a designated parking space. The company maintains a list of residences they manage. Each place could be an apartment, a townhouse or an independent house. Its address (including suburb and postcode) must be part of the record, besides the name of its current owner (or owners), a contact phone number and an email address. The company also records the weekly rent for each residence. Where a tenant is already occupying the home, the company records the name of the primary tenant (and any other family members or friends staying there), besides a contact phone
number and an email address. The company policy is to ensure only one agent manages every residence - this assignment happens when taking over management of that place. While an agent handles many homes, newly recruited agents may have to wait before managing one.

### Part 2:

This company wants to expand its business by entering the commercial segment. While the basic operations may seem identical, some unique features of the commercial sector need to be part of the data model. For one, details of owners and tenants need to be captured in a more organised manner to address regulatory concerns in this market. They also realise that some tenants are companies (instead of individuals), so their business credit rating is critical. Also, these companies usually assign a solicitor to handle all contracts. In addition, tenants leasing multiple properties is standard practice.

To address this market, they realise that some properties might be too large for a single agent to manage. So, they want to remove the earlier restriction of having a single agent for each property. To manage the properties with a professional flair, the company wants to track all property-related issues. They want to ensure that each case is assigned only one agent (to avoid confusion). As they expect increased demand in both markets, they want to assist prospective tenants
(or prospects) in finding suitable properties. This offering means they will need viewing agents while current agents transform into property management agents. Viewing agents don't need any accreditations but must undergo police vetting. These agents arrange for prospects to view vacant properties or those nearing the end of their lease.

Prospects must register with the company before they view properties. Registration involves providing their legal name, some form of government ID, date of birth, phone number and email address. They must also indicate one or more date/time windows suitable for viewing. While optional, sharing a target weekly budget is encouraged to find suitable properties. Only one viewing agent handles this interaction and records the prospect's opinion of the property (yes, no, maybe).

## Chens notation ERD (Download SVG for best resolution)


## Crows foot ERD (Download SVG for best resolution)

