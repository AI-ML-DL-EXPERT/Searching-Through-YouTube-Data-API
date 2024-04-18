## Searching Through YouTube Data API

This repository contains a Python script that utilizes the YouTube Data API v3 to search for videos and retrieve details about the top results.

### Features

* Search YouTube for a specific query.
* Retrieve details of the top 3 search results (videos).
* Identify the video with the most likes among the top results.
* Play the video with the most likes in a web browser.

### Usage

1. **Set up your API Key:**

   * Enable the YouTube Data API v3 in the Google Cloud Console: [https://console.cloud.google.com/](https://console.cloud.google.com/).
   * Create an API key and restrict it to "Other" application type.

2. **Create a `.env` file:**

   * Create a file named `.env` in the root directory (ignore this file with Git).
   * Add the line `YOUTUBE_DATA_API_KEY=YOUR_API_KEY` (replace `YOUR_API_KEY` with your actual key).

3. **Run the script:**

   * Install required libraries (`googleapiclient`, `dotenv`, `pprint`, `webbrowser`).
   * Run the script using `python youtube_search.py`.

4. **Input your search query:**

   * The script will prompt you to enter a search query.

### Dependencies

* `googleapiclient`
* `dotenv`
* `pprint`
* `webbrowser`

### License

**Choose an open-source license:** [https://choosealicense.com/](https://choosealicense.com/) (e.g. MIT, Apache 2.0) and add a LICENSE file to your repository.

**Note:** You'll need to replace `YOUR_API_KEY` in the `.env` file with your actual YouTube Data API v3 key.
