# Release verification

Check desktop and 390px/320px mobile layouts in Chrome; confirm no horizontal overflow, broken local images or unresolved internal anchors. Exercise light/dark toggle, showcase arrows, photo reel and email copy. Check browser errors and reduced-motion presentation.

Verify the final production URL, favicon, sitemap, robots.txt and social preview return unauthenticated HTTP 200. Confirm canonical/Open Graph/Twitter URLs match the production alias and the preview is 1200 × 630. Run `git diff --check` and verify the remote commit and screenshot files.

External product links and case-study business outcomes are not full integration or employment-history verification. Social-platform cache refresh is outside the site’s control.

## Verified 2026-10-24

Live Chrome checks passed at 1440px, 390px and 320px. No page JavaScript errors, missing anchors, broken images or mobile horizontal overflow were detected. Theme toggle worked; showcase advanced to 02 / 06; reel advanced horizontally; clipboard returned the displayed email address. The production page, preview image, favicon, robots.txt and sitemap returned unauthenticated HTTP 200. Preview dimensions are 1200 × 630 and sharing metadata uses the stable production URL.
