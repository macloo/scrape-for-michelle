# Scrape for Michelle

The challenge here was atrociously bad HTML. There were no tables, no lists, not even headings and paragraphs. Nothing but divs.

1. I inspected the code with Chrome Dev Tools and pulled out some samples in operationwearehere.html

2. Then I made a plan, seen in plan.txt

3. I used a Jupyter Notebook for everything from there onward. You can view it here on GitHub just by opening it. Jupyter Notebook gives us a way to code in Python and keep track of all our steps.

4. The final result is vets_animals.csv, a CSV file with 127 records.

The library used is [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/). It provides pretty much all the tools you need for scraping with Python.
