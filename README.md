# News Headlines Web Scraper

## Objective

This project is a simple web scraper that fetches the latest news headlines from the BBC News website using Python. It uses the `requests` library to retrieve the webpage and `BeautifulSoup` to parse the HTML content. The extracted headlines are saved to a text file.

## Tools Used

* Python 3
* requests
* BeautifulSoup (bs4)

## Project Structure

```
Task3/
│── news_scraper.py
│── headlines.txt
│── README.md
```

## Installation

1. Clone or download the project.
2. Install the required Python libraries:

```bash
pip install requests beautifulsoup4
```

## How to Run

1. Open a terminal or command prompt.
2. Navigate to the project folder.
3. Run the Python script:

```bash
python news_scraper.py
```

## Output

* The script connects to the BBC News website.
* It extracts the available news headlines.
* The headlines are saved in a file named `headlines.txt`.

Example output in the terminal:

```
Headlines saved to headlines.txt
```

Example content of `headlines.txt`:

```
1. Top Stories
2. Latest World News
3. Business Updates
4. Sports Headlines
5. Technology News
```

*The actual headlines will vary depending on the latest news available when the script is executed.*

## Features

* Fetches live news headlines from a news website.
* Removes duplicate headlines.
* Saves headlines in a readable numbered list.
* Easy to modify for other news websites.

## Author

Created as part of **Task 3 – Web Scraper for News Headlines**.
