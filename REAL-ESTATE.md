```markdown
# Liberu Real Estate
## Product Feature & Design Scope

> **Version:** 1.0  
> **Framework:** Laravel 13 + Filament 5  
> **Status:** Product Scope Document

---

# Vision

Liberu Real Estate is a modern, API-first estate agency platform designed for residential and commercial agencies of all sizes. It should provide feature parity with established products such as Jupix, Street, AgentOS and Property Hive while embracing modern Laravel architecture, extensibility and localisation.

The platform should support single-office agencies through to multi-branch enterprise organisations, with every major feature exposed through a documented API for future web, mobile and third-party applications.

Accounting functionality is intentionally outside the scope of this project, instead providing seamless integrations with Liberu Accounting and major third-party accounting platforms.

---

# Core Principles

- API-first architecture
- Mobile-ready
- Multi-company support
- Multi-branch support
- Multi-country support
- Fully localisable
- Modular architecture
- Role & permission driven
- Cloud and self-hosted deployments
- Extensive automation capabilities
- Modern user experience
- High performance

---

# First-Time Setup Wizard

Upon installation, the administrator should complete a guided setup wizard.

## Organisation

- Agency name
- Logo
- Branding
- Contact details
- Office address
- Timezone

## Operating Countries

Users should select one or more operating countries.

Example:

- United Kingdom
- Ireland
- Australia
- Canada
- United States
- South Africa
- New Zealand

Country selection should configure defaults such as:

- Currency
- Date formats
- Phone formats
- Address formats
- Measurement units
- Tax defaults
- Language
- Postal code validation
- Portal integrations

Future versions should allow countries to become installable modules without changing the user experience.

---

# Localisation

Designed from day one for localisation.

Support includes:

- Multiple languages
- Multiple currencies
- Regional number formatting
- Timezones
- Translation files
- Local address formats
- Country-specific validation
- Country-specific workflows
- Country-specific legal terminology

---

# User Management

## Users

- User accounts
- Teams
- Branches
- Departments
- Job roles
- Profile management
- MFA support
- API tokens

## Permissions

Granular permissions for every module.

Examples:

- View
- Create
- Edit
- Delete
- Export
- Approve
- Publish
- Archive

---

# CRM

## Contacts

Single contact database for:

- Applicants
- Vendors
- Landlords
- Tenants
- Buyers
- Solicitors
- Developers
- Contractors
- Investors
- Businesses

Each contact includes:

- Multiple addresses
- Multiple phone numbers
- Multiple emails
- Notes
- Communication history
- Documents
- Tags
- Relationships

---

# Companies

Support business contacts including:

- Developers
- Property companies
- Housing associations
- Investment firms
- Contractors

---

# Property Management

## Property Records

Store complete property information.

Including:

- Residential
- Commercial
- Land
- New builds
- Developments
- Mixed-use

Property information:

- Full address
- Coordinates
- EPC
- Floor area
- Bedrooms
- Bathrooms
- Reception rooms
- Parking
- Gardens
- Features
- Description
- Internal notes

---

# Property Media

Support:

- Images
- Floorplans
- EPC certificates
- Videos
- Virtual tours
- 360 tours
- Documents
- Brochures

Automatic:

- Image optimisation
- Ordering
- Watermarks
- Metadata

---

# Property Status

Examples:

- Draft
- Coming Soon
- Available
- Under Offer
- SSTC
- Exchanged
- Sold
- To Let
- Let Agreed
- Let
- Withdrawn
- Archived

---

# Sales

Manage complete sales lifecycle.

Features include:

- Vendor onboarding
- Valuations
- Instructions
- Marketing
- Viewings
- Offers
- Memorandum of Sale
- Sales progression
- Exchange
- Completion

---

# Lettings

Support complete lettings workflow.

Including:

- Landlords
- Tenants
- Referencing
- Guarantors
- Deposits
- Inventories
- Tenancy agreements
- Renewals
- Notices
- End of tenancy

---

# Property Matching

Automatic matching between:

- Buyers
- Tenants
- Available properties

Matching criteria:

- Budget
- Bedrooms
- Property type
- Location
- Radius
- Features
- Availability
- Schools
- Transport

Notify users automatically when matches occur.

---

# Valuations

Support:

- Market appraisals
- Rental valuations
- Commercial valuations

Features:

- Diary booking
- Assigned negotiator
- Notes
- Comparable properties
- Follow-up reminders
- Outcome tracking

---

# Viewings

Manage property viewings.

Features:

- Calendar integration
- Multiple attendees
- Staff assignment
- Confirmation emails
- Reminder emails
- Feedback collection
- Outcome tracking

---

# Offers

Track offers including:

- Offer amount
- Buyer details
- Mortgage status
- Chain information
- Conditions
- Negotiation history
- Accepted
- Rejected
- Withdrawn

---

# Sales Progression

Track every milestone.

Examples:

- Offer accepted
- Memorandum issued
- Mortgage
- Searches
- Survey
- Exchange
- Completion

---

# Property Maintenance

Track maintenance requests.

Features:

- Issues
- Priority
- Photos
- Contractors
- Quotes
- Jobs
- Completion tracking
- Cost references
- Status updates

(No accounting beyond referencing invoices and payments.)

---

# Inspections

Support:

- Routine inspections
- Check-in
- Check-out
- Mid-tenancy inspections

Including:

- Photos
- Notes
- Damage reporting
- Signatures

---

# Diary & Calendar

Unified calendar supporting:

- Viewings
- Valuations
- Meetings
- Inspections
- Maintenance
- Tasks
- Reminders

Calendar views:

- Day
- Week
- Month
- Agenda

---

# Task Management

Features:

- Personal tasks
- Team tasks
- Due dates
- Priorities
- Checklists
- Attachments
- Comments

---

# Communication

Maintain communication history.

Support:

- Emails
- SMS
- Phone logs
- Notes
- Letters

Future support:

- WhatsApp
- Microsoft Teams
- Slack

---

# Document Management

Store:

- Contracts
- Agreements
- ID documents
- Compliance certificates
- PDFs
- Images
- Generated documents

Support:

- Version history
- Categories
- Permissions
- Digital signatures

---

# Marketing

Property marketing tools.

Features:

- Brochure generation
- Window cards
- Social media assets
- QR codes
- Property websites
- Email campaigns
- Featured listings

---

# Website Integration

Provide APIs for agency websites.

Support:

- Property search
- Property details
- Featured properties
- New listings
- Sold properties
- Branch information
- Staff profiles

---

# Property Portal Integrations

Designed around country-specific integrations.

Example (United Kingdom):

- Rightmove
- Zoopla
- OnTheMarket

Future country packs may include:

- Domain
- realestate.com.au
- Zillow
- Realtor.com
- Trade Me Property

Support:

- Automatic exports
- Scheduled synchronisation
- Status updates
- Listing management
- Media uploads

---

# Reporting

Dashboard reports including:

- Sales pipeline
- Lettings pipeline
- Instructions
- Offers
- Viewings
- Valuations
- Staff performance
- Branch performance
- Marketing performance
- Portal statistics

Reports should support:

- Filters
- Saved reports
- Exports
- Charts

---

# Dashboards

Customisable dashboards.

Widgets include:

- KPIs
- Calendar
- Tasks
- Recent activity
- Sales
- Lettings
- New leads
- Property pipeline
- Maintenance
- Branch statistics

---

# Automation

Automation engine for repetitive workflows.

Examples:

- Send follow-up emails
- Assign staff
- Notify negotiators
- Publish listings
- Portal exports
- Reminder emails
- Renewal reminders
- Viewing reminders
- Task creation

Future support should include a visual workflow builder.

---

# Notifications

Support:

- In-app notifications
- Email
- SMS
- Push notifications

Notification events include:

- New enquiries
- Offers
- Viewing requests
- Tasks
- Maintenance
- Renewals
- Portal failures

---

# Search

Global search across:

- Properties
- Contacts
- Companies
- Documents
- Viewings
- Tasks
- Offers
- Maintenance
- Staff

Advanced filtering throughout the application.

---

# Integrations

## Accounting

Native integration with:

- Liberu Accounting
- QuickBooks Online
- Xero
- Sage

Scope includes:

- Customer synchronisation
- Supplier synchronisation
- Invoice references
- Payment status
- Financial summaries

Full bookkeeping remains outside the scope of Liberu Real Estate.

---

## Email

Support:

- SMTP
- Microsoft 365
- Gmail

---

## Calendars

- Google Calendar
- Microsoft Outlook

---

## Maps

Support:

- Google Maps
- OpenStreetMap

---

## SMS Providers

Pluggable SMS providers.

---

# Public API

Every major feature should be accessible through a versioned REST API.

Examples:

- Authentication
- Users
- Contacts
- Companies
- Properties
- Media
- Offers
- Viewings
- Tasks
- Documents
- Maintenance
- Reports
- Portal integrations

The API should be suitable for:

- Public websites
- Mobile applications
- Third-party integrations
- Internal Liberu products

---

# Future Modules

Potential future modules include:

- Auctions
- Holiday lettings
- Student accommodation
- Build-to-rent
- Commercial lease management
- Facilities management
- AI-powered property descriptions
- AI document extraction
- AI enquiry triage
- AI property matching
- Customer portals
- Vendor portal
- Landlord portal
- Tenant portal
- Buyer portal
- Contractor portal
- Mobile applications

---

# Overall Goal

Liberu Real Estate should provide a modern, scalable and extensible estate agency platform capable of competing with established industry products while remaining modular, API-driven and localisation-first.

The platform should deliver a comprehensive experience for agencies managing residential and commercial sales, lettings and property management, while integrating seamlessly with external accounting systems and country-specific property portals.
```
