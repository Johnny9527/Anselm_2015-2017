## Customer Requirements:

Our customer (Lanner Inc.) has already been using Oracle Agile PLM System for a while, however, they only purchased for PC and PPM modules. 
Along with the expanding of departments, our customer wanted to import another module, which is called PQM, to surveillance the product producing process
and to handle the product quality-related issues.

![](https://github.com/Johnny9527/Anselm_2015-2017/blob/main/Pictures/PQM.png)
↑ PQM module within the PLM System


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




## Solution Delivery:

