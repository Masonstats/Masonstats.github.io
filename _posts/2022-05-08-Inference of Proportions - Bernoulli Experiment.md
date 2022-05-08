---
layout: post
title: Getting Started with Mason
featured-img: sleek
---

## Getting started

I am a biostatistician working for an international biopharmaceutical R&D company. My main work is clinical trial design, statistical analysis and real-world drug cost-effectiveness analysis. I have a double master’s degree in Applied Statistics and Econometrics. My areas of interest include drug clinical trials, health economics, Bayesian statistics and modeling, R and Python.

We work extensively with pharmaceutical technology companies, CROs and pharmaceutical companies to conduct drug clinical trials and real-world data exploration. We now have ongoing clinical programs covering a variety of diseases including breast cancer, lung cancer and diabetes. If you are interested in participating in our project, please contact me.

## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_pages/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The home page is located under `index.md` file. You can change the content or design completely different welcome page for your taste.

In order to add a new page, create a new html or markdown file under root directory and link it in `_includes/header.html`.

### Images TODO

Introduce gulp optimization

Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Thumb | 535px | 1070px
sm |Post Thumb | 500px| 1000px
md |Post Thumb | 329.375px | 658.75px
lg |Post Thumb | 445.625px | 891.25px
xl |Post Thumb | 353.125px | 706.25px


Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Hero | 535px | 1070px
sm |Post Hero | 500px| 1000px
md |Post Hero | 329.375px | 658.75px
lg |Post Hero | 445.625px | 891.25px
xl |Post Hero | 353.125px | 706.25px

Happy hacking!
