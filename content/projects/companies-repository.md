---
title: "GetCompany.info Repository"
description: "This project was an online database, where anyone could search for Portuguese companies"
image: "/images/projects/companies-repository/index.png"
ogtype: article
ogimage: "/images/projects/companies-repository/index.png"
date: 2021-02-21T19:29:41Z
draft: false
slug: "companies-repository"
---

## 1. Project Information's
This project was an online database, where anyone could search for Portuguese companies through various ways,
including related companies by activities.

This was a side project developed only for personal use.
As it was beginning to get indexed by Google it started receiving a lot of daily people searching for companies.

This project was later shutdown and now it is available on [Github](https://github.com/G4brym/GetCompany.info).

The source code for this project doesn't include any information's about the companies, you have to get it however you 
want and add it to the database by yourself.


## 2. Features
* ~ 400 ms load time (html + css + js)
* REST API to lazy load additional information about the companies
* Secure API token to prevent crawl bots from dumping all Database
* Cache system to save companies information's
* Contact form and email system to send the form to the website admin
* Twitter integration, 1 tweet send for each new company crawled
* Cloudflare integration to archive max 400ms load time
* Elastic beanstalk for deployments
* Automatic sitemap generator
* SEO optimization + google structured data to friendly SEO


## 3. How I got the database
Someday I was search for a company, and I found a website that was really slow and ugly, and I thought to myself
that I could do it better. So I decided to build a crawler to fetch all the companies in that same website.

I ended up with little more than 700 000 company records, that included much more that just the company name and address.


## 4. Final project
*Index Page*
![index page](/images/projects/companies-repository/index.png)

*Company Profile*
![company profile](/images/projects/companies-repository/company.png)

*Contact Page*
![contact page](/images/projects/companies-repository/contact.png)

*Hidden Status Page*
![status page](/images/projects/companies-repository/status.png)


## 5. Statistics
*Average load time*
![load_time page](/images/projects/companies-repository/load_time.png)

*Clicks and impressions on Google Search*
![google_search page](/images/projects/companies-repository/google_search.png)

*Last month of cloudflare analytics*
![last_month page](/images/projects/companies-repository/last_month.png)

*Example of structured data inside Google Search Console*
![search_data page](/images/projects/companies-repository/search_data.png)

*Twitter page - every time we crawl a new company we publish a new tweet*
![twitter page](/images/projects/companies-repository/twitter.png)
