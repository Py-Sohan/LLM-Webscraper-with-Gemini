# Universal Web Scraper with LLM-Powered Extraction and Pagination

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://[YOUR_STREAMLIT_APP_URL_HERE])
[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)


## Overview

![image](https://github.com/user-attachments/assets/69b2c8a4-a333-4483-b9c6-41e62f92fb5e)


This project is a **Universal Web Scraper** that goes beyond simple data extraction. It leverages the power of **Large Language Models (LLMs)** to intelligently identify and extract structured information from web pages based on user-defined fields. Furthermore, it incorporates sophisticated **pagination handling** to seamlessly navigate and scrape data from multi-page websites. The extracted data, along with pagination details, is efficiently stored in a **Supabase** database, and the entire process is made user-friendly through an intuitive **Streamlit** web interface.

This tool is ideal for various applications, including:

* **Data Aggregation:** Collecting information from multiple online sources.
* **Market Research:** Extracting product details, pricing, and customer reviews.
* **Content Analysis:** Gathering textual data for analysis and insights.
* **Competitive Intelligence:** Monitoring competitor websites for key information.

## Key Features

* **Universal URL Input:** Easily input single or multiple URLs to scrape.
* **Intelligent Field Extraction:** Define specific fields of interest, and the LLM will intelligently extract the relevant information.
* **Multi-LLM Support:** Supports a range of powerful LLMs, including OpenAI's `gpt-4o-mini`, Google's `gemini/gemini-2.0-flash`, DeepSeek's `deepseek/deepseek-reasoner`, and local models via Ollama (`ollama/llama3:70b`).
* **Robust Pagination Handling:** Automatically identifies and navigates pagination on websites based on detected patterns or user-provided hints.
* **Supabase Integration:** Efficiently stores scraped raw data and structured extraction results in a scalable Supabase database.
* **Interactive Streamlit UI:** A user-friendly web interface for easy configuration and execution of scraping tasks.
* **Real-time Feedback:** Provides clear status updates and token usage/cost information for LLM calls.
* **Data Export:** Allows downloading extracted data and pagination URLs in both JSON and CSV formats.
* **API Key Management:** Securely handles API keys for different services.

## Technologies Used

* **Python:** The primary programming language.
* **Streamlit:** For creating the interactive web application.
* **LiteLLM:** A unified interface for interacting with various LLM APIs.
* **Supabase:** A scalable backend-as-a-service for database storage.
* **`crawl4ai`:** For asynchronous web crawling and markdown conversion.
* **`streamlit-tags`:** For the interactive field input component in Streamlit.
* **`python-dotenv`:** For managing environment variables (API keys).
* **`pandas`:** For data manipulation and CSV export.
* **`asyncio`:** For handling asynchronous operations.
* **Pydantic:** For data validation and structuring.

## How It Will Serve Business Purpose?

This Universal Web Scraper offers significant value for businesses by enabling efficient and intelligent data acquisition, leading to better decision-making, cost savings, and a competitive edge. Here's how it can serve various business purposes:

* **Market Research and Analysis:** Businesses can leverage this tool to gather valuable insights into market trends, competitor activities, pricing strategies, and customer sentiment by scraping relevant websites and online platforms. The LLM-powered extraction ensures that unstructured web content is transformed into actionable structured data for analysis.

* **Competitive Intelligence:** Monitoring competitor websites for product updates, marketing campaigns, pricing changes, and recruitment efforts becomes streamlined. This allows businesses to stay informed and adapt their strategies proactively.

* **Lead Generation:** For businesses focused on B2B sales, the scraper can be used to identify potential leads from industry directories, professional networking sites, and company websites by extracting contact information and company details (where publicly available and ethical scraping practices are followed).

* **Content Aggregation and Curation:** Businesses that rely on curating content from various online sources can automate the process of gathering relevant articles, news, and other information, saving time and resources.

* **E-commerce Monitoring:** Online retailers can track product availability, pricing changes, and customer reviews on competitor websites or across different marketplaces, enabling dynamic pricing adjustments and inventory management.

* **Data-Driven Decision Making:** By providing access to large volumes of structured data extracted from the web, this tool empowers businesses to make more informed decisions based on evidence rather than assumptions.

* **Automation of Repetitive Data Collection Tasks:** Many businesses spend significant time and resources on manual data collection. This scraper automates these tasks, freeing up employees to focus on more strategic activities.

* **Cost Efficiency:** Automating web scraping and data extraction can significantly reduce the labor costs associated with manual data collection efforts.

* **Enhanced Data Accuracy:** By using LLMs for intelligent extraction, the tool can identify and extract relevant information more accurately than simple keyword-based scraping methods, reducing the risk of errors in data analysis.

In essence, this project provides a flexible and intelligent solution for businesses to harness the vast amount of publicly available data on the internet, transforming it into valuable insights and operational advantages. By combining robust web scraping with the cognitive abilities of LLMs, it offers a powerful tool for staying competitive in today's data-driven landscape.

## Inspiration

This project was inspired by the insightful work and tutorials of **Reda Marzouk** on YouTube. His content on web scraping and data extraction techniques provided valuable guidance and motivation for the development of this Universal Web Scraper. You can explore his channel for more related content: [Reda Marzouk's YouTube Channel](https://www.youtube.com/@RedaMarzouk)

The following video specifically influenced the conceptualization and implementation of certain aspects of this project:

[YouTube Video Player](https://www.youtube.com/embed/h3nZGjnJG88?si=0wUUS8_aT3JLjoYZ)

I highly recommend checking out Reda Marzouk's channel for anyone interested in learning more about web scraping related topics.
