# Social-Media and Text-Mining-Workshop with `R`
Workshop material on working with social media data and text mining methods in `R` 

Made with [`woRkshoptools`](https://github.com/StefanJuenger/woRkshoptools)

Part of the conference: [„Forschung zur Digitalisierung in der kulturellen Bildung“ ](https://www.dikubi-meta.fau.de/veranstaltungen/digitalisierung-in-der-kulturellen-bildung-whats-next/#sprungmarke2) (29-09-2022)

Contact: [Veronika Batzdorfer](https://www.gesis.org/institut/mitarbeiterverzeichnis/person/Veronika.Batzdorfer?no_cache=1) ([veronika.batzdorfer@gesis.org](mailto:veronika.batzdorfer@gesis.org))

---

# Background
Social media are central sites of collective opinion formation and form an important basis for describing and explaining social phenomena (e.g., online radicalisation). However, when working with this type of data, decisions in all phases of the research cycle (from data collection to pre-processing steps to analytical decisions) carry risks of bias for validity and reliability aspects.

# About
This workshop will include an introduction to how large amounts of text data from Twitter, which are openly available, can be made accessible and usable for research purposes. It will combine conceptual considerations and practical applications in `R`.

- Strategies to collect and process textual data with application programming interfaces (APIs) using common `R` tools. 
- Potentials of bias in the research data cycle
- Basics of natural language processing (NLP), data cleaning (e.g. with 'quanteda' or 'textclean') and application of common NLP tools for automated text analysis
 - Outlook on topic modelling (or word embeddings)
 - Bias and ethics in NLP

# Requirements
- Twitter data: [Kaggle Data Dump, Ukraine, "0729_UkraineCombinedTweetsDeduped.csv.gzip"](https://www.kaggle.com/code/josbenard/prepare-datasets/data?select=0729_UkraineCombinedTweetsDeduped.csv.gzip)
- Download & Installing `R` from: https://cran.r-project.org/
- Download & Installing `RStudio` from: https://www.rstudio.com/

- Dependencies
``` r
pkgs <- c("here", "lubridate", "quanteda", "quanteda.textstats", "tidyverse", 
"academictwitteR", "tibble", "kableExtra", "tidytext", 
"textclean", "academictwitteR")

install.packages(pkgs)
```


# Contents

<table class="table" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>

   <th style="text-align:left;"> Time </th>
   <th style="text-align:left;"> Content </th>
  </tr>
 </thead>
<tbody>
  <tr>
   
   <td style="text-align:left;color: gray !important;"> 09:00 - 10:30</td>
   <td style="text-align:left;font-weight: bold;"> 
Concepts &amp challenges when analysing social web data
    
 https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/1_1_analyse_social_web_data.pdf</td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 10:30 - 11:00 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Coffee break </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;"> 11:30 - 12:30 </td>
   <td style="text-align:left;font-weight: bold;"> Getting Started with Twitter data: (i) Sampling, (ii) Pre-processing/ data wrangling &amp (iii) Basics of textual analyses (frequencies/ co-occurences/ networks) 
    
  https://htmlpreview.github.io/?https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/2_1.nb.html </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 12:30 - 13:30 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Lunch </td>
  </tr>
  <tr>
  
   <td style="text-align:left;color: gray !important;"> 13:30 - 15:00 </td>
   <td style="text-align:left;font-weight: bold;"> Twitter Demo &amp; Crawling Social web data 
    
   https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/3_1_analyse_social_web_data.pdf
   </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 15:00 - 15:30 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Coffee break </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;"> 15:30 - 17:00 </td>
   <td style="text-align:left;font-weight: bold;"> Outlook Advanced NLP techniques (e.g., Topic Modeling) &amp; Social web data collection; Bias and Ethics with NLP
    
   https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/4_1_Ausblick.pdf
   </td>
  </tr>
</tbody>
</table>






[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/HEAD)


