---
layout: post
title: OEA June & July 2022 Newsletter
author: Author
description: In this newsletter, we share updates on new packages and incorporating data standards in OEA.
category: Newsletter
image: /assets/imgs/posts/img_jun_jul_2022_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems and tech partners, coordinated by Microsoft Education, collaborating to develop open source data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.  

- OEA Website: <a href="https://openeducationanalytics.org" target="_blank">https://openeducationanalytics.org </a>
- OEA GitHub Repository: <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">https://github.com/microsoft/OpenEduAnalytics</a>
- OEA Overview Video: <a href="https://www.youtube.com/watch?v=q6snp28bBQU&t=1s" target="_blank">OEA Overview on YouTube </a>

##### OEA Communities
Over 100 education systems and higher education institutions are now members of the Global OEA Community team, and they are participating in both global and regional 
OEA meetings. In upcoming OEA Community calls, we will discuss ideas for some significant changes to how these communities collaborate going forward. 
We look forward to participation from OEA Community members! 
 
In the June OEA Worldwide Community meeting, we heard from the <a href="https://www.mdek12.org/" target="_blank">Mississippi Department of Education </a>. Mississippi is working to develop and deliver a Student Information 
System that incorporates new approaches to data governance, data privacy, infrastructure, data management and security. Among a long list of enhancements and benefits 
this modernization effort is driving, the MDEK12 team anticipates this system will provide high-quality data in near real-time securely to educators while improving 
data transparency and reliability. This data modernization effort is similar to that taking place among large education systems like Georgia, Nebraska, Tennessee, 
South Australia, England, and Azerbaijan. During this call, we also had inputs from our partner in Africa, the African Institute of Mathematical Sciences, drawing 
parallels to some of the challenges that exist in the various ministries of education in Africa. 
 
The focus of the US OEA Community in the June call was higher ed, specifically a deep dive of Power BI use cases in Loma Linda University in Southern California like 
Institutional Peer Benchmarking, Enrollment Metrics and Accreditation. These Power BI reports have been published as Factbooks on their <a href="https://home.llu.edu/academics/office-of-provost/departments-and-divisions/educational-effectiveness/institutional-research" target="_blank">website </a> (N.B: only the reports on Institutional Peer Benchmarking are available to the public). 
  
In May, we welcomed Brazilian institutions to the OEA community with great discussions driven by our partner LEXP. With a quick start, 18 new members from 10 higher 
education institutions have joined the new Brazilian community for monthly discussions, discovery, and best practices sharing. The data journeys and challenges from 
UniCesumar, Unigranrio and ESPM are now available on-demand for everyone in the community. It has been a great opportunity to confirm institutions everywhere face 
similar challenges, and how they learn from and share with each other. 

As we learn from our community members, we're always looking for ways to help discover from and share with  peers around the world. We have made improvements to the OEA Community Team
to improve discoverability of resources and recordings. Please check out the Community Team for these updates!

##### Data Analytics and AI
In partnership with Fresno Unified School District in California and Kwantum Analytics, we have published a new <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/oea/packages/package_catalog/Digital_Equity_of_Access" target="_blank">OEA package </a> on Digital Equity of Access. While education
systems have invested massively in closing the digital access gap, there are still many student populations that do not have digital tools for learning outside of 
school. Those who do not have access continue to be disadvantaged in learning opportunities. 
 
This package shows patterns of digital access and identifies which students have no connected devices outside of schools, and the data enables education system leaders 
to allocate resources like devices and internet connectivity most efficiently so that all learners have digital access to learning. Using this package, multiple <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/oea/modules/module_catalog" target="_blank">OEA modules </a> can be combined, including Student Information System data from Ed-Fi, device assignment data from Microsoft Intune and internet connectivity data.
 
Common education data standards like Caliper, Ed-Fi and SIF allow for data solutions to be built on a common analytical data model and for a ‘plug and play’ approach 
to combining data from multiple sources. The new <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/oea/schemas" target="_blank">OEA data schema standardization </a> starts with the Caliper Analytics Specification to create a digital activity schema. 
This schema is currently being implemented in our existing modules and packages like the Digital Equity of Access and Chronic Absenteeism package, as well as future 
modules and packages. OEA Australia will publish a SIF schema to OEA GitHub in the next few weeks, and OEA US is developing an Ed-Fi based schema that will be published soon.  
 
Another addition to the OEA GitHub repository is the <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/oea/modules/module_catalog/Canvas_Data" target="_blank">Canvas module </a> which contains a set of assets for landing and transforming data from the Canvas Data v1 API. 
This module was developed and contributed by the Tasmania Department of Education, which is a strong member of the OEA Community. The module can support use cases 
like student/course engagement and assessment reporting. If you are interested in testing out this module in your live environment, 
please email OpenEduAnalyticsteam@microsoft.com. 

>
> ##### OEA Community Spotlight
>
>  As noted above, the pandemic aggravated inequalities in access to devices and internet connectivity, creating an opportunity for school systems to prioritize student digital access and inclusion more than ever before. Last month, Fresno Unified School District in California participated in the <a href="https://abc30.com/digital-inclusion-fresno-coalition-for-speed-of-broadband-all-virtual-town-hall-edison-high-school/12025685/" target="_blank">Solutions at the Speed of Broadband for All Townhall </a> as part of the Fresno Coalition for Digital Inclusion. This was an event for state and national leaders to work together to close the digital inclusion divide for families. 
>   
> Superintendent Jim Yovino, acknowledging how critical this is in his 32 school districts said: "If our kids in our Valley do not have access, the same equal access that every child in this Valley has, then they are behind". 
> 
> Fresno’s school district’s OEA-based data analytics solution on equity of digital access was highlighted at the event. The technical assets, documentation and instructions for setting this up in a school system’s environment are now available as the <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/oea/packages/package_catalog/Digital_Equity_of_Access" target="_blank">OEA package on Digital Equity of Access</a>.  

##### Data Engineering
This year’s <a href="https://web.cvent.com/event/1fa13152-c746-472f-a4c4-8e899e3222a5/summary" target="_blank">Learning Impact </a> conference, the largest annual conference for 1EdTech (<a href="https://www.imsglobal.org/article/ims-rebranding-1edtech-2022" target="_blank">formerly known as IMS Global </a>), was held in mid-June in Nashville and was well attended by representatives from the global edtech community. OEA principal architect was invited to present an overview of OEA in a recorded (and available on-demand) session, and he was also invited to participate in a panel discussion entitled “Great Data… From 3000 Apps.” In both sessions, he took the opportunity to highlight the accomplishments achieved to date within the OEA community, as well as the work in progress, and then some joint aspirations – 
especially within the context of education data standards and how they fit into the OEA framework (see standards at left in diagram): 

<div class="container-wrapper text-center">
   <img src="{{ site.baseurl }}/assets/imgs/posts/img_learning_impact_conference.png" class="img-fluid w-100" alt="" />
</div>
*Figure 1: OEA Presentation at the 1EdTech Learning Impact conference*

In the latter session, Emily Bell (CIO, Fulton County School System), Michael Evans (CTO, Forsyth County Schools), Patrick Porter (Director IT, Houston Independent School District), and Gene Garcia (Principal Architect, Microsoft) presented on the following theme: “Districts have adopted hundreds to thousands of teaching and learning apps. 
Most of them don’t have a way to collect, organize and analyze the data that is captured. This Fireside Chat creates an opportunity to initiate a dialogue about the 
collection and consumption of raw data to cross-reference engagement and usage data with formative and summative outcomes.” The discussion was well received by 
attendees and served as yet another validation of the importance of the work we’re all doing as part of the OEA effort. 

##### Plans for August/September
- Community Feedback on and Signup for OEA Working Groups 
- September: next OEA Global and Regional Community calls
- Announcements on OEA Program Updates
- Publishing SIF and Ed-Fi data standards modules in OEA GitHub

##### Product Support
For any Power BI question: 
- Post your question in general tab in <a href="https://aka.ms/pbicat " target="_blank">https://aka.ms/pbicat</a> 
- Contact your local expert (PBI 50) who knows how to engage the :<a href="https://aka.ms/pbicat</a>  https://microsoft.sharepoint.com/teams/PBICATPortal/SitePages/Marquee.aspx?historyId=7BAF2FC2-4543-493C-AFD2-AD4E0B5FC64E&contentId=91DD67E2-07DE-4E4C-B73E-37986385CC2C" target="_blank"> PBI product group</a> 
 
For any Synapse question, you can post a question on this <a href="https://teams.microsoft.com/_?tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47#/l/team/19:UgZ55PTYhXk7xj7T2luIBIuSJcy6RzWlm2fbfx4VSZ01@thread.tacv2/conversations?groupId=c89b27d7-91c1-4cc7-aa61-c6633c2e3904&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47&deeplinkId=06305baa-bf49-4071-b43f-9433c36462c6
" target="_blank">Team </a>  site or make a request to the Azure CSE team by submitting a nomination <a href="https://microsoft.sharepoint.com/teams/SynapseCSE/SitePages/Engage-Azure-Synapse-CSE.aspx" target="_blank">here </a>.
