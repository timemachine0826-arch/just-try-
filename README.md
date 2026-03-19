# WFLMS Chinese Department Site

This folder is ready to deploy as a static website.

## Contents

- `index.html`: homepage
- `assets/logo.png`: school logo
- `assets/baihuajie-campus.png`: official campus header image

## Fast Publish

### Option 1: Cloudflare Pages

1. Open Cloudflare Pages.
2. Create a new project.
3. Upload this folder directly, or connect a Git repository containing this folder.
4. No build command is needed.
5. Output directory can be left blank or set to `/`.

### Option 2: Netlify Drop

1. Open Netlify.
2. Drag the whole `wflms-chinese-site` folder into the deploy area.
3. Netlify will generate a public URL automatically.

## Custom Domain

If the school wants a formal domain such as `chinese.wflms.cn`, the IT team needs to:

1. Create the subdomain DNS record.
2. Bind the domain in the hosting platform.
3. Complete filing requirements if the site is hosted on mainland China servers.

## Notes

- The homepage file must stay named `index.html`.
- Keep the `assets` folder in the same directory as `index.html`.
- If you replace images later, keep the same filenames or update the paths in `index.html`.
