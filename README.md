# achievement-lab

The live lab notebook behind [The GitHub Achievements Field Guide](https://github.com/ssmurfgg04-gif/github-achievements-field-guide).

Everything in this repository happened for a reason. In one controlled run, on an account that was hours old, this repo was used to test how GitHub achievements really behave:

- Issue #1 was opened and closed in **1.4 seconds** (Quickdraw target)
- **9 Q&A discussions** were created and an answer was marked accepted in each (Galaxy Brain target). Try the Discussions tab, they are all live.
- **62 pull requests** authored by the account were merged in a single day (Pull Shark target)
- **50 commits** on main carry a `Co-authored-by:` trailer, plus a 12 PR hedge batch with the trailer in the other direction (Pair Extraordinaire target)

The result, and the part worth your attention: the two single action badges appeared within the hour. The three high volume badges stayed hidden past the documented 24 hour processing window, even though every count was verified through the GitHub API. Bulk farmed activity sits in the queue. Real contributions flow.

That single finding is why the guide recommends the slow path. Read the full requirements, the gotchas that cost us time, and the raw log here:

- Guide: https://github.com/ssmurfgg04-gif/github-achievements-field-guide
- Raw data: https://github.com/ssmurfgg04-gif/github-achievements-field-guide/blob/main/data/unlock-log.json
- Badge checker CLI: https://github.com/ssmurfgg04-gif/github-achievements-field-guide/tree/main/cli

If you replicate the experiment, the guide links replication logs. Open a PR.
