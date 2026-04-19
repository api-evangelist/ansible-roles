# Ansible Roles (ansible-roles)
A curated collection of APIs and resources for discovering, managing, and consuming Ansible roles — the primary unit of reusable automation content in the Ansible ecosystem. Covers the Galaxy and Automation Hub APIs for role discovery, download, and publishing, as well as the Ansible Collections framework.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Ansible, Automation, Collections, Configuration Management, DevOps, Infrastructure As Code, Roles

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Ansible Galaxy Roles API
The Ansible Galaxy v1 and v2 REST API enables searching, discovering, and downloading Ansible roles contributed by the community. Supports searching roles by keyword, author, or tag; retrieving role details and version history; and downloading specific role versions for use in playbooks.

**Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)

#### Tags:

 - Ansible, Community, Galaxy, Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [APIReference](https://galaxy.ansible.com/api/v1/)
- [GettingStarted](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

### Ansible Galaxy Collections API
The Ansible Galaxy v3 API provides enhanced support for Ansible collections — the modern packaging format that bundles roles, modules, plugins, and documentation together.

**Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)

#### Tags:

 - Ansible, Collections, Community, Galaxy

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [APIReference](https://galaxy.ansible.com/api/v3/)
- [GettingStarted](https://docs.ansible.com/ansible/latest/collections/index.html)

### Ansible Automation Hub Roles API
Red Hat Ansible Automation Hub provides certified and partner-validated Ansible collections and roles for enterprise use with SLA-backed quality assurance.

**Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)

#### Tags:

 - Ansible, Certified Content, Collections, Enterprise, Red Hat, Roles

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [APIReference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)

## Common Properties

- [GettingStarted](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)
- [Authentication](https://galaxy.ansible.com/docs/authentication/)
- [TermsOfService](https://www.redhat.com/en/about/terms-use)
- [PrivacyPolicy](https://www.redhat.com/en/about/privacy-policy)
- [GitHubRepository](https://github.com/ansible/galaxy)
- [GitHubOrganization](https://github.com/ansible)
- [JSONSchema — Role Schema](json-schema/ansible-roles-role-schema.json)
- [JSONSchema — Collection Schema](json-schema/ansible-roles-collection-schema.json)
- [Vocabulary](vocabulary/ansible-roles-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Role Search and Discovery | Search Galaxy for community-contributed roles by keyword, author, namespace, or tag to find reusable automation content. |
| Collection Packaging | Bundle roles, modules, plugins, and documentation into distributable collection packages versioned and published via the Galaxy API. |
| Version Management | Access specific versions of roles and collections, enabling pinned dependency management in Ansible projects. |
| Certified Content | Access Red Hat-certified and partner-validated Ansible collections with enterprise-grade quality assurance via Automation Hub. |
| Namespace Management | Manage author namespaces on Galaxy to publish and maintain role and collection content under a consistent identity. |

## Use Cases

| Name | Description |
|------|-------------|
| Role Reuse Across Projects | Discover and install community roles from Galaxy to avoid reinventing automation logic for common tasks. |
| Certified Enterprise Automation | Use Red Hat-certified collections from Automation Hub in production environments where quality assurance and support are required. |
| Private Content Distribution | Publish internal roles and collections to a private Automation Hub instance for controlled distribution. |
| Dependency Management | Pin role and collection versions in requirements.yml files and install them via the Galaxy API in CI/CD pipelines. |

## Integrations

| Name | Description |
|------|-------------|
| Ansible Playbooks | Use roles discovered via the Galaxy API directly in Ansible playbooks with the roles directive or include_role task. |
| Ansible Automation Platform | Synchronize collections from Galaxy or Automation Hub into Ansible Automation Platform for use in job templates. |
| Requirements Files | Define role and collection dependencies in requirements.yml and install them automatically via ansible-galaxy CLI using the API. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Role Schema](json-schema/ansible-roles-role-schema.json)
- [Collection Schema](json-schema/ansible-roles-collection-schema.json)

### JSON Structure

- [Role Structure](json-structure/ansible-roles-role-structure.json)
- [Collection Structure](json-structure/ansible-roles-collection-structure.json)

### JSON-LD

- [Ansible Roles Context](json-ld/ansible-roles-context.jsonld)

### Examples

- [Role Example](examples/ansible-roles-role-example.json)
- [Collection Example](examples/ansible-roles-collection-example.json)

## Vocabulary

- [Ansible Roles Vocabulary](vocabulary/ansible-roles-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, and 3 APIs across the Ansible roles and collections ecosystem

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
