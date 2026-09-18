# Evaluation Pass Map

A single page with two maps for one strategy on MNQ 1-minute data (2023-09 to 2026-09):

- **Evaluation** - how often a 30-day futures prop-firm evaluation would have passed, month by month, across 18 firm plans.
- **Funded payouts** - what a funded account actually paid over 180 days, and how often it paid at all, across 17 plans.

**Live page:** https://zuurohq.github.io/navi-prop-pass-map/

**Version:** map v1.6 (18 September 2026). The page carries its own version line and a "What changed" log, because several
figures have been corrected since the first version - most notably FXIFY, which was published at 44.8% from third-party
rules and is 32.7% (Expert) and 3.1% (Standard) using the firm's own.

Backtest history, not a forecast, and not advice. Firm rules change often; several of the plans shown carry rules taken
from third-party sources and are marked "rules unconfirmed" on the page. Confirm any rule with the firm before paying
for an account.

## Independent review

An adversarial review (2026-09-18) reproduced every figure from the trade lists, and rejected the first published
version of these pages: two plain-words lines were arithmetically wrong, and the payout model's assumptions were not
stated. Both are corrected here. The payout figures remain **modelled**: they assume the drawdown stops trailing at
$100 above the starting balance and use assumed payout caps where a firm does not publish them. Treat the payout map
as a ranking of payout rules, not a forecast.

## Internal page

This page is for the team, not for distribution. It carries a noindex instruction and a robots file so search engines
do not list it, but **anyone who has the link can open it** - GitHub Pages has no access control.

It holds two maps. The **evaluation map** has been through two independent reviews and every figure reproduces. The
**funded payout map** is modelled and its assumptions are not all proven: the floor lock is confirmed for 5 plans of 18,
some payout caps are assumed, and the model withdraws the maximum as soon as it is allowed, which is what drives the
high breach figures. Read it as a ranking of payout rules, not a forecast.
