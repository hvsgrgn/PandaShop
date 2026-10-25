# PandaShop 🐼🌿

A three-page website for a fictional shop that sells hyper-realistic faux plants, built with HTML, CSS, Bootstrap 5 and a little JavaScript.

## Pages

- **Home** (`index.html`): an animated flower intro, an image carousel of new bouquets, and sale tiles showing the original and discounted prices.
- **Shop** (`shop.html`): a product list with descriptions and prices, a working cart counter, and a "We'll help you choose!" table that matches plants to interior design styles.
- **Q&A** (`faq.html`): frequently asked questions, a care video with a full transcript, and a contact form.

## Features

- **Responsive layout** using the Bootstrap grid and custom media queries, so it works on phones, tablets and desktops
- **Frame-by-frame intro animations**, made from PNG image sequences played with JavaScript
- **Cart counter** that is saved in `localStorage`, so it remembers your count after a reload. Adding an item shows a Bootstrap toast notification.
- **Lightbox**: click a product photo in the shop to see it full size
- **Print stylesheet** (`print.css`) with a separate layout for printing. It hides interactive parts like the video and swaps links for plain-text versions.
- **Accessibility**: alt text on images, `aria` labels, "skip to" links for keyboard users, and a video transcript

## Running it

There's nothing to install. Download or clone the repo and open `index.html` in a browser. Bootstrap and the fonts load from a CDN, so you need an internet connection.

## Built with

- HTML5 and CSS3
- [Bootstrap 5.3](https://getbootstrap.com/) and Bootstrap Icons
- Vanilla JavaScript
- The [Parisienne](https://fonts.google.com/specimen/Parisienne) font from Google Fonts

## Notes

- This was a university web development assignment. PandaShop is fictional, and there's no real checkout.
- The plant care video is from the [Blooming Artificial](https://www.youtube.com/@BloomingArtificialCoUK) YouTube channel and is used for educational purposes.
