# SWAPI Data Fetcher

This is a simple HTML page that fetches data from the Star Wars API (SWAPI) and displays it in a formatted JSON format.

## Live Demo

Click [here](YOUR_DEPLOYED_URL) to view the live version of this project.

## Overview

The page fetches data from the SWAPI using JavaScript's `fetch` API, parses the JSON response, and displays it in a `<div>` element. If an error occurs during the fetch operation, an error message is displayed instead.

## Features

- Fetches JSON data from the [SWAPI]( https://ry-f3.github.io/Js-fetch-api/).
- Displays the fetched JSON data in a readable, formatted manner.
- Shows an error message if the fetch operation fails.

## How to Use

1. **Clone the Repository** (if applicable):
    ```bash
    git clone https://github.com/your-username/swapi-data-fetcher.git
    cd swapi-data-fetcher
    ```

2. **Open the HTML File**:
    Open `index.html` in your web browser.

3. **View Data**:
    The fetched data from SWAPI will be displayed in the browser. If there's an error with fetching the data, an error message will be shown.

## Code Explanation

- **HTML**: The page contains a `<div>` element with the ID `content` where the fetched data is displayed.
- **CSS**: Basic styling is applied to the page and the data display.
- **JavaScript**: 
  - Fetches data from the SWAPI.
  - Parses the JSON response.
  - Displays the data in the `#content` element.
  - Handles errors and displays error messages.


