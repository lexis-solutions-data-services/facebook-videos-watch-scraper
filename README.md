# Facebook Videos Search Scraper

![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/facebook-user-search/banner.jpg)

## What is the Facebook Videos Search Scraper?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.14` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `facebook-videos-watch-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---



The Facebook Videos Search Scraper is a web scraping tool that allows you to scrape Facebook video search results. It can be used obtain public data of a video given video URL, or a list of videos given a search query (name).

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/6wLaQMT0jfy0bJp4U/rYjt1mgQ9slDOiexn-fb-videos.png" alt="Facebook Videos (Watch) Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/facebook-videos-watch-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## What data can the Facebook Videos Search Scraper extract?

The Facebook Videos Search Scraper can extract the following data from Facebook video search results:

- Title
- Description
- Video URL
- Thumbnail URL
- Video ID
- Count of reactions
- Count of comments
- Count of views
- Channel name
- Channel URL

## What use cases does the Facebook Videos Search Scraper?

The Facebook Videos Search Scraper can be used for a variety of use cases, including:

- **Market Research** - The scraper can be used to scrape videos of competitors to analyze their video content and engagement.
- **Lead Generation** - The scraper can be used to scrape videos of potential leads to analyze their video content and engagement.
- **Content Creation** - The scraper can be used to scrape videos of influencers to analyze their video content and engagement.

## How to use the Facebook Videos Search Scraper?

1. Create a free Apify account
2. Open Facebook Videos Search Scraper
3. Add either a video URL or a search query
4. Click Start and wait for the results
5. Download the results in JSON, XML or CSV format or connect the actor to your backend via API

## 📥 Input

To run the actor, simply enter either a:

- **Video URL** - the URL of the video you want to scrape (e.g. https://www.facebook.com/watch/?v=1018213269105012)

- **Search Query** - the name of the person you want to search for (e.g. `mkbhd`)

If you enter both a video URL and a search query, the actor will use the video URL.

# 📤 Output

The results are stored in the default dataset associated with the actor. Each item is an ad, having the following format:

```json
{
  "title": "A 360 camera that blew my mind.",
  "url": "https://www.facebook.com/MKBHD/videos/1018213269105012/",
  "thumbnail": "https://scontent-ord5-1.xx.fbcdn.net/v/t15.5256-10/344286673_706099337865339_8740040162425848492_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=596eb7&_nc_ohc=fnofrwbr_xQAb7mxD2S&_nc_ht=scontent-ord5-1.xx&oh=00_AfDlQI8PP0CBlTu-KgrpUJSI5xVvHebF2Vci7-WDAgoPAw&oe=6618D80C",
  "date": "June 16, 2023",
  "views": "497K",
  "comments": "185",
  "reactions": "11K",
  "channelName": "MKBHD",
  "channelUrl": "https://www.facebook.com/MKBHD"
}
```

## How many results can I scrape?

The video search currently uses infinite scroll to load all the videos on the page. This means that the actor will keep scrolling until it reaches the end of the page, and then it will start extracting the videos. To control the number of scrolls, you can use the `scrollsAmount` input field.

## Why use the Facebook Videos Search Scraper?

- ⚡️ **Fast** - The scraper is fast and efficient, allowing you to scrape videos in a programmatic way.

- 🤙 **Easy to use** - The scraper is easy to use and requires no coding knowledge. All you need to do is input the query you want to scrape and the scraper will do the rest.

- ☑️ **Well-Maintained** - The scraper is maintained by the Lexis Solutions team, ensuring that it is always up-to-date and working properly.

## FAQ

- **Is Scraping Facebook Videos Legal?**

  The current scraper only scrapes public data from Facebook videos. This means that the data is publicly available and can be accessed by anyone. However, we recommend that you check Facebook's Terms of Service before using the scraper.

- **How much does it cost?**

  The cost for using the Facebook Videos Search Scraper is shown on the top of this page. You can also check the Apify Store page for more information.

- **I can't visualize images from the dataset. What do I do?**

  Facebook has strict privacy policies and might not allow images to be visualized on sites different than Meta's platforms. To visualize the images, you can download the images from a non-browser environment, e.g Node.js, and copy the assets into your own storage.

## Related Scrapers by Lexis Solutions

- [Facebook User Search Scraper](https://apify.com/lexis-solutions/facebook-user-search-scraper) - Scrape Facebook user search results.

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
