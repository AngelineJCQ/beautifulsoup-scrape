# beautifulsoup-scrape
 Explore scraping with **BeautifulSoup**!

## Part One: Start from Shakespeare

As my professor is a poet (yes, and he teaches me data and database), he loves to give us assignments related to literature.

The start project with **BeautifulSoup** is scraping the first act of William Shakespeare's [The Tempest](http://floatingmedia.com/columbia/tempest.html).

My notebook is [shakespeare-scrape.ipynb](https://github.com/AngelineJCQ/beautifulsoup-scrape/blob/main/shakespeare-scrape.ipynb).

The code includes:
- cook a soup doc, or download the html text from a webpage
- search certain element like dic/p/ul, or certain attribute like class
- locate certain element by .parent or .find_next_sibling()

## Part Two: Develop with Supreme Court Decisions

In this case, I scrape the [2020 Supreme Court Decisions](https://www.supremecourt.gov/opinions/slipopinion/20).

The notebook is [guardian-and-supreme-court.ipynb](https://github.com/AngelineJCQ/beautifulsoup-scrape/blob/main/guardian-and-supreme-court.ipynb).

The code includes:
- use for loop to print each element in a list
- find the link hidden in the attribute
- save the output in a list of lists, even a three-deck list

## Part Three: More practice with The Guardian

The webpage I scrape is the [Best Non-Fiction Books of All Time](https://www.theguardian.com/books/2017/dec/31/the-100-best-nonfiction-books-of-all-time-the-full-list) listed by The Guardian.

The notebook is the same for [Part Two](https://github.com/AngelineJCQ/beautifulsoup-scrape/blob/main/guardian-and-supreme-court.ipynb)!

You will find a surprise if you get the soup doc of that website. Yes! An advertisement hidden in the html!

The code is similar to the last project, but there is more:
- list comprehension
- list of liiiissssst

## Bonus: More Real Shakespeare

In this case, I try to pull out the first 100 lines of Twelfth Night, available [here](http://floatingmedia.com/columbia/FolgerShakes/TN.html).

The notebook is the same for [Part Two](https://github.com/AngelineJCQ/beautifulsoup-scrape/blob/main/guardian-and-supreme-court.ipynb)!

It's indeed that my professor loves Shakespeare.

I had trouble with this project for a long time because it required each line to contain:

1. a code for act.scene.line along with whether is the stage direction
2. the speaker or the last person who spoke prior to the stage direction
3. a line or stage direction

I figured it out in a very complex way and I believe there is a better way to do it!


