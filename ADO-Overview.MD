# ADO Introduction

## The Project
**At present, there is a single default project: Hal**

**Project configuration**<br/>
A default team and default area path defined for the project. New teams added to support their ability to manage their respective backlogs and sprints.

**A team refers to a group of project members who work in a particular product area**<br/>
Teams have an associated area path.<br/> 
Area paths are hierarchical paths that denote the possible areas of ownership in an organization.<br/> 
Many to one: A product area (like Cash.ai) will have multiple team subscriptions.

**A team consists of a name, its members, and its area paths.**<br/>
Boards, Backlogs, Sprints rely on team configurations.<br/> 
For example, if you want to add a Kanban board or product backlog, you define a team.<br/>
Adding a team essentially adds another product backlog associated with that team.

### Area paths
Area paths will group work items by product, feature, or business areas to support teams responsible for work assigned to those areas. We have defined a hierarchical set of areas (supports a business hierarchy that wants to track the progress of several teams).

### Iteration (sprints) and iteration paths
```Best Practice```
We want to set up a series of sprints at the project level that all teams can use. 

```Best practices``` suggest a unified sprint cadence.<br/>
```Best Practice```Naming conventions:
- Simple numerical ordering: Sprint 1, Sprint 2, etc.
- Feature sprints with descriptive names, when appropriate.

### Workflow states
As work progresses from not started to completed, you update the State workflow field from:
New, Active, Resolved, and Closed.

Azure Boards provides the following interactive lists and signboards. 
Each tool provides a filtered set of work items. All tools support viewing and defining work items.  

### Work items and work item types
- When you add a user story, bug, task, or feature, you create a work item. 
- Add epics to track significant business initiatives. 
- Add features to track specific applications or set of work. 
- Define user stories to track work that you'll assign to specific team members, and bugs to track code defects. 
- Use tasks to track even smaller amounts of work for which you want to track time either in hours or days.

```Best Practice```<br/>
The golden rule is that every work item should be traceable to an Epic
- Hierarchically: Epic > Feature > Story/Bug > Task
- Every Epic needs at least a 1 sentence description
- Features require more detail, at a minimum, several descriptive sentences


## Work items 
Use to find work items that are assigned to you quickly. Filter work items based on other criteria, such as work items that you follow, that mention you, or that you viewed or updated. 

### Boards: 
Boards present work items as cards and support quick status updates through drag-and-drop. Use to implement Kanban practices and visualize the flow of work for a team.

### Backlogs: 
Backlogs present work items as lists. Team backlogs can also be product backlogs. When creating a sprint, you'll likely be selecting from product backlogs and moving them into your sprint backlog. 

What can you do from a backlog view versus a board view? 
How do changes you make in one show up on the other? What customizations can you prepare for each?
- Backlogs display work items as a list and boards display them as cards
- You use your product backlog to plan and prioritize your work quickly
- You use your sprint backlogs and taskboards when you work in Scrum
- You use your Kanban board to update work status and when you employ Kanban methods
- Each backlog is associated with a board, changes to priority order made in one board reflect in its corresponding board
- Backlogs, boards, and plans are configurable for each team.

With list backlogs, you can quickly group and prioritize work; and perform bulk updates on selected work items. 
With boards, you can quickly update the status and fields displayed for each work item.

### Sprints: 
Sprint backlogs and taskboards provide a filtered view of work items a team assigned to a specific iteration path or sprint. 
Your sprint backlogs are one of three classes of backlogs available to you (backlogs, boards, and plans).

As noted above, from your backlog, you can assign work to an iteration path by using drag-and-drop. You can then view that work in the associated sprint backlog. 

### Queries: 
Queries are filtered lists of work items based on criteria that you define by using a query editor. You can use queries to support the following tasks:
- Find groups of work items with something in common.
- Create a list of work items to share with others or do bulk updates. Triage a set of items to prioritize or assign.
- Create status and trend charts that you can then add to dashboards.


