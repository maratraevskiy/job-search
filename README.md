# Job Search Workspace

This repository manages the job search process. It uses a structured workflow to tailor resumes and cover letters based on master assets.

## Repository Structure

*   **`src/`**: Master assets — `resume-template.html`, `resume-template-ru.html`, `cover-letter-template.html`, `CV-Bullet-Points-Library.md`, `Instructions-Cover-Letters.md`.
*   **`applications/`**: Job-specific folders where you place `JD.md` and generate tailored application materials.

---

## How to Clone and Use Locally with Agents

1. Clone the repo:
   `git clone git@github.com:maratraevskiy/job-search.git`
2. Open the repo locally in your preferred coding agent environment.
3. Update the HTML templates in `src/` with your own resume content.
4. Prepare or adapt the bullet library for your profession.
5. Create a new folder inside `applications/` for the target role and add `JD.md`.
6. Use the prompt below with your local agent to generate the tailored resume and cover letter.

---

## How to Use This Repo with AI Tools

This repo works best with an AI tool that can read and edit files in a local folder.

Good options:

*   **Codex CLI**: Open a terminal, `cd` into this repo, then start Codex. This gives the agent direct access to the local files it needs to update.
*   **Claude Code**: Open a terminal, `cd` into this repo, then run `claude`. Claude Code is built for terminal-based work inside a local project folder.
*   **Codex app for macOS**: Use it if your workspace has Codex Local enabled. The app supports local workflows, but access can depend on your plan and workspace settings.
*   **Other local coding agents or IDE agents**: Use any tool that can read and edit the repo folder on your machine.

Less ideal options:

*   **Claude Desktop without local file tooling**: Use it only if you have a local desktop extension or MCP setup that lets Claude access local files.
*   **Web chat tools**: Use them only if you paste the needed files or upload them manually. They usually cannot update this local repo directly.
*   **Cloud agents**: Use them only after the repo is pushed to a connected GitHub repository. Cloud agents may not see uncommitted local files.

The key requirement is simple: the agent must be able to read from `src/` and write generated files into `applications/`.

---

## Prepare Your Templates First

Before tailoring applications, update the HTML templates with your base resume content.

The main templates are:

*   **`src/resume-template.html`**: English resume template.
*   **`src/resume-template-ru.html`**: Russian resume template.
*   **`src/cover-letter-template.html`**: Cover letter template.

You can give your agent your current resume as a PDF, another resume file, or pasted resume text. Ask the agent to rewrite the HTML templates while keeping the existing layout and structure.

Use a prompt like this:

"I want to personalize this job search workspace. Use my existing resume as the source and rewrite `src/resume-template.html` and `src/resume-template-ru.html` based on the current template structure. Keep the HTML layout, update the content, and preserve a one-page A4 resume format."

---

## Bullet Library First

Before tailoring resumes for a profession, create or adapt `src/CV-Bullet-Points-Library.md` so it reflects that profession well.

In some cases, you can use `src/bullet-points-prompt.md` to help generate the initial bullet library. This is useful when building a library for a new profession or profile, but it is not necessary for every profession.

---

> [!NOTE]
> You can find remote jobs via [@pronotify_bot](https://t.me/pronotify_bot).
 
---

## 🚀 How to Tailor for a New Job

Follow these steps when starting a new application:

### 1. Setup the Folder
Create a new folder in `applications/` named `YYYYMM-Company` and place the job description inside as `JD.md`.

### 2. Ask an AI Assistant to Craft Assets
Use this after your templates already contain your base resume content. Replace the folder name:

"I've added a new job description in `applications/YYYYMM-Company/JD.md`. Please:
1. First detect the language of `JD.md`.
2. If the JD is in English, use `src/resume-template.html`. If the JD is in Russian, use `src/resume-template-ru.html`. These templates already contain my base resume content. In all cases, use `src/CV-Bullet-Points-Library.md` to craft a tailored `[my-name] Resume.html` inside that folder, and keep the resume language aligned with the JD language.
3. For all written assets, match the output language to the JD language unless I explicitly say otherwise.
4. **Update the Skills section** to include technologies and core skills most relevant to the position in `JD.md`.
5. **Read every bullet in `src/CV-Bullet-Points-Library.md` in full**, then pick the **2-3 most relevant bullets** for each company (EmailMagnet and MonsterDeals). Do not rely on memory or partial reads — scan all categories before selecting. Ensure selected bullets directly correspond to the requirements in `JD.md` to demonstrate fit.
6. Use **clear, accessible language** (avoiding overly dense engineering jargon) to ensure it's understandable for non-technical HR recruiters while maintaining its professional impact.
7. Keep descriptions **concise** to ensure the resume remains a tight one-page A4 layout.
8. **Update the resume subtitle** to 'Product Manager | B2B SaaS | 0→1 & Growth | E-commerce & MarTech', adapting it slightly if needed based on the `JD.md` while maintaining the overall format and core focus areas.
9. Generate a tailored **`[my-name] Cover Letter.html`** using `src/cover-letter-template.html` as the base, following the instructions in `src/Instructions-Cover-Letters.md`. Keep the HTML template the same, but write the letter content in the same language as the JD. Ensure it is **concise and punchy** (roughly 1.5x shorter than standard)."
