# SynthStack Platform API

OpenAPI specification and release notes for the SynthStack platform API.

This repository does **not** contain the API source code. It is the public
record of the API contract: each release includes the specification as it
was at that version, along with a summary of changes.

## Specification

- `openapi.yaml` — the specification snapshot from the latest published release.
- Previous versions are available via Git tags and as assets attached
  to each GitHub Release.

You can use the spec to generate clients, validate requests, or import it
into tools such as Postman, Insomnia, or Swagger UI.

## Releases and versioning

Each API release is published as:

- a Git tag `vX.Y.Z`,
- a GitHub Release with release notes,
- a copy of `openapi.yaml` attached to the release.

Release notes are the primary place to look for what changed. Breaking
changes are called out explicitly in a dedicated section, together with
migration guidance where applicable.

Versions follow [Semantic Versioning](https://semver.org). Deprecated
endpoints are announced in release notes before removal.

## Related resources

- API documentation: [https://api.synthstack.ai/v1](https://api.synthstack.ai/v1)
- Support: [support@synthstack.ai](mailto:support@synthstack.ai)
- Terms of Service: [https://synthstack.ai/legal/terms](https://synthstack.ai/legal/terms)

## Feedback

Questions about the specification or release notes are welcome via
GitHub Issues in this repository. For account, billing, or security
matters, please use the support channels above instead.