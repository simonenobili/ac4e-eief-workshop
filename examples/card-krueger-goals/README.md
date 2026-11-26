# Card–Krueger goal briefs

Short briefs for to-do lists and goals. Each brief opens with a
**one-sentence goal**: a finish line you can check. Give the agent that sentence,
not the whole brief.

| Brief | Goal |
| --- | --- |
| [`goals/ck-replication-audit.md`](goals/ck-replication-audit.md) | An audit note records GREEN, YELLOW or RED with the check-command output |
| [`goals/ck-robustness-checks.md`](goals/ck-robustness-checks.md) | The script prints the main DiD and two robustness versions (ask for the to-do list only) |
| [`goals/ck-parallel-trends-figure.md`](goals/ck-parallel-trends-figure.md) | A figure shows NJ and PA mean employment in both waves |

## How to set a goal in each tool

**Claude Code and Codex** have a `/goal` command. The agent keeps working until the
goal is met or it gets stuck. `/goal` alone shows the current goal; `/goal clear`
removes it.

```text
/goal notes/replication_audit_ck.md exists and records GREEN, YELLOW or RED with the check-command output
```

**Cursor** has no `/goal` command. Put the goal as the last line of your
instructions. For a cloud agent, put it in the task description.

Check the current command names in your installed version:
[Claude Code](https://code.claude.com/docs/en/goal),
[Codex](https://developers.openai.com/cookbook/examples/codex/using_goals_in_codex).

## Caveat

Every brief uses the synthetic data in `examples/card-krueger-toy/`. Use them to
practise directing an agent, not to replicate Card and Krueger (1994).

Ciao
