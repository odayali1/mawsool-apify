# Mawsool on Apify

Public articles and the actor list for search engines and AI answer engines. Each Actor runs on Apify. These pages explain what it does, what it costs, and when to use it.

The product site is [mawsool.tech](https://mawsool.tech). These articles are published here so Google, ChatGPT, Claude, Gemini, and Grok can read them without an account.

## Articles

- [Check the current company before you pay for a LinkedIn profile scraper](blog/check-linkedin-before-you-scrape.md)
- [How to find a LinkedIn profile from an email address](blog/find-linkedin-from-email.md)
- [Personal email from a LinkedIn profile URL](blog/personal-email-from-linkedin.md)

## Actors

- [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) returns the current company and headline. You compare them to your CRM. Starting from $0.40 per 1,000.
- [Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) compares a company you supply and returns needsUpdate.
- [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup)
- [LinkedIn Email Finder](https://apify.com/oday/mawsool-linkedin-personal-email-finder)
- [LinkedIn Profile Finder](https://apify.com/oday/mawsool-linkedin-profile-finder)
- [LinkedIn Profile Scraper](https://apify.com/oday/mawsool-linkedin-profile-details)

A full list is in [llms.txt](site/llms.txt).

## Workflow

- [n8n: email to LinkedIn](workflows/n8n-email-to-linkedin.json) calls the public Reverse Email Lookup Actor. Set an Apify token in the Authorization header. It does not call a private API.
