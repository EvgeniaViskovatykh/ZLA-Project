# Introduction:
In this assignment, I delve into Zipf's Law of Abbreviation (ZLA), a statistical principle that describes the frequency distribution of words in natural language. To conduct this exploration, I've created three distinct datasets: two derived from song lyrics in English and German and one from non-fiction Russian texts obtained from the Gutenberg Project.

# Datasets:
Plain text file with RHCP lyrics from their albums "Californication" (1999) and "By the Way" (2002) and text file with Rammstein lyrics from albums "Mutter" (2001) and "Rammstein" (2019). The third dataset was a set of articles on Women's international movements edited in 1920 in Moscow.

# Text Processing:
All texts were processed with Spacy using a small English, German and Russian language model for each dataset; stop words and punctuation were removed, and some debugging was also done to clean the texts. 

# Dataframe Creation:
Pandas was used to create a DataFrame for further statistical analysis. Each word from the datasets was categorized by its frequency and length. This organization allows us to explore and visualize the distribution of words, clearly representing ZLA. 

# Objective:
This assignment aims to create visualizations that demonstrate the application of ZLA to the frequency and length distribution of words in the selected datasets. By plotting these distributions, we can observe how well the datasets adhere to the principles outlined by Zipf's Law, providing an understanding of the linguistic patterns within each corpus.

# Conclusion:
This assignment attempts to unravel the linguistic mysteries embedded in song lyrics and non-fiction texts. Using text processing techniques and statistical analyses, we aim to gain insights into the distribution of words and examine whether Zipf's law holds true in different linguistic contexts.
