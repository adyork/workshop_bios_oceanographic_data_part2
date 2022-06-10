---
title: "Downloading and Assessing a Dataset"
teaching: 10
exercises: 5
questions:
- "What do we decide what data to work with?  Does a dataset have the quality and metadata we need to analyze it?"
objectives:
- "Identify key aspects of data and metadata quality. Download a dataset and assess it."
keypoints:
- "Good data organization is the foundation of any research project."
---


### Assessing a Dataset

Let's take a look at an example Dataset Metadata Page at BCO-DMO. 

**Dataset: AE1910 CTD Profiles**: https://www.bco-dmo.org/dataset/774958

![AE1910_CTD_page1](../fig/AE1910_CTD_page1.png)

## Reviewing the metadata

Does the metadata include important context for using these data?  Does it indicate anything about the data quality? Is it preliminary or final?

Can you find information about what is in each data column?  What are the units?





> ## Exercise: Finding units
>
> Challenge: pulling month, day and year out of dates 
>
>
> Go to **Dataset: AE1910 CTD Profiles**: [https://www.bco-dmo.org/dataset/774958](https://www.bco-dmo.org/dataset/774958) which serves a data table.  
>
> Can you find which column(s) contain information about how deep the measurements were taken?
>
> What are the column(s) names?  
> 
> What are the units?
>
> > ## Solution
> > In the section called** "Parameters" **has this information.
> >
> > ![exercise vertical cols](../fig/AE1910_CTD_vertical_solution.png)
> > 
> > You can also see this information by viewing the data table with the <img src = "../fig/view_table.png"> button.  However since you don't have descriptions of the columns here, it is best to get the information from the "Parameters" section as shown above.
> > 
> > ![exercise vertical cols2](../fig/vertical_solution2.png)
> > 
> > {: .output}
> {: .solution}
{: .challenge}

## Downloading a Dataset

Instead of using the erddap server, you can download a whole dataset from the BCO-DMO landing page itself. There are buttons to easily download data in many file formats.

![AE1910_CTD bottle badges](../fig/AE1910_CTD_badges.png)
