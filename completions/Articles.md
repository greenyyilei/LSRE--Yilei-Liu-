###•	What is large scale requirements engineering? 
The project that has less than 1000 requirements[10]. 
###•	What are the challenges in large scale requirements engineering? 
Large number of customer requirements takes challenges for analysing, specifying, and managing requirements. To mitigate this challenge, we can develop a well-structured feature list and make a good understanding of customer requirements [8].
Formal communication and interface to customer. The large number of customer requirements make understanding the various aspects of the software very challenging. In order to mitigate this challenge, clarify customer requirements in the early stage of the development process is very important[8]. 
Science the project spanned several years, technology changed during the time. To mitigate this challenge, we can separate the requirements and design decisions[8]. 
Project teams were distributed geographically and often leads to issues of coordination and communication. To mitigate this challenge, we can provide simple visualisations which provide meaning information of the project status to make members identifying issues quickly and taking corrective action early[8].
In long-term projects, resource fluctuation is a challenge. We can establish effective documentation standards and review process to mitigate this challenge[8].
Requirements elicitation, classification, prioritization, and prediction are all challenges in LSRE[9].

###•	What is the order of magnitude of the number of requirements we are discussing? 
This following shown four orders of magnitude of the number of requirements based on the size of the set of requirements[10] .

SSRE： Small-Scale Requirements Engineering   	       ~10 requirements 

MSRE：    Medium-Scale Requirements Engineering 	    ~ 100 requirements 

LSRE：	   Large-Scale Requirements Engineering 	      ~1000 requirements 

VLSRE：	   Very Large-Scale Requirements Engineering 	  ~10000 requirements 


###•	Read and summarise 
####“The art and science of release planning”
A good release plan should provide maximum business value, satisfy the most important stakeholders, use the available resources and present the existing dependencies between features. There are two approach for release planning. The are of RP realise on human intuition, communication and the capabilities to coordinate between conflicting goals and constraints. The science of RP formalizes the problem and use computational algorithms to make best solutions. But they all have disadvantage. The art-based approach can not deal with the RP problem’s complexity as the number of factors grows. The science-based approach can not consider the problem from the human decision maker’s view. The hybrid approach is in a high-level framework for release planning. Firstly, modelling to make it suitable for computational intelligence based techniques. Secondly, exploration. We will generate the solution plan based on the formal model and developed integer programming algorithms to explore the spoliation space and find the alternative solution. Thirdly, consolidation the result. The decision maker will evaluates the alternative solution of the  algorithms based on the experience and the problem context. 



####“Introducing support for release planning of quality requirements–an industrial evaluation of the QUPER model” 
   This paper is an industrial evaluation of the QUPER model used at Sony Ericsson. First we introduce the QUPER model and then based on the situation of the company, tailoring  the QUPER model. Sony Ericsson has a global market and more than 20,000 requirements. The aim of this paper is introduce the QUPER model and evaluate it   based on this case. The goal of this model is solve the constraints between quality and cost and provides helpful information of quality requirements in release planning. As a supplement of cost and value, the QUPER model has a third dimension related to quality which used to prioritise the functional requirements. Quality performance (QUPER) model has several steps: 1) define the quality indicators 2) define current market expectations. In this step, we will estimate the breakpoints and carries for the benefit view and cost view. 3) identify the quality level of reference products. 4) estimate targets for future release. 5) create roadmaps. 6) revise and update roadmaps. 
The QUPER model has three views that can help the companies understand better of the necessary requirements of their products.
The benefit view: there are three breakpoints that show the main changes in the benefit level. The utility breakpoint marks the border of quality from useless to useful. The differentiation breakpoint marks the level of the quality is in a competitive position. The saturation breakpoint marks the product is excessive that higher quality level has no practical impact on benefit. 
The cost view includes cost barriers that present the non-liner relationship between quality and cost. A barrier occurs when the quality cost shift from a low level to a high level. 
The roadmap view combine the first two views by putting the breakpoints and carries in the same scale. The goal of this view is to compare the quality of our product and the competitor’s and make some targets for the future releases. 
The result shown that the QUPER model can support prioprtization and roadmapping  when making high-level decision-making  for quality requirements at early stages of release planing. The challenge in definition is difficult to define and specify the value for the differentiation and saturation breakpoints. 


####“A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”
This paper is a case study of the QUPER model. It presents the detailed practical guidelines of how to use QUPER and added introduction of how to incorporate cost dependencies between QR. And then, they use the detailed guidelines to evaluate QUPER’s applicability with real QR. It also discussed how to define the breakpoints and barriers and the different important level of the three levels. 
This section shown the practical guidelines of QUPER. 1) Identify candidate QR which considered relevant features, market segment, competitor and hardware platform capability. 2) For each selected QR, define a scale and a measurement unit to express the level of quality of QR. 3) Identify reference levels for each QR based on actual products. 4) Define market expectations to elicit quality breakpoints. 5) Estimate the cost in terms of the cost barriers. 6) Propose candidate requirements, discuss and decide actual requirements for the coming release. 7) If cost dependencies between QR are considered important for cost estimations, identify which module needs to be changed if that QR will be improved beyond the “next” breakpoint.
The evaluation shows that the QUPER model is easy to understand, improves the understanding of QR,  and doesn’t take too much time to apply in practice. In the three views, roadmap view is the most important view, benefit view may be helpful for specifying QR, and cost view is the least important view. 




#####Reference
[8] S. Konrad and M. Gall, “Requirements Engineering in the Development of Large-Scale Systems,” in 16th IEEE International Requirements Engineering, 2008. RE ’08, 2008, pp. 217–222.
[9] Safwat and M. B. Senousy, “Addressing Challenges of Ultra Large Scale System on Requirements Engineering,” Procedia Computer Science, vol. 65, pp. 442–449, 2015.
[10] B. Regnell, R. B. Svensson, and K. Wnuk, “Can We Beat the Complexity of Very Large-Scale Requirements Engineering?,” in Requirements Engineering: Foundation for Software Quality, B. Paech and C. Rolland, Eds. Springer Berlin Heidelberg, 2008, pp. 123–128.

####Read up on GAP / CVA / IVA Analysis!
#####GAP Analysis[3][4][5]
A gap analysis is a method that assessing the difference between actual performance with the potential or desired performance. Gap refers to a needs analysis, needs assessment or need-gap analysis. In software development, gap analysis can show which requirements are missing, which are delete and which are still need to be development.


The first step to conducting a gap analysis is to establish a specific target objective. The next step is to analyze the current processes by collecting relevant data. The last step, after comparing the current state with the potential goals, draw a comprehensive plan for future develops. 


In the gap analysis template, it has the following components:

1. Identify the current and future states. 

2. Describe the gap

3. Bridging the gap. 

There are some pro and con of GAP analysis.
Advantage: 
Organization overview: a GAP analysis can provide a comprehensive overview of the product. The overview helps the organization identify gaps, analyze the reasons that led to the current position. 
Establish the priorities of the requirements. 

Disadvantage:
Time and cost are two major disadvantages of the gap analysis. GAP analysis will also influence the morale of the staff. It will result in apprehension or suspicion.

#####CVA analysis[3]
CVA is similar to GAP but includes the perspective of using competitor products in the analysis. CVA can be used to verify the perceived customer value and measure the selection quality post-release.  
#####IVA analysis
Internal Value Analysis is a technique to measure whether a product is in line with the product strategies, taking limit resources and other products into account[1][2]. IVA analysis considers the time, money, risk, and knowledge, the complementing data from GAP and CVA, requirements prioritization, dependency mapping and cost estimate. 
All the three tools help the company choose between products and keep a balance between high risk-high reward and low risk-low reward development. 

#####Reference
[1] S.A. Ross, R. Westerfield, B.D. Jordan, Essentials of Corporate Finance, Third ed., McGraw-Hill, Boston, 2001. 

[2] .H. Mintzberg, B.W. Ahlstrand, J. Lampel, Strategy Safari: A Guided Tour through the Wilds of Strategic Management, Free Press, New York, NY, 1998. 

[3] A. Gomes and A. Pettersson, Market-Driven Requirements Engineering Process Model – MDREPM. 2007.

[4] K. Wnuk, “Understanding and Supporting Large-Scale Requirements Management.”

[5] K. Wnuk, B. Regnell, and L. Karlsson, “What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting,” in Requirements Engineering Conference, 2009. RE ’09. 17th IEEE International, 2009, pp. 89–98.

####	–  Gorschek & Davis “Requirements Engineering. In search of dependent variables” 

This paper provides a taxonomy of levels to assess the impact of the requirement process changing on many dependent variables. These dependent variables are divided into five levels. 

Requirements phase: it is the commonly used measure among companies to improve their requirements process. It includes the dependent variables relate to requirements cost and time, and the requirements quality. It may be measured in its outputs and its activity. The requirements phase is the easiest measured one in the five levels. 

Project: it is often measured about whether the project was completed on time, within the budget, and did it meet the requirements, how many of the documented requirements were actually implemented. It includes dependent variables: project cost and time, project estimates and the degree of requirements change. At this level, there is four requirement-related cause exist for a project’s success or fail. They are 1) poor estimation techniques; 2) mismatch between requirements specified and requirements satisfied; 3) evolving requirements; 4) mismanagement. 

Product: the dependent variables in this level determine the degree of product success. It includes measures related to requirements selection and the degree of impact. What requirements are selected to realize is very important for the successful of a product. At this level, two issues are directly responsible for success or fail. They are requirements selection and product strategies. Actually they are relevant to whether the product make money. Selected the right requirements from the customer perspective and meet customer expectations will have strong impact on the market success. 

####–  Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management of Software Requirements)  

This paper is mainly described the context and concepts of MDRE, and briefly compare it with the customer-specific development. 

Market-driven development is different from the bespoke development that the product is specific to the needs and wishes of one customer. MDRE refers to the situation where the product is offered to an open market with many customers, the development costs are divided among many buyers and the potential profit is rewarded to the producer. MDRE covers the classical RE activities like elicitation, specification and validation. It also covers the release management and market analysis which is specific to MDRE. The following are some differences between MDRE and bespoke development. 

MDRE:
1. The main goal of MDRE is to deliver the right product at the right time. 
2. In the MDRE, whether the product is success or not is decided by sales, market share, and product reviews. 
3. There is often one major release of MDRE and the product is continuous evolution rather than maintenance. 
4. In the NDRE, much effort is devoted to prioritization, cost estimation and release planning. 
5. Case validation in the MDRE is often delayed until a late stage of the development. 

Bespoke:
1. The main goal of the bespoke development is to realisation of a contract and compliance to a requirements specification. 
2. Int the bespoke products, whether the product is success or not is determined by customer satisfaction and user acceptance. 
3. The lifecycle of the bespoke project is often divided into development first and then maintenance. 
4. In the bespoke development, much effort is devoted to negotiation and conflict resolution. 
5. In the bespoke development, validation is continuous doing through the contacts between the customer and the developers. 

There are some challenges in MDRE: find a good balance between technology-driven and need-driven requirements; communication and collaboration between marketing and development; requirements dependencies make release planning difficult; cost-value estimation. The key issue of MDRE is to continuously improve in managing these challenges to make it ahead of the competitors. 

The MDRE process quality is very important in requirements selection. The alfa/beta model of MDRE selection quality is used to capturing decision quality. An alfa requirement has a high inherent quality that it should be selected and a beta requirement has low inherent quality that should be rejected. It is not easy to find and select alfa requirements and rejecting beta requirements and it is difficult to know whether a requirement is an alfa or beta requirements as the cost-benefit trade-off is very difficult.  

There are two typical ingredients in MDRE data management. The requirements state model is used for requirements refinement progress tracking. There are two modes in the requirement state model. 

In the continuous mode, product manager receive and register all kinds of requirements. It includes the following steps:

Candidate: Each received requirements will have the status “Candidate”.

Approved: The requirements with status Candidate will be reviewed at regular time intervals. The requirements that are being accepted get the status “Approved”. This process is very difficult as it is hard to confirm the quality of the requirements. 

Specified: The pervious description of the requirements is almost not very clearly and detail for planning and developing, then a more suitable and detailed specification is linked to the requirements. 

Discarded:  The requirements being rejected get the statusDiscarded. The reason report will be send to the submitter. The discarded requirements are not deleted from the database to enable future analyses. 

In release mode, the release scope is frozen in order to manage the release development project. It includes the following steps:

Planned: The development team will consider about release date and human resources and maximum the number of planned requirements. All the selected requirements get the status Planned and are input for the design and coding process.

Developed: Development includes design, coding, unit tests and production of collateral materials. The requirements will get status Developed when all the activities are successfully completed. 

Verified: Software testing is used to verify the quality of project before it released. 

Released: The requirements will get the status Released when all the activities are completed and the submitter will get a notification. 

The requirements repository is used to store the relevant attributes of candidate requirements. Smaller project will need a simple spreadsheet and large-scale project will need requirements management tool due to the volume of requirements. 

####		–  D. Leffingwell “Scaled Agile Framework” (Note, there is no good article on this, but his webpage provides some help).  Scrum become very popular in software development team, but is doesn’t describe how large project can scale or how manager in program level or portfolio level will handle their requirements together with agile teams[1]. Dean Leffingwell created the Scale Agile Framework(SAFe) to apply agile methodologies to the whole companies. SAFe is based on Lean and Agile principles[2]. 

SAFe proposes three levels[1][2][3][4]: 

Portfolio Level[4]: PPM is the core part in Strategy, Investment Funding, Program Management and Governance.  Epics define large development initiatives that encapsulate the new development necessary to realise the benefits of the investment themes which drive the budget allocations[2]. Portfolio philosophy is the centralised strategy with local execution.   

Program Level: SAFe defines an Agile Release Train(ART) to program. The ART is the main instrument for value delivery at the program level which delivers a value stream for the organization[2]. 5 and 10 teams work together and synchronise their release boundaries and iteration boundaries[2][3].  Every 5 iterations, a train delivers a Potentially Shippable Increment(PSI) and held a demo, inspect and adapt seminars and plan for the next PSI[2]. In this level, new roles are defined. In the IT/PMI environments, the program manager may have more than one roles. If they have domain expertise, they can fill the product manager role. The product manager who defines and priorities the program backlog has content authority at this level. SAFe defines an artifact hierarchy of Epics-Features-User Stories. The program backlog is features prioritised list. Features can generate at the Program level or derive from Epics defined at the Portfolio level[2]. The system architect has design authority at this level. He work with teams day by day to ensure the non-functional requirements are met. He also works with the enterprise architect to ensure there are enough architectural runway to support the upcoming user and business needs at the Portfolio level[2].  The UX Designers provide UI design, UX guidelines and design elements for teams. The Release Train Engineering is the Uber-ScrumMaster. The Release Management Team is a cross-functional team that approves frequent releases of quality solution to customers[2].

Team Level: This level works with traditional agile methods but the team meeting are synchronised. Define/Build/Test teams deliver working and the sprint is also fixed as two weeks[2]. Scrum has many events, sprint planing, sprint review and sprint retrospective, SAFe also add an event called “release planning” meeting to synchronise teams after each five iterations[1]. This meeting is essential for SAFe in order to reduce the coordination overhead between teams, conduct a common direction of all members, and reduce the risks[1]. 

Program and Team Level are work together on the same value stream. 

#####Reference
[1] R. Brenner and S. Wunder, “Scaled Agile Framework: Presentation and real world example,” in 2015 IEEE Eighth International Conference on Software Testing, Verification and Validation Workshops (ICSTW), 2015, pp. 1–2.
[2]  “41 Things You Need to Know about the Scaled Agile Framework® (SAFe) | Rally Software Blog.” [Online]. Available: https://www.rallydev.com/blog/agile/41-things-you-need-know-about-scaled-agile-framework-safe.		
[3] “Program Level – Scaled Agile Framework.” [Online]. Available: http://www.scaledagileframework.com/program-level/.
[4] “Portfolio Level – Scaled Agile Framework.” [Online]. Available: http://www.scaledagileframework.com/portfolio-level/.

####–  Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering” 

The main purpose of this case study is to increase the understanding of the factors that cause overscoping, increased the attention to this risk, and use some steps addressing and avoiding overscoping in the project. In this article, case study is divided into three step. The first step, according to one of the authors’ industry experience, established a hypothesis about possible cause of overscoping and possible effects of overscoping. This hypothesis, as the starting point of the interview appeared in the second step. The third step, the interview results were validated by using a questionnaire to six other employees from the same company.

The results pointed out that overscoping is a challenge for requirements engineering and project management. For the case company, overscoping is mainly caused by the fast-moving market-driven domain. In the early software development phase, low participation of relevant developers for the development of the overall goal will lead to a lot of unrealistic project scope. Our research indicates that overscoping may lead to a lot of negative effects, such as quality problems, delays or cannot meet the target expectations of customers. Delay and quality problems are very expensive. This will not only need to spend money to repair but also lose market share and brand value. We found overscoping will lead to more overscoping, and communication gaps. For the case company, despite increasing agile RE practices, overscoping is still a problem. We conclude that improvement needs continuous optimisation the project scope, combine with implementation cost and schedule estimates, close cooperation of cross-functional teams, thereby reducing the communication gaps. Conclusions of this paper can be used to define the potential factors in order to achieve more realistic project scope.

####		–  Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”  
This paper use case study and survey to investigate the factors affecting decision outcome and lead-time in LSRE. The decision lead-time is the time required to analyse the impact of a decision under this context. The decision outcome is a specific outcome of the decision process called acceptance or rejection under this context. To research on this area, there are three research questions and six hypothesis. After case study and survey among 50 practitioners, they conclude some results. When the decision affect more products, the lead-time to make a decision will increases.  Decision maker should know more complex decisions may take more time. According to the statistical analysis of the decision log, it is more likely to accept the issues of changing requests by important customers. At the same time, the lead-time to accept a decision is shorter than to reject a decision. The number of products affected by a decision increase the decision lead-time. Due to more complex decision take more time, it is wise to decrease their complexity for faster decision. 

####		–  P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Natt och Dag, “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE Interna- tional Symposium on Requirements Engineering, 2001.  

This paper provide an industrial survey in five companies and analysis their requirements’ interdependencies. We found that only about 20% of the requirements are singular. And 20% of the requirements are involved in 75% of all interdependencies. Customer-Specific bespoke product is tend to more functionality-related dependencies, while market-driven product is tend to value-related dependencies. 

In each case, managers are randomly select 20 high priority requirements from the current requirements repository. Based on these cases, there are six commonly used interdependencies of requirements: 

R1 AND R2: means R1 requires R2 to function and R2 requires R1 to function. This is functional-related and is suitable for the bespoke development.

R1 REQUIRES R2: means R1 requires R2 to function but not vice versa. This is functional-related and is tend to be in a bespoke development environment. 

R1 TEMPORAL R2: means either R1 has to be implemented before R2 or vice versa. 

R1 CVALUE R2: means R1 affects the value of R2 for a customer and the value may be either positive or negative. From a product planning view, this relationship is important. It is value-related and is tend to be in a product development situation.  

R1 ICOST R2: means R1 affects the cost of performing R2 and the value could be either positive or negative. In some cases, CVALUE and ICOST are relevant. For instance, R1 increase the value of R2 for the customer, but it increase the cost of implementing R2 at the same time. It is value-related and is tend to be in a product-oriented case. 

R1 OR R2: means only on of R1, R2 needs to be performed. 

In some cases, two requirements may have more then one relationship. In the product development perspective, the value-related interdependencies are more common than functionality-related. However in the bespoke development, functionality-related interdependencies are more common than value-related. To support the release planning, a simple visualization technique is apply to the requirements and their interdependencies. It is a powerful tool and is good for release planning. Requirements having no relationship with others are easily spotted and free clusters can be scheduled for any increment in which requires all involved requirements are scheduled for the same increment. Requirements having interdependencies with others should be implemented at early stage and they should be scheduled for the same release in order to simplify realisation and reduce the risks.  
Company: the main goal in this level is to maximize the total economic benefits of the products. This level is closely related to the scope of the product. It is essential to make an overview of the whole product portfolio includes what have already deployed, what is under development, and those just being planned. GAP, CVA, and IVA can help he company choose between products and keep a balance between high risk-high reward and low risk-low reward development.  It includes three measures: portfolio management, strategic alignment, and the degree of impact. 

Society: the company also has a great responsibility to the society. Although the company may provide grate benefits to its stakeholder, but it pollutes the environment or kills people have to be considered a failure.  It always considers about the positive and negative externalities. This means neither the developer nor the customer have to bears all the costs or get all the benefits generated by the products. When conduct company strategies, the company can try to maximize the positive effects of their product.

This paper also suggests that product strategies should reflect long-term goals, and the goals also have to meet the current market and technology trends.  

####—-Obsolete software requirements Krzysztof Wnuk, Tony Gorschek, Showayb Zahda 

In this paper, we use empirical investigation to define the phenomenon of obsolete software requirements, investigate the potential impact and how they are resolved in industry. We have 219 respondents from 45 countries who are industry practitioners. This paper proposed seven research questions. The questionnaire was created based on a literature review of relevant papers.

RQ1: Based on empirical data, what would be an appropriate definition of Obsolete Software Requirements (OSR)? 
Based on the results of the questionnaire, our respondents defined an OSR as follow: “a software requirement (implemented or not) that is no longer required for the current release or future releases, and it has no or little business value for the potential customers or users of a software artifact.’’ When consider demographics’ impact, The definition of OSRs is not significantly connected to the size of the companies, the length of the typical project, or the domain.

RQ2: What is the impact of the phenomenon of obsolete software requirements on the industry practice? 
When asked about the potential impact of OSRs to their product development, in all respondents, 84.3% considered serious or somehow serious. This indicates that most respondents believe OSRs seem to have a significant impact on the product development. For 6% of respondents, OSRs is a very serious problem, while 10% deemed OSRs a Trivial matter. Those respondents who think OSRs serious, mostly worked in large companies and used agile development. Those who considered trivial, more than 80% worked in large companies. Because the big companies tend to use more complex process models.

RQ3: Does requirement type affect the likelihood of a software requirement becoming obsolete? 
According to our respondents, requirements related to standards, laws and regulations are the least probable to become obsolete. Compare with requirements originating from customers developers, requirements originating from domain experts were less probable to become obsolete.

RQ4: What methods exist, in industry practice, that help to identify obsolete software requirements? 
More than 50% of the respondents proposed that manual ways of discovering OSRs are the main method. At the same time, demographic factors have no significant impact on this question. OSRs identification is mainly a manual activity, less than 10% of the respondents said they have any automatic functionality.

RQ5: When OSRs are identified, how are they typically handled in industry? 
When considering existing processes and practices for managing OSRs, 73.6% of respondents said they did not consider the needs for manage OSRs during their requirements engineering process. At the same time, 73.6% of respondents said they did not have any procedure to deal with OSRs. This result can be used as clear evidence of a lack of industry-related OSR processing method, and confirms the need for developing methods for managing OSRs. According to the survey answers, more than 60% of respondents think that the identified OSRs should be kept in the requirements document or database, but marked as obsolete. Removing OSRS is an undesirable behaviour.

RQ6: What context factors, such as project size or domain, influence OSRs? 
The result indicates that the larger the projects, the more likely to have a negative impact from OSRs. OSRs are more likely to affect large-scale project requirements and very large-scale requirements projects.
The results from the average score shown that outsourcing project is most likely to be affected by the OSRs. Compared to bespoke or contract-driven development, OSRs seem to have a larger impact on an MDRE environment. However, for very large projects all respondents, independent of the environmental factors, the potential impact of OSRs is huge.

RQ7: Where in the requirements life cycle should OSRs be handled? 
According to our respondents' answers, OSRs should be first handled during the requirements analysis phase, requirements validation phase and requirements changes phase. Our respondents also suggested that requirements elicitation is not the best stage to manage OSRs.

Our results show that OSRs is a significant challenge for software system development. 84.3% of the respondents considered that OSRs are serious. In addition, a clear majority of respondents said there are no useful methods or tools to support the identification and treatment for OSRs. Only 10% of the respondents reported having automated support. This suggests that there is a need to develop automated methods or tools to support practitioners identify and manage OSRs.

####- Assessing challenges of continuous integration in the context of software requirements breakdown: a case study 

In this paper, Ericsson as an example, based on case studies and interviews to determine the challenges of continuous integration and requirements break down, and how the latter affects the implementation of the continuous integration process.

In order to support more frequent integration, requirements need to be small enough so that the developer can provide individually tested per day, and integration times. Under continuous integration environment which is not always an easy task. So breaking down large user stories into small enough stories with the right level of detail and visible business and customer value has been identified as a challenge. 

This article only establishes a case study in which the focus and case is an organization. Thus, the unit of analysis is the teams under study that are using continuous integration. From the methodological point of view, the study is from the perspective of interpretation. A semi-structured interview is a method of collecting data in this study. In this study conducts 13 interviews with eight participants from Sweden and five from China.

I will summarize the result based on the different research question.

For RQ1: What are the challenges of implementing a continuous integration process in practice?

There are seven main challenges from the result: developers’ mindset, tools and infrastructure, testing, domain applicability, understanding of continuous integration, code dependencies and software requirements. 

In the opinion of respondents, mindset, tools and infrastructure are the most mentioned. People’s mindset and attitude play an important role when  adopting continuous integration. Similarly, tools, infrastructure and testing also have a significant impact on the success of implementing continuous integration. This means that the use of continuous integration can be considered to introduce a change in the existing software process.

For RQ2: What are the challenges of software requirements breakdown in practice?

There are four main challenges. 

1. Requirements abstraction 

Requirements abstraction is a challenge for developers as they struggled with requirements that are either too large, ambiguous or too low level. In addition, details’ level and quality requirements depend on the type  of requirements. People tend to take shortcuts and not follow a uniform architectural design. This, in turn leads to difficult to estimate the impact of changes. A large number of sub-systems make coordination difficult and will increase the pressure of one developer. This makes requirement difficult to break down into smaller units that can operate independently. At the same time find the right balance when breaking large software requirements is also a big challenge.

2. Alignment of requirements and tests 

Requirements need to be linked up with tests for them to be properly integrated into the mainline, aligning them proved to be a challenge for the studied company. Previously, testing was mainly focused on the end of a sprint. However, the introduction of continuous integration has turned their attention from functional testing to every integration. One software developer argues that it is tough to sync requirements that need to be tested together when integrating.

3. Customer value 

Breaking down software requirements into small enough units to support the integration of code more frequently, while maintaining a competitive advantage in the market and the value of the customer is a very tricky thing. Previously, breaking down requirements was up to system manager, because they have more knowledge. Now, this task is performed by the product owner and the team. Although this will improve access to the customer, many developers feel there is still more work to be done according to an agile coach.

4. Guiding principle 

For the interviewees, no clear process and guidance is a challenge. Since without guidance, how to break down requirements is decided by the teams. Although no unified process has been welcomed by most of the team, especially the more mature team, some of the young team think the lack of a uniform process will make their transition more difficult.


For RQ3: How could the breakdown of software requirements influence the adoption of continuous integration? 

1. The necessity of software requirements breakdown 

When teams are producing new features, they will face more difficulties while transitioning to continuous integration compared to teams that are mainly maintaining existing code and fixing bugs. Teams will face more difficulties while using continuous integration due to the issues when breaking down requirements.

2. Implications of software requirements breakdown 

a. Implementation dependencies 

Continuous integration promotes highly integrated frequency, software requirements may need to be divided accordingly. However, dependencies within the execution of said requirement might benefit from being developed as a whole unit. In addition, implementation dependencies might not be determined prior to the actual development.

b. Test dependencies 

Test dependencies play an important role when breaking down the software requirements into smaller units. If you want to integrate these small units separately, they need to be tested individually.

c. Integration scope 

The results showed that defining the correct scope of integration is important. Result suggest that the code should be integrated to provide customers with new value and contribute to the growth feature.

Overall, the software requirements, as well as their breakdown play an important role in the use of continuous integration process, especially with respect to an increased integration frequency. Those who want to transition to the continuous integration companies can use these challenges as a checklist to reduce the risk.
