# MyMessages
![Alt text](MyMessages_NoMessages.png?raw=true "Screen Shot of My Messages Module with No (Course) Messages")

![Alt text](MyMessages_OneMessage.png?raw=true "Screen Shot of My Messages Module with One (Course) Message")

![Alt text](MyMessages_OneMessage_AfterLinkClick.png?raw=true "Screen Shot with One (Course) Message after clicking link")

## Description
Creates a My Messages module at the course and organization level. It lists all courses with messages in the inbox and presents a direct link to the inbox within the appropriate course.

Bruce Tenison gave written permission to update - Thank You Bruce!

The unm-unmmymessages2017.war (version 2.3.1-q4.2017) is the WAR file for Blackboard Learn (Original Experience only).

My Messages B2 will NOT work in Ultra (since B2s that have a non-system admin UX will not work in Ultra).

The University of New Mexico is currently running unm-unmmymessages2017.war on Blackboard Learn Q4 2017 CU2 (Self Hosted).  

The University of New Mexico has also successfully installed and tested unm-unmmymessages2017.war on BlackBoard Learn Q2 2018 Developer Virtual Machine (DVM).

My Messages may work with SaaS, but UNM is not maintaining My Messages with SaaS due to limited UNM resources since believe this would best be done as a Custom B2 migration to LTI + REST API.

Please post your status with installing My Messages B2 on Q4 2018 with optional CUs (Self-Hosted, Managed Hosted, or SaaS):

https://community.blackboard.com/message/26281-my-messages-b2-for-q4-2018

Please post your status with installing My Messages B2 on Q2 2018 with optional CUs (Self-Hosted, Managed Hosted, or SaaS):

https://community.blackboard.com/thread/6664-my-messages-b2-for-q2-2018

Please post your status with installing My Messages B2 on Q4 2017 with optional CUs (Self-Hosted, Managed Hosted, or SaaS):

https://community.blackboard.com/thread/6412-mymessages-b2-war-file-for-q4-2017-posted-on-oscelot 

The unm-unmmymessages.war (version 2.3.0-q4.2016) is deprecated effective December 1, 2018 since Blackboard Learn Q4 2016 is not supported as of December 2018.

If you are currently using Oscelot Messages (version 2.2.1 or prior) then you will need to uninstall Oscelot Messages in order to successfully install My Messages.

MyMessages is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
MyMessages is distributed in the hope that it will be useful,but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

## Summary

|     |     |
| --- | --- |
| **Lead Developer(s)** | University of New Mexico Information Technologies http://it.unm.edu |
| **Development Status** | Production/Stable |
| **License** | GNU General Public License Version 3 (GPL-3.0)|
| **Programming Language** | Java |
| **Target Platforms** | Blackboard Learn Q4 2018 with optional CUs (ex: 3500.0.0), Q2 2018 with optional CUs(ex: 3400.0.0), or Q4 2017 with optional CUs (ex: 3300.0.0) |

## Documentation

As System Administrator: Communities->Tabs and Modules->Tabs

Top Frame Tab: My Institution

My Institution->Default Content

My Messages - Check both Displayed and Required boxes -> Submit

My Institution - Should see My Messages tab in lower left hand corner with default text: Courses with Messages: You have no new unread messages!
