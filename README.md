# SABnzbd Glitter - Night UserCSS Script

CSS &copy; 2017/2018 [Kris McCann](https://github.com/AJCrowley) - [krismccann@gmail.com](mailto:krismccann@gmail.com)

Some simple CSS enhancements for SABnzbd's Glitter skin (night version).

This is somewhat a work in progress, so please check back regularly for updates to make sure you're running the best version of the CSS.

To use, just install a UserCSS browser extension, I use [Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), as it allows you to define different CSS adaptions by URL, so these mods won't be applied to all servers on your localhost. To limit the mods to SABnzbd, just uncomment the line specifying the URL to watch (and matching bracket on the last line), make sure to modify the filter to match your SABNZBd location:
```css
@-moz-document url-prefix("http://127.0.0.1:6060/sabnzbd/") {
	/* css changes live here */
}
```

There are however plenty of options, depending upon your browser, but I've found this one to be the best for my purposes.

Enjoy!
