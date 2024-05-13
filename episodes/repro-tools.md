---
title: 'Tools for Reproducible Research Workflows'
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- What are reproducible research workflows?
- Which areas of the research process can be made more reproducible?
- What tools can improve reproducibility of research workflows?


::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- provide examples of reproducible research workflows
- list at least 4 different tools and practices for increasing research reproducibility
- demonstrate basic understanding of how to use selected tools for increasing research reproducibility


::::::::::::::::::::::::::::::::::::::::::::::::

## Starting with Reproducible Research Workflows

When we talk about research workflows we mean the sequence of processes through which researchers have to go to get to specific research outputs such as a dataset, analysis result or a publication. We can distinguish three main areas in the research process where workflows can be made more reproducible: 

1. Data acquisition and processing
1. Data analyses
1. Data reports (manuscripts)


![6 helpful steps for reproducible research](fig/image2copy.png)


## What tools are available out there?

Different tools can be used for increasing reproducibility depending on the specific phase of research process. Here is a list of some helpful tools for each of the three phases:

### Data acquisition and processing

Documentation is one of the most important 

Tools for documenting data acquisition and processing:

- README files (Templates, e.g. [https://data.research.cornell.edu/content/readme](https://data.research.cornell.edu/content/readme),
[Dataverse example](https://drive.google.com/file/d/1RHl-D79tZWC3nJJPrnvcgIQDHgmuH2Mk/view))
- Codebooks (Examples)
- Electronic Lab Notebooks (in-lab context)

### Data analyses

In the data analysis phase of the research process, the tools for making analyses more reproducible will differ depending on the methodology used, for example depending on whether researcher applies quantitative or qualitative methods in the study. Here is a list of some helpful tools depending on research methodology:

Quantitative methods:

- Programming languages for track-record and transparency of all steps: R, Python, Syntax from SPSS 
- Versioning: Git 
- Code quality checking and testing: [https://the-turing-way.netlify.app/reproducible-research/code-quality.html](https://the-turing-way.netlify.app/reproducible-research/code-quality.html) 
- Containers for freezing computational environment: [https://the-turing-way.netlify.app/reproducible-research/renv/renv-options.html](https://the-turing-way.netlify.app/reproducible-research/renv/renv-options.html) 
- Code capsules: [https://codeocean.com](https://codeocean.com) 
 
Qualitative methods: 

- Annotations (e.g. [annotation function in NVIVO](https://help-nv11.qsrinternational.com/desktop/concepts/about_annotations.html), ATI: [Annotation for Transparent Inquiry](https://qdr.syr.edu/ati))
- Active citation: [https://www.princeton.edu/~amoravcs/library/ps.pdf](https://www.princeton.edu/~amoravcs/library/ps.pdf)

### Data reports (manuscripts)

- R Markdown (fully reproducible manuscripts)
- Quarto (fully reproducible manuscripts)
- HackMD
- Overleaf
- Jupyter Notebooks

::: challenge

## Exercise

1. Take a look at the README file template that we listed in this lesson: https://data.research.cornell.edu/data-management/sharing/readme/ How could you help a researcher fill out a template like that? Which elements could you help most with?
2. What types of tools can be used for making qualitative analyses more reproducible? If you or a researcher don’t have access to these specific tools, could you think of other ways in which one could make qualitative analysis more reproducible using commonly available tools?


:::


::: keypoints

- Research workflows are sequences of processes that researchers have to go through to get to specific research outputs
- Data acquisition, data analysis and manuscript writing are three phases of the research process that can be made more reproducible
- There are many tools out there that can help make research workflows more reproducible


:::
