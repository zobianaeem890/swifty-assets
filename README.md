# Swifty House Cleaning — site assets

Images for the Swifty House Cleaning booking site.
Served over GitHub Pages and loaded by the Google Apps Script web app.

## Do not rename or move these files

The Google Sheet stores the path to each one. Renaming a file breaks it on
the live site. To swap a photo, upload the new file using the SAME name.

## Folders

- `logo/`        light and dark versions of the Swifty logo
- `hero/`        the main photo at the top of the page
- `beforeafter/` paired before and after job photos
- `cleaners/`    cleaner profile portraits

## Adding a new before/after pair

1. Add both files here as `ba-10-<subject>-before.webp` and `ba-10-<subject>-after.webp`
2. Add two rows to the `Content_Images` tab of the Sheet with matching paths
3. The slider picks them up on the next page load
