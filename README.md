Text Analysis Assignment

Objective

The objective of this assignment is to extract textual data from articles provided in a given URL and perform text analysis to compute specific variables. The details of the analysis and the variables are explained below.

Workflow

	1.	Input Preparation:
	•	Extract URLs from input.xlsx file.
	•	For each URL, extract the article text.
	•	Save each extracted article in a text file with the URL_ID as its file name.
	•	Ensure only the article title and text are extracted, excluding the website header, footer, and any other non-article content.
	2.	Text Analysis:
	•	Perform textual analysis to compute the following variables:
	•	POSITIVE SCORE
	•	NEGATIVE SCORE
	•	POLARITY SCORE
	•	SUBJECTIVITY SCORE
	•	AVG SENTENCE LENGTH
	•	PERCENTAGE OF COMPLEX WORDS
	•	FOG INDEX
	•	AVG NUMBER OF WORDS PER SENTENCE
	•	COMPLEX WORD COUNT
	•	WORD COUNT
	•	SYLLABLE PER WORD
	•	PERSONAL PRONOUNS
	•	AVG WORD LENGTH
	3.	Output:
	•	Save the computed variables in the exact order as given in the Output Data Structure.xlsx file.

Workflow Chart
┌─────────────────────┐
│ 1. Input Preparation│
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│Extract URLs from    │
│input.xlsx           │
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│Extract article text │
│from each URL        │
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│Save articles as     │
│text files with URL_ID│
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 2. Text Analysis    │
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│Compute variables:   │
│- Positive Score     │
│- Negative Score     │
│- Polarity Score     │
│- Subjectivity Score │
│- Avg Sentence Length│
│- % of Complex Words │
│- Fog Index          │
│- Avg Words/Sentence │
│- Complex Word Count │
│- Word Count         │
│- Syllables/Word     │
│- Personal Pronouns  │
│- Avg Word Length    │
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 3. Output           │
│Save variables in    │
│Output Data Structure│
│.xlsx file           │
└─────────────────────┘
Tools and Libraries

	•	Programming Language: Python
	•	Libraries: BeautifulSoup, Selenium, Scrapy (or any preferred Python libraries for data crawling)
 Output Variables

	•	All input variables from Input.xlsx
	•	The computed variables listed above

Output Format

	•	The output should be saved in the format provided in the analyzed_output.xlsx file.
	•	Save the output in CSV or Excel format.
