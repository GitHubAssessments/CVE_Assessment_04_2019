# CVE_Assessment_04_2019

This is a review of Snagit version 19.1.1.2860. The software relies in the use of the Windows installer XML (WiX) toolset which is vulnerable to elevation of privilege by loading dynamic link libraries (CVE-2016-0014). The same file structure from this known vulnerability was found in the software. In addition, it was identified security risks due to compressed parent referred files associated with the dynamic link libraries (*.dll) files in use by the software.

In the past related vulnerabilities to .dll files were found in the CVE-2010-3130 where an untrusted search path vulnerability in TechSmith Snagit 10 (Build 788) allowed local users, and possibly remote attackers, to execute arbitrary code and conduct DLL hijacking attacks via a Trojan horse dwmapi.dll. 

References:
1) http://wixtoolset.org/
2) https://docs.microsoft.com/en-us/cpp/build/reference/linker-support-for-delay-loaded-dlls?view=vs-2017 
3) https://nvd.nist.gov/vuln/detail/CVE-2016-0014
4) https://www.securityfocus.com/archive/1/537344   
5) https://www.virustotal.com/#/file/7b9f919a3d1974fd8fa35ad189edc8bf287f476bd377e713e616b26864a4b0d3/relations 
6) https://www.virustotal.com/gui/file/45466d81b5ff9f510bf697dad0b9330528053c57b9238057f5187c42a80cb23b/detection
7) https://www.virustotal.com/gui/file/d6cdf4dab1d9087f435f6bc50a69bec79c0cfd785a5a9213827dc5f419ff5b31/detection
8) https://www.virustotal.com/#/file/cfed1841c76c9731035ebb61d5dc5656babf1beff6ed395e1c6b85bb9c74f85a/relations
9) https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-3130
 
