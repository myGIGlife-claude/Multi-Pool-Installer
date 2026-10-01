# Handoff for the next Claude Code session

The full handoff (state of all five repos, the owner's rules, the work queue,
how to rebuild the test environment, and the test tools) is in the YiiMP fork:

https://github.com/myGIGlife-claude/yiimp/blob/next/docs/handoff/HANDOFF.md

    git clone https://github.com/myGIGlife-claude/yiimp
    less yiimp/docs/handoff/HANDOFF.md    # start at section 0

Short version (2026-09-30):
- Phases 1-3 (new algos, KawPoW/Equihash/Decred protocols, RandomX/Monero)
  are merged in yiimp `next` and in the installers' `master`.
- Next: fix the coinbase height bug for blocks 1-16, run a payout test per
  algo family, then add solo mining (`-p c=SYMBOL,m=solo`).
- Merge only when the owner says so. Don't touch `claude/oshash`. Never
  force-push or rewrite `claude/multipool-installer-update-s3rama`.
