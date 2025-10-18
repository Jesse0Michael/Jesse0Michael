# Developer Experience
DevEx is the systems, patterns, tools, and processes that make development enjoyable and productive.  
DevEx removes hurdles for developer onboarding, development, maintenance, and troubleshooting. 

> Developer familiarity is **NOT** *developer experience*. 
> Forcing tools and processes that ***you're*** familiar with is not a good developer experience. Even when they work for ***you**.
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

## Infrastructure as Code
Infrastructure should be defined as code, stored in version control, and reviewed through pull requests.
- The infrastructure will be reproducible and consistent
- Changes to infrastructure will be auditable and not forgotten
- Infrastructure will be easier to understand and maintain
- Changes can be automated
