# MicroScope

## About

MicroScope is an RShiny and JavaScript (D3.js) software program designed to produce dynamic, interactive heatmaps in a web browser. MicroScope allows you to magnify any portion of a heatmap by a simple click-and-drag feature to zoom in, and a click-once feature to zoom out. MicroScope is designed with large heatmaps in mind (e.g., gene expression heatmaps with thousands of genes), where individual entries quickly become unreadable as more and more add up. However, MicroScope allows you to repeatedly zoom in to any sector of the heatmap to investigate a region, cluster, or even a single gene. You can scroll up and down the page of your web browser to see more genes than fit your window. MicroScope also allows you to hover the mouse pointer over any specific gene to show precise expression level details. As such, MicroScope presents a significant advance in heatmap visualization technology over current standard protocols. 

MicroScope is an ongoing bioinformatics software project fully financially supported by the United States Department of Defense (DoD) through the National Defense Science and Engineering Graduate Fellowship (NDSEG) Program. This research was conducted with Government support under and awarded by DoD, Army Research Office (ARO), National Defense Science and Engineering Graduate (NDSEG) Fellowship, 32 CFR 168a.

Current work is underway to expand Microscope's user-friendly features.

Please cite: "Khomtchouk et al.: 'MicroScope: magnifying interactive heatmaps using RShiny and JavaScript', 2015 (in preparation)" within any source that makes use of any methods inspired by MicroScope. 

## Installation

### Requirements

* R programming language
  * RStudio

## How to run

##### Git clone this repo to your computer, and in RStudio type:
* `setwd("~/path/to/my_directory/MICROSCOPE")`
* `install.packages("d3heatmap")`
* `install.packages("shiny")`
* `library(shiny)`
* Now go to ui.r and manually change `pwd<-"/path/to/my_directory/MICROSCOPE/genes_file.csv"` to your own file and path
* `runApp("microscope")`

## Screenshots

<img width="1440" alt="screen shot 2015-12-15 at 11 48 53 pm" src="https://cloud.githubusercontent.com/assets/9893806/11832500/c4bfa43e-a386-11e5-8d5c-4d869d6d904b.png">
