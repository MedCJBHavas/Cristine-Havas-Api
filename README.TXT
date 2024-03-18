API Integration for Date Extraction

Introduction:

This online application offers users a simple interface for retrieving historical exchange rates for
 several currencies based on a specific date. Users can enter a date, and the program will retrieve 
 the exchange rates via the Open Exchange Rates API and displays it in a table format. 
 The table displays the currency codes and their exchange rates for the chosen date(s).
Optionally, users can provide a second date to compare exchange rates between two dates.

Technologies:
The API Exchange Rate Viewer web application is designed with HTML5, CSS, and JavaScript technologies.
 HTML5 defines the web page's design and content hierarchy. JavaScript acts as the application's backbone,
 handling user interactions, form submissions, API queries, and dynamic content rendering. Users can use
JavaScript to interact with the input form, submit queries, and receive real-time updates on currency rate
 data obtained via the Open currency Rates API.

PATH PARAMS
Date - required - The requested date in YYYY-MM-DD format (required).

QUERY PARAMS
app_id -string -Your unique App ID (required)

Base - string - Change base currency (3-letter code, default: USD) - Optional

Symbols - string - Limit results to specific currencies (comma-separated list of 3-letter codes) - Optional

Show_alternative - boolean - Extend returned values with alternative, black market and digital currency rates - false

prettyprint - boolean -Human-readable response for debugging (response size will be much larger) - false

