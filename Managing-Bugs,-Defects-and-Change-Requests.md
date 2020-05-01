
[[_TOC_]]



<br>

##Definitions of a Bug, Defect and Change Request:
- a Bug (broken or non working function) 
- a Defect (functionality not aligned with acceptance criteria) 
- a Change request (a change to previously stated requirements discovered while testing; may in the form of a user story, feature or epic).

:information_source: Bugs and Defects in ADO are managed as "work item = Bug" in ADO; Change Requests would be "work item = User Story or Feature or Epic".


<br>
<br>


##Managing Bugs, Defects and Change Requests in Azure DevOps 

Backlog prioritisation of Bugs and Defects will be based on Severity and Priority; this triage process will follow one of two processes (standard and critical processes):
<br>

1. **Non critical bugs** to follow the standard Backlog Refinement process for managing work items, i.e.: 
   - To be placed in rank stacked backlog priority order along with other work items in the backlog (note that this assumes that all teams have frequently conducted Backlog Refinement processes in place).
   - Bug Story Points; bugs will be pointed (following triage) so we can understand the impact of defects and bugs on overall delivery capability and velocity.

<br>

2. **Critical bugs** to follow an expedited triage process:
   - Triage and decisions for expediting critical or urgent bugs or defects can be managed via a Slack channel ['#triage'](https://project-water-team.slack.com/archives/C012D1Z734P); this Slack channel exists for this purpose so we can quickly react to triage and prioritise any incoming critical bugs without the need to wait for the next backlog refinement session. 
   - Ideally we will use the automated integration subscription from Azure DevOps that will notify this channel if any new ADO bugs are created
   - Best practice is then suggested to be to use mentions and threads on these notifications for a new critical bug to address specific discussions and decisions on critical bugs, e.g. for example to prioritise a new bug above already committed work in a sprint.


<br> 
<br> 

###Bug States

Once Bugs are "fixed" they should be moved into "Resolved".
In Resolved, the creater of the bug should be assigned to review and agree that the bug is "resolved".
On confirmation that the bug is resolved the bug should be moved to "Closed"

A view of bugs in the current sprint in a "Resolved" state can be seen here: https://dev.azure.com/pwc-gx-asr-innovation/Hal/_queries/query-edit/b8bdd79c-323a-47d1-b8d3-28f86b844cf3/


<br> 


###Bug Characteristics (Severity and Criticality) 

There is a guide from ADO here for the generic rating of Bugs in the tool (Source, external link): 
https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/manage-bugs?view=azure-devops&tabs=new-web-form

![image.png](/.attachments/image-386a66f9-40b7-4904-9b4e-1f73bda64900.png)


<br> 

-------------


<br> 


##Managing Change Requests / Changes to "frozen" requirements: 
- "Frozen" in this context means the state of a requirement once it is signed off in the FRD and we are able to fully detail the corresponding ADO work item then
 - If after this stage the requirement needs to change for whatever reason as we learn more then the following [Change Request](https://dev.azure.com/pwc-gx-asr-innovation/Hal/_wiki/wikis/Hal.wiki/35/Managing-Bugs-Defects-and-Change-Requests) process is recommended to be followed to ensure transparency and communication:

   - Update the requirement details in the FRD, highlighting the changes applied in the document
   - Add a comment to indicate the changes with a mention (+ or @) to the assignee of the corresponding ADO work item
   - Update the corresponding work item with the appropriate changes and add a comment / mention to whoever needs to be aware of these changes. If the change is significant then this may warrant closure of the current work item and creation of a new work item (Epic, Feature or User Story)
   - Also see more on the FRD and ADO iteration at the following page regarding [processes and documentation](https://dev.azure.com/pwc-gx-asr-innovation/Hal/_wiki/wikis/Hal.wiki/26/Agile-Ceremonies-tools-and-documentation?anchor=1.-functional-requirements-document)

