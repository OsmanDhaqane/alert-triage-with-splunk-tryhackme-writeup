# Alert Triage With Splunk – TryHackMe Write-Up

This repository contains my write-up for the **Alert Triage With Splunk** room on TryHackMe.

The room focused on using Splunk to investigate different alert scenarios across Linux, Windows, and web server logs. The main areas covered were brute-force activity, privilege escalation, scheduled task persistence, discovery commands, and web shell activity.

## Room Focus

- Investigating Linux SSH brute-force activity
- Identifying successful login activity after failed attempts
- Calculating brute-force duration using Splunk
- Detecting Linux privilege escalation and persistence
- Investigating Windows scheduled task creation
- Reviewing process and parent process relationships
- Identifying local group enumeration
- Analysing web shell activity in web server logs
- Using Splunk queries to support alert triage decisions

## Tools Used

- Splunk
- Linux secure logs
- Windows Security logs
- Web access logs
- AbuseIPDB
- Google search for web shell context

## Write-Up

The full walkthrough is available here:

[alert-triage-with-splunk-writeup.pdf](./alert-triage-with-splunk-writeup.pdf)

## Key Takeaway

This room was good practice for SOC-style alert triage. It showed how Splunk can be used to move from an initial alert to evidence-based findings, including identifying attacker activity, confirming true positives, and documenting useful investigation steps.
