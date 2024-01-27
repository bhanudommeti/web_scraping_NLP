# Web Scraping and Text Analysis README

## Data Extraction

For each article provided in the `Input.xlsx` file, the program extracts the article text and saves it in a text file. The filename is based on the 'URL_ID' of the article. The extraction ensures that only the article title and text are saved, excluding any website headers, footers, or extraneous content.

## Project Structure

- **Input.xlsx**: Excel file with the input data containing 'URL_ID' and 'URL' columns.
- **Output Data Structure.xlsx**: Excel file containing the results of the text analysis.

## Results Explanation

- **Positive_Score, Negative_Score, Polarity_Score, Subjectivity_Score**: Sentiment analysis scores for each article.
- **Avg_Sentence_Length, Avg_Words_Per_Sentence**: Average sentence length and words per sentence.
- **Fog_Index**: Readability metric calculated based on average sentence length and percentage of complex words.
- **Complex_Word_Count, Word_Count, Syllables_Per_Word**: Metrics related to word complexity and syllables.
- **Personal_Pronoun_Count, Avg_Word_Length**: Counts of personal pronouns and average word length.

## Troubleshooting

If you encounter any issues, carefully review the error messages and ensure a stable internet connection for web scraping. Confirm that the necessary Python libraries are installed.

Feel free to reach out with any questions or suggestions!
