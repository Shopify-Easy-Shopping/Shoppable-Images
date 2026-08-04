---
layout: default
title: Privacy Policy
description: "How Shoppable Image Hotspots collects, uses, and protects your data"
---

[← Back to Home](index)

---

# Privacy Policy

**Last updated: August 4, 2026**

This Privacy Policy describes how **Shoppable Image Hotspots** ("the App", "we", "us") collects, uses, and retains data when you install and use the App on your Shopify store. By installing the App, you agree to the practices described in this policy.

* TOC
{:toc}

---

## 1. Data We Collect

### 1.1 Merchant Account Data

When you install the App, Shopify provides us with the following store information required to operate the App:

| Data | Purpose |
|------|---------|
| **Shop domain** (e.g., `yourstore.myshopify.com`) | Identifies your store in our database and scopes all data to your account |
| **Shopify access token** | Allows the App to make authenticated API calls on your behalf (e.g., searching products, reading files, detecting theme blocks) |
| **Shopify session data** (state, scope, expiry) | Maintains your authenticated admin session |

We do **not** collect your personal name, email, or payment information through the App installation process.

---

### 1.2 Content Configuration Data

Data you enter when creating or editing content is stored and associated with your shop:

- **Collections** — name and description
- **Shoppable images** — title, the URL of the image file in your Shopify Files library, collection assignment, and published state
- **Hotspots** — position on the image (as X/Y percentages), label text, and the linked product's Shopify ID, handle, title, image URL, and price

Product details are stored as a **snapshot** taken at the moment you attach a product to a hotspot. This is a copy of publicly available product catalogue data from your own store, kept so that storefront product cards render without additional API calls.

---

### 1.3 Analytics & Event Data

The App records storefront interactions to measure hotspot performance. This data is **anonymous** — no personally identifiable information (PII) about your customers is collected or stored.

| Event | Data Recorded |
|-------|--------------|
| **Hotspot click** | Shop domain, hotspot ID, timestamp |

That is the complete record. The App does **not** record IP addresses, user agents, session or device identifiers, referrers, or any customer identity. The App sets **no cookies** on your storefront and does not use any third-party tracking or advertising service on your storefront.

---

### 1.4 Billing Data

Billing is handled entirely by **Shopify's managed billing system**. The App queries Shopify to determine which plan your shop is currently subscribed to, and caches that answer briefly to reduce API calls. The App never receives, processes, or stores your payment card details or financial information.

---

### 1.5 Data We Do NOT Collect

The App does **not** collect or store:

- Customer names, email addresses, or contact information
- Customer IP addresses, device identifiers, or browsing history
- Order, checkout, or cart contents
- Payment card details or financial information
- Passwords or authentication credentials beyond Shopify-issued access tokens
- Any data from storefronts where the App is not installed

The App does not request the `read_customers` or `read_orders` permissions and therefore has no technical access to customer or order data.

---

## 2. How We Use Your Data

### 2.1 To Operate the App

- Authenticating your admin session and securing API requests
- Searching your product catalogue so you can attach products to hotspots
- Listing and uploading images in your Shopify Files library
- Detecting whether the App's blocks have been added to your published theme, so the Dashboard can show the correct next step
- Serving image, hotspot, and collection data to your storefront through the Shopify App Proxy

### 2.2 To Provide Analytics

- Counting hotspot clicks per hotspot and per image
- Calculating totals and averages shown on the Analytics pages

### 2.3 To Enforce Billing Plan Limits

- Determining whether your shop is on the Free or Ultimate plan
- Marking images beyond the Free plan's 3-image allowance as locked, and unlocking them when you upgrade
- Enabling or disabling the plan-gated storefront features (Add to cart, Masonry layout)

### 2.4 To Improve the App

Aggregated, anonymized usage patterns may be used internally to improve App features and performance. This analysis is never tied to individual merchants or their customers.

---

## 3. Data Sharing & Third Parties

We do **not** sell, rent, or share your data with third parties for marketing or advertising purposes.

Data may be shared only in the following limited circumstances:

| Recipient | Reason |
|-----------|--------|
| **Shopify** | The App operates within the Shopify platform. Shopify processes and routes API calls, App Proxy requests, webhook events, and all billing. See [Shopify's Privacy Policy](https://www.shopify.com/legal/privacy). |
| **Hosting / infrastructure providers** | The App's server and database are hosted on cloud infrastructure. Providers are bound by data processing agreements and do not have independent access to your data. |
| **Law enforcement / legal process** | If required by applicable law, court order, or regulatory obligation, we may disclose data to the extent legally required. |

---

## 4. Data Retention

### 4.1 Active Installation

While the App is installed on your store, we retain:

| Data Type | Retention Period |
|-----------|-----------------|
| Session tokens | Until the session expires or you uninstall the App |
| Collections | Indefinitely while the App is installed |
| Shoppable images | Indefinitely while the App is installed |
| Hotspots (including product snapshots) | Indefinitely while the App is installed |
| Hotspot click records | Indefinitely while the App is installed |

You may delete any of this data yourself at any time from within the App. Deleting an image also deletes its hotspots and their click history; deleting a hotspot deletes its click history.

### 4.2 After Uninstallation

When you uninstall the App, Shopify revokes the access token immediately and sends the `app/uninstalled` webhook, at which point the App deletes your stored session records.

Shopify then sends the `shop/redact` webhook **48 hours after uninstallation**. On receiving it, the App permanently deletes **all remaining data associated with your shop**:

- All shoppable images
- All hotspots and their product snapshots
- All hotspot click history
- All collections
- Any remaining session records

If you reinstall the App after this window, you will start with a clean slate.

### 4.3 Customer Data Requests

Shopify may forward a `customers/redact` or customer data request webhook on behalf of one of your customers. Because the App stores **no customer personal data of any kind**, there is nothing to return or erase; the App acknowledges these requests and takes no further action.

### 4.4 Before Uninstalling

Analytics history is deleted along with everything else after uninstallation. If you want a record of your click data, note it down from the Analytics pages before you uninstall.

---

## 5. Merchant Rights

### 5.1 Right to Access

You may request a copy of all data we hold associated with your shop domain by contacting us at the support email below. We will provide a response within **30 days**.

### 5.2 Right to Correction

Collections, images, and hotspots can be corrected directly through the App's admin interface at any time. For account-level corrections (for example, a billing plan discrepancy), contact our support team.

### 5.3 Right to Deletion

You have the right to request deletion of all your data at any time, without waiting for the automatic post-uninstall purge.

To request immediate deletion:

1. Uninstall the App from your Shopify admin.
2. Contact us at the support address below with your shop domain and a deletion request.
3. We will confirm deletion within **7 business days**.

> **Note:** Deleting your data is irreversible. All collections, images, hotspots, and analytics history will be permanently removed.

### 5.4 Right to Restrict Processing

If you wish to stop click data being recorded without uninstalling the App, turn the **Published** switch off on each image, or remove the App's blocks from your theme. With no blocks rendering, no click events are generated.

### 5.5 Right to Data Portability

You may request an export of your data in a machine-readable format (JSON or CSV). Contact us at the support address below with your shop domain and export request.

---

## 6. Security

We implement reasonable technical and organizational measures to protect your data:

- Shopify access tokens are stored encrypted at rest
- All data transmissions between the App and Shopify use HTTPS/TLS
- App Proxy endpoints are verified as originating from Shopify storefronts, and only ever return published, unlocked image and hotspot data for the requesting shop
- All records are scoped to a single shop domain; no data is shared across merchants
- Database access is restricted to application processes only; no public database endpoints are exposed

No system is completely secure. If you believe your account has been compromised, contact us immediately.

---

## 7. Children's Privacy

The App is intended for use by Shopify merchants operating commercial stores. It is not directed at children under the age of 13, and we do not knowingly collect data from children.

---

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the App after changes are posted constitutes your acceptance of the updated policy.

For material changes, we will notify merchants via a banner in the App admin.

---

## 9. Contact

If you have questions, concerns, or requests related to this Privacy Policy, please contact us:

**Email:** joomlageek.com@gmail.com
**Response time:** Within 2 business days

---

[← Back to Home](index)
