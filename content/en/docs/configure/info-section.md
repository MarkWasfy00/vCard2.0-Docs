---
title: "Info section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 210
toc: true
---

{{< alert icon="👉" text="go to src/data/info.json" />}}

### Edit Image

```bash
  "profileImage":"/images/actor.jpg", <-- put your profile image path
  "scaleImage":"1.0", <-- zoom your profile picture
```

- put your image in public/images/yourimage
- copy the path and put it in profileImage
- adjust the image zoom by increasing by 0.1

### Edit Info

```bash
  "name":"Billy J. Cauthen", <-- put your name
    "title":"UI/UX designer", <-- put your title
    "email":"BillyJCauthen@armyspy.com", <-- put your email
    "phoneCode":"1", <-- put your phone code
    "phone":"765-418-8518", <-- put your phone number
    "date":"July 7, 1984", <-- put your birthday
    "location":"Indiana , USA", <-- put your country
```


### Edit Icons

get Icons from [`Here`](https://ionic.io/ionicons)

- search for your desired logo or icon
- get the name value and put it inside iconClass value

![Image](images/add-icons.png "Open cmd")

Add or remove icons as needed 

```bash
  "icons" : [
      {
          "iconClass": "logo-linkedin", <-- put your name value here
          "iconLink": "https://www.linkedin.com/in/yourname" <-- add your link
      },
      {
          "iconClass": "logo-github",
          "iconLink": "https://github.com/yourname"
      },
      {
          "iconClass": "logo-stackoverflow",
          "iconLink": "https://stackoverflow.com/users/yourname"
      }
  ]
```