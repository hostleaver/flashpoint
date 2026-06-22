# Quest submissions

Create one package per quest or closely related quest chain:

```text
submissions/<quest-slug>/
```

Copy [`../templates/PROPOSAL.md`](../templates/PROPOSAL.md) into the package as
`PROPOSAL.md`, then add the Expansion quest files using the layout in the
[repository README](../README.md#package-layout).

Use lowercase kebab-case for the directory name. Do not place loose JSON files
directly in this directory. Authorship is tracked by Git and may also be recorded in
the package's `PROPOSAL.md`.
