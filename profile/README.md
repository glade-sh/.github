<p align="center">
  <img src="logo-mark.svg" alt="Glade boxed contour mark" width="96" height="96">
</p>

<h1 align="center">Glade</h1>

<p align="center">
  Local Apex runtime and tooling for Salesforce teams.
</p>

<p align="center">
  <a href="https://glade.sh">Website</a>
  &middot;
  <a href="https://glade.sh/guide/quickstart">Quickstart</a>
  &middot;
  <a href="https://glade.sh/guide/support-map">What runs locally</a>
  &middot;
  <a href="https://github.com/glade-sh/glade/releases/latest">Releases</a>
</p>

Glade is a local Apex runtime and developer toolkit. Run supported tests,
inspect and debug code, and exercise local SOQL, DML, and triggers without
deploying to an org. Keep Salesforce for final validation and hosted behavior.

Glade reads your source and metadata from disk and executes supported behavior
in its own runtime. The CLI, editor tools, and local browser interfaces use
that runtime. It is not a hidden Salesforce org or only a static analyzer.

## Start Here

Follow the [canonical quickstart](https://glade.sh/guide/quickstart): install
Glade, establish a sample or existing Salesforce DX project, and run one named
test with a nonzero executed count. The guide identifies which sample version
to use, what success means, and how to recover from setup problems.

## Repositories

- [glade](https://github.com/glade-sh/glade): the runtime, CLI, editor tooling,
  product documentation, and releases. Start here.
- [glade-tools](https://github.com/glade-sh/glade-tools): optional first-party
  compatibility, performance, and package-contract plugins. Check its licensing
  status and tested product pairing before adoption; base Glade needs no plugin.

## What Glade Covers

- Apex parse, indexing, and semantic checks.
- Local Apex tests for supported VM paths.
- SOQL, DML, triggers, SObjects, and local storage.
- JSON, SARIF, JUnit, and saved run artifacts for CI.
- VS Code test, debug, and editor workflows.
- Local Salesforce-shaped API routes for supported development loops.

Salesforce remains the validation gate for live auth, hosted service engines,
deploy and retrieve, exact Lightning behavior, Streaming, Pub/Sub, GraphQL, and
production governor accounting.

## Give Feedback

[Report a bug or describe your workflow](https://github.com/glade-sh/glade/issues/new/choose).
Include version, OS, command, test names/count, and a minimal public reproduction.
Do not paste proprietary source, credentials, private package names, customer
records, or unredacted support bundles. Report vulnerabilities through the
[private security route](https://github.com/glade-sh/glade/security/advisories/new).
