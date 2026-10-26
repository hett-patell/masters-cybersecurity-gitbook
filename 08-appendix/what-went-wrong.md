# What we got wrong

{% hint style="info" %}
Transparency is the point. Every error found is listed here so you know what was corrected and what might still be wrong.
{% endhint %}

## Errors found by independent verification (2026-10-15, updated 2026-10-16)

50 claims checked across 2 rounds. **8 proven wrong, 6 need nuance.** All corrected throughout this book.

### ❌ Proven wrong

| # | Error | What the vault said | What's true | Impact |
|---|---|---|---|---|
| 1 | **NZ proof of funds** | NZD $5,000 | **NZD $20,000/year** | 4× understated. The $5,000 is for PSWV, not student visa. |
| 2 | **UK proof of funds** | £1,529 outside London, £1,171 London | **Inverted.** £1,529 = London, £1,171 = outside. *Further: from 30 Nov 2026, rates increase to £1,570 / £1,203.* | Misleading for budget planning |
| 3 | **Chevening rule** | "Degree must be 2 years old" | **2,800 hours work experience** after graduation | Wrong reasoning, similar conclusion |
| 4 | **Canada scholarships** | "No India-specific awards at any Canadian university" | **Wrong.** Carleton, Alberta, Toronto have them. | Overly pessimistic about Canada |
| 5 | **Calgary MISP fee** | CAD $27,237 | **CAD $50,465** (current published rate) | Nearly doubled — changes affordability |
| 6 | **Lancaster grade table** | 1st = 70–80% | **1st = 70–85%**, 2:1 = 60–80% | Affects grade conversion assessment |
| 7 | **NZ govt/defence roles** | "Citizenship-gated" | **PR holders accepted** for Police/NZDF | Opens more career paths in NZ |
| 8 | **IHS rate** | £1,035/year | **£776/year** for students | Affects UK cost calculation |

### ⚠️ Need nuance

| # | Issue | Correction |
|---|---|---|
| 9 | **Abertay "£3,000–£7,000 automatic"** | Only £3,000 is automatic; £4,000 extra is the competitive Principal's Excellence Scholarship |
| 10 | **SFU total fee ~CAD $40,425** | Actual: **CAD $55,425** — the lower figure subtracted a competitive award |
| 11 | **NZ Tier 1 pay threshold = "2× median = $70/hr"** | The actual INZ rate for ICT Security Specialist (262112) is **NZD $72.80/hr ($151,424/yr)** — role-specific, not a simple 2× median |
| 12 | **Green List "changes frequently"** | Official language: **"regularly reviewed"** via Cabinet process |
| 13 | **ATAS "not required for taught cyber MScs"** | **Likely required.** Cybersecurity MScs under CAH11-01-01 / CAH11-01-03 are listed in Appendix ATAS. Indian nationals are not exempt. Always check your CAS — but **plan for it** (free, 30+ working days). |
| 14 | **UK maintenance rates** | Book used pre-Nov 2026 rates (£1,171 / £1,529). From **30 Nov 2026**, new rates apply: **£1,203 outside London / £1,570 London**. Since Het applies mid-2027, all figures now use the new rates. |

### 🔄 Verification agent was itself wrong

{% hint style="danger" %}
**Plymouth NCSC:** The UK University Fee Verifier agent claimed Plymouth MSc Cyber Security is NOT NCSC-certified (only BSc). **The agent was wrong.** The live NCSC register (fetched and parsed 2026-10-15) clearly shows:

| University | Programme | Expiry |
|---|---|---|
| University of Plymouth | BSc Computer Science (Cyber Security) | 30/09/2031 |
| University of Plymouth | **MSc Cyber Security** | **30/09/2028** |

Both are on the register. The original vault claim (Plymouth MSc certified to 30/09/2028) was **correct all along**. This book has been corrected accordingly.

**Lesson:** Even verification agents make errors. Always cross-check agent claims against live primary sources.
{% endhint %}

### Errors found and corrected earlier (before fact-check)

| Error | What happened |
|---|---|
| **Fabricated CVEs** | A competing document claimed CVE-2026-2667 (Free5GC), CVE-2026-3497 (Checkmk), CVE-2026-3897 (D-Link). NVD showed these are completely different vulnerabilities. **Quarantined.** |
| **BVM "NIRF rank 250"** | Aggregator sites quote IIRF (a different body), not NIRF. BVM is NIRF _participant_, not ranked. |
| **Robert Gordon NCSC to 2029** | That's the Graduate Apprenticeship. Taught MSc = 30/09/2027. |
| **Auckland as "cheapest NZ option"** | MSc is 240 points / 2 years. India award covers 1 year only → ≈NZD $97,100 total. |
| **"UK is the only cost-viable country"** | Obsolete — axis changed to settlement |

{% hint style="warning" %}
**🧑 Human review checklist**

* [ ] All corrections verified against current official sources
* [ ] No new errors discovered since last review
* [ ] Last reviewed: \_\_\_\_
{% endhint %}
