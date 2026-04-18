## TC Audio Productions standalone site

This folder is a standalone extraction of the existing `TommyC/` site, prepared to become its own Git repository and GitHub Pages site.

### What was changed

- All `"/TommyC/..."` links were rewritten to root-based paths such as `"/"` and `"/blog/..."`.
- Blog canonical links were changed from the old `deleskie.com/TommyC` URLs to root-based canonical paths.
- The old FormSubmit `_next` redirect tied to `deleskie.com/TommyC` was removed so the site no longer depends on the current host.

### Suggested next steps

1. Create a new repository for Tommy's site.
2. Copy the contents of this folder to the new repository root.
3. In GitHub Pages settings, set the custom domain for Tommy's site.
4. Add the matching DNS records at the registrar.
5. After the final domain is known, optionally change the canonical links in `blog/*.html` from root-relative paths to absolute URLs for that domain.
