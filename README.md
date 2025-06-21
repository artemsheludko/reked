# Reked is a minimal and responsive blog theme for Jekyll. It is focused on the content, speed, simplicity

### Features

* 100% responsive and clean theme
* Optimized for mobile devices
* Minimal design
* Valid HTML5 code
* Post sharing
* Image Zoom
* MailChimp Form Widget
* Supports Disqus Comments
* Supports Google Analytics
* Ionicons
* Google Fonts

* * *

### Demo

Check the theme in action [Demo](https://reked.netlify.com/)

The main page would look like this:

![Main page preview](https://github.com/artemsheludko/reked/blob/master/images/reked-preview.jpg?raw=true)

* * *

### Deployment

To run the theme locally, navigate to the theme directory and run `bundle install` to install the dependencies, then run `jekyll serve` or `bundle exec jekyll serve` to start the Jekyll server.

I would recommend checking the [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

## Stackbit

This theme is ready to import into Stackbit. It can be deployed to Netlify and you can connect any headless CMS including Forestry, NetlifyCMS, DatoCMS, Sanity or Contentful.

[![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/artemsheludko/reked)

* * *

### Posts

To create a new post, you can create a new markdown file inside the \_posts directory by following the [recommended file structure](https://jekyllrb.com/docs/posts/#creating-post-files).

      ---
      layout: post
      title: "Welcome to Jekyll!"
      date: 2018-08-23 16:04:00 +0300
      image: 03.jpg
      tags: Jekyll
      ---


You can set the tags and the post image.

Add post images to **/images/** directory.

For tags, try to not add space between two words, for example, `Ruby on Rails`, could be something like (`ruby-on-rails`, `Ruby_on_Rails`, or `Ruby-on-Rails`).

* * *

### Disqus Comments

Reked Theme comes with Disqus comments enabled.

Open `_config.yml` file, and change the `mr-brown` value on line 30 with your [Disqus account shortname](https://help.disqus.com/customer/portal/articles/466208).

      Comment Section (Disqus)
      disqus-identifier: mr-brown # Add your shortname for Disqus Comment. For example mr-brown


That’s all you need to setup Disqus from the theme side. If you get any issue regarding that comments are unable to load. First, make sure you have [registered your website with Disqus (Step 1)](https://help.disqus.com/customer/portal/articles/466182-publisher-quick-start-guide).

And also check [Disqus troubleshooting guide](https://help.disqus.com/customer/portal/articles/472007-i-m-receiving-the-message-%22we-were-unable-to-load-disqus-%22) if you still have issues.

* * *

### Google Analytics

To integrate Google Analytics, open `_config.yml`, and add your Google Analytics identifier.

    # Google Analytics
    google-analytics: \# Add your identifier. For example UA-99631805-1


* * *

### Update favicon

You can find the current favicon (favicon.ico) inside the theme root directory, just replace it with your new favicon.

* * *

### License

Mit License

* * *

### Premium Themes by Artem

| [![Coderon Jekyll Theme](https://github.com/artemsheludko/artemsheludko.github.io/raw/master/assets/preview/coderon-preview.png?raw=true)](https://jekyllthemes.io/theme/coderon-blog-jekyll-theme) | [![Renva Portfolio Jekyll Theme](https://github.com/artemsheludko/artemsheludko.github.io/raw/master/assets/preview/renva-preview.png?raw=true)](https://jekyllthemes.io/theme/renva-portfolio-jekyll-theme) | [![Nomod](https://github.com/artemsheludko/artemsheludko.github.io/raw/master/assets/preview/nomod-preview.png?raw=true)](https://jekyllthemes.io/theme/nomod-blog-jekyll-theme) |
|:---:|:---:|:---:|
| **Coderon** | **Renva** | **Nomod** |
