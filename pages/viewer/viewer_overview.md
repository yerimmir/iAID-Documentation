---
title: Viewer Overview
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: viewer__viewer_overview.html
---

## Viewer Overview

After selecting data in PACS and pressing viewer button, the following screen appears.

### Details

<img src="images\viewer\viewer_overview\overview.png" />

#### Toolbar

The functions to help check the information of the medical image.

-   Series
-   Layout
-   SplitSeries
-   Pan
-   Zoom
-   Contrast
-   Measure
-   Link
-   Overlay
-   Info
-   FullScreen

#### Series Information

List the current study series in thumbnails.

## Viewport

DICOM files contain a lot of information stored in tags associated with the image. The most important data is overlaid on top of the image displayed, grouped in the corners. Depending on image modality, some fields may be missing.

<img src="images\viewer\viewer_overview\annotation.png" />

#### Top left

-   Number of displayed image and total number of loaded images
-   Series Number

#### Top Right

-   Patient Name
-   Patient ID
-   Patient Birth Date and Sex
-   Institution Name
-   Study ID
-   Study Description
-   Series Description

#### Bottom Left

-   Window level and window width (brightness and contrast), name of window preset, negative mode indicator
-   Thickness and location of the slice

#### Bottom Right

-   KVP
-   Date and time of image acquisition

#### Patient Orientation Information

If the DICOM image contains information about patient orientation in space, there is a letter (or combination of letters) symbolizing the patient’s sides displayed at the center of each panel's edge.

-   A - anterior
-   P - posterior
-   L - left
-   R - right
-   S - superior
-   I - inferior

#### Scale Information

If the DICOM image contains scale information (pixel spacing), two 10cm rulers with 1cm marks are displayed along left and bottom edges of the panel

<img src="images\viewer\viewer_overview\ruler.png" />

### How to load/unload Image

Drag and drop a thumbnail of the series into the viewport.
If you want to unload the image, right-click to unload it.

<img src="images\viewer\viewer_overview\context_menu.png" />

At this time, a warning message appears warning that the data will be deleted from the screen.

<img src="images\viewer\viewer_overview\message.png" width="200px" height="140px"/>
