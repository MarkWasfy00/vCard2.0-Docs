---
title: "Blog section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 250
toc: true
---

{{< alert icon="👉" text="go to src/data/Blog.json" />}}

### Edit Blog

here you can add your blogs

Add or remove projects as needed

- put your blog image in public/images
- id should be unique for each blog

```bash
"turnOnBlog":true, <-- switch between true and false to turn blog section off
    "blogs":[
        {
            "id":"12-UC", <-- id should be unique for each blog
            "image":"/images/blog-2.jpg",
            "title":"best roadmaps 2022",
            "category":"education",
            "date":"2022-02-23",
            "description":"terature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written"

        },
        {
            "id":"13-UC",
            "image":"/images/blog-3.jpg",
            "title":"best code editors of all time",
            "category":"programming",
            "date":"2022-05-23",
            "description":"10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written 10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written 10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written 10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written 10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written 10.33 of 'de Finibus Bonorum et Malorum' (The Extremes of Good and Evil) by Cicero, written"

        },
    ]
```