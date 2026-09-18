CARRY & CO. FREE ONLINE SHOP

WHAT THIS VERSION DOES
- Product catalogue
- Tote / Hobo filters
- Add to cart
- Quantity controls
- Cart saved in customer's browser
- Checkout form
- Customer address and contact details
- Cash on Delivery / UPI-Pay-on-WhatsApp selection
- Generates an order number
- Sends the complete order to YOUR WhatsApp

IMPORTANT
This is a static website. It does not have a server/database, so orders are sent to WhatsApp rather than stored in an online admin panel.

SETUP
1. Open script.js.
2. Find:
   const WHATSAPP_NUMBER = "919999999999";
3. Replace it with your WhatsApp number, e.g.:
   const WHATSAPP_NUMBER = "919876543210";
4. Change STORE_NAME.
5. Edit the PRODUCTS list to your actual products/prices.
6. Put your product images in the images folder using:
   tote-1.jpg, tote-2.jpg, tote-3.jpg
   hobo-1.jpg, hobo-2.jpg, hobo-3.jpg

FREE HOSTING
Upload index.html, style.css, script.js and the images folder to GitHub Pages, Netlify or Cloudflare Pages.

ONLINE PAYMENT
The included UPI option is intentionally "Pay on WhatsApp"; it does not automatically collect payment. For automatic UPI/card payments, connect a payment gateway and a backend/order system later.
