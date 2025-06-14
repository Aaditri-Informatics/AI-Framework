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
