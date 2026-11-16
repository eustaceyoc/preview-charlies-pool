# Charlie's Pool Service: sample site

A one-page sample site I put together for Charlie's Pool Service (Lewisville, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-charlies-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to charlieb513@gmail.com, and the phone buttons dial (214) 704-6391. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Charlie's Pool Service's own website and public listings: business name, Lewisville address, phone, email, hours, the services and service areas listed on charliespoolservice.com. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Charlie's Pool Service, its people or its work.

- `yellow-ring.jpg`: "Yellow Swim Ring on Swimming Pool" by Albin Biju on Pexels (https://www.pexels.com/photo/yellow-swim-ring-on-swimming-pool-11322426/)
- `gold-float.jpg`: "Bright Yellow Inflatable Ring in Blue Pool" by ebrar on Pexels (https://www.pexels.com/photo/bright-yellow-inflatable-ring-in-blue-pool-34193740/)
- `pool-ladder.jpg`: "Ladder in Water at Pool" by Komet Flicker on Pexels (https://www.pexels.com/photo/ladder-in-water-at-pool-20774776/)

Fonts: Shrikhand, DM Sans (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
