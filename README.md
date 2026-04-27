# -FUTURE_CS_02
# 🎣 Phishing Email Detection & Awareness System

## 📋 Project Overview
This project serves as a practical demonstration of threat intelligence and security awareness. It involves the technical analysis of a real-world phishing email sample to identify indicators of compromise (IoCs) and the translation of those findings into a corporate-ready Security Awareness Report.

## 🎯 Objective
* Analyze real phishing email samples using header inspection tools.
* Identify common phishing indicators (Spoofed domains, malicious payloads, brand inconsistency).
* Classify the email risk level clearly for stakeholders.
* Create an actionable awareness document with specific "Do's and Don'ts" to help employees avoid similar attacks.

## 🛠️ Tools Used
* **Google Workspace Admin Toolbox (Messageheader):** Used for deep technical analysis of the raw `.eml` file to verify SPF, DKIM, and DMARC authentication failures.
* **MS Word / PDF:** Utilized to design a clean, client-ready Executive Summary, Visual Threat Anatomy, and Employee Guidelines document.
* **Public Threat Intelligence Repositories:** Sourced realistic, defanged phishing samples for analysis.

## 🕵️ Analysis Approach
1.  **Technical Verification:** Extracted the raw email header and analyzed routing data to expose the true sender (`attacker.example.com`) hiding behind a spoofed display name. 
2.  **Visual Breakdown:** Created a "Visual Anatomy of a Phish" graphic to highlight social engineering tactics, including false urgency and Frankenstein templating (mixing SharePoint, MetroFax, and NHSmail branding).
3.  **Risk Mitigation:** Developed a strict set of security guidelines tailored to the specific threats identified in the sample, converting technical findings into plain-language business rules.

## 📂 Project Files
* [Phishing Detection and Awareness Report.pdf](./Phishing_Detection_and_Awareness_Report.pdf) - The complete analytical report and employee guide.
