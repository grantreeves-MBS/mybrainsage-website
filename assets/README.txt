My Brain Sage website - assets folder

Ruby's graphic assets go here when they arrive. The website is built to expect
the following files by these exact names. Drop the files in with these names
and the site picks them up with the one-line edits noted in WEBSITE_BUILD_NOTES.md.

EXPECTED FILES

logo.svg
  The My Brain Sage logo for the site header. SVG preferred so it scales
  cleanly at any size. A small horizontal lockup (mark plus wordmark) suits
  the header best. If only a PNG is supplied, name it logo.png and adjust
  the header img tag accordingly.

favicon.png
  The browser-tab icon. 32x32 or 48x48 pixels. Can be derived from the app
  icon. A favicon.ico is also fine if that is what is supplied.

og-image.png
  Optional. A social-share preview image, 1200x630 pixels, shown when a
  website link is shared on social platforms or in messages. Can wait.

UNTIL THE ASSETS ARRIVE

The site runs perfectly without them. The header shows the text wordmark
"My Brain Sage", which is the correct fallback. Nothing is broken by their
absence. See WEBSITE_BUILD_NOTES.md for how to slot each one in.
