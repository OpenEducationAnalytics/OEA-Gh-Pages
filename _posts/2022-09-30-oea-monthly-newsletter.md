---
layout: post
title: OEA August & September 2022 Newsletter
author: Author
description: In this newsletter, we share updates on the launch of OEA Community Working Groups and the Dataverse Education Accelerator.
category: Newsletter
image: /assets/imgs/posts/img_aug_sep_2022_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems and tech partners, coordinated by Microsoft Education, collaborating to develop open source data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.  

- OEA GitHub Repository: <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">https://github.com/microsoft/OpenEduAnalytics</a>
- OEA Website: <a href="https://openeducationanalytics.org" target="_blank">https://openeducationanalytics.org </a>
- OEA YouTube Chanel: <a href="https://www.youtube.com/channel/UCojAPdH6vmb395HWP_2yUXg" target="_blank">aka.ms/OEAyoutube </a>
- 5-min OEA Intro Video: <a href="https://www.youtube.com/watch?v=E0kmtQKRzTc" target="_blank">Using Data Analytics and AI to transform Education </a>

##### OEA Working Groups
OEA Customer Communities and Partners are expanding into more targeted working groups, with each working group focused on a specific use case category. This will create more momentum behind community generated open-source contributions and will provide a group of peer organizations to collaborate with on projects of common interest. 

The 4 OEA Working Groups are:

1.	**360 Learner Progress View – Student Level Insights:** This use case combines key education data sources to provide a more comprehensive view of each student across academics, engagement, well-being, and career skills factors that can help educators support every student. This use case could be extended in several areas including Personalized Learning Paths, Student Success and Risk Predictive Models, and Learner Records.
2.	**Learning Analytics – Class/Course Level Insights:** This use case combines data primarily from students' digital learning activities (e.g., LMS, Teams, O365, digital content) for class or course level analytics. It is expected that the key data source for this working group will be Education Insights, which will provide data on Reading Progress, Teams Meetings, and Assignments.
3.	**Institution, District, State, and National Education Reporting – System Level Insights:** This use case focuses on setting up modern data services across an education system to bring together many data sources, using process automation tools to collect data more efficiently from schools, allowing for data validation as necessary, and setting up configurable workflows to enable actions based on data.  
4.	**Skills-based Course Design:** This use case creates an educator workflow that collects data about the content used and skills targeted in a course or class (based on syllabus or course outline). Data from that workflow can then be machine readable and be used to track progress towards career skills, understand content impact, and ultimately progress towards degrees or other learning outcomes.

Registration for Working Groups is still open. If you as an OEA community member are interested in joining, fill out <a href="https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR8N9dofOqa1PobxBN5c5ZxtUQlozU1hPVE1LQlg3WlJETEpGTFVROVFERi4u" target="_blank">this form </a>.

##### Dataverse Education Accelerator joins the OEA Program
We are thrilled to welcome the <a href="https://learn.microsoft.com/en-us/dynamics365/industry/accelerators/edu-overview" target="_blank">Dataverse Education Accelerator</a> to the OEA Program. This partnership allows us to expand the umbrella of OEA to not just include the Azure based data and analytics platforms, but also the D365 and Power Apps platforms, which are key cross-platform benefits for Microsoft customers. We are already seeing OEA customers like the Georgia Department of Education, Fresno Unified School District, and Tasmania Department of Education using a combination of these platforms to enable the digital transformation of their entire system, so this partnership is a natural extension to the program. 

For technical implementation, we considered ways to structure the Dataverse Education Accelerator to work from both data provider and data consumer scenarios. From a data provider standpoint, Dataverse has a feature called <a href="https://learn.microsoft.com/en-us/power-apps/maker/data-platform/azure-synapse-link-synapse" target="_blank">Synapse Link</a> to bring in near-real time data from custom apps, and then make the data available for analysis in Power BI reports or machine learning models. From a data consumer standpoint, Dataverse can push the insights back to D365 or custom apps through automated workflows.

<div class="container-wrapper text-center">
   <img src="{{ site.baseurl }}/assets/imgs/posts/img_welcoming_dataverse.png" class="img-fluid w-100" alt="" />
</div>
*Figure 1: Welcoming Dataverse to OEA*

##### Data Analytics and AI
To make OEA technical assets applicable across different use cases in Azure Synapse environments, we created a first <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/schemas" target="_blank">OEA schema</a> to standardize education digital activity data. This “Plug and Play” approach with the <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/schemas/schema_catalog/Digital_Engagement_Schema" target="_blank">OEA Digital Engagement Schema</a> transforms any digital engagement data (such as Microsoft Education Insights or Clever data) into a single table aligned to the Caliper data standard. When OEA assets are built on this schema table (rather than the original data source), these assets can then be used in any OEA Synapse environment which also utilizes OEA schemas. 
We have recently revised our existing modules (<a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/module_catalog/Microsoft_Education_Insights" target="_blank">Microsoft Education Insights</a> and <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/module_catalog/Clever" target="_blank">Clever</a>), and packages (<a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/packages/package_catalog/Digital_Equity_of_Access" target="_blank">Digital Equity of Access</a> and <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/packages/package_catalog/Predicting_Chronic_Absenteeism" target="_blank">Predicting Chronic Absenteeism</a>) to take advantage of this new Plug and Play approach. Please test them out and share your feedback!


##### Data Engineering
Refining our approach to OEA, we have distilled the OEA framework down to the core pillars where the foundation is Azure Synapse Analytics and Power BI, and the 5 key steps we are facilitating with OEA are to **collect**, **ingest** and **analyze** data, **publish** insights, and **inform** stakeholders.

<div class="container-wrapper text-center">
   <img src="{{ site.baseurl }}/assets/imgs/posts/img_refined_technical_approach.png" class="img-fluid w-100" alt="" />
</div>
*Figure 2: Refined technical approach to OEA*

In line with these steps, there has been a restructuring of the <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">OEA GitHub repository</a> to include 4 key elements to the OEA reference architecture: framework, modules, schemas, and packages. 


##### Plans for October/November
- Working Group Kickoff Meetings
- Regional OEA Community Meetings

##### Product Support
For any Power BI question: 
- Post your question in general tab in <a href="https://aka.ms/pbicat " target="_blank">https://aka.ms/pbicat</a> 
- Contact your local expert (PBI 50) who knows how to engage the <a href="https://microsoft.sharepoint.com/teams/PBICATPortal/SitePages/Marquee.aspx?historyId=7BAF2FC2-4543-493C-AFD2-AD4E0B5FC64E&contentId=91DD67E2-07DE-4E4C-B73E-37986385CC2C" target="_blank"> PBI product group</a> 
 
For any Synapse question, you can post a question on this <a href="https://teams.microsoft.com/_?tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47#/l/team/19:UgZ55PTYhXk7xj7T2luIBIuSJcy6RzWlm2fbfx4VSZ01@thread.tacv2/conversations?groupId=c89b27d7-91c1-4cc7-aa61-c6633c2e3904&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47&deeplinkId=06305baa-bf49-4071-b43f-9433c36462c6
" target="_blank">Team </a>  site or make a request to the Azure CSE team by submitting a nomination <a href="https://microsoft.sharepoint.com/teams/SynapseCSE/SitePages/Engage-Azure-Synapse-CSE.aspx" target="_blank">here </a>.
