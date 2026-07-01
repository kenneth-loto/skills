# Skills

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

AI agents are powerful. They're also stateless, pattern-matching tools that will confidently build the wrong thing if you let them.

Skills give your AI agent the engineering discipline it doesn't have by default — framework-native patterns, typed testing strategies, and structured review. Slash commands that keep you in the driver's seat.

They work with any agent that supports the SKILL.md format: Claude Code, Cursor, Windsurf, Codex, Cline, and more.

**Philosophy:** The problem isn't that AI writes bad code. It's that developers stop thinking when it writes fast code. These skills keep you thinking.

---

## Install

```bash
npx skills@latest add kenneth-loto/skills
```

---

## Skills

### NestJS

#### `nestjs/nestjs-patterns`

**Use before building any module.**

Think through modules, DI, controllers, services, DTOs, guards, filters, and interceptors like a senior engineer before writing any code. Covers project structure, dependency injection rules, route ordering, exception filters, bootstrap order, and the `useClass` vs `useExisting` guard gotcha.

This is not a grilling session. It is a thinking session — collaborative, not adversarial.

---

#### `nestjs/nestjs-jest-testing`

**Use when writing or reviewing tests.**

Write strictly-typed Jest tests using the repository pattern — no `any`, ORM-agnostic mocking via injected interfaces. Covers the four rules of typed mocking, controller unit tests, E2E with in-memory fakes vs real databases.

Working and correct are not the same thing.

---

#### `nestjs/nestjs-jest-prisma-testing`

**Use when testing a Prisma-backed codebase.**

Write strictly-typed Jest tests for services and controllers that use Prisma directly — no `any`, correctly mocked Prisma delegates, real model shapes. Covers mocking Prisma delegates, `$transaction` mocking, service and controller unit tests, E2E with real databases.

---

## The Engineering Loop

```
Pattern  →  Build  →  Test  →  Ship
```

---

## Learn More

Built by [Kenneth Loto](https://github.com/kenneth-loto) — production-grade skills for serious engineers.

---

## Contributing

Found a bug or want to improve a skill? Open an issue or PR. Skills are just markdown — contributions are welcome from anyone.

---

## License

[MIT](LICENSE)
