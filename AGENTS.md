# Project Agent Context

> **IMPORTANT NOTE**: This file must be maintained in English at all times. Do not translate to Chinese or any other language.

## Project Overview

This repository is a minimal job application template workspace for Marat Raevskiy. It contains only the reusable assets needed to tailor resumes and cover letters for new roles.

**Project Type**: Non-code project (documentation and HTML template workspace)

**Primary Purpose**: Shareable resume and cover letter template repository

---

## Directory Structure Overview

```text
job-search/
├── src/                   # Shared resume and cover letter assets
├── applications/          # Empty working folder for job-specific application folders
├── README.md              # Workflow overview and reusable prompt
└── AGENTS.md              # This file
```

### Directory Details

#### `src/`
Stores the shared source materials used to create tailored application documents.

**Core Files**:
- `resume-template.html` - Base HTML resume template
- `resume-template-ru.html` - Base HTML resume template for Russian-language applications
- `cover-letter-template.html` - Base HTML cover letter template
- `Instructions-Cover-Letters.md` - Rules for generating cover letters
- `CV-Bullet-Points-Library.md` - Master bullet library for resume tailoring

#### `applications/`
Stores job-specific working folders. Keep this directory in the shared repository, but keep it empty until creating a new application.

---

## Workflow & Usage Guidelines

### 1. Resume Creation Process

When creating a tailored resume:

1. Create a folder in `applications/` named `YYYYMM-Company-Role`.
2. Add the target job description as `JD.md`.
3. Read the target `JD.md`.
4. Choose the appropriate resume template from `src/`.
5. Read all bullets in `src/CV-Bullet-Points-Library.md` before selecting the strongest options.
6. Tailor the summary, experience bullets, and skills to the role.
7. Keep the final resume concise enough for a one-page A4 layout.

### 2. Cover Letter Creation Process

When creating a tailored cover letter:

1. Use the same application folder inside `applications/`.
2. Start from `src/cover-letter-template.html`.
3. Follow `src/Instructions-Cover-Letters.md`.
4. Keep the letter concise, specific, and aligned with the job description.

### 3. Prompt Usage

Use the reusable prompt embedded in `README.md` when asking an AI assistant to produce tailored application assets.

---

## Resume Content Best Practices

**Work Experience Bullet Points**:
- Keep bullets short and specific
- Prefer achievements and measurable outcomes
- Select only the bullets that best match the role

**Skills Section**:
- Reorder skills based on the job requirements
- Put the most relevant domain or technical skills first

---

## Candidate Information

**Name**: Marat Raevskiy
**Email**: marat.raevsky@gmail.com
**Phone**: +39(378) 060-7397
**LinkedIn**: https://www.linkedin.com/in/mraevskiy/
**WhatsApp**: http://wa.me/+77054483348
**Location**: Spain

**Professional Background**:
- Role: Senior Product Manager
- Education: Saint Petersburg University of Telecommunications, Master of Engineering (IT & Network Security)
- Core Skills: Product Management, API Integrations, Data Analysis, AI/LLMs, Systems Architecture

---

## Important Notes

1. Reuse the existing templates instead of creating new layouts from scratch.
2. Read the full bullet library before selecting tailored bullets.
3. Keep this repository limited to reusable, shareable assets.
