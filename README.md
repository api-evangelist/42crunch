# 42Crunch (42crunch)
42Crunch is a leading API security company that specializes in protecting and securing APIs. They provide innovative solutions that help organizations safeguard their sensitive data and critical assets from potential cyber threats. With their comprehensive API security platform, 42Crunch offers a range of services such as API scanning, traffic monitoring, and runtime protection to ensure that APIs are secure and compliant with industry standards. Their platform covers the full API security lifecycle from design and audit through dynamic testing and runtime firewall protection.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Security, Platform, Scanning, Security, OpenAPI, DevSecOps

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### 42Crunch API Security Audit
The 42Crunch API Security Audit performs automated static analysis of API definitions (OpenAPI 2, 3.0, 3.1 and GraphQL), running over 200 checks across format validation, data definition quality, and security analysis. APIs are scored 0-100 with recommendations to reach 70+ before runtime protection is applied. Integrates with CI/CD pipelines for continuous monitoring.

**Human URL:** [https://docs.42crunch.com/latest/content/concepts/api_contract_security_audit.htm](https://docs.42crunch.com/latest/content/concepts/api_contract_security_audit.htm)

#### Tags:

 - API Security, Static Analysis, OpenAPI, Vulnerability Scanning

#### Properties

- [Documentation](https://docs.42crunch.com/latest/content/concepts/api_contract_security_audit.htm)
- [APIReference](https://docs.42crunch.com/latest/content/home.htm)

### 42Crunch API Scan
42Crunch API Scan performs dynamic API security testing (DAST) that evaluates runtime API behavior against its OpenAPI specification. It tests how well an API adheres to its contract and identifies vulnerabilities that only appear at runtime. Supports integration with CI/CD pipelines and Kubernetes via the scand-manager Kubernetes wrapper.

**Human URL:** [https://docs.42crunch.com/latest/content/home.htm](https://docs.42crunch.com/latest/content/home.htm)

#### Tags:

 - API Security, Dynamic Testing, DAST, Contract Testing

#### Properties

- [Documentation](https://docs.42crunch.com/latest/content/home.htm)

### 42Crunch API Protection
42Crunch API Protection deploys an API-native micro firewall (API Firewall) that provides runtime defense against API attacks. The firewall is tailor-made for each API based on its OpenAPI specification and enforces API contract compliance in real time, blocking malformed requests and unauthorized access.

**Human URL:** [https://docs.42crunch.com/latest/content/home.htm](https://docs.42crunch.com/latest/content/home.htm)

#### Tags:

 - API Security, Runtime Protection, Firewall, API Gateway

#### Properties

- [Documentation](https://docs.42crunch.com/latest/content/home.htm)

### 42Crunch API Conformance Scan Jobs Manager
The 42Crunch Scand Manager provides a convenient way to run 42Crunch API Conformance Scans on-premises as Kubernetes Jobs. It manages the full lifecycle of scan jobs including creation, status monitoring, log retrieval, and deletion.

**Human URL:** [https://github.com/42Crunch/scand-manager](https://github.com/42Crunch/scand-manager)

#### Tags:

 - API Security, Kubernetes, Conformance Scanning, DevSecOps

#### Properties

- [Documentation](https://github.com/42Crunch/scand-manager)
- [OpenAPI](openapi/42crunch-scand-manager.yaml)
- [JSONSchema - Job Name Schema](json-schema/scand-manager-job-name-schema.json)
- [JSONSchema - Jobs Schema](json-schema/scand-manager-jobs-schema.json)
- [JSONSchema - Job Spec Schema](json-schema/scand-manager-job-spec-schema.json)
- [JSONSchema - Job Status Schema](json-schema/scand-manager-job-status-schema.json)
- [JSONSchema - Error Schema](json-schema/scand-manager-error-schema.json)
- [JSONStructure - Job Name Structure](json-structure/scand-manager-job-name-structure.json)
- [JSONStructure - Jobs Structure](json-structure/scand-manager-jobs-structure.json)
- [JSONStructure - Job Spec Structure](json-structure/scand-manager-job-spec-structure.json)
- [JSONStructure - Job Status Structure](json-structure/scand-manager-job-status-structure.json)
- [JSONStructure - Error Structure](json-structure/scand-manager-error-structure.json)
- [Example - Job Name Example](examples/scand-manager-job-name-example.json)
- [Example - Jobs Example](examples/scand-manager-jobs-example.json)
- [Example - Job Spec Example](examples/scand-manager-job-spec-example.json)
- [Example - Job Status Example](examples/scand-manager-job-status-example.json)
- [Example - Error Example](examples/scand-manager-error-example.json)

## Common Properties

- [Website](https://42crunch.com/)
- [Documentation](https://docs.42crunch.com/latest/content/home.htm)
- [Blog](https://42crunch.com/blog/)
- [Support](https://support.42crunch.com/hc/en-us)
- [Pricing](https://42crunch.com/pricing/)
- [Tutorials](https://42crunch.com/tutorials/)
- [Webinars](https://42crunch.com/webinars/)
- [Partners](https://42crunch.com/partners/)
- [Login](https://platform.42crunch.com/login)
- [GitHubOrganization](https://github.com/42Crunch)
- [IDESupport - VS Code](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi)
- [IDESupport - IntelliJ](https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor)

## Features

| Name | Description |
|------|-------------|
| API Security Audit | Automated static analysis of OpenAPI and GraphQL definitions running over 200 security checks, scoring APIs 0-100 for vulnerability and compliance issues. |
| API Scan (DAST) | Dynamic API Security Testing that evaluates runtime API behavior against its OpenAPI contract, identifying vulnerabilities that appear only at runtime. |
| API Firewall | API-native micro firewall that enforces OpenAPI contract compliance at runtime, blocking malformed requests, unauthorized access, and API attacks. |
| API Discovery | Identifies and catalogs APIs across environments to provide full visibility into the API attack surface. |
| CI/CD Integration | GitHub Actions and other CI/CD pipeline integrations for automated security scanning in deployment workflows. |
| IDE Integration | Plugins for VS Code and IntelliJ/JetBrains IDEs that provide real-time OpenAPI editing, validation, and security feedback during API design. |
| OpenAPI Contract Security | Enforces security best practices in OpenAPI specifications covering authentication, data validation, input/output schemas, and transport security. |
| Kubernetes Support | Scand Manager provides a Kubernetes wrapper for running 42Crunch API Scan in containerized environments. |

## Use Cases

| Name | Description |
|------|-------------|
| API Security Testing in CI/CD | Embed automated API security scanning into CI/CD pipelines via GitHub Actions to catch vulnerabilities before they reach production. |
| OpenAPI Specification Review | Audit OpenAPI definitions for security flaws, missing authentication, weak data validation, and schema gaps before API deployment. |
| Runtime API Protection | Deploy the API Firewall in front of production APIs to enforce contract compliance and block attacks in real time. |
| DevSecOps API Governance | Provide development, security, and operations teams with shared visibility into API security posture throughout the API lifecycle. |
| OWASP API Top 10 Compliance | Systematically identify and remediate OWASP API Security Top 10 vulnerabilities in API definitions and runtime behavior. |
| API Security for Financial Services | Address regulatory and compliance requirements for API security in banking, financial services, and insurance sectors. |
| Healthcare API Security | Secure healthcare APIs handling sensitive patient data against unauthorized access and data exposure vulnerabilities. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Native GitHub Actions for API Security Audit and API Scan, enabling automated security checks in GitHub CI/CD workflows. |
| VS Code | OpenAPI extension for Visual Studio Code providing real-time API editing, validation, and security feedback with 42Crunch integration. |
| IntelliJ / JetBrains | OpenAPI/Swagger Editor plugin for IntelliJ IDEA and other JetBrains IDEs. |
| Kubernetes | Scand Manager provides Kubernetes-native deployment of API Scan for containerized API security testing. |
| Tekton | Tekton Pipelines catalog integration for CI/CD security scanning tasks. |
| SonarQube | SonarQube plugin that integrates 42Crunch API security audit results into code quality dashboards. |
| API Gateways | API Firewall integrates with API gateway infrastructure to enforce contract compliance at the network edge. |
| SIEM / SOC Systems | Runtime protection events can be forwarded to SIEM and SOC platforms for centralized threat monitoring and alerting. |
| Atlassian | Data Center App Performance Toolkit support for Atlassian platform integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [42Crunch API Conformance Scan Jobs Manager](openapi/42crunch-scand-manager.yaml)

### JSON Schema

- [Job Name Schema](json-schema/scand-manager-job-name-schema.json)
- [Jobs Schema](json-schema/scand-manager-jobs-schema.json)
- [Job Spec Schema](json-schema/scand-manager-job-spec-schema.json)
- [Job Status Schema](json-schema/scand-manager-job-status-schema.json)
- [Error Schema](json-schema/scand-manager-error-schema.json)

### JSON Structure

- [Job Name Structure](json-structure/scand-manager-job-name-structure.json)
- [Jobs Structure](json-structure/scand-manager-jobs-structure.json)
- [Job Spec Structure](json-structure/scand-manager-job-spec-structure.json)
- [Job Status Structure](json-structure/scand-manager-job-status-structure.json)
- [Error Structure](json-structure/scand-manager-error-structure.json)

### JSON-LD

- [42Crunch Scand Manager Context](json-ld/42crunch-scand-manager-context.jsonld)

### Examples

- [Job Name Example](examples/scand-manager-job-name-example.json)
- [Jobs Example](examples/scand-manager-jobs-example.json)
- [Job Spec Example](examples/scand-manager-job-spec-example.json)
- [Job Status Example](examples/scand-manager-job-status-example.json)
- [Error Example](examples/scand-manager-error-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [42Crunch Scand Manager](capabilities/shared/scand-manager.yaml) — 6 operations for API conformance scan job management on Kubernetes

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Security Scanning](capabilities/api-security-scanning.yaml) | Scand Manager | 6 | DevSecOps Engineer, Security Team |

## Vocabulary

- [42Crunch Vocabulary](vocabulary/42crunch-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [42Crunch Spectral Rules](rules/42crunch-spectral-rules.yml) — 40+ rules across 13 categories enforcing 42Crunch API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
