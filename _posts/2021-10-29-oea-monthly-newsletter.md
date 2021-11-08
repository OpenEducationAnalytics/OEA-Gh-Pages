---
layout: post
title: OEA October 2021 Newsletter
author: Author
description: In this newsletter, we share updates about the new modules and packages published to GitHub, the Global OEA Community and others.
category: Newsletter
image: /assets/imgs/posts/img_october_2021_oea_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems and tech partners, coordinated by Microsoft Education, collaborating to develop open source data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.  

- OEA Website: <a href="https://openeducationanalytics.org" target="_blank">https://openeducationanalytics.org </a>
- OEA GitHub Repository: <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">https://github.com/microsoft/OpenEduAnalytics</a>

##### OEA Communities

On 20th October, we launched the Global OEA Community with education systems from different parts of the world. They shared their visions, scenarios and use cases in data and AI. 

6 OEA Community members provided their visions for data and analytics: 
- **University of Florida** shared their vision to unify data from 2.5 million students and educators in early learning, literacy, and math across the US to accelerate research in equitable learning and application and program development using OEA and Synapse as the cloud data foundation. 
- **Azerbaijan Ministry of Education** shared how they used the “Virtual School” platform to collect information on the learning process, activities, and assessment results of students across 1.6 million students. 
- **City of Helsinki, Education Division** shared how they are using data and AI to ensure all learners’ well-being is supported and each one reaches their full potential through various use cases. 
- **Georgia Department of Education** is launching the development of a Statewide Longitudinal Data System (SLDS) designed to support the collection of longitudinal data for reporting to more stakeholders, including how districts, schools, and students are progressing, and to enable further use of analytics and AI to support every learner. 
- **Penn State University** wants to move from descriptive to prescriptive analytics by creating a university system-wide data environment to support adult and part time learners, even as they move between campuses and different employment scenarios. Predictive analytics will also inform policy decisions and systematic change. 
- **Kent State University** wants to elevate the quality of their data to enhance insightful decision making and forecasting. This includes a robust system-wide data governance policy to ensure data integrity over time. 


##### OEA Tech: Helping Education Systems Setup Their Modern Data Estate
OEA technical assets enable our partners and customers to experience easier deployments of data and AI Azure services, realize high value education use cases, and see quick time to value. Our latest release of the OEA framework, v0.5, focuses on a cleaner separation of the installation of framework assets from the provisioning of the infrastructure, and an updated module and package structure. We have also added infrastructure guidance to better align with Microsoft resources including the Cloud Adoption Framework and Enterprise Scale Analytics. We continue to build out the OEA framework to include assets that codify patterns distilled from the development of modules and packages designed to enable key education use cases for data and AI. 

Our v0.5 release includes among others: 
- Updated OEA framework setup script to simplify installation of framework into existing Synapse workspace. 
- New framework assets including linked services, datasets, and pipelines. 
- Data generator framework and utilities. 

See the full list <a href="https://github.com/microsoft/OpenEduAnalytics/releases/tag/v0.5" target="_blank">here</a>. 


>
> ##### OEA Community Spotlight
>
> Addressing student absenteeism continues to permeate education policy and practice in global education systems. California and many other states have incorporated “chronic absenteeism” as an accountability metric under the Every Student Succeeds Act.
>   
> OEA is partnering with Fresno Unified School District’s Department of Prevention and Intervention over the next few months to build a model for predicting students at risk of becoming chronically absent. This will help Fresno focus its resources to better support students on a trajectory leading to chronic absenteeism.  
> 
> What is unique about this project is that we will include student digital activity data from O365 as one of the features or indicators that may help predict absenteeism more accurately.
 


##### Data Analytics and AI

The OEA community is building shared technology resources, including modules (for a single data source) and packages (for multiple data sources combined for a use case) to help education systems implement the modern data estate in education. In October, we published 1 new module and 1 new package on the OEA GitHub repository. These are the [Graph Reports Module](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Graph) for ingesting data from the Graph Reports API into Synapse and the [Hybrid Engagement Package](https://github.com/microsoft/OpenEduAnalytics/tree/main/packages/ContosoISD_hybrid_engagement) which provides a set of assets for education systems to have a more comprehensive report of in-person attendance and digital activity. 

Our upcoming modules include the Microsoft Education Insights Module for ingesting data from Education Insights to Synapse, the Intune Reports Module for ingesting Intune device report data into Synapse and the Clever Module for ingesting multi-app signals from Clever to Synapse. All of these modules can support education systems seeking to develop Digital Learning Ecosystem Insights, to see how use of various digital learning tools relate to learning outcomes in this era of hybrid learning. 

We will also be publishing the Verified Credentials Package which will enable education systems to issue verified credentials of a students’ knowledge and skills from their OEA-based data estates. 
 

##### Customer and Partner Enablement
To improve the process of developing and contributing modules for our partners and customers, we recently published a kit for module creation. In the OEA framework, a module refers to a set of assets for moving a single data source into Synapse. The [OEA Module Creation Kit](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/_Creation_Kit), now live on the OEA GitHub repository, is designed to make the development of high quality OEA Modules easier by defining guidelines so every module will have a consistent set of assets. The more modules the OEA Community develops, the more education data sources can easily be ingested into each organization’s modern data estate. This will save valuable time and resources for both education systems and analytics partners. OEA modules eliminate the need for each team to build education data source pipelines ‘from scratch’ and speed up the time to value for analytics investments. 

In October, we held our first Quarterly Partner meeting with business leaders and technical members of 20 of OEA partner companies to share recent updates from the OEA team, including technical releases like v0.5 of the OEA framework and our new modules and packages. We then discussed business topics like how partners can get 5+ OEA deployments per year, reviewed the benefits and requirements for each level of partnership and funding programs that partners can tap into. Finally, we discussed one of the use cases that is of interest to our customers: State or National Longitudinal Reporting. 

We are also delighted to announce the first group of 10 “Advanced” OEA Partners who have demonstrated their knowledge of how to use OEA technical assets and Synapse. These partners have the technical knowledge to support Microsoft’s Education customers as they embark on Data and AI projects. These partners serve customers globally in many languages and regions.
