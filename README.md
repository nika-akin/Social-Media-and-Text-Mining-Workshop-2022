# Social-Media und Text-Mining-Workshop mit `R`
Workshopmaterial zur Arbeit mit Social-Media-Daten und Text-Mining-Methoden in `R` im Rahmen der Tagung: [„Forschung zur Digitalisierung in der kulturellen Bildung“ ](https://www.dikubi-meta.fau.de/veranstaltungen/digitalisierung-in-der-kulturellen-bildung-whats-next/#sprungmarke2)


[Veronika Batzdorfer](https://www.gesis.org/institut/mitarbeiterverzeichnis/person/Veronika.Batzdorfer?no_cache=1) ([veronika.batzdorfer@gesis.org](mailto:veronika.batzdorfer@gesis.org))

---

# Beschreibung
Social-Media sind zentrale Orte der kollektiven Meinungsbildung und bilden eine wichtige Grundlage für die Beschreibung und Erklärung sozialer Phänomene (z.B., Online-Radikalisierung). Bei der Arbeit mit diesem Datentyp bergen Entscheidungen in allen Phasen des Forschungszyklus (von der Datenerhebung über Vorverarbeitungsschritten bis hin zu den analytischen Entscheidungen) allerdings Risiken der Verzerrung für Validitäts- und Reliabilitätsaspekte.

# Ziele
Dieser Workshop umfasst eine Einführung dazu, wie man große Mengen an Textdaten von Twitter, die frei verfügbar sind, erschließen und für Forschungszwecke nutzbar machen kann. Dabei werden konzeptionelle Überlegungen und praktischen Anwendungen in  `R` kombiniert.

- Strategien textuelle Daten mit Application Programming Interfaces (APIs) mittels gängiger `R`-Tools zu erheben und zu verarbeiten 
- Potenziale der Verzerrung im Forschungsdatenzyklus
- Grundlagen der natürlichen Sprachverarbeitung (NLP), Datenbereinigung (z.B. mit `quanteda` oder `textclean`) und Anwendung gängiger NLP-Tools zur automatisierten Textanalyse
 - Ausblick auf Topic Modelling (oder Word Embeddings)
 - Bias und Ethik im NLP

# Vorbereitung
- Twitterdaten von: [Kaggle Data Dump, Ukraine, "en_tweets_sample.pkl"](https://www.kaggle.com/code/josbenard/prepare-datasets/data)
- Download & Installierung R from: https://cran.r-project.org/
- Download & Installierung RStudio from: https://www.rstudio.com/

- Installieren der folgenden Pakete:

`install.packages(tidyverse)`
`install.packages(quanteda)`
`install.packages(tidytext)`
`install.packages(textclean)`
`install.packages(academictwitteR)`

# Inhalte--29-09-2022

<table class="table" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>

   <th style="text-align:left;"> Uhrzeit </th>
   <th style="text-align:left;"> Inhalt </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <
   <td style="text-align:left;color: gray !important;"> 09:00 - 10:30 </td>
   <td style="text-align:left;font-weight: bold;"> 
Konzepte &amp Herausforderungen bei der Analyse von Social-Web-Daten </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 10:30 - 11:00 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Kaffeepause </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;"> 11:30 - 12:30 </td>
   <td style="text-align:left;font-weight: bold;"> Getting Started mit Twitterdaten: (i) Sampling, (ii) Pre-processing &amp (iii) Grundlagen der Textanalyse (Häufigkeiten, Co-Occurences, Netzwerke)  </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 12:30 - 13:30 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Mittagspause </td>
  </tr>
  <tr>
  
   <td style="text-align:left;color: gray !important;"> 13:30 - 15:00 </td>
   <td style="text-align:left;font-weight: bold;"> Twitter Demo &amp; Exkurs Crawling Social-Web-Data </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;color: gray !important;"> 15:00 - 15:30 </td>
   <td style="text-align:left;font-weight: bold;color: gray !important;"> Kaffeepause </td>
  </tr>
  <tr>

   <td style="text-align:left;color: gray !important;"> 15:30 - 17:00 </td>
   <td style="text-align:left;font-weight: bold;"> Ausblick: Fortgeschrittene NLP-Techniken (z.B. Topic Modelling) &amp; Social-Web-Data-Collection; Bias und Ethik im NLP</td>
  </tr>
</tbody>
</table>

[Session1](https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/1_1_analyse_social_web_data.pdf)

[Session2](http://htmlpreview.github.io/?https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/2_1_getting_started.nb.html)

[Session4](https://github.com/nika-akin/-Social-Media-and-Text-Mining-Workshop-2022/blob/main/content/sessions/4_1_Ausblick.pdf)
