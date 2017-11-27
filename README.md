# CSS Clocks

Clocks developed using CSS and HTML, without any JavaScript or any other scripting language<sup>*</sup>.

Many of these clocks were developed as part of an app I developed a few years back titled MultiClocks, but they used JavaScript to function. I removed the JavaScript and added CSS animations to make them work again.

## The Clocks

### Analog Clock

The traditional analog clock, with 3 arms pointing to the hours, minutes, and seconds.

![Analog Clock on Imgur](https://i.imgur.com/BPp3t6T.jpg)

### Radial Clock

A set of concentric circles with hours, minutes, and seconds written in text, they rotate (see versions below) to let the current time visible in the center line.

There are two versions of this clock: one in which the rotation is continuous/progressive, and another in which the rotation is step by step (changes every second).

![Radial Clock on Imgur](https://i.imgur.com/ohbO3BE.jpg)

### Square Text Clock

In this clock, the approximate time (it has an error of +/- 4 minutes) is displayed via text, highlighting the current time in a bright color while the rest of the letters are darker.

This was actually a really tricky clock to develop only with HTML and CSS. I used SASS/SCSS because it saved me writing hundreds of lines of code.

![Square Text Clock on Imgur](https://i.imgur.com/O69bSLV.jpg)


## Demos

You can see demos for these clocks on my CodePen:

- [Analog clock](https://codepen.io/alvaromontoro/full/jGYQoP/)
- [Radial clock (progressive)](https://codepen.io/alvaromontoro/full/zEjLag/)
- [Radial clock (step by step)](https://codepen.io/alvaromontoro/full/oGygKq/)
- [Square Text clock](https://codepen.io/alvaromontoro/full/Nwgarb/)

<br/>
<br/>

---
<sup>*</sup> For demo purposes, the HTML files include a small JavaScript snippet with the purpose of setting the clock for the right time. This script is not necessary to make the clock work, and can be substituted for a small code on the server side.
