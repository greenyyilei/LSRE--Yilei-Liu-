#####– What is market-driven requirements engineering? 
Market driven requirements engineering (MDRE) come from internal sources like developers, marketing groups, sales teams, support groups, bug reports, as well as from external sources such as different users, customers groups from different and multiple market segments, and competitors (through e.g. surveys, interviews, focus groups, and competitor analysis) [5]. 
#####Read up on GAP / CVA / IVA Analysis!
######GAP Analysis
A gap analysis is a method that assessing the difference between actual performance with the potential or desired performance. Gap refers to a needs analysis, needs assessment or need-gap analysis. In software development, gap analysis can show which requirements are missing, which are delete and which are still need to be development.
The first step to conducting a gap analysis is to establish a specific target objective. The next step is to analyze the current processes by collecting relevant data. The last step, after comparing the current state with the potential goals, draw a comprehensive plan for future develops. 
In the gap analysis template, it has the following components:
Identify the current and future states. 
Describe the gap
Bridging the gap. 
There are some pro and con of GAP analysis.
Advantage: 
Organization overview: a GAP analysis can provide a comprehensive overview of the product. The overview helps the organization identify gaps, analyze the reasons that led to the current position. 
Establish the priorities of the requirements. 
Disadvantage:
Time and cost are two major disadvantages of the gap analysis. GAP analysis will also influence the morale of the staff. It will result in apprehension or suspicion.

######CVA analysis
CVA is similar to GAP but includes the perspective of using competitor products in the analysis. CVA can be used to measure selection quality post-release. 

######IVA analysis
Internal Value Analysis is a technique to measure whether a product is in line with the product strategies, taking limit resources and other products into account[1][2]. IVA analysis considers the time, money, risk, and knowledge, the complementing data from GAP and CVA, requirements prioritization, dependency mapping and cost estimate. 
All the three tools help the company choose between products and keep a balance between high risk-high reward and low risk-low reward development. 

######Reference
[1] S.A. Ross, R. Westerfield, B.D. Jordan, Essentials of Corporate Finance, Third ed., McGraw-Hill, Boston, 2001. 
[2] .H. Mintzberg, B.W. Ahlstrand, J. Lampel, Strategy Safari: A Guided Tour through the Wilds of Strategic Management, Free Press, New York, NY, 1998.  

######Gorschek & Wohlin “Requirements Abstraction Model” 
RAM is a tool to offer product manager handle and work with requirements on multiple levels of abstraction in a continuous product-center requirement engineering effort. 
RAM has three steps:
Specify(elicit)
The goal of this step is to get an overview of the requirement. There are four attributes to describe the requirements(attributes 1-4): Description, Reason/Benefit/Rationale, Restrictions/Risks, Title. 
Place(evaluate)
In this step, we will analysis which level a requirements is on. RAM consists four abstraction levels: Product Level(goal), Feature Level(features), Function Level(functions/actions), and Component Level(details consists of).  There are two rules for the abstraction. No requirements may exist without having a connection to the Product Level and all the requirements have to be broken down to Function Level.
Abstraction(work-up)
The third step is to abstract and breakdown of a requirement. The work-up process also includes creating new requirements. Specifying additional requirements on adjacent abstraction levels until the work-up rule are satisfied. In this process, attributes 1-4 are specified for the new requirements. 
There are four advantages of RAM. All the requirements can be compared to the product strategies to ensure it does not violate the goals set by the management. All the requirements are break down to an abstract level that is goof for starting a development project. Work-up of requirements means that they are in the same abstract level and they can be compared and set against one another. All the requirements can get a richer understanding through the abstract process. 
RAM use the work-up rules to abstracts and breaks down requirements to several levels and reflecting the need of a development organization. Product Level requirements can be compared to product strategies and attempt to dismiss out-of-scope requirements an early phase. This model provides a detailed analysis of requirements and ensure the risk will not creeping after development effort was planned and started. RAM can be tailored to different organization and products. 

######–  Gorschek & Davis “Requirements Engineering. In search of dependent variables” 
We may assess the impact of the requirement process changing on may dependent variables. These dependent variables are divided into five levels. 

Requirements phase: it is the commonly used measure among companies to improve their requirements process. It includes the dependent variables relate to requirements cost and time, and the requirements quality. 

Project: it is often measured about whether the project was completed on time, within the budget, and did it meet the requirements. It includes dependent variables: project cost and time, project estimates and the degree of requirements change. At this level, there is four requirement-related cause exist for a project’s success or fail. They are 1) poor estimation techniques; 2) mismatch between requirements specified and requirements satisfied; 3) evolving requirements; 4) mismanagement. 

Product: the dependent variables in this level determine the degree of product success. It includes measures related to requirements selection and the degree of impact. What requirements are selected to realize is very important for the successful of a product. At this level, two issues are directly responsible for success or fail. They are requirements selection and product strategies. 

Company: the main goal in this level is to maximize the total economic benefits of the products. GAP, CVA, and IVA can help he company choose between products and keep a balance between high risk-high reward and low risk-low reward development.  It includes three measures: portfolio management, strategic alignment, and the degree of impact. 

Society: the company also has a great responsibility to the society. It always considers about the positive and negative externalities.  

######	–  R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935 
This paper presents the results of an extent interview study at 11 companies about the quality requirements. Not all QR are equally important for all the project. So the prioritization of the requirements is very important. Requirements interdependencies can impact the products’ development in terms of planning, design, and quality.  Consider about the interdependency between the requirements, REQUIRES and CVALUE are considered as the most important and common types. In the cost estimation part, the study showed that there is  no distinction between FR and QR. And the opinion from expert is the primary method for cost estimation.

######	–  J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997. 
For a successful system, the quality must be maximized and the cost must be minimised, and time-to-delivery has to be as short as possible. The cost-value approach will prioritise the requirements based on their value and cost. The approach also uses the AHP approach to investigate the candidate requirements. 

There are five steps for the cost-value approach:
Requirements engineerings review the candidate requirements based on their completeness and ensure they are unambiguous. 
Customers and users use AHP’s pairwise comparison method to assess the value of the requirements. 
Experienced software engineerings use the AHP’s pairwise comparison method to estimate the cost for implementing each requirement. 
A software engineer use AHP to calculate each requirement’s value and cost, and use them make a cost-value diagram. 
The stakeholders use the diagram to analyzing and discussing the candidate requirements. 
Based on the discussion, the manager prioritize the requirements and decide which to be implemented. 
There are some challenges for the cost-value method. Carrying out all the required pairwise comparison is very difficult. The method also doesn’t consider the interdependencies between requirements. And more requirements will increase the complexity. The number of pairwise comparisons is of O(n2).

######–  Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies” 
In this paper, a method that use product strategies for early requirements triage called A Method for Early Requirements Triage and Selection(MERTS) is presented.  The products strategy is shown where a company wants to go, how it will get there, and why it will be successful. To conduct a product strategy, there are five key questions that need to be answered. 

Where do we want to go: The goal of this question is to set the general directions of movement and the objectives specify the specification of accomplishment. The example goal is like profit, growth, and market share. 

How will we get there: This is the core of the product strategy. It addresses such as customer targets, competitive targets and different advantage. The choice of customer targets deepens on the goals and objectives selected when answering the first question. The  chosen of the customer targets set the boundaries of the product strategy. Prioritizing competitors also very important for this question. 

What to do: This is related to the detail programs, tactics to be used to achieve the goals.   It deals with the product, pricing, promotion, distribution, and service. The result also decides the selection of strategic drives. 

Why would we be successful: This is the most important question. The answer is related to the different advantage aspect of the product and has to be clearly answered to produce a competitive product strategy. 

When will we get there: Roadmap can be used to support answering this question. A roadmap can present the targets based on the time and releases. In this paper, the product-technology roadmaps will define the moving targets of the strategy. 

The goal of MERTS is to provide a clear method to deal with how to achieve a common view and understanding of product strategy. There is three part of MERTS. First step is early requirements triage. It includes specify the question 1), 2), 3), assign the weights for each requirement and compare requirements. The second step is to select requirements for release. It includes specify product-technology roadmap,  and estimate resources. The third step is explaining the reason why the proposed strategy will be successful. The contribution of MERTS is to help explicit discussions, conduct and report strategies, and triage the requirements. 










