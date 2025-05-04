# 🤝 Contribution Policy — pn-projects

_Last Updated: May 2025_

This **Contribution Policy** defines how contributors at all levels engage with pn-projects. It aligns fully with our [Constitution](../pn-projects_full_constitution.md), [Code of Conduct](../pn-projects_full_code_of_conduct.md), and [Promotion Framework](../pn-projects_promotion_policy.md). It ensures sustainable growth, mentorship, transparency, and a clear pathway from first PR to core leadership.

This document is **non-negotiable** and **central to membership evaluation**.

---

## 📌 Table of Contents

1. [Philosophy of Contribution](#1)
2. [Who Can Contribute](#2)
3. [Contribution Categories](#3)
4. [Standard Process for Open Source Contributions](#4)
5. [Project Team Contributions (Maintainers)](#5)
6. [Academic and Research Contribution Standards](#6)
7. [Technical Review Standards](#7)
8. [Code and Documentation Standards](#8)
9. [Recognition & Rewards](#9)
10. [Contribution Violations](#10)
11. [Amendments to This Policy](#11)

---

## 1. 🌱 Philosophy of Contribution <a name="1"></a>

Contributions are not just lines of code. They include:
- Suggestions and issue creation
- Documentation improvements
- Project proposal ideas
- Debugging and testing
- Mentorship and review
- Academic submissions
- Research direction support

We believe every contribution, when done with honesty and professionalism, moves our ecosystem forward. Our ladder of growth — from contributor to CMDO — is built on consistent, reliable contribution.

---

## 2. 🧑‍💻 Who Can Contribute <a name="2"></a>

| Role Type            | Contribution Access             |
|---------------------|----------------------------------|
| Public Contributor  | Open-source repositories only    |
| Verified Student    | Open-source + Academic (private) |
| Jr./Sr. Maintainer  | Assigned project scopes          |
| CMDO                | All areas + review rights        |
| Mentor              | Academic/Research consult only   |

Every contributor must abide by the Code of Conduct.

---

## 3. 🗂️ Contribution Categories <a name="3"></a>

### A. Code Contributions
- Feature development
- Bug fixing
- Refactoring

### B. Documentation Contributions
- README improvements
- Tutorials and onboarding guides
- Internal documentation for maintainers

### C. Infrastructure Contributions
- CI/CD setup
- Build scripts
- Tooling automation

### D. Academic Contributions
- Implementing or extending a college project under pn-projects
- Following submission and verification standards

### E. Research Contributions
- Proposing new topics (CMDO/Mentor only)
- Conducting experiments, reporting findings
- Co-authoring publications

### F. Management/Community Contributions
- Running onboarding events
- Reviewing PRs and mentoring newcomers
- Organizing discussions and votes

---

## 4. 🔁 Standard Process for Open Source Contributions <a name="4"></a>

1. **Fork** the repository
2. **Clone** your fork
3. **Create a feature branch**
   ```bash
   git checkout -b feature/<your-feature-name>
   ```
4. Make your changes
5. Run tests locally (where applicable)
6. **Write descriptive commit messages**
7. **Push your branch**
8. **Open a Pull Request (PR)** on GitHub
9. Request review from maintainers
10. Address comments and iterate

Your PR must be linked to an **open issue** (or open one before submitting).

---

## 5. 👥 Project Team Contributions (Maintainers) <a name="5"></a>

### Junior Maintainers Must:
- Ask questions and commit to learning
- Regularly pick issues from their assigned repo
- Track work in GitHub Projects/Issues
- Attend project standups and document progress

### Senior Maintainers Must:
- Create and manage issue lists
- Lead contributors on each project
- Ensure code coverage and documentation completeness
- Merge PRs only after review
- Submit monthly team reports to CMDOs

All maintainers must maintain **project hygiene**: label issues, close stale PRs, and archive inactive branches.

---

## 6. 🎓 Academic and Research Contribution Standards <a name="6"></a>

### Academic Contributions Must:
- Be documented with faculty sign-off (if for submission)
- Follow project template provided in `/docs/`
- Include academic intent in PR/issue comments
- Submit result PDFs or demos (if applicable)
- Be stored in **private repos** (CMDO assigned)

### Research Contributions Must:
- Be visible to CMDOs and Mentors only
- Have a problem statement, dataset (if applicable), and hypothesis
- Involve at least two reviewers (CMDO + Mentor)
- Include reproducible code and final reports
- Be stored under `/research/` with restricted access

Academic misconduct (plagiarism or falsified data) will result in permanent ban and notification to your institution.

---

## 7. 🧪 Technical Review Standards <a name="7"></a>

All contributions are reviewed for quality, relevance, and maintainability.

### Review Responsibilities by Role:
- **Junior Maintainers:** Can suggest changes but cannot approve merges
- **Senior Maintainers:** Can approve and merge with at least 1 peer or CMDO review
- **CMDOs:** Final authority for sensitive/critical repos

### Review Checklist:
- Code compiles and passes existing tests
- Follows repo’s folder and naming standards
- Comments and commits are meaningful
- README/docs are updated where needed
- Any linked issues are properly referenced and resolved

### Merge Rules:
| Repository Type | Required Reviewers |
|------------------|---------------------|
| Open Source      | 1 Maintainer (Sr/Jr) + 1 Peer Contributor |
| Academic         | 1 Maintainer + 1 CMDO or Faculty Mentor |
| Research         | 2 CMDOs + 1 Mentor |

No self-approvals. No force merges to `main` or `release` branches.

---

## 8. 📚 Code and Documentation Standards <a name="8"></a>

### Code Standards:
- Follow language-specific standards (C - MISRA optional, Python - PEP8, etc.)
- Modular code structure with reuse and abstraction
- No hardcoded credentials or keys
- Proper file headers, author tags, and license notices

### Documentation Must Include:
- Project README (purpose, setup, usage, contributors)
- Inline code comments and function docstrings
- API specs if project includes modules
- Markdown-based changelogs and contribution logs

Failure to document = incomplete contribution = cannot be merged.

---

## 9. 🏅 Recognition & Rewards <a name="9"></a>

### Contribution Acknowledgment:
- Weekly shoutouts via Discord + monthly GitHub recognition boards
- Name added to project `CONTRIBUTORS.md`

### Eligibility for Promotion:
- Must show sustained quality contributions (see [Promotion Policy](../pn-projects_promotion_policy.md))
- Must mentor at least one junior (for Sr. Maintainers and above)
- Participation in discussions, events, or reviews adds weight

### Badges & Certification:
- Badges issued per milestone: First PR, 10 merged PRs, First Review, etc.
- CMDO-signed certificates available on request post-semester cycle

---

## 10. 🚫 Contribution Violations <a name="10"></a>

Violation of this policy results in:

| Offense | First Time | Repeated | Severe Case |
|---------|------------|----------|--------------|
| PR without Issue/Docs | Warning | PR Closed | Project Ban |
| Plagiarism | Ban + Report | — | Ban + Institute Notification |
| Misuse of Admin Rights | Access Removal | Demotion | Expulsion |
| Harassment | Warning | Ban | Code of Conduct Sanctions |

All disciplinary actions will be logged and reviewed by CMDOs.

---

## 11. 🧾 Amendments to This Policy <a name="11"></a>

This document is a **living policy** reviewed every semester.

### Amendment Process:
- Proposals must be submitted via GitHub Discussions or Discord `#policy-suggestions`
- Must include rationale, affected sections, and proposed edits
- Reviewed and voted upon by CMDOs (70% quorum)

### Notification of Change:
- All approved changes published to `CHANGELOG.md`
- Notification sent to all active contributors within 48 hours

---

## 🧭 Final Notes

This policy protects both contributors and the project itself.

You are encouraged to:
- Ask questions
- Help each other
- Document your ideas
- Respect the review process

Together, we ensure pn-projects becomes a **benchmark in collaborative, ethical, and scalable engineering development**.

_For issues related to contribution policy enforcement or disputes, contact:_
📩 `team-prabodhnandini@proton.me`

