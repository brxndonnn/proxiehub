# ProxyHub

Simple reverse proxy to bypass CORS.

---

### Features:
 - Deployable on many platforms
 - Header rewrites
 - Bypass CORS
 - Secure it with Turnstile
 - Parse and bypass m3u8 stream restrictions
 - Caching of TLS segments (disable with DISABLE_CACHE=true in .env)

> [!WARNING]
> Turnstile integration only works properly with cloudflare workers as platform

### Supported platforms:
 - Cloudflare workers
 - AWS Lambda
 - NodeJS
 - Netlify edge functions
