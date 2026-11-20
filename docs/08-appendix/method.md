# Method

## How this research was built

### Five research sweeps



### Sweep 1 — `05-top50-sweep`

87 QS-ranked universities → the QS ladder + definitive NCSC cross-check



### Sweep 2 — `06-fit-sweep`

37 specialist cyber schools → schools the top-50 couldn't see (Abertay, Napier, Ulster…)



### Sweep 3 — Stealth pass

Cloudflare/JS-blocked pages → fees and awards that returned `NOT FOUND`



### Sweep 4 — `07-final-verify`

30 UK universities × 4 decision questions → NCSC expiry · India equivalency · MOI · deadlines & deposit risk



### Sweep 5 — `08-ca-nz-verify`

9 Canada + NZ universities → settlement-path verification



### Independent fact-checking

After the research sweeps, **6 AI verification agents** independently checked 46 key claims against official sources:

| Agent | Domain | Claims checked |
|---|---|---|
| CVE & Profile Verifier | NVD, CERT-In, NAAC, BVM | 10 |
| UK Immigration Verifier | gov.uk, Immigration Rules, Chevening | 8 |
| Canada Immigration Verifier | IRCC, Quebec immigration | 8 |
| NZ Immigration Verifier | immigration.govt.nz, INZ Ops Manual | 8 |
| UK University Fee Verifier | University websites, NCSC register | 7 |
| Canada University Fee Verifier | University calendars, fee schedules | 5 |

!!! success
    **Result:** 34 confirmed, 8 wrong (corrected), 3 need nuance, 1 unverifiable.


### Standing rules

!!! info
    1. **No remembered figures.** Every number from a page fetched in-session, with academic year recorded.
    2. **Unfetchable → `NOT FOUND`** — a finding, not a gap. Never interpolate.
    3. **Aggregators are for locating, never as evidence.** Shiksha, CollegeDunia, IDP, ApplyBoard — for finding official pages only.
    4. **Competitive awards are upside, not budget.** Never subtract from net cost.
    5. **Every sweep has frozen INSTRUCTIONS.md + RUN.md + inputs.txt.** No freeform research.


### Known traps (already fell into these)

!!! danger
    | Trap | What happened | Guard |
    |---|---|---|
    | Apprenticeship/DL certification | Claimed Robert Gordon MSc certified to 2029 — that's the Graduate Apprenticeship | Build script now aborts on this error class |
    | Two official pages, two numbers | Waikato's pages gave NZ$72,463 vs NZ$72,471 | Cross-check; prefer programme page |
    | Per-year vs total (NZ) | Auckland read as "NZ$42.7k" when MSc is 240 pts / 2 years | Always multiply for NZ |
    | JS widgets swallow data | Humber hard-blocked; Green List looked empty | Use real keystroke + click; try fee-schedule PDFs |
    | Stale summary tables | Nine files still rank Canada/NZ above UK | Master table is generated — never hand-edit |
    | Verification agent error | Agent claimed Plymouth MSc not NCSC-certified; live register shows it IS (to 30/09/2028) | Always cross-check agent claims against live data |


!!! warning
    **🧑 Human review checklist**

    * [ ] Method documented accurately
    * [ ] Verification agent errors noted
    * [ ] Last reviewed: ____

