# WMIC — Wellbeing, Mental Health, Inequalities & Choices

PhD research project website built with [Quarto](https://quarto.org) and hosted on GitHub Pages.

## 🌐 Live site
[https://a-depalma.github.io/WMIC](https://a-depalma.github.io/WMIC)

## 📁 Structure

```
WMIC/
├── index.qmd          # Homepage
├── project.qmd        # Project description
├── contact.qmd        # Contact form
├── team/
│   └── index.qmd      # Team page
├── publications/
│   └── index.qmd      # Publications list
├── resources/
│   └── index.qmd      # Downloadable resources
├── news/
│   └── index.qmd      # News & updates
├── styles.css         # Global styles
├── custom.scss        # Theme customisation
└── _quarto.yml        # Site configuration
```

## ✏️ How to update content

All pages are written in Markdown (`.qmd` files). To update a page:

1. Navigate to the file on GitHub (e.g. `news/index.qmd`)
2. Click the ✏️ pencil icon to edit
3. Make your changes
4. Click **Commit changes**
5. The site rebuilds automatically in ~1 minute

## 🎨 Customisation

- **Colours and fonts**: edit `custom.scss`
- **Navigation**: edit `_quarto.yml`
- **Styles**: edit `styles.css`

## 📬 Contact form

The contact form uses [Formspree](https://formspree.io). 
Replace `YOUR_FORM_ID` in `contact.qmd` with your Formspree form ID.
