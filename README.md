# Amazon CodeCatalyst

Amazon CodeCatalyst is a unified software development service that helps teams collaborate more effectively on software projects. It provides integrated tools for source code management, CI/CD workflows, issue tracking, and cloud-based development environments (Dev Environments). Teams can use CodeCatalyst to accelerate development velocity, standardize workflows, and integrate natively with AWS services and third-party tools.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codecatalyst/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, Developer Tools, CI/CD, Collaboration, DevOps, Source Control

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CodeCatalyst API

The Amazon CodeCatalyst REST API provides programmatic access to spaces, projects, source repositories, Dev Environments, workflows, workflow runs, and user management. Build integrations, automate project workflows, and manage development environments programmatically.

**Human URL:** [https://docs.aws.amazon.com/codecatalyst/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/codecatalyst/latest/APIReference/Welcome.html)

#### Tags:

 - Amazon, AWS, Developer Tools, CI/CD, Collaboration

#### Properties

- [Documentation](https://docs.aws.amazon.com/codecatalyst/latest/userguide/)
- [APIReference](https://docs.aws.amazon.com/codecatalyst/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-codecatalyst-openapi-original.yaml)

## Common Properties

- [GettingStarted](https://docs.aws.amazon.com/codecatalyst/latest/userguide/getting-started-overview.html)
- [Authentication](https://docs.aws.amazon.com/codecatalyst/latest/userguide/tokens-overview.html)
- [Pricing](https://aws.amazon.com/codecatalyst/pricing/)
- [Console](https://codecatalyst.aws/)
- [Portal](https://aws.amazon.com/codecatalyst/)
- [Documentation](https://docs.aws.amazon.com/codecatalyst/latest/userguide/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/)
- [SignUp](https://codecatalyst.aws/)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Dev Environments | Cloud-based development environments pre-configured with your project code and tools enabling instant onboarding and eli |
| Source Repositories | Built-in Git repositories for hosting and managing source code with branching, pull requests, and code review capabiliti |
| CI/CD Workflows | Visual workflow builder for creating automated build, test, and deployment pipelines with native AWS service integration |
| Project Management | Integrated issue tracking and project boards for organizing work, tracking bugs, and managing feature development alongs |
| Spaces | Organizational units for grouping projects and managing team membership, billing, and resource access across an organiza |
| Third-Party Integrations | Connect to GitHub repositories, Jira, Slack, and other third-party tools to incorporate CodeCatalyst into existing devel |

## Use Cases

| Name | Description |
|------|-------------|
| Rapid Developer Onboarding | Use Dev Environments to eliminate local development setup time, allowing new developers to be productive within minutes  |
| Standardized CI/CD Pipelines | Create and enforce consistent build, test, and deployment workflows across all projects in a space, reducing inconsisten |
| Collaborative Code Development | Enable distributed teams to collaborate on source code through integrated repositories, pull requests, and code review w |

## Integrations

| Name | Description |
|------|-------------|
| GitHub | Connect GitHub repositories to CodeCatalyst projects and sync code. |
| Jira | Link CodeCatalyst issues with Jira for unified project tracking. |
| Slack | Receive CodeCatalyst notifications and workflow status updates in Slack. |
| Amazon Q Developer | AI coding assistance integrated into Dev Environments and code reviews. |
| AWS Lambda | Deploy serverless functions as part of CodeCatalyst CI/CD workflows. |
| Amazon ECS | Deploy containerized applications to ECS from CodeCatalyst pipelines. |
| AWS CloudFormation | Deploy infrastructure as code using CloudFormation actions in workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codecatalyst-openapi-original](openapi/amazon-codecatalyst-openapi-original.yaml)

### JSON Schema

170 JSON Schema files generated from the OpenAPI specification.

- [amazon-codecatalyst-access-token-id-schema](json-schema/amazon-codecatalyst-access-token-id-schema.json)
- [amazon-codecatalyst-access-token-name-schema](json-schema/amazon-codecatalyst-access-token-name-schema.json)
- [amazon-codecatalyst-access-token-secret-schema](json-schema/amazon-codecatalyst-access-token-secret-schema.json)
- [amazon-codecatalyst-access-token-summaries-schema](json-schema/amazon-codecatalyst-access-token-summaries-schema.json)
- [amazon-codecatalyst-access-token-summary-schema](json-schema/amazon-codecatalyst-access-token-summary-schema.json)
- ...and 165 more in [json-schema/](json-schema/)

### JSON Structure

170 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codecatalyst-context](json-ld/amazon-codecatalyst-context.jsonld)

### Examples

170 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codecatalyst](capabilities/shared/codecatalyst.yaml) — 33 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeCatalyst Developer Collaboration](capabilities/amazon-codecatalyst-developer-collaboration.yaml) | codecatalyst | 10 | DevOps Engineer |

## Vocabulary

- [amazon-codecatalyst-vocabulary](vocabulary/amazon-codecatalyst-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 5 actions, 1 workflows, and 2 personas

## Rules

- [amazon-codecatalyst-spectral-rules](rules/amazon-codecatalyst-spectral-rules.yml) — 15 rules enforcing Amazon CodeCatalyst API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
