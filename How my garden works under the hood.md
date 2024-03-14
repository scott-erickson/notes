# How my garden works under the hood

1. I purchased a $4/mo siteplan with [Blot](https//blot.im) which handles hosting and the recursive "Links to this note" functionality. (I think it's $5 now).
2. I gutted the default theme and made it my own through simple HTML, CSS, and JS. Blot uses Handlebars as a simple templating language. I use BarbaJS for page transitions. The light/dark mode is done through css variables.
3. I connected the subdomain through Cloudflare.
4. I write notes in [Obsidian](https://obsidian.md/).
5. I periodically commit these notes to a remote git repository provided by Blot.
6. It just works.