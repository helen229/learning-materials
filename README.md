# Learning materials

Independent learning guides, each in its own directory. The root page is a directory of guides; individual guides retain their own content, design and navigation.

## Current guides

- [Identity, OAuth and tokens](identity-guide/index.html)

## Add, update or remove a guide

1. Add each new guide as `<topic-name>/index.html`, using a lowercase, hyphenated directory name. Keep any supporting assets in that directory and use relative links.
2. Add a link to the guide on the root `index.html` page and in this list.
3. Update a guide by editing its directory. Remove a guide by deleting its directory and its directory-page links.
4. Commit and push changes to the Pages publishing branch. Once configured, GitHub Pages publishes changes automatically.

Review all content before publishing. A private repository does not make a standard GitHub Pages website private. Do not add credentials, private notes or personal information to published content.

## GitHub Pages setup

For a personal private repository, GitHub Pro is required for GitHub Pages. Do not change repository visibility to work around a plan restriction.

In repository Settings → Pages, choose **Deploy from a branch**, select the intended publishing branch (normally `main`), select **/ (root)** and save. The `.nojekyll` file lets the standalone HTML pages publish without Jekyll processing.

Use the deployment URL shown by GitHub. The identity guide is at `identity-guide/` beneath that URL. Verify both the directory page and the guide after deployment.
