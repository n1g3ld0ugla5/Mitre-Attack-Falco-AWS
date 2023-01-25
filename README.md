# Mitre-Attack-Falco-AWS
Aligning curated Falco rules with MITRE ATT&amp;CK Matrix for AWS Cloud

| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access |  Discovery | Lateral Movement | Collection | Exfiltration |  Impact |
| --- | --- | --- | --- |
| `DS0015` | Application Log | [Application Log Content](https://github.com/n1g3ld0ugla5/Mitre-Attack-Linux-Enterprise/blob/44d286a613cfc557848871f68d090a41cc91c417/rules/falco_rules.yaml#L4) | Firewalls and proxies can inspect URLs for potentially known-bad domains or parameters. They can also do *reputation-based analytics* on websites and their requested resources such as how old a domain is, who it's registered to, if it's on a known bad list, or how many other users have connected to it before. |
