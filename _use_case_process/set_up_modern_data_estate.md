---
title: Set Up Modern Data Estate
subtitle: Set Up the modern Data Estate for Use Case
step: 2
---
Using the <a target="_blank" href="https://github.com/microsoft/OpenEduAnalytics">OEA Setup on GitHub<a/>, education data teams can set up the modern data estate in minutes.

To setup the fully functional OEA reference architecture, follow the 3-step setup process on the OEA GitHub repository. The OEA reference architecture has been developed by Microsoft data architects using the most powerful data services from Azure and open source tools. It sets up the foundation to enable many different use cases to be developed by an education system.

**Setup**

You can setup this fully functional reference architecture (which includes test data sets for basic examples of usage) in 3 steps:

 1. Open cloud shell in your Azure subscription (use ctrl+click on the button below to open in a new page)
 
     <a href="https://portal.azure.com/#cloudshell/" target="_blank">
         <button class="btn azure-blue btn-lg btn-bold btn-nav py-0 border-0 rounded-0">
             <img src="{{ site.baseurl }}/assets/imgs/azure.svg" alt="Microsoft Azure logo" class="img-fluid micro-img" /> Launch Cloud Shell
         </button>
      </a>

 2. Download the OEA framework setup script and framework assets to your Azure clouddrive
```
cd clouddrive
```
```
wget
```
```
https://github.com/microsoft/OpenEduAnalytics/releases/download/OEA_framework_v0.6.1/OEA_v0.6.1.zip
```
```
unzip ./OEA_v0.6.1.zip
```

 3. Run the setup script like this (substitute "mysuffix" with your preferred suffix, which must be less than 13 characters and can only contain letters and numbers - this will be used as a suffix in the naming of provisioned resources):
```
./OEA_framework_v0.6.1/setup.sh mysuffix
```

Visit the [OEA GitHub repository](https://github.com/microsoft/OpenEduAnalytics) for additional setup steps and guidance.
