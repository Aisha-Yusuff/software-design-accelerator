# Session 2: Software Development Life Cycle & Methodologies - Thursday 6th October 2022

**LEARNING OBJECTIVES**

1. To understand the Software Development Life Cycle (SDLC)
1. To understand agile software development

## **What is Software Development?**

The process of conceiving, specifying, designing, programming, documenting, testing and bug fixing involved in creating and maintaining applications, frameworks or other software components.

## **Software Development Lifecycle - SDLC**

- Defined processes for creating high-quality software.
- Development teams use the SDLC to produce software and systems in a systematic and cost-effective way.

1. Planning
2. Analysis
3. Design
4. Implementation
5. Testing and Integration
6. Maintenance

Benefits of SDLC

- Lower costs
- Improved quality
- Shorten timelines
- Help developers understand the project scope

In this course, we will focus on 3 (Design), 4 (Implementation) and 5a (Testing).

## **SDLC Methodologies**

- To manage the level of complexity when designing and creating system a number of SDLC models/methodoliges have been developed, such as:

- **Waterfall** - distinct, sequential phases, only start the next phase when current phase has been completed. Work in a linear way to achieve a set goal, more traditional approach.

  - Disadvantages - no working software produced until the late in the life cycle. Difficult to measure progress. Not suitable for projects with moderate-to-high risk of changing. Adjusting scope during the lifecycle can end a project. Integration is done as a "big-bang".

- **Agile** - most recent, iterative approach, allows teams to deliver value to their customers faster. This model believes that every project needs to be handled differently and the existing method need to be tailored to the projects requirements.

  - Advantages - constantly evaluating your plan allows teams to respond and adapt to change quickly, encourages teamwork, self-organisation and accountability.

**Agile manifesto** - not a rigid framework but a mindset for development, allows you to interpret it for your team.

The 12 principles of the manifesto can be summarised into 4 values

- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiations
- Responding to change over following a plan

A sprint is a set of time that you can evaluate your plan and keep a regular cadence within a team.

Agile vs Waterfall diagram - (Slide 21) - https://members.codingblackfemales.com/topic/session-2-software-development-life-cycle-methodologies/

## **Agile Frameworks**

- **Kanban**
  A continuous, fluid methodologies.
  Agile project management tool to help visualise work and limiting the work in progress to maximise work flow.
  A Japanese term _"visual signal"_
  Kanban board with columns - Backlog, To Do, Ongoing, Done and Blocked.

- **Scrum**
  The concept of basis things around short structured cycles called "Sprints".
  Sprint - It is usually 2 - 4 weeks long.
  Refinement session - what can we achieve in the next two weeks?

  Features a series of events:

  - Sprint Planing : Determine the sprint goal and create backlog - work to be completed
  - Daily Scrum / Standup : Short Daily meeting, usually 15mins, what did you do yesterday? What are you working on today? Do you have any blockers?
  - Sprint Review: Demo of the work completed during the sprint in front of the whole team, stakeholders and customer facing teams. Stakeholders ask questions and offer feedback - any iterations that need to be made and will happen in the next sprint.
  - Retrospective : What went well and what didn't go well? The aim is to find things that are working and what needs to be improved and changed in the next sprint.

  Roles:

  - Product owner - represents the "customer", most knowledgeable person on who we are building for and able to translate that to the development team. Break down the stakeholder ideas and goals into deliverables.
  - Development Team - works on the project day-to-day and actively participate within the sprint. Responsible for delivering code, communicating updates and issues.
  - Scrum Lead - Keep an overview of how things are going and help the team to get unstuck and seek ways to improve collaboration and the process.

- **XP (Extreme Programming)**
  Designed to produce higher quality software and higher quality of life. How? Frequent releases with short development life cycles.

  The most specific agile framework due to engineering practices such as:

  - Pair programming : 2 programmers work together on one task, improve code quality due to. Different types: Driver / Navigator, Ping Pong, Backseat, Unstructured, Navigator and Remote.
  - Extensive code reviews
  - TDD - make sure unit testing all the code

    Roles:

    - Tracker : assigned to talk to each programmer once or twice per week, to ask the person about progress and listen and suggest
    - Coach: Chief Architect of a project.
    - Manager: Between T and C, schedule and attend team
    - Doomsayer: More of a personality trait then a role. They mention the pitfalls, bugs, and doubt of the project.

    Advice: "Start with scrum and then invent your own version of XP depending on what your team needs"
    How? By asking questions - Would these bugs have happened if we were doing TDD? Would we notice those issues earlier if we were pairing?

## Legacy Code Projects

- Existing code
- A project that's difficult or painful to maintain. But approaching them with curiosity and patience will help gain an understanding of how they behave over time.

**What are the main challenges?**

- Not made using agile so will need a lot of people to manage
- Lack of documentation with not enough comments
- Team effort for people to work with it and understand it
- Expensive to maintain
- Readability - hard to understand
- High risk because it can have unplanned outcomes and unknown behaviour
- Lack of tests
- Poor process - could have duplication of work, lack of knowledge and good teamwork because it was made using waterfall model
- Technical Debt - work that still needs to be completed after a piece of code has been released.

**Resolutions**

- Include refactoring while developing new work
  eg. In our sprint 80% of our time will be used for .. and 20% used to tackle the technical debt in our backlog
- Reverse TDD helps remove unknown behaviour - characterisation testing
- Improve process using agile methodologies which encourage collaboration and regular release cycles.
- "Leave code better than they found it" Adding unit tests to provide safety to the code, this allows additional work to be done to refactor legacy code

Advice

- Communication is key
- Communicate technical issues with a development team and explain concepts on a higher level to clients or other stakeholders.
- Asking good questions help you understand how systems interact with each other?

---

COURSE PROJECT

- Build a Recipe API
- Support CRUD operations
- Allows a user to:
- Create a new recipe
- Read (retrieve) all existing recipes
- Update a recipe
- Delete a recipe

REQUIREMENTS:

- JSON Objects
- HTTP protocols - GET, POST, PUT, DELETE
- Local Memory
- A recipe should have:
  - ID
  - Name
  - Ingredients
    - Name
    - Quantity
  - Instructions
  - Image

Stretch goals

- Store recipes in a db
- Stub out API calls in test
- Deploy to Heroku
- Customise the UI

- Languages:
  Java - Backend - unit tests
  React - Frontend

  Homework: Research CRUD, HTTP, Existing Recipe Applications
  Understand the requirements of the projects
  Be able to start thinking about hot wo design your project when we move into Software Design
