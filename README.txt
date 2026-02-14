VALENTINE'S CARD WEBSITE
=======================

Open index.html in your browser (double-click or right-click → Open with → your browser).

ADD YOUR OWN PHOTOS
-------------------
Replace the image URLs in index.html with your own:

1. Find the three <div class="slide"> blocks in the first slideshow (Screen 1).
2. Replace each src="https://..." with your photo path, e.g.:
   - src="photos/us1.jpg"  (if you put images in a "photos" folder next to index.html)
   - or a full URL to an image online

3. Do the same for the three slides inside <div class="photos-stack" id="photosStack"> (Screen 2) so the same photos animate upward.

Example for local folder:
  Put your images in: valentines-card/photos/us1.jpg, us2.jpg, us3.jpg
  Then use: src="photos/us1.jpg", src="photos/us2.jpg", src="photos/us3.jpg"

BOUQUET PHOTO (Screen 3)
-------------------------
Replace the bouquet image on the final screen:
  - In index.html, find the <img> inside the bouquet-wrap div (near "Happy Valentines Day").
  - Change the src to your photo: e.g. src="bouquet.jpg" (put bouquet.jpg in the same folder as index.html), or src="photos/bouquet.jpg", or a full image URL.

CALENDAR BUTTON
---------------
The "Add to calendar" button opens Google Calendar with a new event on Feb 27, 2026 (7:00 PM–10:00 PM). She can change the time or title after opening.
