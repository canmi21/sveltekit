---
'@sveltejs/adapter-cloudflare': patch
---

fix: dispose the platform proxy so a build no longer leaks a `workerd` process
