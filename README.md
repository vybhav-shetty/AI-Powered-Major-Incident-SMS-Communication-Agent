# SMS Communication Agent
An AI-powered agent that generates concise SMS communications for Major Incidents while strictly adhering to a 160-character SMS limit and GSM-7 encoding requirements. The agent analyses incident communications, extracts relevant information, determines the communication type, and produces stakeholder-ready SMS updates suitable for enterprise incident management.

## Project Highlights
- Reduced SMS volume by ~72% after implementation
- Built using Claude Sonnet 4.6
- Generates GSM-7 compliant SMS communications
- Enforces strict 160-character limit
- Automates Major Incident SMS creation
- Improved communication consistency and reduced manual effort
  
## Model 
Claude Sonnet 4.6

## Key Features
- Automatically identifies communication types:
    New
    Update
    Resolved
    Retrospective
    New/Resolved
- Extracts critical incident information, including:
    Incident Number
    Priority (P1/P2)
    Impacted IT Service
    Latest Update or Resolution
- Generates SMS messages using predefined templates based on communication status.
- Ignores unnecessary content such as historical updates, preliminary root causes, and non-essential information.
- Strictly enforces a 160-character limit for all SMS content.
- Optimises wording through intelligent compression and abbreviation when required.
- Ensures GSM-7 compatibility by preventing UCS-2 encoding and excluding unsupported characters, emojis, and special symbols.
- Automatically appends: 'Refer to the email communication for detailed information' at the end of every communication.
- Suppresses internal validation and analysis outputs to provide a clean stakeholder-facing message.
  
## Business Value
This agent enables rapid, consistent, and mobile-friendly incident communications while ensuring compliance with SMS platform limitations. It reduces manual effort, improves communication quality, and supports operational teams during high-severity incidents.

## Measurable Outcomes
Following implementation of the SMS Communication Agent, a comparison was performed using historical SMS usage data and actual post-implementation SMS volumes.

## Calculation Methodology

### Baseline Period
- September 2025 was used as the reference period as complete SMS statistics were readily available.
- During September 2025, 8 major incidents generated a total of 14,051 SMS messages.
- This equated to an average of 1,757 SMS messages per major incident.

### Assumptions
- The average SMS volume per incident observed in September 2025 would have remained consistent if the SMS Communication Agent had not been implemented.

### Post-Implementation Analysis
- During Q1 2026, 35 major incidents were recorded.
- Using the historical average, these incidents were estimated to generate approximately 61,495 SMS messages without the SMS Communication Agent.
- Actual statistics showed only 17,120 SMS messages were sent during the same period following implementation.

### 🎖️Results
- Approximate reduction of 44,375 SMS messages.
- Approximate 72% reduction in total SMS volume.
- Significant reduction in SMS-related operational costs.
- Consistent SMS formatting and improved communication quality.
- Reduced manual effort required by Major Incident Managers during high-severity incidents.
