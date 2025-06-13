# 💎 TikTok Video Scraper Premium



![TikTok Scraper Cover Image](https://i.imgur.com/ZBwlcF9.png)
| Try our other scrapers ► | [Social Blade Scraper](https://apify.com/radeance/socialblade-api) | [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper)| [Wellfound Scraper](https://apify.com/radeance/wellfound-job-listings-scraper)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|

Welcome to this **Premium TikTok Video Scraper** on Apify!
This blazing-fast, feature-rich actor is designed to **extract video data from TikTok** like a pro — whether you’re a **marketer**, **data analyst**, **content creator**, or researcher. It effortlessly scrapes public TikTok videos, providing highly detailed metadata including video **captions**, **hashtags**, **mentions**, **likes**, **shares**, **creator profile info**, and **downloads videos** in the **highest available quality** without watermarks.

This scraper is built for scale and precision — capable of scraping hundreds of videos in seconds ⚡️ ⚡️

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/tiktok-video-scraper-premium)

## ✨ Key Features
- **✅ Comprehensive Video Scraping:**
    - Scrapes videos by url (bulk urls supported)
    - Extracts key video details: video id, caption, hashtags, likes, shares, comments count, challenges, mentions, upload date, and video URL
    - Captures video thumbnails and direct video download links (stored in Apify Storage)
- **✅ Raw Video & Subtitles Download:**
    - Downloads raw TikTok videos in native best quality (MP4 format)
    - Or choose the video quality yourself (lowest, 720p, 1080, highest)
    - Retrieves subtitles (if available) and stores them as WEBVTT files in Apify Storage
    - Subtitles are also included in a clean, structured format in the dataset output
- **✅ Creator Insights:**
    - Fetches TikTok user profile data: username, display name, followers, following, bio, verified status, and more
    - Useful for influencer research, audience analysis, or digital marketing
- **✅ High-Speed Performance:**
    - Scrapes hundreds of videos in under a minute, thanks to parallel crawling and smart request handling

- **✅ Flexible Output Formats:**
    - Exports results in multiple formats: JSON, CSV, XLSX, JSONL
    - Videos stored in your Apify Storage as MP4, Subtitles as WEBVTT
    - Clean structured data ready for analytics, dashboards, or further automation

## ✨ Output Sample

```json
{
    "id": "7417869154629192990",
    "created_at": "2024-09-23T16:01:11Z",
    "created_at_timestamp": 1727107271,
    "created_location": "US",
    "description": "Bedtime routine with the NEW Aveeno Daily Moisturizing Cream ✨ @Aveeno_US @Aveeno Canada  #AveenoPartner #ThePowerOfOat #Aveeno #TheSecretsOat",
    "videoHeadline": [],
    "challenges": [
      "aveenopartner",
      "thepowerofoat",
      "aveeno",
      "thesecretsoat"
    ],
    "hashtags": [
      "aveenopartner",
      "thepowerofoat",
      "aveeno",
      "thesecretsoat"
    ],
    "mentions": [
      "aveeno_ca",
      "aveeno_us"
    ],
    "labels": [
      "Beauty",
      "Beauty & Care",
      "Beauty & Style"
    ],
    "suggestedKeywords": [],
    "isAd": true,
    "duration": 24,
    "duration_formatted": "00:00:24",
    "likeCount": 79100,
    "shareCount": 1012,
    "commentCount": 1083,
    "playCount": 19200000,
    "collectCount": 5024,
    "repostCount": 0,
    "height": 1024,
    "width": 576,
    "bitrate": 809165,
    "ratio": "540p",
    "format": "mp4",
    "codecType": "h264",
    "subtitles_formatted": [
      {
        "start": "00:00:00.160",
        "end": "00:00:00.960",
        "text": "Hi, guys."
      },
      {
        "start": "00:00:00.961",
        "end": "00:00:02.441",
        "text": "I'm getting ready for bed."
      },
      {
        "start": "00:00:02.442",
        "end": "00:00:06.041",
        "text": "Skincare before bedtime is so important for your face and your body,"
      },
      {
        "start": "00:00:06.042",
        "end": "00:00:08.801",
        "text": "which is why I use the Aveeno Daily Moisturizing Cream."
      },
      {
        "start": "00:00:08.802",
        "end": "00:00:09.961",
        "text": "It contains oat,"
      },
      {
        "start": "00:00:09.962",
        "end": "00:00:12.841",
        "text": "which is good for people with dry and sensitive skin like me."
      },
      {
        "start": "00:00:12.842",
        "end": "00:00:16.881",
        "text": "The Daily Moisturizing Cream keeps your skin moisturized for 48 hours,"
      },
      {
        "start": "00:00:16.882",
        "end": "00:00:19.041",
        "text": "and it strengthens your skin's moisture barrier"
      },
      {
        "start": "00:00:19.042",
        "end": "00:00:20.941",
        "text": "to keep your skin looking hydrated."
      },
      {
        "start": "00:00:21.960",
        "end": "00:00:24.087",
        "text": "Now I'm ready for bed. Good night."
      }
    ],
    "downloadUrl": "",
    "subtitlesUrl": "",
    "subtitles": [
      {
        "language": "en",
        "url": "https://v16m-webapp.tiktokcdn-us.com/80934a1b33f11626d2ff7fb4d0174f04/67fa5ac6/video/tos/useast8/tos-useast8-v-0068-tx2/6da2598b0ccf4aeab0c4c472586b3373/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=21640&bt=10820&ds=4&ft=4KLMeMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=13&rc=anNoZGw5cjRydTMzaTczNEBpanNoZGw5cjRydTMzaTczNEBeXzBqMmRrc2xgLS1kMTJzYSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&l=20250410122102305FDDB1D3CBB3383C40&btag=e00078000",
        "autoGenerated": true,
        "nativeLanguage": true,
        "format": "webvtt"
      }
    ],
     "cover": "https://p19-pu-sign-useast8.tiktokcdn-us.com/obj/tos-useast8-p-0068-tx2/cdb6521fcc9e44d48a5e76d49e57cee1_1727107274?lk3s=81f88b70&x-expires=1744459200&x-signature=53XWAZEdH5MhBchry8lb%2FwBdhGo%3D&shp=81f88b70&shcp=-",
    "originCover": "https://p16-pu-sign-useast8.tiktokcdn-us.com/obj/tos-useast8-p-0068-tx2/23f5dc49139341b0bfd9035b37f63d33_1727107273?lk3s=81f88b70&x-expires=1744459200&x-signature=8yhgMapeApB%2FZCgoZUINlfYZCgY%3D&shp=81f88b70&shcp=-",
    "dynamicCover": "https://p16-pu-sign-useast8.tiktokcdn-us.com/obj/tos-useast8-p-0068-tx2/2d98757793d041dbbfaea0da9cd85bc7_1727107274?lk3s=81f88b70&x-expires=1744459200&x-signature=sNvgxNx641iDjc6ZgSQJUSoKxJ0%3D&shp=81f88b70&shcp=-",
    "videoUrl": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-ve-0068c001-tx2/oMRB6AIMVvsiZNhBPAknbyVMEvCExQlY5oUGi/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=1580&bt=790&cs=0&ds=6&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=0&rc=ZGQ3PDs0aGQ7N2dmOjk7NkBpanNoZGw5cjRydTMzaTczNEBfXjBfLjEtNi4xLjYvXl41YSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=180edaa201b8f3d2fb9ad5e3eed946ca&tk=tt_chain_token",
    "availableVideoQualities": [
      {
        "name": "adapt_lowest_1080_1",
        "bitrate": 671836,
        "width": 1080,
        "height": 1920,
        "url": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-ve-0068c001-tx2/oYAAwlZs715JXiivVPpQvyoBVRbhEtI4BEBAG/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=1312&bt=656&cs=2&ds=4&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=15&rc=ZGY8ZDY2ODY2O2U7ZjVoNEBpanNoZGw5cjRydTMzaTczNEAuLTVeNmMuNjExNi0yX14vYSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=1bca708b6a144e04630990e5249c1aaa&tk=tt_chain_token",
        "codec": "h265_hvc1"
      },
      {
        "name": "adapt_lower_720_1",
        "bitrate": 442576,
        "width": 720,
        "height": 1280,
        "url": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-ve-0068c003-tx2/ogsvlvBEIoisRy1BbRPv77iVBhQA5G1ATEZaV/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=864&bt=432&cs=2&ds=3&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=14&rc=NWRpOGg6OGQ6Njc4MzM8aUBpanNoZGw5cjRydTMzaTczNEBjYzViL2AzXjAxYzJfNS4zYSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=997553a4dfd309a6e57570de28d589fd&tk=tt_chain_token",
        "codec": "h265_hvc1"
      },
      {
        "name": "normal_540_0",
        "bitrate": 809165,
        "width": 576,
        "height": 1024,
        "url": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-ve-0068c001-tx2/oMRB6AIMVvsiZNhBPAknbyVMEvCExQlY5oUGi/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=1580&bt=790&cs=0&ds=6&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=0&rc=ZGQ3PDs0aGQ7N2dmOjk7NkBpanNoZGw5cjRydTMzaTczNEBfXjBfLjEtNi4xLjYvXl41YSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=180edaa201b8f3d2fb9ad5e3eed946ca&tk=tt_chain_token",
        "codec": "h264"
      },
      {
        "name": "lowest_540_0",
        "bitrate": 340330,
        "width": 576,
        "height": 1024,
        "url": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-ve-0068c001-tx2/ostvAihnGvBRNxVvPZbGEVlI2iskL5BEvoAPy/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=664&bt=332&cs=0&ds=6&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=5&rc=NGVpOWVmOzUzNmZnNGc2OUBpanNoZGw5cjRydTMzaTczNEAvNDM1MGBeNjIxLjExLjExYSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=6f1ed308dd8a80439b9e4b5e6a5782c3&tk=tt_chain_token",
        "codec": "h264"
      },
      {
        "name": "adapt_540_1",
        "bitrate": 332683,
        "width": 576,
        "height": 1024,
        "url": "https://v16-webapp-prime.us.tiktok.com/video/tos/useast8/tos-useast8-pve-0068-tx2/oMBvvybZAPRvhGVsBhIdYR6XlE5VioYPA1EGi/?a=1988&bti=ODszNWYuMDE6&ch=0&cr=3&dr=0&lr=all&cd=0%7C0%7C0%7C&cv=1&br=648&bt=324&cs=2&ds=6&ft=4KJMyMzm8Zmo08~bMb4jVW-odpWrKsd.&mime_type=video_mp4&qs=11&rc=NjQ5OjVoNzM8NTllNzczOkBpanNoZGw5cjRydTMzaTczNEBfXjYyYmJeXi0xLV9eMWBgYSNeXzBqMmRrc2xgLS1kMTJzcw%3D%3D&btag=e000b8000&expire=1744460486&l=20250410122102305FDDB1D3CBB3383C40&ply_type=2&policy=2&signature=0c5333bc613316ec6730148da3336182&tk=tt_chain_token",
        "codec": "h265_hvc1"
      }
    ],
    "music_id": "7417869188033301278",
    "music_title": "original sound",
    "music_play_url": "https://v16m.tiktokcdn-us.com/6a0aa0a3aa2b62171aa5099de780e2ae/67f80c26/video/tos/useast8/tos-useast8-v-27dcd7-tx2/ooCGeLqMNCIZfrFXQxjyhEQfoILj84hAhTYZvT/?a=1233&bti=ODszNWYuMDE6&ch=0&cr=0&dr=0&er=0&lr=default&cd=0%7C0%7C0%7C0&br=250&bt=125&ft=GSDrKInz7ThnQO3OXq8Zmo&mime_type=audio_mpeg&qs=6&rc=aWczNjxlOWRoOmQ6OTM3O0BpanlleHU5cmxzdTMzaTU8NEBiYzRhNTMxNl4xMmNeLWE2YSNkLy80MmRjLmxgLS1kMTJzcw%3D%3D&vvpl=1&l=20250410122102305FDDB1D3CBB3383C40&btag=e000b8000",
    "music_cover": "https://p16-pu-sign-useast8.tiktokcdn-us.com/tos-useast5-avt-0068-tx/d8b707e8ab71dc4c0adcf27e4c841ade~tplv-tiktokx-cropcenter:1080:1080.jpeg?dr=9640&refresh_token=51996334&x-expires=1744459200&x-signature=qBMtNDfGN04K7shKqOPut%2BvQ%2Bso%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=useast5",
    "music_author": "Bella Poarch",
    "music_original": true,
    "music_duration": 24,
    "music_copyrighted": false,
    "author_id": "6748458643983238149",
    "author_secUid": "MS4wLjABAAAAIQGNoHByQvokcLbWCGnIfas0OV2nctsZnRFbN7eB04xt-9usrHe3UvXJRZLxBWlJ",
    "author_unique_id": "bellapoarch",
    "author_nickname": "Bella Poarch",
    "author_avatar": "https://p16-pu-sign-useast8.tiktokcdn-us.com/tos-useast5-avt-0068-tx/d8b707e8ab71dc4c0adcf27e4c841ade~tplv-tiktokx-cropcenter:1080:1080.jpeg?dr=9640&refresh_token=51996334&x-expires=1744459200&x-signature=qBMtNDfGN04K7shKqOPut%2BvQ%2Bso%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=useast5",
    "author_description": "",
    "author_created_at": "2019-10-29T19:33:46Z",
    "author_created_at_timestamp": 1572377626,
    "author_verified": true,
    "author_private_account": false,
    "author_ttSeller": false,
    "author_followerCount": 94000000,
    "author_followingCount": 649,
    "author_heartCount": 2400000000,
    "author_videoCount": 787,
    "author_diggCount": 11000,
    "author_friendCount": 0
  },
```

## Use Cases
-   **Marketers & Agencies:** Track trending videos, analyze hashtag performance, or gather inspiration for branded campaigns

-   **Influencer Managers:** Extract creator data, engagement metrics, and video performance for prospecting and analysis
-   **Data Scientists & Analysts:** Collect rich TikTok datasets to model content virality, sentiment, or topic clustering
-   **Content Creators:** Research video trends, hashtags, and competitors in your niche
-   **Academics & Researchers:** Study TikTok engagement, youth culture, or meme evolution with robust data

## 📌 Input

![Scraper Sample Input](https://i.imgur.com/cdQEZKK.png)

    
**- `urls`**: **(Required) (Array) (Default: empty)**
Enter TikTok video URLs to scrape. You can specify multiple URLs by clicking on the Add button or in bulk by clicking on the Bulk edit button.

**- `preferred_language`**: **(Optional) (String) (Default: na)**
Select your preferred language for subtitles from 10+ supported languages. If not available, subtitles will be translated if translation option is enabled or will remain in native language.

**- `translate_subtitles`**: **(Optional) (Boolean) (Default: false)**
Enable to translate TikTok subtitles to your preferred language. Translated subtitles can be accessed from the `subtitles_webvtt` field. Requires proxy to function properly.

**- `download_videos`**: **(Optional) (Boolean) (Default: true)**
Enable to download TikTok videos to your Apify Storage. Access downloadable files from the `downloadUrl` field in results. If disabled, only video metadata will be scraped.

**- `download_subtitles`**: **(Optional) (Boolean) (Default: true)**
Enable to download TikTok subtitles to your Apify Storage when available. Access downloadable subtitle files from the `subtitlesUrl` field in results.

**- `quality`**: **(Optional) (String) (Default: highest)**
Select video download quality from Lowest (360p) to Highest (1080p). Higher quality means larger file sizes - low quality files are 1-2 MB while high quality can reach 20 MB.
    <br>
    <br>


![Scraper Sample Input](https://i.imgur.com/zEBpIUd.png)
**- `storage_name`**: **(Optional) (String) (Default: empty)**
Specify a custom storage name for your videos and subtitles. Recommended for longer retention beyond the default 7 days. Must be 3-32 characters long.

### 🎛️ Advanced Options



![Scraper Sample Advanced Options Input](https://i.imgur.com/IlnS5eu.png)

**- `proxySettings`**: **(Optional) (Object) (Default: Residential Proxy)**
Configure proxy settings for the scraper. Default uses Apify's residential proxy group which is recommended for reliable TikTok access and subtitle translation features.


### ✏️ JSON Input

Sample JSON input if you use the apify api via CURL, Python, JS etc.
![Scraper Sample JSON Input](https://i.imgur.com/Our9k32.png)

## 📎 Detailed Output Information

### Video Details

Includes detailed metadata for each TikTok video, such as:
-   Video ID, caption, hashtags, upload date, duration, sound title, and video language
-   ngagement metrics: likes, shares, comments, and views
-   Direct video URL, thumbnail URL, and video download link (when accessible)

### Creator Information

Provides comprehensive data about the video’s creator, including:
-   Username, display name, profile URL, bio, profile picture URL
-   Follower count, following count, total likes, and number of published videos
-   Verified status and account privacy status

### Video Page URL

-   Direct link to the original TikTok video post for easy access or reference.

### Hashtags & Mentions

-   List of all hashtags and user mentions included in the video description.

### Music Info

-   Includes sound ID, title, author, and whether it’s an original sound or a commercial track.

### Export Formats

-   Data can be exported in CSV, XLSX, JSON, JSONL, XML, and RSS formats for seamless integration into your data pipeline or analytics workflow.

## ⚙️ While the scraper is running

During the run, the actor will output log messages letting you know what is going on at any point. Each message always contains specific information about the process including which url / page the actor is working on.

If you provide invalid inputs to the actor, it will immediately stop with a failure state and output log messages explaining what is wrong. If you are unsure what went wrong feel free to open up an issue in the issue tab.

## 🔗 Legality of web scraping and scraping of job listings

The **Premium TikTok Video Scraper** is designed to ethically extract **only publicly available data**, and it **does not** scrape private user data such as personal email addresses or personal identifiers.

Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. However, you should be aware that your results could contain personal data. Personal data is protected by the GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our [blog post](https://blog.apify.com/is-web-scraping-legal/) on the legality of web scraping

## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the **Premium TikTok Video Scraper**, please create an issue in the Actor’s Issues tab on the Apify Console.

You can also contact us directly for custom integrations or project use cases at business@radeance.com.

Thank you and happy scraping!

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/tiktok-video-scraper-premium)