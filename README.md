# SMS Communication Agent
An AI-powered Major Incident Management agent that automatically transforms detailed incident email communications into concise stakeholder SMS updates. The agent interprets incident content, identifies communication intent, extracts critical information, and generates GSM-7 compliant messages within the 160-character SMS limit.

<img width="1536" height="1024" alt="Solution Architecture" src="https://github.com/user-attachments/assets/e033380d-df49-4d41-93d8-794497ffede7" />

## Project Highlights
- Reduced SMS volume by more than 70%, delivering significant communication cost savings.
- Eliminated manual conversion of incident emails into SMS communications.
- Enforced GSM-7 compliance and strict 160-character SMS limits.
- Improved communication consistency through standardised SMS templates.
- Built using Microsoft Copilot Studio and Claude Sonnet 4.6.
- Reduced effort for Major Incident Managers during high-severity incidents.

 ## Business Value
The SMS Communication Agent addresses operational challenges by automatically transforming detailed incident communications into concise, standardised stakeholder SMS updates. By automating message generation, enforcing GSM-7 compliance, applying intelligent content compression, and ensuring strict adherence to communication standards, the solution significantly reduces manual effort while improving communication speed, consistency, and accuracy.

The solution enables Major Incident Managers to spend less time crafting communications and more time focusing on incident resolution, stakeholder engagement, and service restoration activities. Additionally, the reduction in concatenated SMS messages has delivered substantial savings in SMS consumption and communication costs while improving the overall stakeholder communication experience.

 ## Problem Statement
Major Incident Managers were required to manually convert detailed incident email communications into concise SMS updates for stakeholders. This process was highly manual, time-consuming, and prone to inconsistency, particularly during high-severity incidents where rapid communication was critical.

 ### Key challenges included
- Manually reviewing lengthy incident communications to identify the most relevant information for stakeholders.
- Condensing complex incident updates into the strict 160-character SMS limit while preserving essential details.
- Frequent use of concatenated SMS messages when communications exceeded character limits, increasing SMS volume and communication costs.
- Inconsistent message quality and wording across different Major Incident Managers.
- Risk of human error through omission of important incident details, incorrect abbreviations, or inconsistent formatting.
- High turnaround time between email publication and SMS distribution, delaying stakeholder awareness during critical incidents.
- Manual enforcement of GSM-7 compliance to avoid unintended UCS-2 encoding and additional SMS charges.
- Difficulty maintaining communication standards during high-pressure incidents where multiple updates were issued in quick succession.
- Lack of a standardized communication approach, resulting in varying stakeholder experiences and message quality.
- Increased operational effort during major incidents, diverting Major Incident Managers from incident coordination and stakeholder management activities.

## My Contribution
- Identified operational communication challenges during major incidents.
- Designed the solution architecture and communication framework.
- Developed the AI agent using Microsoft Copilot Studio.
- Defined SMS templates, guardrails, GSM-7 constraints, and hallucination prevention controls.
- Led testing and rollout activities.
- Measured and reported business outcomes following implementation.
  
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

## Measurable Outcomes
Following implementation of the SMS Communication Agent, an analysis was performed using historical and post-implementation SMS usage data.

### Results
- Achieved a reduction of more than 70% in SMS volume.
- Significant reduction in SMS-related communication costs.
- Reduced use of concatenated SMS messages.
- Improved communication consistency across Major Incident Managers.
- Reduced manual effort required during high-severity incidents.
- Improved stakeholder communication quality through standardised messaging.

### Methodology
The analysis compared historical SMS communication patterns against actual post-implementation usage following the rollout of the SMS Communication Agent. Historical averages were used to estimate expected SMS volume in the absence of the solution, and actual usage was compared against this baseline.
