# Publish on Zoho Sites — click-by-click guide (cochinwood.in)

This is the exact sequence to publish the 6 policy pages and footer. The page
content lives in the [`pages/`](./pages) folder — open each `.html` file, select
all, copy, and paste where indicated below. Total time ≈ 15 minutes.

> You must be logged in to your Zoho account to do this. Nobody else can publish
> to your site on your behalf — it's gated behind your login + 2FA.

---

## Step 0 — Open the editor
1. Go to **https://sites.zoho.in** (or sites.zoho.com) and sign in.
2. Open the **cochinwood.in** website → click **Edit / Builder** to open the editor.

## Step 1 — Create the 6 pages
Do this six times, once per file in `pages/`:

| # | Page title | URL slug | Source file |
|---|---|---|---|
| 1 | Contact Us | `contact-us` | `pages/contact-us.html` |
| 2 | About Us | `about-us` | `pages/about-us.html` |
| 3 | Return & Refund Policy | `return-refund-policy` | `pages/return-refund-policy.html` |
| 4 | Shipping & Delivery Policy | `shipping-policy` | `pages/shipping-policy.html` |
| 5 | Privacy Policy | `privacy-policy` | `pages/privacy-policy.html` |
| 6 | Terms & Conditions | `terms-and-conditions` | `pages/terms-and-conditions.html` |

For each row:
1. In the left panel click **Pages → Add Page → Blank Page**.
2. Set the **page name** (column "Page title") and the **page link/URL** (column "URL slug").
3. On the blank page, from the **Elements** panel drag an **“Embed Code” / “HTML”**
   element onto the page body.
4. Open the matching source file, **select all (Ctrl+A) → copy (Ctrl+C)**, and
   **paste** it into the embed/HTML box. Click **Apply/Save**.
5. (Contact Us only) Also drag a **Form** element onto the page and set its
   **notification/recipient email** to `info@cochinwood.in`.

> Prefer not to use the HTML element? Use a normal **Text** element instead and
> paste the visible text — the styling is optional; the *content* is what Google
> checks.

## Step 2 — Build the footer (shows on every page)
1. Click the site **Footer** area to edit it.
2. Add a **menu/links block** with links to all six pages above.
3. Add a **Text** block containing exactly:

```
Cochin Wood Industries Private Limited · 146/A, Thoppilan Building, Thuruthy,
Kunnathunad Taluk, Kurupampadi, Ernakulam, Kerala – 683545 · Phone: +91 95674 10175 ·
Email: info@cochinwood.in · GSTIN: 32AAJCC9689H1Z5
```

## Step 3 — Publish & verify
1. Click **Publish** (top-right).
2. Open **https://www.cochinwood.in** in a new tab and confirm:
   - [ ] The browser shows a **padlock / HTTPS** (not “Not secure”).
   - [ ] All **six footer links** open the correct pages.
   - [ ] The footer shows name, address, phone, email, GSTIN on every page.

## Step 4 — Then go to Merchant Center
Once the site is live, follow `VERIFICATION_AND_REVIEW_REQUEST.md`:
match the business info, complete verification, and click **Request review**
using the prepared text. Google’s review then takes ~7 business days.

---

### Reminder on editable values
Confirm the return window (7 days), refund timeline (7–10 business days), dispatch
(2–5 business days) and delivery (5–10 business days) in the Return/Refund and
Shipping pages match how you actually operate before publishing.
