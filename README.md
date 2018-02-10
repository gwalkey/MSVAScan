# MSVAScan
Scans SQL Server Databases for Security Vulnerabilities

Uses the same Vulnerability database found in SSMS 17.4

Input:<br>
Run-MSVAScan.ps1 -instance SQLSERVERINSTANCE -User SQLAuthUser -Password SQLAuthPassword<br>

Output:<br>
HTML file with a scan summary sorted by Severity<Br>
HTML file with a Scan summary sorted by Database<br>
Text file with TSQL Remediation Code for each scanned Database<br>
