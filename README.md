# .github — defaults for every trevor-gooch repo

GitHub's default community health files repo. Anything under `.github/` here
applies to every repo on this account that doesn't override it with its own
copy — today that is one issue form, `ISSUE_TEMPLATE/task.yml`, which shapes
new issues so an agent can act on them (context, acceptance criteria,
pointers, verification).

Blank issues stay enabled (`config.yml`) — the form is a nudge, not a gate.

The queue convention the form references (triage labels are the authority
for who acts next: `ready` / `needs-spec` / `needs-trevor`) is documented in
each repo's CLAUDE.md; the cross-repo board is `~/dev/mini-jobs/bin/queue`
and the drift monitor is `mini-jobs/monitors/queue-lint.py`.

This repo must stay **public** — that's what makes GitHub apply its contents
account-wide. Nothing sensitive belongs here.
