# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: Vulnerability : CVE-2023-50447 in the SARIF results
1. Which package or library are you addressing?
Package: Pillow (pkg:pypi/pillow@9.4.0)

2. Which CVE is linked to this vulnerability?
CVE-2023-50447

3. What remediation steps do you suggest?
For remidiation, it is recommended to upgrade to Pillow-Version 10.2.0 or higher because the vulnerability is related to improper control, which means an attacker can gain unuintended-unauthorized access to the Pillow image and craft a malicious image file that can execute unintended code.

### Vulnerability 2: Vulnerability : CVE-2019-20477 in the SARIF results
1. Which vulnerability are you addressing?
Package : PyYAML (pkg:pypi/pyyaml@5.1)

2. Which CVE is linked to this vulnerability?
CVE-2019-20477

3. What remediation steps do you suggest? 
For remidiation, it is recommended to upgrade PyYAML to version 5.2 or higher and use yaml.safe_load() instead of yaml.load() when loading a YAML file. The vulnerability involves unsafe deserilization of untrusted YAML files.