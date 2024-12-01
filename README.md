# LeetCode Scraper

A Python-based scraper using Playwright and AgentQL to extract problem data from LeetCode's study plans.

## Prerequisites

- Python 3.12+
- pip (Python package installer)
- Git

## Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd leetcode_scrape
```

2. Install dependencies:
```bash
poetry install
```

3. Install Playwright browsers:
```bash
playwright install chromium
```

## Usage

You can run the scraper using either the Python script or Jupyter notebook:

### Using Jupyter Notebook
1. Start Jupyter:
```bash
jupyter notebook
```

2. Open `scraper.ipynb` and run the cells sequentially

The script will:
- Launch a Chromium browser
- Navigate to LeetCode's 75 study plan page
- Extract problem data including names, sections, difficulties, and tags
- Save the results to  Excel format

## Output

The scraper generates two output files:
- `output.xlsx`: Excel spreadsheet containing the problem data

## Project Structure

```
leetcode_scrape/
├── .gitignore          # Git ignore rules
├── README.md           # This file
├── scraper.ipynb       # Jupyter notebook implementation
```

## Dependencies

- `playwright`: Browser automation
- `agentql`: Web scraping framework
- `polars`: Data manipulation library
