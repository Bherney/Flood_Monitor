# <Project name>

<One sentence: what this project does, for whom, and where. If a reader
sees only this line, they should understand the project.>

**GeoDev Lab Africa, Cohort One.** <Your name>

---

## The question

> <Your spatial question, in one sentence. It should name a place, be
> answerable with data that exists, and have a point where it is done.>

## What's in here

```
<project-name>/
├── docs/
│   ├── 01-project-brief.md      Week 1
│   ├── 02-data-notes.md         Week 2
│   └── 03-data-preparation.md   Week 3
├── data/
│   ├── raw/                     downloads, not committed
│   └── processed/               outputs, not committed
├── scripts/
└── requirements.txt
```

## How to run it

```bash
git clone https://github.com/<your-username>/<project-name>.git
cd <project-name>

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

The data is not in this repository. Every source is linked in
[the project brief](docs/01-project-brief.md), so anyone can fetch it.

## Progress

- [x] Week 1, project brief with a source link for every dataset
- [x] Week 2, data downloaded, opened and described
- [x] Week 3, reprojected, clipped and quality checked
- [ ] Week 4, first spatial analysis, checked four ways

---

Temitope Waheeb · GeoDev Lab Africa

Learn. Build. Collaborate. Transform.
