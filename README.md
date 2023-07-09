# AutoCharCard
Auto character cards for AI chats, 
to auto fill the character png files used in Text Generation Webui, SillyTavern, or characterhub

It reads a template character png and rewrite the character info using google search and chatgpt.

To use: lanuch the notebook 

It uses the following LangChain tools:
1. python_repl for a language model to run python script,
2. SerpApi: Google Search API

In theory, it can generates all sorts of character cards in json format, even DND character sheets.

To do next: improve the info scraping to get better character description from internet.

