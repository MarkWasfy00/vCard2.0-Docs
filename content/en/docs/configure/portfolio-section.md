---
title: "Portfolio section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 240
toc: true
---

{{< alert icon="👉" text="go to src/data/Portfolio.json" />}}

### Edit Portfolio
here you can add your portfolio projects

Add or remove projects as needed

- you should add categories for your projects
- add the category for the project categroy's section
- they must be the same , case sensitve
  
```bash
 "turnOnPortfolio":true, <-- switch between true and false to turn portfolio section off 
    "categories":[
        "Web development", <--- put this for desired project 
        "Mobile Application",
        "SaaS"
    ],
    "portfolio":[ 
        {
            "title":"E-commerce",
            "category":"Web development", <--- here ^
            "image":"/images/project-1.jpg",
            "link":"#"
        },
        {
            "title":"Elvar",
            "category":"SaaS",
            "image":"/images/project-1.jpg",
            "link":"#"
        },
        {
            "title":"score",
            "category":"SaaS",
            "image":"/images/project-1.jpg",
            "link":"#"
        },
        {
            "title":"figma",
            "category":"Mobile Application",
            "image":"/images/project-1.jpg",
            "link":"#"
        }
    ]

```