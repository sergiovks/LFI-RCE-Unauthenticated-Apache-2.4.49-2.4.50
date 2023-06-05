# LFI-RCE-Unauthenticated-Apache-2.4.49-2.4.50
<h3>LFI / RCE Unauthenticated - Apache 2.4.49 &amp; 2.4.50</h3>

<h3>Explanation:</h3>
Apache HTTP Server is an open source web server from the Apache Foundation in the United States. The server is fast, reliable, and extensible via a simple API. It was discovered that the fix for CVE-2021-41773 in Apache HTTP Server 2.4.50 is insufficient. An attacker could use a path traversal attack to map URLs to files outside of directories configured by alias-like directives. These requests may succeed if the files outside of these directories are not protected by the usual default configuration of "request all rejects". If CGI scripts are also enabled for these alias paths, this may allow remote code execution. This issue only affects Apache 2.4.49 and Apache 2.4.50, and not earlier versions.

<h3>usage:</h3>

'''
1. Put the IP address you want to check into the ip.txt file
2. Run python3 check.py
''' 
