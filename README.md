# Analyzing Twitter Conversations on “Wokisme” During the 2022 French Presidential Election

This project investigates how the term **"wokisme"** was discussed on **Twitter** and in **traditional media** during the 2022 French presidential campaign. It combines **sentiment analysis**, **network analysis**, and **media corpus comparison** to explore how the term is mobilized and framed in both digital and press ecosystems.

## 📅 Context

Between **March 5 and April 27, 2022**, we collected tweets and media articles mentioning *“wokisme”*, a term that became highly politicized in French public discourse. This period includes major campaign milestones: debates, rallies, and extensive media coverage.

## 🎯 Objectives

- Analyze the **volume, tone, and key actors** of Twitter conversations using R and Gephi.
- Compare Twitter discourse with content from **mainstream French media** using **Europresse.com**.
- Identify ideological and emotional framings through **sentiment and network analysis**.
- Understand how controversial terms circulate and polarize public opinion.

## 🛠️ Tools & Technologies

- **R** (`rtweet`, `tidytext`, `dplyr`, `ggplot2`, `igraph`, `textdata`)
- **Gephi** for network visualization
- **Twitter API** for tweet collection
- **Europresse.com** for press article extraction and analysis
- **Markdown** / **RMarkdown** for reproducible reporting

## 📊 Methodology

1. **Media Corpus Collection**  
   Articles were retrieved from **Europresse.com** using the keyword *“wokisme”*.  
   ➤ The term appeared in **3,248 articles**, mostly from **right-wing or far-right outlets**.  
   ➤ Sentiment analysis indicated a **strong negative tone** across the media corpus.

2. **Twitter Data Collection**  
   Tweets were extracted using the `rtweet` package and were used for network ans sentiment analysis.

3. **Network & Actor Mapping**  
   With `igraph` and Gephi, we mapped Twitter interaction networks to uncover influential users and polarized clusters.



