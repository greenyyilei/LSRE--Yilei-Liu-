####1. Requirements (classic/bespoke) 
######– What is a requirement?
In product development and process optimization, a requirement is a singular documented physical and functional need that a particular design, product or process must be able to perform[1].
A requirement is a condition or capability needed by a user to solve a problem or achieve a goal. 
A requirement is a condition or capability that must be met or possessed by a system or system component to satisfy a standard, specification or other imposed documents. 
In software engineering, requirement is the functional and non-functional need that software development must achieve. 
######– What is a good requirement? 
The characteristics of good requirements are variously stated by different writers. They may emphasize different characteristics that are most appropriate to their general discussion or the specific domain. There are some generally acknowledge[2][3].
Cohesive, Complete, Consistent, Atomic, Traceable, Current, Unambiguous, Specify Importance, Verifiable.
In my opinion, good requirements have two basic points: 
A good requirement should be necessary, verifiable, clear, and attainable[4].
Establish a common understanding between the project sponsor, developers, customers and other stakeholders. 
Improve customer confidence for the products. 
######– How do you write them?
There are some tips for writing good requirements[5]:
Each requirement should be atomic, define one requirement at one time. 
Each requirement must use a complete sentence without buzzwords or acronyms. 
Use correct, unambiguous terms and good grammar.
Write verifiable requirements.
Only describe what the system will do not how it will do.
Avoid ambiguity and do not speculate. 
Do not express suggestions or possibilities.
Do not refer to an undefined requirement. 
Track traceability in the process in the early phase and track the owner or source of the requirements. 
Requirements (large scale) 
######– How do you group them? – How do you store them? – How do you deal with them? – Where do you get them? – How do you connect quality requirements into the mix? 
##### Reference
[1] “Requirement,” Wikipedia, the free encyclopedia. 06-Jan-2016.

[2] Davis, Alan M. (1993). Software Requirements: Objects, Functions, and States, Second Edition. Prentice Hall. ISBN 0-13-805763-X.

[3] IEEE Computer Society (1998). IEEE Recommended Practice for Software Requirements Specifications. Institute of Electrical and Electronics Engineers, Inc. ISBN 0-7381-0332-2.

[4] Hooks, I. (1993). Writing Good Requirements (A Requirements Working Group Information Report). In Proceedings of the Third International Symposium of the NCOSE - Volume 2. 

[5] “15 Tips for Writing Better Requirements,” Business Analyst Learnings. [Online]. Available: http://businessanalystlearnings.com/blog/2013/7/26/15-tips-for-writing-better-requirements.

[6] S. Park and J. Nang, “Requirements management in large software system development,” in SMC’98 Conference Proceedings. 1998 IEEE International Conference on Systems, Man, and Cybernetics (Cat. No.98CH36218), 1998, vol. 3, pp. 2680 – 2685 vol.3.

[7] J. Karlsson, S. Olsson, and K. Ryan, “Improved practical support for large-scale requirements prioritising,” Requirements Engineering, vol. 2, no. 1, pp. 51 – 60, Mar. 1997.

#####2. Homework 
######•	What is large scale requirements engineering? 
The project that has less than 1000 requirements[6]. 
######•	What are the challenges in large scale requirements engineering? 
Large number of customer requirements
Formal communication and interface to customer. 
Technology changed during the time.
Project teams were distributed geographically.
In long-term projects, resource fluctuation is a challenge.
Long-term product strategy for a diversity of market segments.

######•	What is the order of magnitude of the number of requirements we are discussing? 
Pair-wise comparison: This approach prioritises requirements in two dimensions: value of the requirements, and their cost of implementation. It is effectively and accurately[7]. 

#####•	Read and summarise 
######“The art and science of release planning”
A good release plan should provide maximum business value, satisfy the most important stakeholders, use the available resources and present the existing dependencies between features. There is two approaches for release planning. The are of RP realise on human intuition, communication and the capabilities to coordinate between conflicting goals and constraints. The science of RP formalizes the problem and use computational algorithms to make best solutions. But they all have disadvantage. The art-based approach can not deal with the RP problem’s complexity as the number of factors grows. The science-based approach can not consider the problem from the human decision maker’s view. The hybrid approach is in a high-level framework for release planning. Firstly, modelling to make it suitable for computational intelligence based techniques. Secondly, exploration. We will generate the solution plan based on the formal model and developed integer programming algorithms to explore the spoliation space and find the alternative solution. Thirdly, consolidation the result. The decision maker will evaluate the alternative solution of the  algorithms based on the experience and the problem context. 

######“Introducing support for release planning of quality requirements–an industrial evaluation of the QUPER model” 
   This paper is an industrial evaluation of the QUPER model at Sony Ericsson. The goal of this model is solve the constraints between quality and cost. Quality performance (QUPER) model has several steps: 1) define the quality indicators 2) define current market expectations. In this step, we will estimate the breakpoints and carries for the benefit view and cost view. 3) identify the quality level of reference products. 4) estimate targets for future release. 5) create roadmaps. 6) revise and update roadmaps. 
The QUPER model has three views that can help the companies understand better of the necessary requirements of their products.
The benefit view: there are three breakpoints that show the main changes in the benefit level. The utility breakpoint marks the border of quality from useless to useful. The differentiation breakpoint marks the level of the quality is in a competitive position. The saturation breakpoint marks the product is excessive that higher quality level has no practical impact on benefit. 
The cost view includes cost barriers that present the non-liner relationship between quality and cost. A barrier occurs when the quality cost shift from a low level to a high level. 
The roadmap view combine the first two views by putting the breakpoints and carries in the same scale. The goal of this view is to compare the quality of our product and the competitor’s and make some targets for the future releases. 
The challenge in definition is difficult to define and specify the value for the differentiation and saturation breakpoints. 
######“A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”
This paper is a case study of the QUPER model. It presents the detail steps of how to use QUPER. It also discussed how to define the breakpoints and barriers and the different important level of the three levels. The study shows that the QUPER model is easy to understand and use and the applicability of the cost dependency. 

######“A market-driven requirements engineering process: results from an industrial process improvement programme” 
REPEAT is a requirement engineering process that manages requirements in the whole release cycle. It has the following states in the REPEAT process: 
New: The start state of a requirement. It has been issues and will be given an initial priority.
Assigned: Assigned the requirements to the expert for classification. 
Rejected: It is the end state means the requirement has been rejected. The reason is like it is a duplicate, it has been implemented or it dose not met the strategy. A selected requirement may be deselected because of the requirements change and it will be back to the classification state or rejected. 
Applied: The end state means that the requirement has been implemented and verified. 
Selected: The requirement has been selected for implementation. 
Each REPEAT has five phases separated by milestones. First is the elicitation phase. It includes two activities: collection and classification. Requirements are described using natural language and the issuer given a summary name of the requirements. Expert will classify the requirements based on the priority, cost estimate, and impact estimate. Secondly, selection phase will select which requirements to implement in the current release and specify the selected requirements more detail. And then, validate the requirement document. After this phase, there will generate a requirement document includes a select list, a detailed specification of all the selected requirements and a list of not selected requirements. Thirdly, Change management, construction, and verification. Last, in the conclusion phase, metrics are collected and a final report that summaries the lessons learned will be done. 
There are also some challenges for REPEAT, like Overload control, Connecting fragments, Bridging the chasm between elicitation and selection, and Long-term product strategy for a diversity of market segments. To reduce these challenges, two techniques are added to REPEAT-2: Hierarchical use case modelling, and Cost-value use case prioritisation.


