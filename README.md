# SMS Communication Agent
An AI-powered Major Incident Management agent that converts detailed incident email communications into concise stakeholder SMS updates. The agent interprets incident content, identifies communication intent, extracts critical information, and generates GSM-7 compliant messages within the 160-character SMS limit.

## Project Highlights
- Achieved a reduction of more than 70% in SMS volume following implementation.
- Built using Claude Sonnet 4.6
- Generates GSM-7 compliant SMS communications
- Enforces strict 160-character limit
- Automates Major Incident SMS creation
- Improved communication consistency and significantly reduced manual effort
  
## Technology Stack 
- Microsoft Copilot Studio
- Claude Sonnet 4.6
- Generative AI
- Prompt Engineering


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
    Next Update Time
- Generates SMS messages using predefined templates based on communication status.
- Ignores unnecessary content such as historical updates and non-essential information.
- Strictly enforces a 160-character limit for all SMS content.
- Optimises wording through intelligent compression and abbreviation when required.
- Ensures GSM-7 compatibility by preventing UCS-2 encoding and excluding unsupported characters, emojis, and special symbols.
- Automatically appends: 'Refer to the email communication for detailed information' at the end of every communication.
- Restricts output to information explicitly provided in the incident communication, minimising the risk of AI-generated assumptions or hallucinated content.
  
## Business Value
Automates the generation of stakeholder SMS communications during major incidents, reducing manual effort and enabling faster delivery of critical updates. By converting detailed incident communications into concise, GSM-7 compliant messages, the solution improves communication consistency, operational efficiency, and overall incident response effectiveness.

## Measurable Outcomes
Following implementation of the SMS Communication Agent, an analysis was performed using historical and post-implementation SMS usage data.

### Results
- Achieved a reduction of more than 70% in SMS volume following implementation.
- Significant reduction in SMS-related communication costs.
- Reduced use of concatenated SMS messages.
- Improved communication consistency across Major Incident Managers.
- Reduced manual effort required during high-severity incidents.
- Improved stakeholder communication quality through standardised messaging.

### Methodology
The analysis compared historical SMS communication patterns against actual post-implementation usage following the rollout of the SMS Communication Agent. Historical averages were used to estimate expected SMS volume in the absence of the solution, and actual usage was compared against this baseline.
