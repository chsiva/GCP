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
