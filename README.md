# Harle: Expert Developer Prompts for Gemini CLI

> This repository provides advanced, opinionated prompts for configuring the Gemini CLI as an expert developer—specializing in TypeScript, Node.js, Fastify, and modern web development.

## Overview

Harle's prompts go far beyond basic configuration. They encode:

- **TypeScript mastery** (strict typing, advanced generics, branded types, domain modeling)
- **Modern JavaScript expertise** (ES2024+, async patterns, performance, security)
- **Enterprise Node.js/Server patterns** (Fastify, observability, error handling, DDD, Clean Architecture)
- **Testing, documentation, and CI/CD best practices**
- **A communication philosophy**: Explain-first, clarify requirements, discuss trade-offs, and always document the "why"

## How to Use

1. **Choose a prompt:**
	- For Node.js/TypeScript/Fastify, use [`javascript/node-ts-fastify.md`](./javascript/node-ts-fastify.md)
2. **Copy and rename:**
	- Copy the desired file to your project root as `GEMINI.md`
3. **Customize:**
	- Edit `GEMINI.md` to match your stack, coding standards, and workflow
4. **Activate:**
	- The Gemini CLI will now use your expert prompt for all interactions

## What Makes These Prompts Different?

- **Explain-First Approach:** Every solution starts with analysis, trade-offs, and rationale—not just code
- **Strict Quality Standards:** TypeScript strict mode, advanced typing, robust error handling, and security by default
- **Modern Architecture:** DDD, Clean/Hexagonal, CQRS, microservices, and event-driven patterns
- **Comprehensive Testing:** TDD, property-based, contract, performance, and accessibility testing
- **Production-Ready Guidance:** CI/CD, observability, containerization, and deployment best practices

## Available Expert Prompts

- [`javascript/node-ts-fastify.md`](./javascript/node-ts-fastify.md):
	- Full-stack TypeScript/Node.js/Fastify expert prompt
	- Includes React, testing, and deployment guidance

- [`javascript/nextjs-ts.md`](./javascript/nextjs-ts.md):
	- Next.js & TypeScript specialist prompt
	- Covers App Router, Pages Router, advanced type safety, performance, SEO, security, and deployment for modern React applications

## Customization

These prompts are designed to be edited! Tweak them for your:

- Frameworks (e.g., Express, Koa, Vue, Svelte)
- Coding style and conventions
- Team workflow and review process
- Security, testing, and deployment requirements

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
