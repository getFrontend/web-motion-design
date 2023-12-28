# About

In this motion design training project, I practice how how to include motion in my web design projects using video, CSS, JavaScript, GSAP, SVG, Lottie, and more.

This will help bring websites to life and make them more interesting and memorable.

## What is Motion Design?

Motion design is a creative discipline that uses **animation** and **visual effects** to bring statuc elements to life. It involves manipulating visual elements like **text**, **illustations** and **images** to create engaging and dynamic **motion graphics**.

## CSS transitions

Remember that:

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

## Difference between animations & transitions

An animation is basically a series of **keyframes**, of **steps** and you can gave any number of those.

**Transitions** can only have **2 steps**: start and end. Nothing in between.

### Looping

Animations support **looping**. Meaning it can be run once, twice, 10 times or **continuously**.

**Transitions** on the other hand run **just once**.

### Direction

You see, **transitions** have a **fixed direction**, meaning they go one way.

Animations can go **forward, in reverse** and they can even **alternate** between the two.

### Play State

An animation can be **paused**. Transitions cannot. Once a transition starts, it runs to the end. But an animation can be paused or resumed at any point.