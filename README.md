# Web scraping with Python

If you need data that's trapped on a website, writing some code to scrape the
page could be your solution. This entry-level class will show you how to use the Python programming language to harvest information from websites into a
spreadsheet. We'll introduce you to the command line and show you how to write
enough code to fetch and parse web content.

**Workshop prerequisites:** This class is programming for beginners. Some basic
familiarity with Python and HTML is helpful but not required.

## Class outline

1. 🐍 [Python basics](session/python-basics.ipynb) (45 minutes to 1 hour)
2. 💧 Water break! (10 minutes)
3. 🔣 [HTML Basics](session/web-scraping-with-python.ipynb#HTML-basics) (15 minutes)
4. 🛠 [Scraping the web](session/web-scraping-with-python.ipynb#Web-Scraping-with-Python) (Remaining time)

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

Looking to expand on what you've done in this workshop? Here are some new adventures:

- [Install Python on your own machine and learn how to manage Python dependencies](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit?usp=sharing)
- Learn how to run your scripts from the command line
  - 💡 Check out [this tutorial)](https://first-web-scraper.readthedocs.io/en/latest/) to review the scraping concepts covered in this class *and* learn the basics of the command line
- Keep writing simple scrapers!
  - 💡 For inspiration, check out [City Scrapers](https://github.com/City-Bureau/city-scrapers),
  a collection of scrapers that gathering information on public meetings,
  written by 60+ contributors of all skill levels
- Learn more precise HTML parsing approaches, e.g., [`lxml`](https://lxml.de/) and [`xpath`](https://devhints.io/xpath)
- Graduate to more complicated scraping tasks, e.g., scrapes that rely on state
  - 💡 For inspiration, check out [`python-legistar-scraper`](https://github.com/opencivicdata/python-legistar-scraper/),
  a Python library for scraping legislative data from the Legistar web interface and API

## Credits

The content for this course was cribbed heavily from IRE's [one-hour course on web scraping with Python](https://github.com/ireapps/teaching-guide-python-scraping).

Some copy in the HTML basics section was lifted from the canonical (to me) [First web scraper tutorial](https://first-web-scraper.readthedocs.io/en/latest/), also developed for IRE. When you're ready to move from Jupyter notebooks into the command line, I'd strongly recommend starting with this workshop!

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
