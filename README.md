# LGSC Election Results Website
This is a website that retrieves data from a database (Google Sheet) tied to a google form, and displays all content in a user-friendly format. It was developed for the *LGSC 2025/26 elections*.

**Installation Instructions**
1. Clone the repository
2. Configure the data source (replace the placeholder URL with your own Google Apps Script endpoint), ensuring your Google Scripts deployment is published and accessible to "anyone".
3. Run locally or host using a static site hosting service.

Note: This website requires a Google Scripts deployment to properly run.

**Usage**
1. Open the site in a web browser.
2. The page will automatically fetch data from a linked Google Sheet via a Google Apps Scripts endpoint.
3. Ensure that:
- The Google App Scripts is published and publicly accessible (Deploy > Web App > Anyone).
- The fetch URL in your JavaScript file or <script> tag points to the correct endpoint.
4. Images and other assets are located in the images/ folder and are automatically loaded by index.html.


**Features**
1. User-friendly display with mobile device compatibility. 
2. Content (text) is fully editable via the linked sheet and/or google form without touching the code.
3. Minor edits are required in the codebase for changing images.


**Requirements**
1. All images should be in .webp format to improve performance and reduce load time.

Entire codebase will be commented out soon.

Can be used for future student body elections, preferably for the *Lancaster University Ghana student body*.

**Author**

GitHub: @Projavax