# Williams Custom Carpentry — website

The public website for williamscustomcarpentry.com. GitHub Pages hosts it for free, straight from this repository.

- **Pages:** 14 pages, plus `404.html` for wrong addresses. Photos are in `img/`, and fonts and logos are in `site-assets/`.
- **Request an Estimate:** the form on `request-an-estimate.html` sends to the WCC Estimator at `https://office.williamscustomcarpentry.com/api/estimate-request`. Requests appear in the estimator's **Requests** tab. If the estimator is ever down, the website still works, and the form tells people to call.
- **Domain:** the `CNAME` file tells GitHub Pages the site's address is `www.williamscustomcarpentry.com`. The bare `williamscustomcarpentry.com` address redirects to it.
- **Search engines:** `robots.txt` and `sitemap.xml` help them find every page.

To change something: open the file on GitHub, click the pencil to edit it (or upload a replacement file), then click **Commit**. The live site updates in a minute or two.
