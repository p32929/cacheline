# CacheLine

The link-in-bio page for **CacheLine**, a channel of short, funny tech stories with real facts. It lives at **https://p32929.github.io/cacheline/**.

Instead of one link that only goes to one app, this page shows every CacheLine video with its thumbnail, and for each one, every place you can watch it. People land here from any social profile and pick the app they already use.

<img src="brand/cacheline-logo-512.png" alt="CacheLine logo" width="160">

## What is on the page

1. **The newest story up top,** with its date and a "Watch it on" list.
2. **Every video,** newest first, with its thumbnail, title and how many apps it is on.
3. **Every place to watch each one:** tap a video to see its links, for example YouTube, TikTok, Instagram, Facebook, X, Threads, Pinterest or Tumblr.
4. **Direct links to one video:** `?v=<slug>` opens that story straight away, handy for sharing.
5. **Follow links** to all CacheLine profiles, including the WhatsApp channel, in one place.
6. **Light and dark mode.**

## How it works

It is one static page with no build step and no server.

1. `index.html` is the whole page.
2. `videos.json` holds the list of videos, with the date, title, thumbnail and the links to each post.
3. `thumbs/` has the video thumbnails, and `brand/` has the logo.

To add a video, add an entry to `videos.json` and its thumbnail to `thumbs/`, then push. GitHub Pages publishes the change.

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit.

## You might also like

<p><a href="https://openstore.pfay.workers.dev/cards/p32929/0?n=4&amp;repo=cacheline"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=cacheline&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=cacheline&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (1)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/1?n=4&amp;repo=cacheline"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=cacheline&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=cacheline&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (2)"></picture></a><br><a href="https://openstore.pfay.workers.dev/cards/p32929/2?n=4&amp;repo=cacheline"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=cacheline&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=cacheline&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (3)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/3?n=4&amp;repo=cacheline"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=cacheline&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=cacheline&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (4)"></picture></a></p>

<p><a href="https://p32929.github.io/share/?repo=cacheline"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
