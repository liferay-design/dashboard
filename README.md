# Team Dashboard

_Built on [Reveal.js](http://revealjs.com)_
_A framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://revealjs.com/)._

## Table of Contents

* [Background](#background)
* [Composition](#composition)
* [Getting Started](#getting-started)
* [Contributing](#contributing)

## Background

There's a projector in our office that we occasionally use for critiques, or team viewings&emdash;but 90% of the time it sits unused. Teams in other parts of the office use their projectors to share dashboards and other status things, we thought it could be a great spot to surface some info about what we're doing!

A couple of us got together on a Friday afternoon, and threw some ideas on a [Freehand](https://liferay.invisionapp.com/freehand/document/D1un6U4eh) and over the course of a long weekend we got a pretty simple couple of slides, some Twitter feeds, and random images from Unsplash.

## Composition

### Slides

#### Static Text

The text is input in the index.html file, read the [reveal.js docs](https://github.com/hakimel/reveal.js#instructions) for more info on editing slides.

#### Dynamic Photos

Currently, we're just pulling a random photo from the [Coastal View](https://unsplash.com/collections/825250/coastal-view) collection using [source.unsplash](http://source.unsplash.com), but would be really great to put together a custom collection, or use the [Unsplash API](http://unsplash.com/developers) to be able to display the photographer, and maybe some keywords in case a really great photo pops up so we can find it.

#### Dynamic Tweets

Dyanmic tweets are displayed in the slides, currently they are just from [lists](https://twitter.com/plhnk/lists) using the embedding tools from [publish.twitter](https://publish.twitter.com/)&emdash;we do have a [developer account](https://developer.twitter.com/en.html) so would be really great to have tweets pulled in this way so more display customization can be made. Reach out to [Paul](http://twitter.com/plhnk) for API keys etc.

Currently, there are four lists:
 1. [Liferay](https://twitter.com/plhnk/lists/liferay) - employees, offices, projects, basically anything officially associated with Liferay. This helps us keep our collective finger on the proverbial pulse.
 1. [Such Frontend](https://twitter.com/plhnk/lists/such-frontend) - developers, designers, pretty much people who are [tweeting tasty treats](http://twitter.com/wesbos) that can take us to the next level in our development.
 1. [Much Design Wow](https://twitter.com/plhnk/lists/much-design-wow) - designers, philosophers, people from all walks, anyone who provides #thoughtleadership or hot tips for designers so we can stay current in Design.
 1. [Liferay.Design](https://twitter.com/plhnk/lists/liferay-design) - designers at Liferay! If you should be on this list, [@me](http://twitter.com/plhnk).

### Sidebar

The Tweets are the last posts from [@Liferay_UX](https://twitter.com/Liferay_UX), [@Liferay](https://twitter.com/Liferay), and a list comprised of [all the Designers at Liferay](https://twitter.com/plhnk/lists/liferay-design).

### Footer

The clock / calendar below the slides is to remind us that life is short, and also tell us the day, date (in YYYY-MM-DD format&emdash;per our DAM guidelines 😬), and current time.

## Getting Started

### Installing and Editing
_(modified from reveal.js docs)_
Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone this repository
   ```sh
   $ git clone https://github.com/liferay-design/dashboard.git
   ```

1. Navigate to the reveal.js folder
   ```sh
   $ cd dashboard
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

### Deploying!
To push your changes live to the web, you need to be added to the Liferay.Design WeDeploy team, _(reach out to [Paul](http://twitter.com/plhnk))_ once you have set that up, simply type: ```we deploy -p liferaydotdesign```.


### Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

## License

GNU GPLv3

Copyright (C) 2018 Liferay Design, https://liferay.design
