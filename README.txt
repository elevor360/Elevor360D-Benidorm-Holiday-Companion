Elevor360D Benidorm Holiday Companion V2

CUSTOMER APP: Upload index.html, guide.json, manifest.webmanifest, sw.js, both icon PNG files, elevor360d-logo.png and the adverts folder to your existing GitHub Pages repository. Replace older files.

MANAGER: Keep guide-manager.html on your computer. Import the included guide.json, edit any section, then export and upload the updated guide.json to GitHub.

V2 adds Beaches & coves, Markets & shopping, Nightlife & evenings, and Family activities. Existing planner, packing, spending, favourites, personal notes and backup retain the same localStorage key as V1.1.

Guide information is general and may change. Confirm current opening hours, prices, schedules and local safety advice online.

V3 NEW: interactive online OpenStreetMap, editable map place list with Google Maps directions links, dining and day trips.
Guide Manager: import the included V3 guide.json, edit new sections, then export guide.json.
The interactive map and directions need internet. Personal saved data uses the same storage key as V2.

V3.1: Removed Explore on the map panel and embedded map. Kept place/directions links under Useful information.

V3.2: Added Memorable Visits with venue, category, date, owner/host, details, 0–5 stars, edit/delete, and backup/restore. No changes to guide manager.

V3.3: Added My Holiday Photo Album. Images resized and stored privately in IndexedDB. The Download backup now includes photos as base64 JSON; large albums create large backup files. Restore supports both older backups without photos and new photo-inclusive backups. The Guide Manager remains unchanged. Photos can be lost if browser data is cleared; encourage customers to back up regularly.

CLICKABLE ADVERTS (V3.4):
1. Upload advert JPG/PNG to adverts/ in your GitHub repository.
2. Open guide-manager.html on your computer and import the current guide.json.
3. In Advertisement, tick Show advert, enter e.g. adverts/advert1.jpg and the full https:// website URL.
4. Click Download updated guide.json, then upload it to the root of the same GitHub repository, replacing the old guide.json.
5. Once GitHub Pages publishes the change, customers opening the app online see the latest advert. Tapping the picture opens the advertiser website in a new tab. Offline users see the previously cached version until they reconnect.
6. To replace an advert, upload a new picture using the same filename and export a fresh guide.json from the manager to refresh the advert revision (including when changing it more than once in a day).
