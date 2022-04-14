---
title: "Working with columns and sorting"
teaching: 5
exercises: 5
questions:
- "How do I move, rename or remove columns in OpenRefine?"
- "How do I sort data in OpenRefine?"
objectives:
- "Explain how to reorder, rename and remove columns"
- "Explain how to sort data in columns"
keypoints:
- "You can reorder, rename and remove columns in OpenRefine"
- "Sorting in OpenRefine always sorts all rows"
- "The original order of rows in OpenRefine is maintained during a sort until you use the option to Reorder Rows Permanently"
---

## Reordering & Renaming columns
You can re-order, delete, rename and move columns to the end, beginning left or right by clicking the drop-down menu, and choosing `Edit columns`

You can rename a column by opening the drop-down menu at the top of the column that you would like to rename, and choosing 'Edit column' > 'Rename this column'. You will then be prompted to enter the new column name.

## Sorting data
You can sort data in OpenRefine by clicking on the drop-down menu for the column you want to sort on, and choosing `Sort`.

Once you have sorted the data, a new `Sort` drop-down menu will be displayed.

Unlike in Excel, 'Sorts' in OpenRefine are temporary - that is, if you remove the `Sort`, the data will go back to its original 'unordered' state. The 'Sort' drop-down menu lets you amend the existing sort (e.g., reverse the sort order), remove existing sorts, and/or make sorts permanent.

## Global editing (all columns)

You may choose to perform transformations and edits in all columns at once for a faster clean-up by clicking the menu in the very first column of the dataset `ALL`. If you choose so, your chances will be apllied across all columns. If you are willing to remove a few columns and reorganize them, you should consider this feature to have a global view of the dataset.

> ## Organizing for more cleanup (DOAJ_big)
>
> Let's get rid of some columns we don't need. This will help us work a little faster.
>
> We will only keep 14 columns to this dataset. Aim for this order:
>
> * Journal title
> * Alternative title
> * Keywords
> * Subjects 
> * Publisher
> * Society or Institution
> * Added on Date
> * Country of Publisher
> * APC amount
> * Currency
> * Digital Archiving
> * Most Recent Article Added
> * Permanent Articles Identifiers
> * Journal license
>
> > ## Solution
> >
> > Instead of using the edit columns menu one by one. Select `ALL` in the first column, then, `Edit columns > Reorder/remove columns...`. Drag the ones you would like to remove to the right pane and re-order the ones you would like to keep. 
> {: .solution}
{: .challenge}
