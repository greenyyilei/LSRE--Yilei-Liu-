#### Method for prioritize requirements

##### Cost-value
For a successful system, the quality must be maximized, and the cost must be minimized, and time-to-delivery has to be as short as possible. The cost-value approach will prioritize the requirements based on their value and cost. The approach also uses the AHP approach to investigate the candidate requirements.

In the article [1], there are five steps for the cost-value approach: Requirements engineerings review the candidate requirements based on their completeness and ensure they are unambiguous. Customers and users use AHP’s pairwise comparison method to assess the value of the requirements. Experienced software engineerings use the AHP’s pairwise comparison method to estimate the cost of implementing each requirement. A software engineer uses AHP to calculate each requirement’s value and cost, and use them make a cost-value diagram. The stakeholders use the chart to analyzing and discussing the candidate requirements. Based on the discussion, the manager prioritizes the requirements and decide which to be implemented. There are some challenges for the cost-value method. Carrying out all the required pairwise comparison is tough. The method also doesn’t consider the interdependencies between requirements. And more requirements will increase the complexity. The number of pairwise comparisons is of O(n2).

#####GAP
GAP is a method used gap analysis for prioritization requirements. It compares the existing usage with potential usage and calculates the gap between them. 
The usage gap= Exist usage-potential usage. 
Gap refers to a requirements analysis, requirements assessment or requirement-gap analysis. In software development, the gap analysis can show which requirements are missing, which are delete and which are still need to be development. Gap analysis is the task that requirements managers perform to ensure the scheduled product functions are covered by the appropriate platform project[2]. The goal of GAP analysis is to provide the misalignments between market requirements and supplier requirements are addressed[2].

The first step to conducting a gap analysis is to establish a specific target objective. The next step is to analyze the current processes by collecting relevant data. The last step, after comparing the current state with the potential goals, draw a comprehensive plan for future develops.

In the gap analysis template, it has the following components: 
1. Defines the current and expected state.
2. Describe the gap
3. Narrow and improve the gap.

There are some pro and con of GAP analysis.

Advantage:

Organization overview: a GAP analysis can provide a comprehensive overview of the product. This summary helps organizations define gaps and analyze the causes of the gaps. Establish the priorities of the requirements.

Disadvantage:

Time and cost are two major disadvantages of the gap analysis. GAP analysis will also influence the morale of the staff. It will result in apprehension or suspicion.


##### RAM
RAM is the process that abstracts the requirements and makes them easy to prioritize and select.
Article [3] detailed described RAM.  

RAM is a tool to offer product manager handle and work with requirements on multiple levels of abstraction in a continuous product-center requirement engineering effort. RAM has three steps: Specify(elicit) The goal of this step is to get an overview of the requirement. There are four attributes to describe the requirements(attributes 1-4): Description, Reason/Benefit/Rationale, Restrictions/Risks, Title. Place(evaluate) In this step, we will conduct the analysis which level a requirement is on. RAM consists four abstraction levels: Product Level(goal), Feature Level(features), Function Level(functions/actions), and Component Level(details consists of). There are two rules for the abstraction. No requirements may exist without having a connection to the Product Level, and all the requirements have to be broken down to Function Level. Abstraction(work-up) The third step is to abstract and breakdown of a requirement. The work-up process also includes creating new requirements. Specifying additional requirements on next abstraction levels until the work-up rule are satisfied. In this process, attributes 1-4 are specified for the new requirements. There are four advantages of RAM. All the requirements can be compared to the product strategies to ensure it does not violate the goals set by the management. All the requirements are broken down to an abstract level that is goof for starting a development project. Work-up of requirements means that they are in the same abstract level and they can be compared and set against one another. All the requirements can get a richer understanding through the general process. RAM use the work-up rules to abstracts and breaks down requirements to several levels and reflecting the need for a development organization. Product Level requirements can be compared to product strategies and attempt to dismiss out-of-scope requirements an early phase. This model provides a detailed analysis of requirements and ensures the risk will not creeping after development effort was planned and started. RAM can be tailored to different organization and products.

#### 2. Roadmapping

#####MERTS

For roadmapping, a method that uses product strategies for new requirements triage called A Method for Early Requirements Triage, and Selection(MERTS) is presented. The products strategy is shown where a company wants to go, how it will get there, and why it will be successful. This method provides five key factors: Where do we want to go, How will we get there, What to do, Why would we be successful, When will we get there. 
The roadmap can be used to support answering ”When will we get there.” A roadmap can present the targets based on the time and releases. In the paper [4], a product-technology roadmap was defined to show the moving targets of the strategy.
The goal of MERTS is to provide a precise method to deal with how to achieve a shared vision and understanding of product strategy. There is three part of MERTS. The first step is early requirements triage. It includes specify the question 1), 2), 3), assign the weights for each requirement and compare requirements. The second step is to select requirements for release. It includes specify product-technology roadmap, and estimate resources. The third step is explaining the reason why the proposed strategy will be successful. The contribution of MERTS is to help explicit discussions, conduct and report policies, and triage the requirements.

In my opinion, I want to use cost-value and RAM to prioritize the requirements. As this cost-value is focused on prioritizing requirements and RAM can abstract the requirements and make them easy to be compared. 
Use RAM(Requirements Abstraction Model) can find more features as this method general requirements into relatively small parts. The general process can help us to find more features.   


#####Reference
[1] J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997.
[2] K. Wnuk, “Understanding and Supporting Large-Scale Requirements Management.”
[3]T. Gorschek and C. Wohlin, “Requirements Abstraction Model,” Requirements Eng, vol. 11, no. 1, pp. 79–101, Nov. 2005.
[4] T. A. Kappel, "Perspectives on road maps: How organizations talk about the future," The Journal of Product Innovation Management, vol. 18, pp. 39-50, 2001. 
