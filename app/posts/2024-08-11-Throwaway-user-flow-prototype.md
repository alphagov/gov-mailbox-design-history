---
title: Throwaway user flow prototype
description: An internal prototype exploring the flow around the inbox and how we might adapt the existing reference app bringing it inline with GDS design patterns
date: 2024-08-11
screenshots:
  items:
    - text: Mobile splash page
      src: 01-prototype-splash-page.jpg
      alt: Example of how you can set alternative text. If you leave this off, the default alt text will be 'Screenshot of [image title]'.
      caption: |
        You can include captions with each image, and each caption can include markdown. This is a screenshot of the [index page](/).
    - text: One login integration
      src: 02-prototype-one-login.jpg
    - text: Message inbox
      src: 03-prototype-message-inbox.jpg
    - text: Email message
      src: 04-prototype-message-reading.jpg
    - text: Email message alt
      src: 05-prototype-message reading-pane.jpg
    - text: Email compose
      src: 06-prototype-compose.jpg
    - text: A design history post
      src: 07-prototype-service-page.jpg
    - text: A design history post
      src: 08-prototype-iservice-page-info.jpg
    - text: Service directory
      src: 09-prototype-service-list.png
    - text: A design history post
      src: 10-prototype-service-start.jpg
    - text: A design history post
      src: 11-prototype-service-form.jpg
    - text: A design history post
      src: 12-prototype-profile.jpg
tags:
  - examples
---
## Prototype

This prototype was used internally in our team to rapidly examine a number of risks
Understanding how GDS design patterns may transfer across to the mailbox
Better understand the user needs around two-way communication and mail
Explore the difference between a standardised mailbox design pattern and a transformed experience for citizens


It seems we have 3 routes of complexity / levels of similarity to GDS style:

‌

1/ Light-touch re-skin of the current AMI platform. This assumes the paradigm of POC remains as predominantly mailbox. Benefit: we prove digitise the letters, savings departments money on physical post

‌

2/ We digitise the letters and direct user via link to the place / service when they need to take action. We make it look GDS style. Benefit: we digitise the letters, saving departments money and direct users to the right place, with the journey being somewhat clunky.

‌

3/ We integrate the service journey into the mailbox and make it look and feel like a GDS compliant service. Benefit: save departments money, prove we can integrate with services, significantly improve user experience.

‌

As next step we need to understand how much time / dev effort each of these would take to achieve.

‌

There are few things we also need to understand:

what do we mean is a two way communication and what are the user needs in this space
how do we talk about the platform benefits vs mailbox benefits and who needs to hear it
how can we work with forms we have in the AMI platform / can we make them look GDS style. Also is there a conflict with GDS Forms at all? Or a benefit to them?


Key learnings
Messages and services are probably too interconnected to silo
It seems possible to do a GDS styled version of the inbox
Treating it as mail without rethinking how communications and services are delivered seems ill-advised and a missed opportunity for transformation


https://www.figma.com/design/Onwb2U0fSWBjIwX92I4WwY/Gov-Mailbox?node-id=1-230&t=ERptLVD98vfb0CmB-1
