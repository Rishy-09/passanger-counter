# Passenger Counter

A small browser-based counter for recording how many people have entered a location. It displays the current count, lets the user save each recorded total, and resets the counter for the next entry.

**Live demo:** [brilliant-melomakarona-abf26f.netlify.app](https://brilliant-melomakarona-abf26f.netlify.app/)

## Features

- Increase the current passenger count with the **INCREMENT** button.
- Save the current total to a running list of previous entries.
- Reset the current count to zero after saving.
- Station-themed background styling.

## Built with

- HTML
- CSS
- Vanilla JavaScript

## Run locally

This is a static website with no dependencies or build step.

1. Clone or download this repository.
2. Open `index.html` in a web browser.

For automatic refresh while developing, serve the folder with any local static-file server.

## Project structure

```text
index.html   # Page markup
index.css    # Visual styles
index.js     # Counter and save behavior
station.jpg  # Background image
```

## How it works

Click **INCREMENT** for each person entering. Click **SAVE** to append that total under "Previous entries"; the current count is then cleared so you can start the next count.
