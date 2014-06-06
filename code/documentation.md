# Documentation

High quality research does not only mean to publish meaningful results. It is much more about convincing readers that this result is sound and reproducable.

An accessible documentation of the project that shows how the project was developed, the simulations were performed and analysed and how the paper was written, is very convincing.

Apart from credibility, there are other reasons to keep a documentation of ongoing research projects.
- **backing up**: If you have lost data due to technical issues and have to repeat things or if you took a wrong turn in the project development, a documentation will help you to start afresh from the point were you got lost.
- **taking a break**: after months of interruption, a documentation helps taking up the thread.
- **handing over**: if new people get onto the project or if the project is handed over to someone else, a documentation will help to get started with the work.


## Best practice
What we consider a minimal requirement for projects within CASCADE WP6:
- use version control (recommended: *git*) for code development

Additionally, a project consists of many things which are not documented by version control. This includes reading papers, writing, software tools you use, offline drawings and notes on paper or in paper notebooks, meetings, conferences and important decisions.

We highly recommend to implement the following in your research workflow:
- use version control for manuscript writing
- include a directory *documentation* or *doc* in your project directory that contains:
    - a frequently updated summary of the projects progress including aims and scope of the study, hypotheses, important decisions
    - a list of the most recent code files
-  a logbook to keep track of all other activities in the project.

The logbook could be a simple text file or table that looks like this:


date |                                 note       | reference
------- | ----------------------------------- | ---------------
 02.06.2014 | I read this paper that said "This correlation is significant" | Author 2013 Journal
02.06.2014 | met with Sonia to talk about paper: Figure 1 should be the one showing A affecting B. |
01.06.2014 | edited figure 3: included plot of correlation X~Y | hash: #4a3fd21
... | ... | ...


Avoid redundancies: For instance, the last example is redundand with the information of a *git* commit for version control. But to some extend, this allows syncing the log with the git history.

By keeping track of changes like this, you will be able to reconstruct the path of the project, understand decisions you made earlier and enable others to follow your work.

Of course, documentation is costly in terms of working time and it is competing with the time you spend on the actual research. And the time invested only pays off indirectly or as an insurance if something goes wrong. It is a trade off.

As a rule of thumb, 10--20 minutes each day should be invested in documentation. The better it is included in the daily workflow and computer set-up, the less time it takes.

## Reproducible research

