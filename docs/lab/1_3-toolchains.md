# Toolchains

At the Generative application layer, we need to make sure that we follow DevSecOps best practices to develop, test and deploy the Gen AI application on a secure infrastructure.

The Deployable Architecture Stack for the RAG Application includes DevSecOps for Application which is supported through IBM Cloud Toolchain Service the CI/CD/CC pipelines were used to deploy the application on Code Engine Services checking for vulnerabilities and ensuring audit-ability.

The (CI) pipeline is used to develop the application, using DevSecOps best practices including evidence collection, artifact signing, and vulnerability checks.

The (CD) pipeline supports continuous deployment of the application, including evidence collection, GitOps flow, change management, and compliance scans. Once deployed on Code Engine, we can launch the application and make it available for end users.
___

1. Expand the **Navigation menu (A)** and hover over **DevOps (B)** then select **Toolchains (C)**
![alt text](../images/1.3.1-n.png)

2. Make sure you are on the right **Resource Group (A)** that corresponds to your group number and select **Dallas for the Location (B).** Select the **rag-lab-##-CI-Toolchain (C)**, where ## is replaced with your group number. 
![alt text](../images/1.3.2-n.png)

3. Select the **ci-pipeline (A)**
![alt text](../images/1.3.3-n.png)

4. Select the **webhook-trigger (A)**
![alt text](../images/1.3.4-n.png)

5. Select the most recent successful pipeline run
![alt text](../images/1.3.5-n.png)

6. Click on **code-compliance-checks (A)**
![alt text](../images/1.3.6-n.png)

7. Select **run-stage (A)**
![alt text](../images/1.3.7-n.png)

8. ADD TEXT REGARDING WHAT THIS SECTION OF THE PIPELINE DOES