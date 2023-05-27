# KeywordGPTCurator
# ArXiv Scholarly Article Finder
This script provides a tool to search for scholarly articles using the ArXiv API. The ArXiv is an open-access archive for scholarly articles in the fields of physics, mathematics, computer science, quantitative biology, quantitative finance, statistics, electrical engineering and systems science, and economics. The script takes user input for a search term, 
fetches articles related to the search term from the ArXiv API, and then generates a curated list of the articles using GPT-3 from OpenAI.

# Usage
Run the script and follow the on-screen prompts. You will be asked to input a term to search for related articles. The script will fetch articles related to this term from the ArXiv API and generate a list of these articles.

You'll need to set your OpenAI API key before running the script:
```
os.environ['OPENAI_API_KEY'] = 'your-openai-key'
openai.api_key = os.environ['OPENAI_API_KEY']
```

# Output
The script will print a curated list of articles from the ArXiv API related to the search term. This list includes the title, authors, and link for each article.
