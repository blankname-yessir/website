# Blog

Static blog built by GitHub Pages (Jekyll). No local build needed.

## Publish a post
1. Add a file to `_posts/` named `YYYY-MM-DD-slug.md` with front matter:
   ```
   ---
   layout: post
   title: "Post title"
   ---
   Markdown body...
   ```
2. `git add -A && git commit -m "Post: title" && git push`
3. Live in about a minute.

## Edit homepage
Title and paragraph live in `_config.yml` (`title`, `description`).
