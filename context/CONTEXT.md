# Algomise GitHub Organization Profile — Context Brief

> Last updated: 2026-06-25

---

## 1. Overview

GitHub Organization profile repository (`.github` repo) for the Algomise
organization. Displays a branded README at https://github.com/Algomise.

- **Repo**: `https://github.com/Algomise/.github.git`
- **Branch**: main
- **Total commits**: 3
- **Type**: Pure content repository (no build steps)

---

## 2. Structure

```
algomise-gihub/
├── README.md              Repo purpose description
├── profile/
│   ├── README.md          Organization profile content (renders on GitHub)
│   └── assets/
│       └── banner.svg     Branded header graphic (1280x380px)
└── .claude/
    └── settings.local.json
```

---

## 3. Profile Content

The `profile/README.md` contains:
- Branded SVG banner (constellation/data-network aesthetic)
- Tagline: "Intelligence, engineered."
- Mission: "Build intelligent systems that transform how businesses operate"
- Social media badges (Website, LinkedIn, X, Instagram, Facebook, Email)
- Capabilities: predictive models, data pipelines, optimization engines, automation
- Values: Precise, Confident, Accessible, Progressive, Trustworthy, Bold
- Tech stack badges: Python, PyTorch, TensorFlow, TypeScript, FastAPI, PostgreSQL, Docker, Kubernetes, AWS
- CTA: "Let's Algomise your workflow"

---

## 4. Banner SVG

- Dimensions: 1280x380px
- Gradient backgrounds (#0D0D2B → #2D1B69 → #0F3D2E)
- Stylized 'A' mark with node (purple-to-teal gradient)
- Wordmark: "algomise" in white, 68px bold
- Tagline: "INTELLIGENCE, ENGINEERED." in light purple

---

## 5. Notes

- No CI/CD workflows, no build config, no dependencies
- Content-only — edits go directly to Markdown + SVG
- Last modified: May 29, 2024
