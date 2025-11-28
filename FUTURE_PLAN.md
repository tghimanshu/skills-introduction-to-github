# Future Plan: Introduction to GitHub Course

## Phase 1: Current State (Completed)
- **Core Course Structure**: A functional interactive course guiding users through branching, committing, pull requests, and merging.
- **Workflow Automation**: Robust GitHub Actions workflows handling state transitions and user verification.
- **Documentation**: Comprehensive documentation of workflows and developer guides.

## Phase 2: Future Enhancements

The following are proposed enhancements for the next phase of development:

### 1. Expanded Curriculum
- **Merge Conflicts**: Add a step that intentionally creates a merge conflict, teaching the user how to resolve it in the UI.
- **Issues and Projects**: Introduce GitHub Issues and Project boards as part of the workflow.
- **Code Review**: Add a step where the "bot" reviews the user's PR and requests changes, simulating a real code review process.

### 2. Infrastructure and Quality
- **Automated Testing**: Implement tests that simulate user actions to verify that the course workflows trigger and complete correctly. This prevents regressions when modifying the course logic.
- **Linting**: Add linting for Markdown files (`markdownlint`) and YAML files (`yamllint`) to ensure consistency.

### 3. Localization
- **Multi-language Support**: Structure the content to support multiple languages, allowing non-English speakers to benefit from the course.

### 4. improved User Feedback
- **Detailed Error Messages**: If a user performs an incorrect action (e.g., names the branch wrong), provide actionable feedback via a comment on the PR or an Issue, rather than failing silently.
