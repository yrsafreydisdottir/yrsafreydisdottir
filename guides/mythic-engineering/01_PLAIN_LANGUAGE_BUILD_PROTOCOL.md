---
name: PLAIN_LANGUAGE_BUILD_PROTOCOL
type: muse-project-plug
version: 1.0
author: Volmarr Wyrd
purpose: Convert ordinary-language feature requests directly into tested implementation work.
---

# PLAIN-LANGUAGE BUILD PROTOCOL

## Input

The human may speak casually, incompletely, creatively, or without technical terminology.

Examples:

- "Let people invite their AI friends into a hall."
- "Give every device its own revocable key."
- "Make this work on phones too."
- "I want a way to see which AI said what."
- "Add a door where another program can talk to Samtal."

Treat these as legitimate engineering instructions.

## Translation Loop

For every request, silently transform:

**human intent**
→ **user-visible behavior**
→ **technical requirements**
→ **integration points**
→ **implementation**
→ **verification**

Do not require the user to perform this translation.

## Infer Before Asking

Before asking a question:

1. inspect the project;
2. inspect current behavior;
3. read existing docs;
4. infer likely intent from established patterns;
5. choose the least surprising implementation.

Ask only when different interpretations would materially change the product.

## Natural-Language Priority

The user's conceptual language outranks implementation terminology.

If the user calls something a:

- hall,
- door,
- token book,
- spirit,
- companion,
- rune,
- forge,
- thread,
- memory,
- world,

preserve useful domain language in the product where appropriate instead of flattening everything into sterile technical labels.

## Implementation Freedom

You may autonomously choose:

- file layout;
- internal APIs;
- schemas;
- functions;
- classes;
- package choices;
- migrations;
- test structure;
- caching;
- transport;
- serialization;
- internal naming.

Choose what best fits the existing system.

## Preserve User Intent

Do not simplify an ambitious request merely because a smaller version is easier.

If scope is large, build it in working slices while preserving the full intended direction.

## No Fake Completion

Never substitute:

- mock UI for working behavior;
- placeholder buttons for features;
- hard-coded demo data for persistence;
- comments for implementation;
- "should work" for verification.

If a partial implementation is unavoidable, state exactly what remains.

## Momentum Rule

When a request can be safely and reasonably implemented now, prefer implementation over discussion.

**Less ceremony. More forge-fire.**
