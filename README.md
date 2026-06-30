[Instagram Search Reels](https://apify.com/data-slayer/instagram-search-reels?fpr=data)

Extract Instagram Reels metadata without logging in. This cookieless scraper enables social media content creators to analyze trending content, engagement metrics, and viral audio tracks for data-driven content strategy optimization.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/L6CXFfq56jQ?enablejsapi=1&rel=0)

---

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| query | String | Search term or keyword to find relevant Reels (e.g., "insights", "marketing tips", "fitness") |

## Outputs

**Formats**: JSON, CSV, Excel

**Key Fields Extracted**:

- `id` - Unique Reel identifier
- `code` - Short URL code for the Reel
- `caption.text` - Full caption text with hashtags and mentions
- `caption.hashtags` - Array of hashtags used
- `caption.mentions` - Array of mentioned usernames
- `user.username` - Creator's username
- `user.full_name` - Creator's display name
- `user.is_verified` - Verification status
- `user.profile_pic_url` - Profile picture URL
- `ig_play_count` - Total video views
- `like_count` - Number of likes
- `comment_count` - Number of comments
- `share_count` - Number of shares
- `video_url` - Direct video file URL
- `video_duration` - Video length in seconds
- `thumbnail_url` - Thumbnail image URL
- `taken_at` - Unix timestamp of post creation
- `taken_at_date` - Human-readable date
- `clips_metadata.audio_type` - Audio type (original/licensed)
- `clips_metadata.original_sound_info.audio_id` - Audio track identifier
- `clips_metadata.original_sound_info.original_audio_title` - Audio track name
- `has_audio` - Boolean indicating audio presence

## How to Use

**Step 1**: Enter your target search term in the `query` field (e.g., "social media tips", "travel", "cooking").

**Step 2**: Click "Start" to begin scraping Reels matching your search criteria.

**Step 3**: Once complete, download your data in JSON, CSV, or Excel format from the dataset tab.

## Sample Output

```
{
  "id": "3575393669538547061",
  "code": "DGeWZllBoV1",
  "caption": {
    "text": "For more tips and insights, follow @iamishachopra\n\n#instagrammarketingtips #instagramgrowthexpert #contentideas",
    "hashtags": [
      "#instagrammarketingtips",
      "#instagramgrowthexpert",
      "#contentideas"
    ],
    "mentions": ["@iamishachopra"]
  },
  "user": {
    "username": "iamishachopra",
    "full_name": "Isha Chopra: Social Media Marketer | Insta Coach",
    "is_verified": true,
    "profile_pic_url": "https://scontent-vie1-1.cdninstagram.com/..."
  },
  "ig_play_count": 7169443,
  "like_count": 39008,
  "comment_count": 284,
  "share_count": 95428,
  "video_url": "https://scontent-vie1-1.cdninstagram.com/...",
  "video_duration": 24.3,
  "taken_at_date": "2025-02-24T23:37:12+00:00",
  "clips_metadata": {
    "audio_type": "original_sounds",
    "original_sound_info": {
      "audio_id": 939635911650210,
      "original_audio_title": "Original audio"
    }
  }
}
```

---

## Key Features

🔒 **Cookieless / No Login Required** - Scrape Instagram Reels data without authentication or session management. No risk of account bans or rate limiting tied to your personal profile.

📈 **Scalable Architecture** - Process thousands of Reels efficiently with built-in pagination and rate limiting. Designed for high-volume data extraction workflows.

✅ **Rich Metadata Extraction** - Capture comprehensive Reel data including play counts, like counts, comment counts, share counts, hashtags, mentions, audio information, video URLs, captions, user profiles, timestamps, and engagement metrics.

⚡ **Fast & Reliable** - Optimized scraping engine delivers consistent results with automatic retry logic and error handling for production-grade reliability.

📊 **Export-Ready Formats** - Download data in JSON, CSV, or Excel formats for immediate analysis in your preferred tools or integration into existing workflows.

## Use Cases

**Content Creators & Influencers**: Identify trending Reels by analyzing play counts, engagement rates, and viral audio tracks. Discover what content formats and topics resonate with your target audience to optimize your content calendar.

**Social Media Marketers**: Track competitor Reels performance, monitor hashtag effectiveness, and analyze engagement patterns across different posting times. Build data-driven campaigns based on real performance metrics.

**Data Analysts & Researchers**: Aggregate large-scale Reels data for trend analysis, sentiment research, and audience behavior studies. Export structured datasets for statistical modeling and visualization.

## 🧩 Other Instagram Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Instagram Followers Scraper | Extract follower lists from any account | [Try it](https://apify.com/data-slayer/instagram-followers-scraper---no-login) |
| Instagram Following Scraper | See who any account follows | [Try it](https://apify.com/data-slayer/instagram-following) |
| Instagram Posts Scraper | Extract posts from any profile | [Try it](https://apify.com/data-slayer/instagram-posts) |
| Instagram Comments Scraper | Extract comments from any post | [Try it](https://apify.com/data-slayer/instagram-comments-scraper-no-login-required) |
| Instagram Likes Scraper | Extract users who liked any post | [Try it](https://apify.com/data-slayer/instagram-likes) |
| Instagram Profile Scraper | Get full profile data with contact info | [Try it](https://apify.com/data-slayer/instagram-user-info-scraper-cookieless) |
| Instagram User Search | Search Instagram users by keyword | [Try it](https://apify.com/data-slayer/instagram-search-users) |
| Instagram Hashtag Scraper | Discover hashtags and media counts | [Try it](https://apify.com/data-slayer/instagram-hashtags-scraper-no-login-required) |
| Instagram Location Posts | Extract posts from any location | [Try it](https://apify.com/data-slayer/instagram-location-posts) |

**Need verified emails?** Our [LinkedIn Post Engagers Email Finder](https://apify.com/data-slayer/linkedin-post-to-verified-leads) and [LinkedIn Audience Email Finder](https://apify.com/data-slayer/linkedin-influencer-audience-to-verified-leads) extract verified work emails from LinkedIn engagement data.

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too

We typically respond within 24 hours.

---

---