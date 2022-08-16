---
title: "About section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 220
toc: true
---


{{< alert icon="👉" text="go to src/data/About.json" />}}

### Edit About me

Add or remove text as needed 

```bash
  "aboutMe": [
        {
            "text":"I'm Creative Director and UI/UX Designer from Sydney, Australia, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs."
        },
        {
            "text":"My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I created web design for many famous brand companies."
        }
    ],
```



### Edit Cards

get svg from [`Here`](https://ionic.io/ionicons)

- search for your desired svg 
- put it in public/images
- open it add this attribute with your desired color in hex --> fill="#AB7C94"
- get the path and put it in cardImage

![Image](images/download-svg.png "svg")

Add or remove cards as needed

```bash
"showCards":true, <-- switch between true and false to remove it from the page
  "cards": [
      {
          "cardImage":"/images/icon-design.svg", <-- put your svg path
          "cardTitle":"Web Design",
          "cardDescription":"The most modern and high-quality design made at a professional level."
      },
      {
          "cardImage":"/images/icon-design.svg",
          "cardTitle":"Web Design",
          "cardDescription":"The most modern and high-quality design made at a professional level."
      },
      {
          "cardImage":"/images/icon-design.svg",
          "cardTitle":"Web Design",
          "cardDescription":"The most modern and high-quality design made at a professional level."
      },
      {
          "cardImage":"/images/icon-design.svg",
          "cardTitle":"Web Design",
          "cardDescription":"The most modern and high-quality design made at a professional level."
      }
  ],

```

### Edit Testimonials 

Add or remove testimonials as needed

- put testimonial photo it in public/images
- make sure you use different name for every testimonial name to not get any errors

```bash
"showTestimonials": true, <-- switch between true and false to remove it from the page
    "testimonials":[
        {
            "testimonialName":"Daniel lewis",
            "testimonialDescription": "Richard was hired to create a corporate identity. We were very pleased with the work done. She has a lot of experience and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt consectetur adipiscing elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.",
            "testimonialPhoto":"/images/avatar-1.png" <-- photo path
        },
        {
            "testimonialName":"Daniel z",
            "testimonialDescription": "Richard was hired to create a corporate identity. We were very pleased with the work done. She has a lot of experience and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt consectetur adipiscing elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.",
            "testimonialPhoto":"/images/avatar-1.png"
        },
        {
            "testimonialName":"Daniel d",
            "testimonialDescription": "Richard was hired to create a corporate identity. We were very pleased with the work done. She has a lot of experience and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt consectetur adipiscing elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.",
            "testimonialPhoto":"/images/avatar-1.png"
        },
        {
            "testimonialName":"Daniel f",
            "testimonialDescription": "Richard was hired to create a corporate identity. We were very pleased with the work done. She has a lot of experience and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt consectetur adipiscing elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.",
            "testimonialPhoto":"/images/avatar-1.png"
        }
    ],

```

### Edit clients

Add or remove clients as needed

here you can put your clients logos 

```bash
 "showClients":true, <-- switch between true and false to remove it from the page
    "clients":[
        {
            "clientImage":"/images/logo-2-color.png",
            "clientLink":"https://facebook.com" <-- add client website link
        },
        {
            "clientImage":"/images/logo-2-color.png",
            "clientLink":"#"
        },
        {
            "clientImage":"/images/logo-2-color.png",
            "clientLink":"#"
        },
        {
            "clientImage":"/images/logo-2-color.png",
            "clientLink":"#"
        },
        {
            "clientImage":"/images/logo-2-color.png",
            "clientLink":"#"
        }
    ]

```