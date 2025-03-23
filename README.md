# Advanced Thematic Analysis for UX Research

This project explores four modern approaches to thematic analysis tailored for UX research. From qualitative surveys and interviews to usability feedback, these techniques help scale the analysis without losing nuance.

## Methods Included

**1. Emotion-Based Sentiment Classification**  
Classifies user feedback using targeted emotion keywords instead of generic "positive" or "negative" categories. This helps surface nuanced feelings like frustration, confusion, delight, or relief.

**2. Theme Co-Occurrence Heatmap**  
Maps how common UX themes appear together across transcripts. Instead of isolated issues, you see networks of pain points to uncover root causes.

**3. Topic Modeling (LDA)**  
Automatically extracts themes using unsupervised learning (LDA). This is useful when analyzing large amounts of unstructured text like open-ended survey responses.

**4. MDS Visualization of Similarity**  
Uses multidimensional scaling to visually cluster participant feedback based on similarity. Great for spotting user groups, unique feedback patterns, and outliers.

## File Overview

- `Ux Thematic Analysis.Rmd`: Main RMarkdown script that runs all analyses and saves visualizations.
- `lda_topic_plot_better.png`: LDA topic visualization.
- `theme_cooccurrence_simulated.png`: Heatmap of theme connections.
- `sentiment_distribution_ux.png`: Sentiment category bar chart.
- `sentiment_wordclouds_ux.png`: Word clouds showing emotion-driven keywords.
- `mds_feedback_similarity_v2.png`: MDS scatter plot showing participant similarity.

## How to Run

1. Open `Ux Thematic Analysis.Rmd` in RStudio.
2. Install required packages (listed in the script).
3. Knit the document to generate visual outputs.

## Ideal Use Cases
- Post-interview/survey analysis
- Feedback from usability tests
- Open-ended responses in UX research
