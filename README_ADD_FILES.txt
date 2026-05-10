============================================================
  RAMACHANDRA TRADERS WEBSITE — FILE GUIDE
  How To Add Your Photos, Videos, Logo & Links
============================================================

Welcome! This guide explains where to put your files so
they automatically appear on your website.

------------------------------------------------------------
1. LOGO
------------------------------------------------------------
Folder: assets/logo/

→ Add your logo image here (logo.png is already placed).
→ Supported formats: .png, .jpg, .webp
→ The logo will automatically show in the Navbar, Hero,
  and Footer sections.

------------------------------------------------------------
2. HOMEPAGE GALLERY PHOTOS
------------------------------------------------------------
Folder: assets/gallery/

→ Add any photos you want shown in the homepage Gallery.
→ Supported: .jpg, .jpeg, .png, .webp
→ They will appear in the Gallery section automatically.

------------------------------------------------------------
3. HOMEPAGE VIDEOS
------------------------------------------------------------
Folder: assets/videos/

→ Add videos you want shown in the homepage Gallery.
→ Supported: .mp4, .webm
→ They will appear alongside photos in the Gallery section.

------------------------------------------------------------
4. CATEGORY PHOTOS
------------------------------------------------------------
Add photos for each business category in these folders:

  assets/categories/tiles/           → Tiles photos
  assets/categories/paints/          → Paints photos
  assets/categories/electrical/      → Electrical photos
  assets/categories/interiors/       → Interior photos
  assets/categories/home-materials/  → Home Materials photos

→ When a visitor clicks a category card, they will see
  all photos you added in that folder.

------------------------------------------------------------
5. ACHIEVEMENT PHOTOS
------------------------------------------------------------
Folder: assets/achievements/photos/

→ Add photos of your shop, projects, awards, events, etc.
→ They will appear in the "Our Achievements" section.

------------------------------------------------------------
6. ACHIEVEMENT VIDEOS
------------------------------------------------------------
Folder: assets/achievements/videos/

→ Add video files (.mp4 or .webm) of achievements here.
→ Videos will show with a play button in the section.
→ Sound is supported when opened in fullscreen popup.

------------------------------------------------------------
7. SOCIAL MEDIA LINKS
------------------------------------------------------------
File: config/social-links.js

→ Open this file in any text editor (Notepad, VS Code).
→ Replace the placeholder URLs with your real profile links.
→ Save the file. Done!

Platforms supported:
  - Instagram
  - Facebook
  - YouTube
  - X (Twitter)
  - Threads

------------------------------------------------------------
8. HOW TO OPEN THE WEBSITE
------------------------------------------------------------
→ Open the file: index.html
→ Double-click it — it will open in your browser.
→ No internet required. Works offline!

------------------------------------------------------------
NOTE ABOUT AUTO LOADING
------------------------------------------------------------
Because this is a plain HTML website (not a server),
photos/videos added to folders need to be registered
in the media manifest files:

  config/gallery-media.js        → Homepage gallery
  config/achievements-media.js   → Achievements section
  config/category-media.js       → Category galleries

Open each file and follow the simple instructions inside
to add your file names. It only takes a minute!

============================================================
  Need help? Everything is clearly commented in the code.
============================================================
