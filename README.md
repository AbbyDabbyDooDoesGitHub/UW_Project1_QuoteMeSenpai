# Project 1: Quote Me Senpai!
Quotes and Photos from your favorite anime shows

## Overview
Create a Quiz to test Anime Knowledge... Do you know who said what?
Ensure Webpage is Functioning as Intended (ie: all links work, etc)
Create an End Product that works on Desktop and Mobile
Use Framework other than Bootstrap (we chose to utilize [Materialize](https://materializecss.com/))
Have Features that Utilize Local Storage

## Contributers
- [Abigail Douglas](https://github.com/AbbyDabbyDooDoesGitHub)
- [Ben Holgate](https://github.com/holgateb)
- [Robert Bishop](https://github.com/rbishop85)
- [Mary Villoso](https://github.com/marycv)
- [Alka Sah](https://github.com/alka485)
- [Priyanka Ghale](https://github.com/prigh-a)

## Technologies Used
- HTML
- CSS
- Javascript
- Materialize CSS Framework
- Nekos Best API
- AnimeChan API
- Google Fonts
- JSON

## Installation

1. Clone this repository to your computer's desktop.
2. Navigate to the top level directory.
3. Open the index.html file in a browser.

## Usage

![Screenshot of Website](./assets/images/screenshot.png)

## Link to Web App:  https://abbydabbydoodoesgithub.github.io/quote-me-senpai/

## API - get quotes by anime title
fetch('https://animechan.vercel.app/api/quotes/anime?title=naruto')
     .then(response => response.json())
     .then(quotes => console.log(quotes))

## API - get quotes by character name
fetch('https://animechan.vercel.app/api/quotes/character?name=saitama')
     .then(response => response.json())
     .then(quotes => console.log(quotes))

## API - get anime images and gifs
https://nekos.best/api/v2/thumbsup?amount=20https://nekos.best/api/v2/thumbsup
