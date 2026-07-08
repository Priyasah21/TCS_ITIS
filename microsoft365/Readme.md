# Microsoft 365 Fundamentals

# Introduction to Microsoft 365

Microsoft 365 is a cloud-based subscription service provided by Microsoft that combines:

* Productivity Applications
* Cloud Services
* Collaboration Tools
* Security Features
* Device Management

It enables users to work from anywhere using the internet.

---

# What is Microsoft 365?

Microsoft 365 is a suite of cloud-based services and applications designed to improve productivity, communication, collaboration, and security.

It includes:

```text id="m365_1"
Applications
+
Cloud Services
+
Security
+
Device Management
```

---

# Why Was Microsoft 365 Created?

Organizations need:

* Remote Work Capability
* Cloud Storage
* Email Services
* Collaboration Tools
* Centralized User Management

Microsoft 365 provides all these services through a single platform.

---

# Office 365 vs Microsoft 365

This is one of the most common interview questions.

## Office 365

Primarily includes:

* Word
* Excel
* PowerPoint
* Outlook
* Exchange Online
* OneDrive
* Teams

Focus:

```text id="m365_2"
Productivity Applications
```

---

## Microsoft 365

Includes everything in Office 365 plus:

* Security Features
* Device Management
* Identity Management
* Advanced Compliance Tools

Focus:

```text id="m365_3"
Productivity + Security + Management
```

---

# Microsoft 365 Architecture

```text id="m365_4"
Microsoft 365
      |
------------------------------------------------
|       |        |        |        |            |
Outlook Teams OneDrive SharePoint Entra ID Security
```

All services work together in a single ecosystem.

---

# Core Components of Microsoft 365

## Microsoft Outlook

Used for:

* Email
* Calendar
* Contacts
* Scheduling

Common business communication platform.

---

## Microsoft Teams

Used for:

* Chat
* Meetings
* Video Calls
* Team Collaboration

Widely used for remote work.

---

## OneDrive

Cloud storage service.

Users can:

* Store files
* Access files remotely
* Share files securely

---

## SharePoint Online

Used for:

* Document Management
* Internal Portals
* Team Collaboration
* Knowledge Sharing

Often called the company's intranet platform.

---

## Exchange Online

Cloud-based email service.

Provides:

* Mailboxes
* Email Routing
* Calendars
* Contacts

Outlook uses Exchange Online in most organizations.

---

## Microsoft Entra ID

Formerly known as Azure Active Directory.

Provides:

* Authentication
* User Management
* Identity Management
* Single Sign-On (SSO)

---

# What is a Tenant?

One of the most important Microsoft 365 concepts.

A Tenant is a dedicated Microsoft 365 environment for an organization.

Example:

```text id="m365_5"
Company A
     ↓
company.onmicrosoft.com
```

Every organization gets its own tenant.

Think of a tenant as:

```text id="m365_6"
Company's Private Cloud Environment
```

---

# Tenant Characteristics

Contains:

* Users
* Groups
* Licenses
* Applications
* Policies

Everything belongs to a tenant.

---

# What is a Domain?

A domain is the organization's internet identity.

Example:

```text id="m365_7"
company.com
```

Users may receive email addresses like:

```text id="m365_8"
john@company.com
```

Domains are connected to the Microsoft 365 tenant.

---

# What is a User Account?

A user account represents an employee or individual.

Example:

```text id="m365_9"
Priya Sah
priya@company.com
```

User accounts allow access to Microsoft 365 services.

---

# What is a License?

A license determines which Microsoft 365 services a user can access.

Without a license:

Users may not be able to use:

* Outlook
* Teams
* OneDrive
* SharePoint

---

# Example

User:

```text id="m365_10"
John
```

Assigned:

```text id="m365_11"
Microsoft 365 Business Standard License
```

Now John can access services included in that plan.

---

# Why Licenses Matter

Licenses control:

* Features
* Storage Limits
* Security Features
* Application Access

---

# Common Microsoft 365 Plans

## Microsoft 365 Business Basic

Includes:

* Web Apps
* Teams
* Exchange Online
* OneDrive

---

## Microsoft 365 Business Standard

Includes:

* Desktop Applications
* Teams
* Outlook
* Exchange Online
* OneDrive

---

## Microsoft 365 Business Premium

Includes:

* Advanced Security
* Device Management
* Endpoint Protection

---

## Enterprise Plans

Examples:

* E1
* E3
* E5

Designed for larger organizations.

---

# What is Microsoft 365 Admin Center?

The Admin Center is the central management portal.

Administrators use it to:

* Create Users
* Delete Users
* Assign Licenses
* Reset Passwords
* Manage Services

Think of it as:

```text id="m365_12"
Control Panel of Microsoft 365
```

---

# Common Administrator Tasks

### Create New Users

Example:

```text id="m365_13"
new.employee@company.com
```

---

### Assign Licenses

Grant access to Microsoft 365 services.

---

### Reset Passwords

Common L1 support activity.

---

### Manage Groups

Control access and collaboration.

---

# Single Sign-On (SSO)

Allows users to sign in once and access multiple applications.

Example:

```text id="m365_14"
One Login
      ↓
Outlook
Teams
OneDrive
SharePoint
```

Benefits:

* Better User Experience
* Fewer Passwords
* Increased Productivity

---

# Benefits of Microsoft 365

## Cloud-Based

Access services from anywhere.

---

## Collaboration

Real-time teamwork.

---

## Security

Built-in protection features.

---

## Scalability

Supports small and large organizations.

---

## Automatic Updates

No manual software installation required.

---

# Real IT Support Scenarios

## Scenario 1

User cannot access Outlook.

Possible Causes:

* License Missing
* Password Issue
* Account Disabled

---

## Scenario 2

User cannot access Teams.

Check:

* License Assignment
* User Account Status

---

## Scenario 3

New employee joins company.

Tasks:

* Create User
* Assign License
* Provide Credentials

---

## Scenario 4

Employee forgot password.

Action:

* Reset Password from Admin Center

---

# Key Terms

| Term         | Meaning                                  |
| ------------ | ---------------------------------------- |
| Tenant       | Organization's Microsoft 365 Environment |
| License      | Access Rights to Services                |
| User Account | Individual Identity                      |
| Domain       | Organization's Internet Identity         |
| SSO          | Single Sign-On                           |
| Entra ID     | Identity Management Service              |

---

# Quick Revision

## Microsoft 365

Cloud productivity and security platform.

---

## Office 365

Productivity applications and services.

---

## Tenant

Dedicated environment for an organization.

---

## License

Determines service access.

---

## Admin Center

Used to manage users and services.

---

## Entra ID

Provides authentication and identity management.

---

# Most Asked TCS ITIS Questions

### What is Microsoft 365?

A cloud-based productivity, collaboration, and security platform.

---

### Difference between Office 365 and Microsoft 365?

Office 365 focuses on productivity tools; Microsoft 365 includes productivity, security, and management features.

---

### What is a Tenant?

A dedicated Microsoft 365 environment for an organization.

---

### What is a License?

A subscription that grants access to Microsoft 365 services.

---

### What is Microsoft Entra ID?

Microsoft's cloud identity and access management service.

---

### What is SSO?

Single Sign-On allows one login to access multiple applications.

---

### What is the Microsoft 365 Admin Center?

A portal used to manage users, licenses, and services.

---

### What are the main Microsoft 365 applications?

Outlook, Teams, OneDrive, SharePoint, and Exchange Online.



# Exchange Online & Outlook Administration

# Introduction to Exchange Online

**Exchange Online** is Microsoft's cloud-based email service that is part of Microsoft 365.

It provides:

* Business Email
* Calendars
* Contacts
* Shared Mailboxes
* Email Security
* Mail Flow Management

Think of Exchange Online as:

```text
Company Email System in the Cloud
```

---

# What is a Mailbox?

A mailbox is a storage location where emails, calendar items, contacts, and tasks are stored.

Every user with an Exchange Online license typically receives a mailbox.

Example:

```text
priya@company.com
```

Everything related to that email account is stored in the mailbox.

---

# Components of a Mailbox

A mailbox contains:

* Inbox
* Sent Items
* Drafts
* Deleted Items
* Calendar
* Contacts
* Notes
* Tasks

---

# Types of Mailboxes

## User Mailbox

Assigned to an individual user.

Example:

```text
john@company.com
```

Characteristics:

* Requires a license
* Has username and password
* Used by one person

---

## Shared Mailbox

Used by multiple users.

Example:

```text
support@company.com
hr@company.com
info@company.com
```

Characteristics:

* Multiple users can access it
* Usually does not require direct login
* Used for team communication

---

# User Mailbox vs Shared Mailbox

| User Mailbox    | Shared Mailbox                   |
| --------------- | -------------------------------- |
| Individual User | Multiple Users                   |
| Requires Login  | Access Granted to Users          |
| Personal Emails | Team Emails                      |
| Licensed        | Often No Direct License Required |

---

# Resource Mailbox

Used for booking resources.

Examples:

* Meeting Rooms
* Conference Halls
* Projectors

Example:

```text
meetingroom1@company.com
```

Employees can book resources using Outlook.

---

# What is an Email Address?

A unique identifier used to send and receive emails.

Example:

```text
priya@company.com
```

Structure:

```text
username@domain.com
```

---

# What is an Email Alias?

An additional email address linked to the same mailbox.

Example:

Mailbox:

```text
priya@company.com
```

Alias:

```text
priya.sah@company.com
```

Both emails arrive in the same mailbox.

---

# Benefits of Email Aliases

* Easier communication
* Multiple email identities
* No extra mailbox required

---

# Distribution Group

A group used to send emails to multiple users at once.

Example:

```text
allstaff@company.com
```

Instead of emailing 500 employees individually:

```text
Send Once
      ↓
Everyone Receives Email
```

---

# Advantages of Distribution Groups

* Faster communication
* Easier management
* Reduced manual effort

---

# Microsoft 365 Group

Provides:

* Shared Mailbox
* Shared Calendar
* Teams Integration
* SharePoint Integration

More advanced than a Distribution Group.

---

# Distribution Group vs Microsoft 365 Group

| Distribution Group   | Microsoft 365 Group    |
| -------------------- | ---------------------- |
| Email Distribution   | Collaboration Platform |
| No Shared Files      | Shared Files           |
| No Teams Integration | Teams Integration      |
| Email Focused        | Collaboration Focused  |

---

# Mail Flow

Mail Flow describes how emails travel from sender to receiver.

Example:

```text
Sender
   ↓
Exchange Online
   ↓
Internet
   ↓
Recipient
```

---

# Mail Flow Components

* Sender
* Exchange Server
* DNS
* Internet
* Recipient

---

# What Happens When an Email is Sent?

Step 1:

User composes email.

---

Step 2:

Outlook sends email to Exchange Online.

---

Step 3:

Exchange processes email.

---

Step 4:

Email delivered to recipient mailbox.

---

# Outlook

Outlook is Microsoft's email client.

Used for:

* Email
* Calendar
* Contacts
* Meetings

Works with Exchange Online.

---

# Outlook Features

* Email Management
* Meeting Scheduling
* Shared Mailboxes
* Contact Management
* Task Management

---

# Outlook Cached Mode

Stores mailbox data locally.

Benefits:

* Faster Performance
* Offline Access

Even without internet:

Users can read previously synchronized emails.

---

# Auto Reply (Out of Office)

Automatically responds when users are unavailable.

Example:

```text
I am currently on leave and will return on Monday.
```

Common business requirement.

---

# Mailbox Permissions

Administrators can grant permissions.

Common permissions:

## Full Access

Allows opening and managing mailbox content.

---

## Send As

Allows sending emails as another mailbox.

Example:

```text
support@company.com
```

Recipient sees:

```text
From: support@company.com
```

---

## Send on Behalf

Allows sending emails for another mailbox.

Example:

```text
From:
John on behalf of Support Team
```

---

# Mailbox Size Limits

Organizations often enforce mailbox quotas.

Purpose:

* Control storage usage
* Improve performance

Example:

```text
Mailbox Limit:
50 GB
```

---

# Common Outlook Issues

## Outlook Not Opening

Possible Causes:

* Corrupt Profile
* Add-in Issues
* Software Problems

---

## Cannot Send Emails

Check:

* Internet Connection
* Mailbox Status
* License Status
* Exchange Service Health

---

## Cannot Receive Emails

Check:

* Mailbox Storage
* Mail Flow Rules
* Email Filtering

---

## Outlook Keeps Asking for Password

Possible Causes:

* Incorrect Password
* Expired Password
* Authentication Issues

---

## Shared Mailbox Not Visible

Check:

* Permission Assignment
* Mailbox Access Rights

---

# Outlook Profile

Stores Outlook configuration settings.

Includes:

* Email Account
* Server Information
* Preferences

---

# Recreating Outlook Profile

Common troubleshooting step.

Used when:

* Outlook crashes
* Sync issues occur
* Login problems occur

---

# Email Security Basics

Exchange Online includes:

* Spam Filtering
* Malware Protection
* Email Threat Detection

Purpose:

Protect users from:

* Spam
* Phishing
* Malware

---

# Phishing Email

Fraudulent email designed to steal information.

Example:

```text
Your account will be suspended.
Click here immediately.
```

Users should verify before clicking.

---

# Real IT Support Scenarios

## Scenario 1

User cannot send emails.

Check:

* Internet Connectivity
* Mailbox Status
* Exchange Service Status

---

## Scenario 2

User cannot receive emails.

Check:

* Mailbox Quota
* Mail Flow Rules
* Spam Filtering

---

## Scenario 3

Shared Mailbox Missing.

Check:

* Permissions
* Group Membership

---

## Scenario 4

Outlook asks for password repeatedly.

Check:

* Credentials
* MFA Status
* Authentication Configuration

---

## Scenario 5

Mailbox Full.

Solution:

* Archive Emails
* Delete Unnecessary Messages
* Increase Mailbox Capacity

---

# Important Exchange Online Terms

| Term               | Meaning                  |
| ------------------ | ------------------------ |
| Mailbox            | Email Storage            |
| Alias              | Additional Email Address |
| Distribution Group | Email Distribution Group |
| Shared Mailbox     | Team Mailbox             |
| Mail Flow          | Email Delivery Process   |
| Outlook            | Email Client             |
| Quota              | Mailbox Storage Limit    |

---

# Quick Revision

## Exchange Online

Microsoft's cloud email platform.

---

## User Mailbox

Personal mailbox.

---

## Shared Mailbox

Accessible by multiple users.

---

## Alias

Additional email address for same mailbox.

---

## Distribution Group

Send one email to many users.

---

## Mail Flow

Journey of email from sender to receiver.

---

## Outlook

Microsoft email application.

---

## Auto Reply

Automatic out-of-office response.

---

# Most Asked TCS ITIS Questions

### What is Exchange Online?

Microsoft's cloud-based email service.

---

### What is a Shared Mailbox?

A mailbox that multiple users can access.

---

### Difference between User Mailbox and Shared Mailbox?

User Mailbox is personal; Shared Mailbox is used by teams.

---

### What is an Email Alias?

An additional email address linked to the same mailbox.

---

### What is a Distribution Group?

A group used to send emails to multiple users simultaneously.

---

### What is Mail Flow?

The process through which emails travel from sender to recipient.

---

### What is Outlook?

Microsoft's email and collaboration client.

---

### What would you check if a user cannot receive emails?

Mailbox quota, mail flow, spam filtering, and Exchange service health.

---

### What is Send As permission?

Allows sending emails as another mailbox.

---

### What is a mailbox quota?

A storage limit assigned to a mailbox.






# Microsoft Teams Administration & Troubleshooting – Part 1

# Introduction to Microsoft Teams

Microsoft Teams is a cloud-based collaboration and communication platform included in Microsoft 365.

It allows users to:

* Chat with colleagues
* Conduct audio/video meetings
* Share files
* Collaborate on documents
* Make calls
* Work remotely

Think of Teams as:

```text
Chat + Meetings + Calls + File Sharing + Collaboration
```

---

# Why Organizations Use Teams

Modern organizations need:

* Remote communication
* Real-time collaboration
* Secure file sharing
* Online meetings
* Team coordination

Microsoft Teams provides all these services in one platform.

---

# Benefits of Microsoft Teams

## Centralized Communication

Employees can communicate from a single application.

Instead of using:

* Email
* Separate Chat Apps
* Separate Meeting Tools

Everything is available inside Teams.

---

## Remote Work Support

Employees can work from:

* Home
* Office
* Client Locations

using internet connectivity.

---

## Real-Time Collaboration

Multiple users can edit files simultaneously.

Example:

```text
Priya edits file
John edits file
Aman edits file

At the same time
```

---

## Integration with Microsoft 365

Teams integrates with:

* Outlook
* OneDrive
* SharePoint
* Exchange Online
* Microsoft Entra ID

---

# Microsoft Teams Architecture

Teams depends on multiple Microsoft services.

```text
Microsoft Teams
      |
------------------------------------------------
|         |         |         |               |
Exchange OneDrive SharePoint Entra ID Microsoft 365
```

Each service provides different functionality.

---

# Teams and Exchange Online

Exchange Online provides:

* Calendar
* Meeting Scheduling
* Mailbox Integration

Without Exchange Online:

* Meeting scheduling may not work properly.

---

# Teams and OneDrive

OneDrive stores:

* Personal Files
* Chat Attachments

Example:

When you send a file in a chat, it is usually stored in OneDrive.

---

# Teams and SharePoint

SharePoint stores:

* Team Files
* Shared Documents
* Collaboration Content

Every Team usually has a SharePoint site.

---

# Teams and Entra ID

Microsoft Entra ID provides:

* Authentication
* User Identity
* Access Control
* Single Sign-On (SSO)

Users sign in to Teams using Entra ID credentials.

---

# Core Components of Microsoft Teams

## Teams

A Team is a group of people collaborating together.

Example:

```text
HR Team
IT Team
Finance Team
Development Team
```

---

## Channels

Channels organize conversations inside a Team.

Example:

```text
IT Team
   |
-------------------
|        |         |
General Projects Support
```

---

# Why Channels?

Channels help organize discussions.

Instead of one large chat:

* Projects in one channel
* Support in another
* Announcements in another

---

# Types of Channels

## Standard Channel

Visible to everyone in the Team.

Example:

```text
General
Announcements
```

All members can access.

---

## Private Channel

Accessible only to selected users.

Example:

```text
Management Discussion
```

Only invited members can view it.

---

## Shared Channel

Allows collaboration with people outside the Team.

Useful for:

* Cross-team collaboration
* Partner collaboration

---

# Teams vs Channels

| Team                | Channel                |
| ------------------- | ---------------------- |
| Collection of Users | Section inside Team    |
| Large Group         | Specific Topic         |
| Contains Channels   | Contains Conversations |

Example:

```text
Team:
IT Department

Channels:
General
Projects
Support
Training
```

---

# Chat in Teams

Used for direct communication.

Types:

### One-to-One Chat

Example:

```text
Priya ↔ Rahul
```

---

### Group Chat

Example:

```text
Priya
Rahul
Aman
Neha
```

All communicate together.

---

# Teams Meetings

Used for:

* Online Classes
* Business Meetings
* Interviews
* Team Discussions

Features:

* Video Calls
* Audio Calls
* Screen Sharing
* Recording

---

# Teams Calls

Allows users to:

* Make Voice Calls
* Make Video Calls

Can be:

* Internal Calls
* External Calls (if configured)

---

# File Sharing

Users can share:

* Documents
* PDFs
* Images
* Excel Sheets
* PowerPoint Presentations

Benefits:

* Centralized storage
* Easy collaboration

---

# Team Roles

## Team Owner

Highest permission level.

Responsibilities:

* Create Team
* Delete Team
* Add Members
* Remove Members
* Manage Settings

---

## Team Member

Regular user.

Can:

* Participate in chats
* Share files
* Attend meetings

Cannot perform administrative tasks.

---

## Guest User

External user.

Example:

```text
Vendor
Client
Partner Company Employee
```

Can collaborate with limited permissions.

---

# Guest Access

Allows external users to access Teams resources.

Benefits:

* Collaboration with clients
* Collaboration with vendors
* External communication

---

# Single Sign-On (SSO)

Users sign in once and access:

* Teams
* Outlook
* OneDrive
* SharePoint

without repeated logins.

---

# Security Features

Microsoft Teams supports:

* Multi-Factor Authentication (MFA)
* Conditional Access
* Data Encryption
* Compliance Policies

---

# Real IT Support Scenarios

## Scenario 1

User cannot sign in to Teams.

Possible Causes:

* Wrong Password
* Account Disabled
* MFA Issue
* License Issue

---

## Scenario 2

User cannot see a Team.

Check:

* Membership
* Permissions
* Team Visibility

---

## Scenario 3

User cannot access a Private Channel.

Check:

* Channel Membership

---

## Scenario 4

User cannot upload files.

Check:

* OneDrive
* SharePoint Permissions
* Storage Limits

---

## Scenario 5

User cannot chat with colleagues.

Check:

* Network Connectivity
* Teams Service Health
* User Account Status

---

# Advantages of Microsoft Teams

* Centralized Communication
* Remote Collaboration
* Secure File Sharing
* Meeting Management
* Microsoft 365 Integration
* Better Productivity

---

# Quick Revision

## Team

Group of users working together.

---

## Channel

Organized section inside a Team.

---

## Standard Channel

Visible to all members.

---

## Private Channel

Visible only to selected members.

---

## Shared Channel

Supports collaboration across teams.

---

## Owner

Manages Team settings and members.

---

## Member

Regular Team participant.

---

## Guest

External collaborator.

---

## SSO

One login for multiple Microsoft services.

---

# Most Asked TCS ITIS Questions

### What is Microsoft Teams?

A collaboration platform for chat, meetings, calls, and file sharing.

---

### Difference between Team and Channel?

A Team is a collection of users; a Channel is a discussion area inside a Team.

---

### What is a Private Channel?

A channel accessible only to selected members.

---

### What is Guest Access?

Allows external users to collaborate in Teams.

---

### What is the role of an Owner?

Managing members, permissions, and Team settings.

---

### Which Microsoft services integrate with Teams?

Exchange Online, OneDrive, SharePoint, and Entra ID.

---

### What is SSO?

Single Sign-On allows users to access multiple services using one login.

# Microsoft Teams Administration & Troubleshooting – Part 2

# Meetings, Calls, Collaboration & Troubleshooting

# Microsoft Teams Meetings

Meetings are one of the most widely used features in Microsoft Teams.

They allow users to:

* Communicate remotely
* Conduct interviews
* Organize training sessions
* Hold business discussions
* Collaborate in real time

---

# Types of Teams Meetings

## Scheduled Meeting

Created in advance and appears on participants' calendars.

Example:

```text id="tm1"
Team Meeting
Date: Monday
Time: 10:00 AM
```

Used for:

* Weekly Team Meetings
* Client Meetings
* Project Discussions

---

## Instant Meeting

Starts immediately without prior scheduling.

Example:

```text id="tm2"
Meet Now
```

Useful for quick discussions.

---

## Recurring Meeting

Meeting that repeats automatically.

Examples:

* Daily Standups
* Weekly Reviews
* Monthly Reports

---

# Scheduling a Meeting

Users can schedule meetings through:

* Microsoft Teams
* Microsoft Outlook

Process:

```text id="tm3"
Create Meeting
      ↓
Add Participants
      ↓
Select Date & Time
      ↓
Send Invitation
```

---

# Meeting Invitation

A meeting invitation contains:

* Meeting Link
* Date
* Time
* Meeting ID
* Agenda (optional)

---

# Joining a Meeting

Users can join using:

* Teams Application
* Web Browser
* Mobile App

Methods:

* Join Link
* Meeting ID
* Calendar Invitation

---

# Meeting Roles

## Organizer

Person who creates the meeting.

Responsibilities:

* Schedule Meeting
* Manage Participants
* Configure Meeting Options

---

## Presenter

Can:

* Share Screen
* Present Content
* Manage Meeting Activities

---

## Attendee

Can:

* Join Meeting
* Listen
* Participate in Chat

Limited administrative permissions.

---

# Meeting Features

## Audio Calling

Allows participants to communicate through voice.

Requirements:

* Microphone
* Speakers/Headphones

---

## Video Calling

Allows participants to use cameras during meetings.

Benefits:

* Better communication
* Improved engagement

---

## Chat During Meetings

Participants can exchange messages without interrupting the speaker.

Example:

```text id="tm4"
Please share the presentation.
```

---

# Screen Sharing

One of the most important Teams features.

Allows users to share:

* Entire Screen
* Specific Window
* PowerPoint Presentation
* Whiteboard

---

# Benefits of Screen Sharing

* Training
* Demonstrations
* Technical Support
* Presentations

---

# Microsoft Whiteboard

Collaborative digital workspace.

Used for:

* Brainstorming
* Diagrams
* Planning Sessions

---

# Meeting Recording

Teams allows recording meetings.

Recording captures:

* Audio
* Video
* Shared Content

Benefits:

* Training
* Documentation
* Future Reference

---

# Live Captions

Automatically displays spoken words as text.

Benefits:

* Accessibility
* Better Understanding
* Language Support

---

# Background Effects

Users can:

* Blur Background
* Use Virtual Backgrounds

Benefits:

* Privacy
* Professional Appearance

---

# Teams Calling

Microsoft Teams supports:

* Internal Calls
* External Calls (if configured)

---

# Types of Calls

## Voice Call

Audio only.

---

## Video Call

Audio + Video.

---

## Group Call

Multiple participants communicate together.

---

# Teams Status Indicators

Status helps users understand availability.

---

## Available

User is active and available.

---

## Busy

User is occupied.

---

## In a Meeting

User is attending a meeting.

---

## Do Not Disturb

Notifications are minimized.

---

## Away

User inactive for a period of time.

---

# File Collaboration in Teams

Files shared in Teams are usually stored in:

## OneDrive

Personal file sharing.

---

## SharePoint

Team file sharing.

---

# Co-Authoring

Multiple users can edit documents simultaneously.

Example:

```text id="tm5"
Priya edits document
Rahul edits document
Neha edits document

At the same time
```

---

# Microsoft Teams Policies

Policies control user behavior.

Examples:

* Meeting Policies
* Messaging Policies
* Calling Policies
* App Policies

Administrators manage policies.

---

# Common Teams Troubleshooting

## Teams Not Opening

Possible Causes:

* Corrupt Cache
* Application Issues
* Outdated Client

Solutions:

* Restart Teams
* Clear Cache
* Update Application

---

# User Cannot Sign In

Possible Causes:

* Incorrect Password
* Disabled Account
* License Issue
* MFA Problem

Check:

```text id="tm6"
User Account
License
MFA Status
```

---

# Teams Keeps Crashing

Possible Causes:

* Corrupt Installation
* Software Conflict
* Low System Resources

Solutions:

* Restart Device
* Update Teams
* Reinstall Teams

---

# Microphone Not Working

Possible Causes:

* Device Not Selected
* Permissions Disabled
* Hardware Problem

Check:

```text id="tm7"
Teams Audio Settings
Windows Microphone Settings
```

---

# Camera Not Working

Possible Causes:

* Camera Permission Denied
* Driver Issues
* Hardware Failure

Troubleshooting:

* Check Permissions
* Verify Device Manager
* Test Camera

---

# User Cannot Hear Others

Check:

* Speaker Volume
* Audio Device Selection
* Teams Settings

---

# User Cannot Be Heard

Check:

* Microphone Mute Status
* Device Permissions
* Audio Settings

---

# Screen Sharing Not Working

Possible Causes:

* Policy Restrictions
* Connectivity Issues
* Application Problems

Verify:

* User Permissions
* Teams Policies

---

# User Cannot Join Meeting

Possible Causes:

* Invalid Link
* Network Issue
* Meeting Restrictions

Check:

* Internet Connectivity
* Meeting Settings
* User Permissions

---

# Poor Call Quality

Common Causes:

* Weak Internet
* High Network Traffic
* Device Performance Issues

Symptoms:

* Voice Lag
* Video Lag
* Call Drops

---

# Teams Shows Offline

Possible Causes:

* Internet Issue
* Teams Service Issue
* Sign-in Problem

Verify:

* Network Connection
* Service Health
* Account Status

---

# Real IT Support Scenarios

## Scenario 1

User cannot join Teams.

Check:

* Account Status
* License Assignment
* MFA
* Internet Connectivity

---

## Scenario 2

User cannot see Team Files.

Check:

* SharePoint Permissions
* Team Membership

---

## Scenario 3

Meeting Recording Missing.

Check:

* OneDrive
* SharePoint
* Recording Permissions

---

## Scenario 4

User cannot share screen.

Check:

* Meeting Policy
* Teams Permissions

---

## Scenario 5

Teams displays "Trying to Connect."

Check:

* Internet Connection
* Firewall
* Microsoft Service Health

---

# Quick Revision

## Meeting Types

* Scheduled
* Instant
* Recurring

---

## Meeting Roles

* Organizer
* Presenter
* Attendee

---

## Teams Status

* Available
* Busy
* Away
* Do Not Disturb
* In Meeting

---

## Common Issues

* Sign-in Problems
* Audio Problems
* Video Problems
* Screen Sharing Issues
* Meeting Join Issues

---

## File Storage

OneDrive → Personal Files

SharePoint → Team Files

---

# Most Asked TCS ITIS Questions

### What are the different meeting roles in Teams?

Organizer, Presenter, and Attendee.

---

### What is screen sharing?

A feature that allows users to share their screen or applications during meetings.

---

### Where are Teams files stored?

OneDrive and SharePoint.

---

### What would you check if a user cannot sign in to Teams?

Account status, license assignment, MFA, and password.

---

### What would you check if microphone is not working?

Audio settings, permissions, and hardware.

---

### What causes poor call quality?

Weak internet connection, network congestion, or device performance issues.

---

### What should you check if a user cannot join a meeting?

Meeting link, permissions, and network connectivity.

---

### What is the purpose of Teams policies?

To control and manage user behavior and Teams features.


