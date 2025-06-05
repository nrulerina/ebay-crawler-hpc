# 🚀 Optimizing High-Performance Data Processing for Large-Scale Web Crawlers

> SECP3133-02 — High-Performance Data Processing  
> Universiti Teknologi Malaysia  
> Group 6 — Submitted on 17 May 2025

## 👥 Team Members

- Nurul Erina binti Zainuddin (A22EC0254)
- Ong Yi Yan (A22EC0101)
- Tang Yan Qing (A22EC0109)
- Wong Qiao Ying (A22EC0118)

## 🎯 Project Objective

1. Develop a scalable web crawler using **Playwright**, **Requests**, **BeautifulSoup**, **Scrapy**, and **Selenium** to extract **100k+ eBay product listings**.
2. Clean and process data using **Pandas**, **Polars**, **Modin**, and **PySpark**.
3. Compare processing performance across different libraries: execution time, CPU usage, memory, and throughput.

## 🌐 Target Website & Data Extracted

- **Source:** [eBay Malaysia](https://www.ebay.com.my)
- **Category:** Consumer Electronics
- **Extracted Attributes:**
  - Title
  - Price
  - Shipping Fee
  - Link
  - Category
  - Brand
  - Condition

## 🏗️ System Architecture

![Architecture Diagram]()

### Data Pipeline:

1. **Web Crawling** → Data from eBay using 4 libraries  
2. **Storage** → MongoDB Atlas  
3. **Cleaning** → Null handling, de-duplication, transformation  
4. **Processing** → Polars, Pandas, Modin, PySpark  
5. **Evaluation** → Time, memory, CPU, throughput  
6. **Visualization** → Matplotlib, NumPy

## ⚙️ Tools and Frameworks

| Area              | Tools Used                                       |
|-------------------|--------------------------------------------------|
| Programming       | Python                                           |
| Web Scraping      | Requests, BeautifulSoup, Selenium, Scrapy, Playwright |
| Data Processing   | Pandas, Polars, Modin, PySpark                   |
| Database          | MongoDB Atlas                                    |
| Visualization     | Matplotlib, NumPy                                |
| Development       | Google Colab, Google Docs, Draw.io               |
