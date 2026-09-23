# GuptaSec4AI · AI4Sec migration

Display name: **GuptaSec4AI · AI4Sec**  
Tagline: **Security for AI · AI for Security**  
Target website: https://gupta-sec4ai-ai4sec.github.io/

## Status

Branding is prepared locally. Organization creation, repository creation, upload and Pages activation are not completed. The existing origin still points to LeakDetectAI/leakdetectai.github.io.

## Publish without rebuilding

1. Sign in to GitHub and create the free organization `gupta-sec4ai-ai4sec` if the name is available. Keep the existing personal account.
2. Under that organization, create the public repository `gupta-sec4ai-ai4sec.github.io` without initializing files.
3. Review the working-tree changes, including existing tracker edits, and commit the intended site files. Do not include `.DS_Store` files.
4. Add the destination as a second remote and push the committed site:

```sh
git remote add organization git@github.com:gupta-sec4ai-ai4sec/gupta-sec4ai-ai4sec.github.io.git
git push organization main
```

5. In the new repository, select Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
6. Verify the homepage, publications, CV, images, PDFs and `research-deadlines.html` at the new address before changing the old site.
7. After verification, optionally replace old-site HTML pages with redirects preserving their paths. Retain the old repository to keep those redirects available. GitHub repository redirects do not substitute for website redirects.

No CNAME is needed for an organization.github.io address. The website uses relative links, so the existing files work at either host. Keep LeakDetect as a separate project; no project repositories have been moved.

GitHub reference: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
