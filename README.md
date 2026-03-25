
# SOC Log Analysis Lab – Brute Force Detection

## Project Overview
This project focuses on detecting brute force login attempts using Linux authentication logs. The goal is to simulate a real-world SOC analyst task: identifying suspicious activity, investigating logs, and producing an incident report.

## Objectives
- Analyze authentication logs
- Identify failed login patterns
- Detect brute force attacks
- Map activity to MITRE ATT&CK
- Document findings in an incident report

## Tools Used
- Linux
- Python
- Log analysis
- MITRE ATT&CK framework

## Project Files
- sample_auth.log - Sample authentication log file
- log_analysis.py - Python script used to analyze failed login attempts
- incident_report.md - Incident report documenting findings

## MITRE ATT&CK Mapping
- Technique: T1110 - Brute Force
- Tactic: Credential Access

## Outcome
The analysis identified suspicious IP activity consistent with brute force login attempts. Mitigation steps were documented to reduce future risk.
