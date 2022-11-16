# Topic: Kanban

**Author**: Dhvani Kotak

**QAs Total**: 3

---

## Q1: What is the difference between project management and product development? And why it is important to understand as a Manager? 
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
