# Event Scraper and Calendar Generator

This script automates the extraction of event details from multiple sources and generates a consolidated, sorted CSV file for an event calendar. It includes dynamically scraped events and pre-defined recurring events.

## Features

- **Dynamic Event Scraping**: Extracts events from the following sources:
  - Marlene Meyerson JCC Manhattan
  - Mustang Harry's
  - 92NY
  - Paley Center for Media
- **Recurring Events**: Includes weekly recurring events from Fleetfeet Hoboken.
- **Data Consolidation**: Combines all events into a single CSV file, sorted by date and time.
- **Excel-Friendly Links**: Formats event sources as clickable hyperlinks in the generated CSV file.

## Requirements

- Python 3.7 or higher
- Required libraries:
  - `selenium`
  - `bs4` (BeautifulSoup)
  - `pandas`
  - `datetime`
  - `dateutil`

### Installing Dependencies

Install the required dependencies using pip:

```bash
pip install selenium beautifulsoup4 pandas python-dateutil
```

### Breakdown of Sections:

- **Features**: Lists what the script does (scrapes events, handles recurring events, consolidates data).
- **Requirements**: Specifies Python version and required libraries.
- **Usage**: Describes how to use the script, including how to install dependencies, clone the repo, run the script, and the format of the output.
- **Adding Event Sources**: Explains how to modify the script to add additional event sources.
- **Known Issues**: Lists potential problems users might face, such as issues with dynamic content or mismatched ChromeDriver versions.
- **Contributing**: Provides guidelines for contributing to the project.
- **License**: Information on the project's license (MIT in this case).

Let me know if you'd like to add anything else!
