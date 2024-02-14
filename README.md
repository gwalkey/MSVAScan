# MS Vulnerability Scanner
Scans SQL Server Databases for Security Vulnerabilities

Uses the same Vulnerability database found in SSMS 17.4+, and Azure Defender for SQL (so why pay for that?)<br>
but runs for ALL Databases on a server, not just one at a time like SSMS does

Note:<br>
MS purposefully removed this from SSMS 19.1 so they could charge for the same thing as Defender<br>
https://learn.microsoft.com/en-us/sql/relational-databases/security/sql-vulnerability-assessment?view=sql-server-ver16#removal-of-the-sql-vulnerability-assessment-in-sql-server-management-studio-191<br>

Defender doesnt actively scan for anything, making it useless


Input:<br>
Run-MSVAScan.ps1 -instance SQLSERVERINSTANCE [-User SQLAuthUser] [-Password SQLAuthPassword]<br>

Output:<br>
*HTML file with a scan summary sorted by Severity<Br>
*HTML file with a scan summary sorted by Database<br>
*Text file with TSQL Remediation Code for each scanned Database<br>


![alt text](https://raw.githubusercontent.com/gwalkey/MSVAScan/master/MSVAScan.gif)
