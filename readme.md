# Heaven On High - Accursed Hoard Tracker

https://joey-robinson.github.io/muhhoard/index.html

## Goals: 

Using my skills to create and have a repository of images that show possible locations of accursed hoard throughout Heaven On High in Final Fantasy 14. 

## Methods And Tools:

I had set out to make this using what I already knew, HTML, CSS, and JS. I used JavaScript to handle the image changing on each page. When an image is clicked, it becomes the primary image. 

For the design, I used CSS Grid and scss to style everything then used npm scripts to compile the scss into css for production and deployment. 

Each page is built using HTML and each page follows the same layout. 

## Usage:

To use, first clone or download the repository. After you've done that, CD into the directory and type:

```javascript
npm install
```

in your terminal to install all the dependencies from the package.json file. After then install process, in your terminal type the following:

```javascript
npm start
```

to get the app started. After that you're free to change things as you see fit. Once you've gotten to a stopping point and want to deploy to production, type the following in your terminal

```javascript
npm run build:css
```

and you're done! If you come across any problems during the start or build process, check to see if you have node-sass installed. In your terminal, type the following:

```javascript
npm install node-sass
```

or

```javascript
npm install node-sass -g
```

one of those should fix any issues you have, if not, feel free to open an issues ticket in the repository.

### Closing Statements:

If I ever rebuild this, I'll use GatsbyJS. The way I approached this isn't ideal but it worked out how I wanted. I should have made an API call to imgur for albumns for each html page, instead of having the static data inside of each html page.

