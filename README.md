About

When chronic pain and illness are not validated, psychological fallout and clinical consequences abound:

* Medical gaslighting leads to trauma, anxiety, and emotional shutdown
  
* Isolation intensifies, loved ones, friends, and self will struggle to understand
  
* Delayed or denied care occurs, without a label, treatment options shrink, referrals stall, and accommodations get denied.
  
All of the above are incredibly overwhelming. Not to mention the radical life changes that take place while we are waiting for answers.

No one knows what to do, doctors, spouses, friends, loved ones, and most of all ourselves.
This leaves the undiagnosed not only miserable due to the lack of answers, but also because of a sense of guilt that is inadvertently placed upon us. We can no longer live life as we did before, with seemingly no explanation. It's a living nightmare.

I created this page to provide a place for those that have walked the walk to share their experiences, and to also provide myself with an outlet. It is easy to spiral due to frustration and overwhelm, and patient advocation is insanely exhausting, especially when it turns up fruitless again and again.

This blog will not serve just as a vent session, but as a challenge to all of us, to look outside of ourselves for sources of inspiration. For me it is Jesus, my favorite band, and trying my best to learn something new every day.

The question is, what is that inspiration for you? We all could use some more pointers and encouragement.


### Tips for the ones with a short working memory:

Here’s the clean, correct way to reference a PNG stored in your assets folder from a post inside your GitHub Pages repo. This works whether you’re using plain Markdown or Jekyll.
---
⭐ Put your image in /assets/ (or /assets/images/), then reference it in your post using a root‑relative path:
![Alt text](/assets/your-image.png)

This is the most reliable method because GitHub Pages serves everything from the repo root.
---
📁 Folder Structure Example
If your repo looks like this:
repo/
├── _posts/
│   └── 2026-03-11-my-post.md
├── assets/
│   └── penguin.png
└── index.md

Then your Markdown reference is:
![Penguin](/assets/penguin.png)

---
🧠 Why Root‑Relative Paths Work Best
GitHub Pages (Jekyll) serves your site from the root of the published branch.
So /assets/penguin.png always resolves correctly, no matter where the post lives.
This is also consistent with GitHub Pages documentation, which states that images can be placed anywhere under /assets and referenced directly. tomcam.github.io
---
📝 If You’re Using a `docs/` Folder
If your site is published from /docs, your structure might look like:
repo/
├── docs/
│   ├── _posts/
│   ├── assets/
│   │   └── penguin.png
│   └── index.md

Then your path becomes:
![Penguin](/docs/assets/penguin.png)

GitHub Pages expects assets under /docs/assets when using the docs‑based setup. tomcam.github.io +1
---
🧩 Common Mistakes to Avoid
✔ Case sensitivity
GitHub Pages is case‑sensitive, so Penguin.png ≠ penguin.png.
This is a common cause of broken images. 
✔ Wrong relative paths
Posts live in _posts/, so ../assets/... often fails.
Use root‑relative (/assets/...) instead.
✔ Wrong file extension
.PNG vs .png matters on GitHub Pages.
---
