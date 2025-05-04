---
date: '2025-04-25T04:07:45+03:00'
title: 'Random Page'
url: "/random-page"
---

You can easily create random pages in your Hugo site! To add a new page, just create it under the `/content` directory, and at the top of your page, add the following:

```yaml
---
date: '<date>'
title: '<page title>'
url: "/<url>"
---
```

Once your page is set up, you can add it to your navigation bar! To do this, simply go to:

```
/themes/raspite/layouts/partials/header.html
```

Then, find the `<nav class="sidebar">` section and add a new `<a>` tag for your page like this:

```html
<nav class="sidebar">
  <a href="/">Home</a>
  <a href="/shoutbox">Shoutbox</a>
  <a href="/random-page">Random Page</a>
</nav>
```

Feel free to customize it to match your site's needs!

### Bonus Features:

In your posts, you have full control over what you can add - just like in the [Shoutbox](/shoutbox)!

Want to keep certain pages secret? You can create "hidden" pages that are only accessible via a direct link, like this [example](/secret).