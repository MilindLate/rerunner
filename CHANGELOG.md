# Changelog

## [0.3.5](https://github.com/MilindLate/rerunner/compare/v0.3.4...v0.3.5) (2026-11-18)


### Features

* add automated PII/secret sanitizer, Anthropic/OpenAI/LangChain adapters, and CLI replay animation ([27986dc](https://github.com/MilindLate/rerunner/commit/27986dc82cfd0938eee8801c564099d4dee9d6aa))
* add cassette security pre-commit hook ([#46](https://github.com/MilindLate/rerunner/issues/46)) ([#65](https://github.com/MilindLate/rerunner/issues/65)) ([367fd9a](https://github.com/MilindLate/rerunner/commit/367fd9a92a22c9f0db1966a257294309628ba120))
* add Google GenAI wrapper, OpenTelemetry exporter, and enterprise RFC process ([6460500](https://github.com/MilindLate/rerunner/commit/6460500f8a1ad0d1db15ce2005e172b96a3abab7))
* Add Groq SDK integration with sync and async replay ([#135](https://github.com/MilindLate/rerunner/issues/135)) ([0c7b4c5](https://github.com/MilindLate/rerunner/commit/0c7b4c5e1c7c5bbf6c79d73211143aff88b7448e))
* add LlamaIndex integration, enhanced verify CLI, and ASCII demo (resolves [#3](https://github.com/MilindLate/rerunner/issues/3)) ([a4c6634](https://github.com/MilindLate/rerunner/commit/a4c6634b1f0af5207e359b3333b49ad40296fd23))
* add LlamaIndex integration, enhanced verify CLI, and ASCII demo (resolves [#3](https://github.com/MilindLate/rerunner/issues/3)) ([efab6a6](https://github.com/MilindLate/rerunner/commit/efab6a61784487eb08dfd1d545fb6074876c2ccf))
* **cli:** add --verify-all strict integrity check to rerunner merge ([#127](https://github.com/MilindLate/rerunner/issues/127)) ([b02f31b](https://github.com/MilindLate/rerunner/commit/b02f31b047cd56538dd74f270c4fe10ccd4c765e))
* **cli:** add '--json' output flag to 'rerunner stats' (closes [#43](https://github.com/MilindLate/rerunner/issues/43)) ([#50](https://github.com/MilindLate/rerunner/issues/50)) ([be0b8bc](https://github.com/MilindLate/rerunner/commit/be0b8bc206b38f2e187c9f6f9b9b579cb8f323fa))
* **cli:** add doctor diagnostic and scrub secret redactor commands ([3193111](https://github.com/MilindLate/rerunner/commit/319311129bc620848a28e0a7fb9dffbc89cfaa2a))
* **cli:** add export-eval command for fine-tuning and benchmark datasets ([2af0997](https://github.com/MilindLate/rerunner/commit/2af0997c96053c484208e8e72c76fbcf41a4c2d4))
* **cli:** add interactive terminal flight deck and bump to v0.3.1 (resolves [#36](https://github.com/MilindLate/rerunner/issues/36)) ([1514e53](https://github.com/MilindLate/rerunner/commit/1514e5357de66451b3e238e8c30170eb84f6a4af))
* **cli:** add summary-only cassette audits to doctor ([#48](https://github.com/MilindLate/rerunner/issues/48)) ([#130](https://github.com/MilindLate/rerunner/issues/130)) ([a4f75b3](https://github.com/MilindLate/rerunner/commit/a4f75b35e413c6c65041d8ec254eb21fdf731841))
* **config:** load default options from [tool.rerunner] in pyproject.toml ([#126](https://github.com/MilindLate/rerunner/issues/126)) ([7906641](https://github.com/MilindLate/rerunner/commit/7906641cb47bfa3d2df5f5e445409e5c342746e9))
* **cost:** support Anthropic prompt-caching token discounts in model pricing (closes [#107](https://github.com/MilindLate/rerunner/issues/107)) ([#128](https://github.com/MilindLate/rerunner/issues/128)) ([c17727f](https://github.com/MilindLate/rerunner/commit/c17727f173f784cd7f0e1f8275990ac8853d618f))
* **enterprise:** add Azure Blob Storage backend and AWS Bedrock adapter ([7712f1f](https://github.com/MilindLate/rerunner/commit/7712f1f9c98cf1d80e7b2ad898a00155c0c36d27))
* **enterprise:** add devcontainer, governance spec, benchmarks, and cli version tests ([#29](https://github.com/MilindLate/rerunner/issues/29)) ([e3e2dfd](https://github.com/MilindLate/rerunner/commit/e3e2dfd077b569e6c5b3b9c671bdc67bf80f52cb))
* **enterprise:** add model pricing, ignore-fields, cassette merge, auto-naming, and nightly mutmut ([#93](https://github.com/MilindLate/rerunner/issues/93)) ([5b40039](https://github.com/MilindLate/rerunner/commit/5b40039889c0c67554bf20412e05672394113cdd))
* implement session api, tee streaming, concurrency hardening, and diff cli ([0855c39](https://github.com/MilindLate/rerunner/commit/0855c39728df549a5319f677ad6dcea9bf1c2bb1))
* initial release of rerunner deterministic flight recorder ([41f3229](https://github.com/MilindLate/rerunner/commit/41f3229458d2b589e37f61b8c0933f65856b7bc3))
* **integrations:** add 1-line wrap_together_client wrapper ([#124](https://github.com/MilindLate/rerunner/issues/124)) ([12e2bb0](https://github.com/MilindLate/rerunner/commit/12e2bb062e8695c8df610e012a55faa6d2daafd0))
* **integrations:** add BaseProviderAdapter protocol and unified rerunner.wrap API ([f4c90cf](https://github.com/MilindLate/rerunner/commit/f4c90cf3fda92bfe70ed9b8c0dc0741a8ccad4d0))
* **integrations:** add DeepSeek client wrapper ([#121](https://github.com/MilindLate/rerunner/issues/121)) ([6fc5649](https://github.com/MilindLate/rerunner/commit/6fc5649701d9c21b59c39a0ac7d57a73e3c9b490))
* **integrations:** add LangGraph multi-agent checkpointer, justfile, and contributor scaffolding ([a9802ca](https://github.com/MilindLate/rerunner/commit/a9802caab8551d81648545d24400631e6dbb16bf))
* **integrations:** add wrap_cohere for the Cohere SDK (closes [#59](https://github.com/MilindLate/rerunner/issues/59)) ([#68](https://github.com/MilindLate/rerunner/issues/68)) ([32ecb11](https://github.com/MilindLate/rerunner/commit/32ecb11fa8998ed82951d2604ec6030fb8cc941f))
* **matcher:** add semantic drift tolerant replay matching via embeddings and cosine similarity (resolves [#35](https://github.com/MilindLate/rerunner/issues/35)) ([0cba454](https://github.com/MilindLate/rerunner/commit/0cba454a763dd1afe0347413ec512ad139bfa698))
* **mcp:** add stdio MCP server, setup wizard, and agent plugins ([#91](https://github.com/MilindLate/rerunner/issues/91)) ([6a2e9c2](https://github.com/MilindLate/rerunner/commit/6a2e9c2164f26a259880e34320d8bd0e584db79d))
* **moat:** add requests/aiohttp patchers, Pseudonymizer, Ed25519+Merkle signing, and cached remote storage ([#95](https://github.com/MilindLate/rerunner/issues/95)) ([ea64efa](https://github.com/MilindLate/rerunner/commit/ea64efa69716bef7ccd3e57fab8a699d338dd2b2))
* **presidio:** add presidio optional dependency and v0.3.0 release notes ([b507ec2](https://github.com/MilindLate/rerunner/commit/b507ec2927c989dd437cf32ed6314974619f0a4a))
* **proxy:** add configurable CORS headers to rerunner serve ([#123](https://github.com/MilindLate/rerunner/issues/123)) ([be4601d](https://github.com/MilindLate/rerunner/commit/be4601d03c112ae5ce9a5a9a861827133a7361bd))
* **proxy:** add rerunner serve proxy, trace viewer, sticky PR bot, and conformance tests ([#92](https://github.com/MilindLate/rerunner/issues/92)) ([056b8ef](https://github.com/MilindLate/rerunner/commit/056b8ef344d5579fd8943d81d7402d6ecc077ff4))
* **pytest:** automatic pytest-xdist worker cassette shard merge hook (closes [#108](https://github.com/MilindLate/rerunner/issues/108)) ([#129](https://github.com/MilindLate/rerunner/issues/129)) ([507a73f](https://github.com/MilindLate/rerunner/commit/507a73f3ad086e8582a2062a6aac1c11eaddbebc))
* **reports:** add standalone HTML cost & token savings report generator (closes [#44](https://github.com/MilindLate/rerunner/issues/44)) ([aff8663](https://github.com/MilindLate/rerunner/commit/aff86632e16075b90ed3a47a54aaa7b1f37dee27))
* **sanitizer:** add optional Sether PII redaction backend ([ee90675](https://github.com/MilindLate/rerunner/commit/ee906759bf1dc5f1eed2513904378d2e2a202b28))
* **sanitizer:** add optional Sether PII redaction backend ([36b710e](https://github.com/MilindLate/rerunner/commit/36b710eec46748b7f92ab26600bec31cd0b2132c))
* **sanitizer:** support custom regex patterns via RERUNNER_REDACT_PATTERNS (closes [#49](https://github.com/MilindLate/rerunner/issues/49)) ([#51](https://github.com/MilindLate/rerunner/issues/51)) ([30a2b6a](https://github.com/MilindLate/rerunner/commit/30a2b6a5bfe86b81601c35a188fd8f31dcb6ff51))
* **security:** complete SAST & dependency audit, add security workflow, and harden storage write_bytes ([1a3f63a](https://github.com/MilindLate/rerunner/commit/1a3f63a52381edbf218f3dd945428ec1b7f1665f))
* **setup:** add Windsurf and Cline MCP targets to rerunner setup ([#125](https://github.com/MilindLate/rerunner/issues/125)) ([d846d1d](https://github.com/MilindLate/rerunner/commit/d846d1d4343034e370a89f41338b8f24d79086ac))
* **storage:** support zstandard (.zst) compression and add structured outputs cookbook ([#28](https://github.com/MilindLate/rerunner/issues/28)) ([d30271f](https://github.com/MilindLate/rerunner/commit/d30271fe0c2a01c59d970435c9c52842d4c323d7))
* **streaming:** add Server-Sent Events (SSE) streaming replay support ([#14](https://github.com/MilindLate/rerunner/issues/14)) ([a3d31df](https://github.com/MilindLate/rerunner/commit/a3d31df1d54eb1cf40a33127ea7d48502c0f99e4))
* **v0.2.1:** implement remote storage backend, PII sanitization filters, and OTel metrics ([66f3e40](https://github.com/MilindLate/rerunner/commit/66f3e4013bb2bdfd894f6ddf5e7b011340c8a186))
* **v0.3.0:** add MCP protocol replay, official GitHub Action, AutoGen/SK adapters, and CI cost reporting ([a4ba3ff](https://github.com/MilindLate/rerunner/commit/a4ba3ff127f0608e14bd42b7d7fd2e499dd630ea))


### Bug Fixes

* address repo review feedback, harden sanitizer, and enforce fail-closed side-effects ([2e982a5](https://github.com/MilindLate/rerunner/commit/2e982a5313c594a82a69ee3b1611070351b2e115))
* **ci:** add tests/__init__.py, configure pythonpath, and optimize ruff/mypy rules ([236f961](https://github.com/MilindLate/rerunner/commit/236f961bd0b0b22b181d48b27fec63afd143c653))
* **ci:** correct model imports in tests and align metadata attributes in otel exporter ([4e89f2c](https://github.com/MilindLate/rerunner/commit/4e89f2ce00f3c20c2bc5ecff9fb90ee1e3d6fdf9))
* **ci:** resolve F401 unused import in tests and fix cli subcommand help assertion ([e575a7f](https://github.com/MilindLate/rerunner/commit/e575a7f3693b425771d8f7770a97a58204f9ff38))
* **ci:** upgrade setuptools to &gt;=83.0.0 in security workflow to address runner CVE PYSEC-2026-3447 ([2a7ed7e](https://github.com/MilindLate/rerunner/commit/2a7ed7efa4183a3713398361f6adfdff6917e00c))
* **cli:** synchronize Cassette path and URI during scrub and register asyncio marker ([088d204](https://github.com/MilindLate/rerunner/commit/088d20443354e52dc90fc130df85c4e6222db7ba))
* **core:** complete hardening audit across auto_patch, streaming, tools, and integrations ([43c40e6](https://github.com/MilindLate/rerunner/commit/43c40e640ed2c78c5b1f9d384f415ebf2996a31c))
* decouple __version__ to eliminate circular import cycle and configure cSpell dictionary ([767d2ef](https://github.com/MilindLate/rerunner/commit/767d2eff6cbb8349803733bde29e21d0fb4ed3df))
* **lint:** modernize typing collections imports and ignore unused var in tests ([656e89c](https://github.com/MilindLate/rerunner/commit/656e89c23755b3bb17330be09bb28e98958d665e))
* **lint:** resolve B007, B010, and ignore B008 for Typer CLI ([97a9a1c](https://github.com/MilindLate/rerunner/commit/97a9a1c6adb6427053801cb6ab2aa4fcf521e138))
* **lint:** simplify nested if in cassette and remove unused CassetteError import ([b8b9cf8](https://github.com/MilindLate/rerunner/commit/b8b9cf8bd5448eb754dd21c76c8bd71f2ae51e84))
* **lint:** tune ruff rules and mypy third-party stubs ([dd042cf](https://github.com/MilindLate/rerunner/commit/dd042cffb7156c45abfd2b4837d4efffa4aebe16))
* resolve core URI/CLI/plugin bugs and harden CI architecture boundaries ([#90](https://github.com/MilindLate/rerunner/issues/90)) ([77b87d0](https://github.com/MilindLate/rerunner/commit/77b87d0a2a2d86d66870a481b6dfc8255caed363))
* **sanitizer:** ensure Presidio operator placeholders match canonical redaction and fallback rules ([aa071e8](https://github.com/MilindLate/rerunner/commit/aa071e879d49bc85a21bc7f3bbc20a9c55f68013))
* **sanitizer:** keep records whose keys sanitize to the same placeholder ([31ccfda](https://github.com/MilindLate/rerunner/commit/31ccfda0f45f0ace77db996ad9a88b8c3eea9b98))
* **sanitizer:** redact split stream values and preserve colliding keys ([7aefa2e](https://github.com/MilindLate/rerunner/commit/7aefa2e363139509b44eef20596cd6050f2d11af))
* **sanitizer:** redact values split across streamed chunks ([27b1ecf](https://github.com/MilindLate/rerunner/commit/27b1ecfb94ed71fbe29c6229b5e412a89287794a))
* **security:** annotate intentional exception handling for bandit SAST scan ([c4933dc](https://github.com/MilindLate/rerunner/commit/c4933dcceb7316c75d322c9e0f9afe4438da9ad0))
* **security:** annotate intentional exception handling for bandit SAST scan ([33ebcf8](https://github.com/MilindLate/rerunner/commit/33ebcf8d7be2481057823e7c5bf906c768d48f34))
* **security:** split dummy secret fixtures to prevent GitHub secret scanning false-positive alerts ([d4a5d15](https://github.com/MilindLate/rerunner/commit/d4a5d155158b4a07025005ba72b2c97bc3e87609))
* **security:** use parsed URL hostname checks in otel provider detection ([#97](https://github.com/MilindLate/rerunner/issues/97)) ([dd2dd67](https://github.com/MilindLate/rerunner/commit/dd2dd67ba1ca62854b80c4c5729b61fd2632b7ad))
* **types:** ignore misc on optional BaseCallbackHandler subclass in llamaindex integration ([661a24d](https://github.com/MilindLate/rerunner/commit/661a24d2537d55baddf4ae9de3230528306e7f46))
* **types:** resolve strict mypy issues and bandit SAST warnings ([0f3cba9](https://github.com/MilindLate/rerunner/commit/0f3cba9f043eaba4d9a78a40fb01d6b92e1d46f8))
* **types:** type annotate mode in pytest_plugin and clean mypy configuration ([f044c61](https://github.com/MilindLate/rerunner/commit/f044c61b52a0bf0690efe5cc84c163bdec17a7d6))


### Performance Improvements

* **sanitizer:** bound the rescan when settling streamed chunks ([2afa2a4](https://github.com/MilindLate/rerunner/commit/2afa2a4ddee333926da188db5ffea10b67bb71b0))
* **sanitizer:** confirm settle points that end in a redacted value ([f1800c8](https://github.com/MilindLate/rerunner/commit/f1800c8efccd0cc36b791dc481ae8a04eaec6297))


### Documentation

* add 5-minute offline testing and replay tutorial (resolves [#21](https://github.com/MilindLate/rerunner/issues/21)) ([67a823e](https://github.com/MilindLate/rerunner/commit/67a823ed2950c29ae9e1d94336739f69d247e288))
* add comprehensive 5-minute tutorial for Pytest offline replay (resolves [#21](https://github.com/MilindLate/rerunner/issues/21)) ([13b0b23](https://github.com/MilindLate/rerunner/commit/13b0b2342e2febda873516b8fbf7154d78d8969d))
* add GitHub Actions cassette caching recipe ([#5](https://github.com/MilindLate/rerunner/issues/5)) ([d5d816b](https://github.com/MilindLate/rerunner/commit/d5d816b65c713d7aecdb4f6599a8b2fa142f28f4))
* add latency & cost benchmarks and runnable examples gallery ([075b46e](https://github.com/MilindLate/rerunner/commit/075b46e62cc504d8d882d9bb5a6ce1781de1db7e))
* **authors:** recognize community contributor [@emorilebo](https://github.com/emorilebo) for Sether PII backend (PR [#37](https://github.com/MilindLate/rerunner/issues/37)) ([65c3bb7](https://github.com/MilindLate/rerunner/commit/65c3bb7456fe784d336c11e72476eefdc4ff0a13))
* **authors:** recognize community contributors @KeuqS and [@abhandary14](https://github.com/abhandary14) ([a8a96f8](https://github.com/MilindLate/rerunner/commit/a8a96f826f05f72fe3441ce6aaa584afc4cfc071))
* **authors:** recognize community contributors @KeuqS and [@abhandary14](https://github.com/abhandary14) ([f01acd6](https://github.com/MilindLate/rerunner/commit/f01acd601294428a5fd16b97bb5262b6e04e0e1d))
* clean up repository links and issue trackers in contributing and roadmap ([c03ab51](https://github.com/MilindLate/rerunner/commit/c03ab5169a208e5a3dfbbd9c652bb348cace0f67))
* **community:** add first-time contributor onboarding, authors hall-of-fame, and makefile ([46af85f](https://github.com/MilindLate/rerunner/commit/46af85f3dda8e939cfc9ac96bcdac14fe7d417cb))
* **contributing:** link AUTHORS.md in recognition section ([941ec19](https://github.com/MilindLate/rerunner/commit/941ec19588a055185c0b44aa7188fde833bcb4f3))
* **contributing:** link AUTHORS.md in recognition section ([6946188](https://github.com/MilindLate/rerunner/commit/6946188a19e1a4667e199bd8698b5ad477010d26))
* **examples:** add CrewAI multi-agent integration example and tutorial ([#42](https://github.com/MilindLate/rerunner/issues/42)) ([#58](https://github.com/MilindLate/rerunner/issues/58)) ([78d43a4](https://github.com/MilindLate/rerunner/commit/78d43a420aac6e73271db698ab36e1ae3cff2404))
* finalize CONTRIBUTING.md with community, recognition, and licensing ([3bab843](https://github.com/MilindLate/rerunner/commit/3bab8439d0283d33848c9796355e5bf0e378e5e2))
* **launch:** add MkDocs Material site, benchmark SVGs, localized READMEs, release-please, and CodeQL ([#94](https://github.com/MilindLate/rerunner/issues/94)) ([3119ba0](https://github.com/MilindLate/rerunner/commit/3119ba016a184f3b670b23c53d74aaf8ae8b1482))
* **readme:** acknowledge community contributions ([0506340](https://github.com/MilindLate/rerunner/commit/05063400a6aefd65c7ea7f84351e369f997f1ffb))
* **readme:** acknowledge community contributions ([c7b2668](https://github.com/MilindLate/rerunner/commit/c7b2668e6dad517f820e418d9fcc10ac9375304b))
* **readme:** highlight interactive TUI flight deck, Azure Blob and AWS Bedrock ([b9a4a54](https://github.com/MilindLate/rerunner/commit/b9a4a54f384ead90ba76d38b0f6281f5edb29d9e))
* **readme:** update release badge, CLI reference, and pre-commit tag for v0.3.2 ([#119](https://github.com/MilindLate/rerunner/issues/119)) ([669f73d](https://github.com/MilindLate/rerunner/commit/669f73db337e42f5bd929f14726a26987adafdc2))
* **rfcs:** establish Enterprise RFC framework with RFC-0001 and RFC-0002 ([168668a](https://github.com/MilindLate/rerunner/commit/168668a9abe981cc21c1b3fc83171de80561a1d2))
* **roadmap:** mark gzip cassettes and CI caching recipe completed in v0.1.1 ([6ce236c](https://github.com/MilindLate/rerunner/commit/6ce236c278788095b21aa3afc956e75a7887c7eb))
* update README with v0.1.2 badges, RFC directory, and roadmap links ([2f4bc36](https://github.com/MilindLate/rerunner/commit/2f4bc36992b6eba7472cb4b601a2798faf5299de))

## [0.3.4](https://github.com/aakash1552005/rerunner/compare/v0.3.3...v0.3.4) (2026-11-16)


### Features

* Add Groq SDK integration with sync and async replay ([#135](https://github.com/aakash1552005/rerunner/issues/135)) ([0c7b4c5](https://github.com/aakash1552005/rerunner/commit/0c7b4c5e1c7c5bbf6c79d73211143aff88b7448e))

## [0.3.3](https://github.com/aakash1552005/rerunner/compare/v0.3.2...v0.3.3) (2026-11-15)


### Features

* **cli:** add --verify-all strict integrity check to rerunner merge ([#127](https://github.com/aakash1552005/rerunner/issues/127)) ([b02f31b](https://github.com/aakash1552005/rerunner/commit/b02f31b047cd56538dd74f270c4fe10ccd4c765e))
* **cli:** add summary-only cassette audits to doctor ([#48](https://github.com/aakash1552005/rerunner/issues/48)) ([#130](https://github.com/aakash1552005/rerunner/issues/130)) ([a4f75b3](https://github.com/aakash1552005/rerunner/commit/a4f75b35e413c6c65041d8ec254eb21fdf731841))
* **config:** load default options from [tool.rerunner] in pyproject.toml ([#126](https://github.com/aakash1552005/rerunner/issues/126)) ([7906641](https://github.com/aakash1552005/rerunner/commit/7906641cb47bfa3d2df5f5e445409e5c342746e9))
* **cost:** support Anthropic prompt-caching token discounts in model pricing (closes [#107](https://github.com/aakash1552005/rerunner/issues/107)) ([#128](https://github.com/aakash1552005/rerunner/issues/128)) ([c17727f](https://github.com/aakash1552005/rerunner/commit/c17727f173f784cd7f0e1f8275990ac8853d618f))
* **integrations:** add 1-line wrap_together_client wrapper ([#124](https://github.com/aakash1552005/rerunner/issues/124)) ([12e2bb0](https://github.com/aakash1552005/rerunner/commit/12e2bb062e8695c8df610e012a55faa6d2daafd0))
* **integrations:** add DeepSeek client wrapper ([#121](https://github.com/aakash1552005/rerunner/issues/121)) ([6fc5649](https://github.com/aakash1552005/rerunner/commit/6fc5649701d9c21b59c39a0ac7d57a73e3c9b490))
* **proxy:** add configurable CORS headers to rerunner serve ([#123](https://github.com/aakash1552005/rerunner/issues/123)) ([be4601d](https://github.com/aakash1552005/rerunner/commit/be4601d03c112ae5ce9a5a9a861827133a7361bd))
* **pytest:** automatic pytest-xdist worker cassette shard merge hook (closes [#108](https://github.com/aakash1552005/rerunner/issues/108)) ([#129](https://github.com/aakash1552005/rerunner/issues/129)) ([507a73f](https://github.com/aakash1552005/rerunner/commit/507a73f3ad086e8582a2062a6aac1c11eaddbebc))
* **setup:** add Windsurf and Cline MCP targets to rerunner setup ([#125](https://github.com/aakash1552005/rerunner/issues/125)) ([d846d1d](https://github.com/aakash1552005/rerunner/commit/d846d1d4343034e370a89f41338b8f24d79086ac))


### Documentation

* **readme:** update release badge, CLI reference, and pre-commit tag for v0.3.2 ([#119](https://github.com/aakash1552005/rerunner/issues/119)) ([669f73d](https://github.com/aakash1552005/rerunner/commit/669f73db337e42f5bd929f14726a26987adafdc2))

## [0.3.2](https://github.com/aakash1552005/rerunner/compare/v0.3.1...v0.3.2) (2026-11-12)


### Features

* add cassette security pre-commit hook ([#46](https://github.com/aakash1552005/rerunner/issues/46)) ([#65](https://github.com/aakash1552005/rerunner/issues/65)) ([367fd9a](https://github.com/aakash1552005/rerunner/commit/367fd9a92a22c9f0db1966a257294309628ba120))
* **cli:** add '--json' output flag to 'rerunner stats' (closes [#43](https://github.com/aakash1552005/rerunner/issues/43)) ([#50](https://github.com/aakash1552005/rerunner/issues/50)) ([be0b8bc](https://github.com/aakash1552005/rerunner/commit/be0b8bc206b38f2e187c9f6f9b9b579cb8f323fa))
* **cli:** add export-eval command for fine-tuning and benchmark datasets ([2af0997](https://github.com/aakash1552005/rerunner/commit/2af0997c96053c484208e8e72c76fbcf41a4c2d4))
* **enterprise:** add model pricing, ignore-fields, cassette merge, auto-naming, and nightly mutmut ([#93](https://github.com/aakash1552005/rerunner/issues/93)) ([5b40039](https://github.com/aakash1552005/rerunner/commit/5b40039889c0c67554bf20412e05672394113cdd))
* **integrations:** add BaseProviderAdapter protocol and unified rerunner.wrap API ([f4c90cf](https://github.com/aakash1552005/rerunner/commit/f4c90cf3fda92bfe70ed9b8c0dc0741a8ccad4d0))
* **integrations:** add LangGraph multi-agent checkpointer, justfile, and contributor scaffolding ([a9802ca](https://github.com/aakash1552005/rerunner/commit/a9802caab8551d81648545d24400631e6dbb16bf))
* **integrations:** add wrap_cohere for the Cohere SDK (closes [#59](https://github.com/aakash1552005/rerunner/issues/59)) ([#68](https://github.com/aakash1552005/rerunner/issues/68)) ([32ecb11](https://github.com/aakash1552005/rerunner/commit/32ecb11fa8998ed82951d2604ec6030fb8cc941f))
* **matcher:** add semantic drift tolerant replay matching via embeddings and cosine similarity (resolves [#35](https://github.com/aakash1552005/rerunner/issues/35)) ([0cba454](https://github.com/aakash1552005/rerunner/commit/0cba454a763dd1afe0347413ec512ad139bfa698))
* **mcp:** add stdio MCP server, setup wizard, and agent plugins ([#91](https://github.com/aakash1552005/rerunner/issues/91)) ([6a2e9c2](https://github.com/aakash1552005/rerunner/commit/6a2e9c2164f26a259880e34320d8bd0e584db79d))
* **moat:** add requests/aiohttp patchers, Pseudonymizer, Ed25519+Merkle signing, and cached remote storage ([#95](https://github.com/aakash1552005/rerunner/issues/95)) ([ea64efa](https://github.com/aakash1552005/rerunner/commit/ea64efa69716bef7ccd3e57fab8a699d338dd2b2))
* **proxy:** add rerunner serve proxy, trace viewer, sticky PR bot, and conformance tests ([#92](https://github.com/aakash1552005/rerunner/issues/92)) ([056b8ef](https://github.com/aakash1552005/rerunner/commit/056b8ef344d5579fd8943d81d7402d6ecc077ff4))
* **reports:** add standalone HTML cost & token savings report generator (closes [#44](https://github.com/aakash1552005/rerunner/issues/44)) ([aff8663](https://github.com/aakash1552005/rerunner/commit/aff86632e16075b90ed3a47a54aaa7b1f37dee27))
* **sanitizer:** add optional Sether PII redaction backend ([ee90675](https://github.com/aakash1552005/rerunner/commit/ee906759bf1dc5f1eed2513904378d2e2a202b28))
* **sanitizer:** support custom regex patterns via RERUNNER_REDACT_PATTERNS (closes [#49](https://github.com/aakash1552005/rerunner/issues/49)) ([#51](https://github.com/aakash1552005/rerunner/issues/51)) ([30a2b6a](https://github.com/aakash1552005/rerunner/commit/30a2b6a5bfe86b81601c35a188fd8f31dcb6ff51))


### Bug Fixes

* resolve core URI/CLI/plugin bugs and harden CI architecture boundaries ([#90](https://github.com/aakash1552005/rerunner/issues/90)) ([77b87d0](https://github.com/aakash1552005/rerunner/commit/77b87d0a2a2d86d66870a481b6dfc8255caed363))
* **sanitizer:** ensure Presidio operator placeholders match canonical redaction and fallback rules ([aa071e8](https://github.com/aakash1552005/rerunner/commit/aa071e879d49bc85a21bc7f3bbc20a9c55f68013))
* **sanitizer:** keep records whose keys sanitize to the same placeholder ([31ccfda](https://github.com/aakash1552005/rerunner/commit/31ccfda0f45f0ace77db996ad9a88b8c3eea9b98))
* **sanitizer:** redact split stream values and preserve colliding keys ([7aefa2e](https://github.com/aakash1552005/rerunner/commit/7aefa2e363139509b44eef20596cd6050f2d11af))
* **sanitizer:** redact values split across streamed chunks ([27b1ecf](https://github.com/aakash1552005/rerunner/commit/27b1ecfb94ed71fbe29c6229b5e412a89287794a))
* **security:** use parsed URL hostname checks in otel provider detection ([#97](https://github.com/aakash1552005/rerunner/issues/97)) ([dd2dd67](https://github.com/aakash1552005/rerunner/commit/dd2dd67ba1ca62854b80c4c5729b61fd2632b7ad))
* **types:** resolve strict mypy issues and bandit SAST warnings ([0f3cba9](https://github.com/aakash1552005/rerunner/commit/0f3cba9f043eaba4d9a78a40fb01d6b92e1d46f8))


### Performance Improvements

* **sanitizer:** bound the rescan when settling streamed chunks ([2afa2a4](https://github.com/aakash1552005/rerunner/commit/2afa2a4ddee333926da188db5ffea10b67bb71b0))
* **sanitizer:** confirm settle points that end in a redacted value ([f1800c8](https://github.com/aakash1552005/rerunner/commit/f1800c8efccd0cc36b791dc481ae8a04eaec6297))


### Documentation

* add latency & cost benchmarks and runnable examples gallery ([075b46e](https://github.com/aakash1552005/rerunner/commit/075b46e62cc504d8d882d9bb5a6ce1781de1db7e))
* **authors:** recognize community contributor [@emorilebo](https://github.com/emorilebo) for Sether PII backend (PR [#37](https://github.com/aakash1552005/rerunner/issues/37)) ([65c3bb7](https://github.com/aakash1552005/rerunner/commit/65c3bb7456fe784d336c11e72476eefdc4ff0a13))
* **examples:** add CrewAI multi-agent integration example and tutorial ([#42](https://github.com/aakash1552005/rerunner/issues/42)) ([#58](https://github.com/aakash1552005/rerunner/issues/58)) ([78d43a4](https://github.com/aakash1552005/rerunner/commit/78d43a420aac6e73271db698ab36e1ae3cff2404))
* **launch:** add MkDocs Material site, benchmark SVGs, localized READMEs, release-please, and CodeQL ([#94](https://github.com/aakash1552005/rerunner/issues/94)) ([3119ba0](https://github.com/aakash1552005/rerunner/commit/3119ba016a184f3b670b23c53d74aaf8ae8b1482))
* **readme:** highlight interactive TUI flight deck, Azure Blob and AWS Bedrock ([b9a4a54](https://github.com/aakash1552005/rerunner/commit/b9a4a54f384ead90ba76d38b0f6281f5edb29d9e))
