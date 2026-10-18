---
title: How to find a LinkedIn profile from an email address
description: Reverse email lookup returns the LinkedIn profile only on an exact match. Uncertain results come back empty. Starting from $0.60 per 1,000 emails.
slug: find-linkedin-from-email
---

# How to find a LinkedIn profile from an email address

Paste the email into [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup). When `hasLinkedIn` is true, `linkedinUrl` is the profile for that email. When the match is not exact, the profile fields are empty.

Starting from $0.60 per 1,000 emails on Diamond. The free plan is $2 per 1,000. You are charged for each email processed, including a row with no match.

## What you get

Name, headline, company, location, and the LinkedIn profile URL. Export CSV or JSON. No LinkedIn login and no cookies.

## How to run it

1. Paste emails, or upload a CSV.
2. Start the Actor.
3. Filter the dataset to `hasLinkedIn` = true.
4. Import the LinkedIn URL, title, and company back into your CRM.

## FAQ

### Does this guess a profile from a similar name?

No. Only an exact match sets `hasLinkedIn` to true.

### Is a miss free?

No. Each email processed is one charge. The row is still useful: you can filter on `hasLinkedIn` = false.
