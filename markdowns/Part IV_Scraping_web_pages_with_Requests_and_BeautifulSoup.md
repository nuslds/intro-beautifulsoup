# Part IV. Scraping web pages with Requests and BeautifulSoup

In part III, we will create a reusable function that scrapes quotes from the website by stating the range of the pages. The outputs will be saved as CSV.

```python
# extract quotes from page 1 to 10
outputs = scrape_quotes(1, 10)
outputs.head()
```

| author          | author_url                                        | quote_text                                        | tags                                     |
| :-------------- | :------------------------------------------------ | :------------------------------------------------ | ---------------------------------------- |
| Albert Einstein | http://quotes.toscrape.com/author/Albert-Einstein | “The world as we have created it is a process ... | change;deep-thoughts;thinking;world      |
| J.K. Rowling    | http://quotes.toscrape.com/author/J-K-Rowling     | “It is our choices, Harry, that show what we t... | abilities;choices                        |
| Albert Einstein | http://quotes.toscrape.com/author/Albert-Einstein | “There are only two ways to live your life. On... | inspirational;life;live;miracle;miracles |
| Jane Austen     | http://quotes.toscrape.com/author/Jane-Austen     | “The person, be it gentleman or lady, who has ... | aliteracy;books;classic;humor            |



## The Steps

### Step 1. Inspecting the patterns

Try to be sensitive in observing different patterns before you write you codes.

In **Activity 3**, we will be figuring out the patterns of the URL of each page.



### Step 2. Enjoy Coding

Please go to the [Jupyter Notebooks on Binder](https://mybinder.org/v2/gh/nuslds/intro-beautifulsoup/master/) - Open the notebook `Part4_Scraping_Web_Pages_with_Requests_and_BeautifulSoup`.
