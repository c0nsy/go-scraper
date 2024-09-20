# Project Structure

go-scraper/
│
├── README.md
├── go.mod
├── go.sum
├── cmd/
│ └── main.go # Entry point for your command-line interface (CLI) if needed.
├── scraper/
│ ├── scraper.go # Core scraper logic (requests, parsing, etc.)
│ ├── config.go # Configuration options for the scraper.
│ └── utils.go # Helper functions like error handling, URL validation, etc.
├── examples/
│ └── basic_scrape.go # Example script to show how to use the library.
└── tests/
└── scraper_test.go # Unit and integration tests for scraper functions.

# go-scraper

`go-scraper` is a simple and efficient web scraping library written in Go. It allows developers to easily extract data from web pages by making HTTP requests, parsing HTML, and supporting features such as request concurrency, user agents, and custom request headers.

## Features

- **Simple HTTP Requests:** Easily make GET requests to scrape HTML content.
- **HTML Parsing:** Extract data from HTML tags using CSS selectors.
- **Concurrency Support:** Scrape multiple pages concurrently for faster results.
- **Custom User-Agent and Headers:** Customize requests with headers like User-Agent or cookies.
- **Error Handling:** Graceful error handling for failed requests or parsing issues.
- **Extensible:** Designed to be modular for adding new features.

## Installation

To use `go-scraper`, install it using `go get`:

```bash
go get github.com/c0nsy/go-scraper
```
