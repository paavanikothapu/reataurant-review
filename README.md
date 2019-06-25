# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
## Steps taken to complete the task
. To loads the map, I used JavaScript token from `mapbox`
. And also added link in the **index.html**, **restaurant.html** to connect with `mapbox`.
## Installation and run locally
. First this repository.
. Clone this repository to your desktop.
. Open the root folder of the repository in a terminal
. Check your python version by python -V
. Start local server:
. For Python 3.x: python3 -m http.server 8000
. Provide data from node server (see below)
. Visit http://localhost:8000
## Requirements
. App includes all requirements, including restaurant information, customer reviews and a new review form.
. App is equally functional on mobile and desktop, using responsive design to ensure its displayed in a useable state.
. All content-related images include appropriate alternate text.
. Focus is appropriately managed allowing users to noticeably tab through each of the important elements of the page.
. Modal or interstitial windows appropriately lock focus.
. Elements on the page use the appropriate semantic elements. For those elements in which a semantic element is not available, appropriate ARIA roles are defined.
. Color selections and contrast are made with accessibility in mind.
## Features
. View all restaurants in map
. View restaurants for a specific district or cuisine
. View details to a restaurant like opening hours and reviews
. Write reviews for a restaurant
. Mark a restaurant as our favorite
. View already loaded pages also in offline mode
## What I feel about this project
. This is very great opportunity for me to learn the restaurant review application and also I thankful to **Udacity Team** .
