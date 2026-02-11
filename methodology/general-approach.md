# General Pentesting Methodology

## 1. Information Gathering
- Identify live hosts
- Port scanning (full TCP scan)
- Service detection
- OS fingerprinting

## 2. Enumeration
- Enumerate every open service
- Look for version-specific exploits
- Check for anonymous access
- Brute force carefully if applicable

## 3. Exploitation
- Manual exploit development preferred
- Modify public exploits
- Avoid heavy metasploit reliance

## 4. Post-Exploitation
- Upgrade shell
- Enumerate internal services
- Credential harvesting

## 5. Privilege Escalation
- Automated checks (linpeas/winpeas)
- Manual verification
- Kernel exploits (if applicable)
- Misconfigurations
