# The Kanban Guide for Scrum Teams

See: https://www.scrum.org/resources/kanban-guide-scrum-teams

Kanban (n): a strategy for optimizing the flow of value through a process that uses a visual, work-in-progress limited pull system.

Central to the definition of Kanban is the concept of flow. Flow is the movement of value throughout the product development system. Kanban optimizes flow by improving the overall efficiency, effectiveness, and predictability of a process.

Scrum is founded on empirical process control theory, or empiricism. Key to empirical process control is the frequency of the transparency, inspection, and adaptation cycle - which we can also describe as the cycle time through the feedback loop.

The <u>four basic metrics of flow</u> that Scrum Teams using Kanban need to track are as follows:

- **Work in Progress (WIP):** The number of work items started but not finished. Note the difference between the WIP metric and the policies a Scrum Team uses to limit WIP. The team can use the WIP metric to provide transparency about their progress towards reducing their WIP and improving their flow.
- **Cycle Time/Lead time**: The amount of elapsed time between when a work item starts and when a work item finishes.
- **Work Item Age:** The amount of time between when a work item started and the current time. This applies only to items that are still in progress.
- **Throughput:** The number of work items finished per unit of time.

Littles Law - The Key to Governing Flow: Average cycle time = average work in progress / average throughput

Scrum Teams can achieve flow optimization by using the following four practices:

1. - **Visualization of the workflow**
   - **Limiting Work in Progress (WIP)**
   - **Active management of work items in progress**
   - **Inspecting and adapting the team’s definition of “Workflow”**

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

## Study Notes from practice tests:

**Work Item Ageing**

While in some cases observing old age across multiple items in a certain area of the workflow can help identify bottlenecks, the main role of the Work Item Age metric is to identify specific items that are struggling and require attention. Bottlenecks/systemic constraints are typically identified by looking at the queues on the board as well as charts like the Cumulative Flow Diagram.

**Throughput**

When planning a sprint our main interest is to figure out how many backlog items to pull into the Sprint. The throughput of previous Sprints is the most useful in figuring this out. An advanced technique would be to use Monte Carlo simulation using this throughput data in order to figure out confidence-levels for various amounts of items in the Sprint Backlog.

**Feedback Loops**

Work Item Age is a leading indicator for the length of the Scrum Team’s feedback loop for that (in progress) item. If an item is aging quite a bit it is certainly an indication that it’s cycle time will be high. Cycle time throughout the team’s definition of Workflow can also be considered the length of the team’s feedback loop.

[Leading vs Lagging Indicators](https://www.agile42.com/en/blog/2018/11/08/leading-and-lagging-indicators-right-way-measure-performance/#:~:text=A%20leading%20indicator%20is%20a,only%20record%20what%20has%20happened.)

Cycle time is a lagging indicator for the length of the Scrum Team’s feedback loop for a product backlog item. You only know the cycle time after the PBI reached the end of the team’s definition of Workflow. You can only measure cycle time by looking at historical data.  It is an indicator and point of reference but should be used carefully when predicting the future. A Service Level Expectation (SLE) is based on cycle time scatter plot percentile lines.

"A lagging indicator without a leading indicator means that you lack clarity on how an outcome will be achieved and miss early warnings on whether or not you are moving towards your strategic goal. Likewise, a leading indicator without a lagging indicator means you lack confirmation on whether or not you are indeed achieving your end goal."

In a Scrum context: https://www.leadingagile.com/2018/02/leading-lagging-indicators/

**Tasks vs Value limit**

In a flow-based system, the number of tasks is not necessarily limited, rather the amount of value-generating work items is limited.

**Team Service Level Expectation (SLE)**

SLE CAN be used in Sprint Planning to provide PO and stakeholders with an idea towards the service level that can be expected from the team. That doesn’t include providing a specific date for each PBI in the SBL. The SLE enables the Development Team to forecast a finished date at a certain confidence level once the item has been started.

------

## Posts and Articles

1. [Understanding the Kanban for Scrum Teams Guide](https://www.scrum.org/resources/blog/understanding-kanban-scrum-teams-guide)

   1. Kanban: Is your sprint a swamp or a river
   2. Only included the 4 main Kanban points because they compliment what a scrum team is already doing. Scrum teams already have a collaborative inspect and adapt experimentation process together with a set of explicit feedback loops they’re using. Advanced concepts not part of the guide because we don’t consider them part of the “Minimally viable set of practices” a Scrum team should focus on when trying to improve their flow.
   3. Advanced Kanban concepts include:
      1. Classes of service
      2. Cost of delay
      3. Flow efficiency 
   4. "I’ve helped Scrum teams achieve an even healthier smoother flow by adding Kanban to their process. I’ve helped Kanban teams accelerate their pace of improvement by adding cadence/rhythm and clarity."

2. [What Scrum Gets Wrong About Kanban and What Kanban Gets Wrong About Scrum](https://www.scrum.org/resources/blog/what-scrum-gets-wrong-about-kanban-and-what-kanban-gets-wrong-about-scrum)

   1. One is not better than the other.
   2. MYTH: Scrum is revolutionary; Kanban is evolutionary.
      1. The concept of limiting work in progress is revolutionary in most organizations.
   3. MYTH: Scrum is for X and Kanban is for X (or Kanban is all about manufacturing)
      1. Although Kanban derived many of its lean concepts from the manufacturing sector, they apply equally as well to complex knowledge work.
   4. MYTH: Kanban doesn't encourage teamwork
      1. What they are missing is Kanban’s key practice of actively managing flow by the team. Combine actively managing flow with the practice of improving collaboratively, and you naturally end up with cross-functional, self-organizing teams of people working together to deliver value. WIP limits encourages individuals to swarm.
   5. MYTH: Scrum’s Sprint Planning Event is a time waste
      1. The intent of the Sprint Planning meeting isn’t to create a detailed Sprint plan, but to instead come together as a team to decide what goal to achieve and to come up with a plan to complete that goal.
   6. MYTH: Sprints constrain flow
      1. "The second misunderstanding is that a Development Team can only work on items specified in Sprint Planning. Nothing in the Scrum Guide stops a team from embarking on new work mid-Sprint as long as it meets two conditions. The first is that <u>the work doesn’t endanger the Sprint Goal</u>. The Development Team is still committed to its delivery. The second is that the team will have a potentially releasable product Increment for the Sprint Review. This means that either the new work will be “Done” by the end of the Sprint or that working on <u>it won’t restrict the team from having a potentially releasable Increment at the end of that Sprint</u>."

3. [A Kanban Primer for Scrum Teams](https://www.scrum.org/resources/blog/kanban-primer-scrum-teams)

   1. Kanban core principals:
      1. Start with what you do now
      2. Agree to pursue incremental, evolutionary change
      3. Respect the current process, roles, responsibilities, and titles
   2. Original core Kanban practices before they striped down for scrum:
      1. Visualize (the work, workflow, and risks to flow/value delivery)
         1. "Visualizing the flow throughout the value stream means we should mainly visualize the flow of Product Backlog items (PBIs) rather than tasks."
      2. Limit WIP (Work in Process)
         1. "WIP limits should be low enough that they introduce pain-- meaning that they push you beyond what you’re comfortable with and used to. You want to channel this pain towards ways of improving the team’s process and policies so that in the future, the flow will be better and the WIP limit will be less painful."
      3. Manage Flow
         1. *..TO BE CONTINUE..*
      4. Make Process Explicit
      5. Implement Feedback Loops
      6. Improve Collaboratively, Evolve Experimentally (using models and the scientific method)

4. [Scrum and Kanban Stronger Together](https://www.scrum.org/resources/blog/scrum-and-kanban-stronger-together)

   1. Because Kanban and Scrum practitioners have broken into separate camps, software teams are missing out on practices that would improve their effectiveness.

5. [4 Key Flow Metrics and how to use them in Scrum's events](https://www.scrum.org/resources/blog/4-key-flow-metrics-and-how-use-them-scrums-events)

   1. These are the 4 key flow metrics that Scrum teams can use to improve their flow:

      1. WIP
         1. Note the difference between WIP and the WIP Limit. The WIP Limit is a policy that the Scrum Team uses as a "constraint" to help them shape the flow of work. The goal of the WIP Limit is to reduce the amount of actual work in process (WIP). The team can use the WIP metric to provide transparency into their progress towards reducing their WIP and improving their flow.
         2. Tool/Report: Cumulative Flow Diagram
      2. Cycle Time
         1. This metric is a lagging indicator of flow. It is available only after an item is actually finished from the workflow perspective (e.g. reached a Done lane on the Kanban board). It is typically used to drive improvement work as well as to be able to establish internal/external expectations as to the team's turnaround time on specific items.
         2. Tool/Report: Cycle Time Scatterplot
      3. Throughput
         1. Note the measurement of throughput is the exact count of work items, without any compensation for item size - which is a major difference between throughput and story-points based velocity.
         2. Tool/Report: Throughput run chart
      4. Work Item Age
         1. Work Item Age complements Cycle Time. If Cycle Time is a lagging indicator only relevant for finished items, Work Item Age is a leading indicator only relevant for non-finished items. The basic idea is to provide transparency to which items are flowing well and which are sort of "stuck" even if not formally blocked.
         2. Look at the overall age but combine it with where the work currently is in the workflow as well as what the teams SLE. Combining all this information can help the team focus on the items that are at the most risk of missing the team's expectations/SLE.
         3. Example:
            1. Let's say a team has an SLE of 16 days with 85% confidence. If one of the cards on their board has an age of 10 days, is that ok? is it a problem? The answer is that it depends. If that card is very close to the end of the workflow it is probably not a problem. If it is very close to the start of the workflow it is probably an indication of a problem that requires attention.
         4. Tool/Report: Aging Work in Progress

   2. Using the flow metrics in Scrum Events

      1. | Metric          | Sprint Planning | Daily Scrum | Retro | Review |
         | --------------- | --------------- | ----------- | ----- | ------ |
         | Cycle Time      |                 |             | Also  | Key    |
         | Throughput      | Key             |             | Key   | Key    |
         | Current WIP     |                 | Key         | Also  | Key    |
         | Work Item Aging | Also            | Key         |       | Also   |

      

6. [Limiting Work in Progress (WIP) in Scrum with Kanban - What? When? Who? How?](https://www.scrum.org/resources/blog/limiting-work-progress-wip-scrum-kanban-what-when-who-how)

   1. Limiting WIP actually aims to reduce and stabilize WIP in order to improve flow and provide predictability.
   2. Limiting WIP is probably even more important than visualizing flow (the board).
   3. The parties involved in the defined workflow would define WIP limits.
   4. Make WIP exceptions in extreme cases rather than change WIP limits.
   5. WIP limits shouldn't be changed on a whim. Create an exception and discussion rather than hide the problem under a policy change. WIP limits SHOULD be changed during the retro but CAN be changed anytime.
   6. WIP limiting can be done in several ways:
      1. Limit the amount of work in progress per person
      2. Per the entire team throughout their workflow
      3. Limit WIP by time (sprint)

7. [Kanban Service Level Expectations and how to use them in Scrum](https://www.scrum.org/resources/blog/kanban-service-level-expectations-and-how-use-them-scrum)

   1. An SLE forecasts how long it should take a given item to flow from start to finish within your workflow. The SLE itself has two parts: a period of elapsed days and a probability associated with that period (e.g., "85% of work items will be finished in 8 days or less" which can also be stated as "8 days with 85% confidence/probability").
   2. We get the SLE from the cycle time scatterplot graph.
   3. Also, SLE's aren't SLA (Service Level Agreements). SLA is a loaded term that means different things in different contexts but generally is an external commitment about the service levels a team will provide. As mentioned an SLE is mainly internally focused.
   4. The term **expectation** is key here. We're not talking about commitments or promises. While it seems like an SLE is mainly serving the team's stakeholders its primary purpose is actually internally focused. The Development Team is using that expectation as a flow transparency, inspection, and adaptation mechanism. The team can start to actually compare active in-flight work to their SLE and look for items that are at risk of missing the SLE.

8. [How an expedite request sunk the Titanic by Daniel Vacanti](https://vimeo.com/239539858)

   1. If you track <u>nothing else</u>, track cycle time for every work item (the date everything starts and the date it finishes).

   2. Predicting when something will be done is determined by cycle time.

   3. The first greatest influence on cycle time is WIP.

   4. The second greatest influence on cycle time is pull policies.

   5. Put cycle time in a histogram and notice the following. Affects of pull policies on cycle time:

   6. | Pull Policy                         | Cycle Time |
      | ----------------------------------- | ---------- |
      | Strict FIFO (no expedites):         | 50 days    |
      | Random queuing:                     | 60 days    |
      | Strict FIFO always one expedite:    | 65 days    |
      | Random queuing always one expedite: | 100 days   |

      Think of your cycle time as a shape and not a number.

   7. FIFO is almost impossible to implement as a pull policy so when you have to choose among multiple items to pull, you should choose the oldest one. 

   8. Tool/Report: Work in progress aging chart

   9. Summary:

      1. Most of the unpredictability in your process is down to poor pull policies.
      2. In general, it is better to finish work already started before starting new work.
      3. Ask yourself: does the work I'm expediting really need to be expedited? Do I even have policies in place on how to decide what to expedite?

9. [My journey with PSK I, and how I passed](https://www.scrum.org/forum/scrum-forum/16795/my-journey-psk-i-and-how-i-passed)
   1. ...

10. [Actionable Metrics for Predictability video](https://vimeo.com/146545310)
   1. ...

## Study Materials

Books: 

- Practical Kanban: From Team Focus to Creating Value by Klaus Leopold
- Agile Project Management with Kanban (Developer Best Practices) by Eric Brechner
- When Will It Be Done by Daniel Vacanti
- Actionable Agile Metrics for Predictability by Daniel Vacanti


Test quizes: 

- Udemy: https://www.udemy.com/course/scrum-with-kanban-psk-i-certification-2019/
- Quiz web app: https://mplaza.training/exam-simulators/psk/

## Terms

ScrumBan: A way to introduce Lean/Kanban flow into a Scrum context – while keeping the core Scrum process intact.

## Certification Test

https://www.scrum.org/professional-scrum-with-kanban-certification

## Tools

Cumulative Flow Diagram (CFD): Band thickness and throughput
   1. Even means input/output are even and flow is good.
   2. If a band on your CFD is continuously narrowing that means that the throughput of the stage it represents is higher than the entry rate. This is a sign that you’ve got more capacity than you really need at this stage and you should relocate it in order to optimize the flow.
   3. Rappidly widening bands means the number of cards that enter the corresponding stage on the Kanban board is higher than the number of assignments that are leaving it. It is a common problem that is usually caused by multitasking and other waste activities that don’t generate value.

The cumulative flow diagram is one of the most advanced analytics for Lean project management.

- It provides a concise visualization of the metrics of flow.
- Shows you how stable your flow is and helps you understand where to focus in order to make your process more predictable.
- Gives you quantitative and qualitative insight into both past and existing problems.