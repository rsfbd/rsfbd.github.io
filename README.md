# Kairoos site (temporary)

This repo is a **temporary** static site. It exists only so the TikTok developer portal has public,
verifiable URLs for Kairoos's home page, Privacy Policy and Terms of Service, which its app review
requires.

Kairoos itself is not hosted here: it runs locally. When Kairoos gets a real public site, this repo
is replaced and can be deleted.

- `index.html`, `privacy.html`, `terms.html`: the pages.
- `tiktok*.txt` (added later): the signature file TikTok generates to verify the URL prefix. Keep it
  at the root, or the verification breaks.
