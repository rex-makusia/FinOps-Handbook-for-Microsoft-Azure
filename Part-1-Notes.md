# Bringing Visibilty and Allocating Cost

- Start with **Well-Architecture Framework(WAF)** Cost Optimization asseessment questionaire. This will help you understand the people side of things and what practices engineers, DevOps, product owners, and solution architecture follow to build and deploy their  workloads in Azure.
- At the end of the self-assessment, you will be provided with a baseline score. The score in your starting point to keep track of your improvements over a quarter of year.
- As you make small adjustments, this score will improve over time. The second tool we will explore is **Microsoft's Cost Management + Billing** to show your current cloud costs and the drivers behind them.

## Technical Requirements
- Use the Azure Well-Architecture Review from Microsoft Assessment to accomplish the tasks in this chapter, which is available at ***https://docs.microsoft.com/en-us/assessments/***
- It is an online self-assessment that take 39-60 minutes to complete
- Make sure to use your organization ID when using the tool

## Tools used in this book for implementing FinOps for Microsoft Azure
###  Azure CI
1. Open the Microsoft Edge
2. Navigate to ***https://aka.ms/installazurecliwindows.***
3. Once the download is complete, navigate to the Donwloads folder
4. Run the MSI installer
5. Once complete, open Command Prompt and run the following command:
   ```Powershell
   az log
   ```
This command will open a pop-up window where you sign into your Azure subscription. You will see the subscription details in the Command Prompt after successful Download

### PowerBI Desktop
1. Open the Microsoft Edge browser.
2. Navigate to ***https://aks.ms/pbidesktopstore.*** This link will open the Windows Store
3. Click **Install**
4. Once the installation is complete, go to the Start menu and open **Power BI Desktop**

## Azure Cost Management + Billing
- Cost Management + Billing is a Microsoft native tool built into the Azure portal that allows you to analyze, manage, and optimize the costs of your application or workload.
- It currently  supports the Microsoft Online Services Program, Enterprise Argeement, and Microsoft Customer Agreement  types of billing account.
- To access Cost Management + Billing, you will need the  **Reader** or **Cost Management Reader** persmission in Azure.
1. Open the Microsoft Edge browser
2. Navigate to ***https://portal.azure.com*** and sign in with your organization's account
3. In the top search bar, search for ***Cost Management + Billing*** and select the highlighted service.
4. Once it opens, you should be able to see the overview page, where you can see the latest billed amount, invoices over time, and subscriptions.

### Azure Advisor
- Azure Advisor is a personalized service that scans Azure resources proactively periodically and provides actionable recommendations for workload optimization. To access the Advisor recommendations,you will need at least the **Reader** permission on Azure.
1. Open the Microsoft Edge Browser
2. Navigate to ***https://portal.azure.com*** and sign in with your organization's account
3. In the top search bar, search for Monitor and select the highlighted service.
4. Once it has opened, you will be presented with an overview page that displays your monitor's **Insights**, **Detection**, **Triage**, and **Diagnotics** details.

### Azure Pricing Calculator
- Azure Pricing Calculator is an online tool that you can estimate the cost of your workload.
- Once you know what services you will need, you can select those in Pricing Calculator; you can select **SKUs** and **Instance Configuration** to get the monthly  price. Here, you can get estimates for pay-as-you-go, 1-year reservation, and 3-year reservation pricing, which includes a 30-60% discount depending on the service.
1. Open the **Microsoft Edge** browser.
2. Navigate to ***https://azure.microsoft.com/calculator*** and log in to Pricing Calculator with your organization's account.
3. Once, you've logged in, you will be able to create, save and share the pricing estimates.

