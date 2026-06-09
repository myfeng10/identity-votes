# Identity Votes

An agent skill that tracks identity votes while users talk.

Most reflection tools wait for a clean journal entry. This skill works during ordinary conversation: the agent notices repeated behaviors, keeps a lightweight vote ledger, and returns the identity pattern at a natural endpoint.

## What It Helps With

- Spotting what identity a routine is reinforcing
- Catching Avoider or Confronter patterns without shame
- Turning scattered self-talk into one high-ROI next vote
- Helping ADHD or distracted users avoid another tracking system

## Install

```bash
npx skills add myfeng10/identity-votes
```

Then restart your agent.

## Example Prompt

```text
Use $identity-votes while I talk through my day. At the end, tell me what identity I reinforced and the highest-ROI next vote.
```

## Core Idea

Behavior disappears. Identity accumulates.

The user should not need to manually track every action. The agent can listen for the votes already present in conversation and hand back a useful read.
