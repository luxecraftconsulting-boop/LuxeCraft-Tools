# LuxeCraft Phase 1 Implementation Toolkit

The complete deliverable system for running a Phase 1 JobTread implementation engagement. Tools are numbered in chronological order of when they get used during an engagement.

---

## Workflow Overview

| When | Tool | What it produces |
|------|------|------------------|
| End of Phase 0 | 01 - Build Complexity Scorecard | Track recommendation + branded report |
| Phase 0 → Week 0 | 02 - Scope Confirmation Templates | Signed engagement contract |
| Week 0 | 03 - Implementation Roadmap Generator | Client-facing 13-week roadmap |
| Week 0 | 04 - JobTread Schedule CSV Generator | Internal week-by-week tracker |
| Week 0 | 05 - Success Champion Playbook | Printed booklet for the Champion |
| Internal use | 06 - Framework Master Doc | Operational reference for Megan + future hires |
| Internal use | 07 - Framework Overview Flowchart | One-page visual of the entire system |
| Active engagements | 08 - Active Client Schedules | Status summary + working CSVs for current clients |

---

## Folder Contents

### 01 - Build Complexity Scorecard
**File:** `LuxeCraft_Build_Complexity_Scorecard.html`

Interactive HTML tool used at the end of Phase 0 to assign a Phase 1 engagement to a track. Twenty weighted criteria across three tiers. Auto-saves to localStorage. Generates a branded client-ready report. Print to PDF for inclusion in the Discovery & Review deliverable.

**When to use:** Run this after the Phase 0 audit, before the Discovery & Review call.

**Score bands:**
- 38-88 → Light Track
- 89-139 → Moderate Track
- 140-190 → Heavy Track

---

### 02 - Scope Confirmation Templates
**Files:**
- `LuxeCraft_Scope_Confirmation_Light_Track.md`
- `LuxeCraft_Scope_Confirmation_Moderate_Track.md`
- `LuxeCraft_Scope_Confirmation_Heavy_Track.md`

Three markdown templates (one per track) for paste-into-JobTread custom documents. Each defines what is included at that track level, what is universally out of scope, and what would trigger a track upgrade. Get this signed before Week 1 begins.

**When to use:** Week 0, after track is assigned. Customize the relevant template, paste into JobTread custom document builder, send for client signature.

---

### 03 - Implementation Roadmap Generator
**File:** `LuxeCraft_Implementation_Roadmap_Generator.html`

Interactive HTML tool. Inputs: client name, kickoff date, track. Outputs a branded vertical roadmap showing all 13 weeks with dates, themes, and color-coded categories.

**When to use:** Week 0, before kickoff meeting. Generate the roadmap, print to PDF, send to client.

---

### 04 - JobTread Schedule CSV Generator
**Files:**
- `LuxeCraft_JobTread_Schedule_CSV_Generator.html` (the generator)
- `Pre-Generated_CSVs/13_Week_Implementation_Light.csv`
- `Pre-Generated_CSVs/13_Week_Implementation_Moderate.csv`
- `Pre-Generated_CSVs/13_Week_Implementation_Heavy.csv`

Generator tool produces a JobTread-importable CSV with the parent group, twelve week sub-groups (each with a branded title), all weekly tasks, twelve Champion training sessions, three milestone invoices, and PREP subtasks for client coordination.

**Structure:** Each week is its own sub-group so weeks can be shared with the client at the group level without exposing internal subtasks.

**When to use:** Week 0 before kickoff. Either use the generator with the client's specific kickoff date, or use one of the pre-generated CSVs as a starting point and find/replace the dates.

**Before importing:** Add the client's Job ID to the Target ID column (left blank by default).

---

### 05 - Success Champion Playbook
**File:** `LuxeCraft_Success_Champion_Playbook.docx`

64-page brand-formatted Word document. Twelve chapters: Prep Week, Weeks 1-10, Closing Week. Includes the 10-tool toolkit appendix.

**Workflow:**
1. Upload to Google Drive → opens as Google Doc
2. Edit any client-specific sections if needed
3. Print to PDF
4. Mail in onboarding box, or share digitally

**When to use:** Week 0, given to the Champion at kickoff. They read one chapter per week alongside the engagement.

---

### 06 - Framework Master Doc
**File:** `LuxeCraft_Implementation_Framework.docx`

38-page comprehensive operational reference covering the entire Phase 1 framework. For internal use (Megan + future hires/contractors). Includes embedded screenshots of the scorecard, roadmap generator, CSV generator, and Champion Playbook cover.

**Sections:**
1. Overview & philosophy
2. The 13-week structure
3. The three tracks
4. The Build Complexity Scorecard
5. Build-out vs. rollout dynamic
6. The Rollout Playbook
7. The Success Champion role
8. Scope management & change requests
9. The deliverable system
10. Using the toolkit
11. Phase 2 transition

**When to use:** Onboard new contractors. Reference when you are unsure about a decision. Update when the framework evolves.

---

### 07 - Framework Overview Flowchart
**Files:**
- `LuxeCraft_Phase1_Framework_Overview.html` (interactive)
- `LuxeCraft_Phase1_Framework_Overview.pdf` (static, Moderate track)

One-page visual of the entire framework. Two-axis grid (weeks across, tracks down) showing the weekly call themes, Champion call themes, and milestone invoices. Includes the Rollout Playbook, the seven-tool deliverable workflow, and the three principles.

**Interactive features:**
- Track toggle: Light / Moderate / Heavy
- Hover any cell for full detail
- Export to PDF button (prints the currently-selected track)

**When to use:** Quick reference. Sales conversations. Onboarding new hires. Embedded in the Framework Master Doc as a visual table of contents.

---

### 08 - Active Client Schedules
**Files:**
- `Active_Client_Status_Summary.docx` (branded reference)
- `Active_Client_Status_Summary.md` (markdown for easier updates)
- `Grande_Construction_12Week_Schedule.csv`
- `True_Living_12Week_Schedule.csv`
- `RBA_Projects_12Week_Schedule.csv`
- `Haven_Valley_12Week_Schedule.csv`

Status summary and working JobTread schedule CSVs for each currently active engagement. The summary includes engagement start, owner, Success Champion, core and extended team, completed milestones, recent activity, and upcoming items for each of the four active clients.

**Note on framework alignment:** These four engagements were started before the new dependency-driven framework with branded titles was finalized. They are using the previous structure. Going forward, every new engagement will use the new framework from Phase 0 forward. The four current clients are grandfathered into the previous structure but can transition any week if it makes sense.

**When to update:** After every weekly meeting that results in completed milestones, new team members joining, or significant adoption events. The markdown version is easiest to edit; regenerate the docx from it when you want a fresh branded copy.

---

## Brand Standards

All client-facing deliverables follow the same brand standards:

**Colors:**
- Black (1A1A1A)
- Gold (B8935A)
- Cream (F5F1E8)
- Cream-darker (E8E4DC)
- Text gray (4A4A4A)

**Voice:** Warm but professional. "We" language for the company, except on the About page. No emojis. No em dashes. Direct and confident.

---

## Engagement Tier Reference

LuxeCraft offers four engagement tiers. This toolkit covers Phase 1 only.

- **Phase 0 — Discovery & Review:** Audit, scorecard, recommendation
- **Phase 1 — 12-Week Implementation:** This toolkit
- **Phase 2 — Legacy Builder Program:** Longer-term advisory
- **Support Lab:** Skool community membership (included with Phase 1 close)

---

*Let's build something that lasts.*

**LuxeCraft Consulting**
LuxeCraftConsulting.com
