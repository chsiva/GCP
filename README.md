#gsutil commands
https://cloud.google.com/storage/docs/gsutil/commands/cp


# GCP
GCP VS AWS

Q. Instance types:
   https://cloud.google.com/compute/docs/machine-types
   
   
Q. Images(like AMI):
   https://cloud.google.com/compute/docs/images#os-compute-support?hl=en_GB
   
   
Q. Steps to Create Instance:
   
     console > vm instances tab on left side > Select Region > Machine config (Instance type (e2 micro/medium) >
     Add Firewall -> Add SSH Key-> Click Launch
     
     Instance: Start/resume, stop, suspend, Delete

   
Q. Connecting to instances:
   https://cloud.google.com/compute/docs/instances/connecting-to-instance
   
Q. Reset VM instance

    Reset performs a hard reset on the instance, 
    which wipes the memory contents of the machine and resets the virtual machine to its initial state. 
    This can lead to file system corruption.
    
Q. VM Import: https://cloud.google.com/migrate/compute-engine/?_ga=2.55412843.-1782596712.1603843653

    You can migrate your VMs directly from on-prem or other clouds using Google Cloud's Migrate for Compute Engine. 
    Supported sources include on-prem VMware, Amazon EC2 and Microsoft Azure.
    
Q. Create Bucket
 
      Go to console > storage > Click craete bucket > NAME > Location (region) > choose storage class (standard)
      > control access ( Fine graned: bucket level ACL or Uniform: IAM level ) > Create
      
# Fine graned: bucket level ACL or Uniform: IAM level
# delete, upload s3 same as aws

# gcloud vs gsutil

1. The gsutil command is used only for Cloud Storage.

2. With the gcloud command, you can interact with other Google Cloud products like the App Engine, Google Kubernetes Engine etc. You can have a look here and here for more info.

The gsutil is a Python application that lets you access Google Cloud Storage from the command line. You can use gsutil to do a wide range of bucket and object management tasks, including:

Creating and deleting buckets. Uploading, downloading, and deleting objects. Listing buckets and objects. Moving, copying, and renaming objects. Editing object and bucket ACLs.

The gcloud command-line interface is the primary CLI tool to create and manage Google Cloud resources. You can use this tool to perform many common platform tasks either from the command line or in scripts and other automations.

For example, you can use the gcloud CLI to create and manage:

Google Compute Engine virtual machine instances and other resources, Google Cloud SQL instances, Google Kubernetes Engine clusters, Google Cloud Dataproc clusters and jobs, Google Cloud DNS managed zones and record sets, Google Cloud Deployment manager deployments.


# BigQuery vs BigTable

BigQuery is a query Engine for datasets that don't change much, or change by appending. It's a great choice when your queries require a "table scan" or the need to look across the entire database. Think sums, averages, counts, groupings. BigQuery is what you use when you have collected a large amount of data, and need to ask questions about it.

BigTable is a database. It is designed to be the foundation for a large, scaleable application. Use BigTable when you are making any kind of app that needs to read and write data, and scale is a potential issue.
