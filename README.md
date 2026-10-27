<p align="center">
  <img src="assets/icon.png" width="96" alt="VidAtlas logo">
</p>

<h1 align="center">VidAtlas</h1>

<p align="center">
  VidAtlas (formerly Shorts Trend Finder) is a Windows app for finding high-performing YouTube Shorts and long-form videos in any niche, using live data from the official YouTube Data API v3.
</p>

<p align="center">
  <a href="https://github.com/Hamadullah123/VidAtlas-Releases/releases/latest"><b>⬇ Download the latest version</b></a>
</p>

---

## Features

The sidebar has **Discover** (with **Shorts** and **Long Form**), **Library** and **Settings**.

- **Shorts and Long Form:** two separate research pages with the same tools. Each keeps its own search, results and history, and their results never mix.
  - **Shorts** shows only videos that meet YouTube's Shorts format: up to 3 minutes and vertical or square, both checked through the API.
  - **Long Form** shows videos 4 minutes and longer by default, with 4–10, 10–20, 20–60 and 60+ minute filters, on larger 16:9 cards.
  - Find the top videos whose *title* contains your keyword, using Exact phrase, All keywords or Any keyword matching.
  - Open **Niches** to browse 10 categories (Gaming, Technology, Finance & Business…), each with sub-niches you can customise. Official YouTube categories are labelled separately from the app's own presets.
  - Click the search bar to see your recent searches, or open **History** for the full list.
- **Sorting:** **Find videos by** Most viewed or Relevance, then set the **Display order** to Default, Newest first or Oldest first. Display order re-arranges the videos you've found by upload time, instantly and without using a search.
- **Filters:** last 24 hours, 7 days, 30 days or custom dates; minimum views; length; language and region.
- **Library:** bookmark videos, organise them into collections and add your own notes, with your saved searches in a second tab so you can rerun them in one click. Filter by **All, Shorts or Long Form**.
- **Automatic updates:** signed and verified before they install, with a What's new page after each update. An optional beta channel is in **Settings → Updates**.
- **Usage:** a quota tracker in the sidebar, plus a daily chart in **Settings → Usage** of the search requests and API units you've used.

## Install

1. Download **VidAtlas-Setup-x.y.z.exe** from the [latest release](https://github.com/Hamadullah123/VidAtlas-Releases/releases/latest).
2. Run it. The installer isn't code-signed, so if Windows SmartScreen appears, click **More info → Run anyway**.
3. VidAtlas updates itself. It checks quietly in the background, downloads and verifies new versions, and asks before restarting. You can also check in **Settings → Updates**.
4. Already using Shorts Trend Finder? Install VidAtlas over it, or let your copy update. Your key, library, searches, history and settings move over automatically.

## You need your own free YouTube API key

No API key is included, and API keys must not be shared. To create one:

1. In [Google Cloud Console](https://console.cloud.google.com/apis/library/youtube.googleapis.com), create a project and enable **YouTube Data API v3**.
2. Go to **APIs & Services → Credentials → Create credentials → API key**, and restrict the key to *YouTube Data API v3*.
3. Paste the key into the app's **Settings**. It's stored on your PC only, encrypted by Windows.

It's free: Google gives each project about 100 searches a day.

## Notes

- All data comes live from YouTube. Results are a sample from YouTube's search index and may not include every matching video.
- **Relevance** is YouTube's own search order, not a trend measurement. Newest and Oldest first arrange the videos retrieved for your search, not everything on YouTube. The app calculates no views-per-hour or growth scores.
- YouTube's API doesn't say whether a video was officially published as a Short, so the Shorts page shows videos that meet the Shorts format rather than claiming confirmed Shorts. Videos whose shape YouTube doesn't report are left out, so a page can show fewer than 20 results.
- The app doesn't download YouTube videos.
- By using the app you agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms). See also the [Google Privacy Policy](https://policies.google.com/privacy).

## License

Copyright © 2026 Hamad. All rights reserved. The software is proprietary. You may download and use the official builds, but not copy, modify or redistribute them. See [LICENSE](LICENSE).

YouTube is a trademark of Google LLC. This app is not affiliated with or endorsed by Google or YouTube.
