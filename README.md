# Quality is a way of life  
## Hi there 👋

# A few of my recent accomplishments
* Developed SQA roadmap, including objectives, scope, priorities, standards and policies, establishing QA KPIs that improved project alignment with cross-functional teams.
* Achived a 75% reduction in hot patch delivery time bby implementing sanity test automation.
* Cut legacy test automation failures by 50%, reducing sprint hardening time by 20%.
* Led a team of 20 domestic and international engineers to improve quality by introducing team ownership of testing, peer test reviews, and test automation code reviews.

# Keys to Quality   
## Test Attributes   
1. Idempotent: The test environment should be unchanged once the test complete
2. Independent: The test should run on its own
3. Autonomous: The test should not affect any other test

## Best Practices
1. Use control IDs or other unique locators for UI tests.
2. Work closely with development to keep tests in sync with the code.
3. Keep tests in the same repository when possible to keep them in sync with the application code.
4. Push tests down the triangle when possible. Generally speaking, this list is in order from least to most reliable:   
  a. UI/E2E tests   
  b. API tests   
  c. Contract tests   
  d. Unit tests
5. Maintain clear logging and reporting for quick failure analysis.
6. Never ship code with broken tests.
7. Use data driven tests to cover a broader set of scenarios with test code.

## Code Design
1. Use a modular design which supports easy re-use of code.
2. Keep your test code separate from action code, and separate from app interaction code (UI code). One nice pattern: Page Objects, Action Objects, Test Objects

## Prioritize tests
Suggested priority order:
1. Critical functionality.
2. Commonly used functionality.
3. High Risk functionality.
4. High Visibility functionality.
5. Bug concentrations.
6. Time consuming tests.
7. Data driven tests.
<!--
# What is an Engineering Team Architecture (ETA)  
Successful organziations have a clear understanding of the required individual roles and responsibilities. These responsibilities define an engineering team's processes. While many engineering organizations wish to have as much flexibility as possible (engineering is an art, after all) , there are certain talents required. There are also certain expectations required of one another, often expressed through the organization's processes.
These two, roles and processes (responsibilities), define how the organization will build things, or the organization's Engineering Team Architecture.

## [Faster through better quality](https://qeunit.com/manifesto/?utm_source=mailpoet&utm_medium=email&utm_campaign=you-are-now-following-the-qe-unit_1 )

- 🔭 I’m currently working on  
-- Quality Leadership: Leading my organization to deliver business value faster through improved quality  
-- Team ownership of quality encourages shared testing  
-- Shared testing delivers higher quality earlier in the SDLC  
-- Building quality from the outset eliminates context switching and rework  
- What does this mean for you  
-- Higher performing teams who find greater fulfillment in their work
- How do i do this?  
-- Designing a Definition of Done with the team  
--- When starting a story, we use a Three Amigos meeting, involving Coder, Tester and Product  
--- We outline our story implementation  
--- We decide how we will test each piece of that implementation  
--- We walk away with an outline of what code will look like, what a test plan will look like, and confidence that we're on target to satisify the needs of the business  
-- During the coding phase, we outline as much, or as little, of a test plan as we need  

  
- 🌱 I’m currently learning  
-- Kubernetes  
-- Cloud testing  
-- Continuous Delivery  
-- More about the Cypress framework every day  
-- Functional programming with Javascript and Typescript  
-- Java and Selenium  
- 💬 Ask me about  
-- Shift Left: Building in quality from the beginning  
-- Shift Right: Testing in production  
-- Test automation best practices  
-- Cypress testing best practices  
-- Full stack test automation  
-- Test frameworks  
-- Defining quality objectives for CI/CD  
-- Defining your test strategy  


- The Value of Testing  
-- One novel way to communicate the value of 
-- Sprint Demo  
--- I’ve found stakeholders and leadership particularly appreciate including test methodologies in the sprint demo. We show what we tested, how we tested it, and what we’ve automated. This gives them insight into the quality being delivered, as well as what we’ve done to prevent future issues.  

### Quality Organizations
[](QE Unit)

<!-- Dead Orgs?
[https://www.veriomqa.com/](Veriom QA)
-->

<!-- Some objectives I might set, if i join your team:  
- 45 Days  
-- Searching for two Senior QA Engineer candidates  
Review current quality processes and identify opportunities/gaps
Join current code review process
Partner with engineering to create DoD (Definition of Done) which meets Quality objectives

90 Days
Partner with Engineering to ensure RACI for the organization includes Quality Engineers
Partner with DevOps to define CI/CD process
   - Clearly defined test environments (orcontainers) with Quality objectives for each
   - Define goals for time from code completion to production


360 Days
Partner with DevOps and Engineering to Implement CI/CD 

**JimHinson/JimHinson** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🤔 I’m looking for help with ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
