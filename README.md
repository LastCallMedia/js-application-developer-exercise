Javascript Application Developer Exercise
=====================================

This exercise is designed to assess your skills and to see how you solve problems. Please don't spend more than 3 hours working on it, and if you have trouble completing it in that time, don't stress about it - just push up whatever you have. There is no right answer here, and work-in-progress code is fine, as long as you can explain what you were working on during the interview.

Thanks, and good luck!

Instructions
------------

1. Read "The Exercise" below.
2. Clone this repository down locally, and perform the exercise.
3. Push your work up to a new, *private* repository in your own Github account.
4. At some point before your interview, give the Github user [`lastcall-automation`](https://github.com/lastcall-automation) read access to your repository.

The Exercise
------------

Last Call Media's [website](https://lastcallmedia.com) wants to change it's background, but we don't know what would fit best. Create a way to select from the available backgrounds and switch between them seemlessly.

* Checkout `backgrounds.js` to view the available backgrounds you can use. You'll see the following object which will correspond to a file we've already added to the `public` folder called "a-background-here.ext". You can use this to get the source path to each of the different backgrounds.
```
{
  name: "a-background-here"
  type: "ext"
}
```
* In `App.css` you'll find useful styles you can use to center the background media and the select field.The styles provided are targetting the latest version of Chrome browser.
* Videos should automatically play in a loop when selected, but should be muted.
* Selecting a different value in a select field should immediately change the background.

Stretch goal:
* Try switching backgrounds without the flickering of loading in the next one we selected.

To get started, run:
```
npm install
npm start
```
