# ProjectPulse AI

**AI-Powered Project Monitoring & Decision Support System**

ProjectPulse AI is an AI-assisted project management application designed to help project coordinators and project managers monitor project progress, identify potential risks, and make data-driven decisions.

The application combines project management data, development activity records, and AI-assisted analysis to improve project visibility, detect inconsistencies, and support proactive project management.

## 1. Project Overview

### Problem Statement

Effective project management requires accurate and up-to-date information about task progress, project schedules, milestones, and potential risks.

However, project management tools do not always reflect actual project activities. Team members may forget to update issue statuses, leave incomplete progress reports, or complete development work without creating corresponding tasks.

These inconsistencies can make it difficult for project coordinators to accurately assess project health, identify potential delays, and communicate progress to stakeholders.

Additionally, manually reviewing project activities and preparing status reports can be time-consuming.

### Proposed Solution

ProjectPulse AI aims to address these challenges by providing a centralized project monitoring and decision-support system.

The application will analyze project records, compare task statuses with development activity, identify potential risks, and generate AI-assisted project reports.

Rather than replacing existing project management tools, ProjectPulse AI is designed to complement platforms such as GitLab and Jira.

The system will provide evidence-based insights and recommendations while keeping final project management decisions under human control.

## 2. Core Features

### 2.1 Project Health Dashboard

Provides an overview of project progress and overall project health.

**Key Functions:**
- Track project tasks, milestones, and deadlines.
- Display task completion status and overall progress.
- Identify overdue tasks and upcoming deadlines.
- Highlight unresolved issues requiring attention.
- Visualize project information through an interactive dashboard.

### 2.2 Progress Verification

Identifies inconsistencies between recorded task progress and available development activities.

**Key Functions:**
- Compare GitLab issue statuses with commit and merge request metadata.
- Identify tasks with outdated progress information.
- Detect missing or insufficient progress updates.
- Highlight development activities without verified issue associations.
- Flag inconsistencies requiring manual review.

Development activities will be treated as supporting evidence rather than definitive proof of task completion.

### 2.3 AI Risk Analysis

Uses structured project data and AI-assisted analysis to identify potential project risks.

**Key Functions:**
- Detect potential scheduling and milestone risks.
- Identify unresolved dependencies and overdue tasks.
- Analyze issue descriptions, progress updates, and meeting notes.
- Generate explanations for identified risk candidates.
- Recommend potential mitigation strategies.
- Provide supporting evidence for risk findings.

The system will distinguish between:

- **Project Delivery Risk:** Potential threats to project deadlines, scope, resources, or deliverables.
- **Project Visibility Risk:** Missing, outdated, or inconsistent information that prevents accurate assessment of project progress.

AI-generated findings will require human review and will not be treated as confirmed project outcomes.

### 2.4 AI Project Reporting

Automatically generates project status summaries to support stakeholder communication.

**Key Functions:**
- Summarize overall project progress.
- Highlight major risks and unresolved issues.
- Identify tasks requiring follow-up.
- Recommend potential management actions.
- Generate structured weekly project status reports.

## 3. Technology Stack

| Category | Technology |
|---|---|
| Frontend | TypeScript, Preact, HTML, CSS |
| Backend | Python, FastAPI |
| Data Processing | Pandas |
| Database | SQLite |
| AI Integration | OpenAI API |
| Version Control | Git, GitHub |
| Future Integrations | GitLab API, Jira API |

The technology stack may be adjusted as development progresses.

## 4. Data Sources

### Initial Development

The initial MVP will use CSV-based project records, including:

- Project tasks and issues
- Task statuses and deadlines
- Project milestones
- Commit metadata
- Merge request metadata
- Progress updates and issue comments

Additional project documentation, such as meeting notes and issue descriptions, may be used for AI-assisted risk analysis.

### Future Integrations

Future versions may support direct integration with:

- GitLab API
- Jira API

These integrations would allow project data to be retrieved automatically rather than through manual CSV uploads.

## 5. Initial Use Case: Seatly

The initial use case is inspired by Seatly, a university library seat reservation system developed as a team software engineering project.

During the project, several project tracking challenges were observed:

- Issue statuses were not always updated to reflect actual progress.
- Some tasks lacked sufficient progress documentation.
- Certain development activities were not associated with corresponding issues.

These challenges motivated the development of ProjectPulse AI.

The application will use representative project scenarios to evaluate its ability to identify progress inconsistencies, improve project visibility, and support risk management.

Private team information and confidential project data will not be published. Public demonstrations will use synthetic or appropriately authorized data.

## 6. Development Roadmap

The project is planned as a six-week individual development project.

| Week | Phase | Deliverables |
|---|---|---|
| Week 1 | Planning & Requirements | Project Charter, Requirements, Data Model |
| Week 2 | Data Processing | CSV Import, Data Validation, SQLite Storage |
| Week 3 | Project Monitoring | Task Monitoring, Progress Verification, Rule-Based Risk Detection |
| Week 4 | AI Integration | AI Risk Analysis, Evidence-Based Recommendations |
| Week 5 | Dashboard & Reporting | Interactive Dashboard, Weekly Project Reports |
| Week 6 | Testing & Deployment | MVP Testing, Evaluation, Documentation, Deployment |

## 7. MVP Scope

### In Scope

- CSV-based project data import
- Project health dashboard
- Task and milestone monitoring
- Progress verification
- Rule-based risk detection
- AI-assisted risk identification
- Evidence-based risk explanations
- Recommended follow-up actions
- Weekly project status report generation
- Human review of identified risks

### Out of Scope

The following features are excluded from the initial MVP:

- Automated code review
- Advanced machine learning prediction models
- Autonomous project management decisions
- Automatic modification of GitLab or Jira records
- Full GitLab/Jira API integration
- Real-time team collaboration
- Enterprise authentication and authorization
- Multi-project portfolio management

## 8. Project Evaluation

ProjectPulse AI will be evaluated using realistic project management scenarios.

### Evaluation Metrics

**Progress Verification Accuracy**

Evaluate whether the system correctly identifies outdated or inconsistent project records.

**Risk Identification Quality**

Assess whether identified risks are supported by relevant project evidence and are useful for management review.

**Reporting Efficiency**

Compare the time required to prepare project status reports manually with the time required using ProjectPulse AI.

**Dashboard Usability**

Evaluate whether users can easily identify overdue tasks, unresolved issues, and project risks.

**Recommendation Relevance**

Assess whether AI-generated recommendations are actionable and appropriate for the available project information.

## 9. Success Criteria

The initial MVP will be considered successful when it can:

1. Import and validate project data from CSV files.
2. Store and retrieve project records using SQLite.
3. Display project progress through an interactive dashboard.
4. Identify overdue tasks and missing progress updates.
5. Detect inconsistencies between task records and development activities.
6. Generate AI-assisted risk explanations supported by available evidence.
7. Recommend appropriate follow-up actions.
8. Generate structured weekly project status reports.
9. Allow users to review identified risks.
10. Demonstrate the application using realistic project scenarios.

## 10. Project Management Skills Demonstrated

This project is designed to demonstrate practical skills relevant to Project Coordinator, IT Project Analyst, and IT Project Management roles.

**Project Planning & Coordination**
- Requirements gathering and analysis
- Scope definition
- Milestone planning
- Project scheduling
- Agile project management

**Risk Management**
- Risk identification
- Risk assessment
- Risk documentation
- Mitigation planning
- Progress monitoring

**Data Analysis & Reporting**
- Project performance analysis
- Data validation
- Dashboard development
- KPI monitoring
- Stakeholder reporting

**Technical Skills**
- Python and TypeScript development
- SQL database management
- REST API development
- AI API integration
- Git version control

## 11. Future Improvements

Potential future enhancements include:

- Direct GitLab and Jira API integration
- Automated project activity synchronization
- Historical project performance analysis
- Customizable risk assessment criteria
- Project schedule simulation
- Multi-project portfolio monitoring
- Advanced project risk prediction

## 12. Project Status

**Current Phase:** Planning & Requirements Definition

**Project Type:** Individual Portfolio Project

**Development Duration:** 6 Weeks (Planned)

**Development Approach:** Agile / Iterative Development

**Target Roles:** Project Coordinator, IT Project Analyst, IT Project Management

The application is currently in the planning stage. The features described above represent planned functionality and will be implemented incrementally.

---

## Project Goal

The goal of ProjectPulse AI is to demonstrate how AI, data analytics, and software development can be applied to real-world project management challenges.

By improving project visibility, identifying potential risks, and supporting evidence-based decisions, ProjectPulse AI aims to help project coordinators manage projects more effectively.
