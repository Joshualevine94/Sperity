# Putting this online

Two files, free hosting, about fifteen minutes. You end up with a URL to give
Plaid for both "website" and "privacy policy".

## GitHub Pages

1. Make a free account at **github.com** if you have not got one.

2. Click **+** (top right) → **New repository**.
   - Name it `sperity` — the name becomes part of the address, and it is case-sensitive
   - Choose **Public** — Pages needs this on a free account
   - Tick **Add a README file**
   - **Create repository**

3. On the repository page, click **Add file** → **Upload files**.
   Drag in `index.html` and `privacy.html`. Then **Commit changes**.

4. Click **Settings** (top of the repository) → **Pages** in the left sidebar.
   Under **Branch**, choose `main` and `/ (root)`, then **Save**.

5. Wait two or three minutes and refresh. It shows your address, something
   like:

   ```
   https://yourusername.github.io/sperity/
   ```

   The policy is that address with `privacy.html` on the end.

## What to give Plaid

- **Company website** — the main address
- **Privacy policy** — the same address + `privacy.html`

Plaid requires the policy to stay reachable, so leave the repository public.

## Changing anything

Open the file on GitHub, click the pencil icon, edit, commit. Live within a
minute. The name appears in a handful of places in each file — a find and
replace for "Sperity" is all a rename takes.

## A real domain, later

Both files work unchanged behind one. Buy a domain (£10–15 a year), point it
at GitHub Pages, and add it under Settings → Pages → Custom domain. The
hosting stays free.
