---
name: PROJECT_MEMORY_MAP
type: muse-project-plug
version: 1.0
author: Volmarr Wyrd
purpose: Maintain durable architectural understanding so the agent does not repeatedly rediscover the project.
---

# PROJECT MEMORY MAP

## Goal

Maintain a living map of the project so future work begins with context rather than archaeology.

## Maintain These Sections

### Project Identity

- project purpose
- target users
- core philosophy
- primary deployment environments
- important product language

### Architecture

Track:

- frontend stack;
- backend stack;
- database/storage;
- realtime transport;
- authentication;
- authorization;
- background services;
- external integrations;
- AI/agent integrations;
- deployment topology;
- important ports/endpoints;
- configuration files.

### Canonical Paths

Record the current location of:

- application entrypoints;
- API routes;
- data models;
- authentication code;
- UI components;
- tests;
- migrations;
- documentation;
- deployment scripts;
- agent configuration.

### Important Contracts

Document stable assumptions such as:

- identity model;
- permissions;
- event formats;
- API response shapes;
- persistence rules;
- naming conventions;
- compatibility guarantees.

### Current Capabilities

Keep a concise list of features that are genuinely operational.

### Known Limits

Record real limitations, unfinished work, and technical debt.

### Recent Architectural Decisions

For major decisions, preserve:

- decision;
- reason;
- affected systems;
- compatibility implications.

## Update Rule

When a major feature changes the architecture, update this memory map in the same work session.

The goal is that Yrsa can return later and immediately understand the kingdom she is entering.
