# MEMELAND Kick-Off 2025 - Scientific Profile Presentation

Scientific profile presentation of Ondřej Mottl for the MEMELAND Kick-Off meeting 2025

## About

This presentation showcases the scientific profile of Ondřej Mottl for the MEMELAND project kick-off meeting. It covers his research focus, current projects, and his specific role within the MEMELAND project as Data Management advisor and main biodiversity dynamics analyst.

The presentation uses [Quarto](https://quarto.org/) and [Reveal.js](https://revealjs.com) to create an interactive scientific presentation.

## Setup

### Content Overview

The presentation covers:

1. **Research Focus**: Biodiversity patterns, big data methods, and open science
2. **Current Projects**:
   - **HOPE** (Humans on Planet Earth) - ERC Advanced Grant project
   - **BIODYNAMICS** - Spatio-temporal dynamics during the Holocene (GAČR funded)
   - **Functional Vegetation Paleoecology** - PRIMUS program at Charles University
   - **PalaeOpen** - COST Action for open palaeoecological data
3. **MEMELAND Role**: Data Management advisor, reproducible analysis pipelines, and main biodiversity dynamics analyst
4. **Tools & Databases**: VegVault, FOSSILPOL, RRatepol, and other open science tools

### Installation of Quarto

To install Quarto, follow the instructions on the [Quarto website](https://quarto.org/docs/getting-started/installation.html).

## Structure

The main presentation file is `presentation.qmd`, which contains:
- Dynamic content generation using R code
- Custom theming with Laboratory of Quantitative Ecology (LoQE) colors
- Interactive QR codes linking to relevant resources
- Rich media including images, logos, and scientific figures

Key supporting files:
- `R/00_Config_file.R` - Configuration and package management
- `custom_theme.scss` - Custom styling for the presentation
- `Materials/` - Images, logos, QR codes, and other presentation assets

### Theme & Branding

The presentation uses a custom theme (`custom_theme.scss`) based on the Laboratory of Quantitative Ecology (LoQE) color scheme:

The color palette includes:
- **Teal** - Primary accent color
- **Pistachio** - Secondary highlights 
- **Dark Green** - Main text and branding
- **Seal Brown** - Data and scientific content
- **Fulvous** - Special emphasis

The theme integrates LoQE branding with MEMELAND project requirements.

### Rendering

The presentation can be rendered locally using:

1. **R/RStudio**: Use the `R/render.R` script which handles proper configuration
2. **Command line**: 
   ```bash
   quarto render presentation.qmd
   ```
3. **IDE**: Use the Quarto extension in RStudio or VS Code

The R environment is managed through `renv` for reproducible package versions.

## Viewing the Presentation

- **Live presentation**: Available at the MEMELAND kick-off meeting
- **Online access**: GitHub Pages deployment (if enabled)
- **QR codes**: Embedded in the presentation for easy sharing and following along

## Dependencies

- [Quarto](https://quarto.org/) - Document publishing system
- [R](https://www.r-project.org/) - Statistical computing environment
- Required R packages (managed via `renv.lock`):
  - `here`, `qrcode`, `cropcircles`, `knitr`, and others

## MEMELAND Project Context

This presentation serves as Ondřej Mottl's introduction to the MEMELAND project team, outlining his expertise in:
- **Data Management**: DMP, PCP, and workflow documentation
- **Biodiversity Analysis**: Quantitative methods for biodiversity dynamics
- **Open Science**: Reproducible research practices and tool development
