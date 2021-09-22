---
layout: post
title: OEA August 2021 Newsletter
author: Author
description: In this newsletter, we share updates about the upcoming launch of the Global OEA Community, new OEA website and others.
category: Newsletter
image: /assets/imgs/posts/img_august_2021_oea_newsletter.png
---

##### OEA Overview

Open Education Analytics (OEA) is a community of education systems, coordinated by Microsoft Education, collaborating to develop open-sourced data analytics solutions for the education sector built on Azure Synapse Analytics and PowerBI.

- GitHub repository: <a href="https://github.com/microsoft/OpenEduAnalytics" target="_blank">https://github.com/microsoft/OpenEduAnalytics</a>
- OEA Overview video: <a href="https://www.youtube.com/watch?v=efNYbS4sC4g" target="_blank">OEA Overview - YouTube</a>


##### OEA Communities

We are excited to announce our first official monthly OEA Global Community meeting series in October.  This community is an ongoing group of education systems who are working together as they implement modern data and AI approaches.  It is a small, private community comprised of institutions and large education systems discussing their work, sharing use cases, and developing thought leadership for the broader international education community. This meeting is the first in a series of monthly meetings where members can share implementation and use case examples, as well as learn about new open-source data services.   

Earlier in the month, we hosted the first United States chapter of the OEA Community. Leaders from US education systems shared their visions for the community and are all embarking on use cases based on the OEA Architecture. One leader said, “We're working on the same types of projects; we want to learn from what each other has done to accelerate the pace. We need a way of looking at data in a comprehensive manner and data that is not all academic in nature: we need to look at the whole child. How do we capture those non-academic pieces? We need a plan for each individual student.” 

The Australian OEA Community also launched in June with 5 Australian states, as well as several Catholic Education systems in Australia. This community has focused on sharing use cases, approaches to data governance, and optimal ways to present data insights to teachers. 

##### New OEA Website
We are thrilled about the launch of the new OEA Website, where all OEA resources, shared use cases, training, and Responsible AI concepts and practices are shared. 
<div class="container-wrapper text-center">
   <img src="{{ site.baseurl }}/assets/imgs/img_new_oea-website.png" class="img-fluid w-100" alt="Home page of New OEA Website" />
   <figcaption class="mt-2">Figure 1: Home page of New OEA Website</figcaption>
</div>
Please take a moment to explore the new site and share it with your organization.


>
> ##### OEA Community Spotlight
>
> After learning about OEA, meeting with the OEA Team, and talking with other OEA partners, the Georgia Department of Education launched their statewide data modernization plan in August. This project aims to move current on prem data systems for statewide education data and reporting to Azure, using OEA as the starting point. 
> A leader from the Georgia Department of Education  said: "This data modernization will enable us to move to a culture that is data driven with an unwavering commitment to building a more student-centered culture."


##### OEA Tech: Helping Education Systems Setup Their Modern Data Estate

We are excited to announce the release of [v0.4 of the OEA architecture](https://github.com/microsoft/OpenEduAnalytics/releases/tag/v0.4) which comes with a number of improvements [(see list here)](https://github.com/microsoft/OpenEduAnalytics/releases/tag/v0.4) and are working to release v0.5 (targeting end of September), which will include test data generators, a well-defined module and package structure that includes guidance on specific criteria for submission of partner contributed assets, and an enhanced installation and administration CLI to facilitate initial setup as well as ongoing setup and maintenance of extension modules and packages. 
With the new version, we are taking additional steps to protect student identity by using the [best practices for GDPR and CCPA compliance using Delta Lake](https://docs.microsoft.com/en-us/azure/databricks/security/privacy/gdpr-delta). Delta Lake provides structured data management on top of the data lakes of education systems, hence providing a simplified, efficient and optimized way of removing personal information of students in response to GDPR and CCPA requests. We are using a one-way cryptographic hashing and salting to pseudonymize personal information. In addition, Delta Lake transaction log records details about every change made to the data providing a full audit trail of changes. The process of ingesting data into the lake and iteratively preparing, cleansing, and optimizing that data is represented in 3 stages that map to the Delta Lake's proposed stages of bronze, silver, and gold. 
The new architecture provides enhanced framework functionality that simplifies the process of preparing and pseudonymizing data from new data sources by building on PySpark to establish a framework level of abstraction. In the end, all that is needed to be able to tap into the power of the framework is to specify the data schema of a new data source. 

<div class="container-wrapper text-center">
   <img src="{{ site.baseurl }}/assets/imgs/img_pseudonymization.png" class="img-fluid w-100" alt="Stages for Pseudonymizing Student Data Using Delta Lake" />
   <figcaption class="mt-2">Figure 2: Stages for Pseudonymizing Student Data Using Delta Lake</figcaption>
</div>

##### Data Analytics and AI
We kicked off our work to build a machine learning model for the prediction of vulnerable students for the Tasmania Department of Education (DoE). The Tasmania DoE has an obligation to look after the wellbeing of learners in the public education system in Tasmania. The sooner that issues can be identified with vulnerable students, the earlier support can be provided for these young people. The Tasmania DoE’s hope is to move to proactive, AI based insights that provide real time advice to care givers or support staff rather than making subjective decisions about who is vulnerable and being reactive.
The next couple of months will be used to build and productionize the predictive model while incorporating the principles of Responsible AI during every stage of the process. We will then use these processes and learnings to create and publish an OEA GitHub machine learning package that will include notebooks, pipelines, test data and documentation that other school systems can use in their own Azure environment. 

##### OEA Technology Partners
OEA is developing a global network of technology partners that are trained on the OEA architecture, services and approaches. These partners are ready to work with education systems, supporting OEA proof of concepts, as well as full scale data modernization and AI use case development. We will be publishing a list of these companies and organizations in October, 2021. 
OEA Partners are a mix of system integrators, analytics companies, education technology companies, and research universities.  They are from all global regions and are vital to how OEA will serve education systems. 

