# James Odiwuor Publishing

Website for books by James Odiwuor, live at
https://jamesodiwuor538-byte.github.io/James-odiwuor-publisher/

The whole site is one file: `index.html`.

## Setting up payments and contact details

Open `index.html`, search for `PUBLISHER SETTINGS`, and fill in:

- `whatsapp`: WhatsApp number for orders, in 254 format (+254119044253)
- `mpesaNumber`: M-Pesa Send Money number+254119044253
- `email`: optional contact email jamesodiwuor538@gmail.com

Anything left as `""` is hidden. Once a WhatsApp number is set, each
"Order this book" button opens a window with the right price and a
prefilled WhatsApp order message.

## Adding a book

Copy one `<article class="title-entry">` block in `index.html`, change the
title, blurb and price, and set `data-book` and `data-price` on its button.

## Previewing locally

    python3 -m http.server 8000

Then open http://localhost:8000
