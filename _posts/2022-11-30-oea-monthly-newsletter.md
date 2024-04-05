---
layout: post
title: OEA October & November 2022 Newsletter
author: Author
description: In this newsletter, we share updates on OEA Working Groups and v0.7 release of the OEA framework.
category: Newsletter
image: /assets/imgs/posts/img_oct_nov_2022_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems and tech partners, coordinated by Microsoft Education, collaborating to develop open source data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.  

- OEA GitHub Repository: <a href="https://github.com/OpenEducationAnalytics/OpenEduAnalytics" target="_blank">https://github.com/OpenEducationAnalytics/OpenEduAnalytics</a>
- OEA Website: <a href="https://openeducationanalytics.org" target="_blank">https://openeducationanalytics.org </a>
- OEA YouTube Chanel: <a href="https://www.youtube.com/channel/UCojAPdH6vmb395HWP_2yUXg" target="_blank">aka.ms/OEAyoutube </a>
- 5-min OEA Intro Video: <a href="https://www.youtube.com/watch?v=E0kmtQKRzTc" target="_blank">Using Data Analytics and AI to transform Education </a>

##### OEA Working Groups' Progress
Over 50 OEA members have joined the 4 OEA Working Groups announced in September. Each collaboration is underway with progress to be discussed in the OEA meetings in the coming weeks. By way of summary: 

**360 Learner Progress:** this working group developed a shared conceptual framework of 3 types of analytical models that would help personalize the learner experience: student success models that look across all elements of student engagement; academic success models that look at student progress across all academic courses; and future success models that look at skill development towards specific types of careers or job roles. A few members of the working group are implementing the OEA Framework and will collaborate to build key modules, a shared data model, and ultimately an OEA Package for 360 Learner Progress in 2023. 

**Learning Analytics:** this working group is focused on analytics to support faculty and teachers in understanding their class dynamics. The collaboration 
is off to a fantastic start. Through discussions, the group has defined the overall goal: to help educators understand if students are actually engaged and 
learning in classes. Learning Analytics represents the right technology and the right data sources to empower educators to: 1) Support student well-being, 
freeing students to engage and learn; 2) Find better ways to encourage students to participate, meeting them where they are, and bridge generational gaps between educators and learners; 3) Develop a healthy and engaging learning environment and optimize learning resources to design the best paths towards students’ learning outcomes. 
 
**Education System Reporting:** In this working group kick-off meeting, the Helsinki Division of Education shared their analytics on modeling 
student well-being and Fresno Unified School District shared their work on reporting on digital equity. A big thank you to them for sharing 
excellent examples of data and AI use cases! The group discussed the need to leverage data from other government agencies, such as social services, to get a more layered picture of learning patterns in their systems. Also discussed were how open-source collaborations like OEA can accelerate through using common datasets (like IPEDS in the US) and through using data standards such as Ed-Fi, CEDS, and SIF. OEA has already developed some of these elements that support education reporting through OEA Modules on <a href="https://github.com/OpenEducationAnalytics/OpenEduAnalytics/tree/main/modules/module_catalog/IPEDS" target="_blank">IPEDS </a>, Ed-FI (to be released soon), and <a href="https://github.com/OpenEducationAnalytics/OpenEduAnalytics/tree/main/modules/module_catalog/SIF" target="_blank">SIF</a>. These will form the foundation of an Education Reporting Package that this group will develop in 
2023.
 
**Skills-Based Course Design:** This working group has completed a research project to understand the process and needs of course design or syllabus development. There is strong agreement that simplifying the course development process and enabling metadata about instructional design and learning resources to be used for analytics is urgently needed. Also, this project will help course designers map course learning outcomes to the LinkedIn Skills taxonomy so that students can better describe the skills they are developing in the same language that job recruiters use. There is work already underway to build a proof-of-concept app using PowerApps to test out concepts and workflows with a small group of universities. 

Please fill out <a href="https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR8N9dofOqa1PobxBN5c5ZxtUQlozU1hPVE1LQlg3WlJETEpGTFVROVFERi4u" target="_blank">OEA Community - Working Groups Survey </a> if you are interested to participate in the working groups.  

##### Data Engineering
Exciting news! <a href="https://github.com/OpenEducationAnalytics/OpenEduAnalytics/releases/tag/v0.7" target="_blank">Version 0.7 </a> of the OEA framework is now available for setup in production and test environments. This new version makes it faster and easier to set up an Azure Synapse environment for data and AI.

This release includes major changes to the data lake structure as well as the OEA API:  

- completely revised data lake structure including a revised folder structure that aligns with the <a href="https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/best-practices/data-lake-zones" target="_blank">latest recommendations from Cloud-scale analytics </a>   
- introduction of “land,” “ingest,” and “refine” methods in OEA to simplify the process of working with new data sources to align with the reference architecture  
- easily switch data lake contexts through use of oea.set_workspace, allowing for development to occur in lakehouse “sandboxes”  
- extended use of OEA metadata format  
- ability to convert swagger into OEA metadata  
- updated provisioning of Spark cluster to use Spark v3.2 (instead of 3.1).This also updates Delta Lake to v1.2 (from 1.0)  

Version 0.7 of the framework is a significant milestone in the maturation of the OEA framework development and release cycle. This release also makes it possible to adopt a more rigorous release cycle and dependency management for OEA components (i.e., modules, packages, and schemas). This version is one step further on the path towards framework maturity to get to a v1.0 release. Stay tuned for coming information on features and expected release date for v0.8. 

In early November the Ed-Fi Alliance hosted the <a href="https://www.ed-fi.org/event/summit-2022/" target="_blank">Ed-Fi Summit 2022 </a> in Austin, Texas. This annual conference connects US state and local education leaders in K12, ed-tech providers, educators, and technical experts who are using data to solve education’s most entrenched problems. At the Summit, Gene Garcia (OEA Principal Architect, Microsoft) presented a session titled “Data Validation that Scales” in which he walked through the lakehouse architecture centered on OEA and how this approach is utilized by <a href="https://www.edgraph.com/" target="_blank">EdGraph </a> to provide critical data validation at multiple levels. The 100+ attendees of the session demonstrated their interest by staying for the Q&A session immediately following the session – making it clear that data validation remains a significant challenge and key scenario to be addressed through the use of a lakehouse architecture. The recorded audio of the session and the slide deck from the session are available here: 
<a href="https://events.bizzabo.com/summit22/agenda/session/932235" target="_blank">Data Validation that Scales </a>. An update to the Ed-Fi OEA module will be released in the coming days.  

##### Data Analytics & AI
To comply with <a href="https://www.microsoft.com/en-us/ai/our-approach?activetab=pivot1%3aprimaryr5" target="_blank">Microsoft’s Responsible AI Principles </a>, all OEA packages that involve machine learning models are going through the Responsible AI Impact Assessment Review with the Microsoft Office of Responsible AI. Last month, the OEA <a href="https://github.com/OpenEducationAnalytics/OpenEduAnalytics/tree/main/packages/package_catalog/Predicting_Chronic_Absenteeism" target="_blank"> Predicting Chronic Absenteeism package </a> was reviewed and has been approved. We presented the package use case and our approach to model building, addressed how Microsoft’s Responsible AI principles were operationalized, and answered questions by the panel. Considering how critical Responsible AI is to our work, the OEA team is planning a series of trainings for OEA communities to share Responsible AI best practices that should be applied to data and AI projects. We have also started work on integrating Microsoft’s Responsible AI toolkit into OEA packages. 

>
> ##### OEA Community Spotlight
>
>  In October, the OEA Australia Community hosted a deep dive session on Designing Effective Power BI Reports with more than 100 community members joining, the highest record in an OEA Community meeting so far! 
>   
> Chris Hamill from the Power BI Team shared the process of designing and delivering compelling, engaging, and intuitive Power BI reports that are easy to understand. The process comprises phases to understand the report users and their requirements, explore report designs, and develop production ready reports. 
> 
> Chris also shared several examples of Power BI designs while highlighting good and bad practices in each. If interested, take the interactive Microsoft Learn learning path on designing effective Power BI reports <a href="https://learn.microsoft.com/en-us/training/paths/power-bi-effective/" target="_blank"> here</a>.  

##### Product Support
For any Power BI question: 
- Post your question in general tab in <a href="https://aka.ms/pbicat " target="_blank">https://aka.ms/pbicat</a> 
- Contact your local expert (PBI 50) who knows how to engage the <a href="https://microsoft.sharepoint.com/teams/PBICATPortal/SitePages/Marquee.aspx?historyId=7BAF2FC2-4543-493C-AFD2-AD4E0B5FC64E&contentId=91DD67E2-07DE-4E4C-B73E-37986385CC2C" target="_blank"> PBI product group</a> 
 
For any Synapse question, you can post a question on this <a href="https://teams.microsoft.com/_?tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47#/l/team/19:UgZ55PTYhXk7xj7T2luIBIuSJcy6RzWlm2fbfx4VSZ01@thread.tacv2/conversations?groupId=c89b27d7-91c1-4cc7-aa61-c6633c2e3904&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47&deeplinkId=06305baa-bf49-4071-b43f-9433c36462c6
" target="_blank">Team </a>  site or make a request to the Azure CSE team by submitting a nomination <a href="https://microsoft.sharepoint.com/teams/SynapseCSE/SitePages/Engage-Azure-Synapse-CSE.aspx" target="_blank">here</a>.
