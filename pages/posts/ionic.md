---
title: "PWA with IONIC"
date: 2024/3/18
description: "Ionic Framework is an open source UI toolkit for building performant, high-quality mobile and desktop apps using the latest web technologies (HTML,CSS, JS) "

---



#### one code for all: Android, IOS and Web

Step by step instruction, how to build a PWA
Create a progressive Web App with Ionic
I am using Visual Code Studio from Microsoft. Make sure to have NodeJS installed.

### Start with a template

```
npm install -g ionic
ionic start myApp
cd myApp
ionic serve
```

### Make it ready for production

```
ng add @angular/pwa
ionic build --prod --service-worker
npm install -g firebase-tools
ionic serve
```

### Certainly , you want to make your App accessible for everyone on the internet

I am using Firebase for that  purpose

```
ionic build --prod
firebase init
firebase serve (check before you deploy)
firebase deploy

```


