<center><img src="https://add-sync.com/wp-content/uploads/2022/03/logo-dark.webp" alt="AddSync Manager" /> <br/><h1>AddSync Manager</h1></center>
# AddSync

**AddSync** is a tool for **real-time calendar synchronization** between Google Calendar, Office 365, Exchange, and iCalendar. Designed for teams, businesses, and individual users, AddSync keeps your calendars, tasks, and contacts fully synchronized across platforms.  

[Visit website](https://add-sync.com) | [Start Free Trial](https://dashboard.add-sync.com)

---

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [FAQ](#faq)
- [Security](#security)
- [License](#license)

---

## Installation

Clone the repository:

bash
git clone https://github.com/yourusername/addsync.git
npm install
npm start

## Usage
JavaScript
const AddSync = require('addsync');

// Connect Google Calendar and Outlook
AddSync.connect('Google Calendar', 'Outlook');

// Start synchronization
AddSync.sync();

Python
from addsync import AddSync

<code>syncer</code> = AddSync()
syncer.connect('Google Calendar', 'Outlook')
syncer.sync()

<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">source</span>:
  <span class="pl-ent">adapter</span>:
    <span class="pl-ent">type</span>: <span class="pl-s"><span class="pl-pds">"</span>outlook_http<span class="pl-pds">"</span></span>
    <span class="pl-ent">calendar</span>: <span class="pl-s"><span class="pl-pds">"</span>[base64-formatstring here]<span class="pl-pds">"</span></span>
    <span class="pl-ent">oAuth</span>:
      <span class="pl-ent">clientId</span>: <span class="pl-s"><span class="pl-pds">"</span>[UUID-format string here]<span class="pl-pds">"</span></span>
      <span class="pl-ent">tenantId</span>: <span class="pl-s"><span class="pl-pds">"</span>[UUID-format string here]<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="source:
  adapter:
    type: &quot;outlook_http&quot;
    calendar: &quot;[base64-formatstring here]&quot;
    oAuth:
      clientId: &quot;[UUID-format string here]&quot;
      tenantId: &quot;[UUID-format string here]&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>

## Configuration
<code>One-way sync:</code> Updates flow only from source to target calendar.<br/>
<code>Two-way sync:</code> Updates flow between all connected calendars.<br/>
<code>Tasks & Contacts:</code> Enable synchronization of tasks and contacts in addition to events.<br/>
<code>Notifications:</code> Optional email notifications for conflicts or updates.

## FAQ

What is AddSync?<br/>
AddSync is a real-time synchronization tool for calendars, tasks, and contacts between Google Calendar, Outlook, Exchange, and iCalendar.<br/>
How does AddSync work?<br/>
AddSync automatically syncs all connected calendars, ensuring updates in one calendar appear instantly in others.<br/>
Which calendars can I sync with AddSync?<br/>
Google Calendar, Office 365, Exchange, and iCalendar are fully supported.<br/>
Does AddSync sync in real-time?<br/>
Yes. AddSync synchronizes events and updates in real-time or near real-time to prevent scheduling conflicts.<br/>
Can I sync multiple accounts at once?<br/>
Yes. AddSync supports unlimited calendar connections across multiple accounts and platforms.<br/>
What is the difference between one-way and two-way synchronization?<br/>
One-way sync updates only the target calendar from the source. Two-way sync updates all connected calendars when changes are made in any calendar.<br/>
Can AddSync synchronize tasks and contacts?<br/>
Yes. Besides calendar events, AddSync synchronizes tasks and contacts to improve team and personal productivity.<br/>
Is AddSync secure?<br/>
Yes. AddSync uses advanced security measures and follows best practices to protect your data. Learn more.<br/>
How do I start using AddSync?<br/>
Create an account on the AddSync website, connect your calendars, set synchronization rules, and AddSync will start syncing automatically.<br/>
Does AddSync offer a free trial?<br/>
Yes. AddSync offers a 14-day free trial to test all features before subscribing. Start Free Trial

## Security

AddSync follows best practices for data protection, including encryption, access control, and secure API connections.

## License
MIT License
