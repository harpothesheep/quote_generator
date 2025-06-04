# Quote Generator README

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [API Information](#api-information)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)

## Overview
The Quote Generator is a simple Python application that retrieves and displays random quotes from the ZenQuotes API. It provides a menu-driven interface for users to fetch quotes or quit the application.

## Features
- Fetches random quotes from the ZenQuotes API
- Displays quotes with their authors
- Simple menu-driven interface
- Error handling for failed API requests

## Requirements
- Python 3.x
- `requests` library

## Installation
1. Clone the repository or download the code.
2. Install the required `requests` library using pip:
   ```bash
pip install requests

## Usage
1. Run the application.
2. Choose an option from the menu:
   - `1`: Get a random quote
   - `2`: Quit the application
3. If a quote is fetched successfully, it will be displayed with its author.

## API Information
The Quote Generator uses the ZenQuotes API, which provides a free tier for random quotes. Please review the API documentation for usage limits and guidelines:
https://zenquotes.io/api/

## Troubleshooting
- If the application fails to fetch a quote, check the API status and your internet connection.
- Ensure you have the latest version of the `requests` library.

## Contributing
Contributions are welcome. Please submit a pull request with your changes and a brief description of what you've added or fixed.
