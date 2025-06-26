# Methodology

This study uses a feminist critical discourse analysis approach to examine how honour killings in Pakistan are linguistically framed in English-language news headlines and articles. The analysis combines both qualitative discourse methods and computational tools for text analysis.

## Data Collection

- **Corpus Size:** 50 news articles and headlines  
- **Time Frame:** 2016 to 2025  
- **Sources:** Leading English-language newspapers in Pakistan  
- **Selection Criteria:** Articles explicitly reporting on honour killings or related violence motivated by familial or societal ideas of "honour"  
- **Contextual Significance:** The starting year, 2016, was chosen because of the passage of Pakistan’s *Criminal Law (Amendment) (Offences in the Name or Pretext of Honour) Act*, enacted following the high-profile murder of Qandeel Baloch.

## Annotation and Preprocessing

- Articles were manually annotated using **Microsoft Excel** to record details such as:  
  - Age of victim  
  - Gender  
  - Relationship to perpetrator  
  - Stated motive (e.g., suspicion, affair, marriage choice)  
  - Method of killing  
  - Whether passive or active voice was used  
- Headlines were manually categorized based on **agency type**:  
  - Active (Male Subject)  
  - Passive (No Subject)  
  - Active (Female Subject)

## Tools Used

- **Python (spaCy, pandas):**  
  - Tokenization  
  - Lemmatization  
  - Part-of-speech tagging  
  - Frequency analysis  
  - Reading, cleaning, and updating Excel files

- **AntConc:**  
  - Concordance line analysis  
  - Cluster patterns (e.g., "family honour", "killed for honour")

- **Visualization (Matplotlib):**  
  - Bar and visualizing:  
    - Age distribution of victims  
    - Gender breakdown  
    - Victim-perpetrator relationships  
    - Stated motives  
    - Methods of killing  
    - Agency type distribution (Active/Passive)  
  - WordCloud for frequent term visualization

## Analytical Framework

- **Fairclough’s (1995) Critical Discourse Analysis model** — specifically focusing on the textual and social practice levels, which examine the vocabulary, grammar, and broader societal ideologies embedded in the text. The discursive practice level was not applied in this study.
- **Feminist linguistics**, particularly:  
  - **Sara Mills’** concept of **agency erasure**  
  - **Simone de Beauvoir’s** subject–object binary  
  - **Judith Butler’s** theory of gender performativity  
  - **Gayatri Spivak’s** notion of **epistemic violence**  
  - **Deniz Kandiyoti’s** idea of **patriarchal bargains**  
  - **Naila Kabeer’s** work on structural inequality and gendered vulnerability

## Limitations

- **Corpus size** is limited to 50 articles, which constrains the generalizability.  
- **Collocation analysis** was not applied due to corpus size; cluster and concordance patterns were used instead.  
- **Subjectivity** in manual annotation and classification was mitigated by consistent criteria but may still reflect researcher bias.

## Outcome

The methodological combination of linguistic annotation, discourse theory, and feminist frameworks allowed the project to highlight how language—particularly in headlines—normalizes, softens, or erases the severity of honour-based violence in Pakistan. The approach balances computational analysis with contextual feminist critique.
