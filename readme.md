# MyWebClass.Org Project - Agile Documentation Assignment

## Overview

For this assignment, you need to develop an initial draft of project documentation based on the principles of the [Agile
Manifesto - MUST READ](https://agilemanifesto.org/principles.html)
and [Lean - READ ALL THE  PARTS 1-7 THAT ARE LINKED ON THE LEFT](https://www.planview.com/resources/guide/lean-principles-101/).
The purpose of this assignment is to help you
develop the mindset required take an idea and turn it into a product that people value. This is an open ended assignment
meaning that you need to think and create and not just follow a set of instructions. You are the one creating
instructions for yourself and the development team that you will be part of and/or possibly leading in the future. For
this assignment, you should use ChatGPT as much as possible to help you write good documentation. It is very good at
taking what you mean to say and turning into this type of documentation.
# Videos
* **[Agile Lean Part 1](https://youtu.be/e4FLisvf7vg)**
* **[Agile Lean Part 2](https://youtu.be/KIxQaWsG3vk)**

## Scope of the exercise

In the spirit of Lean and to start our project off using the "pull" approach to develompent we will only focus on the
following goal. MyWebClass is a website and we will need a development team that needs to work together in parallel
meaning that we eventually need to produce various content to support the objectives of the site. In order for this to
happen we need to create a basic web template that can be found using a search engine, addresses any legal requirements
that are relevant to our project, allows us to legally use Google Analytics to measure user behaviour on the site, and
passes [w3c validation](https://validator.w3.org), [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/), [GDPR Scanner](https://2gdpr.com).

In addition to planning the initial 0.1.0 release of the website template we also need a plan setup a DevOps process
that support the development of the project.

In general, you can expect that you have 3 major parts to your plan at this stage:

1. Basic Project Documentation and Project Management
2. DevOps
3. MyWebClass.org base website template with all technical and legal requirements satisfied to use Google Analytics and
   be appropriately listed in a search engine by implementing the basic on page SEO requirements.

To assist you with this project, I've included ALL of the code for required for a web page in
the [src/index.html](src/index.html) file and included comments as to why that line is in there, so that you can write a
user story and eventually a test for it.

## Things to consider:

1. Lean and Agile are both ideas that are complementary; however, neither is prescriptive in their implementation. Your
   project plan should be inspired by these ideas; however, how you implement them should be tailored to fit the
   particular project. Remember Lean's core idea is build, measure, and learn to create continuous improvement. Agile is
   essentially a way to organize within a software development team to make the development process sustainable and
   effective at producing working software with the least amount of waste.
2. In order to facilitate communication and provide a structure for project planning you must organize your project into
   themes, initiative, epics, user stories, and tasks, which are terms used within agile.
   **Themes:**
    * Themes are high-level categories of work that align with an organization's strategic objectives. They help to
      define and communicate the focus areas for a project or product. Themes can be used to organize and prioritize
      work, guide decision-making, and ensure that efforts are aligned with business goals.
      **Initiatives:**
    * Initiatives are a collection of related projects and activities that are aligned with a common goal or objective.
      They help to break down larger goals into smaller, manageable pieces. Initiatives are usually larger in scope than
      epics and are typically managed by a program or portfolio management team.
      **Epics:**
    * Epics are large pieces of work that can be broken down into smaller, more manageable pieces (i.e., user stories).
      They are larger in scope than user stories and often require coordination across multiple teams. Epics typically
      represent a major business or technical challenge that needs to be addressed.
      **User Stories:**
    * User stories are short, simple descriptions of a feature or piece of functionality from the perspective of a user
      or customer. They are used to communicate requirements and prioritize work. User stories are typically small in
      scope and can be completed in a single sprint (i.e., a short, time-boxed period of work). They help to ensure that
      development efforts are focused on delivering value to the end user.
      **Tasks:**
    * Agile Tasks:
    * Tasks are the smallest units of work in Agile development. They are specific, actionable items that need to be
      completed in order to deliver a user story. Tasks are usually estimated in hours and are used to track progress
      and identify obstacles. They are typically managed by individual team members and are part of the team's daily
      work.
3. Our goal is to develop a "pull" process for the development of the MyWebClass product and minimize or eliminate the
   amount of "push" in the MyWebClass.org
   project.  [Read this about the difference between push and pull to understand how these concepts relate to product development.](documentation/reading/push_vs_pull.md)
4. Every theme, initiative, epic, user story, and task needs a way to test that it is working. You can specify automated
   testing i.e. pytest for unit testing, Playwright for end to end testing, or manual testing. You may need to combine
   both manual and automated testing for themes, epics, and initiatives; however, tasks and user stories should us some
   type of automated testing as much as possible.
5. Every theme, initiative, epic, user story, and task should identify how you will measure it's effectiveness
   quantitatively. If you can't think of one now just put something in that might work in the future and this can be
   improved as things become more clear. YOu need to consider that to implement lean you have to build it, MEASURE IT,
   and LEARN, its not necessary or expected for something to be perfect, it is expected that any resources invested in
   something have some methodology to evaluate performance, and provide feedback for continuous improvement.

## Grading

For this assignment you will need to find a partner to review your project documentation and you will need to review
their documentation. Compare both of your project plans and create a list of the changes you decide to implement and
file them as issues on your repository. Resolve the issues using branches and merge the branch into main, so that you
have the best version of your project plan that combines the best ideas of you and your partner. Do not do the first
draft of the plan together, design it yourself and you should review your partners plan, and they should review yours.  Practice using the GitHub comment and review tool to review the agile tasks.  [Watch this video on how to do a code review using GitHUb](https://www.youtube.com/watch?v=8fx-EaOUK2E)

### Grading Rubric

1. 25 Points for having at least 5 comments on your code by your partner that result in 5 issues being created and  resolved.
2. 50 Points effective and sensible organization of your project that applies Agile and Lean ideas.   Use ChatGPT to help you with the writing, so that its written with a professional business tone and vocabulary. 
3. 25 Points for demonstrating that you understand that each activity needs to be measured and that each task needs some combination of manual and automated testing.

### Submission
Once you have the best version of your project plan after comparing it and resoling the issues turn the plan into Canvas.


## Overview

Looking to learn modern software development technologies and processes in a hands-on learning environment? Look no
further than MyWebClass! Our platform provides an integrated learning experience that contextualizes technology with
business processes to provide realistic scenarios for students to learn technology in a hands-on real world environment.

## Agile Project Documentation

### Templates - Modify these as necessary

* [Theme Template](documentation/templates/theme/theme_template.md)
* [Initiative Template](documentation/templates/theme/initiatives/initiative_template.md)
* [Epic Template](documentation/templates/theme/initiatives/epics/epic_template.md)
* [User Story](documentation/templates/theme/initiatives/epics/stories/story_template.md)
* [Task Template](documentation/templates/theme/initiatives/epics/stories/tasks/task_template.md)

## My Rough Draft

Here is an example of how I initially break down a project; however, I intend to change this in the near future, so that
i organize my themes by business activity instead of release schedule. Examples of these
themes include the DevOps and Search Engine Themes.

In practice, it is commonplace to adapt project documentation to meet evolving project needs early on in the process.
Therefore, please do not feel obligated to follow my approach. Instead, view it as an example of how to develop your own
documentation, based on your preferred methodology for breaking down the problem. Should you find that it does not meet
your needs, it can be adjusted, given that we are still in the early stages of the project.

At this juncture, the efficacy of the documentation is measured by how well it enables us to manage the project. We will
review this effectiveness before the next iteration of the project.

# Your  plan should replace the content below

[Project Setup](documentation/theme_1/theme_project_setup.md)
### Themes
1. Content creation and curation
2. Website development and deployment
3. Privacy & Legal Requirements 
4. Analytics and data collection
5. Testing

### Initiatives
1. Develop and publish high-quality content on Docker, containerization, and GitHub
2. Build a user-friendly website with intuitive navigation and responsive design
3. Collect and analyze data on user behavior to improve website performance
4. Ensure website functionality meets user requirements through comprehensive testing

### Epics
1. Create and curate Docker and GitHub content
2. Set up a development environment for website changes and improvements
3. Develop website structure and layout
4. Customize website template with branding and visual elements
5. Test site functionality using pytest & Playwright
6. Deploy website updates and improvements in a timely and efficient manner
7. Set up and configure Google Analytics
8. Monitor website traffic and user behavior
9. Analyze Google Analytics data

### User Stories
1. As a user, I want to read informative blog posts and tutorials on Docker and containerization
2. As a user, I want to read informative blog posts and tutorials on GitHub
3. As a user, I want to easily navigate the website to find the information I need
4. As a user, I want the website to look visually appealing and reflect the branding of the company
5. As a user, I want the website to have features that enhance my user experience, such as a search bar or interactive elements
6. As a user, I want to be able to understand how my data is collected, stored, and used by the website so that I can make informed decisions about using the website
7. As a website owner, I want to set up Google Analytics to collect data on user behavior
8. As a website owner, I want to monitor website traffic and user behavior to identify areas for improvement
9. As a website owner, I want to analyze Google Analytics data to make data-driven decisions to improve website performance
10. As a website owner, I want to ensure website functionality meets user requirements through comprehensive testing

### Tasks
#### Content creation and curation
- Write blog posts and tutorials on Docker and containerization
- Write blog posts and tutorials on GitHub
- Find and curate external resources on Docker, containerization, and GitHub

#### Website development and deployment
- Set up development environment with necessary tools (e.g. text editor, version control)
- Choose a website template that meets the needs of the website
- Customize the website template with branding and visual elements
- Develop website structure and layout using HTML and CSS
- Implement website features using JavaScript and/or third-party plugins
- Write automated tests for website functionality using pytest
- Perform manual testing to ensure website functionality meets user requirements
- Deploy website to production environment using a web hosting service

#### Analytics and data collection
- Create a Google Analytics account and set up tracking code on website
- Define website goals and conversion events in Google Analytics
- Monitor website traffic and user behavior using Google Analytics reports
- Analyze Google Analytics data to identify user needs and preferences, and make data-driven decisions to improve website performance.

#### Testing
- Write automated tests for website functionality using pytest
- Perform manual testing to ensure website functionality meets user requirements.


## Release Schedule

| Release Version | Release Date | Features |
|-----------------|--------------|----------|
| 0.1.x           | TBD          | TBD      |

