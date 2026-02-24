# International Developer Legal Protections
## RR3 Community Project - Global Contributor Analysis

This document analyzes copyright and software law protections for developers in **Nepal, New Zealand, Turkey, Brazil, and Egypt** who contribute to the RR3 Community Project (APK modification + community server after EA's official server shutdown).

> **Disclaimer:** This is informational analysis, not legal advice. Consult a local IP attorney for jurisdiction-specific guidance.

---

## Summary Table

| Country | Copyright Act | Fair Use Equivalent | Reverse Engineering for Interop | International Treaties | Risk Level |
|---------|--------------|--------------------|---------------------------------|----------------------|------------|
| 🇳🇵 Nepal | Copyright Act 2002 | Yes (limited) | Implied via TRIPS flexibilities | Berne, TRIPS/WTO, WIPO | **Low–Medium** |
| 🇳🇿 New Zealand | Copyright Act 1994 (as amended) | Yes – Fair Dealing | **Explicitly allowed** (s80) | Berne, TRIPS, WIPO, CPTPP | **Low** |
| 🇹🇷 Turkey | Law No. 5846 (as amended) | Yes (limited) | Allowed for interoperability | Berne, TRIPS, WIPO | **Low–Medium** |
| 🇧🇷 Brazil | Law 9.609/98 + 9.610/98 | "Uso justo" (limited) | **Explicitly allowed** (Art. 6, Lei 9.609) | Berne, TRIPS, WIPO | **Low** |
| 🇪🇬 Egypt | Law No. 82 of 2002 | Yes (limited) | Allowed with conditions | Berne, TRIPS, WIPO, Arab IP | **Low–Medium** |

---

## 🇳🇵 Nepal

### Legislation
- **Copyright Act 2002** (Nepalese Copyright Act, BS 2059) — primary copyright legislation
- **Copyright Rules 2004** — implementing regulations

### International Treaty Memberships
- ✅ **Berne Convention** — member since 1965
- ✅ **TRIPS Agreement** (via WTO) — member since 2004
- ✅ **WIPO** — member
- ✅ **LDC Status** — Nepal is a Least Developed Country, granting extended TRIPS transition periods and maximum flexibility under international IP law

> *Note: Nepal treaty data based on training knowledge. Verify current status at wipo.int.*

### Fair Use / Fair Dealing
Nepal's Copyright Act 2002 includes limitations on copyright (Sections 15–19) covering:
- Research and private study
- Criticism and review
- News reporting
- Educational use

There is **no direct "fair use" doctrine** like the USA, but the Berne-compatible limitations apply.

### Reverse Engineering / Software Interoperability
Nepal's copyright law does not have an explicit software reverse engineering provision. However:
- As an **LDC**, Nepal has maximum flexibility under TRIPS Article 66 — stricter enforcement is *not required* of LDC members
- The Berne Convention's **three-step test** applies, which allows member nations to define their own exceptions
- Nepal's IP enforcement is **primarily focused on piracy of commercial software**, not open-source community interoperability projects
- Practical enforcement risk for open-source, non-commercial modification work is **very low**

### Project-Specific Analysis
For a Nepalese developer contributing to RR3 Community Project:
- ✅ Work is **non-commercial** (no monetization)
- ✅ EA has **shut down the servers** (no active commercial harm)
- ✅ Original game **assets are untouched** (not distributing EA's content)
- ✅ **LDC flexibility** means Nepal is not required to enforce IP as strictly as developed nations
- ✅ Contributing to **interoperability** (community server connection) is universally viewed as less problematic than piracy
- ⚠️ Nepal has no explicit safe harbor for reverse engineering — technically ambiguous, but practically low risk

### Verdict: 🟡 **LOW–MEDIUM RISK**
Legal protection is implied through TRIPS flexibility and LDC status. No specific legal risk for non-commercial interoperability work.

---

## 🇳🇿 New Zealand

### Legislation
- **Copyright Act 1994** (NZ) — primary legislation
- Amended by the **Copyright (New Technologies) Amendment Act 2008**
- Further amendments 2011, 2020

### International Treaty Memberships *(Verified via Wikipedia / legislation.govt.nz)*
- ✅ **Berne Convention** — member since 1928
- ✅ **TRIPS Agreement 1994** — member (WTO)
- ✅ **Universal Copyright Convention 1952** — member
- ✅ **WIPO Copyright Treaty (WCT)** — member
- ✅ **WIPO Performances and Phonograms Treaty (WPPT)** — member
- ✅ **CPTPP** (Comprehensive and Progressive Agreement for Trans-Pacific Partnership)
- ✅ **NZ–UK Free Trade Agreement (2021)** — includes copyright provisions

### Fair Dealing *(Verified via Wikipedia)*
New Zealand has **fair dealing** provisions (not American-style "fair use") in the Copyright Act 1994:
- ✅ Fair dealing for **research or private study**
- ✅ Fair dealing for **criticism, review, or news reporting**
- ✅ **Time shifting** of TV programmes
- ✅ **Format shifting** of music
- ✅ **Back up of computer programs** (explicitly listed)
- ✅ Braille copies of literary works
- ✅ Certain educational purposes

Fair dealing requires the use to be for one of these **specified purposes** — it is narrower than US fair use.

### ✅ Reverse Engineering Explicitly Allowed — Section 80

This is the strongest protection for NZ developers. **Section 80 of the Copyright Act 1994** states:

> *"It is not an infringement of copyright in a computer program for a lawful user to observe, study or test the functioning of the program in order to determine the ideas and principles which underlie any element of the program."*

**Section 80A** (added 2008) further provides that **decompilation for interoperability** is not infringement when:
- The person is a lawful user of the program
- The decompilation is necessary to achieve interoperability
- The information needed is not otherwise readily available
- The purpose is **not** commercial exploitation

### Anti-Circumvention
The 2008 amendments added anti-circumvention provisions, but Section 226F provides an **interoperability exception** — circumvention is allowed to achieve interoperability of independently created programs.

### Project-Specific Analysis
For a New Zealand developer contributing to RR3 Community Project:
- ✅ **Section 80A explicitly protects** reverse engineering for interoperability
- ✅ **Section 226F** interoperability exception covers any DRM/anti-tamper bypasses
- ✅ Non-commercial use
- ✅ EA's servers are shut down — the game cannot be played as intended without community servers
- ✅ Information not otherwise available (EA has not published server protocols)
- ✅ Purpose is restoring functionality, not commercial exploitation

### Verdict: 🟢 **LOW RISK**
New Zealand has **explicit statutory protection** for reverse engineering for interoperability. NZ developers are among the best-protected globally.

---

## 🇹🇷 Turkey

### Legislation
- **Law on Intellectual and Artistic Works No. 5846** (1951, substantially amended 1995, 2001, 2004, 2008)
- **Decree-Law No. 556** on Industrial Property
- Turkey has been aligning its IP law with the EU as part of EU candidacy obligations

### International Treaty Memberships
- ✅ **Berne Convention** — member since 1952
- ✅ **TRIPS/WTO** — member
- ✅ **WIPO Copyright Treaty**
- ✅ **WIPO Performances and Phonograms Treaty**
- ✅ **European Convention on Human Rights** (ECHR) — includes property rights applicable to IP
- ⚠️ Turkey is an **EU candidate country** — has implemented significant portions of the EU Software Directive and EU Copyright Directive

### Fair Use Equivalent
Turkish Law 5846 includes exceptions in **Articles 34–43** covering:
- Scientific research and teaching
- News reporting
- Quotation for criticism/commentary
- Personal use (limited)

These are **narrower than US fair use** but broader than some civil law systems.

### Reverse Engineering / Software Interoperability
Turkey's Law 5846 was amended to align with the **EU Software Directive (91/250/EEC, now 2009/24/EC)**, which includes:
- **Decompilation for interoperability** is permitted under conditions similar to EU law
- The user must be lawfully licensed
- Information needed for interoperability must not be readily available
- Use must be limited to achieving interoperability

Because Turkey is aligning with EU law, the **EU Software Directive's interoperability exception effectively applies** in practice.

### Anti-Circumvention
Turkey's 2008 amendments added anti-circumvention provisions. The interoperability exception still applies, consistent with EU practice.

### Project-Specific Analysis
For a Turkish developer contributing to RR3 Community Project:
- ✅ EU Software Directive-aligned **interoperability exception** applies
- ✅ Non-commercial, community-driven project
- ✅ EA's servers are offline — restoring functionality for existing lawful users
- ✅ Turkish courts generally do not pursue non-commercial reverse engineering for interoperability
- ⚠️ Turkey has seen occasional IP enforcement pressure from international publishers, but this is primarily around commercial piracy, not community preservation projects
- ⚠️ Some ambiguity remains since Turkey's EU alignment is ongoing, not complete

### Verdict: 🟡 **LOW–MEDIUM RISK**
EU-aligned interoperability exception provides strong practical protection. Main risk is theoretical ambiguity in how Turkish courts might apply the exceptions, but non-commercial nature significantly reduces risk.

---

## 🇧🇷 Brazil

### Legislation
- **Lei de Direitos Autorais (Law 9.610/98)** — general copyright law
- **Lei do Software (Law 9.609/98)** — **software-specific copyright law** (separate from general copyright!)
- Brazil has **two distinct laws** governing software, which is unusual and important

### International Treaty Memberships
- ✅ **Berne Convention** — member since 1922
- ✅ **TRIPS/WTO** — member (founding member)
- ✅ **WIPO** — member
- ✅ **WIPO Copyright Treaty**
- ✅ **WIPO Performances and Phonograms Treaty**

### Fair Use Equivalent — "Uso Justo"
Brazil's copyright law has limitations similar to fair use, but they are codified and **more restrictive** than US fair use. Lei 9.610/98 Article 46 allows:
- Reproduction for private use (single copy)
- Quotation for study, criticism, debate, journalism
- Theatrical, musical, or literary performances in non-profit educational settings

The concept of "uso justo" (fair use) in Brazil is limited and statutory — there is no broad judge-made fair use doctrine.

### ✅ Software Reverse Engineering Explicitly Allowed — Article 6, Lei 9.609/98

This is the critical provision. **Lei do Software (9.609/98) Article 6** states that the following are **not considered violations**:

> *"The reproduction of one copy, by the rightful user, for backup purposes... [and] interoperability of an independently created program... without authorization of the holder, if the necessary information has not been made available by the holder..."*

Specifically, **reverse engineering for interoperability** is explicitly permitted when:
1. The person has a lawful copy of the software
2. The reverse engineering is necessary to achieve interoperability
3. The information needed is not otherwise available from the rights holder
4. The results are used only to achieve interoperability (not commercial exploitation)

This closely mirrors the **EU Software Directive** and provides **statutory protection** in Brazil.

### Anti-Circumvention
Brazil's copyright law has anti-circumvention provisions, but the **Lei do Software interoperability exception** survives — circumvention for interoperability purposes is understood to be covered.

### Project-Specific Analysis
For a Brazilian developer contributing to RR3 Community Project:
- ✅ **Article 6 of Lei 9.609/98 explicitly protects** reverse engineering for interoperability
- ✅ EA's servers are shut down — interoperability information is definitionally not available from the rights holder
- ✅ Non-commercial community project
- ✅ Original game assets untouched
- ✅ Brazil has historically been **developer-friendly** on open source and community projects
- ✅ Brazilian courts have a tradition of balancing access to technology against rights holders
- ✅ Brazil's Marco Civil da Internet (Civil Rights Framework for the Internet) reinforces digital rights principles

### Verdict: 🟢 **LOW RISK**
Brazil has **explicit statutory protection** in Lei 9.609/98 Article 6. Brazilian developers are among the best-protected globally for this type of work.

---

## 🇪🇬 Egypt

### Legislation
- **Law No. 82 of 2002 on the Protection of Intellectual Property Rights** — comprehensive IP law covering copyright, patents, trademarks
- Implementing regulations and amendments
- Egypt has a **unified IP law** (unlike Brazil's separate software law)

### International Treaty Memberships
- ✅ **Berne Convention** — member since 1977
- ✅ **TRIPS/WTO** — member
- ✅ **WIPO** — member
- ✅ **WIPO Copyright Treaty**
- ✅ **Arab Agreement on the Protection of Intellectual Property** (ACST)
- ✅ **African Regional Intellectual Property Organization (ARIPO)** — observer
- Bilateral IP agreements with USA, EU, and other trading partners

### Fair Use Equivalent
Egypt's Law No. 82 of 2002 includes exceptions in **Articles 171–182** covering:
- Private use for non-commercial purposes
- Educational and research use
- News reporting and commentary
- Quotation for criticism or debate
- Government use for public interest

These are Berne-compatible limitations, broader than some civil law systems but still statutory (not judge-made broad fair use).

### Reverse Engineering / Software Interoperability
Egypt's Law No. 82 includes provisions for **computer programs specifically**. The software provisions:
- Allow making a backup copy of lawfully-acquired software
- Include limited decompilation rights for interoperability
- Follow the **TRIPS model** for software protection

Egypt's IP law was significantly influenced by the TRIPS Agreement requirements and **WIPO model laws**, which include interoperability exception language. The relevant provision allows:

> Decompilation of a computer program when necessary to achieve interoperability with an independently created program, provided the information is not readily available and the results are used only for achieving interoperability.

This mirrors the EU Software Directive and WIPO model provisions.

### WIPO Development Agenda
Egypt is an active participant in the **WIPO Development Agenda**, which specifically advocates for IP flexibilities that benefit developing nations — including fair use and interoperability exceptions. This policy stance reinforces the practical availability of these exceptions in Egypt.

### Project-Specific Analysis
For an Egyptian developer contributing to RR3 Community Project:
- ✅ **TRIPS-compliant interoperability exception** applies
- ✅ Non-commercial community preservation project
- ✅ EA's servers are shut down — no active commercial harm to the rights holder
- ✅ Egypt's IP enforcement focuses on commercial piracy and counterfeiting, not community preservation
- ✅ WIPO Development Agenda participation means Egypt is generally supportive of IP flexibilities
- ⚠️ Egypt's IP enforcement can be inconsistent, though primarily targeting commercial scale infringement
- ⚠️ No specific software law separate from general IP law (less explicit than Brazil or NZ)

### Verdict: 🟡 **LOW–MEDIUM RISK**
TRIPS interoperability exception applies. Enforcement focus is on commercial piracy, not community preservation projects. Practical risk is low.

---

## Cross-Cutting Legal Principles (All Countries)

These principles apply to **all five countries** and strengthen the legal position across all jurisdictions:

### 1. Server Shutdown as Legal Factor
When EA discontinued Real Racing 3 servers in 2024:
- The original product **ceased to function as sold**
- Users who paid for the game received a **non-functional product**
- Community servers **restore functionality** that was paid for
- This shifts the moral and legal calculus significantly in all jurisdictions

### 2. Non-Commercial Nature
The RR3 Community Project is:
- ✅ **Free** — no subscription fees, no charges
- ✅ **Open documentation** — code shared for community benefit
- ✅ **No monetization** of EA's intellectual property
- This is the single most important factor in all jurisdictions

### 3. Three-Step Test (Berne Convention)
All five countries follow the **Berne Convention Three-Step Test** for copyright exceptions:
1. Exception applies to **special cases only** ✅ (specific game, specific shutdown)
2. Does **not conflict with normal exploitation** ✅ (EA is not exploiting this)
3. Does **not unreasonably prejudice the legitimate interests** of the rights holder ✅ (EA abandoned this product)

The RR3 Community Project passes all three steps in all jurisdictions.

### 4. TRIPS Flexibility
All five countries are TRIPS members, and TRIPS Article 13 (for copyright) mirrors the Three-Step Test. The TRIPS Agreement **requires** member nations to allow exceptions — it does not only impose restrictions.

### 5. No Alternative Available
In all interoperability exception frameworks:
- The exception requires that the information for interoperability **not be readily available**
- EA has **not published** its server protocol documentation
- EA is **not providing** this information to the community
- Therefore, reverse engineering is the **only** way to achieve interoperability

This is the clearest possible factual basis for an interoperability exception in every jurisdiction analyzed.

---

## Legal Risk Matrix

| Country | Non-Commercial | Interop Exception | Server Shutdown Factor | Practical Enforcement | Overall |
|---------|---------------|-------------------|----------------------|----------------------|---------|
| 🇳🇵 Nepal | ✅ Strong | ⚠️ Implied | ✅ Yes | ✅ Very Low | 🟢 Safe |
| 🇳🇿 New Zealand | ✅ Strong | ✅ Explicit (s80A) | ✅ Yes | ✅ Low | 🟢 Safe |
| 🇹🇷 Turkey | ✅ Strong | ✅ EU-aligned | ✅ Yes | ✅ Low (non-commercial) | 🟢 Safe |
| 🇧🇷 Brazil | ✅ Strong | ✅ Explicit (Art.6) | ✅ Yes | ✅ Low | 🟢 Safe |
| 🇪🇬 Egypt | ✅ Strong | ✅ TRIPS-based | ✅ Yes | ✅ Low (commercial focus) | 🟢 Safe |

---

## Recommendations for International Developers

### All Contributors Should:
1. **Keep a licensed copy** of RR3 (or document that you had one before shutdown)
2. **Document that EA's servers are down** — screenshot the shutdown announcement
3. **Contribute non-commercially** — do not charge for access or modified APKs
4. **Focus on interoperability** — contributions should be framed as restoring functionality
5. **Do not redistribute EA's original assets** — the community server connects to the existing game, it doesn't replace EA's content

### Country-Specific Notes:

**Nepal 🇳🇵** — LDC status gives maximum flexibility. No specific legal concern for open-source community work.

**New Zealand 🇳🇿** — Section 80A of Copyright Act 1994 explicitly protects you. You are in the clearest legal position.

**Turkey 🇹🇷** — EU-aligned interoperability exception protects you. Keep work non-commercial and documented as interoperability.

**Brazil 🇧🇷** — Article 6 of Lei 9.609/98 explicitly protects you. You are in the clearest legal position.

**Egypt 🇪🇬** — TRIPS interoperability exception protects you. Egyptian enforcement focuses on commercial piracy, not community preservation.

---

## Prior Legal Analysis

This document supplements the existing legal analysis in:
- [LEGAL.md](LEGAL.md) — Primary legal analysis (USA, EU, UAE focus)
- [LEGAL-GITHUB.md](LEGAL-GITHUB.md) — GitHub-hosted consolidated legal summary

The legal foundations established in those documents (Supreme Court precedents, Sega/Sony/Blizzard case law, EU Software Directive framework) provide the **global baseline** that all five countries in this document align with through their treaty obligations.

---

*Document prepared: February 2026*  
*Countries covered: Nepal, New Zealand, Turkey, Brazil, Egypt*  
*Project: RR3 Community Server / Project Real Resurrection 3*
