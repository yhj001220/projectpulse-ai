# ProjectPulse AI

**AI-Powered Project Monitoring & Risk Management**

ProjectPulse AI is a web-based project management decision-support tool designed to help project coordinators and project managers monitor project progress, identify potential risks, and make informed decisions using AI.

The application combines structured project data, development activity records, and AI-assisted analysis to improve project visibility and support proactive risk management.

## 1. Project Overview

### Problem Statement

Effective project management requires accurate information about task progress, project schedules, milestones, and potential risks.

However, project tracking tools do not always reflect actual project activities. Team members may forget to update task statuses, leave incomplete progress reports, or complete development work without creating corresponding issues.

These inconsistencies can make it difficult for project managers to understand project health, identify potential delays, and determine which tasks require attention.

Additionally, project risks may emerge from information that is not captured by predefined tracking metrics, such as meeting notes, changing requirements, or stakeholder concerns.

### Proposed Solution

ProjectPulse AI aims to improve project visibility by analyzing project records, identifying potential risks, and providing evidence-based recommendations.

Rather than replacing existing project management platforms, ProjectPulse AI is designed to complement tools such as GitLab and Jira.

The system supports project management decisions without automatically determining whether a task is complete or whether a project will fail.

## 2. Core Features

### 2.1 Project Health Monitoring

- Monitor project milestones, deadlines, and task progress.
- Identify overdue tasks and potential scheduling issues.
- Visualize project health through an interactive dashboard.
- Highlight tasks and milestones requiring management attention.

### 2.2 AI Risk Identification

- Analyze structured project data and unstructured project documentation.
- Identify potential risks related to scheduling, dependencies, resources, and changing requirements.
- Discover additional risk candidates from issue descriptions, progress updates, and meeting notes.
- Explain identified risks using supporting evidence.
- Recommend potential mitigation strategies.

### 2.3 Progress Verification

- Compare recorded issue statuses with available development activity metadata.
- Identify outdated or missing progress updates.
- Detect commits and merge requests without verified issue associations.
- Highlight inconsistencies that require manual verification.
- Distinguish missing project information from confirmed project delays.

Development activity is treated as supporting evidence rather than proof of task completion.

### 2.4 AI Project Reporting

- Generate project status summaries.
- Identify major risks and unresolved issues.
- Summarize tasks requiring follow-up.
- Recommend potential management actions.
- Support stakeholder communication and project reporting.

## 3. Risk Analysis Approach

ProjectPulse AI combines rule-based monitoring with AI-assisted risk identification.

**Rule-Based Analysis**

Identifies measurable conditions such as:

- Overdue tasks
- Missing progress updates
- Unresolved task dependencies
- Inconsistencies between issue statuses and development activity
- Unlinked development activities

**AI-Assisted Analysis**

Uses project documentation and activity records to:

- Identify potential risks not covered by predefined rules
- Explain possible causes and impacts
- Generate clarification questions
- Recommend mitigation actions

AI-generated findings are treated as potential risks requiring human review.

The system distinguishes between:

- **Project Delivery Risk:** Potential threats to project deadlines, scope, resources, or deliverables.
- **Project Visibility Risk:** Missing, outdated, or inconsistent information that prevents accurate assessment of project progress.

## 4. Technology Stack

| Category | Technology |
|---|---|
| Frontend | TypeScript, Preact, HTML, CSS |
| Backend | Python, FastAPI |
| Data Processing | Pandas |
| AI Integration | OpenAI API |
| Database | SQLite |
| Version Control | Git, GitHub |
| Planned Integrations | GitLab API, Jira API |

The technology stack is planned and may be adjusted during development.

## 5. Data Sources

### Initial Development

The initial version will use CSV files containing project management information, including:

- Issues and task records
- Commit metadata
- Merge request metadata
- Progress updates and comments
- Project milestones and deadlines

Meeting notes and other project documentation may also be provided for AI-assisted risk identification.

### Future Integrations

Future versions will support direct data retrieval through:

- GitLab API
- Jira API

The long-term goal is to reduce manual data collection and support automated project monitoring.

## 6. Initial Use Case: Seatly

The initial use case is based on Seatly, a university library seat reservation system developed as a team software engineering project.

The project has experienced challenges related to:

- Outdated issue statuses
- Missing progress updates
- Development activities without corresponding issue records

ProjectPulse AI will use these challenges as initial test scenarios for its project monitoring and risk identification features.

Private project information will remain separate from the public repository. Public demonstrations will use synthetic or appropriately authorized data.

## 7. Development Roadmap

| Week | Development Phase | Deliverable |
|---|---|---|
| 1 | Project Planning & Requirements | Project Charter, Requirements, Data Model |
| 2 | CSV Data Processing | Data Import & Validation |
| 3 | Project Activity Monitoring | Progress Verification & Rule-Based Detection |
| 4 | AI Risk Identification | Risk Analysis & Recommendations |
| 5 | Dashboard & Reporting | Interactive Dashboard & Project Reports |
| 6 | Testing & Deployment | Tested MVP, Documentation & Demo |

## 8. Project Scope

### In Scope

- CSV-based project data analysis
- Project health dashboard
- Task and milestone monitoring
- Progress verification
- Rule-based risk detection
- AI-assisted risk identification
- Evidence-based recommendations
- Project status reporting
- Manual review of AI findings

### Out of Scope — Initial MVP

- Automated code review
- Automatic modification of GitLab or Jira issues
- Autonomous project management decisions
- Custom AI model training
- Advanced machine learning predictions
- Enterprise authentication and permission management
- Real-time collaboration
- Full GitLab/Jira API integration

## 9. Success Criteria

The initial MVP will be considered successful when it can:

1. Import and validate structured project data from CSV files.
2. Identify predefined project monitoring issues.
3. Detect missing or inconsistent progress information.
4. Generate AI-assisted risk explanations supported by available evidence.
5. Present findings through a project dashboard.
6. Generate a project status report with recommended follow-up actions.
7. Allow users to review AI-generated findings.
8. Demonstrate the system using realistic project scenarios.

## 10. Future Improvements

- Direct GitLab and Jira API integration
- Automated project monitoring
- Historical project performance analysis
- What-if schedule simulations
- Advanced risk prediction models
- Multi-project portfolio monitoring
- Customizable risk assessment criteria

## 11. Project Status

**Current Phase:** Planning & Requirements Definition

**Development Duration:** 6 Weeks (Planned)

**Project Type:** Individual Portfolio Project

**Development Approach:** Agile / Iterative Development

All features described in this README are currently planned unless explicitly identified as implemented.

---

### Project Goal

To develop a practical AI-assisted project management tool that improves project visibility, identifies potential risks, and helps project managers make evidence-based decisions.
