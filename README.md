# UAPKG Official Registry

This repository contains the installable Git representation of the official
UAPKG registry. The UAPKG CLI uses this repository as its default production
registry.

Package metadata is generated from accepted state in the
[UAPKG publishing platform](https://github.com/uapkg/registry-infra).
The platform maintains `.uapkg/registry.meta.json` and the package records under
`packages/`; changes to those managed files should go through UAPKG's publishing
and registry administration workflows.

Registry identity and compatibility information are available in
[`.uapkg/registry.meta.json`](.uapkg/registry.meta.json).
Repository history is retained through initialization and subsequent projection.

See the [UAPKG project](https://github.com/uapkg/uapkg) for the CLI and package
format, and [UAPKG Account](https://account.uapkg.dev) for publishing and registry
administration.
