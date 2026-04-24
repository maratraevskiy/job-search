# Job Search Workspace

This repository manages the job search process for Marat Raevskiy. It uses a structured workflow to tailor resumes and cover letters based on master assets.

## Repository Structure

*   **`src/`**: Master assets — `resume-template.html`, `resume-template-ru.html`, `cover-letter-template.html`, `CV-Bullet-Points-Library.md`, `Instructions-Cover-Letters.md`.
*   **`applications/`**: Job-specific folders where you place `JD.md` and generate tailored application materials.

---

## 🚀 How to Tailor for a New Job

Follow these steps when starting a new application:

### 1. Setup the Folder
Create a new folder in `applications/` named `YYYYMM-Company-Role` and place the job description inside as `JD.md`.

### 2. Ask an AI Assistant to Craft Assets
Use a prompt like this to get started (replace the folder name):

"I've added a new job description in `applications/YYYYMM-Company/JD.md`. Please:
1. First detect the language of `JD.md`.
2. If the JD is in English, use `src/resume-template.html`. If the JD is in Russian, use `src/resume-template-ru.html`. In all cases, use `src/CV-Bullet-Points-Library.md` to craft a tailored `Marat Raevskiy Resume.html` inside that folder, and keep the resume language aligned with the JD language.
3. For all written assets, match the output language to the JD language unless I explicitly say otherwise.
4. **Update the Skills section** to include technologies and core skills most relevant to the position in `JD.md`.
5. **Read every bullet in `src/CV-Bullet-Points-Library.md` in full**, then pick the **2-3 most relevant bullets** for each company (EmailMagnet and MonsterDeals). Do not rely on memory or partial reads — scan all categories before selecting. Ensure selected bullets directly correspond to the requirements in `JD.md` to demonstrate fit.
6. Use **clear, accessible language** (avoiding overly dense engineering jargon) to ensure it's understandable for non-technical HR recruiters while maintaining its professional impact.
7. Keep descriptions **concise** to ensure the resume remains a tight one-page A4 layout.
8. **Update the resume subtitle** to 'Product Manager | B2B SaaS | 0→1 & Growth | E-commerce & MarTech', adapting it slightly if needed based on the `JD.md` while maintaining the overall format and core focus areas.
9. Generate a tailored **`Marat Raevskiy Cover Letter.html`** using `src/cover-letter-template.html` as the base, following the instructions in `src/Instructions-Cover-Letters.md`. Keep the HTML template the same, but write the letter content in the same language as the JD. Ensure it is **concise and punchy** (roughly 1.5x shorter than standard)."
