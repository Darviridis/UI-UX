### Expose your design system to LLMs
https://hvpandya.com/llm-design-systems

### Building AI-driven workflows
https://uxdesign.cc/designing-with-claude-code-and-codex-cli-building-ai-driven-workflows-powered-by-code-connect-ui-f10c136ec11f

### Your design system has been lying to you
https://designsystemsforai.com

### Spec-Driven UI Component Development
https://nathanacurtis.substack.com/p/spec-driven-ui-component-development

### Component Contracts and Schemas
https://nathanacurtis.substack.com/p/component-contracts-and-schemas

### What Component Specs Leave Behind
https://nathanacurtis.substack.com/p/what-component-specs-leave-behind

### Generating Code from Figma via Specs
https://nathanacurtis.substack.com/p/generating-code-from-specs

### Design System Conventions in Figma
https://nathanacurtis.substack.com/p/design-system-conventions-in-figma

### Design system contracts: the component lives in neither Figma nor code
https://christinevallaure.substack.com/p/design-system-contracts-the-component

### Design systems are contracts, not libraries
https://www.giorris.dev/thoughts/design-systems-are-contracts-not-libraries

### Building design system components with agent teams
https://www.kaelig.fr/design-system-components-with-ai-agent-teams/?ref=blog.murphytrueman.com

### How Coinbase Used Code Connect to Guide Agents and Shrink Token Costs
https://www.figma.com/blog/how-coinbase-used-code-connect-to-shrink-token-costs/

### You Don't Have a Design System
https://mattrothenberg.com/notes/you-dont-have-a-design-system/

### The call for an agentic standard: We need to stop shipping the same form four different times
https://uxdesign.cc/the-call-for-an-agentic-standard-we-need-to-stop-shipping-the-same-form-four-different-times-be5b9d40e370

### How to Make Your Design System Agent-Ready
https://medium.com/design-bootcamp/how-to-make-your-design-system-agent-ready-ea4cfc062270

My notes:

1. Preparing and organizing the Figma file
2. Components have consistent naming conventions (check)
3. Props and variants follow semantic patterns
4. Create tokens for colors, typography, spacings, radius (Token architecture is three-tier minimum)
5. Publish library
6. Create spec files: design.md, tokens.json, components (yaml - Spec2), assets (svg), agents.md
7. Change your hex to tokens in yaml
8. Create metadata docs for components (docs.yaml)
9. Create JSON files with schema validation
10. Create code examples
11. Design decisions are documented with rationale (I skip it for now)
12. Create llms.txt
13. Create primitives.css и semantic.css
14. Code Connect
15. Built a React + Vite codebase, structured around three core folders:
- styles: with primitives.css, semantic.css, and components.css
- components: where each component included its .tsx, .stories.tsx, and .css file
- pages: a directory used for testing prototypes

After code

1. Add a code syntax in Figma
2. Write a script to audit




