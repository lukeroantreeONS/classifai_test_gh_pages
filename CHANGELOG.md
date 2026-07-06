# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.4.0](https://github.com/lukeroantreeONS/classifai_test_gh_pages/compare/v0.3.0...v0.4.0) (2026-07-06)


### Features

* **ci:** Add whl building and manifest config to release-please action ([#4](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/4)) ([2ad1865](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/2ad186553aa818d1994c1b077bb5e0cb2601e959))

## [0.3.0](https://github.com/lukeroantreeONS/classifai_test_gh_pages/compare/v0.2.1...v0.3.0) (2026-07-03)


### Features

* 98 generative AI agent for classification ([#105](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/105)) ([bef9146](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/bef91463e6916d10ec2dca96c90e694257c705e0))
* ClassifaiError class for Errors and logging ([#121](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/121)) ([f21f873](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/f21f873de61254f7819ec34979e68844e456de0c))
* Cloud storage compatibility with build, save and from_filespace vectorstore operations ([#170](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/170)) ([2c5bd3d](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/2c5bd3d7faf56522c9b83ccbe70ccdd1e5347bc6))
* **docs:** Quarto-generated documentation site ([#96](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/96)) ([9f7435e](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/9f7435e0b9873c9cb2ba44bcc5b25068cd248671))
* Evaluation Module Prototype ([#172](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/172)) ([aa64e52](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/aa64e5284047abb9c33321b6b32653c6b969b2f4))
* **indexers:** add framework for default hooks ([#140](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/140)) ([9706568](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/9706568700acc195bf8fc6f29969dece641beb65))
* **indexers:** added partial matching to reverse search ([#131](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/131)) ([57cc2c8](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/57cc2c8b6f08232d3aef301183ab839ebe6f75ff))
* **indexers:** make persisting VectorStore to disk optional ([#174](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/174)) ([fca5d25](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/fca5d25645fb37947c488f94d7a8bb6d38064b18))
* **quarto docs:** add workflow to trigger quarto build & deployment to GitHub Pages on changes to new branch 'gh-pages-publish' ([#151](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/151)) ([ae162d9](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/ae162d922b58d56ea408a1fba2e51adb53f3d8b5))
* **servers:** refactors server to expose APIRouter ([#125](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/125)) ([f477d34](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/f477d346703a6e0f07d3451bab78c8733f434eca))
* **servers:** setup organization of the apirouters ([#179](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/179)) ([e29898c](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/e29898c297728aff5ea2c3753ca4e780c5089821))


### Bug Fixes

* **CICD:** new release of gitleaks docker requires username/password for setup, no longer works in CICD, so disabling as GitGuardian offers same protection ([#160](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/160)) ([6089271](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/6089271fe594ae9d0a987e9b65b9e07960027a28))
* **CICD:** revert workflow permissions from 'checks' to 'pull-requests' ([#145](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/145)) ([3c1164d](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/3c1164dadc78011528b3c5626806a7bc7bcdc625))
* **dependabot:** update google-genai min version, triggering inclusion of patched pyasn1 dependency ([#159](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/159)) ([ae60231](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/ae6023139b8b6f0b2484cdfdd09b60f14c585fd9))
* **hooks:** make RAGHook aligned with optional dependency approach ([#157](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/157)) ([cb94f67](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/cb94f671c7910c5d3f56096f0467f8a8b1a6ee7c))
* pipeline hook data into FastAPI response ([#135](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/135)) ([9bce67a](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/9bce67a3fad2f7a4acce37abaa66330451c02b27))
* replaces strenum with mixin ([#193](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/193)) ([fad6304](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/fad630440e9e38a9f5bcb0182f342f25d83066bb))
* **reverse_search:** bugfix for reverse_search ([#186](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/186)) ([30619cb](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/30619cbe93ccb23b2b011c4766d2a5a3abc481e3))
* **servers:** update default reverse search api max_n_results to optionally return all ([#137](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/137)) ([d772809](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/d772809c7ebfa427fe2d2c1d1122d17a43d06ef3))


### Documentation

* **eval:** Quarto Updates v1.1.0 ([#199](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/199)) ([0d9bcef](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/0d9bcef57a73e566976c502d26c04cf3d3a59fa7))
* Evaluation module demo and documentation ([#194](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/194)) ([52e5229](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/52e522993fe86ff8d87c4a40fac2c665d55ddfce))
* **hooks:** added hooks to docs ([#164](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/164)) ([94b70f7](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/94b70f75ba83a0cce46069e749e979d11a6355ac))
* **quarto:** Tidy up & address Quarto-rendered formatting for first Pages deployment ([#148](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/148)) ([fdeddff](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/fdeddff97540b8e79c0df10e953ed71f2ecfce4d))
* readme instructions updated to reference 1.0.0 ([#162](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/162)) ([db41db7](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/db41db770376b41e5c99b5c47a503e5be6688204))
* **repo:** Add Mandatory Files as required for all ONS repositories ([#133](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/133)) ([282e47f](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/282e47f11fec4ba1555141b1c7a937cd70f7f37a))
* update documentation for release 1.1.0 ([#191](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/191)) ([#196](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/196)) ([a1cc038](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/a1cc0380211f760fe1dd9624e01b3d09d54a251c))
* **version:** update package-internal version ([#180](https://github.com/lukeroantreeONS/classifai_test_gh_pages/issues/180)) ([806dfda](https://github.com/lukeroantreeONS/classifai_test_gh_pages/commit/806dfda5855f29a6eb6fbad48904ee1d95680e72))

## [v1.1.0] - 2026-07-03

### Added

- Evaluation module demo and documentation
- Quiet mode; suppress progress bars, raise logging level to Warning & above
- Integrated Cloud storage interactions for VectorStore creation, saving, and re-loading
- Made persisting VectorStore to disk optional
- Hooks now in docs
- Logging levels and host IP to run_sever() function

### Changed

- Updated VectorStore batch size to improve performance
- Improved Server Router Organization for better OpenAPI docs

### Fixed

- Resolved reverse search Error when no matched Documents


## [v1.0.0] - 2026-03-27

### Added

- AI Agents - Hooks for using genai to perform tasks on VectorStore results.
- Hooks Framework - new framework for hooks to support premade and custom hook development.
- Server Class Features:
    - new methods for instantiating the FastAPI application and/or routing.
    - allows middleware to be used, or the routing to be attached to another FastAPI service.
- Documentation - new QuartoDocs documenting the ClassifAI package and new demo notebooks.
- Partial String matching - reverse search VectorStore method now does optional partial matching.
- Vectoriser Class - More options for instantiating HuggingFace models.

### Changed

- Datasets - updated dataset column names for v1.0.0
- Documentation - better docstrings and updated demo notebooks.
- Dataclasses - updated for more intuitive dataframe column naming.
- Server Class Refactor:
    - expanded scope of features.
    - renamed start_api method to run_server.

### Fixed
- Server hook data - hook metadata now returned in FastAPI responses.
- Reverse Search results - fixed issue where max_n_results defaulted to None causing errors.

## [v0.2.1] - 2026-02-06

### Fixed

- Dependency Bug - Removed old dependency code for data processing.

## [v0.2.0] - 2026-01-28

### Added

- Improved Vectorisers - More ways to use GcpVectoriser.
- Hooks - User defined hook functions for custom input and output VectorStore logic.
- Dataclasses - Data objects for interfacing with core VectorStore methods.
- Documentation and Demo - README updates, Jupyter Notebooks for running server, hooks and more.

## [v0.1.0] - 2025-11-04

### Added

- Vectoriser Class - Abstract base class, and GCP, HuggingFace, Ollama Vectorisers
- Vector Store Class
- REST API - FastAPI served with Uvicorn
- Documentation and Demo - README and Jupyter Notebook minimal demo with fake dataset.


<!-- Links to tags -->
[v1.0.0]: https://github.com/datasciencecampus/classifai/compare/v0.2.1...v1.0.0
[v0.2.1]: https://github.com/datasciencecampus/classifai/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/datasciencecampus/classifai/compare/v0.1.0...v0.2.0
[v0.1.0]: https://github.com/datasciencecampus/classifai/releases/tag/v0.1.0
