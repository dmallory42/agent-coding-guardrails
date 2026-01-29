---
name: coding-guardrails
description: Use when user asks to add, create, build, fix, modify, update, refactor, or write code. Use when making plans for code changes. Use before ANY coding task. Single entry-point enforcing four guardrails (assumptions, scope, simplicity, success criteria) through one checklist.
---

# Coding Guardrails

**This skill loads all guardrails in one place.** Run through this checklist before writing any code.

## The Four Gates

### 1. Success Criteria (What does "done" look like?)

Before coding, state: **"Success means ___"**

- A test passes
- Output matches expected
- Behavior is observable

If you can't complete that sentence, you're not ready to code.

### 2. Assumptions (What am I assuming?)

List your assumptions about:
- User intent
- Existing code behavior
- Constraints/requirements

For each: **Verified** (read the code) or **Uncertain** (need to ask)?

Resolve uncertain assumptions before proceeding.

### 3. Scope (What will I touch?)

Define the boundary:
- Which files?
- Which functions?
- What's explicitly OFF-LIMITS?

**Adjacent code is off-limits.** Comments you didn't write are sacred.

### 4. Simplicity (What's the minimum?)

Ask: **"What's the dumbest thing that would work?"**

Start there. If user could say "couldn't you just..." you're over-engineering.

## Red Flags - STOP

- Starting to code without answering all four gates
- Thinking "they probably want..."
- Creating abstractions for single use
- Touching code outside your defined scope
- Can't state observable success criteria

## Quick Reference

| Gate | Question | If Uncertain |
|------|----------|--------------|
| Success | "Done means ___" | Define criteria first |
| Assumptions | "I'm assuming ___" | Ask or verify |
| Scope | "I'll only touch ___" | Define boundary |
| Simplicity | "Simplest approach is ___" | Start dumber |

## After Implementation

Re-check:
- [ ] Only touched files in scope?
- [ ] No drive-by improvements?
- [ ] Simplest solution that works?
- [ ] Success criteria met?

**Four gates. Every time. No exceptions.**
