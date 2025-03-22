# RealSelf.com Data Scraper

This project is designed to scrape comprehensive data from [RealSelf.com](https://www.realself.com/), a popular platform featuring profiles of cosmetic and medical professionals. By overcoming advanced security barriers, this scraper collects detailed information on practitioners, including ratings, reviews, specialties, and contact details.

# ⚠️ **Important Notice: Business Use Only** ⚠️

This repository is for **demonstration purposes only** and **not for free use**. It showcases my professional expertise in **web scraping** and **automation**.

🚫 **Unauthorized use, redistribution, or modification is strictly prohibited.**

💼 **For custom web scraping and automation solutions, please contact me directly for professional, business-focused services.**

📩 [Get in Touch](https://mominur.dev)


## Project Description

RealSelf.com employs advanced security measures to prevent unauthorized data scraping, including **PerimeterX** and **HSTS**. These technologies use **IP blocking** and **Press & Hold captchas** to detect and block bots. This project successfully bypasses these barriers to provide complete and structured data on professionals listed on the platform. Sample data files (`realself_sample_data.json` and `realself_sample_data.csv`) are included for easy access and understanding of the dataset.

## Features

- **Comprehensive Data Collection**: Gathers detailed information on each professional listed on RealSelf, including their name, specialty, rating, location, and user reviews.
- **Security Bypass Techniques**: Implements advanced techniques to overcome IP restrictions, captchas, and security headers.
- **Data Format**: Data is available in JSON and CSV formats for easy integration and analysis.

## Data Fields

The scraper extracts the following data fields for each professional:

- **id**: Unique ID for each professional
- **score**: Platform-assigned score indicating profile quality or ranking
- **country**, **state**: Location information
- **source**: URL link to the professional's RealSelf profile
- **name**: Full name and title of the professional
- **category**: Professional category (e.g., Dermatologist, Surgeon)
- **specialty**: Specialty title (e.g., Board Certified Dermatologist)
- **postalCode**, **location**: Address information
- **realself verified**: Indicates if the professional is RealSelf verified
- **website**, **phone**, **email**: Contact information (if available)
- **rating**: Average rating score out of 5
- **review_count**: Number of reviews received
- **aggregateRating**: Nested object containing rating details
- **years_experience**: Number of years in practice
- **reviews**: Nested array of reviews, including author, rating, and review content


## Challenges and Solutions
This project encountered several security measures that required sophisticated approaches to bypass:

- **PerimeterX & HSTS:** These technologies work to prevent bot access through ***IP blocking*** and ***Press & Hold captchas***. I developed custom techniques, including header manipulation, user-agent rotation, and proxy usage, to successfully bypass these detections.

- **IP Blocking:** Implemented rotating proxies to distribute requests and avoid IP-based rate limiting.
- **Press & Hold Captcha:** I bypass this captcha mechanism by changing IPs and manipulating headers and user agents.


## Sample Data

For a quick overview of the scraped data structure, refer to the sample files in this repository:

- `realself_sample_data.json`
- `realself_sample_data.csv`

These files illustrate the kind of information collected from RealSelf, making it easier to analyze and utilize the data.

## Contact Me

For any inquiries or service requests, please reach out to me via LinkedIn or visit my portfolio website:

- **Portfolio:** [mominur.dev](https://mominur.dev)
- **GitHub:** [github.com/mominurr](https://github.com/mominurr)
- **LinkedIn:** [linkedin.com/in/mominur--rahman](https://www.linkedin.com/in/mominur--rahman/)
- **Email:** mominurr518@gmail.com

I look forward to connecting with you!

