
# Making Cost Management Work in Public Cloud 


 


To make cost management work for Public Cloud you need to stop looking at it from a "Pure Cash" perspective. As conflicting as it sounds, cost management analysis and decisions based on a "Pure Dollar" point of view is an unqualified decision in the Public Cloud arena. Cost Management in the public cloud also entails, on top of cash, tracking and analyzing variables such as utilization and performance in order to calculate, analyze and monitor cost.  


 


As you can see, cost management in the Public Cloud requires to change your paradigm around data collection. More types of data are require to keep cost in check and source of data will provide increasingly higher volumes of data cost items. As your Public Cloud footprint matures and increases in size, the initial human processes established to capture, analyze and monitor the data will face efficiency and complexity challenges becoming your cost management bottleneck. To address this, you need to support your processes with the analytics and monitoring engines that takes care of the complexity, letting your user focus on getting the cost management data ready for decision making.  


 

The following diagram shows a consolidated view of the cost management capabilities that need to be available for an end-to-end management of cost: 


![ConsolidatedCostManagement](https://github.com/alvarovitta/Cost-Management/blob/master/Images/ConsolidatedCostManagement.png)

 


Cost Management for the Public Cloud comprises the following components/capabilities (in a Bottom-Up view): 


 


## Data Sources 

For the context of this document, we will focus the Azure Cloud Platform as the main data source. As mentioned in the section [Azure Resource Manager (ARM) Overview](4.1-Azure-Resource-Manager-Overview.md), the Azure Resource Manager offer a Service Management API Layer in which all resource related interactions happen including the collection of Azure Data Types described in the diagram above.  


## Data Types 

As mentioned earlier in this section, we will focus on collecting more than just billing data and augment our scope of data to include usage, utilization, pricing, and any other metadata to help outline the most complete and accurate cost management view. 


## Data Collection, Aggregation and Normalization 

From the perspective of Azure cost management, the process of collection, aggregation and normalization will happen in the background. For more details check the [Azure Resource Manager (ARM) Overview](4.1-Azure-Resource-Manager-Overview.md) section in this document. 


## Analytics & Monitoring 

**TO DO**

## User Experience 

**TO DO**

## Design Considerations 

The Azure Cloud Cost Management capabilities have been designed with the following three core principles in mind: 

### Accountability Principle - Drive Organizational Accountability 

As mentioned in principle number one, providing high degrees of visibility is a fundamental step to increase the cost awareness of the organization. Once visibility is a mature capability in your cost management activities, the next step is to make stakeholders directly accountable to their cloud spending and highlight the overall impact to the organization. To drive accountability in the organization, the cloud spending should focus on the following: 

  - Allocate usage and costs to business units and projects 
  - Produce chargeback and showback reports 
  - Let teams access data and insights with Role-based Access Control (RBAC) 
  - Automatically alert stakeholders of spending anomalies and risks 


## Cost Management Tutorials 


### Review Usage and Costs 

  - [Track usage and cost trends](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-review-usage#track-usage-and-cost-trends) 
  - [Detect usage inefficiencies](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-review-usage#detect-usage-inefficiencies) 
  - [Create alerts for unusual spending](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-review-usage#create-alerts-for-unusual-spending) 


### Control Access to Data 

  - [Create a user with admin access](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-user-access#create-a-user-with-admin-access) 

  - [Create a user with user access](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-user-access#create-a-user-with-user-access) 

  - [Create entities](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-user-access#create-entities) 


### Forecast future spending 
  
  - [Forecast Spending](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-forecast-spending#forecast-future-spending-1) 


### Manage Costs 

  - [Use custom tags to allocate costs](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-manage-costs#use-custom-tags-to-allocate-costs) 

  - [Create showback and chargeback reports](https://docs.microsoft.com/en-us/azure/cost-management/tutorial-manage-costs#create-showback-and-chargeback-reports) 



## Next Steps 



## Links 

 
## Additional Information 



