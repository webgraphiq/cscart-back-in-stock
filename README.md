# Back in Stock for CS-Cart

**🛑 PREMIUM ADD-ON: This repository does not contain the open-source code. It serves as the official listing and documentation page for the WebGraphiq premium add-on.**

**Back in Stock** is an out-of-stock waitlist and restock-email add-on for CS-Cart and Multi-Vendor. Shoppers leave an email on a zero-stock product (or option combination); when inventory returns, the add-on sends the restock notice in the language they used at signup.

## [🛒 Buy & View Live Demo](https://www.webgraphiq.com/back-in-stock.html)

One-time license. The current price and the live demo are on the product page.

## Why store owners use it

- Product page **Notify me when available** replaces the buy path while stock is zero — guests and signed-in customers can subscribe.
- Works with **product options / track-with-options** inventory: each combination has its own waitlist entry.
- Optional **double opt-in** confirmation email before the request is queued.
- Built-in **honeypot**; Google reCAPTCHA follows the shop’s Custom forms setting (Add-ons → Google reCAPTCHA).
- Restock mail fires when you save a product (or option combination) with stock greater than zero — or you can **notify all** from admin.
- Restock emails can include a product thumbnail; size is configurable.
- No CS-Cart core file edits.

## Storefront waitlist

1. Customer opens an out-of-stock product and submits **Notify me when available**.
2. If opt-in is on, they get a verification mail and must click the link to activate.
3. The request is stored with email, product, option combination hash, language, and queued status.
4. Duplicate signup for the same email + combination is rejected with a clear message.

You can limit the button to the product details page only, or leave it available where the theme hooks the buttons block (lists / search when that layout shows the block).

## Admin: Marketing → Back in stock

- **View requests** — queued vs notified, request date, email, product and options.
- **Statistics** — aggregate counts per out-of-stock item / combination.
- Delete selected requests; **Clear back in stock list**; **Notify all subscribers manually** (useful with ERP / external stock sync).
- New storefront requests can also alert the admin by email.

## What you control

- License key on **Add-ons → Wg Back In Stock**.
- Opt-in confirmation (off by default).
- Honeypot (on by default).
- Product-details-only button.
- Thumbnail size in notification emails (default 120).

## Requirements

- CS-Cart or Multi-Vendor **4.12.1** or newer, including **4.21**
- PHP **8.3** or a current 8.x release used by that shop
- Optional: Google reCAPTCHA add-on for Custom forms anti-bot on the notify form

## This repository

<p align="center">
  <a href="https://www.webgraphiq.com/back-in-stock.html">
    <img alt="Buy and view the live demo" src="https://img.shields.io/badge/CS--Cart-Buy%20%26%20View%20Live%20Demo-28a745?style=for-the-badge&labelColor=1A365D">
  </a>
</p>

<p align="center"><strong>One-time license · waitlist and restock alerts by email</strong></p>

This is the public product listing. The add-on package, license checks, and source files are not published here. After purchase, the package is readable PHP under the WebGraphiq commercial license, installed from your WebGraphiq account.

Support: [webgraphiq.com](https://www.webgraphiq.com) · webgraphiq@gmail.com

© WebGraphiq. All rights reserved. [License](https://www.webgraphiq.com/license.html)

## Other Premium CS-Cart Add-ons by WebGraphiq

More CS-Cart and Multi-Vendor add-ons are listed on the [WebGraphiq GitHub profile](https://github.com/webgraphiq).
