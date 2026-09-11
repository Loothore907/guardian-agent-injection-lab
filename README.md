# Guardian injection lab

Public, synthetic prompt-injection evaluation fixtures for Agentic Guardian. Instructions in fixtures are untrusted test content, not directions to repository maintainers or tools. No credentials or real business data belong here.

`manifest.json` pins each published HTML artifact. `sites/` contains static, non-executable pages for the two approved fixture subdomains. Legitimate merge demonstrations use the separate `Loothore907/guardian-agent-demo` repository.

`fixtures/v2/` adds a matched release pair with the same neutral supporting context in both pages. The injection paragraph is their only content difference. This separately versioned pair addresses unreliable Basic extraction of the short v1 control at its raw GitHub URL. Its manifest pins file bytes; consume commit-pinned raw URLs and verify live extraction before evaluating model behavior. Publication here does not deploy the custom fixture domains or supersede historical v1 evidence. Tracking: [Guardian issue #19](https://github.com/Loothore907/guardian-agent/issues/19).
