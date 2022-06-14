---
title: "Tabular Data & Spreadsheets"
teaching: 5
exercises: 0
questions:
- "Why is the focus on spreadsheets?"
- "What are spreadsheet drawbacks?"
- "How can spreadsheets be used in a research project?"
- "What other data exist that does not use spreadsheets?"
objectives:
- "Using spreadsheets appropriately in a research project, based on their pro and cons
keypoints:
- "Good Data Management pracitces for tabular data."
- "Working with a real life data example"
---

### Data organization and the data life cycle

Good data organization is the foundation of your research project and should already be part in the acquisition phase of a research project. 

<img src="../fig/data-life-cycle-acquisition.png" alt="data-life-cycle-acquisition" style="zoom:30%;" />

The structure and format of datasets can be planned and described in the data management plan of the project. Important to note that this is a living document and can be adjusted as you move forward. But it helps as a framework at the start. 

![dmp-data-organization](../fig/dmp-data-organization.png)

### Spreadsheet programs

Most researchers have data or do data entry in spreadsheets. Spreadsheet programs are very useful graphical interfaces for designing data tables and handling basic data quality control. 

Many spreadsheet programs are available. Since most participants utilize Excel as their primary spreadsheet program, this lesson will make use of Excel examples.

<img src="../fig/survey-results-tools.png" alt="data-types" style="zoom:25%;" />



NOTE: Excel is **proprietary software**, which means that it is owned by a company that is restricting the ways it can be used. A free spreadsheet program that can also be used is LibreOffice.

![libreoffice-excel](../fig/libreoffice-excel.png)

Commands may differ a bit between programs, but the general idea is the same.

> ## Exercise
> - How many people have used spreadsheets in their research?
> - How many people have accidentally done something that made them
> frustrated or sad?
{: .callout}

Spreadsheets encompass a lot of the things we need to be able to do as researchers. We can use them for:

- Data entry
- Organizing data
- Subsetting and sorting data
- Statistics
- Plotting

We do a lot of different operations in spreadsheets. What kind of operations do you do in spreadsheets? Which ones do you think spreadsheets are good for?


## Problems with Spreadsheets

Spreadsheets are good for **data entry**, but in reality we tend to use spreadsheet programs for much more than data entry. We use them to create data tables for publications, to generate summary statistics, and make figures.

Generating **tables for publications** in a spreadsheet is not optimal - often, when formatting a data table for publication, we’re reporting key summary statistics in a way that is **not really meant to be read as data**, and often involves special formatting (merging cells, creating borders, making it pretty). 

![publication-layout](../fig/layout-publication.png)

The latter two applications, **generating statistics and figures**, should be used with caution: because of the graphical, drag and drop nature of spreadsheet programs, it can be very difficult, if not impossible, to **replicate your steps** (much less retrace anyone else's), particularly if your stats or figures require you to do more complex calculations. Furthermore, in doing calculations in a spreadsheet, it’s easy to accidentally apply a slightly different formula to multiple adjacent cells. When using a  command-line based statistics program like R or SAS, it’s practically impossible to apply a calculation to one observation in your  dataset but not another unless you’re doing it on purpose. 

### Using Spreadsheets for Data Entry and Cleaning

However, there are circumstances where you might want to use a spreadsheet program to produce “quick and dirty” calculations or figures, and data cleaning will help you use some of these features. Data cleaning also puts your data in a better format prior to importation into a statistical analysis program. We will show you how to use some features of spreadsheet programs to check your data quality along the way and produce preliminary summary statistics.

In this lesson, we will assume that you are most likely using Excel as your primary spreadsheet program - there are others (gnumeric, Calc from OpenOffice), and their functionality is similar, but Excel seems to be the program most used by biologists and ecologists.

In this lesson we're going to talk about:

1. [Formatting data tables in spreadsheets](../01-format-data/)
2. [Formatting problems](../02-common-mistakes/)
3. [Dates as data](../03-dates-as-data/)
5. [Exporting data](../05-exporting-data/)

### Why aren't we teaching data analysis in spreadsheets

- Data analysis in spreadsheets usually requires a lot of manual work. If you want to change a parameter or run an analysis with a new dataset, you usually have to redo everything by hand. (We do know that you can create macros, but see the next point.)

- It is also difficult to track or reproduce statistical or plotting analyses done in spreadsheet programs when you want to go back to your work or someone asks for details of your analysis.

### Not all data is tabular

The focus of this class is tabular data. However, it is important to note that there are other data types out there such as documents, experimental data, fasta files, spectral counts, code, images, maps. 

<img src="../fig/other-data-types.png" alt="data-types" style="zoom:0%;" />







