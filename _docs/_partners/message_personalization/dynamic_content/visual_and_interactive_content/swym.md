---
nav_title: Swym Wishlist Plus
article_title: Swym Wishlist Plus
description: "This reference article outlines the partnership between Braze and Swym, that empowers shoppers to save products and seamlessly continue their journey across website, mobile app, and retail stores."
alias: /partners/swym/
page_type: partner
search_tag: Partner
---

<!-- In most cases, the ARTICLE_TITLE will be your company name. If your tool requires several separate pages on Braze Docs, you can add a relevant page descriptor to your title, such as "MyCompany Analytics." -->
# Swym

<!-- The description starts with a '>' character and contains an introduction to your company, a link to your main site, and a concise overview of your integration. In a following paragraph, highlight the the relationship between your company and Braze and how this partnership helps your customers. -->
> [Swym](https://getswym.com) make it easy for merchants to adapt the shopping experience on their websites to solve their unique challenges and workflows.

*This integration is maintained by Swym.*

## About the integration

The Swym + Braze integration empowers merchants to deliver highly personalized, event-driven marketing campaigns that convert shopper intent into sales. The merchants leverage our platform to make it easy for shoppers to pick up where they left off, to collaborate with others throughout their shopping journey and to deploy high performance retargeting campaigns

<!-- Most partner integrations will require the following prerequisites. However, you may add additional prerequisites as needed. -->
## Prerequisites

Before you start, you'll need the following:

| Prerequisite          | Description                                                                                                                                |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Swym Wishlist Plus   | Swym Wishlist Plus app installed in the merchant's ecommerce platform (Shopify/BigCommerce).                                                                     |
| A Braze REST API key  | A Braze REST API key with `users.track` permissions. <br><br> This can be created in the Braze dashboard from **Settings** > **API Keys**. |
| A Braze REST endpoint | [Your REST endpoint URL]({{site.baseurl}}/developer_guide/rest_api/basics/#endpoints). Your endpoint will depend on the Braze URL for your instance.                                                 |
{: .reset-td-br-1 .reset-td-br-2}

<!-- An optional section you can use to outline the typical or atypical use cases for your integration. -->
## Use cases

By connecting Swym’s Wishlist Plus and Back in Stock Alerts apps with Braze, merchants can automatically send shopper activity events—such as wishlist adds, back-in-stock subscriptions, price drop alerts, and reminders—into Braze as custom events. These events can then be used to trigger automated email and SMS campaigns via Braze Canvases, ensuring timely, relevant, and engaging communication that brings shoppers back to purchase.

<!-- Create step-by-step instructions for integrating your tool with Braze. It's important to be concise and only outline the minimum necessary steps. -->
## Integrating Swym

### Step 1: Connect your Swym app to Braze

Establish the connection so that your Wishlist Plus app can securely communicate with Braze.

<!-- Use the "Make a post request", "Default behavior," and "Rate limit" sections to outline how users can make a POST request. If this information isn't required for your integration, you can remove these sections. -->
### Step 2: Subscribe to events you want to send

Choose which Swym events (e.g., price drop, back in stock, wishlist reminder) should be sent to Braze. Without selecting events, no triggers will reach Braze.


### Step 3: Create Canvas(es) in Braze

Set up Canvas(es) that use these events to send personalized emails/ SMS to your shoppers. This is what ensures that the right communication goes out when an event occurs.
