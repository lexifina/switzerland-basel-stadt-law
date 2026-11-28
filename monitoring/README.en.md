<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Basel Stadt only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:55 UTC, Basel Stadt: systematic collection (www.gesetzessammlung.bs.ch): 379 addresses read; 0 added, 1 changed, 0 removed; changes found; 5 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Basel Stadt: systematic collection (www.gesetzessammlung.bs.ch)](https://www.gesetzessammlung.bs.ch/) | `<act>/` | daily | 2026-11-28 05:55 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:49](checks/2026-11.md#ch-lexwork-basel-stadt-20261128t054900z) | lexwork-basel-stadt | 379 | 0 | 1 | 0 | 5 (0) | changes found | — |
| [2026-11-27 05:51](checks/2026-11.md#ch-lexwork-basel-stadt-20261127t055126z) | lexwork-basel-stadt | 397 | 0 | 1 | 0 | 4 (0) | changes found | — |
| [2026-11-26 05:49](checks/2026-11.md#ch-lexwork-basel-stadt-20261126t054926z) | lexwork-basel-stadt | 397 | 110 | 0 | 0 | 4 (0) | changes found | [193](https://github.com/lexifina/switzerland-basel-stadt-law/compare/719ea2dbe296...fd06bd9f7b8e) |
| [2026-11-25 06:04](checks/2026-11.md#ch-lexwork-basel-stadt-20261125t060422z) | lexwork-basel-stadt | 488 | 260 | 0 | 0 | 112 (0) | changes found | [260](https://github.com/lexifina/switzerland-basel-stadt-law/compare/067cc4896743...ecbdf8aea6af) |
| [2026-11-24 14:34](checks/2026-11.md#ch-lexwork-basel-stadt-20261124t143453z) | lexwork-basel-stadt | 270 | 260 | 2 | 0 | 263 (0) | the check failed | — |
| [2026-11-24 11:55](checks/2026-11.md#ch-lexwork-basel-stadt-20261124t115546z) | lexwork-basel-stadt | 611 | 261 | 0 | 0 | 262 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
