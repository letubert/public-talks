# Lit review

## Resources

 - [cheat sheet](cheat_sheet/scrum_cheat_sheet.md)
 - Agile quick reference book
 - Retro book
 - [Atlassian Retro playbook](https://www.atlassian.com/team-playbook/plays/retrospective)

# Outline

 - Intro / Why scrum
 - What is scrum?
 - Cheat sheet

Follow up blog post:

 - Roles, Meetings & artifacts

# Draft

## Title

Project Management, for Data Science

## Content

Managing Data Science projects is a unique opportunity. Data engineering and modeling can be more iterative and open ended than most other realms of software engineering, and variable data quality can cause huge changes in the level of effort necessary to train a model. 

This begs the question: 'How do I keep Data Science projects rolling?'. In my experience delivering fraud, cyber security and process automation projects at a Fortune 100 company, I've found Scrum to be an invaluable tool for scoping and delivering software products. It's also paradigm shift for many Data Scientists, so let's dive a bit deeper into what Scrum is, and how to make it work for you. 

### What is Scrum?

Scrum is a set of roles, meetings and artifacts which allow teams to work happily and effectively. This paradigm has been developed and optimized by companies like Google, Tesla, Apple and Salesforce  to:

 - Minimize meeting time
 - Regularize workload
 - Keep projects tightly tied to customer need

As [many](https://www.youtube.com/watch?v=9TycLR0TqFA) [great](https://www.atlassian.com/agile/scrum) [introductions](https://www.scrum.org/resources/introduction-scrum) to Scrum are available, I'll focus instead on the high level goals of the paradigm. 

A core principle of scrum is to quickly build a product, identify feedback, and iterate on the product. This avoids 
building needless features ([clippy](https://en.wikipedia.org/wiki/Office_Assistant)), or getting to attached to an inefficient approach. 

Additionally, the atomic unit of time in scrum is a sprint (usually 1, 2, 3 or 4 weeks). This atomic unit of time allows teams to iterate rapidly, minimize meetings, and still have regular time to work through items that are slowing the team down. During each sprint a team will:

 - Produce an atomic, documented and integrate-able unit of work
 - Hold each of one planning meeting and one recap meeting

Let's dive deeper, and look at how to make scrum work for you. 

### Customizing the scrum method

Scrum is a paradigm that has been found helpful at many companies, but the dirty secret is that each of these shops have iterated on and customized the Scrum paradigm for their domain.

While no two teams are the same, there are a few tips and tricks that I've found helpful for running scrum on Data Science teams. 


Start with a bang

Give the team context. Let them know why your organization is investing Scrum, the benefits of Scrum, and how long you expect the learning curve to be

 - Yes: Have a kick off meeting, and let people know that there will be a learning curve.
 - No: Expect that the team will immediately 'get it', or that they will be as productive while learning a new project management style


Make milestones tangible

Data Science is often an interative process, with unknown data issues lurking at every step. This is an opportunity to focus on tasks, rather than results when laying out milestones. 

 - Yes: Create tangible milestones, such as `train an baseline model`.
 - No: Define milestones with large possible time range, such as `train a model with .98 test AUC`


Explicitly address data quality

Variable data quality is an issue that is unique to Data Science, and doesn't effect other reals of Software Engineering in quite the same way. It's helpful to allocate a bit of extra effort to adress this. 

 - Yes: Create tasks specific to data QA, and building POC models to gain domain experience, such as `Evaluate schema and nulls of sales data set`, or `build a prototype transformation pipeline, to inform final pipeline design`
 - No: Roll data QA into other tasks, such as `Gain access to data set *and* build baseline model`

Communicate uncertainty

Additionally, 
