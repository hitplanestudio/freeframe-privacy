# FreeFrame privacy policy

Public privacy-policy webpage for **FreeFrame**, published by **Hit Plane Studio**.

- Website: [hitplanestudio.github.io/freeframe-privacy](https://hitplanestudio.github.io/freeframe-privacy/)
- Privacy and support: [hitplanestudio@gmail.com](mailto:hitplanestudio@gmail.com)
- Android application ID: `com.hitplanestudio.freeframe`

`index.html` is a complete, responsive static page with inline styling, section navigation and print styles. It needs no JavaScript, packages, build process, fonts or other downloaded assets. Its code adds no analytics, cookies, browser storage, advertising or forms. GitHub Pages handles hosting requests under GitHub's own privacy practices.

## GitHub Pages configuration

This repository is named **freeframe-privacy** and is public. In **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/ (root)**, then save. Keep HTTPS enabled. The entry file is `index.html`; `.nojekyll` tells Pages to serve these static files directly.

The expected public URL is:

**https://hitplanestudio.github.io/freeframe-privacy/**

After publication, open that address without signing in and use it in FreeFrame's Google Play Console privacy-policy field. The Android app has an offline policy entry before photo access and in Settings, plus a link that opens this public address in a browser.

## Maintaining the policy

The text describes FreeFrame's local media processing and Google Play Billing 9.1.0 integration, including its supporting libraries. Update both the website and the policy bundled with the app whenever its permissions, SDKs or data handling change. Revise the effective date when the policy changes. Verify the actual release code instead of reusing blanket “no data collected” or “no internet permission” claims.

Only these public website files belong in this repository: `index.html`, `.nojekyll` and this README. Android source, signing keys, credentials, user media and local app data are excluded.

Hosting reference: [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).
