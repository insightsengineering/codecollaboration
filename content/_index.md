## Collaborations across late stage pharma

Examples of presentations across pharma of open source: [pharmaverse](https://pharmaverse.org/) - [more pharmaverse](https://www.linkedin.com/feed/update/urn:li:activity:6900402808219414528/) - [R validation hub](https://www.pharmar.org/) - [NISS Meet-up](https://www.niss.org/news/niss-merck-meet-discusses-open-source-software-pharma-april-21-2021) - [GSK example 1](https://github.com/rinpharma/2020_presentations/tree/master/talks_folder/2020-Rimler-Clinical_Reporting_GSK.pptx), [example 2](https://www.youtube.com/watch?v=J3Tgn-bDHmE) - [J&J/Janssen example](https://www.youtube.com/watch?v=C2Suw5Trh0A) - [Roche example 1](https://www.youtube.com/watch?v=A8ePOTOSGg0), [example 2](https://github.com/openpharma/rinpharma_workshop_2021). [Merck example](https://www.linkedin.com/posts/yilongzhang_welcome-r-for-clinical-study-reports-and-activity-6854822261954883585-yL_B). 

We anticipate that Vendors, CROs and Academia will also play important roles in this major shift. In general, allowing Data Scientists to publish the great code that they write will increasingly be a major talent attraction factor ([a story for inspiration](https://www.gene.com/stories/the-paper)).

At Roche we are in the process of deploying a full R based GxP compliant Regulatory Reporting pipeline using collaboratively built components. Our long term vision is to use [containers](https://www.docker.com/resources/what-container) ([or other means](https://rconsortium.github.io/submissions-wg/pilot-overall.html)) to deliver interactive visualizations to give a vastly enhanced user experience for Health Authorities in their review. We expect that [Accumulus](https://www.accumulus.org/) will pave the way to achieve this globally and also anticipate that helpful changes will be implemented in the US by FDA’s New [Office of Digital Transformation](https://www.fda.gov/news-events/press-announcements/fda-advances-data-it-modernization-efforts-new-office-digital-transformation). The motivation behind all of this is to benefit the patients we aspire to help.

## Open sourced clinical reporting code collaborations

- [rtables](https://cran.r-project.org/web/packages/rtables/index.html) - an open sourced package offering groundbreaking table creation. 
    - rtables package enables creation of queryable output objects allowing the user to access all table content. Our intention is to [generate structured GxP relevant content](https://www.pharmexec.com/view/optimizing-pharma-content-for-faster-product-submissions) (for example parts of CSR body text) in an automated fashion using this functionality.
- respectables and synthetic.cdisc.data - open sourced packages to generate random CDISC data. 
- admiral - an open collaboration between Roche and GSK to derive ADaMs. 18 other pharma companies & CROs testing. Introduction video.
- NEST - a full exploratory/regulatory visualization and reporting suite. Collaboration is currently being formed.
    - NEST is fully modular allowing user to efficiently create flexible visualizations of data and also generate reproducible R source code with one click. NEST MMRM presentation (slides) NEW! Example apps: [Efficacy](https://genentech.shinyapps.io/teal_efficacy/) - [Safety](https://genentech.shinyapps.io/teal_safety/) - [Exploratory](https://genentech.shinyapps.io/teal_exploratory/) - (these apps are a small subset of available content)
    - Open sourcing of NEST components is being planned with timing depending on the formation of the collaboration.
    - Early presentation from 2019 of this toolkit at RStudio webinar [Part 3: Analyzing Clinical Trials Data using R for Decision Making and Regulatory Submissions](https://www.rstudio.com/resources/webinars/the-role-of-r-in-drug-discovery-research-and-development/) (part 3 starts at 25 minutes)
- Open sourced RNA-seq analysis R-package hermes. Available at Bioconductor. ([LinkedIn post with more information](https://www.linkedin.com/pulse/nest-presentation-biodata-world-daniel-saban%25C3%25A9s-bov%25C3%25A9/?trackingId=Pe3tP4k3XzZ0GwPQmCGHhw%3D%3D))
- [staged.dependencies](https://openpharma.github.io/staged.dependencies/) simplifies the development process for developing a set of interdependent R packages. Released as open source.
- The goal of [visR](openpharma.github.io/visr/) visR is to enable fit-for-purpose, reusable clinical and medical research focused visualizations and tables with sensible defaults and based on sound graphical principles. visR is a collaboration between Roche, Novartis, J&J and others.

## Talks about specific open sourced clinical reporting projects

* `Admiral | Roche, GSK, J&J` [Introducing {admiral}—The ADaM in R Asset Library | Thomas Nietmann, R/Pharma 2021](https://www.youtube.com/watch?v=N7Bw8c3D5fU)
* `rtables and tgen | Roche, Rstudio` [The gt Package: Past, Present, and Future | R/Pharma 2021](https://www.youtube.com/watch?v=LwP21KMV3MA)
* `visR | Roche, Novartis, J&J` [visR - a package for effective visualization in Pharma | R/Pharma 2020](https://youtu.be/JxvPBp2OhgA)

## General about open source or code collaboration in clinical reporting

* [Phuse CSS panel on Open Source in Clinical Data Science | James Black, PHUSE Computational Science Symposium 2021)](https://www.youtube.com/watch?v=cBSzQ4270F8/)
* [R/Pharma short talk on prioritising what R code to open source, and what notes on license choice helping collaboration discussions | James Black, R/Pharma 2021](https://rinpharma.com/publication/rinpharma_226/)
