# What is Starpage
Starpage is startpage with Catppuccin Mocha colors. Now there's not many functions, but i plan to add:
- [x] Customisable links list (using cookies)
- [x] Customisable logo (again, using cookies)
- [x] Search bar
- [ ] Modal window for changing config

## How to change links?
- 1. Install "Cookie Editor" for your browser
- 2. Open editor and redact cookie named "links" (format of every link: {'name': 'insert_name', url: 'insert_url'}
        - Name: name of site, you'll see it on this page
        - URL: URL to page. Don't forget to add "https://" in the start of URL! 

## How to change logo?
- 1. Install "Cookie Editor" for your browser
- 2. Open editor and insert URL of picture, then save and reload page 

## How to customise searcher?
- 1. Open Cookie Editor
- 2. At cookie "searchQuery" you'll see link to search query. To change searcher, insert here link to different searcher. Some links for example:
        - DuckDuckGo (in Starpage by default): `https://duckduckgo.com/search?q=`
        - Google: `https://google.com/search?q=`
        - Yandex: `https://yandex.ru/search?text=`
