# Job Search Status — 2026-06-28

**Candidate:** Nathan Tugume · Target: software dev / IT support / sysadmin / networking, 1–5 yrs, Dubai & wider Middle East, visa sponsorship preferred.

## Result for this run: no new verified listings (data sources unavailable)

Today's automated search could **not pull fresh individual job postings** because the live data sources this routine depends on were unavailable in this session:

- **Indeed MCP integration not connected** — yesterday's run (2026-06-27) compiled its shortlist from the Indeed AE/SA job API. That MCP server did not expose any tools this session, so no API-backed listings could be retrieved.
- **Job boards blocked by network egress policy** — direct fetches of Indeed AE, Bayt, Naukrigulf, GulfTalent, ZeroTaxJobs and TheDubaiVacancy all returned **HTTP 403 (organization policy denial)** through the agent proxy. Per proxy policy these are not retried.
- **ZipRecruiter MCP is US/Canada-only** — not usable for Middle East roles.
- **WebSearch** returned only aggregator landing pages (e.g. "600+ IT support visa-sponsorship jobs in Dubai"), not individual postings with working apply links. Compiling a shortlist from these would mean fabricating apply links, which was not done.

## What this means

The market itself is clearly active — search aggregators show hundreds of IT-support / CCNA / network-admin and junior-developer roles in Dubai advertising visa sponsorship as of late June 2026. There is no sign of a downturn; the gap is purely tooling/access on the routine's side.

## Still current

Yesterday's shortlist (`job-matches-2026-06-27.md`, 7 ranked roles + 6 secondary) is only one day old and remains valid. Top sponsorship-safe picks there:
1. IT Technician — Supreme Legislation Committee (Dubai, govt) — election/legislation + secure-systems fit
2. Network Administrator — UAE University (Al Ain) — direct CCNA fit
3. IT Support Engineer — BlackStone eIT (Dubai) — near 1:1 skills match
4. IT Support–Network — Dar Al Uloom University (Riyadh) — lowest experience bar (1–2 yrs)

## Next steps

- Reconnect / re-enable the **Indeed MCP** server so the routine can resume API-backed searches.
- Consider allow-listing Gulf job-board domains (bayt.com, gulftalent.com, naukrigulf.com, ae.indeed.com) in the session network policy so WebFetch can extract individual postings.
- In the meantime, yesterday's links remain the actionable list to apply against.
