# MyMessages
![Alt text](MyMessagesNoMessages.png?raw=true "Screen Shot of My Messages Module with No (Course) Messages")

![Alt text](MyMessagesOneMessage.png?raw=true "Screen Shot of My Messages Module with One (Course) Message")

![Alt text](MyMessagesOneMessageAfterLinkClick.png?raw=true "Screen Shot with One (Course) Message after clicking link")

## Description
Creates a My Messages module at the course and organization level. It lists all courses with messages in the inbox and presents a direct link to the inbox within the appropriate course.

The unm-unmmymessages-q2-2019.war (version 2.3.3-q4.2018) is the WAR file for Blackboard Learn SaaS, Q2 2019, Q4 2018, or Q2 2018 (Original Experience only).

Recommend to upgrade your existing My Messages to version 2.3.3-q4.2018 as soon as practical since My Messages version 2.3.1-q4.2017 will be deprecated effective November 27, 2019 because Q4 2017 is not supported as of December 2019.

For Q4 2017 My Messages version 2.3.3-q4.2018 will not install (requires at least Q2 2018 Learn Release).

For Q4 2017 use My Messages unm-unmmymessages2017.war (version 2.3.1-q4.2017) until upgrade Learn Release to at least Q2 2018.

My Messages (version 2.3.3-q4.2018) is not recommended for Q4 2019 since Q4 2019 is planned to use Amazon Corretto 11.  Plan to post another My Messages version for Q4 2019 about December 2019.

My Messages B2 will NOT work in Ultra (since B2s that have a non-system admin UX will not work in Ultra).

The University of New Mexico is currently running unm-unmmymessages-q2-2019.war (version 2.3.3-q4.2018) on Blackboard Learn Q4 2018 CU6 (Self Hosted).

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q2 2019 CU2 Developer Virtual Machine (DVM).

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q2 2019 CU1 Developer Virtual Machine (DVM).

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q2 2019 Developer Virtual Machine (DVM).

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q4 2018 CU7 DVM.

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q4 2018 CU6.

The University of New Mexico has successfully installed and tested unm-unmmymessages-q2-2019.war on BlackBoard Learn Q4 2018 CU5.

My Messages may work with SaaS, but believe this would best be done as a Custom B2 migration to LTI + REST API.

My Messages (version 2.3.3-q4.2018) is a rebuild (with modifications) of Bruce Tenison's (OSCELOT Archive) MyMessages B2 - Thank You Bruce!

My Messages (version 2.3.3-q4.2018) rebuilt with Q4 2018 Building Block APIs: Building Blocks API 3500.0.0

1. Using updated B2Context version 1.9.00 - GitHub - OSCELOT/bb-b2context: This package provides basic support functions for Building Blocks.

Thanks to Stephen Vickers https://github.com/OSCELOT/bb-b2context and OSCELOT https://oscelot.org/

2. Added Portuguese (Brazil) language, aka pt_BR, based on enhancement submission.

Thanks to Diego Roberto de Sousa for translation.

Supplemental Information: https://community.blackboard.com/ideas/2949-my-messages

Please post your status with installing My Messages B2 on Q2 2019 with optional CUs (Self-Hosted or Managed Hosted):

https://community.blackboard.com/message/29581-my-messages-b2-for-q2-2019

Please post your status with installing My Messages B2 on Q4 2018 with optional CUs (Self-Hosted or Managed Hosted):

https://community.blackboard.com/message/26281-my-messages-b2-for-q4-2018

Please post your status with installing My Messages B2 on Q2 2018 with optional CUs (Self-Hosted or Managed Hosted):

https://community.blackboard.com/thread/6664-my-messages-b2-for-q2-2018

Please post your status with installing My Messages B2 on Q4 2017 with optional CUs (Self-Hosted or Managed Hosted):

https://community.blackboard.com/thread/6412-mymessages-b2-war-file-for-q4-2017-posted-on-oscelot 

Please post your status with installing My Messages B2 on SaaS (Original Experience only):

https://community.blackboard.com/thread/7587-my-messages-b2-for-saas-including-plans-to-move-to-java-11-original-experience

The unm-unmmymessages.war (version 2.3.0-q4.2016) is deprecated effective December 1, 2018 since Blackboard Learn Q4 2016 is not supported as of December 2018.

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
| **Target Platforms** | Blackboard Learn Q2 2019 with optional CUs (ex: 3700.0.0), Q4 2018 with optional CUs (ex: 3500.0.0), or Q2 2018 with optional CUs (ex: 3400.0.0)|

## Documentation

As System Administrator: Communities->Tabs and Modules->Tabs

Top Frame Tab: My Institution

My Institution (at same level as Notifications Dashboard)->Default Content

My Messages - Check both Displayed and Required boxes -> Submit

My Institution - Should see My Messages tab in lower left hand corner with default text: Courses with Messages: You have no new unread messages!
