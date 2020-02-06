# MyMessages
![Alt text](MyMessagesNoMessages.png?raw=true "Screen Shot of My Messages Module with No (Course) Messages")

![Alt text](MyMessagesOneMessage.png?raw=true "Screen Shot of My Messages Module with One (Course) Message")

![Alt text](MyMessagesOneMessageAfterLinkClick.png?raw=true "Screen Shot with One (Course) Message after clicking link")

## Description
Creates a My Messages module at the course and organization level. It lists all courses with messages in the inbox and presents a direct link to the inbox within the appropriate course.

Recommend to uninstall all previous versions of My Messages before installing a newer version of My Messages.

The unm-unmmymessages-3800.4.war (version 2.4.3-3800.4) is the WAR file for Blackboard Learn SaaS 3800.4.0 (not 3800.x.0) only (Original Experience only).

My Messages (version 2.4.3-3800.4) rebuilt with 3800.4.0 Building Block APIs: Building Blocks API 3800.4.0

1. Using 3800.4.0 Blackboard APIs.

The unm-unmmymessages-3800.2.war (version 2.4.2-3800.2) is the WAR file for Blackboard Learn SaaS 3800.2.0 (not 3800.x.0) only (Original Experience only).

My Messages (version 2.4.2-3800.2) rebuilt with 3800.2.0 Building Block APIs: Building Blocks API 3800.2.0

1. Using 3800.2.0 Blackboard APIs.

The unm-unmmymessages-q4-2019.war (version 2.4.1-q4.2019) is the WAR file for Blackboard Learn SaaS 3800.0.0 (not 3800.x.0) and Q4 2019 (Original Experience only).

My Messages (version 2.4.1-q4.2018) rebuilt with Q4 2019 Building Block APIs: Building Blocks API 3800.0.0

1. Using Amazon Corretto 11 
2. Updates for SaaS and Q4 2019 (ex: JSP Precompilation)
3. Updated for known issue with Blackboard Maven Repository 

The unm-unmmymessages-q2-2019.war (version 2.3.3-q4.2018) is the WAR file for Blackboard Learn SaaS (3700.x), Q2 2019, Q4 2018, or Q2 2018 (Original Experience only).

My Messages (version 2.3.3-q4.2018) is not recommended for Q4 2019 and SaaS 3800 (or higher) since Q4 2019 and SaaS 3800 uses Amazon Corretto 11.   

My Messages B2 will NOT work in Ultra (since B2s that have a non-system admin UX will not work in Ultra).

The University of New Mexico is currently running unm-unmmymessages-q2-2019.war (version 2.3.3-q4.2018) on Blackboard Learn Q4 2018 CU6 (Self Hosted).

My Messages may work with SaaS (Original only), but believe this would best be done as a Custom B2 migration to LTI + REST API.

My Messages (version 2.3.3-q4.2018) rebuilt with Q4 2018 Building Block APIs: Building Blocks API 3500.0.0

My Messages (version 2.3.3-q4.2018) is a rebuild (with modifications) of Bruce Tenison's (OSCELOT Archive) MyMessages B2 - Thank You Bruce!

1. Using updated B2Context version 1.9.00 - GitHub - OSCELOT/bb-b2context: This package provides basic support functions for Building Blocks.

Thanks to Stephen Vickers https://github.com/OSCELOT/bb-b2context and OSCELOT https://oscelot.org/

2. Added Portuguese (Brazil) language, aka pt_BR, based on enhancement submission.

Thanks to Diego Roberto de Sousa for translation.

Please post your status with installing My Messages B2 on Q4 2019 with optional CUs (Self-Hosted or Managed Hosted):

https://community.blackboard.com/discuss/viewtopic/80/5449

Please post your status with installing My Messages B2 on SaaS 3800.4.0 only (Original Experience only):
https://community.blackboard.com/discuss/viewtopic/80/5601

Please post your status with installing My Messages B2 on SaaS 3800.2.0 only (Original Experience only):

https://community.blackboard.com/discuss/viewtopic/80/5497

Please post your status with installing My Messages B2 on SaaS 3800.0.0 only (Original Experience only):

https://community.blackboard.com/discuss/viewtopic/80/5448

If you are currently using Oscelot Messages (version 2.2.1 or prior) then you will need to uninstall Oscelot Messages in order to successfully install My Messages.

MyMessages is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
MyMessages is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

## Summary

|     |     |
| --- | --- |
| **Lead Developer(s)** | University of New Mexico Information Technologies http://it.unm.edu |
| **Development Status** | Production/Stable |
| **License** | GNU General Public License Version 3 (GPL-3.0)|
| **Programming Language** | Java |
| **Target Platforms** | Blackboard Learn SaaS 3800.2.0 (Original) only, Blackboard Learn SaaS 3800.0.0 (Original) only, SaaS 3700.x (Original), Q4 2019 with optional CUs (ex: 3800.0.0), Q2 2019 with optional CUs (ex: 3700.0.0), Q4 2018 with optional CUs (ex: 3500.0.0), or Q2 2018 with optional CUs (ex: 3400.0.0)|

## Documentation

As System Administrator: Communities->Tabs and Modules->Tabs

Top Frame Tab: My Institution

My Institution (at same level as Notifications Dashboard)->Default Content

My Messages - Check both Displayed and Required boxes -> Submit

My Institution - Should see My Messages tab in lower left hand corner with default text: Courses with Messages: You have no new unread messages!
