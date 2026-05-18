### LAB 1 DISCUSSION QUESTIONS:

- 1. Why should the root account not be used daily?
     - The root account is where the user account credentials are found, and where Multifactor Authentication is enabled for console sign-in.
     - It follows "The rule is NON_COMPLIANT if the AWS Identity and Access Management (IAM) root account user does not have multi-factor authentication (MFA)             enabled"(Amazon Web Service, 2026).
     
- 2. What risk exists without MFA?
  - Ransomware - where a hacker is able to access your account and hold your data hostage for a ransom.
      
- 3. Why is least privilege important?
  - Since your KMS keys protect sensitive information, it is recommended to follow the principle of least-privileged access.
  - When you give an AWS service permission to use a KMS key, ensure that the permission is valid only for the resources that the service must access on your           behalf. This least privilege strategy helps to prevent unauthorized use of a KMS key when requests are passed between AWS services. 
