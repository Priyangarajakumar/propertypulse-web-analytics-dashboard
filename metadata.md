
---

### Replace your metadata.md with this (copy-paste)

```markdown
# PropertyPulse — Project Metadata (Extended)

## Project Summary
PropertyPulse is an AI-assisted analytics project that models real-estate website performance (sessions, conversions, bounce, page engagement) and generates executive recommendations using LLMs. It is a portfolio-quality demonstration of end-to-end data analyst capabilities.

---

## Dataset (sample)
**File:** `data/sample_dataset.csv` (synthetic)  
**Period:** July–August 2025 (sample)  
**Rows (sample):** 90 daily aggregates (example repo contains 30–90 rows for demo)

**Schema**
- `date` (YYYY-MM-DD) — Date of the aggregate  
- `page` (string) — Page name or slug  
- `city` (string) — City name  
- `device` (string) — Mobile / Desktop  
- `sessions` (int) — Sessions count  
- `users` (int) — Unique users  
- `bounce_rate` (float) — Bounce % (no % sign)  
- `avg_session_duration_sec` (int) — Average session duration  
- `conversions` (int) — Contact / lead conversions  
- `top_keyword` (string) — Highest-performing search keyword

**Data license:** Synthetic sample — free to use for demo and learning.

---

## Tools & Libraries
**AI / LLMs**
- ChatGPT — cleaning, narrative & executive summary prompts  
- Gemini / Claude — secondary validation, alternative phrasing

**Analytics**
- Power BI Desktop — visuals and layout  
- Bolt.new — hosted dashboard generation  
- Google Sheets — light ETL & collaborative edits  
- Python (pandas) — optional programmatic cleaning

---

## Artifacts included
- `/assets/branding/PropertyPulseTheme.json` — Power BI theme JSON  
- `/assets/branding/logo.png` — project logo  
- `/dashboard/PropertyPulse_Dashboard_Screenshot.png` — screenshot  
- `/documents/PropertyPulse_Case_Study.pdf` — case study and reproducible steps  
- `/documents/Business_Recommendations.pdf` — prioritized recommendations  
- `/data/sample_dataset.csv` — demo dataset

---

## How to reproduce / notes
1. Load `data/sample_dataset.csv` in Power BI.  
2. Import theme JSON (Home → Switch theme → Import).  
3. Recreate visuals or use the screenshot in `/dashboard` as a layout guide.  
4. Use the pandas code in README to compute weekly aggregates if needed.

---

## Author & contact
**Priyanga Rajakumar** — Data Analyst (AI-assisted analytics)  
Email: your-email@example.com

---
