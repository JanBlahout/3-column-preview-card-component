# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Live Site URL: https://frosty-fermi-147c81.netlify.app/

## My process

Started marking up the html.
The first step was to make a container and center it.
I found out the main thing is setting min-height to 100vh. That way i am able to center the container. Used body as flex column direction, align and justify center.

Then I separated the text into 3 sections based on category and went from there. Styled text, styled button, put in the margins.

Lastly fiddle with the padding, margin, max width and then go with the querries.

### Built with

- Semantic HTML5 markup
- CSS Grid
- Desktop-first workflow

### What I learned

I have learned how to use "a href" as buttons.
One of the lines of the codes I am really proud of is hover and creating a "border".
Its not a border per say but inset box shadow. I tried border but it will move the 1-2 pixels of the border. If you do it with border shadow nothing moves.

To see how you can add code snippets, see below:

```css
/* how to center a div */
body {
  background-color: hsl(0, 0%, 95%);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  min-height: 100vh;
  font-family: "Lexend Deca", sans-serif;
}

.car-box .btn,
.car-box .btn:hover,
.car-box .btn:active {
  background-color: inherit;
  box-shadow: inset 0 0 0 1.5px hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
}
```

### Continued development

I would like to use css properties way more. If I understand that correctly its like variables so I dont have to remember colours all the time.

The next step would be to start usin REM( or em) units to better scale with querries.

In one course there was a hint:
html {
font-size: 62.5%
}

that way 1 rem = 10px and later on in querries you just go font-size: 80% etc to scale it up or down.

### Useful resources

- I have used course on Udemy to help me style the links (buttons). I already had that but feel free to google / youtube any other guide for that. I found out its very common to do it that way.

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/JanBlahout
