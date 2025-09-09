# Neural Networks & Deep Learning — Full Course

Hands-on deep learning course: build from scratch, train CNNs, and fine‑tune transformers. Autograded assignments included.

## 📦 What’s Here
- `assignments/` — A1–A4 specs, starters, solutions, tests
- `nbgrader/` — instructor autograding workflow
- `gradescope/` — ready-to-upload autograder zips (A2–A4)
- `slides/` — Reveal.js HTML decks + Master PPTX
- `marketing/` — thumbnails & social promo + trailer script
- `instructor/` — Instructor Guide PDF, platform CSVs, community setup, deploy guide
- `website/` — landing page ready for GitHub Pages/Netlify
- `requirements.txt`, `environment.yml`

## 🛠️ Setup
```bash
# Option A: conda
conda env create -f environment.yml
conda activate nn-dl-course

# Option B: pip
python -m venv .venv && source .venv/bin/activate  # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## ▶️ Start
```bash
jupyter lab
# open lessons or assignments in the notebooks
```

## 🧪 Autograding
- **nbgrader:** see `nbgrader/README.md` (release, collect, autograde)
- **Gradescope:** upload the zips in `gradescope/` to respective assignments

## 🌐 Landing Page
Deploy `/website` via GitHub Pages or Netlify. See `instructor/DEPLOY.md`.

## 📣 Community
Use the Discord/Slack templates in `instructor/` to run announcements, Q&A, and showcases.
