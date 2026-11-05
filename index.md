# phishscan-ingest crawler

This is an automated crawler run by Charles, a developer in Lagos, Nigeria, as part of a phishing-detection research project.

**What it does:** for each site, it requests `robots.txt`, then reads the sitemap files the site publishes (and sometimes the homepage once). It keeps only URL strings, never page content.

**How it behaves:** it obeys `robots.txt` and `Crawl-delay`, makes only a handful of requests to your site, rejects cookies, and identifies itself in its User-Agent.

**To opt out:** email phishscan.crawler@gmail.com with your domain, and it will be added to an exclusion list within 7 days.
