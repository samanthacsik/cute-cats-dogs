# Materials for the August 3, 2023 NCEAS Roundtable

## Setup

This repository contains materials that accompany the talk/workshop, **Just enough CSS (and Sass) for data scientists** ([slides](https://samanthacsik.github.io/just-enough-css-sass/#/title-slide)).

If you'd like to follow along during the workshop, please be sure to complete the following: 

1. install [R](https://cloud.r-project.org/) and [RStudio](https://posit.co/products/open-source/rstudio/) – I’ll be using RStudio, though you may use alternative IDEs (e.g. VS Code) if that’s where you’re most comfortable
2. install [Quarto](https://quarto.org/docs/get-started/) – this may require updating R/RStudio if you already have those installed; Quarto now comes packaged with RStudio, so a separate install is not required if you're installing RStudio for the first time
3. grab workshop materials by either forking/cloning or downloading the repo. You can find instructions for both options, below:

- If you **don't** have git/GitHub configured: [Instructions for downloading the GitHub repository to work locally](https://github.com/samanthacsik/cute-cats-dogs/wiki/Download-the-GitHub-repository-to-work-locally)
- If you **do** have git/GitHub configured: [Instructions for forking & cloning a GitHub respository](https://github.com/samanthacsik/cute-cats-dogs/wiki/Forking-&-Cloning-a-GitHub-respository)

## What's in this repo?

```
.
|
├── practice-files/            # files for initial practice writing HTML and CSS
|  └── practice-html.html      # example HTML file
|  └── practice-markdown.qmd   # example markdown file
|  └── practice-styles.css     # a blank stylesheet for writing CSS, which will be applied to `practice-html.html` & `practice-markdown.md`
|
├── report/                    # files for building an example report
|  └── cuteness-report.qmd     # a Quarto markdown "report" to practice styling
|  └── images/                 # images of cute animals, which are rendered in `cuteness-report.qmd`
|  └── _extensions/            # a folder of Quarto extensions, which includes the Font Awesome Extension for rendering fa icons
|
├── README.md
├── .gitignore
└── cute-cats-dogs.Rproj
```

## Some cute cats & dog 

Because the README of any repo named `cute-cats-dogs` must include a photo of such.

![cute_fam](https://github.com/samanthacsik/cute-cats-dogs/assets/43836046/bac29c07-35ae-4a00-8ee4-c47c019dbe53)
