# About

In this motion design training project, I practice how how to include motion in my web design projects using video, CSS, JavaScript, GSAP, SVG, Lottie, and more.

This will help bring websites to life and make them more interesting and memorable.

## What is Motion Design?

Motion design is a creative discipline that uses **animation** and **visual effects** to bring statuc elements to life. It involves manipulating visual elements like **text**, **illustations** and **images** to create engaging and dynamic **motion graphics**.

## Remember

* Not all CSS properties support transitions, like for example **background**. However, there are workarounds, one of which being the use of **pseudo-elements**.

* Not all transitions in a page need the same **duration**. Sometimes, using a longer transition among shorter ones can create a very satisfying movement.

* Transitions are **not limited** to hover states. For example, they can be **triggered** when an element receives a certain *class*.

## CSS Animations

A CSS **animation** is a way to make elements **gradually change** their appearance or position over time.

It's done by defining **keyframes**, which are the in-between states of this change. The animation is then created by smoothly **transitioning** beetween these keyframes.

### Is the order important?

The order of time values is important! The **first** one that can be parsed as a time value is assigned to the *animation-duration*, and the **second** one is assigned to the *animation-delay*.

### It's important to keep in mind

If a value can be used for something **other than the animation's name**, it's applied to that property first.