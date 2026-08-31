# Dealmakers Digest: The Ledger

Every deal on this page gets scored the same way, on the record, in public. Two tables below.
The first holds the rows scored live... deals logged within days of being announced, before anyone
could know how they turn out. The second is the calibration set: the deals the scoring system
was built and checked against, scored after the fact and labelled that way. **This is the receipt.**

**Subscribe:** [Dealmakers Digest on Substack](https://shavaye.substack.com/subscribe?utm_source=ledger&utm_medium=web&utm_campaign=the_ledger)

**What the scores mean.** *Posture* is the company's role in the deal: **Empire-building**
(buying something), **Focus** (selling off a piece of itself), or **Partnership** (a joint
venture, alliance or strategic partnership... working together, nobody buys anybody).
*Structure* is what kind of deal it is: **Scale** (more of the same), **Complementary**
(buying a capability they lack), or **Convergence** (combining two worlds to make something
new). **Cross-industry** in front means the two sides come from clearly different industries.

**What the numbers mean.** *Since announced* is the live one: the price the stock closed at on
the day of the deal, and how far it has moved against the overall market since. It updates
every night, so it changes between visits.

The 30d, 90d and 1yr columns are a different thing and sit behind a dividing line for that
reason. They are fixed research horizons measured 30, 90 and 252 trading days after the deal
(roughly six weeks, four months and a year), calculated on the frozen method and then left
alone. Blank means not enough time has passed yet... that is the point of scoring in public,
the number arrives when it arrives. Status shows how much of the outcome is in so far.

**On the timestamps.** `Scored` is the date this row was committed and pushed to this public
repo. GitHub records the push time on its own servers, independent of anything set locally in
the commit, and the full history has been public since this repo went live. Anyone can audit it.

**Read this honestly.** These are research observations about how the market has *reacted*
historically, not investment advice and not predictions about any single stock. The patterns
are exploratory and small-sample. Every quarter I report back, including the misses.

_Last updated 2026-09-01. 9 live, 6 calibration, 15 tracked total._

## The live table: scored before the outcome was known

Every row here was scored within 14 days of the deal being announced... before any of the
outcome numbers existed.

All 9 live rows are still waiting on the market. The first 30-day
numbers land around 2026-09-11.

| Company | Deal date | Scored | Posture | Structure | Since announced | 30d | 90d | 1yr | Status | Filing |
|---|---|---|---|---|---|---|---|---|---|---|
| Schlumberger (SLB) | 2026-08-31 | 2026-09-01 | Empire-building | Complementary | from $60.10 |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/87347/000119312526375358/d106278d8k.htm) |
| Aon plc (AON) | 2026-08-30 | 2026-09-01 | Empire-building | Scale | from $321.52 |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/315293/000119312526375328/d108801d8k.htm) |
| Oneok (OKE) | 2026-08-28 | 2026-09-01 | Empire-building | Scale | +1.6% (from $94.76) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1039684/000119312526377023/d405989d8k.htm) |
| WEC Energy Group (WEC) | 2026-08-14 | 2026-08-20 | Empire-building | Scale | -2.7% (from $110.52) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/783325/000078332526000095/wec-20260814.htm) |
| Nvidia (NVDA) | 2026-08-17 | 2026-08-18 | Partnership | Complementary | -1.7% (from $225.01) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000069/nvda-20260817.htm) |
| Newmont (NEM) | 2026-08-10 | 2026-08-16 | Partnership | Scale | +8.3% (from $117.26) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1164727/000110465926095968/tm2623048d1_8k.htm) |
| Teledyne Technologies (TDY) | 2026-08-10 | 2026-08-11 &dagger; | Empire-building | Complementary | -10.4% (from $690.25) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1094285/000109428526000047/tdy-20260810.htm) |
| Prologis (PLD) | 2026-08-04 | 2026-08-05 &dagger; | Empire-building | Scale | +1.2% (from $139.05) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1045609/000110465926089980/tm2621154d2_8k.htm) |
| Intercontinental Exchange (ICE) | 2026-07-29 | 2026-08-02 | Empire-building | Complementary | -1.0% (from $154.28) |  |  |  | pending | [SEC](https://www.sec.gov/Archives/edgar/data/1571949/000119312526324909/d116245d8k.htm) |

&dagger; 2 rows scored before this ledger fetched the underlying 8-K, so the rubric was applied to a filing index rather than to the document. Re-judged against the real filing. All were unchanged: the original score held. The original date stands, because the original score stands.



## The calibration table: scored after the fact

These 6 rows were scored well after their event, with a scoring lag from
48 to 101 days (median 62). This is the set the scoring system
was built and checked against, not a record of live scoring. The lag is stated on every row
so nobody has to take that on faith.

| Company | Deal date | Scored | Lag (days) | Posture | Structure | Since announced | 30d | 90d | 1yr | Status | Filing |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Eaton (ETN) | 2026-06-10 | 2026-07-28 | 48 | Empire-building | Scale | +1.3% (from $375.46) | +5.8% |  |  | 30d in | [SEC](https://www.sec.gov/Archives/edgar/data/1551182/000095014226001733/eh260792115_8k.htm) |
| CoStar Group (CSGP) | 2026-05-28 | 2026-07-24 | 57 | Empire-building | Complementary | -2.4% (from $32.30) | -10.0% |  |  | 30d in | [SEC](https://www.sec.gov/Archives/edgar/data/1057352/000119312526246361/d91732d8k.htm) |
| Tractor Supply (TSCO) | 2026-05-28 | 2026-07-24 | 57 | Empire-building | Convergence | +9.6% (from $31.37) | -2.7% |  |  | 30d in | [SEC](https://www.sec.gov/Archives/edgar/data/916365/000091636526000046/tsco-20260528.htm) |
| Boston Scientific (BSX) | 2026-05-18 | 2026-07-24 | 67 | Empire-building | Complementary | -17.5% (from $55.92) | -25.3% |  |  | 30d in | [SEC](https://www.sec.gov/Archives/edgar/data/885725/000088572526000042/bsx-20260518.htm) |
| American Express (AXP) | 2026-05-04 | 2026-07-24 &dagger; | 81 | Focus | Scale | -3.5% (from $319.21) | +3.2% |  |  | 30d in | [SEC](https://www.sec.gov/Archives/edgar/data/4962/000000496226000207/axp-20260504.htm) |
| Leidos (LDOS) | 2026-04-14 | 2026-07-24 | 101 | Partnership | Cross-industry Complementary | -20.7% (from $156.17) | -21.1% | -12.3% |  | 90d in | [SEC](https://www.sec.gov/Archives/edgar/data/1336920/000119312526155884/d148240d8k.htm) |

&dagger; 1 row scored before this ledger fetched the underlying 8-K, so the rubric was applied to a filing index rather than to the document. Re-judged against the real filing. It was unchanged: the original score held. The original date stands, because the original score stands.


*The live "since announced" figure and the 30d/90d/1yr columns measure differently, and can legitimately disagree. Since announced is the plain gap to the market, regrown nightly. The outcome columns freeze at fixed horizons and judge each stock against what its own market sensitivity implied, giving no credit for the trend it was already on... a stock that was falling into its announcement does not score points for levelling off. When the two tell different stories, the outcome column is the stricter measure.*


_The scoreboard is free. The written breakdowns (the players, the deal, the
principle behind it) go out on [Dealmakers Digest](https://shavaye.substack.com/subscribe?utm_source=ledger&utm_medium=web&utm_campaign=the_ledger)._

_Full machine-readable history in `ledger.csv`, with a `prospective` Y/N column. The vocabulary
and the receipts are public; the exact rubric is proprietary and stays private._

_Disclosure: the author works in this industry. Deals involving the author's employer are
excluded from public scoring as a matter of standing policy; they are scored privately on the
same instrument and are not published on this page._
