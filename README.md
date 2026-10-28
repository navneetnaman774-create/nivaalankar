# Niva Alankar

An online storefront for **Niva Alankar**, a small imitation-jewellery brand. Customers can browse earrings, bracelets, necklaces, rings and anklets, add them to a cart and send their order to the shop in a few taps.

**Live site:** https://navneetnaman774-create.github.io/nivaalankar/

Built for **Prompt War**, with the page designed and written by prompting Claude.

## Features

- **Animated intro:** scrolling columns of product photos, then the logo reveals with a shimmer. It can be skipped with a tap.
- **Hero section:** a photo reel that changes automatically, with the name and price of the product on show.
- **Shop by category:** tap a category tile or tab to filter the collection.
- **Collection:** 11 products with price, short description, occasion tag and stock status.
- **Photo zoom:** tap any product photo to open it full-screen, move between photos with the arrows or by swiping, and add to cart from there.
- **Cart:** change quantities, remove items, see the subtotal, and see how much more is needed for free delivery (free above Rs. 999, otherwise Rs. 49).
- **Checkout:** validates name, 10-digit mobile number, address and pincode, and lets the customer choose UPI, Card or COD. The finished order is prepared as a ready-to-send message to the shop's email (or WhatsApp, if a number is set).
- **FAQ:** tap-to-ask questions about COD, delivery, returns and jewellery care.
- **Contact:** Instagram @nivaalankar and nivaalankar@gmail.com.
- **Responsive and accessible:** works on phones and desktops, follows the device's light or dark setting, and respects reduced-motion settings.

## How it is built

- A single `index.html` file with plain HTML, CSS and JavaScript.
- No frameworks, no build step and no dependencies. Product photos and the logo are embedded in the file.
- Hosted free on GitHub Pages.

## How ordering works

There is no backend. When a customer places an order, the page builds a message with their details, items and total, and opens it in their email app (or WhatsApp). The shop then confirms payment and delivery with the customer directly. Orders are not stored on the site, and stock counts are managed by the shop owner.

## Contact

Instagram: @nivaalankar
Email: nivaalankar@gmail.com
