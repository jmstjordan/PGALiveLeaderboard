## PGA Tour Leaderboard Scraper

This is a python demonstration to scrape the current PGA tournament's leaderboard from ESPN's leaderboard (http://www.espn.com/golf/leaderboard).

Running this job will write a file in this format:

{"Tournament": "PGA Championship", "Players": {"Brooks Koepka": {"TO PAR": -7, "THRU": "F"},...}}

### Dependencies

- BeautifulSoup (bs4)
- Requests (requests)

### Usage

Clone this directory, then install the dependencies from above. Then, run the scraper via 

`python pull_pga.py`

This will write a json file with relevant leaderboard data to a file.