# Deploy MY-lab Stack 

Retrieval augmented generation (RAG) is an AI framework for improving the quality of LLM-generated responses by grounding the model on external sources knowledge to supplement the LLM’s internal representation of information.

On the Dashboard of the Cloud account, first make sure you are on the **itz-enablement-012 account (A)**.
    ![alt text](../images/0.0.0.png)

1. Expand the **Navigation menu (A)** on the upper right-hand corner. Select **Projects (B)**
![alt text](../images/0.1.1-n.png)

     **Projects** are a named collection of configurations used to manage resources and deployments across accounts, employing an Infrastructure as Code (IaC) approach. Projects allow teams to configure, deploy, and monitor deployments using DevOps best practices.


2. Select the **deployed project(A)** that corresponds to your group number (rag-stack-lab-##, where ## is replaced with your group number). <br>
For example: rag-stack-lab-00
![alt text](../images/0.1.2-n.png)

3. Switch to the **Configurations tab (A)**
![alt text](../images/0.1.3-n.png)

4. Click **Create (A)**
![alt text](../images/0.1.4-n.png)

5. You will be redirected to the Catalog, make sure you are on the **Community registry (A).**
![alt text](../images/0.1.5-n.png)

6. Find and select the **Retrieval Augmented Generation Pattern** <br>
![alt text](../images/tile.png)

Scroll down and take a minute to review the **Architecture Overview** tab. This will give you an even deeper understanding of what is deployed.

7. Select the **Basic variant (A)** and then click **Add to Project (B)** <br>
![alt text](../images/0.1.7-n.png)

8. Configure the DA <br>

    a. Make sure you are on **Add to existing (A)** <br>

    b. Make sure the **Select a project (B)** matches your group number.

    c. Change the Configuration name to **MY-lab-## (C)**, where the ## is replaced with your group number. <br> 
    For example: MY-lab-00
  
    d. Make sure the **environment (D)** corresponds to your group number. For this lab you will using a predefined environment configuration. 
    
    e. Click **Add (E)** <br>
![alt text](../images/0.1.8-n.png)

9. You will now need to update the prefix for your stack. Scroll down until you find the **Configure (A)**. Select the **Required (B)** tab.  
    
    You will need to update the **prefix (C)** (<ins>use all lowercase for the prefix</ins>) to **my-lab-##**, where ## is replaced with your group number. <br>
    For example: my-lab-00

    Click **Save (D)**.
![alt text](../images/0.1.9-n.png)

10. Once you have saved, select **View stack configurations (A)**. 
![alt text](../images/0.1.10-n.png)

11. You will be brought back to the projects list. Next to your newly created project **MY-lab-##** (where ## is replaced with your group number), you will need to click **validate (A)**. When you click validate a new window will appear, you can exit out of the window. Your project will now start deploying. 

    ![alt text](../images/0.1.11-n.png)
___

Congratulations, you have just deployed your own DA! For the remainder sections of the lab you will be viewing resources that were deployed by an already deployed stack and is ready for you to explore. This will provide valuable insight into how these resources integrate to form a secure and compliant generative AI (Gen AI) solution.