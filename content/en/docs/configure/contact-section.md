---
title: "Contact section"
description: ""
lead: ""
date: 2022-08-15T02:48:08+02:00
lastmod: 2022-08-15T02:48:08+02:00
draft: false
images: []
menu:
  docs:
    parent: "configure"
weight: 260
toc: true
---


{{< alert icon="👉" text="go to src/data/Contact.json" />}}

### Enable Contact

we integrated [`EmailJs`](https://www.emailjs.com) in vCard so head up to emailjs and signup for account 

- first pick a service -> most common is Gmail

![Image](images/pick-service.png "pick-service")


- keep the service id cause we will need it later
- login up with your service provider in this case is gmail

![Image](images/setup-service.png "pick-service")

- go to template section to configure one
- click on create a template

![Image](images/create-template.png "pick-service")


- {{ name }} equal to user name
- {{ message }} equal to user message
- {{ email }} equal to user email
- go to setting and get the template id cause we will need it later
- save it
 
![Image](images/setup-template.png "setup-template")

- go to account setting
- and copy public key

![Image](images/setting.png "setting")


- go to your files and paste all your info here

```bash 
  "turnOnContact":true, <-- switch between true and false to turn contact section off
  "serviceKey":"service_igsd34",  <-- paste here
  "templateKey":"template_3gwdg12", <-- paste here
  "publicKey":"Ne8dmV0wewsxsdew_U", <-- paste here
```

thats it you should have a working contact section !! gratz


### Edit Map

go to [`MapGenerator`](https://google-map-generator.com) 

- get your location
- make your own customization
- then click on Get HTML-Code
- only pick the src value
- copy the start of the quote till the end  src=" value "

![Image](images/map-link.png "setup-template")


go back to the file and paste it there

```bash
"mapLink":"https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d199666.5651251294!2d-121.58334177520186!3d38" 
```

