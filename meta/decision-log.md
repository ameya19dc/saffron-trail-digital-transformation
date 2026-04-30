# Decision Log

## About
- Decisions made during the engagement. Newest at the top.
- To answer why things were done the way they were.
- Absence of this file would lead to guesswork for reflection or a waste of time analysing.
- To have a solid dated record of reasoning, alternatives considered, and involvement of people in decision making.
- Creates accountability.

---

## YYYY-MM-DD — Short title of the decision

**Context:** What situation prompted this decision. 1-2 sentences.

**Options considered:** 
- Option A — brief description
- Option B — brief description  
- (Option C, etc., if relevant)

**Decision:** Which option was chosen.

**Reasoning:** Why this one. The tradeoffs accepted. 2-4 sentences.

**Revisit when:** (optional) A condition under which this should be 
re-examined. E.g., "if the engagement scope expands beyond Markdown work."

---

## 2026-04-27 — Single time-log file plus separate parking-lot file

**Context:** To keep track of time spent, check the chronology and reasoning of decisions made. 

**Options considered:** 
- time-log one file and parking-lot — To track the the time planned vs actual for every session in one file and have another file for logging extra questions to keep distractions away during the session.
- time-log multiple files — Each file would contain a fairly detailed breakdown of time spent in each session, with one goal being to check focus every 15 minutes.  


**Decision:** time-log single file and parking-lot.

**Reasoning:** Keeping everything in one file saves a lot of clutter. Also my goal is to evaluate what my estimation of task executing capabilities are vs what I can actually do. The other option requires putting a lot of overhead in time logging.

**Revisit when:** In 5-10 sessions see how this is working out.

---

## 2026-04-27 — Repository structure organized by engagement phase

**Context:** Setting up the project repo. Needed to decide how to organize 
top-level folders.

**Options considered:**
- By engagement phase (discovery, analysis, recommendations, deliverables)
- By artifact type (interviews, diagrams, reports, presentations)
- By stakeholder (Priya, Ramesh, Suresh, etc.)

**Decision:** Organize by engagement phase, with a separate /meta folder 
for project management artifacts.

**Reasoning:** Phase-based structure mirrors how the engagement actually 
flows over time and makes it easy for a reviewer to follow the work 
chronologically. Artifact-based would scatter related work across folders. 
Stakeholder-based would hide the analytical structure.

**Revisit when:** If a phase produces enough sub-types to need its own 
internal structure.

---

## 2026-04-27 — Used Node .gitignore template as starting point

**Context:** Needed a .gitignore for a primarily Markdown repo. GitHub 
offers language-specific templates.

**Options considered:**
- Empty .gitignore, add entries as needed
- Generic OS-only template (.DS_Store, Thumbs.db, etc.)
- Node template (broad coverage, mostly irrelevant to this project)

**Decision:** Started with Node template, but switched to empty .gitignore and added entries.

**Reasoning:** Defaulted to a familiar template under time pressure. 
Acknowledging this was not a careful choice — flagged for cleanup. Changing to an empty one and adding entries made it cleaner and easier to see why I was writing each line. Once I began removing entries, it seemed wiser to spend time on understanding which lines to put rather than which ones to remove.

**Revisit when:** Cleanup task on 2026-04-30.