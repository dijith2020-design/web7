KRISHNA CATERING SERVICES WEBSITE DRAFT

Files:
- index.html: complete single-page website (CSS and JavaScript are included in this file)
- assets/: original user-supplied photos, copied without beautification, plus the supplied logo image

HOW TO PREVIEW
1. Keep index.html and the assets folder together.
2. Open index.html in a browser, or use a local preview extension in your editor.

HOW TO ADD TO GITHUB
1. Create a new branch (for example: website-preview) before changing the live branch.
2. Upload index.html and the complete assets folder to the same folder where your static website entry point belongs.
3. If your current project already has an index.html or uses a framework, do not replace it blindly. First check the current entry point and Cloudflare build setup.
4. Preview the branch/deployment before merging to the production branch.

EDIT CONTACT DETAILS
Open index.html and find: const KCS_CONFIG = {
Fill phoneDisplay, phoneDial, whatsappNumber, and enquiryEmail with real details.

EDIT TEXT
Find the relevant heading/paragraph in index.html and change the text.

REPLACE PHOTOS
Replace a photo in assets/ with the new photo and keep the same filename, or change the corresponding src="assets/filename" in index.html. Use the original images as supplied; do not edit them unless you choose to.

NOTES
- No dependencies or build configuration are added.
- The enquiry form uses mailto and does not store/send form data to a server.
- Industrial client cards use supplied general canteen photos as illustrative images; they are explicitly noted as not being site-specific photos. Replace them with verified site photos when available.
- Verify the FSSAI wording and the experience claim before public launch.
