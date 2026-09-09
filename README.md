# Press Release to Plot Industry Comparison

Academic team project completed for CIS 3120 Programming for Analytics at Baruch College in Spring 2026.

## Project Overview

This project compared location related business events in the Financial Services and Travel and Hospitality industries.

The workflow used public SEC EDGAR filings, Python, REST API requests, an LLM based classification step, geocoding, and Folium to identify and visualize business location events.

My work included building parts of the data pipeline, testing industry specific search phrases and time windows, reviewing results for relevance, and helping visualize geographic patterns.

## Workflow

1. Search SEC EDGAR for candidate 8 K filings using location related phrases.
2. Restrict results to companies in the selected industry.
3. Retrieve filing text and identify likely location events.
4. Extract structured event information and geocode locations.
5. Compare the two industries and visualize the results with Folium.

## Tools and Skills

* Python
* REST APIs
* SEC EDGAR
* pandas
* Folium
* Data cleaning
* Data validation
* LLM assisted classification
* Structured JSON output
* Git and GitHub

## What I Learned

This project gave me experience working with real public filing data, tuning search logic, validating noisy results, and connecting multiple stages of a data pipeline from retrieval through visualization.

It also showed how the same data collection approach can produce very different patterns across industries depending on the business context.

## Project Context

This was a three person team academic project. The repository documents my project experience and portfolio summary. Team and instructor materials are not presented here as solely my own work.