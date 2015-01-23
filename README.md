![preview Long Haul](/preview.jpg)

Long Haul is a minimal jekyll theme built with COMPASS / SASS / SUSY and focuses on long form blog plosts. It is meant to used as a starting point for a jekyll blog/website.

If you really enjoy Long Haul and want to give me credit somewhere on the send or tweet out your experience with Long Haul and tag me [@brianmaierjr](https://twitter.com/brianmaier).

####[View Demo](http://brianmaierjr.com/long-haul)

## Features

- Minimal, Type Focused Design
- Built with SASS + COMPASS
- Layout with SUSY Grid
- SVG Social Icons
- Responsive Nav Menu
- XML Feed for RSS Readers
- Contact Form via Formspree
- 5 Post Loop with excerpt on Home Page
- Previous / Next Post Navigation
- Estimated Reading Time for posts
- Stylish Drop Cap on posts
- A Better Type Scale for all devices

## Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Long Haul repo](http://github.com/brianmaierjr/long-haul)
3. Clone it
4. Run Jekyll `jekyll serve -w`
5. Run `compass watch`
6. Customize!

## Site Settings

The main settings can be found inside the `_config.yml` file:

- **name:** name of your site
- **description:** description of your site
- **url:** your url
- **paginate:** the amount of posts displayed on homepage
- **navigation:** this is links for the main site navigation

## File Structure

``` bash
long-haul/
├── _includes
|    ├── footer.html  //site footer
|    ├── head.html  //site head
├── _layouts
|    ├── default.html  //default page layout
|    ├── post.html  //single post layout
├── _posts
├── assets
|    ├── css  //processed sass styles.
|    ├── img  //images and graphics used in css and js
|    ├── js
|    |   ├── scripts.js  //jQuery scripts go here
|    └── sass //preprocessed sass stylesheets
|        ├── breakpoints  //responsive breakpoint stylesheets
|        ├── modules  //module stylesheets
|        ├── partials  //partial stylesheets
|        ├── _config.scss  //configuration settings
|        ├── ie.scss  //ie stylesheet
|        ├── style.scss  //main stylesheet
├── images  //images for posts and pages
├── about.html  //about page
├── contact.html  //contact page
├── feed.xml  //xml feed for rss readers
└── index.html  //homepage. lists 5 most recent posts
```

## License

This is [MIT](LICENSE) with no added caveats, so feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.