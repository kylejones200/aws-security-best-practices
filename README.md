# AWS security best practices

Published: 2023-03-19
Medium: [https://medium.com/@kyle-t-jones/aws-security-best-practices-c6a0ff8845f7](https://medium.com/@kyle-t-jones/aws-security-best-practices-c6a0ff8845f7)

## Business context

Identity and Access Management (IAM) is a crucial aspect of cloud security. It refers to the policies, technologies, and tools used to manage digital identities and access to resources in the cloud. IAM allows you to control access to your AWS resources by providing granular permissions to users and groups.

Implementing IAM best practices is essential to ensure the security of your AWS environment. Here are some key IAM best practices to follow:

1. [Enforcing Least Privilege Access: IAM policies should grant the least privilege access required to perform specific actions. By granting users only the permissions they need, you can reduce the risk of accidental or intentional misuses of resources.] 2. [Setting up Multi-Factor Authentication (MFA) for users and roles: MFA adds an extra layer of security to the authentication process, making it harder for attackers to gain unauthorized access. You should require MFA for all users and roles that have access to sensitive resources.] 3. [Using IAM Roles instead of IAM Users for applications and services: IAM roles provide temporary security credentials for applications and services to access AWS resources. Unlike IAM users, roles do not have permanent security credentials and cannot make direct requests to AWS services. Using roles instead of users for applications and services reduces the risk of security breaches.] 4. [Periodic Review of IAM policies and users' access: You should review your IAM policies and user access regularly to ensure that they are up-to-date and aligned with your security policies. This includes removing unnecessary permissions and disabling or removing inactive users.]



## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).