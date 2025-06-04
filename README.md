# Jacksonville Policy Engagement Group Website

This repository contains the static website for the **Jacksonville Policy Engagement Group (JPEG)**.

The site provides information on upcoming events, organizational leadership and ways for Jacksonville residents to get involved in local policy discussions.

## Local Development

The site is fully static. To preview it locally simply open `index.html` in a web browser:

```bash
# from the repository root
open index.html  # use your OS-specific command to open the file
```

All of the HTML and CSS is inline, so no build step is required.

## Deployment

Deployment is handled automatically through [GitHub Pages](https://pages.github.com/). A GitHub Actions workflow defined in `.github/workflows/static.yml` uploads the contents of the repository whenever changes are pushed to the `main` branch. The site is served at the custom domain specified in the `CNAME` file.

To deploy an update, commit your changes to `main` and push. The workflow will publish the site to GitHub Pages.

## Contributing

Feel free to submit pull requests to improve the site or fix any issues. Since the pages are static, changes are typically limited to editing HTML and image assets.

