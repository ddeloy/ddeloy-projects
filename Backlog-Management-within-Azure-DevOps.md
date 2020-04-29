[[_TOC_]]


    
<br> 

For more information on Azure DevOps as a tool see the following (external) links to get started, note there are other areas of documentation to cover test, code repos, pipeline and others: 
- [Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/?view=azure-devops)
- [ADO Boards](https://docs.microsoft.com/en-us/azure/devops/boards/?view=azure-devops)

<br>

#Epic, Feature, Story implementation (work item heirarchy)

<br>
 
Prior to WI’s (Work Items) being added into ADO, the correct Product should be identified, for example. Should you wish to update the AP.ai backlog, you should find the AP.ai backlog and begin populating items in this location.
<br/>
The wider [Audit.ai backlog](https://dev.azure.com/pwc-gx-asr-innovation/Hal/_backlogs/backlog/Audit.ai%20Programme/Stories) can be used for a view across all FSLI’s / products under the Audit.ai product.

<br/>

 ![image.png](.attachments/image-audit-backlog.png)


<br>

#Developing a DEEP Backlog
<br>

To ensure ADO is built out with a defined backlog of Work Item’s (WI’s), its key to ensure clear objectives to act as a guideline. DEEP is an acronym that indicates key traits to an effective product backlog.
- **Detailed appropriately**:
  Ensure Work Items (WI) are clearly defined and details of requirements can be understood so that the business/developers can start work without additional discussion or input.


- **Emergent**: 

  WI’s are added into the backlog as new information arises, the backlog evolves and emerges over time with those at the top of the backlog having more detail than those at the bottom of the backlog. 


- **Estimated**: 
  Work items are pointed (we use story points; see the estimation wiki for more detail) in order to clearly define the estimated effort required to deliver the work item, the approach should be standardised at a team level in order to improve estimation accuracy and consistency over time.


- **Prioritised**: 
  Work items are in rank order on the backlog based on business value and risk; this is important to ensure work begins on key deliverables, this also helps with Sprint Planning and decision making when there is excess or a lack of capacity to deliver Work Items; those at the top of the backlog have the highest priority order. Note: A work item may have a priority assigned (1 being the highest) within the item itself, however, the backlog priority order is the preferred prioritisation mechanism.

<br/>
<br/>

**Below is a break down of each DEEP section to explain the process within ADO to follow out these steps:**
<br/>

------------
<br/>

## Detailed Appropriately
<br> 

We use the [Agile process in Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/about-work-items?view=azure-devops&tabs=agile-process#wit) which breaks work items and organises them as follows; for more on this see [ADO Defining Features and Epics](https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/define-features-epics?view=azure-devops&tabs=agile-process):


<br><br>

**Work Item definition and hierarchy**:

<br>

**Epic:** This is the overall objective that you are delivering; used as a broader grouping of work items required to deliver a significant component of the overall product. An epic typically represents a business initiative to be accomplished.
<br>
**Feature:** This will break down the key deliverables of the Epic to ensure the business objectives can be achieved; a feature typically represents a function or module of software that forms part of the overall epic or business need.
<br>
**Story:** Within each feature, work items are defined to achieve the functionality delivered and to represent the user requirement at a more granular level; user stories typically represent a specific user need with a strong focus on the customer “persona”. 
<br>
**Task:** A task is simply a break-down of work that needs to be completed in order to achieve the delivery of the Story. 
<br>
**Bug:** A bug tracks identified bugs (broken or non working function) or defects (functionality not aligned with acceptance criteria) identified during manual or automated testing processes.

<br/>
 <br/>
<br/>

 ![image.png](.attachments/image-workflow-1.png)



###A focus on Azure DevOps User Stories

Ideally stories should be created and linked to a feature delivery to visualise all requirements required to deliver a feature(s). A story would be created by the developers & product owners. Collaborating to ensure that both Business and Technical requirements are documented and understood.
<br/>
*What should this process look like?*
Product owners should be defining the product they wish to deliver for management/stakeholders. Once high level requirements are defined within the FRD document, the developers should be included into the review sessions to raise work items, potential blockers & additional items/considerations to factor in.
<br/>

*Where would this be managed?*

ADO is the best location to document and manage the feature and story creation, once a feature is documented we are able to build out user stories within it to define the deliverables required to ensure the feature is delivered.

 ![image.png](.attachments/image-workitems-1.png) 


As seen above, it's clearly visible that the EPIC Cash.ai - Refactoring is our objective, to deliver that objective we have multiple features. Refactoring - Bank Confirmation Pipeline is one feature required to deliver the EPIC, therefore to ensure we meet the features requirements it would be essential to to document story items to ensure the feature can be delivered with all requirements met.
<br/>
The backlog ordering (priority ordering) can also be set at this stage to reflect the most important work items at the top of the backlog and those that may be addressed later at the bottom of the backlog.

<br>

-------
<br>


##Emergent 


*Adding Work Items to the backlog as new requirements and information emerges:*
<br>
ADO has multiple ways of adding items, the preferred method would be adding them directly into a backlog.
<br/>
As mentioned above, prior to adding a WI into ADO you must confirm the application/team that your item will be in relation to.
<br/>
Go to the backlog item located under Board within ADO (Seen below)

  ![image.png](.attachments/image-sidemenu-backlog.png) 

After arriving on the backlog of choice, select the top right hand corner of the page and select the Work Item type you wish to add:

   ![image.png](.attachments/image-product-backlog.png) 


<br/>
Once confirmed, select ‘+ New Work Item’. 

   ![image.png](.attachments/image-plus-workitem-1.png) 
   
   ![image.png](.attachments/image-plus-workitem-2.png) 
 
<br/>

-----------------
<br>

##Estimated  

The common practice when estimating effort required to deliver WI’s is using the Fibonacci Sequence. 
See Wiki Article: [Agile Estimating](https://dev.azure.com/pwc-gx-asr-innovation/Hal/_wiki/wikis/Hal.wiki/15/Agile-Estimating)

<br>

 ![image.png](.attachments/image-fibonacci-sequence.png) 
 
This should be used to estimate the effort required to complete a WI. 

1 Point is seen as half a day's work, 2 Points is seen as a day's work, 3 Points is seen as a day and a half etc. This should be the consistent method of estimation across all applications and will be tracked in reports and stand ups. 

<br/>

**How do we add points?**

Upon creating a story, you would be required to point up the effort required to complete the WI. To add a point estimation to an item, select the chosen story within ADO and click the box seen below named ‘Story Points’. From here you can add in your Fibonacci estimate and it will automatically save.

   ![image.png](.attachments/image-ado-pointing.png) 
 

<br>

-------

<br>

## Prioritised 

Work items should be in backlog rank order (Azure DevOps calls this "stack rank" order) on the backlog based on business value and risk; this is important to ensure work begins on key deliverables, this also helps with Sprint Planning and decision making when there is excess or a lack of capacity to deliver Work Items; those at the top of the backlog have the highest priority order. 

<br/>

An example of this ordering is shown below: 

![image.png](/.attachments/image-15ffc220-9351-4b5d-bb34-e640c3ff3d23.png)

Note: A work item may have a priority assigned (1 being the highest) within the work item itself on the "priority attribute" field, however, the backlog priority order is the preferred prioritisation mechanism.

<br/>
<br/>

**Why prioritise?**

Once you have a prioritised, estimated and detailed backlog that is continually refined (built upon and developed on a regular basis, **preferably via frequent (at least weekly) backlog refinement meetings** with the PO / project owners) then the Sprint Planning process becomes a lot easier. You can use the built in ADO Velocity forecasting tool to help indicate what work items can be accomodated in upcoming sprints based on the work items estimated sizing.
<br/>
A view of an example backlog with forecasting turned on is shown below which indicates when each work item can be accommodated in terms of upcoming iterations (a.k.a. sprints): 

   ![image.png](.attachments/image-sample-backlog.png)

<br/>

It is worth noting that you cannot use the velocity based forecasting tool when you have the parent / hierarchy view (i.e. showing which epic and feature a story belongs to) in Azure DevOps; these are mutually exclusive views (but you can still prioritise by forced rank ordering within a feature or epic, just not across the entire backlog in this view): 

  ![image.png](.attachments/image-sample-backlog-1.png)

 