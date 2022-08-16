---
title: "Gradients"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "Styling"
weight: 320
toc: true
---
here a website to pick [`HSL`](https://hslpicker.com) with ease !

here a website to pick [`Gradients`](https://colordesigner.io/gradient-generator) with ease !

- pick direction: to top - to bottom - to right - to left or use degrees for example 45deg no spaces


```bash
"gradients":{
        
        "testimonialColor":{
            "direction":"to bottom right",
            "from":"hsla(240, 1%, 18%, 0.251) 0%",
            "to":"hsl(0, 0%, 19%) 97%"
        },

        "cardsColor":{
            "direction":"to bottom right",
            "from":"hsla(240, 1%, 18%, 0.251) 0%",
            "to":"hsla(240, 2%, 11%, 0) 100%",
            "last":"hsl(240, 2%, 13%)"
        },

        "hoverBorder":{
            "direction":"to bottom right",
            "from":"hsl(45, 100%, 71%) 0%",
            "to":"hsla(36, 100%, 69%, 0) 50%"
        },


        "hoverButton":{
            "direction":"135deg",
            "from":"hsla(45, 100%, 71%, 0.251) 0%",
            "to":"hsla(35, 100%, 68%, 0) 59.86%",
            "last":"hsl(240, 2%, 13%)"
        },


        "borderBoxes":{
            "direction":"to bottom right",
            "from":"hsl(0, 0%, 25%) 0%",
            "to":"hsla(0, 0%, 25%, 0) 50%"
        },
        
        "progressbar":{
            "direction":"to right",
            "from":"hsl(45, 100%, 72%)",
            "to":"hsl(35, 100%, 68%)"
        }
        
    },
```