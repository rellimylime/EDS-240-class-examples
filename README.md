# EDS 240: Data Visualization & Communication - Class Examples

This repository contains code-along examples and lab exercises from EDS 240, a graduate-level course on data visualization and communication using R and the tidyverse.

## Author

Emily Miller 
MEDS 2026  
UC Santa Barbara

## Repository Structure

```
EDS-240-class-examples/
├── week1/
│   ├── data/
│   └── [code files]
├── week2/
│   ├── data/
│   └── [code files]
├── week3/
│   ├── data/
│   └── [code files]
└── ...
```

Each week's folder contains:
- `.qmd` files for lectures and labs
- `data/` subdirectory for datasets (gitignored)

## Key Tools & Packages

- `ggplot2` - data visualization
- `tidyverse` - data wrangling and manipulation
- `patchwork` - combining plots
- `palmerpenguins` - practice datasets
- `janitor` - data cleaning
- `here` - reproducible file paths

## Notes

- Data files are excluded from version control (see `.gitignore`)
- Weekly materials follow along with course lectures and labs
- Code examples focus on creating effective, communicative visualizations

## Data Access

All datasets used in this repository are stored locally in `week*/data/` directories and are not tracked by Git. Data sources include:

- `palmerpenguins` package (Palmer Station penguins data)
- FracFocus fracking registry data (downloaded from Google Drive)
- Additional datasets as assigned throughout the course

To replicate this work, download data files as instructed in weekly prep materials and place them in the appropriate `week*/data/` folder.

## Acknowledgements

Course originally developed by [Samantha Csik](https://github.com/samanthacsik)  
MEDS program at UC Santa Barbara Bren School of Environmental Science & Management

Course materials licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## License

This repository is for educational purposes as part of the MEDS program.