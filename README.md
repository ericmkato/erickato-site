# erickato.com

Static personal brand site: **Work** (Solutions Engineering experience, SE playbook, blog) and **Play** (golf reviews, dash-cam commentary).

## Deploy (Cloudflare Pages)
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → pick this repo.
2. Framework preset: **None**. Build command: *(leave empty)*. Output directory: `/`.
3. After the first deploy, open **Custom domains** and add `erickato.com` and `www.erickato.com`, then add a Redirect Rule sending www to the root (301).

Every push to `main` redeploys automatically.

## Editing content
Blog posts, golf reviews and dash-cam episodes live in the `posts`, `reviews` and `drives` arrays near the bottom of `index.html`.
