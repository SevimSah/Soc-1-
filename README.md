# CASE_1001 – Impossible Travel: Cloud Identity

## Project Overview

Brief explanation of the security alert and investigation.

## Scenario

What triggered the SOC alert and why it required investigation.

## Tools Used

* Splunk
* JSON log analysis
* Cloud identity/authentication logs
* OSINT / IP investigation, if applicable

## Investigation Process

Step-by-step explanation of what I did as a Tier 1 SOC Analyst.

### 1. Alert Review

What information I received from the alert.

### 2. Log Ingestion

How I imported and prepared the JSON logs in Splunk.

### 3. Splunk Investigation

The SPL searches I used and what I was looking for.

### 4. Evidence Identified

Important usernames, IP addresses, locations, timestamps, authentication results, devices, or other indicators found in the logs.

### 5. Impossible Travel Analysis

Comparison of the login locations and times to determine whether legitimate travel between the locations was realistically possible.

### 6. False Positive vs. True Positive Analysis

Evidence supporting my determination.

## Findings

Summary of what the investigation revealed.

## Incident Classification

**Classification:** True Positive / False Positive / Benign Positive

**Severity:** Low / Medium / High

## Recommended Actions

Actions I would take or recommend as a Tier 1 SOC Analyst, such as:

* Escalate suspicious activity
* Disable or temporarily restrict the affected account
* Revoke active sessions
* Reset credentials
* Verify activity with the user
* Review MFA activity
* Block malicious IP addresses when appropriate
* Continue monitoring for additional authentication attempts

## MITRE ATT&CK Mapping

Relevant MITRE ATT&CK techniques based on the evidence.

## Skills Demonstrated

* SIEM investigation
* Splunk SPL
* Cloud identity monitoring
* Authentication log analysis
* Alert triage
* IOC analysis
* Incident classification
* Incident documentation
* Escalation decision-making

## Evidence

Screenshots and selected sanitized log evidence from the investigation.

## Conclusion

A concise explanation of my final determination and why I reached that conclusion.
