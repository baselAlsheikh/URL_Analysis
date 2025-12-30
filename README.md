# Web Search – URL Analysis (Option 1)

## Overview
This project implements **Option 1 – URL Analysis** as part of the Web Search assignment.  
The goal is to analyze a set of URLs, extract their structural components, and examine crawling restrictions using the `robots.txt` protocol.

The solution is implemented in **Python** using a **Jupyter Notebook** and presents all results in structured **Pandas DataFrames**.

---

## Features

### 1. URL Structure Analysis
For each URL, the following components are extracted:
- Scheme (protocol)
- Top-Level Domain (TLD)
- Domain
- Subdomain
- Host
- Port
- Path
- File name (if exists)
- Query key–value parameters

The extracted data is displayed in a clear tabular format.

---

### 2. robots.txt Analysis
For each URL host, the program checks whether a `robots.txt` file exists and, if so, extracts:
- List of **User-Agents**
- **Disallowed paths**, converted to full URLs
- **Crawl-delay** directive (when available)

This ensures compliance with web crawling best practices and polite crawling rules.

---

## URLs Analyzed
- https://edition.cnn.com
- https://www.nhm.ac.uk
- https://is-web.hevra.haifa.ac.il

---

## Technologies Used
- Python 3
- Jupyter Notebook
- pandas
- requests
- urllib
- tldextract

---

