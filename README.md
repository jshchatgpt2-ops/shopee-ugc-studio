# Shopee Affiliate UGC Studio
Vercel-ready Next.js app using the Magica reference-to-video API supplied in the request.

## Deploy
1. Import this folder/repository into Vercel.
2. Add `MAGICA_API_KEY` in Vercel Environment Variables.
3. Add `MAGICA_UPLOAD_ENDPOINT`: an upload endpoint that accepts multipart field `file` and returns JSON `{ "url": "https://..." }`. Magica's example accepts `image_urls`, so browser-selected files must first become reachable URLs.
4. Deploy.

The API key is only used in server routes and is never sent to the browser.
