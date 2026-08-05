---
layout: default
title: FAQ
description: Common questions, important notes, and a glossary
---

[← Back to Home](index)

---

# FAQ

* TOC
{:toc}

---

## Getting Started

**Do I need to edit my theme code?**
No. Both blocks are added through the Shopify Theme Editor as app sections. You never touch Liquid.

**Which themes are supported?**
Any Online Store 2.0 theme — that is, any theme with an *Apps* section in the Theme Editor. All current free Shopify themes and almost all paid themes qualify.

**Can I use the app on more than one page?**
Yes. Add as many blocks as you like, on as many pages as you like, each pointing at a different image or collection.

**Why does the app need product permissions?**
To search your catalogue in the hotspot editor and read each product's title, image, and price. It does not modify your products.

**Why does the app need file permissions?**
To list the images already in your Shopify Files library so you can pick one, and to upload a new image from your computer into that library.

---

## Images and Hotspots

**How many hotspots can I put on one image?**
Unlimited, on every plan including Free.

**Can I change the picture on an existing image?**
No. Hotspot positions are stored relative to the original picture, so swapping the file would leave every pin misplaced. Create a new image instead.

**Will my hotspots move on mobile?**
No. Positions are stored as percentages of the image's width and height, so they stay correct at every screen size. Do check spacing on a phone, though — pins that look well separated on desktop can crowd on a narrow screen.

**A hotspot shows the wrong price. Why?**
Product details are snapshotted when you attach the product. Open the hotspot, re-select the same product, and save to refresh them. See [Hotspots](hotspots#product-details-are-snapshotted).

**Are variants and stock status also snapshotted?**
No — those are read live when the card opens, so sold-out variants are always shown correctly.

**How do I temporarily take an image off my storefront?**
Turn its **Published** switch off. Hotspots and click history are kept, and turning it back on restores everything.

**What happens to the picture if I delete a shoppable image?**
The file stays in your Shopify **Content → Files** library. Only the app's record, its hotspots, and its click history are removed.

---

## Collections

**Can an image be in more than one collection?**
No. Each image belongs to at most one collection.

**If I delete a collection, do I lose its images?**
No. They are simply unassigned and keep everything else. Any *Shoppable Collection* block still pointing at the deleted collection's ID will need updating in your theme.

**Can I control the order images appear in a grid?**
Yes, through the block's **Order by** setting: Newest, Oldest, or Title (A–Z). For full manual control, sort by title and name your images *"Look 01"*, *"Look 02"*, and so on.

---

## Theme Blocks

**The block shows nothing on my page.**
Check the ID is filled in, the image is **Published**, the image is not **Locked** by the Free plan, and you saved the theme. See [Theme Blocks](theme-blocks#troubleshooting).

**The Dashboard says my block is not added, but it is.**
The Dashboard only checks your **home page** template on your **published** theme. Blocks on other pages work fine but are not detected. It is a display limitation, not a problem with your block.

**Can I change the pin colours?**
Yes — pin colour, hover colour, and text colour are all block settings.

**Can shoppers enlarge the image?**
Yes, if **Open image in full-page popup on click** is enabled — they click the image, or the expand control in its corner, and it opens full-page with the hotspots still working. The setting is on both blocks and is on by default. It is an **Ultimate plan** feature: on Free the popup does not open on your live store, though you can preview it in the Theme Editor.

**Clicking the image does nothing on my live store.**
The full-page popup is an Ultimate feature. On the Free plan the pins still work but the image cannot be enlarged. See [Theme Blocks](theme-blocks#plan-gated-settings).

---

## Billing

**Is the Free plan a trial?**
No. It is permanent and does not expire. The only limit is 3 active images.

**What exactly happens at the Free plan limit?**
Your 3 most recently created images stay active. Any others are marked **Locked** and stop rendering on your storefront. Nothing is deleted, and everything returns when you upgrade. See [Billing & Plans](billing).

**Can I choose which 3 images stay active on Free?**
Not directly. The app keeps the 3 most recently created. Creating a new image will lock your oldest active one.

**Is analytics limited on Free?**
No. It works identically on both plans.

**Which features need the Ultimate plan?**
Unlimited images, plus three storefront display features: **Add to cart from hotspots**, the **full-page image popup**, and the **Masonry** collection layout.

**Can I try Add to cart or the popup before paying?**
Yes. Switch them on and preview them inside the Theme Editor on the Free plan. They just do not activate for real shoppers until you upgrade.

**How do I cancel?**
Go to **Pricing** and click **Downgrade to Free**. Your subscription is cancelled and you drop to the Free plan.

**Will I lose my work if I downgrade?**
No. Images beyond the 3 most recent are locked, not deleted, and come straight back if you upgrade again.

---

## Important Notes

> **The Free plan keeps your 3 most recent images.** Not your best, not your favourites — the 3 created most recently. Creating a fourth locks the oldest.

> **Locking is never destructive.** Locked images keep their hotspots, their settings, and their full click history, and are restored instantly on upgrade.

> **Product details are a snapshot.** Change a price in Shopify and the hotspot card keeps the old one until you re-save the hotspot.

> **Deleting is permanent.** Deleting an image or a hotspot also deletes its click history. Use **Published → off** if you only want to hide something.

> **Your own storefront clicks are counted.** Testing on a live page inflates your analytics. Theme Editor previews are not tracked.

> **Analytics measures pin opens only.** There are no impressions, conversions, or revenue figures — use Shopify's own analytics for those.

> **The Dashboard theme check only sees your home page.** Blocks elsewhere work but show as "not added".

---

## Glossary

**App block** — a section provided by an app that you add through the Shopify Theme Editor without editing theme code.

**Collection** — a group of shoppable images in this app, rendered together by the *Shoppable Collection* block. Unrelated to Shopify's own product collections.

**Collection ID** — the identifier you paste into the *Shoppable Collection* block to tell it which collection to render.

**Hotspot** — a clickable pin placed on an image and linked to one product.

**Image ID** — the identifier you paste into the *Shoppable Image* block to tell it which image to render.

**Locked** — the status of an image that is blocked by the Free plan's 3-image limit. Hidden from the storefront, but fully preserved.

**Full-page popup** — an enlarged, full-screen view of an image, opened by clicking it or its expand control, with the hotspots still working. An Ultimate plan feature, controlled by the *Open image in full-page popup on click* block setting.

**Masonry** — a staggered grid layout where each image keeps its own height and the gaps are filled. An Ultimate plan feature.

**Published** — whether an image renders on your storefront. Controlled by a switch on the image's edit screen.

**Shoppable image** — one picture plus the hotspots placed on it.

**Snapshot** — the copy of a product's title, image, and price stored on a hotspot when you attach the product.

---

[← Back to Home](index)
