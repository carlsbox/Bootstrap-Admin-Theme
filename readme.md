This branch is looking at taking designs and porting them to a Nodejs based app.


OpenHIM Web-UI Admin Theme 
==========================

A test bed for exploring a new interface and design for the HIM Web UI that will address some of the administrative needs of the tool.

Some key features that this interface will need to address:
- List and Display active 'channels' on the HIM
- List and administer all 'system' users of the HIM (i.e. applications that have access to the HIM channels)
- List and display the 'monitoring aspects' of the HIM:
-- Number of messages per channel etc

The interface is forked from a generic admin theme built with Bootstrap free for both personal and commercial use. 

This is still a work in progress and will begin to focus itself on a Web ADMIN UI for the OpenHIM.

HIM-Monitor App Site Map
========================

- Login
- Home Page (index) - Dashboard
- Channel List - List of all channels with links to channel details
-- Channel Detail page
-- Add / Remove / Edit Channel Page * 
- System Users (PoCs) - list of all registered system users
-- User Detail Pages
-- Add / Remove / Edit User Page * 
- Transaction Log
-- Log per Channel
-- Log per message type (Success / Error)
--- Ability to edit messages **
- Admin / Settings -- Area for admin users to administer the settings of the HIM Monitor App *
-- Add Users / User Administration
-- Edit Notification Settings
- Profile
-- User Profile
-- Change password etc

* Only accessable to Admin users
** only available to HIM Maintenance Users


HIM Monitor App User types
==========================
- Super User / Root
-- Created manually and only one per systems
-- All rights within the system
- Admin
-- Can create users | full user management
-- full access to all system
-- Create and maintain channels
-- Create and maintain system users
- Maintenance
-- Access to monitoring dashboard and error consol
-- can't add new users or systems or channels
- System
-- has rights to submit to the system

Existing Pages to be used for referecne:

- Login
- Admin Dashboard (Tables, Statistics, Chart, Media Gallery)
- Full Calendar (Viewing calendar, adding events, dragging events)
- Statistics & Charts (Multiple examples of Pie, Bar, Line charts using Morris.js, knob.js, jquery flot, easypiechart)
- Buttons & Icons
- WYSIWYG & HTML 5 Editors
- Forms & Wizard
- Tables & Bootstrap dataTables
- UI & Interface Elements (Modals, Popovers, Tooltips, Alerts, Notifications, Labels, Progress Bars)

The Working demo page:
http://carlsbox.github.io/HIM-Admin-Theme-bootstrap/


License
===============
The MIT License (MIT)

Copyright (c) 2013 - Vincent Gabriel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
