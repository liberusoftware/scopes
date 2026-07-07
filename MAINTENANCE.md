```markdown id="6ef56"
# Liberu Maintenance
## Product Feature & Design Scope

> **Version:** 1.0  
> **Framework:** Laravel 13 + Filament 5  
> **Product Type:** Computerised Maintenance Management System (CMMS)

---

# Vision

Liberu Maintenance is a modern, API-first Computerised Maintenance Management System (CMMS) designed for organisations and service providers responsible for maintaining buildings, equipment, facilities and assets.

The platform should support everyone from independent tradespeople through to enterprise facility management companies, offering a clean, intuitive user experience while remaining highly configurable and scalable.

Rather than focusing on a single industry, Liberu Maintenance should provide flexible workflows suitable for:

- Facility Management
- Property Maintenance
- Building Management
- Electrical Contractors
- Plumbing Companies
- HVAC Contractors
- Fire & Security Engineers
- Cleaning Companies
- Landscaping Contractors
- General Builders
- Handymen
- Commercial Maintenance Providers
- Industrial Maintenance
- Manufacturing
- Schools
- Healthcare
- Hospitality
- Retail
- Warehousing
- Public Sector
- Housing Associations

---

# Core Principles

- API-first architecture
- Multi-company support
- Multi-branch support
- Multi-site support
- Mobile-first workflows
- Fully localisable
- Modular design
- Role & permission driven
- Offline-friendly future mobile support
- Asset-centric maintenance
- Preventative maintenance first
- Simple enough for small businesses, scalable for enterprise

---

# First-Time Setup Wizard

Upon installation the administrator should complete a guided setup.

## Organisation

- Company name
- Branding
- Logo
- Contact information
- Timezone
- Currency
- Language

## Business Type

Examples:

- Facility Management
- Property Maintenance
- Electrical
- Plumbing
- HVAC
- Fire & Security
- General Contractor
- Manufacturing
- Multi-service contractor

This should configure sensible defaults without restricting future customisation.

---

# Localisation

Designed from the ground up for international deployments.

Support includes:

- Multiple languages
- Multiple currencies
- Regional date formats
- Timezones
- Address formats
- Country-specific validation
- Local tax references
- Translation files

---

# User Management

## Users

- User accounts
- Teams
- Departments
- Branches
- Job roles
- Engineer profiles
- Profile photos
- Skills
- Certifications

---

# Permissions

Granular permissions for every module.

Examples:

- View
- Create
- Edit
- Delete
- Approve
- Complete
- Assign
- Export
- Manage

---

# Customers

Store customer information including:

- Residential customers
- Commercial customers
- Organisations
- Property owners
- Housing associations
- Facilities managers
- Landlords

Customer records include:

- Contact details
- Multiple sites
- Notes
- Documents
- Communication history
- Contracts
- Tags

---

# Sites & Locations

Customers may have multiple sites.

Each site supports:

- Buildings
- Floors
- Rooms
- Zones
- External areas

Location hierarchy should be unlimited.

Example:

Customer

→ Site

→ Building

→ Floor

→ Room

→ Asset

---

# Asset Management

Maintain a complete asset register.

Examples:

- Boilers
- Pumps
- HVAC units
- Lifts
- Electrical panels
- Fire alarms
- CCTV
- Generators
- Doors
- Lighting
- Appliances
- Machinery
- Vehicles
- IT equipment

Each asset includes:

- Name
- Reference number
- QR code
- Barcode
- Category
- Manufacturer
- Model
- Serial number
- Purchase information
- Warranty
- Supplier
- Installation date
- Expected lifespan
- Current status
- Photos
- Documents
- Manuals
- Certificates
- Service history

---

# Asset Categories

Unlimited nested categories.

Examples:

- HVAC
- Electrical
- Plumbing
- Mechanical
- Fire Safety
- Security
- Cleaning
- Landscaping
- Vehicles
- Plant Equipment

---

# Work Orders

Central work order management.

Types include:

- Reactive
- Preventative
- Corrective
- Emergency
- Inspection
- Installation
- Quotation
- Warranty
- Planned Maintenance

Work orders include:

- Priority
- Status
- Assigned engineer
- Customer
- Site
- Asset
- Description
- Attachments
- Photos
- Parts
- Labour
- Notes
- Completion details

---

# Work Order Lifecycle

Example statuses:

- Draft
- New
- Awaiting Assignment
- Assigned
- Accepted
- Travelling
- On Site
- In Progress
- Waiting Parts
- Waiting Customer
- On Hold
- Completed
- Reviewed
- Closed
- Cancelled

---

# Job Scheduling

Powerful scheduling system.

Features include:

- Calendar view
- Drag-and-drop scheduling
- Engineer allocation
- Availability
- Travel planning
- Multi-day jobs
- Recurring jobs
- Route optimisation (future)

---

# Preventative Maintenance

Create maintenance schedules based on:

- Time
- Usage
- Meter readings
- Calendar dates

Examples:

- Weekly
- Monthly
- Quarterly
- Biannually
- Annually
- Every X days
- Custom schedules

Automatic work order generation.

---

# Reactive Maintenance

Quickly create reactive jobs.

Support:

- Customer requests
- Internal reports
- Portal requests
- Email requests
- API requests

---

# Inspections

Inspection templates.

Examples:

- Fire alarms
- Emergency lighting
- HVAC inspections
- Boiler servicing
- Electrical testing
- Property inspections

Features:

- Pass / Fail
- Photos
- Notes
- Measurements
- Signatures
- Follow-up actions

---

# Checklists

Configurable checklists.

Support:

- Required steps
- Pass / Fail
- Numeric readings
- Photos
- Notes
- Signatures

---

# Parts & Inventory

Inventory management for maintenance.

Features:

- Parts catalogue
- Stock locations
- Warehouses
- Vans
- Branch stock
- Transfers
- Reserved stock
- Reorder levels
- Suppliers

Track:

- Stock movements
- Usage
- Returns
- Adjustments

---

# Suppliers

Store supplier information.

Including:

- Contact details
- Products
- Price lists
- Documents
- Performance notes

---

# Purchase Requests

Support:

- Part requests
- Purchase approvals
- Supplier allocation
- Delivery tracking

Accounting remains outside project scope.

---

# Labour Tracking

Record:

- Engineers
- Time on site
- Travel time
- Breaks
- Overtime
- Internal notes

---

# Time Tracking

Support:

- Manual entry
- Timer
- Start/Stop
- Mobile tracking
- Daily summaries

---

# Quotations

Create quotations for:

- Repairs
- Installations
- Maintenance
- Planned works

Support:

- Line items
- Labour
- Materials
- Notes
- Approval tracking

---

# Contracts

Manage maintenance contracts.

Features:

- Contract types
- Coverage
- SLA
- Start/end dates
- Renewal reminders
- Documents
- Linked customers
- Linked assets

---

# SLA Management

Configure response targets.

Examples:

- Emergency
- Urgent
- Standard
- Planned

Track:

- Response time
- Arrival time
- Completion time
- SLA compliance

---

# Compliance

Track compliance documents.

Examples:

- Gas Safety
- Electrical Certificates
- PAT Testing
- Fire Safety
- Risk Assessments
- RAMS
- Insurance

Receive renewal reminders.

---

# Documents

Store:

- Manuals
- Drawings
- Certificates
- Photos
- Videos
- PDFs
- Contracts

Support:

- Categories
- Version history
- Permissions
- Expiry dates

---

# Media

Support:

- Before photos
- During photos
- After photos
- Videos
- Voice notes

Automatic image optimisation.

---

# QR Codes & Barcodes

Generate QR codes for:

- Assets
- Locations
- Equipment
- Work orders

Future mobile applications should allow engineers to scan codes for instant access.

---

# Customer Portal

Customers should be able to:

- Raise requests
- View job progress
- View assets
- Download certificates
- View quotations
- Approve quotations
- View maintenance history

---

# Engineer Portal

Engineers should be able to:

- View assigned jobs
- Accept work
- Start travel
- Start work
- Upload photos
- Complete checklists
- Capture signatures
- Record parts
- Complete jobs

---

# Notifications

Support:

- In-app notifications
- Email
- SMS
- Push notifications

Events include:

- New jobs
- Assignment
- SLA alerts
- Overdue work
- Low stock
- Contract renewals
- Asset failures

---

# Communication

Maintain communication history.

Support:

- Emails
- SMS
- Phone logs
- Internal notes
- Customer notes

---

# Dashboards

Configurable dashboards.

Widgets include:

- Open work orders
- Jobs due today
- Overdue work
- Engineers on site
- SLA performance
- Asset health
- Stock alerts
- Contracts due
- Customer requests

---

# Reporting

Comprehensive reporting.

Examples:

- Work orders
- Engineer productivity
- Asset maintenance
- Downtime
- Parts usage
- SLA compliance
- Customer history
- Preventative maintenance
- Reactive maintenance
- Inventory
- Contracts

Support:

- Saved reports
- Filters
- Charts
- Exports

---

# Search

Global search across:

- Customers
- Sites
- Assets
- Work orders
- Engineers
- Suppliers
- Parts
- Contracts
- Documents

Advanced filtering throughout.

---

# Integrations

## Accounting

Native integrations with:

- Liberu Accounting
- QuickBooks Online
- Xero
- Sage

Scope includes:

- Customer synchronisation
- Supplier synchronisation
- Invoice references
- Payment status
- Purchase references

Full accounting remains outside the scope of Liberu Maintenance.

---

## Calendar

- Google Calendar
- Microsoft Outlook

---

## Maps

Support:

- Google Maps
- OpenStreetMap

Engineer navigation should integrate with mapping providers.

---

## Email

Support:

- SMTP
- Microsoft 365
- Gmail

---

## SMS

Pluggable SMS providers.

---

# Public API

Every major feature should be accessible through a versioned REST API.

Examples:

- Authentication
- Customers
- Sites
- Assets
- Work Orders
- Inspections
- Checklists
- Inventory
- Suppliers
- Contracts
- Documents
- Engineers
- Reports

The API should support:

- Web applications
- Mobile applications
- Customer portals
- Third-party integrations
- Internal Liberu products

---

# Future Modules

Potential future modules include:

- Predictive maintenance
- IoT sensor integration
- Smart building integration
- GPS fleet management
- Vehicle maintenance
- BIM integration
- AI maintenance scheduling
- AI fault diagnosis
- AI document extraction
- Offline mobile applications
- Digital twin support
- Energy monitoring
- Carbon reporting
- Permit to Work management
- Health & Safety module
- Incident reporting
- Risk assessments
- Contractor management
- Multi-tenant SaaS management

---

# Overall Goal

Liberu Maintenance should provide a modern, highly configurable and scalable CMMS that supports organisations of all sizes, from independent tradespeople to enterprise facilities management providers.

The platform should deliver comprehensive asset, maintenance, scheduling and workforce management capabilities through a clean Laravel 13 and Filament 5 experience while remaining modular, API-driven and ready for future mobile applications and integrations.
```
