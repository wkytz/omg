# Introduction

## Purpose
This document describes a set of requirements specified by the project OMG, a Web application for identifying gene expression differences, which can quickly obtain differentially expressed genes.

## Overview
This application has only one button to ¡°upload and go". We only need to upload a plain text file containing two samples of gene expression level, which contains two experimental conditions. After accepting the document, it will return a differentially expressed gene list and a scatter map of these genes, the X-axis is controlled and Y-axis is treated. If the uploaded file is invalid, it will return to a page and inform the user to provide the correct format.

## User characteristics
*  user:Scientists who obtain the results of gene expression.
*  Maintainer: Technicians with knowledge of Github and python.

## Terminologies
*  Treatment sample - a cell sample treated by special chemicals, or in which some genes
*  Control sample - A cell sample prepared in its normal condition.
*  Differentially expressed genes - The genes which have significantly different expression levels between two samples.
*  Up-regulation - A gene is said to be up-regulated if it has higher expression in treatment than in control.
*  logFC - log fold change of gene expression. log_2 [T/C].T is the gene expression level from a treatment sample, while C is the gene expression level from a control sample.