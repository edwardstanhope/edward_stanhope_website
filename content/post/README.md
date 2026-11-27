# Adding post 1 to your blogdown site

**Post:** BEACON: Shining a light on exercise oncology research
**Bundle folder:** `beacon-shining-a-light/` (contains `index.md` and `featured.png`)

## Steps

1. **Copy the folder.** Put the whole `beacon-shining-a-light/` folder into your site's `content/post/` folder, so you have:
   ```
   content/post/beacon-shining-a-light/index.md
   content/post/beacon-shining-a-light/featured.png
   ```
   (Or unzip `beacon-01-hugo-post.zip` at your site root; it creates the same folder.)
2. **Fill in the placeholders** in `index.md`:
   - `[BEACON URL]` appears twice (closing call to action and Further reading). Search for it and replace with the link to your BEACON page. To make it a link, use `[BEACON Background and Chapter 1](https://your-url)`.
   - `date:` and `lastmod:` are set to 2026-12-01. Change them if you publish on another day.
3. **Check the config once.** The interactive boxes and the Figure 2 simulator are raw HTML and a script, so your `config.yaml` (or `hugo.yaml`, or `config/_default/params...`) must have:
   ```yaml
   markup:
     goldmark:
       renderer:
         unsafe: true
   ```
   If you use `config.toml`, the equivalent is `[markup.goldmark.renderer]` then `unsafe = true`.
4. **Preview.** In RStudio, run `blogdown::serve_site()`. Open the post and check that:
   - the boxes are styled (not shown as plain text or code);
   - the "Try it" simulator moves when you drag a slider or click a scenario button;
   - the citation links jump to the reference list.
   If the boxes show as raw text, step 3 is the fix. Drafts only appear in preview, which is expected.
5. **Publish.** Change `draft: true` to `draft: false`, then build and deploy as you normally do (for example `blogdown::build_site()` and push, or let Netlify build from your repository).
6. **After publishing:** put the live post URL into the social posts in `beacon-01-output-package.md` (replace `[BLOG URL]`), and upload the final `index.md` to the Project files so later posts avoid repeating it.

## Other files in this folder

- `beacon-01-output-package.md`: assumptions, title options, learning design, image list, metadata, the LinkedIn and X posts, the reference check log and the quality checklist.
- `beacon-hero.svg`: the editable source of `featured.png`.
- `beacon-01-hugo-post.zip`: the bundle folder, zipped.
