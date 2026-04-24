# Cover Letter Creation Instructions

Use these instructions to generate brief, cozy, and high-impact cover letters for Marat Raevskiy.

---

## 1. Tone & Style
*   **Greeting:** Start with "Hey [Company Name] team!", "Hi [Name]!", or similar.
*   **Style:** Simple, cozy, and friendly. Avoid overly formal or corporate "robotic" language.
*   **Length:** **Extreme brevity is key.** Keep it ~2x shorter than a standard cover letter. Aim for 2-3 punchy paragraphs total. No "water."

---

## 1.5 Required JD Prioritization Workflow

Before writing a single sentence, do this in order:

1. **Read the full JD from top to bottom.**
2. **Extract the top 2-3 requirements** that are most central to the role.
3. **Rank them by importance** to the hiring decision, not by how easy they are to match.
4. **Cross-check each requirement against Marat's resume and `src/CV-Bullet-Points-Library.md`.**
5. **Only then draft the letter** using the highest-priority requirements with the strongest proof.

### Priority rules

- Lead with the **most role-defining requirements**, not broad generic themes.
- Do **not** default to filler themes like "B2B SaaS", "cross-functional delivery", "analytics", or "growth" unless they directly support one of the top-ranked JD requirements.
- If the JD is specific about domain or product shape, reflect that specificity in the letter.

### Bridge rule for partial matches

- If an important JD requirement is not a perfect 1:1 resume match, do **not** ignore it.
- Mention the requirement directly and connect it to the closest proven adjacent experience.
- Prefer **direct bridging** over generic relevance statements.
- Do **not** invent experience or overclaim exact domain depth that is not present in the resume.

---

## 2. Technical Requirements (HTML/CSS)

*   **Base template:** Always start from `src/cover-letter-template.html`. It has all fixes pre-applied.
*   **Font:** Keep the base template font stack as-is (`Arial, Helvetica, sans-serif`).
*   **No header block:** The HTML body must contain ONLY the letter text — greeting, paragraphs, and sign-off. Do NOT add a name heading, date, contact info, or any `.sender` / `.date` block.

---

## 3. Structure & Key Theses

### Phase 1: Representation (The "Who I Am")
Since the resume does not include a summary, the first paragraph must represent Marat's core professional identity.
*   **Required Points:**
    *   Name: Marat.
    *   Role: Project/Product Manager and UX Researcher (7+ years across product and UX).
    *   Core Strengths: Turning user insights into features; technical background (M.Eng.).
    *   Leadership Style: High ownership and excitement.

### Phase 2: The Job Match (The "Why Me")
Based on the specific Job Description, highlight **the two highest-priority JD requirements** where Marat has the strongest evidence.
*   **Action:** Bridge their most important needs to Marat's most relevant past results.
*   **Evidence rule:** Pick **one concrete result** from `src/CV-Bullet-Points-Library.md` per role. One sentence, one number. Do not summarise multiple bullets.
*   **Order rule:** The first requirement mentioned should usually be the one most likely to drive hiring interest.
*   **Specificity rule:** Name the actual requirement category when possible: platform strategy, wallet/payments ownership, merchant discovery, roadmap ownership, key metrics, MVP-to-scale, etc.

### Phase 3: Mission Resonance (The "Why You")
Include 1 sentence about why the company's mission resonates.

### Phase 4: Closing
*   Keep it simple: "If you agree that I could be a good fit, I'd love to chat at your convenience."
*   Sign-off: "Cheers, Marat".

---

## 4. Example Output (Condensed Style)

**Hey [Company Name] team!**

My name is Marat — I'm a Project/Product Manager and UX Researcher with 7+ years across product and user experience in B2B SaaS. I specialize in turning user and data insights into high-impact features, backed by a technical M.Eng. background in IT & Network Security. I lead with full ownership and genuine excitement for the product.

I'm drawn to this role because of your focus on **[top-ranked Requirement A]**. At [Previous Company], I **[one specific result with one number]**.

**[Company Name]**'s mission to **[Mission Statement]** resonates with my passion for **[connection]**. If you think I could be a good fit, I'd love to chat at your convenience.

Cheers,
Marat
