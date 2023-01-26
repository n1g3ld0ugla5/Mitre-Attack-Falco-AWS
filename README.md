# Using Falco to address the MITRE ATT&CK Matrix for AWS Cloud
Aligning curated Falco rules with MITRE ATT&amp;CK Matrix for AWS Cloud: <br/>
https://attack.mitre.org/matrices/enterprise/cloud/

| <sub>Initial Access</sub> | <sub>Execution</sub> | <sub>Persistence</sub> | <sub>Privilege Escalation</sub> | <sub>Defense Evasion</sub> | <sub>Credential Access</sub> |  <sub>Discovery</sub> | <sub>Lateral Movement</sub> | <sub>Collection</sub> | <sub>Exfiltration</sub> |  <sub>Impact</sub> |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| <sub> [Drive-by Compromise](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/599e7ea5418ecfc74b8a32b4dd294411bf5e75fb/plugins/rules/aws_cloudtrail_rules.yaml#L1) </sub> | <sub> [Serverless Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/f85e8ca0f7d876107d1d61e59ba9bc1021fce169/plugins/rules/aws_cloudtrail_rules.yaml#L13) </sub> | <sub> [Account Manipulation](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/f85e8ca0f7d876107d1d61e59ba9bc1021fce169/plugins/rules/aws_cloudtrail_rules.yaml#L28) </sub> | <sub>[Domain Policy Modification](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/e708cb47bc0604240f0dfd122b634fd948ab17f6/plugins/rules/aws_cloudtrail_rules.yaml#L38)</sub> | <sub>Domain Policy Modification</sub> | <sub>[Brute Force](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/8c5e48e3dcda7f38dd8e81525a3c5eae3a115308/plugins/rules/aws_cloudtrail_rules.yaml#L52)</sub> | <sub>[Account Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/48c521238858739845d693812395d6355c05eb78/plugins/rules/aws_cloudtrail_rules.yaml#L64)</sub> | <sub>[Internal Spearphishing](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/2bb20f0690bc85ee91c75bdfabf69ec263319ac3/plugins/rules/aws_cloudtrail_rules.yaml#L77)</sub> | <sub>[Automated Collection](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/2bb20f0690bc85ee91c75bdfabf69ec263319ac3/plugins/rules/aws_cloudtrail_rules.yaml#L91)</sub> | <sub>[Transfer Data To Cloud Account](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/8999556878911d203a87118fd7022c4cc063130a/plugins/rules/aws_cloudtrail_rules.yaml#L124)</sub> | <sub>[Account Access Removal](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/008396261305c1bd73c985298fa358d540dab6c8/plugins/rules/aws_cloudtrail_rules.yaml#L103)</sub> |
| <sub> [Exploit Public-Facing Application](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/71c3ce691f1e84a1b59dca7d2ffc9a0d8c256c81/plugins/rules/aws_cloudtrail_rules.yaml#L140) </sub> | <sub> [User Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/348f6c2f55efbe5ae0df741b55c18dfd2cee1a9b/plugins/rules/aws_cloudtrail_rules.yaml#L152) </sub> | <sub> [Create Account](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/9cdb5e6a4cd05b5927c2af1dbbcad2271d737f49/plugins/rules/aws_cloudtrail_rules.yaml#L164) </sub> | <sub>[Event Triggered Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/7bddd524cd5831c2e717498dc5d5def7195a7256/plugins/rules/aws_cloudtrail_rules.yaml#L181)</sub> | <sub>[Hide Artifacts](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/bb8cce4d87f0a7ba7a48a55c3b866fec4ad69b6b/plugins/rules/aws_cloudtrail_rules.yaml#L193)</sub> | <sub>Forge Web Credentials</sub> | <sub>Cloud Infrastructure Discovery</sub> | <sub>Taint Shared Content</sub> | <sub>Data From Cloud Storage</sub> |  | <sub>Data Destruction</sub> |
| <sub> Phishing </sub> |  | <sub> Event Triggered Execution </sub> | <sub>Valid Accounts</sub> | <sub>Impair Defenses</sub> | <sub>Modify Authentication Process</sub> | <sub>Cloud Service Dashboard</sub> | <sub>Use Alternate Authentication Material</sub> | <sub>Data From Information Repositories</sub> |  | <sub>Data Encrypted For Impact</sub> |
| <sub> Trusted Relationship </sub> |  | <sub> Implant Internal Image </sub> |  | <sub>Indicator Removal</sub> | <sub>MFA Auth Request Generation</sub> | <sub>Cloud Service Discovery</sub> | | <sub>Data Staged</sub> |  | <sub>Defacement</sub> |
| <sub> Valid Accounts </sub> |  | <sub> Modify Auth Process </sub> |  | <sub>Modify Auth Process</sub> | <sub>Network Sniffing</sub> | <sub>Cloud Storage Object Discovery</sub> | | <sub>Email Collection</sub> |  | <sub>Endpoint Denial of Service</sub> |
| |  | <sub> Office Application Startup </sub> |  | <sub>Modify Cloud Computer Infra</sub> | <sub>Steal App Access Token</sub> | <sub>Network Service Discovery</sub> | | <sub>Email Collection</sub> |  | <sub>Network Denial of Service</sub> |
| | | <sub> Valid Accounts </sub> | | <sub> Unused / Unsupported Cloud Regions </sub> | <sub>Steal or Forge Auth Certs</sub> | <sub>Network Sniffing</sub> | | | | <sub>Resource Hijacking</sub> |
| | | | | <sub>Use Alternate Auth Material</sub> | <sub>Steal Web Session Cookie</sub> | <sub>Password Policy Discovery</sub> | | | | |
