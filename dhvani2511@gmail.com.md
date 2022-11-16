# Topic: Kanban

**Author**: Dhvani Kotak

**QAs Total**: 3


---
## Q1: What are the steps to implement Kanban in your organization? 
**Difficulty:** `Junior`

**Source:**
https://www.pmi.org/learning/library/integrating-agile-methodology-waterfall-environment-6311

**Answer:**

1. **Understand the Kanban and its need** - 
The first step is you understand what is Kanban and what is not. Also, make sure you really need this in your organization and how it fits. You should be aware with the limitations of Kanban and terms like WIP limits, swimlanes etc. 

2. **Map and Visualise your workflow** -
 Map your current work flow to deliver products, from todo to done. Each column represents a step for adding value to a unit of work. You can also add columns to represent Buffer or neccessary wait time in between tasks.  
Check your recently completed task with the board and compare that if it moves smoothly in all the columns or you need updates in workflow. 

3. **Apply WIP Constraints** - 
 In kanban, it is important you decide the number of tasks for an individual column at a time. Any new tasks can not be moved to the column until you clear the previous one. 
More tasks in one column will create chaos. 
This is the most easy and powerful practice. 

4. **Make Policies Explicit**
 Define classes like "fixed date", "Standard (FIFO)" , Expedite. Idea behind scheduling this is to avoid delays due to high cost-of-delay items. If we follow FIFO for all, the board will be stuck and low cost-of-delay items will not be able to move up. 

5. **Optimize using scientific method**
   1. Declare a hypothesis about how a change to board will result in measurable outcome
   2. Make the change and allow the team to use the board for a period of time. 
   3. Measure whether it actually improved performance and change it back if it doesn't work.

----- 

## Q2: What is the difference between project management and product development? And why it is important to understand as a Manager? 
**Difficulty:** `Mid`

**Source:**
https://www.pmi.org/learning/library/integrating-agile-methodology-waterfall-environment-6311

**Answer:**
As a manager, it is very much important to understand that what type of problem you are solving. Based on the type of problem, we should decide the method and processes we should use in this particular case. 
Product management is concerned with the life of the product; from conception, through development, and eventually to discontinuation. A project is about the creation of something, but when something is created, the project is done. Projects are not concerned with the ongoing improvement or enhancement of a product over the entire lifecycle of that product. So, based on the problem we should decide if we should go with Agile or Waterfall or a blend of it. 

Projects manage the triple constraint: scope, schedule, and budget (sometimes people throw quality and/or resources in there too). Product management is concerned about these things as well, but they are concepts that are more fluid.For example, budgets are a renewable resource (every year there is a new budget). The schedule is a perpetual timeline, and the scope is an endless roadmap of features, releases, and new products.If we run out of money for development on a product, as long as that product is producing value for the customer and the company, then it is likely that next year there will be more money for the product owner to spend to implement the features that weren’t implemented the previous year. Not so for projects, when the money is gone it is gone. Similarly, the schedule for product management is more fluid than on projects. Projects are often concerned with making timelines. By this, project managers mean, meeting their milestones and ending the project on time. Products are also concerned about making timelines and meeting their milestones but not about ending, because product development is more about enhancing the next version.

---

## Q2: How do you deal with _bugs_ or mistakes in Kanban? Would you move items back on a board?

**Difficulty**: `Senior`

**Source:**

https://pm.stackexchange.com/questions/3935/kanban-moving-items-back-or-how-do-you-manage-mistakes

**Details**:

Given that you have a feature tracking through your Kanban board, the dev marks it done, it's pulled into QA, and the dev pulls in new work. QA fails the item.

Now what? Would you move the item back to the Dev stage? What will you do if you can't move it back into the dev stream as it's full?

**Answer:**

My first advice would be to treat your QA stage as the one **covering both**: _testing_ and _bug fixing_ which basically renders the problem of moving index cards anywhere irrelevant. Developers work in the QA stage (same as testers) when they are fixing production defects. 

I won't personally **move cards back** as it just adds a lot of hassle. You can have policies that you can violate limits in such situation but chaos introduced isn't worth the value.

Other options to consider might be: 
* You may **"park" features** which didn't pass testing. You may have dedicated subcolumn where you put such features so everyone knows that they require bug-fixing.
* You may just **visualize status of testing**, e.g. testing started, testing passed, testing failed, with additional visual signal and keep the index cards in QA column.
* You may **deal with bugs using additional information radiator**, usually not a full-blown Kanban board. Then, again, you keep the index cards in QA stage but you deal with bugs independently.
