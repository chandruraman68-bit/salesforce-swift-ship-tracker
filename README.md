# Swift Ship Tracker - Salesforce Agentforce Project

## Overview
**Swift Ship Tracker** is an advanced AI-driven parcel tracking and management system built on the Salesforce platform. It leverages **Salesforce Agentforce** and **Einstein Copilot** to automate parcel status tracking, providing users with a seamless, conversational interface to retrieve real-time delivery information.

---

## Project Details
* **College Name:** N.S.N College of Engineering and Technology
* **College Code:** 9209

### Team Members
* **Chandru R** (Team Lead)
* **Buvanesh K**
* **Ashwinkumar D**
* **Dhanush M**

---

## Key Features
* **Custom Objects & Architecture:** Utilizes robust Salesforce custom objects (`Parcel__c`, `Delivery__c`, `Sender__c`, `Receiver__c`) to securely manage logistical data.
* **Agentforce Integration:** A custom AI Agent (`Swift Ship Tracker Agent`) built using Agent Builder to understand natural language queries.
* **Autolaunched Flows:** Integrates a crash-proof, System-Mode Flow (`Parcel_Details`) that dynamically retrieves and formats tracking information without exposing sensitive data.
* **Field-Level Security (FLS):** Enforces strict visibility controls while allowing the AI Agent to securely access necessary system records.

---

## Technical Stack
* **Platform:** Salesforce Developer Edition
* **AI Tooling:** Salesforce Agentforce, Einstein Copilot, GenAI Prompt Templates
* **Automation:** Lightning Flows (Autolaunched)
* **Deployment:** Salesforce CLI (SFDX) / Metadata API

## Deployment Instructions
To deploy this project to your own Salesforce Org:
1. Clone this repository.
2. Authenticate your Salesforce Org using the CLI:
   ```bash
   sf org login web
   ```
3. Deploy the source code:
   ```bash
   sf project deploy start
   ```
