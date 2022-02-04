# Use Cases & Threat Models

## **Account Authentication & New Accounts**

Account authentication and account creation workflows are abused from bad actors who manually or programmatically attempt to take control of existing accounts (a form of identity theft) or create a large number of accounts that they can subsequently use to abuse the platform.

Threat models per OWASP taxonomy:
* [OAT-007 Credential Cracking](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-007_Credential_Cracking.html)
* [OAT-008 Credential Stuffing](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-008_Credential_Stuffing.html)
* [OAT-019 Account Creation](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-019_Account_Creation.html)
* [OAT-020 Account Aggregation](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-020_Account_Aggregation.html)

## **Invalid Traffic (IVT)**

Falsification of the number of times an item such as an advert is clicked on, or the number of times an advertisement is displayed. Performed by owners of websites displaying ads, competitors and vandals. 

Invalid traffic is any activity that doesn't come from a real user with genuine interest. It can include accidental clicks caused by intrusive ad implementations, fraudulent clicking by competing advertisers, advertising botnets and more (per [Google’s](https://www.google.com/ads/adtrafficquality/invalid-activity) definition).

Threat models:
* [TAG IVT Taxonomy](https://f.hubspotusercontent40.net/hubfs/2848641/Invalid%20Traffic%20Taxonomy%20(IVT)/IVT%20Taxonomy%20v2.0.pdf)
* [OAT-003 Ad Fraud](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-003_Ad_Fraud.html)


## **Online Purchases**

Automation is used to abuse the purchase workflows of digital or physical goods. Bad actors are able to complete purchases faster (e.g. sneaker bots, auction sniping) and at larger quantities compared to other buyers.

Threat models:
* [OAT-005 Scalping](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-005_Scalping.html)
* [OAT-013 Sniping](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-013_Sniping.html)

## **Payments**

Payment workflows are abused using automated or manual techniques in order to buy merchandise using stolen payment cards, validate stolen payment cards, brute force and crack payment cards, or abuse promotions.

Threat models:
* [OAT-001 Carding](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-001_Carding.html)
* [OAT-010 Card Cracking](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-010_Card_Cracking.html)
* [OAT-012 Cashing Out](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-012_Cashing_Out.html)
* Promotion or refund abuse

## **Sensitive Data Scraping**

Sensitive data (e.g. user profiles, product prices, user generated content) that is available in the public domain (account authentication may or may not be required) is programmatically exfiltrated at scale for use elsewhere.

Threat models per OWASP taxonomy:
* [OAT-011 Scraping](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-011_Scraping.html)


## **User Generated Content / Content Platforms**

Mass spammy user generated content (videos, reviews, comments, likes, audio/video playback). Bypassing creator's restrictions on accessing content.

Threat models:
* [OAT-016 Skewing](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-016_Skewing.html)
* [OAT-017 Spamming](https://owasp.org/www-project-automated-threats-to-web-applications/assets/oats/EN/OAT-017_Spamming.html)
* Spin fraud (for audio and video content)


# Focal Use Cases
TBD

# Out of Scope
TBD

# References
* [OWASP automated threats](https://owasp.org/www-project-automated-threats-to-web-applications/)
* [TAG IVT Taxonomy](https://f.hubspotusercontent40.net/hubfs/2848641/Invalid%20Traffic%20Taxonomy%20(IVT)/IVT%20Taxonomy%20v2.0.pdf)
