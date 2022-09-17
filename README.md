# Prime_Ministerial_speech_analysis_webscraping
A report on how the importance of Indian Economy over time has changed in lieu of the Governments priorities through an analysis of PM Modi’s speeches and the number of times the word ‘Economy’ or ‘Economic’ is used.

Brief of methods used: Web scraping, BeautifulSoup4 library in Python, Jupyter Notebook environment for execution

The Idea/Algorithm:
1. A public webpage https://www.pmindia.gov.in/en/tag/pmspeech/?query containing the speeches of PM Modi was used.
2. Web scraping of HTML source code of main page provided link to speech page and date of speech.
3. Web scraping was used to extract only the actual text of the speech made. Done for last 50 speeches.
4. The number of times ‘Economy’ or ‘Economic’ was used in each speech was counted and stored along with the date of the speech.
5. A simple point plot was done with speech date on the x axis and ‘Economy’ word count on the y axis. The graph was analysed.
