---
title: "Exporting Transformed Data, Saving and Reusing Scripts"
teaching: 10
excercises: 0
questions:
- "How do I export transformed data?"
- "How do I export transformation scripts?"
- "How do I apply transformations using scripts?"
objectives:
- "Explain how to export data in different formats from OpenRefine"
- "Explain the process of exporting scripts"
- "Describe how to apply existing scripts to transform raw data"
keypoints:
- "You can export your data in a variety of formats"
- "You can reuse scripts for transformation you have performed for related datasets"
---

## Exporting Transformed Data
Once you have finished working with a data set in OpenRefine you may wish to export it. The export options are accessed through the ```Export``` button at the top right of the OpenRefine interface.

Export formats support include HTML, Excel and comma- and tab-separated value (csv and tsv). You can also write a custom export, selecting to export specific fields, adding a header or footer and specifying the exact format.

## Saving and Reusing Scripts

As you conduct your data cleaning and preliminary analysis, OpenRefine saves every change you make to the dataset. These 
changes are saved in a format known as JSON (JavaScript Object Notation). You can export this JSON script and apply it to other data files. If you had 20 files to clean, and they all had the same type of errors (e.g., species name misspellings, leading white spaces), and all
files had the same column names, you could save the JSON script, open a new file to clean in OpenRefine, paste in the script and run it.
This gives you a quick way to clean all of your related data.

1. In the `Undo / Redo` section, click `Extract...`, and select the steps that you want to apply to other datasets by clicking the check boxes. 
2. Copy the code from the right hand panel and paste it into a text editor (like NotePad on Windows or TextEdit on Mac). Make sure it saves as a plain text file. In TextEdit, do this by selecting `Format` > `Make plain text` and save the file as a `txt` file. 

Let's practice running these steps on a new dataset. We'll test this on an uncleaned version of the dataset we've been working with. 

1. Download an uncleaned version of the dataset: [https://ndownloader.figshare.com/files/7823341](https://ndownloader.figshare.com/files/7823341) or use the version of the raw dataset you saved to your computer.  
2. Start a new project in OpenRefine with this file and name it something different from your existing project (e.g., Testing-Transformations) 
3. Click the `Undo / Redo` tab > `Apply` and paste in the contents of `txt` file with the JSON code. 
4. Click `Perform operations`. The dataset should now be the same as your other cleaned dataset.

For convenience, we used the same dataset. In reality you could use this process to clean new related datasets from the same source or that keeps being updated for the same project. For example, data that you had collected over different fieldwork periods or data that was collected by different researchers (provided everyone uses the same column headings). 


> ## Can you guess what is the function of the `Permalink` next to the Project name (left-hand side)?
> The `Permalink` allows you to return to a project at a specific view state - that is, with facets and filters applied. The Permalink can help you pick up where you left off if you have to close your project while working with facets and filters. It puts view-specific information directly into the URL: clicking on it will load this current-view URL in the existing tab. You can right-click and copy the Permalink URL to copy the current view state to your clipboard, without refreshing the tab you’re using.  
{: .callout}
