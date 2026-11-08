# Technology Stack Selection

Choose the smallest stack that meets the product requirements and the team's ability to operate it.

## Decision factors
- Existing codebase and team familiarity
- Hosting and deployment constraints
- Data model and transaction requirements
- SEO, rendering, and interaction needs
- Authentication and compliance requirements
- Operational cost and expected traffic
- Ecosystem maturity and maintenance

## Defaults are not mandates
For a TypeScript web product, consider React/Next.js or a lightweight Vite frontend based on routing, SEO, and server needs. For APIs, choose an established runtime and validation library. Select PostgreSQL for relational integrity and transactions unless another data model is clearly better.

## Deliverable
Record the selected stack, rejected alternatives, deployment model, database, authentication approach, testing strategy, and major trade-offs. Verify current package versions before installation.
