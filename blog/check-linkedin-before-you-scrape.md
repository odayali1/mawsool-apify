---
title: Check the current company before you pay for a LinkedIn profile scraper
description: A LinkedIn profile URL list does not all need a full scrape. Get the current company and headline first, compare them to your CRM yourself, and refresh only the rows you choose.
slug: check-linkedin-before-you-scrape
---

# Check the current company before you pay for a LinkedIn profile scraper

Get the current company and headline from the LinkedIn profile URLs you already have. Compare those two fields to your CRM yourself. Pay for a full profile scrape only on the rows you decide to refresh.

[Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) does the first step. It does not decide whether a company matches. It does not ask you for the old company name.

## What it returns

One row per URL:

- `currentCompany`
- `headline`
- `fullName`
- `linkedinNumId`

You keep the match rule. If your CRM says "Acme" and the row says "Acme Inc", you decide whether that is the same employer.

## What 10,000 profiles cost

The freshness check is $0.40 per 1,000, so 10,000 URLs cost $4. The free plan is $0.60 per 1,000. Run [LinkedIn Profile Scraper](https://apify.com/oday/mawsool-linkedin-profile-details) only on the rows you choose.

## How to run it

1. Export profile URLs from your CRM. One column, `url` or `linkedinUrl`.
2. Run Profile Freshness Check.
3. Compare `currentCompany` and `headline` to the values you already store.
4. Send only the rows you want refreshed to the LinkedIn profile scraper.

No LinkedIn login and no cookies. You supply the URL.

## FAQ

### Does this tell me who changed jobs?

No. It returns the current company and headline. You compare them to your own data.

### Is this a LinkedIn profile scraper?

It is the step before one. The full scraper is a separate Actor, and you run it only on the rows you choose.
