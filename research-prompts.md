# Research Prompts: Data Onboarding Validation

These prompts are designed for AI research agents to find validated, citable data to support claims on the Payup data strategy page.

---

## 1. Hospital Billing Outsourcing Rates

**Claim to validate:** "35%+ of small hospitals outsource billing" / "~35% of CAHs outsource billing"

**Research prompt:**
> Find published research, surveys, or industry reports on the percentage of small hospitals (under 100 beds) and Critical Access Hospitals that outsource their revenue cycle management or billing operations to third-party companies. Look for data from HFMA, MGMA, AHA, Chartis, or healthcare consulting firms like Kaufman Hall, Advisory Board, or Guidehouse. Include the source name, publication date, sample size, and methodology if available. We need data specific to small/rural hospitals, not aggregate healthcare industry figures.

**Specific questions:**
- What percentage of Critical Access Hospitals outsource billing?
- What percentage of hospitals under 100 beds use third-party RCM?
- What percentage use partial vs. full outsourcing?
- Has this percentage increased in recent years?

---

## 2. Hospital Count by Category

**Claim to validate:** "~2,100 small/rural hospitals"

**Research prompt:**
> Find the current count of small and rural hospitals in the United States from AHA, CMS, or other authoritative sources. We need breakdowns by:
> - Critical Access Hospitals (CAHs)
> - Rural community hospitals
> - Hospitals under 100 beds
> - Hospitals under 50 beds
> - Sole Community Hospitals
> Include the source, date, and definition used for each category.

**Specific questions:**
- How many Critical Access Hospitals are currently operating?
- How many rural community hospitals exist?
- What is the total count of hospitals with fewer than 100 beds?
- How many have closed in the past 5 years?

---

## 3. Clearinghouse Market Share

**Claim to validate:** Clearinghouse market share table (Change Healthcare ~33%, Availity ~25%, etc.)

**Research prompt:**
> Find market share data for healthcare clearinghouses in the United States. Look for data on Availity, Change Healthcare/Optum, Waystar, Trizetto, Office Ally, and other major clearinghouses. Include transaction volume, provider connections, or revenue-based market share. Sources might include KLAS Research, Gartner, company press releases, SEC filings, or healthcare IT publications.

**Specific questions:**
- What is Change Healthcare's market share in claims processing?
- How many transactions does Availity process annually?
- What percentage of medical claims flow through electronic clearinghouses?
- Which clearinghouses are most used by small/rural hospitals specifically?

---

## 4. Clearinghouse File Retention Policies

**Claim to validate:** "Clearinghouses retain files for only 30 days in active mailboxes"

**Research prompt:**
> Find documentation on file retention policies for major healthcare clearinghouses (Availity, Change Healthcare, Waystar, Office Ally). How long do they retain 835 and 837 files in active mailboxes? How long in archives? What is the process for retrieving archived files? Look for official documentation, user guides, or support articles from these clearinghouses.

**Specific questions:**
- How long does Availity retain 835/837 files?
- How long does Change Healthcare retain files?
- What is the process for restoring archived files?
- Are there fees for archive retrieval?

---

## 5. Hospital Staff Technical Capabilities

**Claim to validate:** "2-4 hours onboarding time" and staff ability to navigate clearinghouse portals

**Research prompt:**
> Find research on the technical capabilities and training levels of hospital revenue cycle and business office staff, particularly at small and rural hospitals. Look for data on:
> - Staff familiarity with EDI file formats (835, 837)
> - Time required to train staff on new systems
> - Clearinghouse portal usage patterns
> - IT staffing levels at small hospitals
> Sources might include HFMA surveys, NAHAM, AAHAM, or academic research on healthcare IT adoption.

**Specific questions:**
- What percentage of hospital billing staff are familiar with X12 EDI formats?
- What is the average IT staff size at Critical Access Hospitals?
- How much time do revenue cycle staff spend on clearinghouse portals?
- What training is typically required for clearinghouse navigation?

---

## 6. RCM Vendor Integration Timelines

**Claim to validate:** Comparison to existing vendor onboarding timelines

**Research prompt:**
> Find published data on implementation timelines for healthcare revenue cycle management software and services. How long does it typically take to implement:
> - RCM analytics platforms (like Rivet Health)
> - Denial management software
> - Underpayment recovery services (like Aspirion)
> - Full RCM outsourcing (like R1 RCM, Ensemble)
> Look for KLAS Research reports, vendor case studies, or industry surveys on implementation timelines.

**Specific questions:**
- What is the typical implementation timeline for RCM analytics software?
- How long does denial management software take to implement?
- What is R1 RCM's typical implementation timeline?
- Are there any vendors with self-service or rapid onboarding?

---

## 7. SOC 2 / HITRUST Requirements in Healthcare

**Claim to validate:** Security certification timelines and requirements

**Research prompt:**
> Find data on security certification requirements for healthcare technology vendors:
> - What percentage of hospitals require SOC 2 Type I vs Type II?
> - What percentage require HITRUST?
> - What are typical timelines and costs for achieving these certifications?
> - Do requirements vary by hospital size?
> Look for CHIME surveys, HIMSS research, or healthcare security industry reports.

**Specific questions:**
- What percentage of hospitals require SOC 2 for vendors?
- Is HITRUST required for clearinghouse partnerships?
- What is the typical timeline to achieve SOC 2 Type I?
- What are typical costs for SOC 2 vs HITRUST certification?

---

## 8. Hospital Data Sharing and BAA Processes

**Claim to validate:** "CAH approval timeline: 2-8 weeks"

**Research prompt:**
> Find research on hospital vendor approval processes, particularly for technology vendors requiring access to PHI:
> - How long does vendor approval typically take at different hospital sizes?
> - What committees or approvals are required?
> - Do Critical Access Hospitals have faster approval processes?
> - What documentation is typically required (BAA, security questionnaires)?
> Look for CHIME, HIMSS, or healthcare procurement research.

**Specific questions:**
- What is the typical vendor approval timeline at Critical Access Hospitals?
- What approval process do large health systems use?
- What security documentation do hospitals typically require?
- How do approval timelines compare by hospital size?

---

## Priority Order

1. **Hospital billing outsourcing rates** — Critical for market sizing
2. **Hospital count by category** — Foundational for TAM
3. **Clearinghouse file retention** — Core to data access strategy
4. **Clearinghouse market share** — Informs partnership strategy
5. **Staff technical capabilities** — Informs onboarding design
6. **Security requirements** — Informs timeline and investment
7. **Vendor implementation timelines** — Competitive context
8. **BAA/approval processes** — Sales cycle planning

---

## Output Format Requested

For each research prompt, the agent should return:
1. **Finding:** The specific data point or statistic
2. **Source:** Publication name, author, date
3. **URL:** Direct link to the source
4. **Methodology:** Sample size, methodology if available
5. **Confidence:** High/Medium/Low based on source quality
6. **Notes:** Any caveats or context
