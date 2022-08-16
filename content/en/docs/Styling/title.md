---
title: "Title"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "Styling"
weight: 350
toc: true
---

{{< alert icon="👉" text="go to src/index.html" />}}

your index.html will be structured like this 


```bash
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/vite.svg" /> <------ change the icon path from here
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite + React</title> <------ change the title from here
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/javascript/jsonToSass.js"></script>
    <script type="module" src="/src/main.jsx"></script>
    <script  src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
  </body>
</html>
```