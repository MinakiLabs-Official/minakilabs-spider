
# MinakiLabs Spider Project (Tunnel Spider)

Welcome to the MinakiLabs Spider Project, also known as Tunnel Spider! This project helps you efficiently scrape and query web data using our advanced scraping technology.

## Overview

The MinakiLabs Spider Project is a comprehensive solution for web scraping, allowing you to extract and query data from web pages seamlessly. Key features include:

- **Automated Web Scraping**: Extract data from web pages with our powerful scraping engine.
- **Querying JSON Data**: Use JMESPath to query and manipulate the scraped JSON data.
- **User-friendly CLI**: Access all functionalities via our intuitive Command Line Interface (CLI).
- **IP Rotation**: Ensure anonymity and avoid IP blocking with our extensive pool of IP addresses.
- **Customizable Device Switching**: Change the device type for each request to mimic different user agents.
- **API Integration**: Integrate our scraping capabilities into your applications with our well-documented API.
- **Detailed Documentation**: Comprehensive guides and references to help you get the most out of our service.

## Installation

To get started with the MinakiLabs Spider CLI tool, follow these installation steps:

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation via pip

```bash
pip install spider-cli
```

## Configuration Guide

### Setting Up Your API Key

Before using the CLI, set up your API key:

```bash
spider login
```

To configure the API key:

```bash
spider config --apikey YOUR_API_KEY
```

## Usage Guide

### Scrape a Web Page

To scrape a web page and display the data in the console:

```bash
spider scrape https://example.com --display
```

### Query Scraped Data

To scrape a web page and query the data using JMESPath:

```bash
spider query https://example.com --query 'links[*]' --display
```

## API Reference

### Endpoints

#### Scrape HTML

- **URL**: /api/v1/scrape-html
- **Method**: POST
- **Query Parameters**:
  - **url**: The URL of the web page to scrape.
- **Headers**:
  - **apikey**: Your API key.
  - **Content-Type**: application/json
- **Response**:
  - Returns the scraped data in JSON format.

## Contact

For any questions or support, please contact us at support@minakilabs.dev.

## Feedback and Support

We are using Jira for issue tracking and feedback. Please visit our Jira board to report any issues or to request new features.

## Contributing

We welcome contributions to the MinakiLabs Spider Project. Please read our contributing guidelines for more details.

## Roadmap

- **Pre-Alpha**:
  - Initial release of CLI tool and API.
  - Basic scraping and querying functionality.
  - Documentation and usage examples.
- **Alpha**:
  - Feedback collection and bug fixes.
  - Additional features like IP rotation and device switching.
  - Enhanced documentation.
- **Beta**:
  - Performance improvements.
  - Expanded feature set based on user feedback.
  - Security enhancements.
- **Release**:
  - Full release with all planned features.
  - Comprehensive documentation.
  - User support and maintenance.

## ASCII Art and Loading Wheels

Our CLI tool features cool ASCII art and loading wheels to enhance the user experience.
