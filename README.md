# engineering-handbook

The document summarizes *principles* or *laws* that anyone contributing to source code of the product abides by. Make sure you have clear understanding of these.



## Guiding principles

1. Eliminate waste
   1. What it means for engineering
      1. Tasks which are **prioritized and are being provided with an acceptance criteria** get addressed first
      2. There is always one **IN PROGRESS** ticket* per developer
      3. Raise pull request/approve pull request/merge pull request immediately whenever criteria are met
      4. Priorities once negotiated are fixed in generally 
2. Build Quality In
   1. What it means for engineering
      1. Follow simple design principles & patterns
      2. Write test cases always
      3. Write clean code
3. Create Knowledge 
   1. What it means for engineering
      1. Perform internal demo for major features, to receive early feedback
      2. Keep prodct documentation updated
4. Defer Commitment
5. Deliver Fast 
6. Respect People
7. Optimize the Whole



**Rule - 1**

Target audience : Engineering Lead/Support Lead/Domain Lead

1. Before creating a JIRA ticket, ensure that the work is <u>prioritized via Customer Need Prioritization Matrix & acceptance criteria for the ticket is documented</u> and negotiated with engineering team

**Rule - 2**

Target audience : Engineering team members

1. Before initiating work on a JIRA ticket, estimate it and provide an ETA for the same. 
2. Ensure that you have <u>considered</u> **Design**, **Implementation**, **Test Case Development** phases for all tickets

**Rule - 3**

Target audience : Engineering team members

1. Focus on delivering one ticket at a time, unless required otherwise in exceptional scenario

**Rule - 4**

Target audience : Engineering team members

1.  Arrange for a **design review workshop** proactively to receive a sign - off around the design before starting implementation

**Rule - 5**

Target audience : Engineering team members

1. Create a feature branch from the JIRA ticket (**at the level of user story, bugs or task**)
2. Implement while following common code quality standard
3. Leave the code in better shape than you find it
4. Write unit/acceptance test cases to validate implementation
5. Commit to remote at least once a day
6. Ensure that branch build is successful, if not **treat fixing it as highest priority**
7. Raise a pull request when
   1. Feature has been implemented
   2. Test case has been developed
   3. Branch build is passing
8. You must keep the status of **user story, bug or task** **in progress** 
9. For **subtasks**, however, you must set the status to **done** as soon as the code is committed to branch and the resultant CI build is successful

**Rule - 6**

Target audience : Engineering team members who **approves pull request** 

1. Approve the pull request
   1. if the implementation has followed agreed design
   2. if the implementation is functional
   3. if the implementation has respective test case 
   4. if there is proof (screenshots in case of UI features and acceptance test case for backend features)

**Rule - 7**

Target audience : Individuals who **merges pull request**

1. Merge the pull request
   1. if it has been approved
   2. if you are confident with the implementation, overall
2. **When a pull request is merged move corresponding user story, bug or task to done**

**Rule - 8**

Target audience : individuals who makes public facing releases of the product

1. Update fix version for the tickets 
2. Update release notes
3. Release


   
