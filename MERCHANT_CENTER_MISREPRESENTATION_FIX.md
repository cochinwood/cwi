# Fixing the Google Merchant Center "Misrepresentation" Issue — cochinwood.in

**Account:** cochinwood.in — Google Merchant Center Account ID **5595484250**
**Business:** Cochin Wood Industries Private Limited
**Prepared:** 21 June 2026

Google flagged the account for **Misrepresentation**. This is a trust/transparency
issue, *not* a coding bug. Google's automated review decided the website doesn't
clearly prove it's a legitimate, transparent business. Clearing it has two parts:

1. **Publish the trust/policy pages** (provided in `/pages`) on cochinwood.in.
2. **Make business identity consistent everywhere** and **request a review** in
   Merchant Center.

Reviews typically take ~7 business days. Do everything below *before* requesting one —
you don't want a failed review forcing a waiting period before you can try again.

---

## Verified business identity (use these EXACT details everywhere)

These were pulled from your Zoho Books profile and must appear identically on the
website, in Merchant Center, and on any verification documents.

| Field | Value |
|---|---|
| Legal name | Cochin Wood Industries Private Limited |
| CIN | U20219KL2021PTC072862 |
| GSTIN | 32AAJCC9689H1Z5 |
| Address | 146/A, Thoppilan Building, Thuruthy, Kunnathunad Taluk, Kurupampadi, Ernakulam, Kerala, India – 683545 |
| Phone | +91 95674 10175 |
| Email | info@cochinwood.in |
| Website | https://www.cochinwood.in/ |

---

## Step 1 — Publish the policy pages on Zoho Sites

For each HTML file in the `/pages` folder, create a matching page on Zoho Sites:

1. Open **Zoho Sites → Pages → Add Page**.
2. Name the page and set a clean URL (slug):
   | File | Page name | Suggested URL |
   |---|---|---|
   | `contact-us.html` | Contact Us | `/contact-us` |
   | `about-us.html` | About Us | `/about-us` |
   | `return-refund-policy.html` | Return & Refund Policy | `/return-refund-policy` |
   | `shipping-policy.html` | Shipping & Delivery Policy | `/shipping-policy` |
   | `privacy-policy.html` | Privacy Policy | `/privacy-policy` |
   | `terms-and-conditions.html` | Terms & Conditions | `/terms-and-conditions` |
3. Drag an **"HTML / Embed Code"** element onto the page and paste the contents
   of the corresponding file. (Alternatively, paste the visible text into a normal
   text element — the styling is optional, the *content* is what matters.)
4. On the Contact Us page, also drag in Zoho Sites' built-in **Contact Form**
   element and set its recipient to `info@cochinwood.in`.
5. **Publish** each page.

## Step 2 — Link every policy page in the site FOOTER

Google needs these links visible from **every page** of the site. In Zoho Sites,
edit the site **Footer** and add links to all six pages above. The footer should
also show, in text:

> Cochin Wood Industries Private Limited · 146/A, Thoppilan Building, Thuruthy,
> Kunnathunad Taluk, Kurupampadi, Ernakulam, Kerala – 683545 · +91 95674 10175 ·
> info@cochinwood.in · GSTIN 32AAJCC9689H1Z5

## Step 3 — Confirm secure checkout & payment transparency

- [ ] Confirm the whole site loads over **HTTPS** (padlock in the browser). Zoho
      Sites provides SSL — make sure it's enabled and the site doesn't show
      "Not secure".
- [ ] Make sure accepted payment methods are shown (e.g., UPI / cards / netbanking
      icons) near checkout or in the footer.
- [ ] Confirm the **price in the product feed = price shown on the product page =
      price at checkout**, including tax and shipping. Even a ₹1 mismatch can
      trigger Misrepresentation. This is one of the most common real causes.

## Step 4 — Make Merchant Center match the website

In Merchant Center (Account ID 5595484250):

- [ ] **Business information → About your business:** set business name, address,
      phone and email to the *exact* values in the table above.
- [ ] **Business information → Online store URL:** `https://www.cochinwood.in/`.
- [ ] Confirm the **contact email domain** matches your website domain
      (`info@cochinwood.in`) — generic gmail addresses weaken the review.
- [ ] Complete any **business/identity verification** prompts (the "ID check"
      link). Be ready to upload: company registration (CIN), GST certificate, a
      government ID of the authorised representative, and a recent utility bill /
      bank statement showing the business name and address.

## Step 5 — Request the review

1. In Merchant Center, open **Account status / Diagnostics** (the Misrepresentation
   notice).
2. Read the linked Misrepresentation policy, then click **Request review**.
3. If a free-text box is offered, briefly state that you've added Contact, About,
   Return/Refund, Shipping, Privacy and Terms pages (linked in the footer), that
   business identity is consistent across the site and account, that the site is
   secure (HTTPS), and that feed prices match the site.
4. Wait ~7 business days. **Do not** delete or recreate the account — suspensions
   follow the business and the new account will be suspended too.

---

## Pre-submission checklist

- [ ] All six policy pages published and reachable on cochinwood.in
- [ ] All six pages linked in the footer on every page
- [ ] Footer shows legal name, address, phone, email, GSTIN
- [ ] Contact page has a working form / email / phone
- [ ] Site is fully HTTPS, no "Not secure" warnings
- [ ] Product prices: feed = product page = checkout (incl. tax/shipping)
- [ ] Merchant Center business info matches the website exactly
- [ ] Identity/business verification completed
- [ ] Review requested

---

### Notes on editable values
The return window (7 days), refund timeline (7–10 business days), dispatch time
(2–5 business days) and delivery time (5–10 business days) in the policy pages are
sensible defaults for an Indian wood/timber retailer. **Confirm they match how you
actually operate** before publishing — Google checks that the policy matches reality
and matches what your product/checkout pages promise. Adjust the numbers in the
relevant HTML files if needed.
