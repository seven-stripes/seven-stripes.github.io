# seven-stripes.github.io

The Seven Stripes studio page and the files it serves:

- `index.html` - the studio page: the mark, a line about the studio, Bubble Stripes with its Google Play badge (the link carries `utm_source=strona_studia`), the privacy policy and the contact address. No cookies, no counters, nothing loaded from other sites.
- `gry/bubble-stripes/` - the Bubble Stripes page: what the game is (Polish and English), three screenshots that open full size, the Google Play badge (`utm_source=strona_gry`), the privacy policy and the contact address.
- Structured data (JSON-LD in each page's head): the studio page names the studio (`Organization`, also known as Seven Stripes Games, its logo `img/logo-7s-512.png` and its profiles in `sameAs`: YouTube, Facebook, the Google Play developer page, GitHub) and the site (`WebSite`, the name Google shows next to the address); the game page describes Bubble Stripes (`VideoGame` + `MobileApplication`, its store titles in ten languages, PEGI 3, free). Keep `sameAs` in step with the studio's profiles.
- `sitemap.xml` and `robots.txt` - the pages for Google; Search Console reads the sitemap.
- `google9dbc27da4b681621.html` - Google Search Console's proof that the studio owns the site. Do not remove: the property stops being verified.
- `img/` - the page's pictures, made by `games/bubble-stripes/scripts/grafiki-studia-bubbles.py` in the studio's main repo.
- `app-ads.txt` - lets ad networks confirm that ads in our games belong to our AdMob account. Do not remove.
