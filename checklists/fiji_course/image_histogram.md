(image_histogram)=
# Image histogram

Topics: intensity sampling, image quality, image histogram

## Motivation

A digital light microscopy image is a measurement of a biological object including its light intensity. Intensity measurement can be performed incorrectly and thus degrade the captured information.

In this mini tutorial, we discuss how to use image histograms to check whether a digital image has sufficient intensity-measurement quality for visualization.

## Key considerations

- Is oversaturation or clipping present at maximum intensity?
- Is the minimum signal properly sampled?
- Are there any intensity sampling artefacts?

## Introduction

Light microscopy images in life sciences represent a measurement of a biological object, for instance, a cell. In light microscopy, or more specifically for the example we use, fluorescent light microscopy, the cell is measured over:

- Space
- Time
- Fluorescent labels
- Intensity

The spatial dimension is represented as pixels in 2D or voxels in 3D volumes. The time dimension is present either as a single timepoint or as multiple frames in a timelapse. The fluorescent labels are represented as different channels.


```{figure} ./image_histogram_resources/sampling.png
:alt: In
:align: center
:name: sampling
:width: 100%

Illustration demonstrating sampling in space and intensity. (A) Illustration of a real object, e.g., a cell, with a smooth, continuous outline (i.e., analog). (B) A modern microscope samples this analog object (yellow grid lines) and transforms (digitizes) it into a digital representation, thus discretizing the space into pixels and the intensity into different gray values. (C) The sampled cell as a digital image; note the loss of spatial information due to the sampling.
```

```{admonition} Think about it
:class: tip

The above example is extreme to illustrate a point. However, image acquisition always means some loss of information. Can you think of why this is unavoidable?

:::

Finally, the light intensity that the microscope captures is represented as different shades of gray of each pixel or voxel.

This intensity measurement can be performed incorrectly, or the images can be processed incorrectly afterward, negatively impacting analysis and image visualization. For instance:

- The image can be oversaturated, clipping high intensities.
- The offset can be set incorrectly, cutting off minimum intensities.
- Image intensity can be resampled (e.g., converted to a lower bit depth), changing the intensity distribution.

We can check these artefacts using the image itself but often they are not easily visible.

We can use tools such as Histograms and line plots to easily spot these artefacts. 

## Histogram

Analyze > Histogram

Shows intensity distributions

### Intensity artfacts in Histograms

## Line plots

Click on line ROI 

Draw line ROI on images

Analyze > Plot Profile

### Clipping in line plot