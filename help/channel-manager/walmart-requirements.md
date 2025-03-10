---
title: "[!DNL Walmart] Requirements"
description: "Verify that you have the required[!DNL Walmart Marketplace]information and resources to integrate with Channel Manager."
exl-id: c4f247e8-280a-4595-a6c8-cf8b732d7aab
---
# [!DNL Walmart] requirements

[!DNL Channel Manager] requires the following resources and information to configure a [!DNL Commerce] sales channel for [!DNL Walmart Marketplace.]

* Approval to sell on [!DNL Walmart] and credentials to log in to the registered Marketplace Seller account

* An API key to connect Adobe Commerce or Magento Open Source to [!DNL Walmart Marketplace]

  The [!DNL Walmart Marketplace] API key enables the integration between [!DNL Channel Manager] for Adobe Commerce or Magento Open Source and the Walmart Marketplace. Set up the API key in Seller Central before starting the Channel Manager onboarding process.

## Set up a Marketplace Seller account

1. [Submit your Walmart Seller application](https://marketplace-apply.walmart.com/apply?id=0014M00001zivMpQAI).
1. After obtaining approval from [!DNL Walmart], [set up your Walmart Seller account](https://sellerhelp.walmart.com/seller/s/guide?article=000008219).

## Generate a [!DNL Walmart Marketplace] Production API key

1. Go to [!DNL Walmart Marketplace]to generate a [solution provider production API key for Adobe](https://developer.walmart.com/#preloginModal?redirectUri=https%3A%2F%2Fdeveloper.walmart.com%2Faccount%2FgenerateKey).

1. Create the key and configure permissions:

   * Select Adobe as the solution provider.
   
   * Set the permissions as shown in the following table. For details, see [API Credentials](https://sellerhelp.walmart.com/seller/s/guide?article=000006422) in the _Walmart Marketplace Seller Help_.

    **Adobe API key configuration for Walmart**

    | **Permission** | **Setting** |
    |----------------|-------------|
    | Content        | Full Access |
    | Get Feeds      | View Only   |
    | Inventory      | Full Access |
    | Items          | Full Access |
    | Lag Time       | Full Access |
    | Order          | Full Access |
    | Price          | Full Access |
    | Reports        | View Only   |
    | Returns        | Full Access |
    | Rules          | Full Access |
    | Shipping       | Full Access |

## [!DNL Walmart Marketplace] Store status

When you publish products to the marketplace, listing availability depends on the status of your [!DNL Walmart Marketplace] stores:

* For live stores, your product offers are listed and available for sale when the match operation completes. 

* For stores that are not live, your product offers are staged and not visible to customers. When the [!DNL Walmart Marketplace] store goes live, staged listings are pushed to the live store automatically. 

![[!DNL Walmart Seller Central] staged products](assets/walmart-seller-central-staged.png)
