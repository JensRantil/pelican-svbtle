
# SVBTLE

Svbtle theme is a close copy of [Svbtle.com](http://www.svbtle.com) with a few minor changes for use with [Pelican](http://pelican.notmyidea.org).

## DEMO

You can see this theme in action on my [blog](http://williamting.com).

![theme screenshot](https://raw.github.com/wting/pelican-svbtle/master/screenshot.png)

## FEATURES

- syntax highlighting for code blocks
- Google Analytics
- Disqus commenting
- custom list of links

## MISSING FEATURES

- pages
- custom menu
- index page date format is coded via JavaScript and ignores DEFAULT_DATE_FORMAT (current format is: Aug 05, 2012).
- tag cloud

## INSTALL

### FROM SOURCE

Download the repository and save it somewhere accessible. Edit `settings.py` and modify the `THEME` variable to point to the downloaded theme location.

### FROM OFFICIAL REPO

Please refer to Pelican theme [install instructions](http://pelican.notmyidea.org/en/latest/pelican-themes.html).

## SETTINGS.PY

These are the Pelican global variables currently supported by the theme:

- `GOOGLE_ANALYTICS`
- `DISQUS_SITENAME`
- `LINKS(('name1', 'url1'), ('name2', 'url2'))`
- `DEFAULT_DATE_FORMAT = ('%b %d, %Y')`: suggested date format
- `FEED_DOMAIN = SITEURL`

## MODIFICATION

- Accent color can be changed by editing `@accent` in `./static/css/style.less`.

- A different Pygmentize theme can be used by editing `./Makefile` and running `make pygments`.

## SOURCE CODE

Code can be found at this GitHub [repo](https://github.com/wting/pelican-svbtle).

## AUTHOR

William Ting

## LICENSE

Released under MIT License, full details in `LICENSE` file.
