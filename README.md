# My Personal Portfolio

This is a repository for my personal portfolio webpage, which tracks the site and all I add to it. It was originally created as part of the FreeCodeCamp Responsive Web Design certification, but I have added to it since.

You can access my website at [doctor-glass.github.io](https://doctor-glass.github.io/)

## How I Developed My Portfolio.

I started with a blank canvas and threw on the usual necessities. From there I put together a responsive top navbar and some early sections for the site. I chose a responsive top navbar because it gave the website a clean and professional look and feel, placing all of the relevant links at the top for ease of access yet keeping the content at the center of focus.

From there I decided to build my website around a unifying color palette. I initially found a palette at [colorhunt.co](https://colorhunt.co/palette/ccffbd7eca9c40394a1c1427), which offered some nice green and black colors that complemented each other well. I chose green and black as the color themes for my website in order to emulate old-school computer terminals that typically displayed text in those colors, green text on a black background. The colors I used in this site are `#CCFFBD`, `#7ECA9C`, `#40394A`, and `#1C1427`. I followed the pattern on the black and gray colors to add a few more, including `#645E6D` and `#898390`.

That theme worked, but I didn't quite like it. From there I went with another palette from [coolors.co](https://coolors.co/f03a47-fffcf2-44cf6c-4357ad-3c3c3b). It's a little more vibrant and offers a bit more variety for the eye.

After that, I decided to choose a font for my site. In keeping with the terminal theme, I decided to use a monospace font. I'm a big fan of monospace fonts and use them a lot in my personal life (they're particularly handy for spreadsheets, where consistent character widths make comparing data at a glance easy), so it also fit well for a personal site. However, I wanted a font that wouldn't look too stiff and robotic, but slightly more organic. I wanted a site that had a theme that was structured and orderly, yet welcoming and inviting. To that end I decided to use the [Noto Sans Mono](https://fonts.google.com/noto/specimen/Noto+Sans+Mono/) font, which is monospace and yet organic enough. I added that to my project and started working.

One problem I had to solve on this project was the fact that the top navbar made the links scroll oddly. When clicking on a nav link at the top of the page, the page would scroll that header to the top of the screen, which cut off the first 50px of the header. To solve that, I added the following to my stylesheet:

```css
html {
  scroll-padding-top: 50px;
}
```

This padded out the scroll destination for the anchors, solving the problem.
