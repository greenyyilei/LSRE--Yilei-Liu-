###•	What is large scale requirements engineering? 
The project that has less than 1000 requirements[10]. The project has a complex structure and a variety of sources of requirements. 

#####Reference

[10] B. Regnell, R. B. Svensson, and K. Wnuk, “Can We Beat the Complexity of Very Large-Scale Requirements Engineering?,” in Requirements Engineering: Foundation for Software Quality, B. Paech and C. Rolland, Eds. Springer Berlin Heidelberg, 2008, pp. 123–128.


####“A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”
This paper is a case study of the QUPER model. It presents the detailed practical guidelines of how to use QUPER and added introduction of how to incorporate cost dependencies between QR. And then, they use the detailed guidelines to evaluate QUPER’s applicability with real QR. It also discussed how to define the breakpoints and barriers and the different important level of the three levels. 

This section showed the practical guidelines of QUPER. 1) Identify candidate QR which considered relevant features, market segment, competitor and hardware platform capability. 2) For each selected QR, define a scale and a measurement unit to express the level of quality of QR. 3) Identify reference levels for each QR based on actual products. 4) Define market expectations to elicit quality breakpoints. 5) Estimate the cost in terms of the cost barriers. 6) Propose candidate requirements, discuss and decide actual requirements for the coming release. 7) If cost dependencies between QR are considered important for cost estimations, identify which module needs to be changed if that QR will be improved beyond the “next” breakpoint.

The evaluation shows that the QUPER model is easy to understand, improves the understanding of QR,  and doesn’t take too much time to apply in practice. In the three views, roadmap view is the most important view, benefit view may be helpful for specifying QR, and cost view is the least important view. 


####Read up on GAP / CVA / IVA Analysis!
#####GAP Analysis[3][4][5]

A gap analysis is a method of assessing the difference between actual performance with the potential or expected performance.  Gap refers to a requirements analysis, requirements assessment or requirement-gap analysis. In software development, gap analysis can show which requirements are missing, which are delete and which are still need to be development. Gap analysis is task that requirements managers perform in order to ensure the scheduled product functions are covered by the appropriate platform project[4]. The goal of GAP analysis is to ensure the misalignments between market requirements and supplier requirements are addressed[4]. 

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

#####CVA analysis

CVA(customer value analysis) is similar to GAP but includes the perspective of using competitor products in the analysis. CVA can be used to verify the perceived customer value and measure the selection quality post-release[3]. 

A large number of meaningful user feedback to understand the market needs is crucial[6].

Customer value is created by[6]:

1. Select the most important value drivers

2. Based on the most attention factors, proposing a value proposition that you are able to provide.

3. Setting product pricing that is equivalent to the perceived value provided.

The conjoint analysis tools can be used to complete the CVA analysis[3].

CVA is a powerful tool that can be used to define a company's products and service as it provides a better understanding of what customers value most[6]. It provides the company a perspective that they can compare their performance with their competitors[6]. This information allows managers to improve products’ quality on area where it will be most beneficial and pertinent to its respective customers[6].

#####IVA analysis

Internal value analysis is a technique to evaluate whether a product is in line with the product strategies and his company's strategy, taking the limited resources and other  products into account[1][2]. IVA analysis considers the time, money, risk, and knowledge, the complementing data from GAP and CVA, requirements prioritization, dependency mapping and cost estimate[7]. I think, IVA can be a good assessment of the entire production process, reduce the gap to reducing the risk of product failure.

All the three tools help the company choose between products and keep a balance between high risk-high reward and low risk-low reward development. 

#####Reference
[1] S.A. Ross, R. Westerfield, B.D. Jordan, Essentials of Corporate Finance, Third ed., McGraw-Hill, Boston, 2001. 

[2] .H. Mintzberg, B.W. Ahlstrand, J. Lampel, Strategy Safari: A Guided Tour through the Wilds of Strategic Management, Free Press, New York, NY, 1998. 

[3] A. Gomes and A. Pettersson, Market-Driven Requirements Engineering Process Model – MDREPM. 2007.

[4] K. Wnuk, “Understanding and Supporting Large-Scale Requirements Management.”

[5] K. Wnuk, B. Regnell, and L. Karlsson, “What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting,” in Requirements Engineering Conference, 2009. RE ’09. 17th IEEE International, 2009, pp. 89–98.

[6] Customer Value Analysis: How Customers Make Purchase Decisions. (2015, June). Retrieved from http://www.slideshare.net/jmckeever/customer-value-analysis-how-customers-make-purchase-decisions-pdf

[7] T. Gorschek and A. M. Davis, “Requirements engineering: In search of the dependent variables,” Information and Software Technology, vol. 50, no. 1–2, pp. 67–75, Jan. 2008.

####• What tools are available for Continuous Integration? 

#####– Try one out (build something, have it run tests automatically, . . . ), and write up your experiences. 

In software engineering, Continuous Integration (CI) is the practice of consolidating copies of all developer work multiple times a day into a shared mainline [9].

The features of Continuous Integration 

It is a cyclical automatic integration testing process, checking code, compile building, test running , result recording, and test statistic are all automatically, without human intervention. It needs a dedicated server to perform an integration build and code hosting tools to support. 

The role of Continuous Integration

It guarantees the quality of the submitted code, reducing the pressure on the software when it is published. Each step of continuous integration is done automatically, without much human intervention, and helps to reduce the repetitive processes to save time, cost and effort.

The following are two tools for CI: 

######Jenkins[8]

Jenkins has two main tasks: building/testing software projects continuously and monitoring externally-run jobs. 
Jenkins is a service from third-party vendors. But if you have a big list of software need to be tested, it may be better to run it on your own server. It not only gives the infrastructure issue full control but also help for companies worried about  software security.

######Buildbot[8]

Buildbot is developed in Python and based on the Twisted framework. It began as an alternative to the Tinderbox project. Now it is used in Mozilla, Webkit, Chromium, and others. The ideology behind this setup is that most CI tools have a fixed fundamental design and limited to the basic design tools envisaged by the author. But use cases may have those assumptions to be violated.

Travis CI, Strider, and Integrity are all common tools for continuous integration. 

######My experiences of using Jenkins: 

Easy to install: We only need to download the latest jenkins.war files from the Jenkins home page and then run java -jar jenkins.war. We don’t need to install the database;

Change support: Jenkins can acquire and generate the code update lists  from the code repository (Subversion / CVS) and outputs to the compiler output information.

Easy to configure: Jenkins provides rich management and configuration functions, including system configuration, management plug-in, view system information, system log, node management, Jenkins command line window, information statistical and other functions. When I tried it, I found Jenkins very useful.

Support permanent link: Users access Jenkins via web, and these web page link addresses are permanent link addresses, so you can use these links directly in various documents.

Support distributed build: Jenkins can distribute integrated construction work to multiple computers to complete.

Support third-party plug-ins: Jenkins also provides a wealth of plug-in support, which makes Jenkins become more and more powerful. We can easily install a variety of third-party plug-ins, thus facilitating a quick integration of third-party applications. For example, Jenkins provides a plug-in for IBM Rational ClearCase support.

#####Reference
[8] “6 top continuous integration tools,” Opensource.com. [Online]. Available: https://opensource.com/business/15/7/six-continuous-integration-tools.

[9] “Continuous integration,” Wikipedia, the free encyclopedia. 31-Aug-2016.

####What is technical product management?

Gap between Management and Technical Management[10]

Requirements can be seen as the-least-common-denominator on which decisions affecting what to include in the product offering is decided. This makes communication between management and technical management important. All parties should participate in the decision-making process from the early triage to the final selection. In addition, all parties have a lot of requirements in their own sources. Due to these reasons, the process MDRE needs to provide decision support material, multiple roles, to encourage and support cooperation and joint work.

In reality, the term Technical Product Manager describes a person, rather than a role. It does not describe a product manager who needs to implement technical tasks, such as software architecture design and coding. They did not actually develop the product, they just closing the coordination in the software development team as a product manager[11].

Technical Product Manager Do’s[11]:

1. Focusing on the role of the business side.

2. Using your skills to improve prioritization and planning.

3. Using your professional skills to bridge the communication between engineering and the rest of the world.

Technical Product Manager Don’t’s[11]:

1.  Don’t design/solution the product yourself.

2. Don’t take on non-Product Management deliverables.


#####Reference

[10]Gorschek T (2006) Requirements Engineering Supporting Technical Product Management. Doctoral Dissertation Series No. 2006:01. Blekinge Institute of Technology.

[11] D. Elizalde, “What is a Technical Product Manager, Anyway?,” MindTheProduct, 12-May-2014. [Online]. Available: http://www.mindtheproduct.com/2014/05/technical-product-manager-anyway/. 


####• What is roadmapping? How can you do it large scale? 

A roadmap draws a timeline of what things will happen, combined with different aspects of product strategies, such as commercial and technological[14]. In other words, the product roadmap can be used to maintain attention on the long-term intentions, which are often defined at a high level (organizational strategies), as well as keeping the focus on the right issues that reflect these intentions (product strategies)[14]. The aspects of markets, products and technology can be included in a roadmap and are usually use a time-based chart to represent these activities when it happens in the lifecycle[14]. Since the roadmap is built upon a long-term perspective, among others, marketing information it is important to frequently update and review these[14]. 

There are many types of roadmaps. Product-Technology Roadmap is suitable for MDRE[15]. Developing a roadmap has three main purposes[12]. It helps reach a consensus comprising a series of requirements and the technologies required to satisfy those requirements, it provides a mechanism that can help predict the development of technology, and it provides a framework to help plan and coordination of technical development [13].

In my opinion, to do large-scale product roadmap needs to consider many factors, including product attributes, the dependency between product characteristics, product cycle, the characteristics of competitors, market value, market share and other factors. Because the complexity of large-scale products is very high, so the mutual influence between the characteristics of the product is very large. Based on [16], self-awareness and self-adaptation have become primary concerns in large-scale systems, we can conclude that modeling dependencies between resources, goals, and activities increase system efficiency and effectiveness will make the expected results can be predicted more precisely.

#####Reference

[12] Laube, T. and Abele, T. (2005). Technologie-Roadmap: Strategisches und taktisches Technologiemanagement. Ein Leitfaden. Fraunhofer-Institut Produktionstechnik und Automatisierung (IPA), Stuttgart, Germany. ISBN 3-8167-7186-6

[13] “Technology roadmap,” Wikipedia, the free encyclopedia.

[14] A. Gomes–andrigo, A. Pettersson, and T. Gorschek–tony, “Market-Driven Requirements Engineering Process Model–MDREPM,” 2007, version 1.0.”

[15] K. Wnuk, “Understanding and supporting large-scale requirements management,” LU-CS-LIC, vol. 2010.

[16] S. Dustdar, C. Dorn, F. Li, L. Baresi, G. Cabri, C. Pautasso, and F. Zambonelli, “A Roadmap Towards Sustainable Self-aware Service Systems,” in Proceedings of the 2010 ICSE Workshop on Software Engineering for Adaptive and Self-Managing Systems, New York, NY, USA, 2010, pp. 10–19.


####How do you connect your requirements to your architecture?

Various approaches have been proposed to assist architects in transitioning from requirements to an architecture, or even (partially) automate this step[2]. They defined a more systematic technique[2]. They describe a method to transform the KAOS requirements model into a so-called Architectural Prescription Language (APL) specification, which is a high-level architectural model[2].

More recently, Pimentel [PLC+12] proposed a process for generating architecture models (expressed in the Acme language) from requirements model (expressed in i*), specifically adaptive systems[2]. The method is based on the STREAM [Luc10], and there are several methods proposed to assist architects in transitioning from requirements to an architecture, or even (partially) automating this step[2].

M. Svahnberg said that PQA can be used together with the FQA(Framework for Quality Attribute) and the FAS(Framework for Architecture Structure) to evaluate which architecture candidate best match the quality requirements of the system[1]. 

#####Reference

[1] M. Svahnberg, “An Industrial Study on Building Consensus Around Software Architectures and Quality Attributes,” Information and Software Technology, vol. 46, no. 12, pp. 805–818, 2004.

[2] Koen Yskout, (supervisors: Wouter Joosen, Riccardo Scandariato), “Connecting Security Requirements and Software Architecture with Patterns (Beveiligingsvereisten en softwarearchitectuur verbinden met patronen)”, Ph.D. Thesis, 19 April 2013

#### Can you connect all requirements directly? What do you do if you cannot? 

In market-driven development, requirements are usually generated from a variety of sources like internal (engineers) and external (partners and customers)[3]. As the source of the requirements is diversified, and the requirements themselves are both direct and indirect sources, it is very common for them to have different forms and multiple levels of abstraction, and described on varying levels of refinement[3]. 

Because there are many different levels and forms of requirements, so we cannot directly connect all the requirements. RAM is a requirement abstraction model that can be used to abstract requirements to complete the requirement's connection. RAM can abstract requirements in the same abstract level and they can be compared and set against one another. All the requirements can get a richer understanding through the abstract process. 

#####Reference
[3]T. Gorschek and C. Wohlin, “Requirements Abstraction Model,” Requirements Eng, vol. 11, no. 1, pp. 79–101, Nov. 2005.

####–  Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management of Software Requirements)  

This paper has mainly described the context and concepts of MDRE, and briefly compare it with the customer-specific development. 

Market-driven development is different from the bespoke development that the product is specific to the needs and wishes of one customer. MDRE refers to the situation where the product is offered to an open market with many customers, the development costs are divided among many buyers and the potential profit is rewarded to the producer. MDRE covers the classical RE activities like elicitation, specification and validation. It also covers the release management and market analysis which is specific to MDRE. The following are some differences between MDRE and bespoke development. 

MDRE:
1. The main goal of MDRE is to deliver the right product at the right time. 
2. In the MDRE, whether the product is success or not is decided by sales, market share, and product reviews. 
3. There is often one major release of MDRE and the product is continuous evolution rather than maintenance. 
4. In the NDRE, much effort is devoted to prioritization, cost estimation and release planning. 
5. Case validation in the MDRE is often delayed until a late stage of the development. 

Bespoke:
1. The main goal of the bespoke development is to realization of a contract and compliance to a requirements specification. 
2. Int the bespoke products, whether the product is success or not is determined by customer satisfaction and user acceptance. 
3. The lifecycle of the bespoke project is often divided into development first and then maintenance. 
4. In the bespoke development, much effort is devoted to negotiation and conflict resolution. 
5. In the bespoke development, validation is continuously doing through the contacts between the customer and the developers. 

There are some challenges in MDRE: find a good balance between technology-driven and need-driven requirements; communication and collaboration between marketing and development; requirements dependencies make release planning difficult; cost-value estimation. The key issue of MDRE is to continuously improve in managing these challenges to make it ahead of the competitors. 

The MDRE process quality is very important in requirements selection. The alfa/beta model of MDRE selection quality is used to capturing decision quality. An alfa requirement has a high inherent quality that it should be selected and a beta requirement has low inherent quality that should be rejected. It is not easy to find and select alfa requirements and rejecting beta requirements and it is difficult to know whether a requirement is an alfa or beta requirements as the cost-benefit trade-off is very difficult.  

There are two typical ingredients in MDRE data management. The requirements state model is used for requirements refinement progress tracking. There are two modes in the requirement state model. 

In the continuous mode, product manager receives and register all kinds of requirements. It includes the following steps:

Candidate: Each received requirements will have the status “Candidate”.

Approved: The requirements with status Candidate will be reviewed at regular time intervals. The requirements that are being accepted get the status “Approved”. This process is very difficult as it is hard to confirm the quality of the requirements. 

Specified: The previous description of the requirements is almost not very clearly and detail for planning and developing, then a more suitable and detailed specification is linked to the requirements. 

Discarded:  The requirements being rejected get the statusDiscarded. The reason report will be sent to the submitter. The discarded requirements are not deleted from the database to enable future analyses. 

In release mode, the release scope is frozen in order to manage the release development project. It includes the following steps:

Planned: The development team will consider about release date and human resources and maximum the number of planned requirements. All the selected requirements get the status Planned and are input for the design and coding process.

Developed: Development includes design, coding, unit tests and production of collateral materials. The requirements will get status Developed when all the activities are successfully completed. 

Verified: Software testing is used to verify the quality of project before it released. 

Released: The requirements will get the status Released when all the activities are completed and the submitter will get a notification. 

The requirements repository is used to store the relevant attributes of candidate requirements. Smaller project will need a simple spreadsheet and large-scale project will need requirements management tool due to the volume of requirements. 

####–  Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering” 

The purpose of this study is to deepen the understanding of the factors leading to overscoping, increased the attention to this risk, and use some steps addressing and avoiding overscoping in the project. In this article, case study is divided into three step. The first step, according to one of the authors’ industry experience, established a hypothesis about possible cause of overscoping and possible effects of overscoping. This hypothesis, as the starting point of the interview appeared in the second step. The third step, the interview results were validated by using a questionnaire to six other employees from the same company.

The results pointed out that overscoping is a challenge for requirements engineering and project management. For the case company, overscoping is mainly caused by the fast-moving market-driven domain. In the early software development phase, low participation of relevant developers for the development of the overall goal will lead to a lot of unrealistic project scope. Our research indicates that overscoping may lead to a lot of negative effects, such as quality problems, delays or cannot meet the target expectations of customers. Delay and quality problems are very expensive. This will not only need to spend money to repair but also lose market share and brand value. We found that overscoping can lead to more overscoping and other issues, such as communication gaps. For the case company, despite increasing agile RE practices, overscoping is still a problem. We conclude that improvement needs continuous optimisation the project scope, combine with implementation cost and schedule estimates, close cooperation of cross-functional teams, thereby reducing the communication gaps. Conclusions of this paper can be used to define the potential factors in order to achieve more realistic project scope.

####		–  Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”  
This paper use case study and survey to investigate the factors affecting decision outcome and lead-time in LSRE. The decision lead-time is the time required to analyze the impact of a decision in this context. The decision outcome is a specific outcome of the decision process called acceptance or rejection under this context. To research in this area, there are three research questions and six hypothesis. After case study and survey among 50 practitioners, they conclude some results. When the decision affects more products, the lead-time to make a decision will increases.  Decision maker should know more complex decisions may take more time. According to the statistical analysis of the decision log, it is more likely to accept the issues of changing requests by important customers. At the same time, the lead-time to accept a decision is shorter than to reject a decision. The number of products affected by a decision increases the decision lead-time. Due to a more complex decision take more time, it is wise to decrease their complexity for faster decision. 

####		–  P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Natt och Dag, “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE Interna- tional Symposium on Requirements Engineering, 2001.  

This paper provides an industrial survey in five companies and analysis their requirements’ interdependencies. We found that only about 20% of the requirements are singular. And 20% of the requirements are involved in 75% of all interdependencies. Customer-Specific bespoke product tends to more functionality-related dependencies, while market-driven product tends to value-related dependencies. 

In each case, managers are randomly select 20 high priority requirements from the current requirements repository. Based on these cases, there are six commonly used interdependencies of requirements: 

R1 AND R2: means R1 requires R2 to function and R2 requires R1 to function. This is functional-related and is suitable for the bespoke development.

R1 REQUIRES R2: means R1 requires R2 to function but not vice versa. This is functional-related and is tend to be in a bespoke development environment. 

R1 TEMPORAL R2: means either R1 has to be implemented before R2 or vice versa. 

R1 CVALUE R2: means R1 affects the value of R2 for a customer and the value may be either positive or negative. From a product planning view, this relationship is important. It is value-related and is tend to be in a product development situation.  

R1 ICOST R2: means R1 affects the cost of performing R2 and the value could be either positive or negative. In some cases, CVALUE and ICOST are relevant. For instance, R1 increase the value of R2 for the customer, but it increases the cost of implementing R2 at the same time. It is value-related and is tend to be in a product-oriented case. 

R1 OR R2: means only on of R1, R2 needs to be performed. 

In some cases, two requirements may have more than one relationship. In the product development perspective, the value-related interdependencies are more common than functionality-related. However, in the bespoke development, functionality-related interdependencies are more common than value-related. To support the release planning, a simple visualization technique is applied to the requirements and their interdependencies. It is a powerful tool and is good for release planning. Requirements having no relationship with others are easily spotted and free clusters can be scheduled for any increment in which requires all involved requirements are scheduled for the same increment. Requirements having interdependencies with others should be implemented at early stage and they should be scheduled for the same release in order to simplify realisation and reduce the risks.  

Company: the main goal in this level is to maximize the total economic benefits of the products. This level is closely related to the scope of the product. It is essential to make an overview of the whole product portfolio includes what have already deployed, what is under development, and those just being planned. GAP, CVA, and IVA can help the company choose between products and keep a balance between high risk-high reward and low risk-low reward development.  It includes three measures: portfolio management, strategic alignment, and the degree of impact. 

Society: the company also has a great responsibility to the society. Although the company may provide grate benefits to its stakeholder, but it pollutes the environment or kills people have to be considered a failure.  It always considers about the positive and negative externalities. This means neither the developer nor the customer has to bears all the costs or get all the benefits generated by the products. When conducting company strategies, the company can try to maximize the positive effects of their product.

This paper also suggests that product strategies should reflect long-term goals, and the goals also have to meet the current market and technology trends.  

####—-Obsolete software requirements Krzysztof Wnuk, Tony Gorschek, Showayb Zahda 

In this paper, we use empirical investigation to define the phenomenon of obsolete software requirements, investigate the potential impact and how they are resolved in industry. We have 219 respondents from 45 countries who are industry practitioners. This paper proposed seven research questions. The questionnaire was created based on a literature review of relevant papers.

RQ1: Based on empirical data, what would be an appropriate definition of Obsolete Software Requirements (OSR)? 
Based on the results of the questionnaire, our respondents defined an OSR as follow: “a software requirement (implemented or not) that is no longer required for the current release or future releases, and it has very limited business value for the potential customers or users of a software artifact.’’ When consider demographics’ impact, The definition of OSRs is not significantly connected to the size of the companies, the length of the typical project, or the domain.

RQ2: What is the impact of the phenomenon of obsolete software requirements on the industry practice? 
When asked about the potential impact of OSRs to their product development, in all respondents, 84.3% considered serious or somehow serious. This indicates that most respondents believe OSRs seem to have a significant impact on the product development. For 6% of respondents, OSRs is a very serious problem, while 10% deemed OSRs a Trivial matter. Those respondents who think OSRs serious, mostly worked in large companies and used agile development. Those who considered trivial, more than 80% worked in large companies. Because the big companies tend to use more complex process models.

RQ3: Does requirement type affect the likelihood of a software requirement becoming obsolete? 
According to the respondents, requirements related to standards, laws and regulations are the least probable to become obsolete. Compare with requirements originating from customers developers, requirements originating from domain experts were less probable to become obsolete.

RQ4: What methods exist, in industry practice, that help to identify obsolete software requirements? 
More than 50% of the respondents proposed that manual ways of discovering OSRs are the main method. At the same time, demographic factors have no significant impact on this question. OSRs identification is mainly a manual activity, less than 10% of the respondents said they have any automatic functionality.

RQ5: When OSRs are identified, how are they typically handled in industry? 
For managing OSRs, there are some existing processes and practices. When considering this, 73.6% of respondents said they did not consider the needs for manage OSRs during their requirements engineering process. At the same time, 73.6% of respondents said they did not have any procedure to deal with OSRs. This result can be used as clear evidence of a lack of industry-related OSR processing method, and confirms the need for developing methods for managing OSRs. According to the survey answers, more than 60% of respondents think that the identified OSRs should be kept in the requirements document or database, but marked as obsolete. Removing OSRS is an undesirable behavior.

RQ6: What context factors, such as project size or domain, influence OSRs? 
The result indicates that the larger the projects, the more likely to have a negative impact from OSRs. OSRs are more likely to affect large-scale requirements project and very large-scale requirements projects.
The results from the average score shown that outsourcing project is most likely to be affected by the OSRs. Compared to bespoke or contract-driven development, OSRs seem to have a larger impact on an MDRE environment. However, for very large projects all respondents, independent of the environmental factors, the potential impact of OSRs is huge.

RQ7: Where in the requirements life cycle should OSRs be handled? 
According to our respondents' answers, OSRs should be first handled during the requirements analysis phase, requirements validation phase and requirements changes phase. Our respondents also suggested that requirements elicitation is not the best stage to manage OSRs.

Our results show that OSRs is a significant challenge for software system development. 84.3% of the respondents considered that OSRs are serious. In addition, a clear majority of respondents said there are no useful methods or tools to support the identification and treatment for OSRs. Only 10% of the respondents said they have automated support. This suggests that there is a need to develop automated methods or tools to support practitioners identify and manage OSRs.

####- Assessing challenges of continuous integration in the context of software requirements breakdown: a case study 

In this paper, Ericsson as an example, based on case studies and interviews to determine the challenges of continuous integration and requirements break down, and how the latter affects the implementation of the continuous integration process.

In order to support more frequent integration, requirements need to be small enough so that the developer can provide individually tested per day, and integration times. Under continuous integration environment which is not always an easy task. So breaking down large user stories into smaller one with the right level of detail and visible business and customer value has been identified as a challenge. 

This article only establishes a case study in which the focus and case is an organization. Thus, the unit of analysis is the teams under study that are using continuous integration. From the methodological point of view, the study is from the perspective of interpretation. In this study, a semi-structured interviews were used to collect data. In this study conducts 13 interviews with eight participants from Sweden and five from China.

I will summarize the result based on the different research question.

For RQ1: What are the challenges of implementing a continuous integration process in practice?

There are seven main challenges from the result: developers’ mindset, domain applicability, testing, understanding of continuous integration, code dependencies, tools and infrastructure, and software requirements. 

In the opinion of respondents, mindset, tools and infrastructure are the most mentioned. People’s mindset and attitude play an important role when  adopting continuous integration. Similarly, tools, infrastructure and testing also have a significant impact on the success of implementing continuous integration. This means that the use of continuous integration can be considered to introduce a change in the existing software process.

For RQ2: What are the challenges of software requirements breakdown in practice?

This paper proposes four primary challenges. 

1. Requirements abstraction 

Requirements abstraction is a challenge for developers as they struggled with requirements that are either too large, ambiguous or too low level. In addition, details’ level and quality requirements depend on the type  of requirements. People tend to take shortcuts and not follow a uniform architectural design. This, in turn leads to difficult to estimate the impact of changes. A large number of sub-systems make coordination difficult and will increase the pressure of one developer. This makes requirement difficult to break down into smaller units that can operate independently. At the same time find the right balance when breaking large software requirements is also a big challenge.

2. Alignment of requirements and tests 

Requirements need to be linked up with tests for them to be properly integrated into the mainline, aligning them proved to be a challenge for the studied company. Previously, testing was mainly focused on the end of a sprint. However, the introduction of continuous integration has turned their attention from functional testing to every integration. One software developer argues that it is tough to sync requirements that need to be tested together when integrating.

3. Customer value 

Breaking down software requirements into small enough units to support the integration of code more frequently, while maintaining a competitive advantage in the market and the value of the customer is a very tricky thing. Previously, breaking down requirements was up to system manager, because they have more knowledge. Now, this task is performed by the product owner and the team. Although this will improve access to the customer, many developers feel there is still more work to be done according to an agile coach.

4. Guiding principle 

For the interviewees, no clear process and guidance is a challenge. Since without guidance, how to break down requirements are decided by the teams. Although no unified process has been welcomed by most of the team, especially the more mature team, some of the young team think the lack of a uniform process will make their transition more difficult.


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
