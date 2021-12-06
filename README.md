# Fitness Tracker

![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

This is a NodeJS based project using a MongoDB that allows a user to add track their exercise for fitness use.


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Credits](#credits)


## Installation

Download, clone, or fork the repo and run an `npm install` command in the folder directory. This will install the dependencies needed for NodeJS to run the application as listed in `package.json`. This will also seed 

 * [`express`](https://www.npmjs.com/package/express) allows the application to utilize express.
 * [`mongoose`](https://www.npmjs.com/package/mongoose) allows for use of object templates with MongoDB.
 * [`morgan`](https://www.npmjs.com/package/morgan) is an HTTP request middleware logger for nodeJS that allows for easier logging.

To start the application, run `npm start` on the command line.

Alternatively, visit the online version deployed on Heroku, currently under construction, but available here: https://philosophers-fitness-tracker.herokuapp.com/

## Usage

To start the application, run `npm start` on the command line or [visit the deployed version on Heroku] when the bugs have been fixed.

From the main page, you can choose to start a new workout or continue an existing workout. Alternatively, you can also select to go to the Dashboard in the upper left. Selecting the "Fitness Tracker" will take you bac to this main page.

There are 2 types of exercises: Cardio and Resistance.

With Resistance selected, you are required to fill in the exercise name, weight, sets, reps, and duration in minutes.

With Cardio selected, you are required to fill in the exercise name, distance in miles, and duration in minutes.

On the Dashboard page, you can view the history of workouts completed. Hovering over the data will display more information.

## License

Licensed under the [MIT](LICENSE.txt) license.


## Credits
Base development files were provided by the MSU Coding Bootcamp.

The package `express` for NodeJS can be found [here](https://www.npmjs.com/package/express).

The package `mongoose` for NodeJS can be found [here](https://www.npmjs.com/package/mongoose).

The package `morgan` for NodeJS can be found [here](https://www.npmjs.com/package/morgan).


## Questions
GitHub: [MaxAeon](https://github.com/MaxAeon/)

Email: maxaeonparks@gmail.com
