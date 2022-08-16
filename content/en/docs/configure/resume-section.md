---
title: "Resume section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 230
toc: true
---
{{< alert icon="👉" text="go to src/data/Resume.json" />}}

### Edit Treeline
here you can add your resume

get your treeline icon from [`Here`](https://ionic.io/ionicons)

- search for your desired logo or icon
- get the name value and put it inside timelineClass value

![Image](images/add-icons.png "icons")

Add or remove timelines as needed

it should be at least 1 timeline to work without any errors

  
```bash
"turnOnResume":true, <-- switch between true and false to turn resume section off
    "timelines": [
        {
            "timelineClass":"analytics-outline",
            "timelineTitle":"Education",
            "timelineItems": [
                {
                    "timelineItemTitle":"Bachelor of Science in Elementary Education",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"put your description"
                },
                {
                    "timelineItemTitle":"Rahway High school",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"put your description"
                },
                {
                    "timelineItemTitle":"Cranford High school",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"put your description"
                }
            ]
        },
        {
            "timelineClass":"analytics-outline",
            "timelineTitle":"Experince",
            "timelineItems": [
                {
                    "timelineItemTitle":"Google",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"test"
                },
                {
                    "timelineItemTitle":"Apple",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"test"
                },
                {
                    "timelineItemTitle":"Netflix",
                    "timelineItemDate":"2020 — 2024",
                    "timelineItemDescription":"test"
                }
            ]
        }
    ],

```

### Edit Skills


Add or remove Skills as needed

```bash

"showSkills":true, <-- switch between true and false to turn it off 
    "skills":[
        {
            "skillName":"python",
            "skillProgress":"50%"
        },
        {
            "skillName":"node js",
            "skillProgress":"40%"
        },
        {
            "skillName":"React",
            "skillProgress":"70%"
        }
    ]

```