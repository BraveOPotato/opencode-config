---
description: Start a large implementation, migration, framework port, or application build using the architect-builder-integrator workflow.
agent: builder
---

Treat the following as a large engineering project:

$ARGUMENTS

Before substantial implementation:

1. Inspect enough of the repository to understand the request.
2. Invoke the architect subagent.
3. Produce or update durable architecture/migration documentation under docs/.
4. Turn the architecture into bounded milestones with acceptance criteria.
5. Begin implementation with the first milestone.
6. Run relevant tests after each milestone.
7. Keep the documented status current.

Use the integrator subagent when implementation reveals an architectural
problem rather than repeatedly guessing.

Do not attempt the entire project as one monolithic coding pass.
