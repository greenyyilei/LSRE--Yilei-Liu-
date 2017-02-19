
#### Which articles have you chosen, and why?
I choose paper “Requirements Abstraction Model” written by Gorschek & Wohlin. This paper detailed introduced what is RAM and the process of it. RAM is a tool to offer product manager handle and work with requirements on multiple levels of abstraction in a continuous product-center requirement engineering effort. There are four advantages of RAM. All the requirements can be compared to the product strategies to ensure it does not violate the goals set by the management. All the requirements are broken down to an abstract level that is goof for starting a development project. Work-up of requirements means that they are in the same abstract level and they can be compared and set against one another. All the requirements can get a richer understanding through the abstract process. RAM use the work-up rules to abstracts and breaks down requirements to several levels and reflecting the need for a development organization. Product Level requirements can be compared to product strategies and attempt to dismiss out-of-scope requirements an early phase. This model provides a detailed analysis of requirements and ensures the risk will not creeping after development effort was planned and started. RAM can be tailored to different organization and products.

I also choose paper “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements” written by Svensson and Regnell. This paper is a case study of the QUPER model. It presents the detailed practical guidelines of how to use QUPER and added the introduction of how to incorporate cost dependencies between QR. And then, they use the detailed guidelines to evaluate QUPER’s applicability with real QR. It also discussed how to define the breakpoints and barriers and the different important level of the three levels.

#### How do you plan on implementing the proposed technique/method?

##### RAM:
RAM has three steps: 

Specify(elicit) 
The goal of this step is to get an overview of the requirements. There are four attributes to describe the requirements(attributes 1-4): Description, Reason/Benefit/Rationale, Restrictions/Risks, Title. 

2. Place(evaluate) 
In this step, I will analysis which level a requirement is on. RAM consists four abstraction levels: Product Level(goal), Feature Level(features), Function Level(functions/actions), and Component Level(details consists of). There are two rules for the abstraction. No requirements may exist without having a connection to the Product Level and all the requirements have to be broken down to Function Level. 

3. Abstraction(work-up) 
The third step is to abstract and breakdown of a requirement. The work-up process also includes creating new requirements. Specifying additional requirements on adjacent abstraction levels until the work-up rules are satisfied. In this process, attributes 1-4 are specified for the new requirements. 

After requirements abstract, I will use QUPER for requirements elicitation. 

##### QUPER:
This section showed the practical guidelines of QUPER. 
1) Identify candidate QR which considered relevant features, market segment, competitor and hardware platform capability. 
2) For each selected QR, define a scale and a measurement unit to express the level of quality of QR. 
3) Identify reference levels for each QR based on actual products. 
4) Define market expectations to elicit quality breakpoints. 
5) Estimate the cost in terms of the cost barriers. 
6) Propose candidate requirements, discuss and decide actual requirements for the coming release, create roadmaps. 
7) If cost dependencies between QR are considered important for cost estimations, identify which module needs to be changed if that QR will be improved beyond the “next” breakpoint.

The QUPER model has three views that can help the companies understand better of the necessary requirements of their products. The benefit view: there are three breakpoints that show the main changes in the benefit level. The utility breakpoint marks the border of quality from useless to useful. The differentiation breakpoint marks the level of the quality is in a competitive position. The saturation breakpoint marks the product is excessive that higher quality level has no practical impact on benefit. The cost view includes cost barriers that present the non-liner relationship between quality and cost. A barrier occurs when the quality cost shift from a low level to a high level. The roadmap view combines the first two views by putting the breakpoints and carries on the same scale. The goal of this view is to compare the quality of our product and the competitor’s and make some targets for the future releases. The challenge in the definition is difficult to define and specify the value for the differentiation and saturation breakpoints.

#### Run through a worked example of using your implementation

An example is a student eduction system. This system is for students and teachers. The target market now is Sweden schools that have international students.

#### Describe what you have done.

##### RAM:

Step one: Specify.

In this step, four attributes need to be specified: description, reason/benefit/ rational, and restrictions/risks and title. the following are the attributes for the above three requirements. 

Requirement 1: 

Description: All access to the system must take place via the systems own user interface, i.e. access from third-party products is not allowed. 

Reason/Benefit/ Rational: This can control the look and user feel. The benefits are to avoid security issues and compatibility problems. 

Restrictions/Risks: Access from the third party is a risk. More functions need to be fixed to reduce this risk. 

Title: Restricted User Interface

Requirement 2:

Description: As a user, I want to have the personalized view in the system so that I am only presented with information that is relevant to me. Users in the system shall have a Personal Profile. Allow other users to find contact information. 

Reason/Benefit/ Rational: This can facilitate the interaction between users.

Restrictions/Risks: Should provide a function to allow users upload their contact information.

Title: Personalize Views

Requirement 3:

Description: We are currently focusing on the Swedish market, but will extend this to the European market in the future. Long-term, we may wish to target other continents as well. The user interface language is Swedish or English. This will be extended to other languages. 

Reason/Benefit/ Rational: The target market is Swedish. The students and teachers are almost understand Swedish and English. 

Restrictions/Risks: Some of the users may don’t know Swedish and English. Translate to another language may result in other problems.

Title: Market and User Interface Language

Step two: Place.

RAM has four abstraction levels: Product level, Feature level, Function level, and component level. This step is to analysis which level the requirements are on and place it. The following are the descriptions for each level.

Product level: this is the most abstract level. Requirements in this level are goal-like in nature.

Feature level: requirements on this level are the features that the product supports.

Function level: this is a repository for functional requirements and for non-functional requirements.

Component level: this is the last level of abstraction.

To place the requirements into the right level, there are some steps and questions need to be done to help analysis the level the requirements are on. RQ1: Restricted User Interface. RQ2: Personalize Views. RQ3: Market and User Interface Language. 

Is the requirement function or not?

RQ2 is a function for personalizing views. So RQ 2 is placed on the function level. 

Is the requirement include specific suggestions of how things solve?

RQ1 is a solution for own user interface and is the candidate for a Component level.

3. Is the requirement comparable to the product strategies?

RQ3 is abstract in nature. But RQ1 is only close to the product strategies and is not directly comparable to the product strategies. 

4. Is the requirement describes “what the system should include or support”?

RQ3 means that the system only support Swedish and English and the target market is Sweden now. And it will be extended in the future. So RQ3 is placed on the Feature level. 

Step three: Abstraction(work-up)

This step is abstract and breakdown requirements and creates new requirements. There are two tules in this step:

Rule 1: Requirements can not exist without a connection to the Product level.

Rule 2: All the requirements need to be broken down to function level.

RQ1: Restricted User Interface. 

Product level: Keep user information security. This is a created requirement.

Feature level: Own user interface.

Function level: User need to use username and password to access to their own interface. This is a  created requirement. 

Component level: Restricted User Interface. This is the original requirement.

RQ2: Personalize Views. 

Product level: This is the usability of the system. 

Feature level: User can have their personalize view. 

Function level: Personalize Views. This is the original requirement. 

RQ3: Market and User Interface Language. 

Product level: This is the usability of the system. 

Feature level: Market and User Interface Language. This is the original requirement. 

Function level: Use can choose the language when they are using the system. This is a created requirement.

Component level: The interface can adopt to the language text length. This is a created requirement.

After these steps, the requirements are abstracted. 

##### QUPER:

QUPER is a method for requirements prioritization. 

Quality performance (QUPER) model has several steps: 
1) define the quality indicators: When defining quality requirements, consider relevant features, competitors, market segment, and hardware are very important. This system needs high quality and security. The competitors are other student education systems.
2) define current market expectations. In this step, we will estimate the breakpoints and carries for the benefit view and cost view. The target market is Sweden and will be extended to other countries. 
3) identify the quality level of reference products. 
4) estimate targets for the future release. This step is to estimate the requirements for future release. 
5) create roadmaps. 
6) revise and update roadmaps. 

The QUPER model has three views that can help the companies understand better of the necessary requirements of their products. 

The benefit view: there are three breakpoints that show the main changes in the benefit level. The utility breakpoint marks the border of quality from useless to useful. The differentiation breakpoint marks the level of the quality is in a competitive position. The saturation breakpoint marks the product is excessive that higher quality level has no practical impact on benefit. 

The cost view includes cost barriers that present the non-liner relationship between quality and cost. A barrier occurs when the quality cost shift from a low level to a high level. 

The roadmap view combines the first two views by putting the breakpoints and carries on the same scale. The goal of this view is to compare the quality of our product and the competitor’s and make some targets for the future releases. The challenge in the definition is difficult to define and specify the value for the differentiation and saturation breakpoints.

#### What did you learn about LSRE/MDRE and the implementation?

Market-driven development is different from the bespoke development that the product is specific to the needs and wishes of one customer. MDRE refers to the situation where the product is offered to an open market with many customers, the development costs are divided among many buyers and the potential profit is rewarded to the producer. MDRE covers the classical RE activities like elicitation, specification and validation. It also covers the release management and market analysis which is specific to MDRE.

#### How does your implementation, and your experiences, relate to what other /research/ articles say?

For QUPER, it is important to know that breakpoints will change over time. Regnell said that in mature markets, utility and saturation are relatively stable over time, but there are still differences happen. The QUPER way of thinking is very important. As it forces you to know where your statement in the market, what you want to achieve and the cost you need to achieve your goals. QUPER's three views are a good indication of why these goals are set.
