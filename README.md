# Security-Audit-for-Botium

## Objective

This lab was facilitated by the Google Cybersecurity Professional Certificate in Coursera. The student was given a scenario where they must conduct a security audit on a fictional company. The main task involved reviewing the IT Manager's scope, goals and risk assessment report, then create a controls and compliance checklist as part of the internal audit.

### Skills Learned

### Tools Used

## Assessment

### Controls Assessment Checklist

| Yes | No | Control | Explanation |
| --- | --- | --- | --- |
| | X | Least Privilege | All employees have access to internally stored data, customer PII/SPII and credit card information. Access needs to be limited based on roles to reduce risk of data breach. |
| | X | Disaster Recovery Plan | No disaster recovery plan in place. The company has no plan of recvoery in case of breach. Highly urgent as it ensures that company can return to normal operations in case of security incident. |
| | X | Password Policies | Password policies are enforced but the requirements are nominal and current minimum password complexity doesn't comply with NIST standards. Password policies need to be updated to strengthen password security. |
| | X | Separation of Duties | Access controls regarding separation of duties are not implemented. Policies need to be enforced to minimise risk or data breach as well as provide some form of accounting. |
| X | | Firewall | Firewall is active and blocks traffic based on appropriately defined rules. |
| | X | Intrusion Detection System | IDS not installed. IT department needs a way to detect and/or prevent malicious activity or traffic. |
| | X | Backups | No backups implemented. Data loss would severely cripple the company due to lack of backups. Regular backups will be required as part of disaster recovery plan. |
| X | | Antivirus Software | Antivirus is active and regularly monitored by the IT department. |
| | X | Manual Monitoring, Maintenance and Intervention for Legacy Systems | Legacy systems are monitored and maintained but at irregular intervals. Furthermore current playbooks are unclear regarding intervention methods. Legacy systems need to be regularly and frequently monitored due to unpatched vulnerabilities. Playbook also needs to be updated to be more concise for an effective response. |
| | X | Encryption | Not implemented. Customer credit card information transmitted within internal network in clear text. Encryption needed to provide confidentiality to customer credit card information, PII and SPII. |
| | X | Password Management System | No centralized password management to enforce password policies. If implemented then employee productivity will increase due to reduced tickets from password issues. |
| X | | Physical Locks | Physical locks are in place in offices, store front and warehouse. |
| X | | CCTV Surveillance | Surveillance cameras are up to date and regularly monitored. |
| X | | Fire Detection/Prevention | Fire detection and prevention systems in place and functional. |

### Compliance Checklist

<strong>Payment Card Industry Data Security Standard (PCI DSS)</strong>

| Yes | No | Best Practices | Explanation |
| --- | --- | --- | --- |
| | X | Only authorized users have access to customers' credit card information. | All employees have full access to company's internal data. |
| | X | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | Credit card information is not encrypted and can be accessed by all employees. |
| | X | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | No encryption is in place to provide confidentiality to customer credit card information. |
| | X | Adopt secure password management policies. | No centralized password management to enforce policies. Current password policies are nominal and do not meet NIST standards. |

<strong>General Data Protection Regulation (GDPR)</strong>

| Yes | No | Best Practices | Explanation |
| --- | --- | --- | --- |
| | X | E.U. customers’ data is kept private/secured. | No encryption in place to provide confidentiality to customer credit card information. |
| X | | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | Plan in place includes notifying E.U. customers within 72 hours in case of data breach. |
| | X | Ensure data is properly classified and inventoried. | Assets have been inventoried but not classified. |
| X | | Enforce privacy policies, procedures, and processes to properly document and maintain data. | Privacy policies, procedures and processes have been enforced among company employees, as needed. |

<strong>System and Organization Controls (SOC Type 1 and Type 2)</strong>

| Yes | No | Best Practices | Explanation |
| --- | --- | --- | --- |
| | X | User access policies are established. | Access controls for least privileged and separation of duties are not implemented. All employees have access to company's internal data. |
| | X | Sensitive data (PII/SPII) is confidential/private. | No encryption applied to customer financial data. |
| X | | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity in place. |
| | X | Data is available to individuals authorized to access it. | Data is available to authorized individuals but it's not restricted to them. |

<strong>Recommendations</strong>

Botium is currently lacking crucial controls that weakens its security posture. This will increase the risk of a succesful data breach on the company and result in the exposure of sensitive customer data to threat actors and losing the company valuable time and money. The company will need to address the critical issues:
- Implement access controls such as least privilege and separation of duties to minmise the risk of unqualified personnel handling the data and increase the risk of a data breach.
- Apply encryption to PII, SPII and customer financial information to provide confidentiality.
- Install a centralized password management system to streamline password policy enfrocement and ensure that these policies align with current standards.
- Regularly maintain and monitor legacy systems and develop a more concise plan of intervention in case of a breach.

Additionally, Botium also needs to properly classify its assets to identify additional controls that may needs to be implemented to improve their security posture and better protect sensitive informaton.
