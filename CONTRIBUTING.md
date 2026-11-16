# Contributing

This is a fork of
[dcaliste/sailfish-crypto-plugins](https://github.com/dcaliste/sailfish-crypto-plugins).
master follows upstream; changes to the RNP plugin are made on
sailfish/rnp-secrets. Describe a bug, proposed change or unresolved question in
this repository's issue tracker. Use public or synthetic examples. Project
artifacts are written in English.

For a change, open a pull request against sailfish/rnp-secrets explaining the
problem, the resulting behavior and the checks you ran. State failures and
checks you could not run. Keep each change small enough to review, one logical
change per commit, in the upstream commit style. Plugin changes are offered
upstream per topic; workflow files (CONTRIBUTING.md, LICENSING.md,
.github/) are not.

## AI assistance and responsibility

This project uses AI-assisted development tools. The maintainer is responsible for deciding what is merged and released.

Contributors must understand and review the changes they submit, whether written manually or with assistance. If AI materially contributed to a change, briefly state what it helped with and how the result was checked. Tool output and generated text are not evidence that a change is correct.

The maintainer reviews proposed changes before merge. Crypto behavior and release-critical changes also require verification separate from implementation. Reports must distinguish automated checks, assistant review and human review. An assistant reviewing its own work, or another assistant agreeing with it, is not a human audit. The maintainer decides whether the evidence is sufficient; unresolved findings stay open.

AI tools cannot approve their own changes, waive acceptance criteria or authorize installation or publication. Merge acceptance is separate from permission to change devices/systems, publish packages or send upstream contributions.

## Testing and licensing

Tests use keys generated at run time, synthetic data or published test vectors. Do not submit real keys, passphrases, password stores or recovery data in issues, PRs or test inputs.

Contributions are BSD-3-Clause, like the upstream code; see [LICENSING](LICENSING.md).

Shared working agreements are maintained in sailfish-workspace.
