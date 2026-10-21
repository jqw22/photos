# photos

A photo gallery of my Nostr posts tagged **#photography**, shown in a scrolling grid.

Live at https://jqw22.github.io/photos/

The page is a single static file (`index.html`) with no build step. It connects straight to public Nostr relays from your browser, fetches posts from `npub1aqz7wpp99fg4c8qpasyp7yeg735x0vg8le7c4h4shgfhsxlwhmfqg3w3pe`, and keeps the ones tagged #photography.

## Changing it

Edit the settings at the top of the script in `index.html`:

- `NPUB`: the account to show
- `HASHTAG`: the tag to filter on (without the `#`)
- `RELAYS`: the relays to query
