# 🛡️ Cybersecurity Vulnerability Analysis Project

## Redynox Cybersecurity Internship Tasks

### This repository documents the foundational cybersecurity tasks completed during the Redynox Cybersecurity Internship. The project focuses on hands-on application security (AppSec) principles, environment setup, and the identification and mitigation of common web vulnerabilities.

# 🎯 Key Objectives Demonstrated

# Environment Setup: Configuration of a local security testing environment.

# Vulnerability Assessment: Utilizing industry-standard tools for automated and manual testing.

## Vulnerability Analysis: Deep analysis of high-risk web application security flaws.

Security Reporting: Professional documentation of findings and strategic mitigation recommendations.

Foundational Knowledge: Solid understanding of core threat vectors (Malware, Phishing, DoS) and defensive measures.

# 🛠️ Tools & Technologies Used

# Tool/Technology                                 # Purpose
OWASP ZAP                                  Used as a local proxy and automated security scanner for active and passive scanning.

WebGoat                           A purposefully insecure web application used as a safe, controlled target for ethical hacking exercises.

Python                                (Implied) Used for running local testing tools or analysis scripts.

HTTP/HTTPS Proxy               Configuration of network settings to intercept, inspect, and modify traffic between the browser and WebGoat.

# 💻 Task 2 Focus: Web Application Vulnerability Analysis

The core of this project involved setting up a local testing environment to analyze vulnerabilities within WebGoat.

# Methodology Overview:

## Proxy Setup: Configured a local proxy using OWASP ZAP to intercept all traffic directed to the WebGoat application.

## Spidering (Passive Scan): Mapped the application's structure to discover hidden paths and pages.

## Active Scanning: Executed automated high-risk tests against identified targets.

## Reporting: Documented findings, exploitation steps, and defensive controls.

Key Vulnerabilities Identified:

Vulnerability                                              Security Impact                                   Mitigation Principle

SQL Injection (SQLi)             High: Unauthorized access to underlying database information.                            Use of Parameterized                                                                                                                  Queries (Prepared Statements).

Cross-Site Request Forgery (CSRF)      High: Forcing authenticated users to execute unwanted actions.        Implementation of Synchronizer                                                                                                                         Tokens (CSRF Tokens).

Missing Security Headers                   Medium: Exposes users to potential attack vectors like XSS       Implementing HTTP Strict Transport                                                                                                           Security (HSTS) and X-Content-Type-                                                                                                                        Options.

# 📁 Repository Structure

/reports: Contains the final submission documents, including Task 1 Report (Orientation and Setup) and Task 2 Report (Vulnerability Findings).

/screenshots: Contains all documentation images of the ZAP proxy setup, successful scans, and specific vulnerability alerts (e.g., SQLi Injection detected.png, CSRF vulnerability detected.png).

/linkedin_tasks: Documentation of professional engagement (Task 3).

# 🚀 Getting Started

## To replicate the environment for ethical practice:

Install OWASP ZAP and Java (JDK).

Download and run the WebGoat executable jar file.

Configure your browser to use ZAP as a local HTTP/HTTPS proxy (typically on localhost:8080 or localhost:8081).

Begin exploring and scanning the WebGoat application.

Completed as part of the Redynox Cybersecurity Internship Program.
