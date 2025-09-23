<img width="940" height="735" alt="image" src="https://github.com/user-attachments/assets/d48b0452-63f9-4459-9d51-bced99947405" /># coredata-azuredatafactory

🚀 Azure Data Factory - Simple Pipeline Demo
Welcome to the coredata-azuredatafactory repository!
This project contains step-by-step code, configuration, and screenshots for building a simple data pipeline using Azure Data Factory (ADF).

🌟 Project Overview
This guide walks you through:

Setting up an Azure Data Factory and Storage Account

Integrating GitHub for version control

Creating, configuring, and running a basic pipeline that copies data between containers

Monitoring pipeline runs and validating the results

Whether you’re brand-new to ADF or looking to see how simple cloud data engineering can be, you’ll find this repo useful!

🛠️ Prerequisites
Azure Subscription

GitHub Account

Basic understanding of Azure Portal navigation

Azure Storage Explorer (optional for blob file checks)

📝 Quick Steps
1. Create Your Azure Data Factory
Go to Azure Portal → "Create a resource" → "Analytics" → "Data Factory"

Enter unique name, region, and resource group

Click Review + Create

Deploy & Go to Resource

<details> <summary>📸 Click to view create Data Factory screenshot</summary> <img width="940" height="852" alt="image" src="https://github.com/user-attachments/assets/762d9f71-d8f2-47d2-9433-44f30c9d1dee" /> </details>

<details> <summary>📸 Click to view create+review screenshot</summary> <img width="940" height="906" alt="image" src="https://github.com/user-attachments/assets/9b333372-541d-4731-8186-8b5625fc3505" /> </details>


2. GitHub Integration
Create a GitHub repo (private or public)

Link your ADF to your GitHub (for versioning & collaboration)

Authorize access

<details> <summary>📸 Click to view authorization screenshot</summary> ![GitHub Connect Example](screenshots/<img width="925" height="1350" alt="image" src="https://github.com/user-attachments/assets/64da1373-d11f-4f3e-a361-63c53213f5e5" /> </details>


3. Launch Data Factory Studio & Open the ADF Studio and explore the homepage layout!Open the ADF Studio and explore the homepage layout!

<details> <summary>📸 Click to view ADF studio screenshot</summary> <img width="940" height="718" alt="image" src="https://github.com/user-attachments/assets/6917d84e-fde3-41d1-a7f0-c413e1cfd6b3" /> </details>


4. Create a Storage Account (Source/Sink)
Azure Portal → "Storage Account" → "Create"

Configure name, redundancy, and region

<img width="940" height="1000" alt="image" src="https://github.com/user-attachments/assets/5506a107-0fae-4fa5-a9b5-bbf5eb451e4d" />


Click Review + Create and deploy

![Storage Account Example](screenshots/<img width="940" height="963" alt="image" src="https://github.com/user-attachments/assets/70a9a90d-af55-4d51-9345-b946e5e04442" /> )


5. Build & Configure Your Pipeline

Create a pipeline named data_copy_pipeline

Add source and sink datasets:

Source: Input file (test_data.txt)

Sink: Output file (test_data_out.log)

Configure datasets to use Azure Blob Storage

<details> <summary>📸 Click to view Pipeline Overview screenshot</summary> <img width="940" height="741" alt="image" src="https://github.com/user-attachments/assets/a99fd9f3-ab7e-4c25-82b2-e0d7a3b29679" /> </details>


6. Link Services for Source & Sink
Set up linked services that connect your datasets to the storage account (set the container, path)

![Linked Service Example](screenshots/linked-service 


<details> <summary>📸 Click to view Linked Services creation screenshot</summary> <img width="940" height="1283" alt="image" src="https://github.com/user-attachments/assets/52341ec8-2818-4fbb-bf0e-a7581485f8e5" /> </details>

<details> <summary>📸 Click to view input dataset screenshot</summary> <img width="940" height="387" alt="image" src="https://github.com/user-attachments/assets/8b8bd1af-96bb-40fd-91ba-51ac03b9e620" /> </details>

<details> <summary>📸 Click to view output dataset screenshot</summary> <img width="940" height="442" alt="image" src="https://github.com/user-attachments/assets/da471a98-c717-4c89-9249-337bbc10b45b" /> </details>


7. Trigger & Monitor Pipeline

Trigger the pipeline using Trigger now

Monitor run status under Monitor → "Pipeline Runs"

Review activity runs and logs for details

<details> <summary>📸 Click to view Pipeline run screenshot</summary> <img width="940" height="329" alt="image" src="https://github.com/user-attachments/assets/086c81aa-c97d-4775-afa0-0e423a013db7" />  </details>

<details> <summary>📸 Click to view Activity run creation screenshot</summary> <img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/3f2d797f-019f-471f-8787-a3a0a48e0fd7" />  </details>
 
![Run detailed log]( <img width="940" height="735" alt="image" src="https://github.com/user-attachments/assets/4a1e9d2b-2c70-4c68-8c23-98c0028fc7e3" />

8. Verify Output
Check the output blob in the sink container (test_data_out.log)

Use Storage Explorer or Azure Portal (Blob storage) to confirm the results

![Sink File Example]( <img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/19c19249-6e9b-4fb8-b823-64ed5bc7f1b2" />



📖 For a Detailed Guide
📝 Read the full step-by-step blog here:
Full Tutorial & Explanations »
(https://dev.to/arunkumar_panneerselvam_2/azure-data-factory-building-a-simple-pipeline-step-by-step-guide-ilb)

🙋 Feedback & Questions
Feel free to open an issue or submit a pull request if you spot anything that can be improved.

💬 Share & Stay Connected
If you like this repo, star it ⭐ and share with friends!

“Keep transforming data, keep transforming yourself!” 😊

Happy building with Azure Data Factory!
