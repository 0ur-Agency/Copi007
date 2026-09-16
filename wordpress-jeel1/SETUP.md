# Jeel 1 one-time setup

## 1. Hostinger / WordPress

1. Install WordPress on `jeel1.com` and enable HTTPS.
2. Install and activate Astra, Elementor, Tutor LMS, WooCommerce, Fluent Forms, WP Mail SMTP, and Tawk.to Live Chat.
3. Set **Settings → Reading** to a static homepage. Set **Settings → General** to Arabic/English brand copy as preferred, and set the site direction to RTL using the language/site settings.
4. Import `jeel1-kit.json` from **Elementor → Tools → Import Kit**. If your Elementor version rejects the kit envelope, import `jeel1-homepage-free.json` through **Templates → Saved Templates → Import Templates** instead.
5. Edit the imported template and set it as the homepage. Replace the image placeholders with optimized, consented photos from the Media Library.

## 2. Brand system

Global colors: Deep Islamic Green `#0F3D2E`, Luxury Gold `#C9A86A`, Cream `#FDF8F0`, White `#FFFFFF`.

Use Tajawal from Google Fonts (weights 400, 500, 700, 800). The template includes RTL-friendly alignment and Arabic copy. Keep all parent/child imagery consented and avoid publishing identifiable children without permission.

## 3. WooCommerce

1. Import `woocommerce-products.csv` at **Products → Import**.
2. Create or select the checkout, cart, account, and shop pages.
3. Configure currency/tax/shipping rules for the selling entity. WooCommerce core does not natively switch EGP/SAR pricing per customer, so use one store currency or a free currency/pricing extension after checking compatibility.
4. Install/configure Paymob for WooCommerce and enable the methods available to your merchant account (Vodafone Cash, Fawry, InstaPay where offered). Add PayPal Standard and/or Stripe only with verified business credentials.
5. Make each plan virtual/download-free and set the matching Tutor LMS course ID in the enrollment automation supplied by your chosen free integration/workflow. Test payment callbacks in sandbox/live mode before launch.

## 4. Tutor LMS

Create courses matching these plan/course slugs: `baraem-8-sessions`, `hafez-12-sessions`, and `family-20-sessions`. Create Halaqas as groups/cohorts, add teachers, and enable student/parent accounts. Add lessons for weekly schedule, recordings, teacher notes, and Werd. Use Tutor LMS progress and assignment reports for the parent dashboard. Public links in the template intentionally point to `/student-dashboard/` and `/book-free-trial/`, so create those pages and adjust slugs if needed.

## 5. Fluent Forms / mail / chat

Create a Fluent Forms form with exactly: Parent Name, Child Age, WhatsApp Number. Put the form shortcode in the final CTA section after creating the form. Configure WP Mail SMTP with Gmail OAuth or an app password and verify deliverability. Paste the Tawk.to property ID in the Tawk.to plugin.

## 6. Launch checklist

- Test RTL on mobile, tablet, and desktop.
- Test free-trial form confirmation and WhatsApp click-to-chat.
- Test every plan through checkout and verify enrollment only after a successful payment callback.
- Test Tutor LMS dashboard with a parent/student test account.
- Remove demo claims/photos if they are not factual. The social proof copy in this starter design is editable placeholder marketing copy.
- Add privacy, terms, refund, safeguarding, and payment-policy pages before accepting real student data.
