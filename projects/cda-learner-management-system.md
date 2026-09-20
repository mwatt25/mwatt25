# CDA Learner Management System

## Program management and learner-progress system

**Status:** Private operational prototype  
**Focus:** implementation, program operations, learner tracking, workflow design

### The problem

Professional credential programs often require staff to track many moving parts at once: learner progress, documentation, verification steps, credential status, milestone completion, communication, and follow-up.

When that information lives across disconnected tools, staff spend too much time reconstructing status instead of supporting learners.

### The solution

I designed a learner-management system around the actual program workflow rather than around a generic database structure.

The system was built to support:

- Cohort-level progress monitoring
- Individual learner status
- Credential milestones
- Administrative follow-up
- Document and workflow visibility
- Reporting and program oversight
- Clearer identification of learners who need attention

### Product thinking

The goal was not to create another place to store information. The goal was to make the next action easier to see.

That meant organizing the experience around questions such as:

- Who needs follow-up?
- Which step is holding up progress?
- What has already been completed?
- What milestone comes next?
- What information does staff need without opening several systems?

### Technology

The private application uses a modern TypeScript and React stack with server-side application logic, database tooling, file-storage capabilities, and email integration.

### What this project demonstrates

- Turning a real operational process into a usable system
- Mapping program workflows before designing screens
- Designing for implementation staff, not only end users
- Data organization and dashboard thinking
- Connecting learner support with operational efficiency

### Privacy

No real learner records, contact information, credentials, or program data are published in this case study. The production repository remains private.
