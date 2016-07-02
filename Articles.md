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


####“A market-driven requirements engineering process: results from an industrial process improvement programme” 
REPEAT is a requirement engineering process that manages requirements in the whole release cycle. It has the following states in the REPEAT process: 
New: The start state of a requirement. It has been issues and will be given an initial priority.
Assigned: Assigned the requirements to the expert for classification. 
Rejected: It is the end state means the requirement has been rejected. The reason is like it is a duplicate, it has been implemented or it dose not met the strategy. A selected requirement may be deselected because of the requirements change and it will be back to the classification state or rejected. 
Applied: The end state means that the requirement has been implemented and verified. 
Selected: The requirement has been selected for implementation. 
Each REPEAT has five phases separated by milestones. First is the elicitation phase. It includes two activities: collection and classification. Requirements are described using natural language and the issuer given a summary name of the requirements. Expert will classify the requirements based on the priority, cost estimate, and impact estimate. Secondly, selection phase will select which requirements to implement in the current release and specify the selected requirements more detail. And then, validate the requirement document. After this phase, there will generate a requirement document includes a select list, a detailed specification of all the selected requirements and a list of not selected requirements. Thirdly, Change management, construction, and verification. Last, in the conclusion phase, metrics are collected and a final report that summaries the lessons learned will be done. 
There are also some challenges for REPEAT, like Overload control , Connecting fragments, Bridging the chasm between elicitation and selection, and Long-term product strategy for a diversity of market segments. To reduce these challenges, two techniques are added to REPEAT-2: Hierarchical use case modelling, and Cost-value use case prioritisation.


#####Reference
[6] S. Park and J. Nang, “Requirements management in large software system development,” in SMC’98 Conference Proceedings. 1998 IEEE International Conference on Systems, Man, and Cybernetics (Cat. No.98CH36218), 1998, vol. 3, pp. 2680 – 2685 vol.3.
[7] J. Karlsson, S. Olsson, and K. Ryan, “Improved practical support for large-scale requirements prioritising,” Requirements Engineering, vol. 2, no. 1, pp. 51 – 60, Mar. 1997.
[8] S. Konrad and M. Gall, “Requirements Engineering in the Development of Large-Scale Systems,” in 16th IEEE International
