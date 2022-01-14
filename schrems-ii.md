## GDPR & Schrems II Report

EEA and EU, GDPR and Schrems II, relevant audit report:

All regulated data has data-residency locks to prevent transfer to locations that have not confirmed as to abide by GDPR and Schrems II processing standards. All authorizated data is stored in AWS using the appropriate level of controls. Data is encrypted at rest and in transit. While in process, our services use the latest generation of compute instances that automatically gain the protection of the AWS Nitro System. Using purpose-built hardware, firmware, and software, AWS Nitro provides unique and industry-leading security and isolation by offloading the virtualization of storage, security, and networking resources to dedicated hardware and software. This enhances security by minimizing the attack surface and prohibiting administrative access while improving performance. Nitro was designed to operate in the most hostile network we could imagine, building in encryption, secure boot, a hardware-based root of trust, a decreased Trusted Computing Base (TCB) and restrictions on operator access. The newly announced AWS Nitro Enclaves feature enables customers to create isolated compute environments with cryptographic controls to assure the integrity of code that is processing highly sensitive data.

For more information on how our data is protected please see:
* [AWS Nitro Enclaves](https://aws.amazon.com/ec2/nitro/) - For compute time data segregation.
* [AWS KMS](https://aws.amazon.com/kms/) - For encryption at rest documentation.
* [TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security) - For data encryption in transit

### Data transfers
In rare situations data transfers to customers may be necessary to facilitate customer-owned workflows. These transfers are not governed by the above process and restrictions, and therefore the customer takes full responsibility in ensuring the transfer of this data, as well as receiving it, are handled according to their own requirements and regulations.
