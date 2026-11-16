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

## Share

<a href="https://p32929.github.io/share/?repo=cacheline"><img src="https://p32929.github.io/readme/share.svg" alt="Share this with your friends in just a click" width="420"></a>

## Support

<a href="https://p32929.github.io/support/"><img src="https://p32929.github.io/readme/support.svg" alt="If you like my works and want to support me, feel free to support" width="420"></a>
