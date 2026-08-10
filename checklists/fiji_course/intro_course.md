(tutorials)=
# Introduction to course

This course shows in practice how to create a scientific image figure. It deliberately focuses on only the most critical items that affect whether a figure is legible and truthful. The condensed checklist below shows the covered items. 

For the complete set of recommendations, see the full [Checklists](https://doi.org/10.1038/s41592-023-01987-9). 

```{figure} ./intro_resources/condensed_checklist.png
:alt: In
:align: center
:name: figure-checklist

Condensed checklists. 
```

## Who this course is for

Any person who wants to process scientific images for visualization in image figures (e.g. scientific articles, posters, presentations).

This course assumes no prior knowledge of image processing. It uses the freely accessible, open-source tools [Fiji](https://fiji.sc/) and [Inkscape](https://inkscape.org/).

:::{note}

The content is created with microscopy images, specifically light microscopy in mind. The core principles are applicable to other scientific image domains. 

:::

## Course learning objectives

The overall course objective is to walk through creating one complete image figure from raw data, including the figure legend and the methods used to create and process the images.

After the course, the learner will be able to produce an image figure from an original microscopy image that truthfully and effectively reports the scientific result that the figure represents (see below).

```{figure} ./unit-3_resources/annotations/annotated_panel.png
:alt: In
:align: center
:name: annotated_image_result
:width: 100%

Example of an image figure with key annotations provided, such as a scale bar and content including the shown image colors. An enlarged crop is shown next to the overview to focus the viewer on a key result. The origin of the crop is annotated in the overview. Additional annotations, such as white arrowheads, are used to further guide the viewer.
```

### Overview of teaching units

The units follow the image processing workflow step by step: adjusting visibility and formatting in Fiji, preparing the figure in Inkscape, and finally describing the methods used for image processing and analysis. 

|  |Unit|Learning objective| Time |
|--|----------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------|
|1.|[Unit 1: Visibility](./unit-1_visibility.md)              |Process microscopy images in Fiji to clearly and accurately represent the underlying image content.        | 45 min|
|2.|[Unit 2: Format and annotations](./unit-2_format.md)      |Format microscopy images in Fiji (e.g., cropping and rotating) and add key annotations (e.g., scale bars). | 25 min |
|3.|[Unit 3: Figure and availability](./unit-3_figure_prep.md)|Complete scientific image figure using a vector graphics software, adding legible annotations, figure legends, and method descriptions|15 min|
|4.|[Unit 4: Quantification](./unit-4_analysis.md)            |Describe how quantitative image analysis should be documented to ensure transparency and reproducibility.  | 10 min |
|5.|[Further information](./intro_background.md)           | Further supplementary topics image processing ethics and image interpolation| |

Total time for course about 1-2 hours. Each teaching unit is self-contained and can be executed individually. The individual tasks performed in each unit can also be followed using the condensed checklist (see {numref}`figure-checklist`).

## Materials

For this tutorial you are going to need: 

- Fiji is just ImageJ (Fiji): [https://fiji.sc/](https://fiji.sc/) tested with Version ImageJ 2.18.0/1.54p; Java 21.0.7 (64-bit)
- Inkscape: [https://inkscape.org/](https://inkscape.org/) tested with v1.4.3


The course shown here contains all necessary image data as a download. Alternatively, the input, processed, and result images can also be downloaded from a [Zenodo repository](https://doi.org/10.5281/zenodo.19852464).

:::{note}

We selected Fiji and Inkscape because they are free, open source, and familiar to the authors. The underlying principles can be applied to other tools. 

We recommend to use the latest versions of these programs. 
:::

## Further material

Cheatsheets for creating image figures:

Schmied C. and Jambor HK. Effective image visualization for publications – a workflow using open access tools and concepts [version 2]. F1000Research 2021, 9:1373 ([doi: 10.12688/f1000research.27140.2](https://doi.org/10.12688/f1000research.27140.2))

Images for the examples were published here: 

Wolff C. et al. Morphological profiling data resource enables prediction of chemical compound properties. iScience 2025 ([doi: 10.1016/j.isci.2025.112445](https://doi.org/10.1016/j.isci.2025.112445))

## Help

If you need help write to the team on [image.sc](https://forum.image.sc/): [https://forum.image.sc/tag/quarep](https://forum.image.sc/tag/quarep). 

You can also reach out to the creator of this tutorial: [schmiedc](https://forum.image.sc/u/schmiedc) 