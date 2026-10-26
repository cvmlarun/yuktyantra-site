# YuktYantra & Arun Patil Labs — Website & Research Repository

A clean, responsive static website and research publication suite for **YuktYantra** (a unit of **Arun Patil Labs**).

## File Directory & Structure

| File | Purpose | Description |
| :--- | :--- | :--- |
| `index.html` | Flagship Homepage | Main landing page: Applied AI systems overview, core programmes, and direct link to the 39-slide viticulture field study PDF. |
| `agrotech.html` | Farm AI & Viticulture | Precision agriculture field study in Kudari Salawadgi, Basavana Bagewadi taluk: 51-row block explorer, 4-phase protocol, and direct link to the field study PDF. |
| `internships.html` | Academic Fellowships | Research fellowship portal for B.Tech & B.Sc Horticulture students (3 tracks, applicant matrix, IP & safety terms). |
| `voice-ai.html` | Duplex Voice Lab | High-throughput speech-to-speech inference research, 80ms live frame animation, and GPU concurrency calculator. |
| `physical-ai.html` | Physical AI & Manipulation | Procedural grapevine pruning decision model, 10 domestic mobile manipulation challenges, and DPDP consent architecture. |
| `arunpatillabs-index.html` | Consulting Profile | Standalone personal consulting homepage for Arun Patil Labs (LLM inference, speculative decoding, computer vision). |
| `Grape_Growth_to_Raisin_ArunPatilLabs.pdf` | Field Study (PDF) | Complete 39-slide research document: 'From Vine to Raisin' covering the 173-day grape cycle, drying shed physics, and sensor telemetry. |
| `Grape_Growth_to_Raisin_ArunPatilLabs.pptx` | Editable Presentation | Full PowerPoint widescreen (16:9) presentation deck with editable slides, tables, and clickable links. |
| `CHANGELOG.md` | Revision Audit | Complete audit of all pre-publishing content corrections, Udyam registration alignment, and mobile responsiveness fixes. |

## How GitHub Serves the PDF Document
When you push this repository to GitHub and enable **GitHub Pages**:
1. All static files located in the root directory (or `/docs`) are automatically served on the web.
2. The PDF file (`Grape_Growth_to_Raisin_ArunPatilLabs.pdf`) is publicly accessible at:
   `https://<your-username>.github.io/<repo-name>/Grape_Growth_to_Raisin_ArunPatilLabs.pdf`
   (or on custom domain: `https://arunpatillabs.com/Grape_Growth_to_Raisin_ArunPatilLabs.pdf`).
3. In `index.html` and `agrotech.html`, the links `<a href="Grape_Growth_to_Raisin_ArunPatilLabs.pdf" target="_blank">` open the PDF directly in the browser's native document viewer or trigger a direct download.

## Local Testing
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000` to preview the homepage and test the PDF download link locally.
