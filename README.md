# Ansible Roles (ansible-roles)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A curated collection of APIs and resources for discovering, managing, and consuming Ansible roles — the primary unit of reusable automation content in the Ansible ecosystem. Covers the Galaxy and Automation Hub APIs for role discovery, download, and publishing, as well as the Ansible Collections framework that has extended the role model into full-featured content packages.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml)

## Tags

- Ansible
- Automation
- Collections
- Configuration Management
- DevOps
- Infrastructure As Code
- Roles

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Ansible Galaxy Roles API

The Ansible Galaxy v1 and v2 REST API enables searching, discovering, and downloading Ansible roles contributed by the community. Supports searching roles by keyword, author, or tag; retrieving role details and version history; and downloading specific role versions for use in playbooks.

- **Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)
- **Base URL:** `https://galaxy.ansible.com/api/v1/`

#### Tags

- Ansible
- Community
- Galaxy
- Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [API Reference](https://galaxy.ansible.com/api/v1/)
- [Getting Started](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)
- [Postman Collection](collections/ansible-roles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-roles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Galaxy Collections API

The Ansible Galaxy v3 API provides enhanced support for Ansible collections — the modern packaging format that bundles roles, modules, plugins, and documentation together. Supports listing, searching, downloading, and versioning of published collections from the community namespace on Galaxy.

- **Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)
- **Base URL:** `https://galaxy.ansible.com/api/v3/`

#### Tags

- Ansible
- Collections
- Community
- Galaxy

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [API Reference](https://galaxy.ansible.com/api/v3/)
- [Getting Started](https://docs.ansible.com/ansible/latest/collections/index.html)
- [Postman Collection](collections/ansible-roles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-roles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Automation Hub Roles API

The Red Hat Ansible Automation Hub provides certified and partner-validated Ansible collections and roles for enterprise use. The API enables access to Red Hat-certified content with SLA-backed quality, partner-certified content, and community content synced from Galaxy in supported namespaces.

- **Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)
- **Base URL:** `https://console.redhat.com/api/automation-hub/v3/`

#### Tags

- Ansible
- Certified Content
- Collections
- Enterprise
- Red Hat
- Roles

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [API Reference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)
- [Postman Collection](collections/ansible-roles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-roles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)
- [Authentication](https://galaxy.ansible.com/docs/authentication/)
- [Terms of Service](https://www.redhat.com/en/about/terms-use)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [GitHub Repository](https://github.com/ansible/galaxy)
- [GitHub Organization](https://github.com/ansible)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-role-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/vocabulary/ansible-roles-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
