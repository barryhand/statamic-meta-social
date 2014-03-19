Statamic fieldtype and partial Meta tags with added social data for FB, Twitter and Google+ for blog posts.

![Twitter Example](http://www.barryhand.ie/assets/img/blog/git.png)

You can see it in [action](http://barryhand.ie/blog/smart-dns-unlocator) - view the source code.

**What it does:**

* Adds two fieldtypes - meta and posts
* Allows social open graph data to be used

---

**What it doesn't do:**
* Add meta data for other pages

---

## Basic Installation
1. Merge _config folder in statamic
2. Add 'partials' to your theme folder
3. Include {{ theme:partial src="_meta-social" }} into theme head tag

---

## Testing
Verify it is working correctly here by checking your blog post url against the following:
* Twitter - https://dev.twitter.com/docs/cards/validation/validator
* Facebook - https://developers.facebook.com/tools/debug/og/object
* Google - http://www.google.com/webmasters/tools/richsnippets


## Version History
0.1 - Initial release

## Thanks
Utilises some of the meta code found in [GarethRedfern's](https://github.com/garethredfern) [Statarkers](https://github.com/statamicthemes/statarkers-theme) theme.

## Author
Created by Barry Hand. Have a question or suggestion? Feel free to reach out.

Twitter: [@barryhand](http://twitter.com/barryhand/)
Website: [barryhand.ie](http://www.barryhand.ie)