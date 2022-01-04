---
layout: post
title: OEA November & December 2021 Newsletter
author: Author
description: In this newsletter, we share updates about the Azure in Action webinar, Global OEA Community meeting and others.
category: Newsletter
image: /assets/imgs/posts/img_november_december_2021_oea_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems and tech partners, coordinated by Microsoft Education, collaborating to develop open source data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.  

- OEA Website: <a href="https://openeducationanalytics.org" target="_blank">https://openeducationanalytics.org </a>
- OEA GitHub Repository: <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">https://github.com/microsoft/OpenEduAnalytics</a>
- OEA Overview Video: <a href="https://www.youtube.com/watch?v=q6snp28bBQU&t=1s" target="_blank">OEA Overview on YouTube </a>


##### OEA Communities

In December, we conducted US, Australia and Global OEA Community calls. The Australia OEA Community call welcomed in participants from higher ed for the first time. Under discussion was the development of a new OEA Package based on the SIF education data standard used in Australia. That will likely include an analytical data model based on the SIF standard, and be produced in the first half of 2022.

In the US OEA Community call, we had a robust discussion on statewide P20W reporting and analytics opportunities. The Georgia Department of Education is starting work with Microsoft on their full data modernization initiative in 2022 and will share their inventory of Use Cases that will be part of this initiative. The CCSSO has agreed to work with OEA to develop a collection of the Use Cases that states are developing for P20W reporting. 

At the December OEA Global Community call, we heard exciting updates from the Azerbaijan Ministry of Education on their progress with national real-time education data reporting and on their AI/ML Studies for their national Virtual School that commenced during the pandemic and hosts 1.6M students across K-12 and Higher Ed. By using tools like Azure ML with guidance from OEA data scientists, they are able to execute complex projects like machine learning and predictive analytics on their own. This has helped them channel more of their time and effort to defining and exploring the research problems and enriching the models. At this same meeting, Kent State University described their work in developing a data-driven culture and how that was addressed through negotiating data governance policies and forming a data governance council. This sets up a strong foundation for the institution to trust in their data and leverage it across many analytics and AI use cases in the years to come. 

Also, check out the new case study on the Nebraska OEA story on statewide longitudinal reporting <a href="https://openeducationanalytics.org/blog/2021/10/29/nebraska-department-of-education-generates-actionable-insights-with-microsoft-azure.html" target="_blank">here</a>.


##### OEA Tech: Helping Education Systems Setup Their Modern Data Estate
Data governance and compliance is increasingly becoming top of mind for school systems. In Australia, the Tasmania Department of Education recently presented to the Australian OEA Community how they use Azure Purview as the foundation for their data governance strategy and implementation. Azure Purview is now a recommended component of the <a href="https://openeducationanalytics.org/get-started/" target="_blank">OEA reference architecture.</a> Tasmania described creating a data governance operating model and building a lifecycle of data across people, processes, and policies right from when the data is created, how it is mapped, how it is classified, how it can be protected, how it can be stored, how it can be used all the way to how it can be maintained. Learn more about Azure Purview <a href="https://docs.microsoft.com/en-us/azure/purview/overview" target="_blank">here </a>. 

**New OEA Modules and Packages** 
-	Updated Microsoft Teams <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Data/Microsoft_Education_Insights_Premium" target="_blank">Education Insights Premium Module </a> (requires paid subscription to <a href="https://education.microsoft.com/en-us/resource/3978f2d8" target="_blank">Education Insights </a>)
-	<a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Data/Intune" target="_blank">Intune Reports Module </a>
-	<a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/packages/Verified_Credentials" target="_blank">Verifiable Credentials Package for Digital Learner Records</a>

These are all very new OEA tech assets, and we welcome contributions or feedback on the ease of implementing them, or opportunities to develop Proof of Concept projects with education systems.


>
> ##### OEA Community Spotlight: Predicting Vulnerable Students in Tasmania
>
> The shift to hybrid learning is not just changing the way students learn – it’s producing a trove of data that can provide insights into how to better support students. The OEA project with the Tasmania Department of Education was highlighted in the fourth episode of Microsoft Australia’s “Azure in Action” series in November. Azure in Action is a public Data and AI series. Tasmania’s Department of Education co-presented the story with the OEA Team. 
>   
> This session which is open to the public, provides demos of: 
> 
> -	Purview and Synapse and the steps taken to discover and ingest data from multiple data sources. 
> - How Azure ML and Responsible ML tools like <a href="https://fairlearn.org/" target="_blank">Fairlearn </a> are being used to develop predictive models of vulnerable students.
> Feel free to <a href="https://info.microsoft.com/AU-AzureAI-VDEO-FY22-12Dec-06-Azure-in-Action-Ep-4-Empowering-educators-to-drive-better-education-outcomes-with-AI-and-open-data-analytics-SRGCM5449_LP01-Registration---Form-in-Body.html" target="_blank">take a look </a> and you are welcome to share this story. 


##### Data Analytics and AI

Community contributions are at the center of thriving open-source communities. With the improved OEA framework and <a href="https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/_Creation_Kit" target="_blank">our new Module Creation Kit</a>, we’re making the process for contributing and curating new OEA modules easier, while empowering our customers and partners to make contributions to the community.
Our first customer contributions to OEA are underway. Fresno Unified School District is working on a Clever module for ingesting multi-app signals from Clever to Synapse. A Canvas module is being developed by the Tasmania Department of Education in Australia for ingesting data from the Canvas LMS. 

We also have a partner working on our first module using public data, the Integrated Postsecondary Education Data System (IPEDS), which provides data from all higher ed institutions in the US. And finally, an OEA Advanced Partner has contributed a <a href="https://azuremarketplace.microsoft.com/en-US/marketplace/consulting-services/spyglassmtgllc.oea" target="_blank"> 10-week OEA based solution </a>
 to Azure Marketplace that delivers overall student engagement and learning analytics for higher education. 
The OEA team will review all new module contributions against our Module Creation Kit rubric to ensure that they meet the appropriate quality and OEA alignment standards before being published on the GitHub repository. If you have an idea for contributing a module or package to OEA, please get in touch with the OEA team.

##### OEA Partner Spotlight: Spyglass’s OEA solution on Azure Marketplace
One of our OEA Advanced Partners recently published an OEA based solution on Azure Marketplace. The <a href="https://azuremarketplace.microsoft.com/en-US/marketplace/consulting-services/spyglassmtgllc.oea" target="_blank">OEA Open Education Analytics: 10-Wk Implementation </a>  is designed to help lower student dropouts and increase engagement rates in higher education institutions. It includes standardized modules that can be seamlessly integrated with learning management systems like Blackboard or Nexus LMS.
This solution is a great example of how to leverage the OEA Program and technical assets, and it is of high value to Microsoft account executives who are incentivized when they land these solutions. We are broadcasting this solution to our Microsoft account executives and higher education customers in the US. We welcome more such OEA-based solutions from our OEA Partners.
