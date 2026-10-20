# Maintenance Plan

This document lays out the housekeeping plan for this repository. It is tracked in **issue #3 — "Housekeeping: maintenance tracker"**.

## Background

Before planning this sprint, every repository in the account was checked for community discussions (questions, ideas, and requests). **None were found anywhere**:

- Personal repositories (`HeziLiu/Little-rookie`, `HeziLiu/Big-Buzzard`, `HeziLiu/CodingInterviewChinese2`, `HeziLiu/awesome-chatgpt-prompts-zh`) — the Discussions feature is switched off on each of them.
- Organization repositories (`mcpmark-eval-liuhezi/*`) — the ~50 most recently updated were each checked; all returned zero discussions.

With no community-sourced feedback to fold in, this plan is built from routine maintenance instead.

## Tasks

Three tasks are tracked as sub-issues of #3:

1. **#4 — Task: dependency audit** — inventory all dependencies, check for advisories and outdated versions, flag anything deprecated or vulnerable, record findings and remediation.
2. **#5 — Task: README refresh** — review the README for accuracy, update the project description, setup/build instructions, and usage examples; fix typos, stale links, and outdated references.
3. **#6 — Task: stale branch cleanup** — list all branches, identify merged/abandoned/long-unused ones, confirm no in-flight pull requests, delete confirmed stale branches, and record what was removed or kept.

## Workflow

Each task is performed on its own branch and merged through a pull request into `main` once reviewed. The tracking issue (#3) stays open until all three sub-issues are closed.
