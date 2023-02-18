# Week 0 — Billing and Architecture


## Required Homework

- ### Recreate Conceptual Diagram in Lucidchart

**insert image**
**insert link**

- ### Recreate Logical Architectual Diagram in Lucidchart

**insert image**
**insert link**
  
- ### Create Admin User with MFA turned on

**insert image**
  

- ### AWS CLI installation

**Reference gp yaml file**

  
- ### Create Billing Alarm
programmatically and via console
***Insert screenshot***

- ### Create a Budget
programmatically and via console
***Insert screenshot***

  

  
## Homework Challenges

 - Set up custom password policy: This is to minimize the use of root user account to reset IAM User passwords. Also, I enabled 'Allow users to change their own password', and only after password expiration within 30 days that I will have to use the root user account if IAM user forgets to rotate their password.

- Review the AWS Well-Architected Tool 

- Explore Access Advisor:  This will allow me to keep tabs on IAM Users to fine-tune assigned policies to follow the least-privilege principle should I have other users other than the admin IAM user.

- Research technical and service limits of resources allocated under the [AWS Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)

- [AWS Pricing Calculator](https://calculator.aws/#/addService): Use AWS Pricing Calculator to get an estimate of the cost of resources bearing in mind that the pricing calculator generates estimates using 730 hours/month.
