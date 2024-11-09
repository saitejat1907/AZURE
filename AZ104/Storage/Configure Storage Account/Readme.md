# AZ-104 Certification Prep: Azure Storage Accounts Explained

## 📺 Watch the Video
[![AZ-104 Exam Prep: Azure Storage Accounts Explained](https://github.com/saitejat1907/AZURE/blob/main/AZ104/Storage/Configure%20Storage%20Account/a%20business.png)](https://youtu.be/hvdwIqQCJJ0?si=chJ0huPN2P3jiVxN)

## 📄 Description
Welcome to my AZ-104 certification series! In this video, we dive into the **Azure Storage module** with a focus on configuring storage accounts. This is an essential topic for the AZ-104 exam, and understanding these concepts will help you effectively manage storage in Azure.

### What You'll Learn:
- **Types of Data**:
  - **Unstructured Data**: Data without a predefined structure, such as images, videos, and text files. Stored commonly in Azure Blob Storage.
  - **Structured Data**: Data organized in a defined schema, like tables in SQL databases. Can be stored in Azure Table Storage for NoSQL needs.
  - **Virtual Machine Data**: Includes VM disks and backups, often stored as Page Blobs in Azure Blob Storage for optimized disk performance.

- **Azure Storage Services**:
  - **Blobs**: Used for storing large unstructured data. Includes Block Blobs (for large files), Append Blobs (for logs), and Page Blobs (for VM disks).
  - **Files**: Azure Files provides cloud-based file shares accessible via SMB/NFS protocols, suitable for sharing data between applications and services.
  - **Tables**: A NoSQL key-value store for structured data, useful for large datasets without a fixed schema.
  - **Queues**: Used for storing and processing messages asynchronously, aiding in decoupling components in a distributed application.

- **URL Generation**:
  - Every Azure Storage service generates a unique URL for accessing its data.
  - **Format**: `https://<storage-account-name>.<service>.core.windows.net/<container-name>/<file-name>`
  - **Example**: `https://mystorageaccount.blob.core.windows.net/mycontainer/myfile.txt`

- **Storage Account Types**:
  - **General-Purpose v2 (GPv2)**: Supports all Azure storage services with options for Hot, Cool, and Archive tiers.
  - **Premium**: Offers high-performance storage, mainly for low-latency needs like VM disks or real-time data processing.

- **Replication Strategies**:
  - **Locally Redundant Storage (LRS)**: Replicates data three times within a single region, offering basic redundancy.
  - **Zone-Redundant Storage (ZRS)**: Distributes data across multiple availability zones in a region for enhanced availability.
  - **Geo-Redundant Storage (GRS)**: Replicates data to a secondary region for disaster recovery, combining LRS and cross-region replication.
  - **Geo-Zone-Redundant Storage (GZRS)**: Combines ZRS and GRS, providing the highest level of durability by replicating data across zones and to a secondary region.

- **Securing Storage Endpoint Access**:
  - **Allow All Networks**: Default setting, but exposes data publicly. Not recommended for sensitive storage.
  - **Allow Only Specified Virtual Networks**: Restricts access to specified Azure virtual networks for enhanced security.
  - **Disable Public Access**: Completely blocks public access, securing the storage account for private use only.

- **Knowledge Check Questions**:
  - Example questions to test your understanding, like "Which replication strategy offers the highest level of durability?" or "What type of blob storage is ideal for frequently appended log files?"

## 📝 Timestamps
- **00:00** - Introduction
- **02:00** - Configuration of Storage Account
- **03:50** - Implement Storage Account
- **09:32** - Azure Storage Services
- **13:06** - Storage Account Types
- **14:45** - Replication Strategies
- **18:54** - URL Format Explained
- **20:26** - Securing Storage Access
- **21:29** - Knowledge Check Questions

## 📌 Key Topics Covered
- Azure Storage Account Configuration
- Understanding Replication Strategies
- Storage Account Security Settings
- Knowledge Check and Practice Questions

## 📚 Additional Resources
- [Microsoft Learn: Introduction to Azure Storage](https://learn.microsoft.com/en-us/training/modules/configure-storage-accounts/)
- [AZ-104 Exam Skills Outline](https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/?practice-assessment-type=certification)

<!-- ## 🤝 Connect with Me
- [GitHub](https://github.com/your-github-username)
- [LinkedIn](https://www.linkedin.com/in/your-linkedin-username)
- [YouTube Channel](https://www.youtube.com/channel/your-channel-id) -->

## 👍 Don't Forget to Like & Subscribe
If you found this video helpful, please give it a thumbs up, subscribe to my channel, and hit the notification bell so you never miss an update on my AZ-104 preparation series!

## 📢 Feedback
Have questions or suggestions? Feel free to leave a comment on the video or reach out to me via my social media channels. Let's ace this certification together!

---

**#Azure #AZ104 #AzureStorage #CloudComputing #MicrosoftCertification #DevOps #CloudEngineer #AzureTraining #LearnAzure #StorageAccount**

