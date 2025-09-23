# coredata-azuredatafactory

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

<details> <summary>📸 Click to view example screenshot</summary> <img src="screenshots/adf-create.png" alt="ADF Create Example" width="400"/> </details>
2. GitHub Integration
Create a GitHub repo (private or public)

Link your ADF to your GitHub (for versioning & collaboration)

Authorize access

![GitHub Connect Example](screenshots/adf-github.png. Launch Data Factory Studio

Open the ADF Studio and explore the homepage layout!

![ADF Home](

4. Create a Storage Account (Source/Sink)
Azure Portal → "Storage Account" → "Create"

Configure name, redundancy, region

Click Review + Create and deploy

![Storage Account Example](screenshots/storage-create 5. Build & Configure Your Pipeline

Create a pipeline named data_copy_pipeline

Add source and sink datasets:

Source: Input file (test_data.txt)

Sink: Output file (test_data_out.log)

Configure datasets to use Azure Blob Storage

![Pipeline Overview](

6. Link Services for Source & Sink
Set up linked services that connect your datasets to the storage account (set the container, path)

![Linked Service Example](screenshots/linked-service 7. Trigger & Monitor Pipeline

Trigger the pipeline using Trigger now

Monitor run status under Monitor → "Pipeline Runs"

Review activity runs and logs for details

![Monitor Runs](

8. Verify Output
Check the output blob in the sink container (test_data_out.log)

Use Storage Explorer or Azure Portal (Blob storage) to confirm the results

![Sink File Example](

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
