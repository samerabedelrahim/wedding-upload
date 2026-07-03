# Fixed QR Link

Upload this folder to GitHub Pages.

The printed QR code should point to your GitHub Pages URL, for example:

```text
https://YOUR-GITHUB-USERNAME.github.io/wedding-upload/
```

When the Cloudflare tunnel link changes, edit `index.html` and update this line:

```js
const uploadUrl = "https://YOUR-CLOUDFLARE-LINK.trycloudflare.com/?code=quLvBZmoOq6-";
```

Do not remove the `?code=quLvBZmoOq6-` part.
