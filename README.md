#  Controls (Guardrails)
Overview

Controls, also known as guardrails, are high-level rules that provide ongoing governance for your AWS environment. They help ensure that your AWS accounts comply with your organization’s policies and best practices.
Types of Controls

##  Preventive Controls:

These controls prevent actions that could lead to non-compliance. For example, they can restrict certain configurations or actions that don't meet security standards. Preventive controls are automatically enforced and help maintain a compliant environment by preventing non-compliant resources from being created.
##  Detective Controls:

These controls detect non-compliant resources and activities. They continuously monitor your AWS environment and alert you to any deviations from your defined policies. Detective controls help identify issues so they can be addressed promptly.
##  Proactive Controls:

These controls ensure compliance before resources are created. They provide guidance and recommendations to help you configure resources correctly from the start. Proactive controls help maintain a compliant environment by guiding users to follow best practices.
##  Categories of Controls

###  Mandatory Controls:

These are essential controls that must be applied to all accounts within your AWS environment. They enforce critical security and compliance requirements.
## Strongly Recommended Controls:

These controls are highly recommended to enhance the security and compliance of your AWS environment. While not mandatory, they provide significant benefits and should be implemented wherever possible.
## Elective Controls:

These controls are optional and can be applied based on specific needs or use cases. They offer additional governance capabilities but are not required for all accounts.
Examples of Controls

## Preventive Control Example:

Disallow S3 Buckets Without Encryption: This control ensures that all Amazon S3 buckets are encrypted, preventing the creation of unencrypted buckets.
### Detective Control Example:

Detect Unrestricted SSH Access: This control monitors for security groups that allow unrestricted SSH access and alerts you to potential security risks.
### Proactive Control Example:

Enforce MFA for Root Account: This control ensures that multi-factor authentication (MFA) is enabled for the root account, enhancing the security of your AWS environment.
### Benefits of Controls

## Enhanced Security:

Controls help enforce security best practices, reducing the risk of security breaches and vulnerabilities.
## Compliance:

They ensure that your AWS environment complies with regulatory requirements and organizational policies.
## Automated Governance:

Controls provide automated governance, reducing the manual effort required to maintain a compliant environment.
## Continuous Monitoring:

Detective controls offer continuous monitoring, helping you identify and address compliance issues promptly.
By implementing these controls, AWS Control Tower helps you maintain a secure, compliant, and well-governed AWS environment.
