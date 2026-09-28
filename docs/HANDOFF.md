# Handoff for the next Claude Code session

The full handoff document (the state of all five repos, open PRs, where the
work stopped, next steps, how to rebuild the test environment, and the test
tools) is in the YiiMP fork:

https://github.com/mygiglifeinc-glitch/yiimp/blob/claude/phase2/docs/handoff/HANDOFF.md

Clone it with:

    git clone -b claude/phase2 https://github.com/mygiglifeinc-glitch/yiimp
    less yiimp/docs/handoff/HANDOFF.md

Short version (2026-09-28):
- Phase 1 PRs (#3) and Phase 2 PRs (#4) are open in yiimp,
  multipool_yiimp_single and multipool_yiimp_multi, with green CI. Merge #3
  first.
- Phase 3 (RandomX bridge) has not started. Check in with the owner first.
- Don't touch `claude/oshash`. Never force-push or rewrite
  `claude/multipool-installer-update-s3rama`.
