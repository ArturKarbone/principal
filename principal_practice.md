### #1 Think and discuss (20 min)

1. Who is the customer in your software development process?

*In large organizations, there could be multiple customers (external and internal). The goal is to identify each group of customers, understand the process “from idea to cash” for each group, and continuously reduce the average lead time.*

2. When the clock starts and stops in your process? Use a sheet of paper to sketch the whole process “from idea to cash”.

*In development, the clock starts when a customer places an order. The clock stops when the customer’s problem is solved. What this means will differ from one organization to the next, but the process always starts and ends with a customer.* 

*Pro Tip: customers do not care about other requests or how busy you are. They care about how long it takes for you to act on their request. Look at the whole process from the customers' perspective.*

Answer the following questions:

3. What is your average lead time (CT)?
4. How does CT impact customers' business? 
5. What happens when CT is unsatisfactory high? 
6. How does CT impact our reputation?
7. Do you see opportunity for reducing CT? How?
8. Do you agree that devs who can reduce CT are extremely valuable? Why?

Share your results with teammates. Are there any process similarities? What are the differences? What can you learn from teammates?

### #2 Teamwork (30 min)

In a team, mark activities that reduce WiP with ❤️ and activities that increase WiP with ❌. Make sure that you understand each activity, why and how particular activity influences WiP. 

1. Multitasking
2. Monotasking
3. Pair Programming
4. Mob Programming
5. Starting working on a new feature, while testing is in progress
6. Helping testers complete testing faster (pair testing)
7. Working closely with testers before the feature is completely developed
8. Teams without testers
9. Expert and overspecialization in the team (backend/frontend/mobile/db)
10. T-shaped people (generalizing specialists) in the team
11. People working on the same codebase, but in different time zones
12. Developers thinking that “done” means “coded”
13. Testers thinking that “done” means “tested”
14. People with completely different values and interests
15. Continuous Integration
16. QA or “DevOps” is a separate department with different incentives
17. Office / table layout does not enable zero-friction pairing / mobbing
18. The Principal asks everybody to reduce WiP, but works alone
19. Shotgun refactoring (shotgun surgery)
20. Developing a feature in baby steps and keeping the code on your laptop green
21. The team does not have pairing experience and The Principal is not mentoring
22. Decoupling deployment from release
23. Fear of saying *no* / accepting lots of work to *please* customer(s)
24. The Principal is too busy to explain Little's Law to the team
25. Jerks in the team (knowledge refrigerators)
26. Untracked / Invisible work
27. Unresolved conflicts in the team
28. Lack of a common goal
29. Isolation / work on long-living feature branches
30. Daily standups
31. Insecure work environment
32. "Teammates" working on different and unrelated projects (resource sharing)
33. No WiP limits (pushing of work)
34. Strict WiP limits (pulling of work)
35. Dependencies on people, teams, 3rd-party
36. Long-running tests
37. Waiting for code review (asynchronous code review)
38. Code review is the first priority (synchronous code review)
39. Waiting for clarification, approvals
40. Unplanned work (Critical Bug found on Production)

In your project, which activities contribute to increased WiP? List three major activities. Share it with the team and discuss how to improve the situation.

### #3 Teamwork (30 min)

In a team, classify each waste from the list using *PONDR*. Make sure that you understand each waste and the cause(s) of each waste.

1. **P**artially Done Work
2. **O**verproduction
3. **N**on-value added activities
4. **D**elays / Waiting
5. **R**ework

Wastes:

1. Cancelled or Postponed tasks
2. Setup Time / Onboarding
3. Suffering from high discovery cost due to spaghetti code
5. Work that is under development
6. Work that is deployed, but not yet released
7. Extra / unused features “for the future”
8. Submitting time sheets
9. Putting in-process defects into tracking system
10. Re-implementing solution due to misunderstood requirements
11. Re-learning (answering the same questions, discussing the same things)
12. Unplanned work (expediting)
13. Focusing on 100% test coverage and forgetting about MTTR / MTTD
14. Building a wrong test pyramid (Ice-Cream Cone vs. Eye of Providence)
15. Code that we wrote “for the future”, before it's actually required
16. Refactoring functionality that does not change
17. Doing routine tasks manually
17. Trying to maximize output, not outcome (delivering features with zero impact)
18. Unplanned work (downtime)
19. Team members shared across projects
20. Optimizing part of the process that is not a bottleneck
21. Gathering in-process metrics in the sake of reporting
22. Waiting for the code review
23. Non-automous teams
24. Coding more stuff while “in testing” work is piling up
25. Writing more user stories than needed for the next few Sprints
26. Maintaining a large backlog with work that won't be done anytime soon
27. Accidental complexity
28. Adoping a technology and tools because they are trendy (Marchitecture)
29. Failing too late in the pipeline / fixing escaped defects
30. Overitulized workforce
31. Handoffs (inability to complete the work independently)
32. Meetings with low ROI
33. Impasse
34. Long-running tests (long = 1 coffee roundtrip)
35. Dealing with merge conflicts
36. Prefering flexible and abstract code over simple and direct code
37. Making a wrong *write vs. rent* decisions, *on-prem vs. SaaS*
38. Writing software when Excel spreadsheet is good enough
39. Building things right before you know what is the right thing
40. Choosing MVP over MVE / Fake Door Testing

In your project, which wastes are the most painful? List three major wastes. Share it with the team and discuss how to improve the situation.