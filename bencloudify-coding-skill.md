---
name: @BenCloudify-coding-skill
description: "GitHub profile skill from @BenCloudify. Use it when the task would benefit from mimicking this developer's repo choices, coding style, and implementation techniques."
---

### What they tend to build
- Cloud infrastructure and operations tooling, especially around AWS.
- Small, task-focused automation scripts rather than one large monolith.
- IaC/resources for solution-architect work plus a personal/portfolio site.
- Multi-account operational tooling: compliance checks, resource scans, and tagging workflows.

### Coding patterns to mirror
- Prefer clear, utility-first filenames that describe the job:
  - `*_iam_roles_reporter.py`
  - `*_ec2_port_scanner.py`
  - `*_resource_tagger.py`
- Organize features as separate scripts/modules per operation, not a generic framework first.
- Keep outputs operational and explicit: report, scan, tag, check compliance.
- Support multi-account AWS use cases when relevant.
- Use version markers in user-facing descriptions when introducing tools (`v1.0` style).
- If adding a new tool, a playful codename is acceptable, but keep the function obvious in the filename and README.

### Product and UI taste
- Strong preference for lightweight, badge-driven profile presentation.
- Friendly, personal tone with emoji and a direct greeting.
- Visuals lean toward colorful GitHub stats widgets and high-contrast themes (`radical`, `synthwave`).
- README structure is simple and scannable: intro, social links, skills, stats.
- Looks comfortable mixing practical architecture content with a personable, casual voice.

### Tech stack clues
- Primary language signal: **Python**.
- Also uses **JavaScript** and lists **HTML** in the profile.
- Cloud focus spans **AWS**, with exposure to **Azure** and **GCP**.
- IaC is a meaningful theme, though the exact tooling isn’t visible from the provided repo metadata.
- Works across **Windows**, **macOS**, and Linux distros; editor comfort includes **VS Code**, **Vim**, and **Notepad++**.
- Uses Git/GitHub heavily; profile README is built with Markdown + HTML image badges.

### When to inspect repos first
- Before editing `MySite`, `My-IaC`, or `BenCloudify`, inspect the repo structure first: the public evidence is mostly README-level, so framework and deployment conventions aren’t visible yet.
- Before adding shared utilities or refactoring AWS tools, inspect how credentials, account iteration, and CLI args are handled in the existing Python scripts.
- Before matching the visual style of the site/profile, inspect actual asset/layout files rather than assuming the badge-heavy README translates to the web app.
- If you need to extend the AWS tools, confirm whether the repo expects standalone scripts, shared helpers, or a package layout.

## Repo Map

- [BenCloudify/MySite](https://github.com/BenCloudify/MySite) (0 stars)
- [BenCloudify/AWS-Magic](https://github.com/BenCloudify/AWS-Magic): Automation tools for cloud operations on the AWS cloud platform. (0 stars, Python)
- [BenCloudify/BenCloudify](https://github.com/BenCloudify/BenCloudify): My (0 stars)
- [BenCloudify/My-IaC](https://github.com/BenCloudify/My-IaC) (0 stars)
- [BenCloudify/Dome9-V2-API](https://github.com/BenCloudify/Dome9-V2-API) (0 stars, JavaScript)

## How To Use This Skill

- Reach for this skill when the user asks for Ben's style, when the repo stack matches this person's ecosystem, or when studying their real code would reduce made-up output.
- Pick one or more relevant repositories from the list above based on the current task.
- Clone the most relevant repository or repositories into `/tmp` for temporary inspection.
- Study the implementation details, naming patterns, architecture, UI taste, and tooling choices there.
- Return to the main task and apply the useful patterns you observed instead of copying blindly.
- Treat the upstream repositories as reference material for style and technique, then adapt them to the current codebase responsibly.
