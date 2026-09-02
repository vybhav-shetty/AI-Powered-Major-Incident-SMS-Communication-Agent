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
Following implementation of the SMS Communication Agent, an analysis was performed using historical and post-implementation SMS usage data.

### Results
- Approximately 72% reduction in SMS volume.
- Significant reduction in SMS-related communication costs.
- Reduced use of concatenated SMS messages.
- Improved communication consistency across Major Incident Managers.
- Reduced manual effort required during high-severity incidents.
- Improved stakeholder communication quality through standardised messaging.

### Methodology
The analysis compared historical SMS communication patterns against actual post-implementation usage following the rollout of the SMS Communication Agent. Historical averages were used to estimate expected SMS volume in the absence of the solution, and actual usage was compared against this baseline.
