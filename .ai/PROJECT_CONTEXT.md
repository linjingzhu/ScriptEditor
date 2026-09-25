---
doc_id: ai-project-context
version: 1.1.1
canonical_path: .ai/PROJECT_CONTEXT.md
updated: 2026-09-25
---

# ScriptEditor Context

## Facts the checks read

```text
repository_mode: protected
base_branch: main
merge_deploys: no
runtime_gate: none
test_command: python3 .ai/tools/check_policy_set.py
lint_command: none
build_command: none
generated: none
external_scripts: none
public_ids: none
owner_ledger: .ai/reports/OWNER_ACTIONS.md
```

## Authoritative product constraints

- The repository linjingzhu/ScriptEditor was empty before policy adoption.
- No application, product requirements, platform, or architecture is defined yet.
- Do not infer product scope from the repository name. Confirm product scope
  before starting application implementation.

## Current architecture

- This repository currently contains development policy and agent capabilities only.
- Local policy validation requires Python 3.11 or newer; no application runtime
  or build system is installed or claimed.
- No deployment configuration exists in this repository. Recheck hosting and
  update merge_deploys before any product/deployment work.

## Current development slice

- ai-dev-rule 3.0.0 adoption, with GitHub Actions disabled and no workflow files.
- Preserve this Actions state unless the user explicitly requests a change.

## Permanently excluded scope

- No permanent product exclusions have been established.
