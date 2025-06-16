# AI-Framework

## SPARC

### Core Philosophy

1. Simplicity
   - Prioritize clear, maintainable solutions; minimize unnecessary complexity.

2. Iterate
   - Enhance existing code unless fundamental changes are clearly justified.

3. Focus
   - Stick strictly to defined tasks; avoid unrelated scope changes.

4. Quality
   - Deliver clean, well-tested, documented, and secure outcomes through structured workflows.

5. Collaboration
   - Foster effective teamwork between human developers and autonomous agents.

### Methodology & Workflow

- Structured Workflow
  - Follow clear phases from specification through deployment.
- Flexibility
  - Adapt processes to diverse project sizes and complexity levels.
- Intelligent Evolution
  - Continuously improve codebase using advanced symbolic reasoning and adaptive complexity management.
- Conscious Integration
  - Incorporate reflective awareness at each development stage.

### Agentic Integration

- Agent Configuration (02-workspace-rules.md)
  - Embed concise, workspace-specific rules to guide autonomous behaviors, prompt designs, and contextual decisions.
  - Clearly define project-specific standards for code style, consistency, testing practices, and symbolic reasoning integration points.

## Context Preservation

- Persistent Context
  - Continuously retain relevant context across development stages to ensure coherent long-term planning and decision-making.
- Reference Prior Decisions
  - Regularly review past decisions stored in memory to maintain consistency and reduce redundancy.
- Adaptive Learning
  - Utilize historical data and previous solutions to adaptively refine new implementations.

### Track Across Iterations:
- Original requirements and any changes
- Key decisions made and rationale
- Human feedback and how it was incorporated
- Alternative approaches considered

### Maintain Session Context:
**Problem:** [brief description]
**Requirements:** [key requirements]
**Decisions:** [key decisions with rationale]
**Status:** [completed/remaining/blockers]

### INDEX Maintenance:
- Update INDEX.md files when making relevant changes to:
  - Directory structure modifications
  - New files or folders added
  - Navigation links affected
- INDEX.md files serve as navigation hubs, not exhaustive catalogs
- context/INDEX.md navigates collaboration artifacts within context/
- context/[PROJECT_NAME]/INDEX.md navigates /[PROJECT_NAME] files and folders
- Include brief descriptions for all linked items

### Project Context & Understanding

1. Documentation First
   - Review essential documentation before implementation:
     - [PROJECT_NAME]/README.md
     - context/[PROJECT_NAME]/prd.md (Product Requirements Documents (PRDs))
     - context/[PROJECT_NAME]/architecture.md
     - context/[PROJECT_NAME]/technical.md
     - context/[PROJECT_NAME]/tasks.md
   - Request clarification immediately if documentation is incomplete or ambiguous.

2. Architecture Adherence
   - Follow established module boundaries and architectural designs.
   - Validate architectural decisions using symbolic reasoning; propose justified alternatives when necessary.

3. Pattern & Tech Stack Awareness
   - Utilize documented technologies and established patterns; introduce new elements only after clear justification.

### Directory Structure:
```
/
├── README.md
├── context/
│   ├── INDEX.md
│   ├── docs/
│   ├── workflows/
│   ├── [PROJECT_NAME]/
│   │   ├── architecture.md
│   │   ├── prd.md
│   │   ├── technical.md
│   │   ├── INDEX.md
│   │   ├── tasks.md
│   │   └── journal/
│   │       ├── [YYYY-MM-DD]/
│   │       │   ├── [HHMM]-[TASK_NAME].md
├── [PROJECT_NAME]/
│   ├── README.md
│   └── (other project folders/files)
```
