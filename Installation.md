---
title: Installation & Setup
has_children: false
nav_order: 4
---

### Pre-Workshop Installation Instructions:

Go to [this website](https://datacarpentry.org/ecology-workshop/setup-r-workshop.html) and follow the instructions to install
  1. "Spreadsheet program" (unless you have Microsoft Excel installed already)
  2. OpenRefine
  3. R & RStudio

**Do not** install SQL. **Ignore** the "Data" section.

The "For everyone" section describes how to install R packages. Use the code below instead of the code they provide. we'll be using slightly different R packages. We do not need the `RSQlite` package.
```
install.packages(c("tidyverse", "rmarkdown", "tinytex"))
```

Note that the **`tinytex` package requires the latest version of R**. So if you already had R and/or RStudio installed, follow the instructions under the "If you already have R and RStudio installed" section. More installation instructions for the `rmarkdown` and `tinytex` packages can be found [here](https://bookdown.org/yihui/rmarkdown/installation.html) if needed.

**Test that the `rmarkdown` package installed correctly:**
1. Open RStudio
2. Navigate to `File` > `New File` >` R Markdown...`
3. A small window with the options Title, Author, and Default Output Format should open up. You should be able to select between HTML, PDF, and maybe Word output formats. Leave the default settings in place, and use whatever Title and Author info you'd like, then press OK.
4. A script should now open up (this is an R Markdown document). It will have a short header with title, author, date, and output fields. Find the `Knit` button at the top of the script and press it. You can select `Knit to HTML` or `PDF` if it asks. Provide a filename of your choice and press Save.
5. If a document is successfully exported to the save location you chose then R Markdown is working.

**Lastly**, make sure that you have the [most recent version of Zoom](https://support.zoom.us/hc/en-us/articles/201362233-Upgrade-update-to-the-latest-version) installed on your computer.
