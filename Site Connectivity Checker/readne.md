# Website Availability Checker

The Website Availability Checker is a Streamlit-based web application designed to help users monitor the availability of various websites. Users can add URLs to a list, and the application will check if those sites are accessible online (returning a status of "up" or "down"). This tool is particularly useful for website administrators, developers, and anyone interested in the status of specific web pages.

## Features

- **URL Management**: Users can add or remove URLs from their monitoring list.
- **Availability Check**: The application checks the availability of each website and displays the result with intuitive emojis.
- **Streamlit UI**: A user-friendly interface built with Streamlit for easy interaction.

## Technical Details

- **URL Formatting**: The application formats URLs to include "https://www." prefix, ensuring consistency in how URLs are processed.
- **Availability Check**: Uses Python's `requests` library to send a GET request to each website and check the response status.
- **Streamlit Framework**: Leverages Streamlit to create an interactive web application without the need for complex web development.

## Project Setup

To get started with this project, you will need to have Python installed on your machine. Additionally, the project depends on the following Python packages:

- `streamlit`
- `requests`

You can install these packages using pip:

```bash
pip install streamlit requests
```

To run the application, navigate to the project directory in your terminal and execute:

```bash
streamlit run app.py
```
