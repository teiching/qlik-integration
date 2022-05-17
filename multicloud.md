# Multi-Cloud
Using your existing QlikView or Qlik Sense Client Managed deployment along with Qlik Sense Enterprise on SaaS will enable you to bring everything together in a multi-cloud environment, making the most of your existing components and migrating entirely to SaaS at some point.
This page will provide you with some information about the most common multi-cloud scenarios and also provide you with some best-practice guidance on how to approach the migration to a full SaaS solution.

## Common Multi-Cloud scenarios
### Using QlikView with Qlik Sense SaaS
If you are alread running on QlikView, you can upload and access your existing QlikView apps to Qlik Sense SaaS given the following prerequisits are met:

* Your QlikView release is at least April 2019 or newer
* Your QlikView license is a [Unified License](https://community.qlik.com/t5/Knowledge/QlikView-amp-Qlik-Sense-Unified-Dual-Use-License-User-Allocation/ta-p/1717668) with SaaS Add-on.

In case these conditions are met you will be able to:

* Publish a QlikView app with QlikView Publisher to your Qlik Sense Enterprise SaaS environment. QlikView apps in Qlik Sense SaaS can be explored inside Qlik Cloud, but are view-only.
* Publish a link to a QlikView app inside Qlik Sense Enterprise SaaS. Accessing a QlikView app through this link will redirect you to the QlikView AccessPoint where you can explore the app given that you are able to access the QlikView server from your network
* Manually upload a QlikView file (.qvw) from your environment to your personal space inside the Qlik Sense cloud hub. In the cloud hub you can share the app with other tennant members in a shared or managed space. Users will only be able to access the app in view-only mode and not perform any edits or reload the data. So make sure the app is reloaded before you upload it!  

Further information on how to use QlikView with Qlik Sense SaaS in a multicloud deployment can be found in our [Online Help](https://help.qlik.com/en-US/cloud-services/Subsystems/Hub/Content/Global_Common/Migrate/using-QV-cloud-hub.htm "Qlik View apps in Qlik Sense")

### Using Qlik Sense Client Managed with Qlik Sense SaaS
If you have already deployed Qlik Sense Enterprise on Windows, connecting it to Qlik Sense Enterprise SaaS will allow your users to develop apps on-premises and distribute them to the cloud for consumption. Users won't be able though to modify apps that you have published to the cloud from your client managed deployment. Another prerequisit is that your Qlik Sense license includes the multi-cloud option.

The following diagram shows how a multi-cloud deployment with Qlik Sense client managed and Qlik Sense SaaS works. Once your multi-cloud deploymentr is configured, users can distribute apps created in your on-premise systems for consumption to the cloud. Thanks to a common identity provider users access both Qlik Sense client managed as well as Qlik Sense SaaS with one single license.

[![Multi-cloud deployment](https://help.qlik.com/en-US/sense-admin/November2021/Subsystems/DeployAdministerQSE/Content/Resources/Images/dr_multi-cloud2.svg)](https://help.qlik.com/en-US/sense-admin/November2021/Subsystems/DeployAdministerQSE/Content/Sense_DeployAdminister/Multi-Cloud/Cloud-deployment.htm "Multi-cloud deployment")


## Migrating to Qlik Sense SaaS
Migrating to Qlik Cloud from your on-premis Qlik system is a journey that requires some [planning](https://help.qlik.com/en-US/migration/Content/Migration/qliksense-qliksense-planning-your-migration.htm "Planning your migration to Qlik Cloud") in advance. Here are some steps that you should perform as part of your planning process:

* Run an assessment of your current system to collect information and metrics that facilitate the planning process, e.g. How many apps do you have? What are their usage metrics? What datasources are you currently using in you analytics apps and how can these be made available for consumption in the cloud?
* Define your strategic direction for moving your analytics to the cloud based on your business needs.

As shown in the diagram below, the detailed assessment should be the starting point in our recommended phased approach. After that you can start offloading the consumption of your analytic apps into Qlik Cloud, followed by creating the data pipeline that moves your on-premise data to the cloud as well until you reach the state of Active Intelligence where the Qlik Cloud capabilities actively support you in making informed decisions. Click on the image for further information regarding the planning process in our Qlik Migration Center!   

[![Phases of migration to Qlik Cloud](https://help.qlik.com/en-US/migration/Content/Resources/Images/SaaSMigrationPhases.png "Phases of migration to Qlik Cloud")](https://help.qlik.com/en-US/migration/Content/Migration/qliksense-qliksense-planning-your-migration.htm)

There are several tools and options available that can assist you during the assessment and migration process:

* Engage with Qlik Presales / Consulting to obtain a detailed assessment of your current apps and their SaaS readiness.
* Use the [Qlik Cloud migration tools](https://help.qlik.com/en-US/migration/Content/Migration/Qlik-migration-playbook.htm "Qlik Cloud migration tools") (a Qlik Sense App, migration scripts and a migration playbook) to help you during the migration process.
* Qlik Consulting also offers various packages that can actively support you during your migration, e.g. a "Qlik on-prem to cloud migration" package. Check out  what's available in the latest version of our [Qlik Consulting Catalog](https://www.qlik.com/us/services/qlik-consulting "Qlik Consulting Catalog")

Further detailed information on the migration to Qlik Cloud can be found in our Migration Center (click on the image below to get there)!

[![Migration Center](https://user-images.githubusercontent.com/72072893/168600571-78fa1f85-2656-477c-9dec-33d0b0221263.png)](https://help.qlik.com/en-US/migration/Content/Migration/Home.htm "Qlik Migration Center")



