# rtdThemeForPelican
rtdThemeForPelican

Read The Doc theme for pelican. Perfect theme, don't know why there isn't one for Pelican.


```
GOOGLE_ANALYTICS = 'UA-xx'
DISQUS_SITENAME = 'dis'
GITHUB_URL = 'https://github.com/sadas'
SELFIE_PATH = '/images/logo/logo.svg'
FAVICON = '/images/logo/logo.png'
AUTHOR_NAME = 'name'
SELFIE_NOTE = 'Note'
TOP_CATEGORY = 10
TOP_TAG = 10
SITENAME = 'KNOWN'

JINJA_FILTERS = {
    'sort_by_article_count': partial(
        sorted,
        key=lambda tags: len(tags[1]),
        reverse=True)} # reversed for descending order

```

We need to add a `Jinja` Filter because inline filter cannot support sort by attribute's length.

Previews:
    https://brianshen1990.github.io/

Screenshots:

![SC01](./ScreenShot01.png)

![SC02](./ScreenShot02.png)

![SC03](./ScreenShot03.png)


