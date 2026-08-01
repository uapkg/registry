# UAPKG Official Registry — Temporary Bootstrap

This private repository is temporary bootstrap state for the production UAPKG CLI.

It intentionally contains no package manifests. When production registry linking is available through the UAPKG website service, this repository will be reset and initialized through that workflow.

The metadata under `.uapkg/registry.meta.json` uses the canonical official registry and organization identities so clients can exercise the final trust contract without introducing disposable service identifiers.
