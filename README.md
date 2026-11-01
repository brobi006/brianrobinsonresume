# Brian Robinson — GitHub Pages Website

This folder contains the website page and the PDF resume link target.

## Files
- `index.html` — the personal website.
- `resume.pdf` — the PDF resume linked from the website.
- `README.md` — these publishing instructions.

A professional-photo placeholder is already built into the page. You can publish the website before adding a photo.

## Publish the website on GitHub Pages

1. Sign in at https://github.com/ (or create a free account).
2. Find your GitHub username. Your website repository must be named exactly:
   `YOUR-USERNAME.github.io`
   Replace `YOUR-USERNAME` with your actual GitHub username.
3. On GitHub, click the **+** button in the top-right and choose **New repository**.
4. Enter the repository name `YOUR-USERNAME.github.io`.
5. Choose **Public**, optionally select **Add a README file**, and click **Create repository**.
6. In the repository, choose **Add file → Upload files**.
7. Upload `index.html` and `resume.pdf` from this folder. Keep both files in the repository's top/root level, not inside another folder.
8. Scroll down and click **Commit changes**.
9. Open the repository's **Settings** tab.
10. Choose **Pages** from the left menu.
11. Under **Build and deployment**, set Source to **Deploy from a branch**.
12. Select branch **main** and folder **/(root)**, then click **Save**.
13. Wait a few minutes. Your site address will be:
    `https://YOUR-USERNAME.github.io`
14. Open that address and test the **View My Resume (PDF)** link.

## Add your professional photo later

1. Choose a professional headshot and save it as `profile.jpg`.
2. Upload `profile.jpg` to the same repository root using **Add file → Upload files**.
3. Open `index.html` in GitHub and click the pencil/edit icon.
4. Find the `div` with class `photo-frame`. It currently contains the words “Professional Photo Goes Here”.
5. Replace the `<span>...</span>` placeholder with this line:

   `<img src="profile.jpg" alt="Professional photo of Brian Robinson">`

6. Click **Commit changes**. Refresh your website after GitHub Pages republishes it.

## Important checks
- The resume file must be named exactly `resume.pdf` because the page links to `resume.pdf`.
- Keep `index.html`, `resume.pdf`, and (when added) `profile.jpg` in the same repository root.
- The GitHub Pages repository must be public for this free public-site setup.
- Your resume includes contact details. Anyone who can access your public website may be able to view and download the PDF, so publish it only if you are comfortable sharing those details publicly.
