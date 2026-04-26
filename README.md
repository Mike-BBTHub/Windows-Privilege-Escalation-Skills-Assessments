Windows Privilege Escalation Skills Assessment - Part I
During a penetration test against the INLANEFREIGHT organization, you encounter a non
domain joined Windows server host that suffers from an unpatched command injection
vulnerability. After gaining a foothold, you come across credentials that may be useful for
lateral movement later in the assessment and uncover another flaw that can be leveraged to
escalate privileges on the target host.
For this assessment, assume that your client has a relatively mature patch/vulnerability
management program but is understaffed and unaware of many of the best practices around
configuration management, which could leave a host open to privilege escalation.
Enumerate the host (starting with an Nmap port scan to identify accessible ports/services),
leverage the command injection flaw to gain reverse shell access, escalate privileges to 
NT
AUTHORITY\SYSTEM
 level or similar access, and answer the questions below to complete this
portion of the assessment.


.....................

Windows Privilege Escalation Skills Assessment - Part II
As an add-on to their annual penetration test, the INLANEFREIGHT organization has asked you to perform a security review of their standard Windows 10 gold image build currently in use by over 1,200 of their employees worldwide. The new CISO is worried that best practices were not followed when establishing the image baseline, and there may be one or more local privilege escalation vectors present in the build. Above all, the CISO wants to protect the company's internal infrastructure by ensuring that an attacker who can gain access to a workstation (through a phishing attack, for example) would be unable to escalate privileges and use that access move laterally through the network. Due to regulatory requirements, INLANEFREIGHT employees do not have local administrator privileges on their workstations.

You have been granted a standard user account with RDP access to a clone of a standard user Windows 10 workstation with no internet access. The client wants as comprehensive an assessment as possible (they will likely hire your firm to test/attempt to bypass EDR controls in the future); therefore, Defender has been disabled. Due to regulatory controls, they cannot allow internet access to the host, so you will need to transfer any tools over yourself.

Enumerate the host fully and attempt to escalate privileges to administrator/SYSTEM level access.
