# Progressive Web Applications (PWA): Text Editor

This project is divided into three parts

1. Introduction
2. Problem
3. Solution

## Introduction

This project is to build a text editor that runs in the browser. The app isa single-page application that meets the PWA criteria. Additionally, it has the feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor, had to start with an existing application and implement methods for getting and storing data to an IndexedDB database. Have used a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

You will deploy this full-stack application to Render using the [Render Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide).

## Problem

Understanding PWA concepts and manifest and service worker to work to run the application was a real journey.

## Solution

GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application

## Mock-Up
https://pwa-text-edit-xd1h.onrender.com

<img width="938" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/1b35c08f-26aa-45cc-b3e4-6db4b6a5ab25">


<img width="947" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/d0bf7883-8fa9-4869-90b9-ac9511a4def8">

<img width="1177" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/21122cd5-ef6c-45be-8015-ee257d640c7f">

<img width="506" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/1c6dcf5a-4d46-4f7a-8df5-bea6336e53e3">

<img width="670" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/b6704e87-09e4-4a10-a482-f1ecb4c901bc">

<img width="1187" alt="image" src="https://github.com/MeerKar/Text-Editor-PWA/assets/116701851/0d5992e5-680f-4fb5-b03d-e1a19b33341f">






