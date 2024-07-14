# Full-Stack Developer Bootcamp Module 09 - Project: Movie Finder

## Table of Contents

- [Description](#description)
- [Install](#install)
- [Usage](#usage)
- [Generator](#generator)
- [Badge](#badge)
- [Credit and Source Code](#credits-and-code-source)
- [Related Efforts](#related-efforts)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)
- [Tests](#tests)
- [GitHub Repository Location (HTTPS)](#github-repository-location-https)
- [GitHub Pages Location](#github-pages-location)
- [Application Screenshots](#application-screenshots) 


## Description

The Movie Finder is a browser-based application that enables Users to search the third-party website IMDb for movies, by name, and returns both information about the movies as well as idenfities Streaming Services currently hosting the movies for view.

IMDb is a comprehensive online database of movies, and television shows, providing expansive information such as movie and program summaries, release dates, actors, writers, producers, and crew, as well as movie and program rankings, and contact information for cast and crew. The third-party API utilized in the Movie Finder app queries current IMDb data and returns data parameterized for the U.S. region, only.

The Movie Finder app displays key, relevant information for searched movies, and maintains a instance-specific history of previously searched movies, enabling quick refresh of prior movie information and availability.

Utilizing the movie identification information provided by IMDb--the defacto industry reference for movies and programs--the Movie Finder app invokes a second API to return details of, and links to, Streaming Services that offer the identified movies in the U.S. The Movie Finder app differentiates and identifies Streaming options by offer type (rent, purchase) and streaming resolution (HD, UHD).

The Movie Finder app places accurate, current Movie information at Users' fingertips, utilizing the industry-leading movie information of IMDb through responsive, flexible third-party APIs.

As developed, the Movie Finder app is only accessible through a local instance, specific to each accessing computer.

Movie Finder data is "live," through active refreshes using third-party APIs, but historical movie searches are held in Local Storage and, consequently, not currently accessible through the Web.

The Movie Finder app source code is published on GitHub, and may be cloned to individual User computers to instantiate local versions.

Movie Finder historical movie name-based earches are recorded through a Movie Name search entry form availabe in the app itself and aggregated and displayed in the app sidebar UI.

The app utlizes an HTML-based Form to ingest User search input, JavaScript to push movie name-based searches to Local Storage, and dynamically update the app with newly-searched movies, and Tailwind to style the site. JavaScript is also used to drive third-party API calls, and responsive behavior, such as search history display updates.

Because the Movie Finder app is held in Local Storage, movie search entries will persist across User sessions on individual, hosting computers.


## Installation

The Movie Finder app source code may be downloaded from its GitHub repository, and run directly by a hosting computer.

No Installation of the Movie Finder app is required; the app is fully browser-based, accessible through any modern browser that supports JavaScript.

Tailwind-provided styling utilizes standard CSS libraries already available to modern browsers, and requires no installations or other actions by Users to enjoy the styling that it provides.


## Usage

The Movie Finder app is intended for use by one or more Users to view personalized movie information specific to User-selected movies and maintain a quick-access history of movie searches that will be held locally, persisting across multiple sessions. 

All Users of the Movie Finder app on a local computer will have full visibility to all movie name searches.


## Credits and Code Source

Code, where referenced from a third-party Source, is noted in Comments accompanying the relevant Code lines.


## License

Copyright <YEAR> <COPYRIGHT Chris Milazzo>


MIT License

Copyright (c) 2024 MeanderingBrook

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Badges

N / A


## Features

N / A


## How to Contribute

N / A


## Tests

API parameter testing and data evaluation, see test.js (Archive)

JavaScript-created Movie Finder presentation of movie search entries as &lt;ul&gt; to confirm searchHistory (Array) update.

`console.log` output of third-party IMDb and Streaming Services API data specific to called movies and search history data on search requests; see script.js.


## GitHub Repository Location (HTTPS)

https://github.com/DevWes91/Group-Project-1.git


## GitHub Pages Location

* PENDING *


## Application Screenshots

![Movie Finder: Empty UI Screenshot](?raw=true "Movie Finder: Empty UI Screenshot")

![Movie Finder: Populated UI Screenshot 01 - Titanic](?raw=true "Movie Finder: Populated UI Screenshot 01 - Titanic")

![Movie Finder: Populated UI Screenshot 01 - Star Wars](?raw=true "Movie Finder: Populated UI Screenshot 01 - Star Wars")

![Movie Finder: Populated UI Screenshot 01 - Barbie](?raw=true "Movie Finder: Populated UI Screenshot 01 - Barbie")