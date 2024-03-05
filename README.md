# JobScraper

JobScraper is a Python-based web scraping tool designed to automate the process of searching for job listings that match specific skills and preferences. It filters out listings based on skills you're not familiar with, allowing users to focus on the most relevant job opportunities. Built with BeautifulSoup and Requests, this script scrapes job listings from TimesJobs, focusing on Python-related positions.

## Features

- **Custom Skill Filtering**: Users can specify skills they are not familiar with to filter out undesired job listings.
- **Recent Listings**: The script prioritizes job listings published in the last few days, ensuring users see the most up-to-date opportunities.
- **Automated Job Search**: Runs continuously in the background, with user-defined intervals between searches, providing real-time updates on new listings.
- **Easy to Use**: Simple CLI for setting up preferences and starting the job search process.

## Getting Started

### Prerequisites

- Python 3.6 or later
- BeautifulSoup4
- Requests

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/BaldeepArora/PyJobScraper.git
```
2. Navigate to the cloned directory:
```
cd PyJobScraper
```
4. Install the required Python packages:
```  pip install -r requirements.txt ```
### Usage
1. Start the script
```  python main.py```
2. When prompted, enter the skills you are not familiar with, separated by commas. For example:
```
Put some skills that you are not familiar with (separate them by comma): 
> Django, Flask, Docker
```
3. The script will start searching for jobs and will save the listings that don't require the specified skills in the posts directory. Each listing is saved in a separate text file named according to its index.
