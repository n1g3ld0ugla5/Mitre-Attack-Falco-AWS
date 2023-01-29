# Using Falco to address the MITRE ATT&CK Matrix for AWS Cloud
Aligning curated Falco rules with MITRE ATT&amp;CK Matrix for AWS Cloud: <br/>
https://attack.mitre.org/matrices/enterprise/cloud/

| <sub>Initial Access</sub> | <sub>Execution</sub> | <sub>Persistence</sub> | <sub>Privilege Escalation</sub> | <sub>Defense Evasion</sub> | <sub>Credential Access</sub> |  <sub>Discovery</sub> | <sub>Lateral Movement</sub> | <sub>Collection</sub> | <sub>Exfiltration</sub> |  <sub>Impact</sub> |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| <sub> [Drive-by Compromise](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/52271ae3664408db2657b6f0538d3966e06dc1b1/plugins/rules/aws_cloudtrail_rules.yaml#L1) </sub> | <sub> [Serverless Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/f85e8ca0f7d876107d1d61e59ba9bc1021fce169/plugins/rules/aws_cloudtrail_rules.yaml#L13) </sub> | <sub> [Account Manipulation](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/f85e8ca0f7d876107d1d61e59ba9bc1021fce169/plugins/rules/aws_cloudtrail_rules.yaml#L28) </sub> | <sub>[Domain Policy Modification](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/e708cb47bc0604240f0dfd122b634fd948ab17f6/plugins/rules/aws_cloudtrail_rules.yaml#L38)</sub> | <sub>Domain Policy Modification</sub> | <sub>[Brute Force](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/8c5e48e3dcda7f38dd8e81525a3c5eae3a115308/plugins/rules/aws_cloudtrail_rules.yaml#L52)</sub> | <sub>[Account Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/48c521238858739845d693812395d6355c05eb78/plugins/rules/aws_cloudtrail_rules.yaml#L64)</sub> | <sub>[Internal Spear phishing](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/2bb20f0690bc85ee91c75bdfabf69ec263319ac3/plugins/rules/aws_cloudtrail_rules.yaml#L77)</sub> | <sub>[Automated Collection](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/2bb20f0690bc85ee91c75bdfabf69ec263319ac3/plugins/rules/aws_cloudtrail_rules.yaml#L91)</sub> | <sub>[Transfer Data To Cloud Account](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/8999556878911d203a87118fd7022c4cc063130a/plugins/rules/aws_cloudtrail_rules.yaml#L124)</sub> | <sub>[Account Access Removal](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/6d81c7011f9de5a2aa0bec86e2a9c104f8b02850/plugins/rules/aws_cloudtrail_rules.yaml#L145)</sub> |
| <sub> [Exploit Public-Facing Application](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/71c3ce691f1e84a1b59dca7d2ffc9a0d8c256c81/plugins/rules/aws_cloudtrail_rules.yaml#L140) </sub> | <sub> [User Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/348f6c2f55efbe5ae0df741b55c18dfd2cee1a9b/plugins/rules/aws_cloudtrail_rules.yaml#L152) </sub> | <sub> [Create Account](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/9cdb5e6a4cd05b5927c2af1dbbcad2271d737f49/plugins/rules/aws_cloudtrail_rules.yaml#L164) </sub> | <sub>[Event Triggered Execution](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/35edff1ea517f3d221bde078770309e41a59abe1/plugins/rules/aws_cloudtrail_rules.yaml#L268)</sub> | <sub>[Hide Artifacts](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/bb8cce4d87f0a7ba7a48a55c3b866fec4ad69b6b/plugins/rules/aws_cloudtrail_rules.yaml#L193)</sub> | <sub>[Forge Web Credentials](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/29f96af3ee2c6b8c89f40f223e63ed753c579147/plugins/rules/aws_cloudtrail_rules.yaml#L204)</sub> | <sub>[Cloud Infrastructure Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/5ec8fe2ab524a848599cd0aeed6b3406f5068fcd/plugins/rules/aws_cloudtrail_rules.yaml#L218)</sub> | <sub>[Taint Shared Content](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/fe79bae2bf4d4b6d2b8513ab0554e5681c85e1a8/plugins/rules/aws_cloudtrail_rules.yaml#L237)</sub> | <sub>[Data From Cloud Storage](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/6f2bd50f56b716189cc5bc563ab273be775330d6/plugins/rules/aws_cloudtrail_rules.yaml#L250)</sub> |  | <sub>[Data Destruction](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/e45467951be10c9cb20d30aa131c9338c025bd96/plugins/rules/aws_cloudtrail_rules.yaml#L298)</sub> |
| <sub> [Phishing](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/8c82470e9b66f58de05cbf11fe1bb89f3995a999/plugins/rules/aws_cloudtrail_rules.yaml#L262) </sub> |  | <sub> Event Triggered Execution </sub> | <sub>[Valid Accounts](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/315d1efb30c5b65d18a70171d7f1bb376cdbb78d/plugins/rules/aws_cloudtrail_rules.yaml#L274)</sub> | <sub>[Impair Defenses](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/5d883d81ab90d27985ed3d77969fbf67143a98a7/plugins/rules/aws_cloudtrail_rules.yaml#L49)</sub> | <sub>[Modify Auth Process](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/bd49942e2fa5fd454b74b557d4577f2ff60c8622/plugins/rules/aws_cloudtrail_rules.yaml#L406)</sub> | <sub>Cloud Service Dashboard</sub> | <sub>Alternate Auth Material</sub> | <sub>Data From Information Repositories</sub> |  | <sub>Data Encrypted For Impact</sub> |
| <sub> Trusted Relationship </sub> |  | <sub> [Implant Internal Image](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/4d17a81a07869758f84903fdfb1066739f7cbb90/plugins/rules/aws_cloudtrail_rules.yaml#L30) </sub> |  | <sub>Indicator Removal</sub> | <sub>MFA Auth Request Generation</sub> | <sub>[Cloud Service Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/116e08224c5007e059abdd1f8d142f2ebceff3a3/plugins/rules/aws_cloudtrail_rules.yaml#L118)</sub> | | <sub>Data Staged</sub> |  | <sub>Defacement</sub> |
| <sub> Valid Accounts </sub> |  | <sub> [Modify Auth Process](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/bd49942e2fa5fd454b74b557d4577f2ff60c8622/plugins/rules/aws_cloudtrail_rules.yaml#L417) </sub> |  | <sub>[Modify Auth Process](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/bd49942e2fa5fd454b74b557d4577f2ff60c8622/plugins/rules/aws_cloudtrail_rules.yaml#L395)</sub> | <sub>Network Sniffing</sub> | <sub>[Cloud Storage Object Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/32474a3928962762c6dd6d0e75354bffb8e2b254/plugins/rules/aws_cloudtrail_rules.yaml#L56)</sub> | | <sub>Email Collection</sub> |  | <sub>Endpoint Denial of Service</sub> |
| |  | <sub> Office Application Startup </sub> |  | <sub>[Modify Cloud Compute Infra](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/e8f4b2a4e65502a7c7230ad2c76841d9605d3938/plugins/rules/aws_cloudtrail_rules.yaml#L14)</sub> | <sub>[Steal App Access Token](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/c016e111d3efa497006ba150d15cf678be6d2422/plugins/rules/aws_cloudtrail_rules.yaml#L333)</sub> | <sub>Network Service Discovery</sub> | | |  | <sub>Network Denial of Service</sub> |
| | | <sub> Valid Accounts </sub> | | <sub> [Unused / Unsupported Cloud Regions](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/c41aeefab73717f360775ea9f24b8038330eb006/plugins/rules/aws_cloudtrail_rules.yaml#L314) </sub> | <sub>[Steal or Forge Auth Certs](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/03b0f6a7b488487a231bcd92cfe7985256213c10/plugins/rules/aws_cloudtrail_rules.yaml#L14)</sub> | <sub>Network Sniffing</sub> | | | | <sub>Resource Hijacking</sub> |
| | | | | <sub>Use Alternate Auth Material</sub> | <sub>Steal Web Session Cookie</sub> | <sub>[Password Policy Discovery](https://github.com/n1g3ld0ugla5/Mitre-Attack-Falco-AWS/blob/c281c5004e097228216d699c5b422fa9306c8707/plugins/rules/aws_cloudtrail_rules.yaml#L402)</sub> | | | | |
