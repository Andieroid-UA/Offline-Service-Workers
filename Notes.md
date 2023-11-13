***********************************
# Adding Offline Capabilities with Service Workers

## Module Introduction

Starting with an angular example of a lot of text...

![Alt text](image.png)

![Alt text](image-1.png)

It's a "dummy text" API to get articles on your app. Index also has some special google font!

## Adding Service Workers

So what's a service worker?

![Alt text](image-2.png)

A proxy between your app and the http request (catches the request, then might allow to let it leave the app?)

Not every 3rd party handles this. But this one below does: 

   ng add @angular/pwa

Downloads the Angular service worker package, and start with a preconfigured service worker!

Install a lightweight node server
    npm install -g http-server
    OR
    http-server

## Caching Assets for Offline Use



## Caching Dynamic Assets & URLs