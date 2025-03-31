# CLOUD-SECURITY-IMPLEMENTATION

COMPANY NAME: CODETECH IT SOLUTIONS

NAME: VIGNESH T

INTERN ID: CT04WX109

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This task is based on the implemennting IAM polices, secure storage and data encryption on any cloud platform, I have used aws cloud platform to perform this features. basically IAM (Identity and Access Management)it means this function in aws is used to create a iam user who can login as second user in the aws console and access many services. an iam user cant access services directly so we use polices, i have created a policy or permission for the iam user to access s3 services were the iam user can access the console and the s3 services in the console only we can manage polices by allowing different services to the iam user.

Secure Storage and Data Encryption are the services that are avilable in the aws console.Secure storage and data encryption is similar services were it allows to encrypt the data present in the s3 bucket by using our own keys  here i have used kms(key management system) to encrypt the data in the s3 bucket, firstly i have created a customized key named task-4-s3-kms-key to store the data of the bucket in this key, thn i have created a s3 bucket and enabled default encryption as kms to store the data of the bucket in my own key,then created a s3 bucket .now we should upload any files in the s3 bucket and check the encryption key (KMS),now the data contains in the s3 bucket is encrypted.

OUTPUT:IAM POLICES

![Image](https://github.com/user-attachments/assets/4fb6d758-6303-46e6-8826-b62c6350bd44)

OUTPUT:SECURE STORAGE AND DATA ENCRYPTION

![Image](https://github.com/user-attachments/assets/53d6a963-a797-48b6-9230-8fac5f6c7f7d)
