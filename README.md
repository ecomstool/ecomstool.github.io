# ecomstool.github.io

Public website for EcomsTool Chrome extensions, served free by GitHub Pages at **https://ecomstool.github.io**.

It hosts the pages the Chrome Web Store needs: privacy policies, support, and a page for each extension.

## Pages

| URL | File | Used for |
|---|---|---|
| `/` | `index.html` | Home, list of extensions |
| `/fba-calculator/` | `fba-calculator/index.html` | Extension page (Store "Homepage URL") |
| `/fba-calculator/privacy/` | `fba-calculator/privacy/index.html` | Store "Privacy policy URL" |
| `/support/` | `support/index.html` | Store "Support URL" |
| `/privacy/` | `privacy/index.html` | Index of all privacy policies |

## Adding a new extension

1. Copy `fba-calculator/` to a new folder, e.g. `listing-checker/`.
2. Edit the product page and its `privacy/index.html` so the policy describes exactly what that extension reads and stores.
3. Add a card to `index.html` and `privacy/index.html`.

## Rules

- Plain static HTML and one stylesheet. No build step, no JavaScript, no external fonts or scripts.
- A privacy policy must change **before** the extension version that changes data handling is published.
