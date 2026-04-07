# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0](https://github.com/first-storm/ultimate-playwright-mcp/compare/v0.2.1...v0.3.0) (2026-04-07)


### Features

* add browser_evaluate tool for in-page JS execution ([2fc47dc](https://github.com/first-storm/ultimate-playwright-mcp/commit/2fc47dc597ab42d878bf59c8d049bfa18e11f158))
* add checkpoint capture tools ([e0c3591](https://github.com/first-storm/ultimate-playwright-mcp/commit/e0c3591dd0de8282e0625170ed230f11d86701d9))
* add screenshot tool, tests, fix extensionId persistence bug ([e2a7230](https://github.com/first-storm/ultimate-playwright-mcp/commit/e2a723098fc06af7ba8055e0ae9328dab31c68db))
* auto-load bundled tab-grouper extension by default ([7f20e80](https://github.com/first-storm/ultimate-playwright-mcp/commit/7f20e80e163b471ab69a2b2e1f3b9a5a459c0a3a))
* comprehensive stealth script injection ([6588548](https://github.com/first-storm/ultimate-playwright-mcp/commit/658854878d6ce1a6c19695567646401299249d50))
* configurable download dir via --download-dir / DOWNLOAD_DIR env ([7e2279c](https://github.com/first-storm/ultimate-playwright-mcp/commit/7e2279ca7b36a601a9753a2a98c6411d047c0bc0))
* enable file downloads in CDP-controlled Chrome ([c1ed92f](https://github.com/first-storm/ultimate-playwright-mcp/commit/c1ed92f6620e2a00f30bbf96fb113e39a1cf4ef5))
* expose snapshot filtering options and screenshot quality for small-model friendliness ([48acc12](https://github.com/first-storm/ultimate-playwright-mcp/commit/48acc12f310e87eb2296419be4331d7008bc1679))
* lazy-start daemon and disable keepalive by default ([82e89c4](https://github.com/first-storm/ultimate-playwright-mcp/commit/82e89c483d7dff1efb365696673d9f5c41a2d970))
* set Chrome downloads to ~/Downloads by default ([42f1c19](https://github.com/first-storm/ultimate-playwright-mcp/commit/42f1c19a9a43aff60cea269be4b0118c0afc0084))
* stealth mode - remove automation fingerprints from Chrome ([cdc9421](https://github.com/first-storm/ultimate-playwright-mcp/commit/cdc94215bf678500ee0b9b57ba732944333a855c))
* tab group isolation with visual Chrome tab groups ([a3142d6](https://github.com/first-storm/ultimate-playwright-mcp/commit/a3142d6b118391b8a97184ae32bc7a1769abd714))


### Bug Fixes

* create tabs via extension for reliable visual grouping ([7435421](https://github.com/first-storm/ultimate-playwright-mcp/commit/743542184ee96d1ca73664b7e7cf46fbbd76f1bc))
* guard publish job with tag check instead of releases_created condition ([b5c7b51](https://github.com/first-storm/ultimate-playwright-mcp/commit/b5c7b511f73989c9048f662e8d910e2f1776496a))
* guard publish job with tag existence check ([1af1312](https://github.com/first-storm/ultimate-playwright-mcp/commit/1af1312962b6cf922bed5161e899b02f34089550))
* lint errors for CI (add node/browser globals, fix empty blocks) ([bdd0b88](https://github.com/first-storm/ultimate-playwright-mcp/commit/bdd0b88529d37b05224b616810c3284c3bf4572d))
* persist ref store to disk for cross-process ref resolution ([6fd64ac](https://github.com/first-storm/ultimate-playwright-mcp/commit/6fd64aca797bf5bf5ccec4df31c60ffcbe0e004c))
* relax lint to allow warnings ([40ff2b4](https://github.com/first-storm/ultimate-playwright-mcp/commit/40ff2b4c5b136a445c75274cb175816a39367f23))
* resolve all 28 TypeScript any warnings ([f2dc6f6](https://github.com/first-storm/ultimate-playwright-mcp/commit/f2dc6f67079f6d6df74bd3edcd76c5698d4b4d4f))
* use tag_name for checkout to fix npm publish ([4b27fa4](https://github.com/first-storm/ultimate-playwright-mcp/commit/4b27fa4bea930a26688c62cac25dbaca54515502))
* use tag_name output for checkout instead of github.ref ([d082f3d](https://github.com/first-storm/ultimate-playwright-mcp/commit/d082f3dbe98834f5ebe049992eb40e02a8299ec8))


### Documentation

* add badges, comparison table, and Why section to README ([78521c8](https://github.com/first-storm/ultimate-playwright-mcp/commit/78521c8857b6a8af049922f8bee2cb3a9dfb438c))
* add CHANGELOG.md ([8610d56](https://github.com/first-storm/ultimate-playwright-mcp/commit/8610d56c03349362c87d8f5247b41a1ecbde7ef7))


### Miscellaneous

* add .npmrc to gitignore ([c108556](https://github.com/first-storm/ultimate-playwright-mcp/commit/c10855669e3564880c51c3c28bc3c87d3b61cef3))
* add release-please automation and commitlint ([#2](https://github.com/first-storm/ultimate-playwright-mcp/issues/2)) ([626e626](https://github.com/first-storm/ultimate-playwright-mcp/commit/626e62646975f9d75d6548dd122e6e81a90b1e03))
* bump to 0.1.1 ([b939de2](https://github.com/first-storm/ultimate-playwright-mcp/commit/b939de2d03bd7c819d75492186575bad5d89648b))
* bump v0.1.2 ([9940f0b](https://github.com/first-storm/ultimate-playwright-mcp/commit/9940f0bfed8d2a88807cd50812361aaf1f5fb227))
* bump v0.1.3 ([f596450](https://github.com/first-storm/ultimate-playwright-mcp/commit/f596450e7a8a676b1c0b697ffd21c11abf37181a))
* initialize beads ([4d65b83](https://github.com/first-storm/ultimate-playwright-mcp/commit/4d65b837db3f22431312a63ec92547066706a25a))
* integrate npm publish into release-please workflow ([47542cb](https://github.com/first-storm/ultimate-playwright-mcp/commit/47542cb9f9f110ba7f20d623e48b1fd867d2eaa9))
* integrate npm publish into release-please workflow ([52d2da3](https://github.com/first-storm/ultimate-playwright-mcp/commit/52d2da3e695e026f070cbad8ea0a7340134e5346))
* **main:** release 0.2.0 ([25d9bcd](https://github.com/first-storm/ultimate-playwright-mcp/commit/25d9bcda52c76122c7866fdff1c1359569d8a3f2))
* **main:** release 0.2.0 ([cbf6cee](https://github.com/first-storm/ultimate-playwright-mcp/commit/cbf6cee7e23bf2061b7c872bb6b70b92d397d0d4))
* **main:** release 0.2.1 ([4191132](https://github.com/first-storm/ultimate-playwright-mcp/commit/4191132a15e032dd49c62894c0ea8981bce1108e))
* **main:** release 0.2.1 ([06275d7](https://github.com/first-storm/ultimate-playwright-mcp/commit/06275d7ac1149f08075f2797683ad992d37d1c3e))
* run npm pkg fix to normalize bin paths ([ab16323](https://github.com/first-storm/ultimate-playwright-mcp/commit/ab16323beaf7ac98e708704a6c556312f852fbbf))
* sync beads issues ([550fe30](https://github.com/first-storm/ultimate-playwright-mcp/commit/550fe30d28ffaa61b9faf47e97404e2b4d9a6417))


### Code Refactoring

* move tab group state from JSON file to extension storage ([d3ab187](https://github.com/first-storm/ultimate-playwright-mcp/commit/d3ab1877b346979421cf044a811ed6b578632bc7))

## [0.2.1](https://github.com/pm990320/ultimate-playwright-mcp/compare/v0.2.0...v0.2.1) (2026-04-03)


### Bug Fixes

* use tag_name for checkout to fix npm publish ([4b27fa4](https://github.com/pm990320/ultimate-playwright-mcp/commit/4b27fa4bea930a26688c62cac25dbaca54515502))
* use tag_name output for checkout instead of github.ref ([d082f3d](https://github.com/pm990320/ultimate-playwright-mcp/commit/d082f3dbe98834f5ebe049992eb40e02a8299ec8))

## [0.2.0](https://github.com/pm990320/ultimate-playwright-mcp/compare/v0.1.3...v0.2.0) (2026-04-03)


### Features

* comprehensive stealth script injection ([6588548](https://github.com/pm990320/ultimate-playwright-mcp/commit/658854878d6ce1a6c19695567646401299249d50))
* expose snapshot filtering options and screenshot quality for small-model friendliness ([48acc12](https://github.com/pm990320/ultimate-playwright-mcp/commit/48acc12f310e87eb2296419be4331d7008bc1679))
* stealth mode - remove automation fingerprints from Chrome ([cdc9421](https://github.com/pm990320/ultimate-playwright-mcp/commit/cdc94215bf678500ee0b9b57ba732944333a855c))


### Bug Fixes

* guard publish job with tag check instead of releases_created condition ([b5c7b51](https://github.com/pm990320/ultimate-playwright-mcp/commit/b5c7b511f73989c9048f662e8d910e2f1776496a))
* guard publish job with tag existence check ([1af1312](https://github.com/pm990320/ultimate-playwright-mcp/commit/1af1312962b6cf922bed5161e899b02f34089550))
* persist ref store to disk for cross-process ref resolution ([6fd64ac](https://github.com/pm990320/ultimate-playwright-mcp/commit/6fd64aca797bf5bf5ccec4df31c60ffcbe0e004c))


### Miscellaneous

* add release-please automation and commitlint ([#2](https://github.com/pm990320/ultimate-playwright-mcp/issues/2)) ([626e626](https://github.com/pm990320/ultimate-playwright-mcp/commit/626e62646975f9d75d6548dd122e6e81a90b1e03))
* integrate npm publish into release-please workflow ([47542cb](https://github.com/pm990320/ultimate-playwright-mcp/commit/47542cb9f9f110ba7f20d623e48b1fd867d2eaa9))
* integrate npm publish into release-please workflow ([52d2da3](https://github.com/pm990320/ultimate-playwright-mcp/commit/52d2da3e695e026f070cbad8ea0a7340134e5346))

## [0.1.1] - 2026-02-09

### Fixed

- Relaxed ESLint max-warnings for CI compatibility
- Added .npmrc to .gitignore

## [0.1.0] - 2026-02-09

### Added

- Initial release
- Tab group isolation for multi-agent browser sharing
- 10 MCP tools: tab_group, tabs, navigate, snapshot, click, type, hover, press_key, fill_form, wait_for
- CDP connection to existing Chrome instances
- Accessibility tree snapshots with element refs
- Chrome tab group extension for visual organization
- Persistent tab group registry (~/.ultimate-playwright-mcp/tab-groups.json)
