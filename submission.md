# Project Submission Report

## 1. Student Details

- **Full Name:** Njuguna Quincy Kariuki
- **GitHub Username:** quincyjeff
- **Email:** quincy.njuguna@strathmore.edu
- **admission:** 166316

---

## 2. Deployed Project Link

- **Live GitHub Pages URL:** https://is-project-2026.github.io/portfolio-166316/

---

## 3. Reflection — Grounded in Your Git History

### A. Your Best Commit

- **Commit URL:** [https://github.com/IS-PROJECT-2026/portfolio-166316/commit/1500fead4248157d1f84348774cef73cbb72177c]
- **Why this one?**
  
  This commit follows the Conventional Commits specification, clearly describes the feature implemented, and represents a significant milestone in the development of my portfolio website.

---

### B. A Mistake or Struggle

- **Link to the evidence:** [https://github.com/IS-PROJECT-2026/portfolio-166316/commit/b96301634a0c383217755f95bc4402ad32ac2eee]

- **What happened and how did you recover?**

  While completing the assignment, I intentionally created merge conflicts to demonstrate conflict resolution. I reviewed the conflicting changes, manually resolved the conflicts, staged the corrected files, and completed the merge successfully.

---

### C. A Pull Request You're Proud Of

- **PR URL:** [https://github.com/IS-PROJECT-2026/portfolio-166316/commit/934af128d127b95fa38e3ed0f0f952e3be082ea9]

- **What did you check before merging?**

  I reviewed the modified files, confirmed that the website still functioned correctly and ensured there were no unnecessary changes before merging into the main branch.

---

### D. One Thing You Would Do Differently

- **What would you change?**

  If I restarted the project, I would plan my feature branches and project workflow more carefully before writing code. This would reduce unnecessary branch switching and make merge conflict management easier.

- **Link to the evidence of the original decision:** [https://github.com/IS-PROJECT-2026/portfolio-166316/commit/953576500e01507a60e1b3d6685f04d850da4612]

---

## 4. Screenshots of Key GitHub Features

### A. Milestones and Issues

<img width="1528" height="506" alt="milestones" src="https://github.com/user-attachments/assets/287b1b57-5bf8-43c7-9181-3f9aff15f740" />


The project was organized into milestones representing planning, development, testing, deployment, and documentation. Each milestone contained linked GitHub Issues that tracked individual tasks.

### B. Project Board

<img width="1907" height="357" alt="image" src="https://github.com/user-attachments/assets/fa27f9b7-f99f-4322-9e67-1c559965cdcb" />


The GitHub Project Board was used as a Kanban board to track issues through the To Do, In Progress, and Done stages during development.



### C. Branching Architecture

<img width="382" height="132" alt="branches" src="https://github.com/user-attachments/assets/121b4b70-b5de-434c-b363-0ad83e81687d" />


Development was carried out using separate feature branches following the required naming convention such as `feat/1-...`, `feat/8-...`, and `feat/11-...` before merging into `main`.



### D. Pull Requests & Traceability

<img width="1907" height="357" alt="pullrequest" src="https://github.com/user-attachments/assets/2ba7273a-b112-4904-ac6f-91cae91366ca" />


Each completed Pull Request was linked to its corresponding GitHub Issue using the `Closes #IssueNumber` convention, providing clear traceability.



## 5. Merge Conflict Evidence

### Conflict 1 — Full Chronology
<img width="1497" height="897" alt="conflict_evidence_1 png" src="https://github.com/user-attachments/assets/fbc83aea-265b-4eec-8801-4d233109ddea" />

**What cause did you use?**

Both branches modified the same line in the same file differently.

---

#### Step 1: Generating the Clash


Two feature branches modified the same line in `README.md`, causing Git to stop the merge because it could not determine which version should be kept.

---

#### Step 2: Inside the Code Editor (Conflict Markers)

Git displayed the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) to indicate the conflicting changes. I reviewed both versions and selected the correct final version before removing the markers.

---

#### Step 3: Resolution & Clean Merge

After resolving the conflict and committing the changes, the merge completed successfully and the repository history was clean.

---

### Conflict 2 — Different Cause
<img width="1497" height="897" alt="conflict_evidence_1 png" src="https://github.com/user-attachments/assets/1e106673-7a0a-405f-8c5e-94221c29cce5" />

**What cause did you use?**

Delete vs Modify Conflict.

**Why does this cause trigger a conflict?**

One branch deleted `contact.html` while another branch modified the same file. Git could not automatically determine whether the file should remain deleted or keep the modified version.

The conflict occurred because one branch deleted `contact.html` while another branch modified it.

---

### Conflict 3 — Different Cause
<img width="1906" height="970" alt="conflict_evidence_3 png" src="https://github.com/user-attachments/assets/2999c42f-c054-48de-8d91-c8f7325891b4" />

**What cause did you use?**

Rename vs Rename Conflict.

**Why does this cause trigger a conflict?**

Two branches renamed the same file to different filenames. Git could not determine which filename should become the final version, requiring manual resolution.

The conflict occurred because `projects.html` was renamed differently in two separate branche

## Final Submission

I confirm that my repository contains the completed project, GitHub Issues, Milestones, Project Board, Pull Requests, merge conflict evidence, GitHub Pages deployment, and all required documentation.
