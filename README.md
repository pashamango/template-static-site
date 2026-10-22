# template-static-site

Fleet template: static site in the hackt-com shape. Created via **Use this template**.

**When instantiating:** replace `index.html`, set your domain in `CNAME`,
rewrite `llms.txt` / `canon.json`, update `.well-known/agent-card.json`.

## Deploy

Fleet standard: Cloudflare Pages (primary) + IPFS mirror via Pinata.
Any static host works: the output is plain files.

## Files

- `index.html` / `style.css` — the site
- `CNAME` — custom domain (replace `example.com`)
- `llms.txt`, `canon.json` — machine-readable docs
- `robots.txt`
- `.well-known/agent-card.json` — agent-readable repo card

## License

MIT — see [LICENSE](LICENSE).
