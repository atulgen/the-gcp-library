# The GCP Library

- Google Cloud Platform (GCP) is a

  - suite of cloud computing services offered by Google
  - provides a series of modular cloud services
    - computing,
    - data storage,
    - data analytics
    - machine learning
    - management tools.

- [Wikipedia page](https://en.wikipedia.org/wiki/Google_Cloud_Platform)

- Office Site: https://cloud.google.com/

- After Amazon launched its cloud computing service in 2006, Google put its data center expertise to work by launching a cloud service of its own in April of 2008.

- As of now, 31 July 2025, Google Offers $300 of credit for free signup.


- Certification
  - Cloud Digital Leader
  - Associate Cloud Engineer
  - Professional (Domain Specific)
    - Cloud Architect
    - Cloud Developer
    - Data Engineer
    - Cloud Network Engineer



### Individual 

-  [Associate Cloud Engineer](https://cloud.google.com/learn/certification/cloud-engineer)

- An Associate Cloud Engineer 
  - deploys and secures 
    - applications, 
    - services, 
    - infrastructure, 
    - monitors operations of multiple projects
    - maintains enterprise solutions to ensure that they meet target performance metrics. 
- This individual has experience working with public clouds or on-premises solutions. 
- They are able to perform common platform-based tasks to maintain and scale one or more deployed solutions that leverage Google-managed or self-managed services on Google Cloud.

- The Associate Cloud Engineer exam assesses your ability to:
  - Set up a cloud solution environment
  - Plan and implement a cloud solution
  - Ensure successful operation of a cloud solution
  - Configure access and security

- GCP - ACE



### Resource hierarchy in Google Cloud

- Organization Node
  - Folder
    - Project
      - Resources
        - Compute
        - Storage
        - Database

### GCP Project

- Project
  - ID
  - Name
  - Number

## Accessing the GCP:

- Cloud Console
- Cloud SDK and Cloud Shell
- APIs
- Cloud console mobile app

You can access GCP via 4 ways:

- Web interface: GUI. Allows you to check health, manage, set budgets. Can also connect to instances via SSH
- Cloud SDK & Cloud shell: SDK has gcloud main CLI tool, gsutil CLI for storage, bq CLI for big query. SDK is installed on your workstation. Cloud Shell is a CLI running on the cloud and accessed via browser. Is Debian based with 5 GB persistent storage and loaded with SDK.
- GCP API: Web and client libraries in different languages - Java, Python, C#, node, Ruby, C++ etc.
- Cloud console mobile app: certain management, start-stop operations, view budgets, view server status etc, incident management.



## Networking on GCP

Each project in GCP has a default VPC (virtual private cloud) configured. The resources within a project can talk to each other via this internal IP Address. By default, the firewall is configured to block all incoming traffic, but allow all out-going traffic from within a project.


## Storage and Database:

- Cloud SQL provides fully managed RDBMS including mysql, postgresql, sql server. You can scale up to 64 cores, 400 GB of RAM and 30 TB of storage.

- Cloud spanner is also a fully managed RDBMS, but for high throughput SQL operations including joins, reads, writes. It sounds like you would start with Cloud SQL and upgrade to spanner if your needs warrant that.

- Firestore - scalable, NoSQL DB where data is stored in documents and stored in collections. Firestore is suitable for web or mobile apps (in addition to other users), allows for offline replication & sync. Cost is fine grained, per read, write, query ops and the amount of data stored.

- Cloud Bigtable - NoSQL, big data DB. Bigtable is suitable when data is high throughput, exceeds 1TB, either structured or unstructured, supports time-series. Frequently customers that run ML jobs on data use bigtable.


### Getting Started: 




- https://cloud.google.com/docs/get-started

- [Cloud Engineer Learning Path](https://www.cloudskillsboost.google/paths/11)

- Creating your Google account might require an android phone.





---

### Resources:

- https://atmamani.github.io/projects/cloud/gcp-1/
  - Good blog
- https://inventive.io/insights/introduction-to-google-cloud-platform

- https://github.com/sathishvj/awesome-gcp-certifications

- Google Cloud Certification Path-Hindi/Urdu | Lec-01 | Google Cloud Platform tutorial for beginners
  - https://youtu.be/F8gAq_wT6F0?list=PLBGx66SQNZ8YWRUw6yicKtD4AIpUl_YiJ
  - A good GCP lectures in hindi

- [Google Cloud Associate Cloud Engineer Course \[2025\] - Pass the Exam!](https://youtu.be/OlAmyf8_4O4)

