# Multi-Cloud
Using your existing QlikView or Qlik Sense Client Managed deployment along with Qlik Sense Enterprise on SaaS will enable you to bring everything together in a multi-cloud environment, making the most of your existing components and migrating entirely to SaaS at some point.
This page will provide you with some information about the most common multi-cloud scenarios and also provide you with some best-practize guidance on how to approach the migration to a full SaaS solution.

## Common Multi-Cloud scenarios
### Using QlikView with Qlik Sense SaaS
### Using Qlik Sense Client Managed with Qlik Sense SaaS

## Migrating to Qlik Sense SaaS
Migrating to Qlik Cloud is a journey that 

[![Phases of migration to Qlik Cloud](https://help.qlik.com/en-US/migration/Content/Resources/Images/SaaSMigrationPhases.png "Phases of migration to Qlik Cloud")](https://help.qlik.com/en-US/migration/Content/Resources/Images/SaaSMigrationPhases.png)

### Key considerations
### Best-practice workflow

1. Engage with Qlik Presales or Consulting for an analysis of your existing QlikView / Qlik Sense Apps with the Qlik SaaS Readiness app to get some insight into where you are in your journey to SaaS and create a transition plan.
If you are running QlikView, you can also use the [QlikView Governance Dashboard App](https://help.qlik.com/en-US/governance-dashboard/Content/QV_GovDashboard/What.htm) to collect some additional metrics on your QlikView Applications

![image](https://user-images.githubusercontent.com/72072893/166587639-dee6d381-c2ec-4769-876b-d0f554dd0a74.png)



2. Offload the consumption of your QlikView/Qlik Sense applications to the cloud by publishing them to Qlik Sense SaaS. Development of apps, app reloads as well as reporting will continue on you on-premises systems. 
3. Create a data pipeline to move data from your on-premises system to the cloud. This could be done using Hybrid Data Delivery, using the Qlik Data Gateway or even publishing entire QVDs to the cloud
4. Once all your relevant apps and the connected data have been migrated to the cloud, you can now also continue with app development inside Qlik Sense SaaS and also run the app reloads there. Ideally you won't need your on-premises system anymre

## FAQ
