# AcornOps Charts Entry Point

This repository is a generated public Helm chart repository. It serves packaged
chart archives and the Helm `index.yaml` file for the classic `helm repo add`
install path.

## Agent-Assisted Development

When using a coding agent directly inside this repo, start from this repository
root and read this file before editing files.

For work that touches multiple AcornOps repositories, start the agent from the
AcornOps workspace root instead. The workspace root is cloned from the
`acornops` repository and contains the cross-repo manifest, shared skills,
validation helpers, and PR coordination workflow.

## Working Rules

- Keep chart source changes in the owning repositories.
- Keep this repository limited to static chart repository artifacts and minimal
  documentation.
- Do not hand-edit packaged chart archives.
- Regenerate `index.yaml` with Helm when chart packages change.
- Shared skills live in `.agents/skills/shared`; repository-owned skills live in
  `.agents/skills/local` if this repository ever needs local automation.

## Ownership

- Platform chart source: `acornops-deployment`
- Agent chart source: `agentk`
- Classic Helm repository mirror: `charts`
