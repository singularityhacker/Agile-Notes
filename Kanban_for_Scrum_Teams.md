# The Kanban Guide for Scrum Teams

See: https://www.scrum.org/resources/kanban-guide-scrum-teams

Kanban (n): a strategy for optimizing the flow of value through a process that uses a visual, work-in-progress limited pull system.

Central to the definition of Kanban is the concept of flow. Flow is the movement of value throughout the product development system. Kanban optimizes flow by improving the overall efficiency, effectiveness, and predictability of a process.

Scrum is founded on empirical process control theory, or empiricism. Key to empirical process control is the frequency of the transparency, inspection, and adaptation cycle - which we can also describe as the cycle time through the feedback loop.

The four basic metrics of flow that Scrum Teams using Kanban need to track are as follows:

- **Work in Progress (WIP):** The number of work items started but not finished. Note the difference between the WIP metric and the policies a Scrum Team uses to limit WIP. The team can use the WIP metric to provide transparency about their progress towards reducing their WIP and improving their flow.
- **Cycle Time:** The amount of elapsed time between when a work item starts and when a work item finishes.
- **Work Item Age:** The amount of time between when a work item started and the current time. This applies only to items that are still in progress.
- **Throughput:** The number of work items finished per unit of time.

Littles Law - The Key to Governing Flow: Average cycle time = average work in progress / average throughput

Scrum Teams can achieve flow optimization by using the following four practices:

1. - Visualization of the workflow
   - Limiting Work in Progress (WIP)
   - Active management of work items in progress
   - Inspecting and adapting the team’s definition of “Workflow”

The four Kanban practices are enabled by the Scrum Team’s definition of “Workflow” and are as follows:

1. Visualize the workflow (Kanban board)
   1. Defined points at which the Scrum Team considers work to have started and to have finished.
   2. A definition of the work items – the individual units of value (stakeholder value, knowledge value, process improvement value) that are flowing through the Scrum Team’s system (most likely Product Backlog Items (PBIs)).
   3. A definition of the workflow states that the work items flow through from start to finish (of which there must be at least one active state).
   4. Explicit policies about how work flows through each state (which may include items from a Scrum Team’s definition of “Done” and pull policies between stages).
   5. Policies for limiting Work in Progress (WIP).
2. Limiting Work in Progress (WIP)
   1. The primary effect of limiting WIP is that it creates a pull system. It is called a pull system because the team starts work (i.e. pulls) on an item only when clear that it has the capacity to do so. When the WIP drops below the defined limit, that is the signal to start new work. Note this is different from a push system, which demands that work starts on an item whenever it is requested. Limiting WIP helps flow and improves the Scrum Team's self-organization, focus, commitment, and collaboration.
3. Active management of work items in progress
   1. Making sure that work items are only pulled into the workflow at about the same rate that they leave the workflow.
   2. Ensuring work items aren’t left to age unnecessarily.
   3. Responding quickly to blocked or queued work items as well as those that are exceeding the team’s expected cycle time level (See Service Level Expectation – SLE).
      1. The SLE itself has two parts: a period of elapsed days and a probability associated with that period (e.g., 85% of work items should be finished in eight days or less). The SLE should be based on the Scrum Team's historical cycle time, and once calculated, the Scrum Team should make it transparent.
4. Inspecting and adapting the team’s definition of “Workflow”
   1. The Scrum Team uses the existing Scrum events to inspect and adapt its definition of "Workflow”, thereby helping to improve empiricism and optimizing the value the Scrum Team delivers. The following are aspects of the Definition of “Workflow” the Scrum Team might adopt:
      1. Visualization policies – for example, workflow states – either changing the actual workflow or bringing more transparency to an area in which the team wants to inspect and adapt.
      2. How-we-work policies – these can directly address an impediment. For example, adjusting WIP limits and SLEs, changing the batch size or how often items are pulled between states can have a dramatic impact.

**Flow-Based Events**

1. The Sprint
   1. Even in environments where continuous flow is desired/achieved, the Sprint is still a cadence or a regular heartbeat for inspection and adaptation of both product and process.
2. Sprint Planning
   1. A flow-based Sprint Planning meeting uses flow metrics as an aid for developing the Sprint Backlog.
3. Daily Scrum
   1. What work items are blocked and what can the Development Team do to get them unblocked?
   2. What work is flowing slower than expected? What is the Work Item Age of each item in progress? What work items have violated or are about to violate their SLE and what can the Scrum Team do to get that work completed?
   3. Are there any factors that may impact the Scrum Team’s ability to complete work today that are not represented on the board?
   4. Have we learned anything new that might change what the Scrum Team has planned to work on next?
   5. Have we broken our WIP limit? And what can we do to ensure we can complete the work in progress?
4. Sprint Review
   1. Inspecting Kanban flow metrics as part of the review can create opportunities for new conversations about monitoring progress towards a goal. Reviewing Throughput can provide additional information when the Product Owner discusses likely delivery dates.
5. Sprint Retrospective
   1. A flow-based Sprint Retrospective adds the inspection of flow metrics and analytics to help determine what improvements the Scrum Team can make to its processes. The Scrum Team using Kanban also inspects and adapts the definition of “Workflow” to optimize the flow in the next Sprint. Using a cumulative flow diagram to visualize a Scrum Team’s WIP, average approximate Cycle Time and average Throughput can be valuable.
6. Increment
   1. Scrum’s empiricism encourages the creation of multiple releasable increments during the Sprint to enable fast inspect and adapt feedback loops. Kanban helps manage the flow of these feedback loops more explicitly and allows the Scrum Team to identify bottlenecks, constraints, and impediments for faster, more continuous delivery of value.

**Endnote**

Scrum is not a process or technique. It is a framework within which people can address complex adaptive problems while productively and creatively delivering products of the highest possible value. As *The Scrum Guide* points out, it functions well as a container for other techniques, methodologies, and practices. Kanban's hyperfocus on transparency, visualization, and flow maximizes feedback, empiricism, and ultimately the delivery of value.



------

## Study Notes:

Work Item Ageing:

While in some cases observing old age across multiple items in a certain area of the workflow can help identify bottlenecks, the main role of the Work Item Age metric is to identify specific items that are struggling and require attention. Bottlenecks/systemic constraints are typically identified by looking at the queues on the board as well as charts like the Cumulative Flow Diagram.

Throughput:

When planning a sprint our main interest is to figure out how many backlog items to pull into the Sprint. Throughput of previous Sprints is the most useful in figuring this out. An advanced technique would be to use Monte Carlo simulation using this throughput data in order to figure out confidence-levels for various amounts of items in the Sprint Backlog.

Feedback Loops:

Work Item Age is a leading indicator for the length of the Scrum Team’s feedback loop for that (in progress) item. If an item is aging quite a bit it is certainly an indication that it’s cycle time will be high. Cycle time throughout the team’s definition of Workflow can also be considered the length of the team’s feedback loop.

[Leading vs Lagging Indicators](https://www.agile42.com/en/blog/2018/11/08/leading-and-lagging-indicators-right-way-measure-performance/#:~:text=A%20leading%20indicator%20is%20a,only%20record%20what%20has%20happened.):

Cycle time is a lagging indicator for the length of the Scrum Team’s feedback loop for a product backlog item. You only know the cycle time after the PBI reached the end of the team’s definition of Workflow. You can only measure cycle time by looking at historical data.  It is an indicator and point of reference but should be used carefully when predicting the future. A Service Level Expectation (SLE) is based on cycle time scatter plot percentile lines.

"A lagging indicator without a leading indicator means that you lack clarity on how an outcome will be achieved and miss early warnings on whether or not you are moving towards your strategic goal. Likewise, a leading indicator without a lagging indicator means you lack confirmation on whether or not you are indeed achieving your end goal."

In a Scrum context: https://www.leadingagile.com/2018/02/leading-lagging-indicators/

Tasks vs value limit:

In a flow-based system, the number of tasks is not necessarily limited, rather the amount of value-generating work items is limited.

Team Service Level Expectation (SLE):

SLE CAN be used in Sprint Planning to provide PO and stakeholders with an idea towards the service level that can be expected from the team. That doesn’t include providing a specific date for each PBI in the SBL. The SLE enables the Development Team to forecast a finished date at a certain confidence level once the item has been started.