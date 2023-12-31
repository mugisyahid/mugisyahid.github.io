---
layout: post
title: "Review Paper #2 - Main Paper"
date: 2022-10-25
description: Review Paper
tags: KA
---



NOTES: ALL OF THIS WAS NOT PROPERTIES OF MINE. 
JUST TAKING KEYPOINT HERE

## Paper 2



### Software Development Models


#### Waterfall 

Waterfall is a well-known software development model in which, the development process is carried out in a sequential pattern (Royce, 1987).

* Sys Requirement
* Software Requirement
* Analysis
* Program Design
* Coding 
* Testing (SIT & UAT)
* Operation


Issue: after the testing phase the requirement might need to be changed for fixing the problem that is existing in the system, because of this, the development process starts all over again. 100% schedule or cost overrun in the project.


#### Agile Software Development Model

During 2001 the Agile Alliance was formed, and the Agile Manifesto was published. 


### Estimation Scale

To measure the story points some sort of scales are used, these scales are relative in nature and the values can be numbers or any objects that are easy to compare (Ziauddin & Zia, 2012)



#### Relative estimation

is the estimation process in which the related items are estimated based on 3 parameters of a user story - COMPLEXITY, UNCERTAINTY, and EFFORT.

According to the (Alliance, 2016), "Relative estimation is one of the several distinct flavors of estimation used in Agile teams, and consists of estimating tasks or user stories, not separately and in absolute units of time, but by comparison or by grouping items of equivalent difficulty".

#### Absolute estimate
refers to the estimation method in which user stories are measured based on the time like, estimation based on ideal hours (Alliance, 2016).




#### Expert Estimation Method
• Fewer data required
• Adopt to special projects

• Its success depends on a team of experts

#### COCOMO
• Transparent technique
• It provides clear results
• Independent on programming language

• Much data required
• The requirements must be clear.
• Not adopted to changes in requirements.
• Require historical data which are not available sometimes


#### Planning Poker
• Adopt to changes in requirements
• Reduced bias by involving a team of experts

• Its success depends on the expert
• Estimation is relative to a team.


#### Machine Learning (ML)
• The good quality of the data helps in constructing the machine learning-based effort estimation model used for validating the model’s accuracy.

• The ML model needs existing historical data.

#### Neural Network
• Change the structure during the learning process because of its adaptive nature.

• The main limitation of implementing this model is that there is no consensus on which model is the best.


#### Story Point
• Easy to compare the sizes of the features/ functionality to each other to determine the relative size.
• Require less time.

• With the pressure of the performance improvement, teams may increase story points, e.g. something that was 3 story points, now becomes 5 story points.


#### T-Shirt Sizes
• It is better to have something that implies a range rather than an absolute number

• They are not additive; it is difficult to tell a boss you will be done in 3 mediums.
#### Analogy
• Based on similar project experience
• More accurate

• Information about past projects is required
• Historical data may not be accurate

#### Use Case Point (UCP)
• It is based on use cases and can be measured very early in the project life cycle.
• Easy to use and does not call for additional analysis.

• It can be used only when requirements are written in the form of use cases.
• Technical and environmental factors have a high impact on UCP .


####  Swimlane Sizing
• Work best with teams at any experience also work with the team having less or no experience with story points already.
• Work for the team that had never used planning poker before.

• If the estimating team is big, it may not fit in the board.

#### Dot Voting
• It helps to prioritize the improvements during the sprint retrospective.

• It sometimes gives confusing or false results.
• Participants can cheat by adding extra dots, peeling off dots or moving dots

#### The Bucket System
• It can also be used with larger groups
• Very large numbers of items can be estimated.

• Estimate roughly.
• Relative results.


#### Team Estimation Game
• Faster than planning poker.
• Easier to play.
• Simple setup
• Team members having no experience of the method can be directly involved in estimation rounds.

• Once introduced, the method can be difficult to replace.
• From a group size of more than nine people, a single round takes several minutes.


### No estimate


in software development does not mean to eliminate estimation, but exploring the distinct methods of solving the problems without asking the question "How long will it take?" (Heusser, 2013).

the requirement for estimation is decreased and the focus will be in measuring the development progress and predicting the future of the project

Estimation is the main concern for the software development industry, in particular, an accurate estimate always has become a matter of concern (R. Popli & Chauhan, 2014).
Due to this, #NoEstimates has been creating a buzz in the software industry and it is an emerging movement within the agile community.
So far, only one book "NoEstimates: How To Measure Project Progress Without Estimating" by Vasco Duarte (Duarte, 2015) and study (Hannay et al., 2018) is available.

estimation is a great area of concern but it is hard to calculate the accurate estimates of the unknown parts. In this situation, many teams are unable to deliver the committed work, because their estimates are often way off. They face project overruns and this restricts the companies from achieving their goal due to delayed delivery.


* breaking the larger tasks into smaller tasks.

the team should immediately start working on those tasks so that, it will give feedback which helps in delivering the project.

* grouping the stories according to their priorities.

The highest value or higher priorities (maybe risk) should be grouped, so that, the delivery helps on generating the feedback and throughput.

According to Boiten (2017), some of the notable features of #NoEstimates are:

1. The team can concentrate from day one to create the value for the project.
2. Relying on the project improvement good decisions can be made.
3. Frequently reviewing the project development and predicting a project will help to launch the project without any difficulty or trouble.


##### Hofstadter’s Law

It always takes longer than you expect, even when you take into account Hofstadter’s Law”

##### Parkinson’s Law
“Work expands to fill the time available for its completion”.

##### Accidental Complication.

* Essential complication or g(e) 
means the problem becoming hard within itself. For instance, the problem is hard, so the system is complicated. 

* Accidental complication or h(a) 
means not being good at our jobs or “we stuck at our jobs” due to various factors supposedly, the pressure from the organizational structure (till when will we be able to get approval for a new test environment?) and from how programs are written (development keeps on evolving so, things keeps on changing and functionality will be evolving).

- “#NoEstimates is faster since it needs very less time for estimating time”
- “Sometimes overshadowed the project scope”
- “Proper estimations will give you the clear timelines and will provide the best results in delivery”




### The #NoProject 
concept started in 2005 and it is gaining popularity in recent years. According to (Leybourn & Hastie, 2018), "#NoProject is a movement and a philosophy that represents a set of principles, practices, and ideas that any organization can apply". It can be seen as a modern agile approach that directs companies on continuous and market-validated value delivery. There are no hard and fast rules for the organization that adopts #NoProject, but if they want then they can evaluate it, experiment it, and then adopt #NoProject rules. (Leybourn & Hastie, 2018)


Common Activity: 

• The expected outcomes should be defined in terms of metrics that truly provide values, instead of easy-to-measure vanity metrics.
• Recognizing the first small step or experiment to validate the assumptions that are being made for obtaining the outcomes.
• Execute that step.
• Measure the results.
• Examine the method and adapt to the reality of your learning.
• Finally, continue the above steps, pivot, or stop if its already done enough (reached
maximum value, or learned enough).


Both of them focus on delivery value.
#NoEstimate removes the justification of estimates and helps the organization focus on value delivery first (Duarte, 2015). And, #NoProjects is the modern agile approach that directs companies on continuous and market-validated value delivery (Leybourn & Hastie, 2018).

most of the previous studies are focused on outlining the various estimation techniques available. The majority of studies also identified expert judgment to be the most popular estimation technique. 





#### Research Method -> sample


### Quesionare

Demographics
 - Country/Location
 - Genre
 - Agile Experience

Software Development Project
 - Job Role
  Software Developer
  Software Tester
  Scrum Master
  Product Owner
  Software Architect
  Program Manager
- Certification?
- Team Size
- Project Size, based on time completion?
- Business Domain

#### open question
1. I've never heard of it;
2. I've HEARD of it and Not interested;
3. I've HEARD of it and WOULD like to learn it;
4. I've USED it before, and would NOT use it again;
5. I've USED it before, and WOULD use it again;


## Benefit?
- Drive the team to complete the project successfully
- Identify the resources and project scope
- Helps to identify important issues earlier
- Monitors project progress
- To create transparency
- To gain accuracy


### other benefit
Quick and timely delivery
Provide a sense of teamwork
Increase adaptability of the team for accepting new feature
Remove conflict among development and management teams as they agree on specific estimation.
Easier forecast
Cross-Functional team


## Inaccuracy

### Requirement Related Issues
Complexity and Uncertainty - 
Missing and changing requirements - 
Overlooking non-functional requirements
Poor user stories - 

### Project Management Related Issues
Poor change control
Scope creep -
Scrum Master not guiding the team
Unstructured group estimation process

### Team Related Issues
Distributed teams - 
Dominant Personalities
Inexperience - 
Knowledge sharing problem in team - 
Pressure of timeline -
Unskilled team members -

### Over-Optimism
Considering best case scenario -
Purposely underestimating to obtain work -

### Other
Hardware - 
Ignoring testing effort -
Insufficient customer involvement during estimation process -
Lack of formal estimation process -


#### Other challenges according to respondents
- Estimates are often used by sales/project managers in a way that a customer gets high expectations. An estimate of 1 month may mean it takes 3 months to deliver because of parallelism etc. If the customer only sees 1 month, they get upset if it takes 3 in practice.
- Not understanding the impact areas of changes being done on user stories can lead to inaccurate estimates. Not understanding the impact of third-party integration or third-party dependencies also causes the issue.
- Accurate demand for a specific project in a given timeline.




## Sample Quesinare




#### pengertian-pengertian

* anchoring effects (a cognitive bias in which people make a decision based on the first piece of information available).