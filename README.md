# CS 3338 Final Project - Group 11 - Project Mirage

Jira Project URL: https://calstatela-cs3338-fall25-g11.atlassian.net/jira/software/c/projects/CGFP/summary

### **Team:**
- Matthew Moc
- Agustin Liscano
- Charles Lopez
- Miguel Vasquez-Naranjo
- Damian Bonds

### **Overview:**

Project Mirage is a AI powered assistent called Anya, made to streamline IT support, admistrative workflows, file retrieval, translation,
document automation, and internal communucations for thre Santa Barbra Public Defender's Office. It operates inside Microsoft 
Teams and intergrates with PowerApps, Copilot, SharePoint, and Smarthsheet to create a smooth centralized user experience.

### **System Architecture:**

Anya is built from multiple modular components working together through PowerApss and Copilot Studio.
- **User Interface Subsystem** – Adaptive Cards in Teams
- **ChatHandler** – NLP engine directing user intents
- **TicketManager** – PDHelpDesk integration
- **AdminRequestManager** – PDGo integration
- **FileRetriever** – SharePoint + Smartsheet search
- **SessionLogger** – Tracking user actions
- **Data Services Layer** – Secure API communication

### **Features:**

- **IT Support**  
  - Submit new tickets
  - Track ticket status
  - View comments and updates
  - Allow admins to reassign, recategorize, and resolve issues

- **Administrative Workflows**
  - Time-off requests
  - MCLE Logging
  - General admin submissions via PDGo

- **File Retrieval**
  - Keyword-based search across SharePoint and Smartsheet
  - Metadata-aware document lookup
  - Adaptive Card results with links

- **Contact Lookup**
  - Search by name or keyword
  - Returns detailed contact information pulled from Office 365

- **Translation**
  - Supports multiple languages (English, Japanese, Spanish, and Italian)
  - Streamlines document translation directly within Teams
 
- **Fillable Documents**
  - Select, fill, and generate official forms
  - Automatically stores and formats output  

- **Session Logging**
  - Tracks user actions for auditing and troubleshooting

### **Tech Stack:**

- **Microsoft Teams** – User interface
- **PowerApps** – Backend logic and forms
- **Copilot Studio** – NLP & bot behavior
- **Power Automate** – Process flows
- **SharePoint** – Ticketing, sessions, metadata storage
- **Smartsheet** – Admin workflows


