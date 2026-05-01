# Decision Log

## About
- Decisions made during the engagement. Newest at the top.
- To answer why things were done the way they were.
- Absence of this file would lead to guesswork for reflection or a waste of time analysing.
- To have a solid dated record of reasoning, alternatives considered, and involvement of people in decision making.
- Creates accountability.
- Check out the template in the decision-log-template.md file.

---

## 2026-05-01 — Created a current-understanding.md file as the running record of what I know about the client.

**Context:** What I know and what my character in the simulation knows are two different things.

**Options considered:** 
- A: To have no record and just do this mentally.
- B: To record my understanding by citing sources available at the time in the simulation.


**Decision:** Option B

**Reasoning:** Maintains honest separation between known facts,
hypotheses, and open questions throughout discovery. Prevents
over-claiming in stakeholder conversations and provides a
chronological trail of how my understanding evolved. Mirrors a real
consulting hygiene practice.

---

## 2026-04-30 — Kickoff response second draft

**Context:** I had to decide whether or not to make a second draft of the kickoff response email after Claude's review

**Options considered:** 
- A: Continue with draft 1.
- B: Make a better second draft but spend a lot of extra time.


**Decision:** Option B

**Reasoning:** I treat this as a serious project and also a learning opportunity. Creating a first draft makes me think on my own how I want to respond. The review exposed significant flaws in the first draft and also suggested refinement. I feel that writing a better one shows me my ability to understand critique as well as apply it and grow.

---

## 2026-04-27 — Not using Claude Agent for the first phase of the engagement

**Context:** Whether or not to use Claude Agent to do my tasks 

**Options considered:** 
- A: Use Claude Agent all the way through the engagement.
- B: Use it in a later phase where programming and quantitative analysis is required.  


**Decision:** Option B

**Reasoning:** The more time I spend reading and struggling with the project and manually taking help from Claude as my mentor, I expect to learn more and build confidence for future real life settings which option A would not.

**Revisit when:** When the first phase is complete.

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