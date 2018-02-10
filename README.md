# MSVATool
Scans SQL Server Databases for Security Vulnerabilities

Uses the same Vulnerability database found in SSMS 17.4

Input:
Run-MSVAScan.ps1 -instance SQLSERVERINSTANCE -User SQLAuthUser -Password SQLAuthPassword

Output:
HTML file with a scan summary sorted by Severity
HTML file with a Scan summary sorted by Database
Text file with TSQL Remediation Code for each scanned Database
