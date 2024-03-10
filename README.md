# Louis Stewart Website

A website dedicated to one of Ireland's greatest musicians, the jazz guitarist Louis Stewart.

Created for a web development assignment for SETU's Computer Science HDip course. This website can be found [here](https://cosmic-lamington-1ac99e.netlify.app/).

## Why

I was struggling to come up with an idea for a site, but I was watching the assessment runthrough video when I heard the idea of making a site for a band. It got me thinking. I used to play music for a living and my hero was Louis Stewart. I transcribed several of his solos, listened to all of his albums, and was fortunate to meet him a couple of times.

Louis had a site several years ago but it seems to have disappeared. Although I haven't listened to his music in a while, it is still very important to me. Although learning to play music is a great thing to do, it can sometimes slightly take away some of the magic when you know exactly what chords, scales, and notes are being used. Listening to Louis brings me back to the feelings I had listening to music before I knew anything about it. I have even transcribed some of his playing, and although I understand it a little it is still magic to me.

## Technologies Used

This site has been built with the static site generator [Eleventy](https://www.11ty.dev/) using the [Nunjucks](https://mozilla.github.io/nunjucks/templating.html) templating language. The website has been deployed on [Netlify](https://app.netlify.com/).

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- Eleventy
    - ```npm install -g @11ty/eleventy```

### Project Setup

- Navigate to the project directory in a command prompt and run ```eleventy```. This will create the site in the **_site** directory.
- Run ```eleventy --serve``` to serve the site locally.

## Project Structure

### Layouts

Layouts are contained in the **_includes** folder.

### CSS

**home.css** contains general or global styles and imports other .css files.

### Images

All images are found in the **/images** folder.

## Sources

Audio was sourced and linked from Bandcamp and Spotify. Images were found through Google Images. Remove.bg and Removal.ai were used to remove the background of the header image of Stewart.

- [https://www.remove.bg/](https://www.remove.bg/)
- [https://removal.ai/](https://removal.ai/)

W3Schools articles on CSS Image Galleries and Navbars were used.

- [https://www.w3schools.com/css/css_image_gallery.asp](https://www.w3schools.com/css/css_image_gallery.asp)
- [https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp](https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp)