Absolutely, Prajwal! Here's a **clear and simple description** of your project — perfect for your GitHub README, report, or even to explain in your video:

---

Project Title: Fetching Pharma Research Papers from PubMed

 Project Description:-

This Python program allows users to search for research papers from PubMed (a trusted database of biomedical research) using any topic or keyword they provide. But here's the special part:

It doesn't just fetch random papers.
It finds papers that include at least one author from a pharmaceutical or biotech company (like Aganitha Cognitive Solutions or Pfizer).  
This helps users **focus only on industry-related research**, rather than academic or university-only studies.

---

 What the Program Does:=

1. **Takes a search query** like "COVID-19 vaccine Pfizer".
2. **Connects to PubMed** and finds matching research papers.
3. **Analyzes the authors' affiliations** to find non-academic ones (like "Aganitha", "Inc.", "Solutions", etc.).
4. **Filters out purely academic papers**.
5. **Extracts important info**, including:
   - PubMed ID
   - Title
   - Publication Date
   - Non-academic Author(s)
   - Company Name(s)
   - Corresponding Author Email
6. **Saves all of this into a CSV file** so it’s easy to open in Excel or Google Sheets.

---

### 🛠 Features

- Supports **full PubMed query syntax** (e.g., "gene therapy Moderna").
- **Command-line support**: Accepts `--query`, `--file`, and `--debug` options.
- Uses **heuristics** to identify non-academic affiliations (e.g., ignores "University", keeps "Solutions", "Inc.").
- Clean and typed Python code with error handling.
- Packaged using **Poetry** and version-controlled with **GitHub**.
- Can be extended or reused for different biotech/pharma research needs.

---

 Output Example

Your CSV file might look like this:

| PubmedID | Title | Publication Date | Non-academic Author(s) | Company Affiliation(s) | Corresponding Author Email |
|----------|-------|------------------|--------------------------|--------------------------|-----------------------------|
| 12345678 | AI in Drug Discovery | 2023-11-02 | Dr. Smith | Aganitha Cognitive Solutions | smith@aganitha.ai |

---

  Useful

- Helps researchers find **industry-backed studies**.
- Saves time by **filtering out academic-only papers**.
- Useful for people working in **biotech, pharma, or health tech** industries.
- Can be automated or integrated into larger systems.

