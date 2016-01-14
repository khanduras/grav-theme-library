---
title: News
external_links:
    process: true
    title: false
    no_follow: true
    mode: active
    target: _blank
body_classes: 'header-image fullwidth'
content:
    items: '@self.children'
    limit: 5
    pagination: true
    url_taxonomy_filters: true
    order:
        dir: desc
        by: date
child_type: news_item
sitemap:
    changefreq: monthly
icon: newspaper-o
blog_url: news
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

