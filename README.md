# Google News Content Scrape and Analyze with Azure OpenAI Service (GPT-3)

This demo repository illustrates how to use Python to scrape news articles from Google based on a given keyword. The scraped articles are then processed by [Azure OpenAI Service (AOAI)](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview)'s [GPT-3 model](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/models#gpt-3-models), which generates concise summaries of the main points. The summaries are then formatted and sent via email using [MailJet](https://www.mailjet.com/) API.

This demo uses two Python libraries to scrape the latest news articles from Google and get their full text content. The first library is [GoogleNews](https://pypi.org/project/GoogleNews/), which allows us to search for news articles based on a keyword and get their titles and URLs. The second library is [Newspaper3k](https://pypi.org/project/newspaper3k/), which enables us to download the HTML pages of the articles and parse them to get their text content. For this demonstration, I decided to scrape the news about [GPT](https://en.wikipedia.org/wiki/Generative_pre-trained_transformer), a family of powerful natural language models developed by [OpenAI](https://openai.com/). This topic is very popular and hard to keep up with as normal humans, because there are so many new developments and applications of GPT every day.

This demo also shows how to use the [Natural Language Toolkit (NLTK)](https://www.nltk.org/) library to perform chunking, a technique that divides long articles into smaller segments based on linguistic cues. This allows us to overcome the 4000-token limit of GPT-3, which is the maximum number of words that it can process at a time.

![alt text](https://github.com/easonlai/google_news_content_scrape_and_analyze_with_gpt/blob/main/git-images/git-image-1.png)

Enjoy!

