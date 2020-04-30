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