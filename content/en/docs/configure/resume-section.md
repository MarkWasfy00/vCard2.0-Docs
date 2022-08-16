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
            "timelineClass":"book-outline", <-- get icon name and put it here
            "timelineTitle":"Education",
            "timelineItems": [
                {
                    "timelineItemTitle":"A Levels",
                    "timelineItemDate":"2005 — 2009",
                    "timelineItemDescription":[
                        "Yorkshire College",
                        "more items", <-- add more if needed
                        "more items"
                    ]
                },
                {
                    "timelineItemTitle":"GCSEs",
                    "timelineItemDate":"2009 — 2010",
                    "timelineItemDescription":[
                        "Conventry School"
                    ]
                },
                {
                    "timelineItemTitle":"BSc Product Design",
                    "timelineItemDate":"2010 — 2013",
                    "timelineItemDescription":[
                        "Brunel University"
                    ]
                }
            ]
        },
        {
            "timelineClass":"finger-print-outline",
            "timelineTitle":"Experience",
            "timelineItems": [
                {
                    "timelineItemTitle":"Arts and Entertainment Reporter",
                    "timelineItemDate":"Valley Oak Times, 2018-Present",
                    "timelineItemDescription":[
                        "Cover a wide variety of arts and entertainment stories as assigned ",
                        "Adhere to all story deadlines",
                        "Provide quality coverage in all stories",
                        "Proofread every story for grammar and spelling",
                        "Adhere to the newspaper style guide"
                            
                    ]
                },
                {
                    "timelineItemTitle":"Entertainment Reporter",
                    "timelineItemDate":"San Jose Star Journal, 2013-2018",
                    "timelineItemDescription":[
                        "Covered various entertainment and celebrity news stories",
                        "Wrote headlines and photo captions for all stories",
                        "Edited stories for spelling and grammar before submitting",
                        "Coordinated coverage with other arts section reporters"
                    ]
                },
                {
                    "timelineItemTitle":"Freelance Reporter",
                    "timelineItemDate":"The Denver Times, 2012-2013",
                    "timelineItemDescription":[
                        "Wrote articles for the arts section of the newspaper",
                        "Proofread all stories for spelling and grammar"
                    ]
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