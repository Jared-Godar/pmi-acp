# Agile Project Scheduling and Monitoring

## Work in Progrss Limits

- Flow and productive state essential.
- Limiting work
- Benefits
  - Prevent bottlenecks
  - Improve throughput
  - Min / Max concurrent workload - realistic, avoid multi-tasking
- Ensures limites agreed upon during planning part of prcess
- Identify idleness and overload
  - Developers?
  - QA testers?
- Identify and address inefficiencies
  GOALS: - Consistently sized tasks - Limiting what should be worked on at one time - 2/4/5 - Individual tasks should take less than a couple days - Overall WIP limit as team - can collaborate on items holding up process - Protect quality of work by avoiding rushing and multitasking

## Scheduling Buffer Types

- Speed and reliability: To get both, schedule without too much time to execute and implement, but not too little.
- Still trying to achieve early finishes
  - Save costs
  - Free up resources
  - Innovate
- Once teams self-organize, can be challenging to manage
- Hoe to Introduce the right buffers?
- Parkinson's law - work expands to fill the time available
- Murphy's Law - whatever can happen, will happen - expect delays
- Student Syndrome - leave work until last possible moment especially difficult or new tasks - can result in missed deadlines
- How much buffer to introduce into schedule?
  - Can make extra problems by allocating too much work
    - Backfires
- Types of buffers
  - Feature buffers: into implementation of each feature (little extra time for each)
  - Project buffer: time at the end of a project schedule. Protect release date from delays
  - Feeding buffer: Task / cross-team dependencies don't cause delays. In between cross team handoffs.
  - Resources buffer: people and skills in place longer than estimated. Extra flexibility

## Calculating a Project Buffer

Statistical practives

1. Standard Distribution of Task Duration sd and variances between estimates and actual time
2. Estimating at 50% confidence
3. Estimating at 90% Confidence
4. Both 50 & 90: come up with a range - local safety. Should fall betw

- Critical Chain Project Management (CCPM)
  - Resources needed to complete task
  - Longest series of dependent tasks + buffers at the end

Square Root of the Sum of the Squares - Mike Cohbn

- Often more accurate
- Difference between 50% & 90% estimates = 2 standard deviations from actual value

1. Take 90% worst case estimate
2. Subtract 50% average estimate
3. Divide results by 2 and square result
4. Calculate sum of frsults for all the task
5. Calculate square root of that result and multiply by two for the final result

Guidelines

- Buffer for porjects with more than 10 user stories
- Project buffer should be at least 20% total project duration

## Monitoring Iteration Progress

1. Daily Standups

- Daily meetings
- Short and simple
- Share what has been done since last, what will be doing until next, what is blocking progress
- Only talk about those three things, no
- Scrummaster identify conversations for outside meeting. Table
- Single, smaller porject teams
- Set daily meeting at time when everyone is available
- Set time limit (15 min)
- Remain standing

1. What's been done
2. What will be done
3. Impediments / blocking issues

4. Backlog Grooming / Product Backlog Refinemens

- Reassess priority of user stories
- Team ask clarifying questions
- Team can refine estimates
- Derived from roadmap and requirements
- Prioritizing list of work with business owners
- Most important items listed first

1. Gather and analyze user and customer feedback
2. Integrate learnings - feedback, data analytics, etc
3. Determine next steps
4. Develop small stories - break up existing or create new
5. Prepare stories
   Acceptance critera - success discussed with projuect owner

- Should be collaborative between product owner and developers
- Prior to or during development
- 5-10% of effort in each sprint

## Tracking Progress

- See how work performed aligns with work planes
- Always update project Release Plan

1. List of high level deliverables
2. Release Goals
3. High-level user stories
4. Set of priorities for release
5. Estimate of the number of iterations
6. Project completion date

- Show which items have been developed, tested, ready for release
- Change as customer prioriteis change
- Update every few iterations

- Tools for tracking at project level include
  1. Relesease Burnup / Burndown Charts
     - Work outstanding in full project
     - Story points vs interations estimated to complete
  2. Parking Lot Charts
     - Project progress by themes
     - High-level, complete overview
     - Name of theme, number of user stories, number story pointe, percentage of project theme represents, percent complete
  3. Defect Report
     - Open / unresolved defects
     - Daily open / kil rates
     - Defects over time /status
     - How often a build fails and when

Iteration burnup/burndown at iteration level

## EVM for Agile Projects (Earned Value Management)

- Should create value. Must be able to calculate.
- Performance in terms of cost and schedule
- Can provide early warnings of problems and communicate progress to stakeholders
- EVM schedule performance
  Agile EVM
- Actual Project Cost
- Estimated backlog in story points
- Release Plan
- Assumed velocity for team

- Plan - this many story points in this much time
- How many storypoints completed at any point in time
- Work expresreed as storypoints completed over time
- Must divide work into user stories / story points
- Planned value, Earned Value, Actual Costs
- Good way to determine if on track in terms of cost and schedule
- Lots of calculation and tracking required
- KPIs
  - Aggregate metrics tied to strategic objective
  1. Leading KPIs - affect future performance
     - Product Owner's Time with team
     - Ready for Dev in backlog
  2. Lagging KPIs
     - Estimated effort / actual effort
     - Defects / iteration
     - Actual velocity

## Reviews and Feedback

- Project work and product iterations

1. Retrospectives
   - Meetings at the end of work perios (iteration/release)
   - Team-driven: May be faclitiated by others, but content from teAM
   - EXAMINE WORK, ANALYZE RESULTS, ID WAYS TO IMPROVE
   - More about teram dynamics than technical tasls
   1. Set the stage
   2. Gather Data
   3. Generate insights
   4. Decide what to do
   5. Close and ID ways to make future ones better
2. Five Whys
   - Root cause of specific issue or symptom
   - Retrospective technique
   - Clearly understand situation at hand
   1. Display problem statement
      - Divide team into groups of <= 5 people
        Why? - 1., 2., 3., 4., 5 Get causia
3. Fishbone Diagram Analysis /Ishikawa
   - 5 whys - assign categories
   - Realate causes to issues
   - Problem goes on right. Backbone line
   - Potential causes written as bone lines by cause category 4-5 levels
   - Represents all the potential causes
4. Product feedback loops
   - Based on Deming Cycle
     1. Plan: with info we have now
     2. Do: implement part of plan
     3. Check: measure preformance
     4. Act: change course and adapt
   - Total quality management movement
   - Continually inspect performance, interactions, teamwork, process, and progress
   - Effectiveness of all things and how to continuously improve

## Risk Management

- Any uncertainty that can +/- impact project
- Negative risks

  - Productivity variation
    - Variation between planned and actial productivity
  - Scope Creep
  - Specification Breakdown
    - Lack of consensus on what to implement
  - Personell Loss
  - Poor Estimation

- Risk estimation is a funciton of probability of a vent and severity of impact
- Risk severity = probability \* impact
- Categories

1. Business Risks: threaten business value
2. Technical Risks: relate to technologies and implementation
3. Logistic Risks: funding, scheduling, etc
4. Political Risks

- Pre-mortem Activity

  - Prior to release
  - Prepare for challence
  - Simulate already failed case
  - Identify reasons for filure
  - Elimitate
  - Brainstorm all possible pronlems, even remote chance
  - Don't work on solution now, just identify potential problems
  - Identify 5-10 likely, major challenges
  - Ignore things outsie control
  - Create solutions to top problems
  - Make backup plans

- Variance
  - Expected vs actual
  - Favorable vs adverse variance
  - Variance analysis
  - Significance of results: identify the standard and determine the interdependence
- Maintain Contrtol
  - Project budget
  - Spot trends
  - Identify opportunities
  - Identify threats
- Values used

  - Purchase price
  - Selling price
  - Labor efficiency
  - Variable overhead efficiency
  - Material yield
  - Fixed overhead spending
  - Labor rate

- Introspectives

  - Systems-level view to sustain organizational
  - Assess processes, functions, tools, rules, and technology

  1. Identify survey participants - consumers of product
  2. Summarize survey results - prep step
  3. Run Introspective session; discuss findings, implement plan

  - Requires trained facilitator and note taker
  - About three hours
  - Come out with a plan, bradcasr results

- Value Stream Mapping - describes flow of information and activities ideas from concept to implementation
- Identify bottlenecks, queues, and silos

1. Identify criteria
2. identify current state
3. Careate future state map
4. Implement future stat map

- Identifies areas of waste
- Required changes-
- Improves efficiency

Negatigve: stakeholders differentiate value / waste

## Product Quality, Testing, and Integration

- Only successful if have level of quality planned

1. Verification
   - Right product
   - Compliance
2. Validation
   -Integration
   - Code review
   - Peer review
   - Meets customers needs
   - Walkthroughs, feedback, inspections, unit testing, custome
   - Consistency, coorrectness, completebess
3. Continupous Integration
   - minimize effors
   - concurrent version system (CVS)

- Agile testing - Save time and money - Costs less - Less documenation
  Principles

1. Testing continously - moves forward. all teams must participate, nobody exempt
2. Gathering continuous feedback - coding issues fixed
3. Less documentation, but testing throughout the implementation

- Exploratory, scripted approach - tapid development pace
- Autonomy, skill, creativity
- Complementary to test automoation -

- Usability focus
- Exploratory technique
- Think of end user and workflow
- Observe users without intervening
- Examine challenges users faced

- Continuous integration practices
  - Identify problems early
  - Minimize effort
  - Deliver suitable product
  - Maintain single source repository
  - Automate biuld
  - Make builds
  - keeping build fast
  - Everyone commits to main line daily
  - Test in clone
  - Easy for everyone to get latest executabe

-Agile testing - continuous - mandatory - exploratoy - scripted

focused on usability
