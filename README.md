# Text Analysis 

## Objective

The objective of this assignment is to extract textual data from articles given in the URL and perform text analysis to compute specific variables.

## Workflow

1. **Input:** URLs provided in `input.xlsx` file.
2. **Extraction:** Extract the article title and article text from each URL. Ensure only the article content is extracted (no headers, footers, or ads).
3. **Saving:** Save the extracted article in a text file named with the `URL_ID`.
4. **Analysis:** Compute the following variables for each article:
   - POSITIVE SCORE
   - NEGATIVE SCORE
   - POLARITY SCORE
   - SUBJECTIVITY SCORE
   - AVG SENTENCE LENGTH
   - PERCENTAGE OF COMPLEX WORDS
   - FOG INDEX
   - AVG NUMBER OF WORDS PER SENTENCE
   - COMPLEX WORD COUNT
   - WORD COUNT
   - SYLLABLE PER WORD
   - PERSONAL PRONOUNS
   - AVG WORD LENGTH

5. **Output:** Save the computed variables in the specified format as per `Output Data Structure.xlsx`.

## Variables

For detailed definitions and calculations of each variable, refer to `Text Analysis.docx`.

## Workflow Chart

```mermaid
graph TD;
    A[Start] --> B[Load URLs from input.xlsx]
    B --> C[Extract Article Title and Text]
    C --> D[Save Extracted Text as URL_ID.txt]
    D --> E[Compute Text Analysis Variables]
    E --> F[Save Results to Output Data Structure.xlsx]
    F --> G[End]
