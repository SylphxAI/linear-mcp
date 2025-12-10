# @sylphx/linear-mcp

## 1.4.0 (2025-12-10)

### ✨ Features

- add new changeset for removing validation before execution ([a57325a](https://github.com/SylphxAI/linear-mcp/commit/a57325a00b43075e32294076ab9dedb168059963))
- **issues:** support projectId argument in list_issues tool ([93d580c](https://github.com/SylphxAI/linear-mcp/commit/93d580ca7bd78196954d19f6a7b1450492523a30))

### 🐛 Bug Fixes

- add shebang for executable script support in changeset ([843c91b](https://github.com/SylphxAI/linear-mcp/commit/843c91b9e29e15a654cb628d04b1962ef221ddca))
- add shebang to index.ts for executable script support ([d2a4819](https://github.com/SylphxAI/linear-mcp/commit/d2a481955c8f03101ac7aceeac50d649a547e978))
- add missing order by enum in changeset ([2953433](https://github.com/SylphxAI/linear-mcp/commit/2953433efd480d613e7812b1b3514939d4f87550))
- **SYL-102:** resolve TypeScript errors in src/index.ts ([1391b3d](https://github.com/SylphxAI/linear-mcp/commit/1391b3d0307e6049c728bf1f575f0de8f474d453))

### ♻️ Refactoring

- issue and project tools for improved error handling and filtering ([788b37c](https://github.com/SylphxAI/linear-mcp/commit/788b37c850b7430e42f3e07a1f041d0cfa3b662c))
- update CommentOutput interface and improve type safety in mapping functions ([0e59a35](https://github.com/SylphxAI/linear-mcp/commit/0e59a35ecc4eb2e900d3163b0dff21ba1f0e1df8))
- localize schemas and streamline output mapping for issue, project, team, and user tools ([b3ef4d3](https://github.com/SylphxAI/linear-mcp/commit/b3ef4d39fdc5ffe7897b8f469c621bfd4375e87c))
- localize schemas for issue creation, updating, and retrieval tools ([6f0e09b](https://github.com/SylphxAI/linear-mcp/commit/6f0e09bfabb12d620b06aca1e9a7128d3a389f54))
- localize project schemas and streamline project handling logic across tools ([61ddeaf](https://github.com/SylphxAI/linear-mcp/commit/61ddeaf4e77cc6ee095486a14de88afbf10b00fb))
- simplify project retrieval logic by localizing schema and removing redundant checks ([f9580cd](https://github.com/SylphxAI/linear-mcp/commit/f9580cd946e2d45c9bd29d4e1ddc430452804bed))
- localize all schemas/utilities and remove shared.ts files (SYL-165) ([5d22f60](https://github.com/SylphxAI/linear-mcp/commit/5d22f6093848f2f4ae226093de5d5d6c32d9887c))
- streamline issue and project validation logic, removing redundant checks and imports ([166ca2c](https://github.com/SylphxAI/linear-mcp/commit/166ca2ce9121ecdbe9dbf4ed5fcea7b32d2efc1e))
- streamline code structure and improve import organization ([bafdd61](https://github.com/SylphxAI/linear-mcp/commit/bafdd61b882fa5421eb251386beb69300334145e))
- enhance updateIssueTool with improved validation and error handling ([6ca4609](https://github.com/SylphxAI/linear-mcp/commit/6ca46093e6cbdb7004445bb9eac0fb327157aa6a))
- update import statements for Linear SDK types and improve orderBy usage ([6475432](https://github.com/SylphxAI/linear-mcp/commit/6475432ffc9345220278ce1e90e5842d8a70d878))
- reorganize imports in list_my_issues tool for clarity ([266b7f9](https://github.com/SylphxAI/linear-mcp/commit/266b7f979c2b8cda147b248e4db79d02a6c6ce3d))
- issue tools and improve code consistency ([e2f6977](https://github.com/SylphxAI/linear-mcp/commit/e2f697703880a6f0bf7ec9afb96c8f8ad750d10d))
- **labels:** update label function to use specific IssueLabel type and adjust imports ([d487fc2](https://github.com/SylphxAI/linear-mcp/commit/d487fc2809b70898a6243340d7d1f1d94ebcb769))
- **tools:** update imports to use shared module for issue and project tools ([19ac55e](https://github.com/SylphxAI/linear-mcp/commit/19ac55e208957acad40eeaaa0d9fed2ec93958ff))
- **tools:** add index.ts to each tool module, remove upper-level re-export, export array ([9aaa809](https://github.com/SylphxAI/linear-mcp/commit/9aaa809ca9a871ee2f54ff7acaacea5a584c0a94))
- **teams,users:** modularize all team/user tools, extract shared logic, unify exports ([657e38f](https://github.com/SylphxAI/linear-mcp/commit/657e38f034afbb0cb7fc69c534ee81722623bae1))
- **schema:** move all schemas/types to local tool modules, remove centralized schema directory ([4a708ca](https://github.com/SylphxAI/linear-mcp/commit/4a708cadcc67bbb0b57e313e77a2e01936dd5950))
- **tools:** modularize all tool files, extract shared logic, unify exports ([9a5f198](https://github.com/SylphxAI/linear-mcp/commit/9a5f198f5ab62a2f565d280b2aece2d6cc7ad5f8))
- standardize quotes and improve error handling in team and user tools ([e2b6480](https://github.com/SylphxAI/linear-mcp/commit/e2b64803de8fc601b81a976964eb68a1ca0576b4))

### ✅ Tests

- remove obsolete tests for getTeamTool functionality ([80df13b](https://github.com/SylphxAI/linear-mcp/commit/80df13baed167f0d68c6157120303672e30ae5df))

### 🔧 Chores

- **ci:** migrate to unified release.yml workflow ([2286bf0](https://github.com/SylphxAI/linear-mcp/commit/2286bf06f1dd819e810226dc080b4035337674c9))
- **ci:** migrate to shared pnpm workflow ([b477b68](https://github.com/SylphxAI/linear-mcp/commit/b477b684e245ef8eb5165273a7d80d2e436bd20d))
- **deps:** update pnpm to v10.11.0 (#21) ([2528222](https://github.com/SylphxAI/linear-mcp/commit/252822255f6b257a6ac9011fd310808d4a6bcd8f))
- version packages ([9ee52ec](https://github.com/SylphxAI/linear-mcp/commit/9ee52ece9f72e274ae7b25a779bca80632617c19))
- version packages ([088dd3c](https://github.com/SylphxAI/linear-mcp/commit/088dd3ca9462b62721faf9f0d033c7833529dce4))
- version packages ([02874bc](https://github.com/SylphxAI/linear-mcp/commit/02874bc58497f154e9612bc5331e6bc82712bda7))
- **changeset:** add modern-islands-accept changeset for type bugfix ([d1fd10e](https://github.com/SylphxAI/linear-mcp/commit/d1fd10eeba31e7c5d9dfbf43ea80f5f20c326a2b))
- **lint:** fix biome import type, no any, reduce complexity in issues/projects/labels ([76796df](https://github.com/SylphxAI/linear-mcp/commit/76796df9437582edbbf87bd3234147e718c63f18))

## 1.3.4

### Patch Changes

- 843c91b: fix: add shebang for executable script support

## 1.3.3

### Patch Changes

- 2953433: fix: missing order by enum

## 1.3.2

### Patch Changes

- d1fd10e: bugfix: types

## 1.3.1

### Patch Changes

- modularize all tools, remove centralized schema, unify exports, breaking file structure refactor

## 1.3.0

### Minor Changes

- Enhanced ID error handling in MCP tools to provide a list of valid IDs upon error.

## 1.2.0

### Minor Changes

- d0f31e1: Remove Cycles, add Project Milestones, update README

## 1.1.2

### Patch Changes

- f8289d3: return cycle information on other nodes.

## 1.1.1

### Patch Changes

- c1ec30d: fix node support version

## 1.1.0

### Minor Changes

- 17c4627: support cycle

## 1.0.2

### Patch Changes

- 8f2303f: updated Readme.md

## 1.0.1

### Patch Changes

- 7266d0c: bump version

## 1.0.0

### Major Changes

- 929a382: first stable version.
