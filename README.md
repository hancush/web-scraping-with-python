# Web scraping with Python

If you need data that's trapped on a website, writing some code to scrape the
page could be your solution. This entry-level class will show you how to use the
Python programming language to harvest information from websites into a
spreadsheet. We'll introduce you to the command line and show you how to write
enough code to fetch and parse web content.

**Workshop prerequisites:** This class is programming for beginners. Some basic
familiarity with Python and HTML is helpful but not required.

## Class outline

1. 🐍 [Python basics](session/01-python-basics.ipynb)
2. 🌐 [Working with web content](session/02-working-with-web-content.ipynb)
3. 🔢 [Writing tabular data](session/03-writing-tabular-data.ipynb)
4. 🛠 [Putting it all together](session/04-putting-it-all-together.ipynb)

## You will learn...

- Some Python basics
  - Data types: String, numeric, and Boolean types
  - Data structures: Lists and dictionaries
  - Control flow: `if... else` statements
  - Iteration: `for... in` statements
  - Functions: Reusable bits of code
- How to write and run Python code using Jupyter Notebooks
  - Retrieve web content with [`requests`](https://requests.readthedocs.io/en/master/)
  - Parse meaningful information from raw HTML with [`beautifulsoup4`](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  - Output tabular data with [`csv`](https://docs.python.org/3/library/csv.html)
- How to inspect source code in your browser
- How to go about getting unstuck

## Next steps

- [Install Python on your own machine](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit#)
- Learn how to manage Python dependencies yourself
- Keep writing simple scrapers!
  - 💡 For inspiration, check out [City Scrapers](https://github.com/City-Bureau/city-scrapers),
  a collection of scrapers that gathering information on public meetings,
  written by 60+ contributors of all skill levels
- Learn more precise HTML parsing approaches, e.g., [`lxml`](https://lxml.de/) and [`xpath`](https://devhints.io/xpath)
- Graduate to more complicated scraping tasks, e.g., scrapes that rely on state
  - 💡 For inspiration, check out [`python-legistar-scraper`](https://github.com/opencivicdata/python-legistar-scraper/),
  a Python library for scraping legislative data from the Legistar web interface
  and API

## Who am I?

👋 I'm Hannah! I apply my journalism background to civic technology projects as
a Lead Developer at DataMade. These include:

- Writing a web driver to fill out a branching, stateful web form in service of
lowering the barrier to completing a prerequisite to doing business with or
receiving funds from the City of Chicago
- Maintaining an inter-system scrape, transform, load (ETL) pipeline
for legislative data
- Managing millions of payroll and pension records to power the
[Illinois Public Salaries Database](https://salary.bettergov.org/) and the
[Illinois Public Pensions Database](https://pensions.bettergov.org/)
