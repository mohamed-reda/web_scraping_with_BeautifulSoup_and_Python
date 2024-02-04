# Web Scraping with BeautifulSoup and Python - Project Repository

Welcome to the consolidated repository for three insightful web scraping projects using BeautifulSoup and Python. Each
project addresses distinct aspects of web scraping and serves as a valuable resource for understanding and leveraging
BeautifulSoup in different scenarios.

## Project 1: [Web Scraping with BeautifulSoup and Python](Web%20Scraping%20with%20BeautifulSoup%20and%20Python.ipynb)

### Overview

The third project provides a comprehensive guide to web scraping with BeautifulSoup. Covering essential topics like
parsing, navigation, handling attributes, and working with different filters, this guide aims to serve as a go-to
resource for web scraping enthusiasts.

### Key Features

- Introduction to BeautifulSoup and its purpose.
- Web scraping basics and different types of parsers.
- HTML and XML parsing examples.
- Navigation through HTML structure and attribute handling.
- In-depth coverage of filtering techniques with practical examples.

## Project 2: [BeautifulSoup with Filters - tom and Jerry Story](BeautifulSoup%20with%20Filters-tom%20and%20Jerry%20Story.ipynb)

### Overview

Project two involves parsing HTML content from a file named `TomJerry_Story.html` using BeautifulSoup. The emphasis is
on showcasing filters such as string, regular expression, list, and function for effective data extraction.

### Key Highlights

- Parsing HTML content from a local file.
- Utilizing string, regular expression, list, and function filters to extract relevant data.
- Examples demonstrating filtering techniques for various scenarios.

## Project 3: [Static Website Information Extraction](Static%20Website%20Information%20Extraction.ipynb)

### Overview

The first project centers around extracting information from a specific URL containing details on building static
websites. The focus is on utilizing BeautifulSoup to parse HTML and extract links based on various filters.

### Key Highlights

- Fetching webpage content using the `requests` library.
- Extracting links using BeautifulSoup and regular expressions.
- Demonstrating different filtering techniques to isolate specific links.

## How to Use This Repository

This repository is organized into three separate projects, each residing in its designated directory. Explore the
respective project directories to access detailed README files and source code for individual projects.

Whether you are a beginner seeking foundational knowledge or an experienced developer looking for specific insights,
each project is designed to cater to a diverse audience. Feel free to delve into the projects based on your interests
and requirements.

**Happy Web Scraping!**

------------

**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.