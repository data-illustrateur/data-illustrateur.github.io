---
title: "Prepare and Import Your Data"
description: "We do not use cookies and we do not collect any personal data."
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "data"
weight: 20
toc: false

---

Data Illustrateur currently supports tabular data formatted as csv ([comma-separated values](https://en.wikipedia.org/wiki/Comma-separated_values)) files, with the assumption that the first row contains the column names.

The same dataset can have a long format and a wide format. For example, Table 1 shows the 2012 Summer Olympic medal table dataset in the long form. Table 2 shows a wide form of the same dataset, where each of the medal type values (Gold, Silver, Bronze) is a column.

<!-- {{< img-simple src="long-wide-form.png" width="700px" alt="Long vs. wide data format" caption="" class="border-0 mx-auto text-center" >}} -->

{{< figure src="long-wide-form.png" width="650px" alt="Long vs. wide data format" caption="" class="border-0 mx-auto text-center" >}}

The current version of Data Illustrateur supports the long format. Wikipedia has a high level explanation of the [differences between long and wide forms of data](https://en.wikipedia.org/wiki/Wide_and_narrow_data). For a more technical discussion, refer to Section 3 of ["Tidy Data"](http://vita.had.co.nz/papers/tidy-data.pdf) by Hadley Wickham.

<!-- To import a dataset, click the "Open Dataset File" button in the variables pane. Data Illustrateur provides a collection of sample datasets with a short description for each file. Many of these sample datasets are used in the demo videos on [the Gallery page](/gallery). You can open a sample dataset and follow the corresponding demo video to re-create the visualization. -->

To import your own dataset, click the "Import Data" button in the Data Panel, and choose your file in the dialog. Data Illustrateur parses the data file, infers the data type for each column, and displays the column names and summaries in the Data Panel.