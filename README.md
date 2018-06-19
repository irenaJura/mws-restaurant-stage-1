# Frontend Nanodegree Udacity & Google

## Project Overview:

For this project I was converting a static webpage to a mobile-ready web application. I added accessibility in form of aria-labels and by the use of semantic HTML and alt attributes and made the site responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for users.

### Specification

I have been provided the code for a restaurant reviews website. The code had a lot of issues. It was barely usable on a desktop browser, much less a mobile device. It also didn’t include any standard accessibility features, and it didn’t work offline at all. My job waas to update the code to resolve these issues while still maintaining the included functionality. 

### Instructions 

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

OR use npm live server if you find it easier (I am talking to Windows users like myself :). In this folder run `npm install -g live-server` and after it's installed run the command `live-server`. The new tab will open in your default browser and you got yourself a live reloading local server working! The default port number is 8080 but if you wish to change it just run `live-server --port=NUMBER` where in place of NUMBER you can type a different port number. The port number has to match the one in the dbhelper.js file, line 10: 

static get DATABASE_URL() {
    const port = 8080 // Change this to your server port
    return `http://localhost:${port}/data/restaurants.json`;
  }
  
<strong>Important!!! Change the host address to `localhost:`, the default is set to your IP address.</strong>

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. 



