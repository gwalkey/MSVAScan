# MSVAScan
Scans SQL Server Databases for Security Vulnerabilities

Uses the same Vulnerability database found in SSMS 17.4+, 
but runs for ALL Databsaes on a server, not just one at a time like SSMS

Input:<br>
Run-MSVAScan.ps1 -instance SQLSERVERINSTANCE [-User SQLAuthUser] [-Password SQLAuthPassword]<br>

Output:<br>
*HTML file with a scan summary sorted by Severity<Br>
*HTML file with a scan summary sorted by Database<br>
*Text file with TSQL Remediation Code for each scanned Database<br>


![alt text](https://raw.githubusercontent.com/gwalkey/MSVAScan/master/MSVAScan.jpg)
