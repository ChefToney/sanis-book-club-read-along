# Sani's Book Club Read Along

A mobile-friendly, browser-based PDF reader for Sani's Book Club.

## Current starter features
- Open a PDF locally from a phone, tablet, or computer
- Render original PDF pages and illustrations
- Previous/next page navigation and reading progress
- Device-provided text-to-speech controls (play, pause, replay, speed, voice selection)
- Best-effort word highlighting when the browser reports speech boundaries

## Important notes
- PDFs opened with the file picker stay in the visitor's browser; they are not uploaded to this website.
- The current voice is the device/browser's built-in speech voice, **not yet a generated AI narrator**.
- Word-boundary events are not equally supported in every browser. iPhone Safari may highlight words inconsistently.
- Scanned/image-only pages may display correctly but have no selectable text to read aloud.

## Publish with GitHub Pages
In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. GitHub will publish the site at:

https://cheftoney.github.io/sanis-book-club-read-along/

## Next stage
Add the first book's page-specific reading text and narration timing, then upgrade to a consistent AI narrator with synchronized highlighting.