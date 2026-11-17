# Beauty Corner – Website

Website for **Beauty Corner**, an artificial jewellery shop (retail & wholesale) at Shop G-1A, Howrah AC Market, 47 Dobson Road, Howrah 711101.

A single static page (`index.html`), with no build step. Every "Enquire" button opens WhatsApp chat with +91 80170 71702 and a ready-written message.

## Adding real photos
Put JPG photos in the `images/` folder with these names. Until a photo is added, a gold jewellery icon is shown in its place.

| Section | File names |
|---|---|
| Collections | `necklace-sets.jpg`, `earrings.jpg`, `bangles.jpg`, `bridal-sets.jpg`, `maang-tikka.jpg`, `rings.jpg`, `hair-accessories.jpg`, `anklets.jpg` |
| Instagram strip | `insta-1.jpg` … `insta-6.jpg` |

Portrait photos (4:5) work best for collections; square photos for the Instagram strip.

## Changing categories or the WhatsApp number
Edit the `COLLECTIONS` list and `WHATSAPP` value near the bottom of `index.html`.

## Publishing (free) with GitHub Pages
Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / root → Save**. The site will be live at `https://rish-25ag.github.io/beauty-corner/` in a minute or two.
