# Azure Cost & Capacity Insights
This is a Customized Azure Cost & Capacity Insights Power BI Template App derived out of standard Cost Management Template App and is meant to assist in analyzing and managing your Cloud Cost & Capacity. 

You can utilize the Azure Cost & Capacity Insights app to Monitor Costs, Capacity, Usage Trends and identify Cost & Capacity Optimization options to reduce Azure Cloud expenditures. Please use Focus Mode for better & full-page visibility

You can install & use the app as is or you can also download the Customized Azure Cost & Capacity Insights Template as .pbix file into Power BI Desktop and join with additional data to create customized reports to get holistic views of your overall business cost. 

# Azure Cost & Capacity Insights consists of 2 categories of Reports;
 **Azure Services Consumption Insights - High Level Overview & Azure Services - Current Consumption & Capacity Insights**
  * Both the Reports serves as a Readymade Template to provide insights into Azure Service Cost Consumption, as latest as n-2 day, over a selected period.
  * You need to Connect to the Dataset with an Enterprise Admin (Read Only) Role.  The Reports are scheduled to Refresh daily at 00:00 hours
  * The initial duration is set to 1 or 2 Months, the same can be changed between 1 to 12 Months by changing the "Number of Months" Parameter Value

 **Azure Resource Quota Usage Insights**
  * This Report is derived based on Azure Management REST API's. This Report serves as Readymade Template to get Azure Quota & Usage information for Compute, Disks, Storage & Network Resources and Idle / Orphaned Resources like NIC's, Managed Disks & Public IP's across all the Subscriptions under a specific AAD Tenant
  * You can download the Report Template (MS Excel version) & go through the setup documentation from my GitHub Repo here - [GitHub - i4dCEP/Azure-Quota-Usage-Insights](https://github.com/i4dCEP/Azure-Quota-Usage-Insights) 
  * You only need to authorize the API connection for once – Go to Data à Get Data à Data Source à Edit Permissions à Credentials à Organizational Account à Sign in as different user for both the web url's as below;
    * "https://management.azure.com/subscriptions" & "https://management.azure.com/tenants"

**Learn more about the Standard Azure Cost Management Power BI template App**
Visit https://aka.ms/CostMgmt/ACMinsights for additional information on the Cost Management template app. To create customized visualizations from scratch, see: [Connect to Azure Cost Management in Power BI Desktop](https://aka.ms/CostMgmtConnector)

**Azure Cost Management documentation:** https://aka.ms/CostMgmt/Docs | Azure Cost Management video channel: https://aka.ms/CostMgmt/Video | Azure Cost Management updates: https://aka.ms/CostMgmt/Blog

**Provide Feedback**
Have an idea or suggestion? E-mail: hemacn@microsoft.com to post your thoughts.
