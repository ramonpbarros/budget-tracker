# Budget Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/ramonpbarros/)

> Budget Tracker application to allow for offline access and functionality.

## Table of contents

- [General info](#general-info)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Features](#features)
- [Status](#status)
- [Contact](#contact)

## General info

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

## Screenshots

![Example gif](/public/img/project.gif)

## Technologies

- JavaScript
- CSS 3
- HTML 5
- Node.js
- Express
- MongoDB
- IndexedDB

## Setup

This application runs in the browser. Nothing needs to be installed except for your default browser.

- Repository can be found here: [GitHub](https://github.com/ramonpbarros/workout-tracker) Check out the code!

## Code Examples

    if ("serviceWorker" in navigator) {
      window.addEventListener("load", () => {
        navigator.serviceWorker.register("service-worker.js").then(reg => {
          console.log("We found your service worker file!", reg);
        });
      });
    }

## Features

List of features:

- Enter deposits offline.
- Enter expenses offline.

To-do list:

- Better UI.

## Status

Project is: _in progress_

- Make sure to check the application [here](https://serene-atoll-05842.herokuapp.com/).

## Contact

Created by [@ramonpbarros](https://ramonbarros.me/) - feel free to contact me!
