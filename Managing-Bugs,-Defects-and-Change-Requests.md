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

1. **Non critical bugs** to follow the standard Backlog Refinement process, i.e. to be placed in rank stacked backlog priority order along with other work items in the backlog (note that this assumes that all teams have frequently conducted Backlog Refinement processes in place).

2. **Critical bugs** to follow an expedited triage process; we have a Slack channel for this purpose so we can quickly react to triage and prioritisation of any incoming critical bugs without the need to wait for the next backlog refinement session. Ideally we will automate the integration of ADO bugs into this slack channel and then use mentions / threads to address specific discussions and decisions on critical bugs (under development). 