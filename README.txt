
GH Pages Starter — ReDoc + OpenAPI

How to publish in ~2 minutes:

1) Create a new GitHub repo (public).
2) Put these two files in the root of the repo:
   - index.html
   - openapi.yaml
3) Commit & push. Then open repo Settings → Pages →
   - Source: "Deploy from a branch"
   - Branch: "main" (or default), Folder: "/ (root)"
   - Save. GH Pages will give you a URL like:
     https://<your-username>.github.io/<repo-name>/
4) Share that URL. ReDoc renders your openapi.yaml on that page.

Updating the spec:
- Edit / replace openapi.yaml and push; the page updates automatically.
