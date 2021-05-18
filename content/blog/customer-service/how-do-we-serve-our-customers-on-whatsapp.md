---
title: How do we serve our customers on WhatsApp?
date: 2021-05-18 20:05:16
category: 'customer-service'
thumbnail: ./images/whatsapp-service.jpg
draft: false
---

![](./images/whatsapp-service.jpg)

- [Why we chose WhatsApp?](#why-we-chose-whatsapp)
- [Getting started with WhatsApp](#getting-started-with-whatsapp)
- [Our workflow with WhatsApp](#our-workflow-with-whatsapp)
    - [After-sales service](#after-sales-service)
    - [Next steps with WhatsApp](#next-steps-with-whatsapp)

# Why we chose WhatsApp?

We had experimented with many different customer service platforms, many of them offered live chat and email channels. However, we found that we had to chase after our customers once they had left the chat. People don't read their personal emails that often and emails get cluttered real fast.

WhatsApp is the perfect solution to combat this - the conversation doesn't end when the customer leaves our website.

# Getting started with WhatsApp

To get started with WhatsApp, many businesses use personal or business accounts on their mobile phones and answer their customers from the phone or from the WhatsApp web. While this can work for a small operation, we needed something more powerful to be able to keep track of all the queries and to access APIs to enable "machine-powered messaging".

So for this task there are a few possible choices.

- <a href="https://www.twilio.com/WhatsApp" target="_blank">Twilio</a>
- <a href="https://www.waboxapp.com/" target="_blank">Waboxapp</a>

Twilio offers an official integration with the WhatsApp Business API. This is what we ended up going for. With this integration the WhatsApp doesn't live on our phone but it is provided by Twilio/WhatsApp (when with Waboxapp you can use your own WhatsApp account on your phone). You can sign up for WhatsApp business API <a href="https://www.twilio.com/WhatsApp" target="_blank">here</a>.

When you apply for the official WhatsApp Business API, you can't use your own number. Instead you will be able to choose a new number from their collection.

# Our workflow with WhatsApp

For our customers the WhatsApp service starts when they first contact us or when they place an order. If it is the latter, they will receive an order confirmation via WhatsApp in addition to receiving it by email. The second point of contact happens when their order leaves our warehouse and at that point they receive a shipping notification with their tracking info.

This is made possible by the powerful WhatsApp/Twilio API and some custom functions that are run on our backend (Prestashop).

### After-sales service

You might think that this is where the service experience ends unless the customer contacts us. But we have found out that often the customers need to exchange the product in case it didn't fit them just right. So after the customer receives their order, we will send them a review request by email/WhatsApp. We ask them to review their ordered product and in case they need to exchange it, it will be just as easy as answerring our WhatsApp message to get started with the process.

We use a custom Prestashop module to monitor the customer shipments so we deliver the review requests just at the right time.

### Next steps with WhatsApp

At the moment we are building automated processes/bots to facilitate a better and a faster customer experience when exchanging products. If you are interested in building chat bots, have a look at the <a href="https://cloud.google.com/dialogflow/docs" target="_blank">Dialogflow platform</a>.

If you have any questions or comments, don't hesitate to write a comment or contact me at <a href="mailto:petteri@pucilowski.eu">petteri@pucilowski.eu</a> :)
