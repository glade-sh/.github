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

Glade is a clean-room Apex runtime for local development and testing. It reads
Salesforce projects from disk, checks Apex, runs supported tests without an org,
and exposes the same runtime through a CLI, editor tools, a playground, and a
Salesforce-shaped local API server.

## Start Here

```bash
curl -fsSL https://glade.sh/install.sh | sh
glade doctor
glade check --project .
```

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
