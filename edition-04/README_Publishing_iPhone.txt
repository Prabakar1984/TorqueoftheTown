Torque of the Town — Issue 04: iOS / Android publication package

IMPORTANT: Publish the WHOLE folder as a website over HTTPS.
The working paths MUST be:
  /index.html
  /assets/treatment_simulation_ios.mp4
  /iPhone_Compatibility_Test.html  (optional technical test)

Example: upload the entire directory under an edition-04 folder at your existing newsletter website, then provide its HTTPS URL. Do not share an .html attachment or a link to a ZIP preview as the primary iPhone reading experience.

For the video, configure the web server or CDN to return Content-Type: video/mp4, allow HTTP Range: bytes requests and return 206 Partial Content when appropriate. The MP4 is H.264/AAC with fast-start metadata.

Submission: the iPhone buttons use https://wa.me/..., navigating in the same Safari tab. Android retains its working WhatsApp application protocol. Safari typically preserves tab position when users return from WhatsApp, but iOS controls app switching and permission screens.

To verify on iPhone, open iPhone_Compatibility_Test.html via HTTPS in Safari. The test WhatsApp link is an ordinary link with no JS. After that, test the form and the video in the full newsletter.

The PDF here is unchanged; only the web submission/media delivery mechanism was adjusted.
