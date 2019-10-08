# Part III. Extracting Data from HTML with BeautifulSoup

In Part III, we will create a reusable function to extract information below from the HTML strings of a single quote on [Quotes to Scrape](http://quotes.toscrape.com/).

| **Variable Name** | **Description**                                        |
| :---------------- | :----------------------------------------------------- |
| quote_text        | Text of the quote                                      |
| author            | Name of the author                                     |
| author_url        | URL of the author page, e.g. '/author/Albert-Einstein' |
| tags              | Tags that assigned to the quote                        |



## Steps

### Step 1. Inspecting HTML Elements

It is important to inspect the HTML elements before you write you codes to extract information from the HTML strings.



#### HTML Element

An HTML element usually starts with a **starting tag** and ends with a
**closing tag** in which the element name is prefixed with a slash.

Example: `<small>Albert Einstein</small>`

| Start  Tag &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Content         &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | End Tag &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| &lt;small>                                                   | Albert Einstein                                              | &lt;/small>                                                  |



#### Attributes

Attributes, placing inside the starting tags, define the characteristics
of HTML elements. An attribute is always a **name-value pair**.
Example: `<small class="author">Albert Einstein</small>`

| Tag Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Attribute&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Attribute Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Attribute Value&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| small                                                        | class="author"                                               | class                                                        | author                                                       |



Now let's complete **Activity 2** on the **Activity Sheet**. You will use the information you fill in the table when you code.



### Step 2. Enjoy Coding

Please go to the [Jupyter Notebooks on Binder](https://mybinder.org/v2/gh/nuslds/intro-beautifulsoup/master/) - Open the notebook `Part3_Extracting_Data_from_HTML_with_BeautifulSoup.ipynb`.





