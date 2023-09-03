## Part 2: Azure Exploration

**Storage**
1. **Azure Files**: This is a cloud-based file-sharing service. It allows you to use the industry standard Server Message Block (SMB) protocol, Network File System (NFS) protocol, and Azure Files REST API to access fully managed file-sharing spaces in the cloud. Azure files are helpful in replacing or supplementing on-premises file servers and simplifying cloud development projects. This service interacts with Python through Azure SDKs which uses FileREST API that incorporates C#, Java, Python, JavaScript, and Go. FileREST API is also designed specifically for Azure Files, therefore, you can access inaccessible features from SMB and NFS. 
2. **Azure Data Share**: This is a service that allows the data provider to share data and control how their data is handled. Azure Data Share provides snapshot-based sharing and in-place sharing for data providers. For data consumers, it allows for viewing the terms of use for the data and accepting the data shared. All of these capabilities are used through REST APIs and Azure portals. Python can be used to work with REST APIs.

**Compute**
1. **Azure Virtual Desktop**: This is a virtual service that runs on the cloud and gives a scalable and flexible environment. The virtual desktop can reduce the costs of resources used by your users. You can also use Azure portal, Azure CLI, PowerShell, and REST API in the virtual desktops and applications. Azure CLI is built using Python for its core functionality. However, the user does not interact with Python through Azure CLI unless they are developing the plugins or extensions. 
2. **App Service**: This is an HTTP-based service offered for developers to run web apps on Windows and Linux environments with features of multiple languages and frameworks such as Python, Java, Ruby, etc. Python can be used here to develop a web application to run in the environments. 

**Database**
1. **Azure Cache for Redis**: This service helps improve application performance and contains an in-memory data store with the Redis software. This can be deployed by itself or through Azure SQL or Azure Cosmos DB. You can incorporate this service into a Python app. 
2. **Azure Confidential Ledger**: This is a new service that is used to manage sensitive data. Azure Confidential Ledger (ACL) uses the Azure Confidential Computing platform and Confidential Consortium Framework that helps maintain the integrity of the application. This can be used in a Python virtual environment with Azure CLI or Azure PowerShell.
