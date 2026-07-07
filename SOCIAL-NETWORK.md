```markdown id="48271"
# Liberu Social Network
## Product Feature & Design Scope

> **Version:** 1.0  
> **Framework:** Laravel 13 + Filament 5  
> **Frontend:** Livewire 4 + Alpine.js  
> **PHP:** 8.5  
> **Product Type:** Decentralised Social Network & Community Platform

---

# Vision

Liberu Social Network is a modern, decentralised, API-first social networking platform designed for organisations, communities, businesses, educational institutions, clubs and private groups.

Unlike traditional social networks, Liberu Social Network should primarily focus on secure, self-hosted communities where organisations control their own data while optionally allowing federation between trusted Liberu Social Network instances.

The platform should support both **private invitation-only communities** and **fully public social networks**, making it suitable for everything from internal company collaboration to public interest communities.

---

# Core Principles

- Self-hosted by default
- API-first architecture
- Decentralised and federated
- Privacy focused
- Mobile friendly
- Offline-first capable (future)
- Modern user experience
- Role & permission driven
- Modular architecture
- Highly configurable
- Community driven
- Accessible and inclusive
- Open standards where practical

---

# Deployment Modes

## Private Network

Ideal for:

- Businesses
- Schools
- Universities
- Clubs
- Government
- Healthcare
- Internal communities

Features include:

- Invitation only
- Administrator approval
- Private content
- Internal messaging
- Organisation branding

---

## Public Network

Supports:

- Public registration
- Public profiles
- Public communities
- Search engine indexing
- Public posts
- Public media

Administrators should be able to mix private and public areas.

---

# First-Time Setup Wizard

Upon installation, administrators should configure:

## Organisation

- Name
- Branding
- Logo
- Theme colours
- Domain
- Contact details

## Community Type

- Private
- Public
- Hybrid

## Registration

Options include:

- Disabled
- Invite only
- Approval required
- Public registration

---

# User Accounts

Support:

- Email registration
- Invitations
- Username selection
- Display names
- Profile photos
- Cover images
- MFA
- API tokens
- Session management

Future support:

- Passkeys
- Social login
- Enterprise SSO

---

# User Profiles

Profiles include:

- Biography
- Avatar
- Cover image
- Website
- Pronouns
- Location
- Interests
- Skills
- Occupation
- Education
- Social links
- Badges

Privacy controls for every profile field.

---

# Connections

Support multiple relationship models.

Examples:

- Friends
- Followers
- Following
- Connections
- Family
- Colleagues

Administrators should choose which model(s) are enabled.

---

# News Feed

Modern personalised feed.

Support:

- Chronological
- Recommended
- Following
- Groups
- Local community
- Trending
- Saved posts

---

# Posts

Users can publish:

- Text
- Images
- Videos
- Audio
- Documents
- Polls
- Events
- Articles
- Links

Features:

- Drafts
- Scheduled publishing
- Rich text editor
- Markdown support (optional)
- Mentions
- Hashtags
- Emojis
- Attachments

---

# Reactions

Configurable reactions.

Examples:

- Like
- Love
- Celebrate
- Support
- Funny
- Insightful

Administrators may customise available reactions.

---

# Comments

Features include:

- Nested replies
- Rich text
- Images
- GIFs
- Reactions
- Mentions
- Moderation

---

# Sharing

Support:

- Reposts
- Quote posts
- Cross-community sharing
- External sharing
- Internal sharing

---

# Media Library

Support:

- Images
- Videos
- Audio
- Documents
- PDFs
- Archives

Features:

- Albums
- Compression
- Metadata
- EXIF removal
- Image optimisation
- Permissions

---

# Stories

Optional short-lived content.

Features:

- Photos
- Videos
- Text
- Stickers
- Expiry after 24 hours (configurable)

---

# Communities & Groups

Users can create communities.

Types:

- Public
- Private
- Hidden
- Invite only

Community features:

- Moderators
- Categories
- Announcements
- Files
- Events
- Galleries
- Polls
- Rules

---

# Pages

Organisation and public pages.

Suitable for:

- Businesses
- Schools
- Clubs
- Projects
- Products
- Teams

---

# Events

Event management.

Features:

- Public/private events
- RSVP
- Calendar
- Attendees
- Maps
- Tickets (future)
- Event discussions
- Reminders

---

# Messaging

Private messaging.

Support:

- One-to-one
- Group conversations
- File sharing
- Images
- Videos
- Voice notes
- Read receipts
- Message editing
- Message deletion
- Reactions

Future support:

- Voice calls
- Video calls

---

# Notifications

Support:

- In-app notifications
- Email
- Push notifications
- SMS (optional)

Notification types include:

- Mentions
- Messages
- Friend requests
- Reactions
- Comments
- Event reminders
- Group invitations

---

# Search

Global search across:

- Users
- Communities
- Pages
- Posts
- Events
- Documents
- Media
- Hashtags

Advanced filtering throughout.

---

# Hashtags

Support:

- Trending hashtags
- Following hashtags
- Suggested hashtags
- Search

---

# Bookmarks

Users may bookmark:

- Posts
- Articles
- Events
- Communities
- Profiles

Private to each user.

---

# Polls

Users may create polls.

Support:

- Single choice
- Multiple choice
- Anonymous voting
- Scheduled closing
- Result visibility

---

# Articles

Long-form publishing.

Features:

- Rich text
- Markdown
- Categories
- Tags
- Drafts
- Publishing workflow
- Comments
- Reading time

---

# File Sharing

Users can securely share:

- Documents
- Images
- Videos
- Archives
- Presentations
- Spreadsheets

Permissions include:

- Public
- Friends
- Community
- Private

---

# Knowledge Base

Optional wiki module.

Support:

- Documentation
- Categories
- Version history
- Collaboration
- Permissions

---

# Offline Sharing (Future)

Support offline-first functionality through Progressive Web App capabilities.

Potential features:

- Cached feeds
- Offline reading
- Offline drafting
- Automatic synchronisation
- Local notifications

---

# Federation

Support optional federation between Liberu Social Network instances.

Features include:

- Trusted servers
- User discovery
- Cross-server messaging
- Cross-server communities
- Cross-server profiles
- Shared content
- Server-level permissions

Federation should always be optional and configurable.

---

# External Social Network Import

Optional migration and synchronisation tools.

Potential integrations include:

- Mastodon
- Bluesky
- ActivityPub-compatible platforms
- Facebook (where APIs permit)
- LinkedIn (where APIs permit)
- X (Twitter) (where APIs permit)
- Instagram (where APIs permit)
- Reddit (limited import)
- Discord communities

Support:

- Profile import
- Contacts import
- Posts
- Media
- Followers (where available)
- Community migration

Availability depends on third-party API capabilities and policies.

---

# Privacy Controls

Users should control:

- Profile visibility
- Post visibility
- Community visibility
- Messaging permissions
- Search visibility
- Online status
- Read receipts
- Last active status

---

# Content Moderation

Support:

- Reports
- Content review
- Moderation queues
- Warnings
- Temporary suspension
- Permanent bans
- Appeal process

---

# Roles & Permissions

Granular permissions for:

- Users
- Moderators
- Community owners
- Administrators
- Editors

Permissions include:

- View
- Post
- Moderate
- Manage communities
- Manage users
- Manage media
- Export

---

# Analytics

Community analytics.

Examples:

- Active users
- Engagement
- Growth
- Popular posts
- Trending topics
- Community activity
- Content types
- User retention

---

# Admin Panel

Built with Filament 5.

Manage:

- Users
- Communities
- Pages
- Posts
- Events
- Media
- Reports
- Moderation
- Notifications
- Analytics
- Federation
- System settings

---

# Themes & Branding

Support:

- Organisation branding
- Logos
- Colours
- Fonts
- Dark mode
- Light mode
- Custom CSS (optional)

---

# Accessibility

Accessibility should include:

- WCAG compliance
- Keyboard navigation
- High contrast themes
- Screen reader support
- Adjustable font sizes
- Reduced motion options

---

# API

Every major feature should expose a versioned REST API.

Examples:

- Authentication
- Users
- Profiles
- Communities
- Pages
- Posts
- Comments
- Messages
- Events
- Notifications
- Media
- Federation

Suitable for:

- Mobile applications
- Desktop clients
- Community integrations
- Internal Liberu applications
- Third-party developers

---

# Future Modules

Potential future modules include:

- Voice calls
- Video conferencing
- Live streaming
- Podcasts
- Marketplace
- Classified adverts
- Jobs board
- Learning platform
- Digital asset management
- AI-assisted moderation
- AI content summaries
- AI translation
- End-to-end encrypted messaging
- ActivityPub interoperability
- Matrix messaging bridge
- Mobile applications
- Desktop applications
- Public developer SDKs

---

# Overall Goal

Liberu Social Network should provide a secure, modern and highly configurable decentralised social platform that enables organisations and communities to own their data while delivering a familiar and engaging social networking experience. By supporting both private and public deployments, optional federation, robust collaboration features and comprehensive APIs, it should serve as a flexible foundation for everything from internal communication platforms to large-scale public social communities.
```
