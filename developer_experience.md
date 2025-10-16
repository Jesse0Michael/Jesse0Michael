# Developer Experience
DevEx is the systems, patterns, tools, and 
DevEx removes hurdles for developer onboarding, development, maintenance, and troubleshooting. 

> Developer Experience is **NOT** *developer familiarity*. It does not force developers to use the tools and processes that ***you're*** familiar with.
> 
> **Developer Familiarity:**
> - Locks teams into old patterns and brittle workflows  
> - Normalizes friction in workflows  
> - Discourages exploration because “that’s how we’ve always done it”  
> - Rewards obscure in-house practices instead of adopting clear standards.

## DevEx
- Fast, self-service onboarding  
- Small feedback loops (Reviews, CI, Testing, Deployment)  
- Easy-to-install tooling and reproducible local environments with explicit dependencies and no hidden prerequisites
- Automation for repetitive setup and maintenance, Code generation where appropriate  
- Discoverable and current documentation
- Organized repositories and codebases (knowing where things belong should be intuitive)  
- Quality Guardrails (linting, templates, patterns)

## Testing
When tests are difficult to write, they are often skipped. Developer experience comes into play by making it easy to write tests by removing friction and hurdles.

It must be easy to:
- Write new tests
- Run tests locally, **quickly** and **reliably**
- Mock dependencies and external systems and spin up local test environments
- Understand test failures, debug tests, and remove flakiness
