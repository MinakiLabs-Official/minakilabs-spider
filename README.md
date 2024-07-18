# MinakiLabs Spider Project (Tunnel Spider)

Welcome to the MinakiLabs Spider Project, also known as Tunnel Spider! This project helps you efficiently scrape and query web data using our advanced scraping technology.

## Overview

The MinakiLabs Spider Project is a comprehensive solution for web scraping, allowing you to extract and query data from web pages seamlessly. Key features include:
- **Automated Web Scraping:** Extract data from web pages with our powerful scraping engine.
- **Querying JSON Data:** Use JMESPath to query and manipulate the scraped JSON data.
- **User-friendly CLI:** Access all functionalities via our intuitive Command Line Interface (CLI).
- **IP Rotation:** Ensure anonymity and avoid IP blocking with our extensive pool of IP addresses.
- **Customizable Device Switching:** Change the device type for each request to mimic different user agents.
- **API Integration:** Integrate our scraping capabilities into your applications with our well-documented API.
- **Detailed Documentation:** Comprehensive guides and references to help you get the most out of our service.

## Installation

## To get started with the MinakiLabs Spider CLI tool, follow these installation steps:

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation via pip

pip install spider-cli

#### configuration.md

# Configuration Guide

## Setting Up Your API Key

# Before using the CLI, set up your API key:

spider login

#configure API

spider config --apikey YOUR_API_KEY

# Usage Guide

## Scrape a Web Page

#To scrape a web page and display the data in the console:

spider scrape https://example.com --display

#Query Scraped Data
#to scrape a web page and query the data using JMESPath:

spider query https://example.com --query 'links[*]' --display

# API Reference

## Endpoints

### Scrape HTML

**URL:** `/api/v1/scrape-html`

**Method:** `POST`

**Query Parameters:**

- `url`: The URL of the web page to scrape.

**Headers:**

- `apikey`: Your API key.
- `Content-Type`: `application/json`

**Response:**

#Returns the scraped data in JSON format.
