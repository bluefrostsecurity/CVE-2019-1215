# CVE-20190-1215 ws2ifsl.sys UAF exploit for Windows 10 19H1 x64
This exploit uses the recently patched use after free vulnerability CVE-2019-1215 in ws2ifsl.sys to achieve local privilege escalation. The exploit targets Windows 10 19H1 (1901) x64 and demonstrates how to bypass kASLR, kCFG and SMEP. When executing the exploit with medium integrity privileges, successful exploitation spawns a new cmd.exe with system privileges.

The full bug analysis and exploitation details can be found at (https://labs.bluefrostsecurity.de/blog/2020/01/07/cve-2019-1215-analysis-of-a-use-after-free-in-ws2ifsl/) 
