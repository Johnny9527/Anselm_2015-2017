## Customer Requirements:

Our customer (Lanner Inc.) has already been using Oracle Agile PLM System for a while, however, they only purchased PC and PPM modules. 
Along with the expanding of departments, our customer wanted to import another module, which is called PQM, to surveillance the product producing process
and to handle the product quality-related issues.

![](https://github.com/Johnny9527/Anselm_2015-2017/blob/main/Pictures/PQM.png)
↑ PQM module within the PLM System

* Annotation: 
  * PC modules, which is an abbreviation for Product Collaboration, offers basic functions such as "Parts", "Components", "Documents", "Bill of Materials (BOM)", "Workflows", "Approved Manufacturer List (AML)", and "Approved Vendor List (AVL)" management. It can improve the cooperation between different departments within the enterprise and shorten the product lifecycle by sharing real-time updated information through the PLM system. From the design phase of products to End of Life (EOL), PC module can provide our client with a complete record in every manufacturing procedure, lower the production cost, and enhances the merchandise quality.
  
  * PPM modules, which is an abbreviation for Product Portfolio Management, offers a perfect environment in controlling every project that runs by different Project Managers (PMs) throughout the company. It provides a clear Work Breakdown Structure (WBS) containing detailed task information and deadline, easily for engineers to follow, and handout deliverables on time. It also has a real-time resource monitor that can aid PMs to control the whole process and budget of each project. The dashboard function of PPM module also offers visualized diagrams for senior supervisors to quickly understand every project status within the company.


## System Design:

According to customer needs, we design a "three-workflows process" to meet this requirement.

![](https://github.com/Johnny9527/Anselm_2015-2017/blob/main/Pictures/PQMWorkflows.png)
↑ The "three-workflows process" we designed.

At the beginning of the first workflow, when the quality department receives a complaint or error report from whether a consumer or an internal operator, 
they can initiate a PSR form to record down the issue. After the PSR form is created and submitted, the director of the quality department will review 
the content of it then assign a specific engineer to deal with this issue by creating a QCR form. During the QCR process, the engineer has to review and 
fix the problem. If the engineer can fix this issue, he or she may record down the modification procedure or attach a report along with the QCR form, 
close it, and release it back to the PSR form, waiting for further examination. However, if the engineer finds out that this issue may affect the product 
structure, the engineer needs to implement another Engineering Change (EC) Form to inform another department's engineer (ex: EE or ME) taking care of 
and waiting for further instruction.

In the real project, we created 10 different forms and 10 corresponding workflows to handle their requirements. The "three-workflows process" above only
shows the basic concept of our solutions. In the real use case, it was way more complicated. As a consultant, I need to amend the system structure and 
workflows responding to our client's needs at all times. This requires lots of energy but also presents our value.




## Solution Delivery:

