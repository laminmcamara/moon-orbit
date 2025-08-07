# CSS Animation: Moon Orbit - FreeCodeCamp Project

## 1. Project Overview

This project is a practical exercise from the FreeCodeCamp curriculum, designed to teach and reinforce core concepts of CSS animations and transforms. The goal is to create a visual animation of a moon orbiting the Earth using only HTML and CSS. This demonstrates how complex motion can be achieved by nesting positioned and animated elements.

This project can be viewed by opening the `index.html` file in any modern web browser.

---

## 2. Purpose and Learning Objectives

The primary purpose of this project is to build a deeper understanding of CSS positioning and animation. The key skills demonstrated are:

*   **CSS Positioning:** Using `position: relative` on a parent container (`.space`) to create a positioning context for `position: absolute` children (`.earth`, `.orbit`).
*   **The Absolute Centering Trick:** Mastering the technique of combining `top: 50%`, `left: 50%`, and `transform: translate(-50%, -50%)` to perfectly center an element within its parent.
*   **CSS Keyframe Animations:** Defining a simple, continuous rotation animation using the `@keyframes` at-rule.
*   **Nested Animations:** Creating the illusion of an orbit by placing a static element (`.moon`) inside a rotating parent container (`.orbit`). The moon itself doesn't have an orbit animation; it is simply "carried" by its parent.
*   **CSS Transforms:** Using `transform: rotate()` to create the orbital motion and `transform: translateX()` to precisely position an element.
*   **Basic Structuring:** Using simple, semantic HTML to structure the elements of the animation.

---

## 3. Technologies Used

*   **HTML5:** For the fundamental structure of the space, earth, orbit, and moon elements.
*   **CSS3:** For all styling, positioning, and animation logic.
    *   **Flexbox:** To center the entire animation on the page.
    *   **Positioning:** `relative` and `absolute`.
    *   **Transforms:** `translate()`, `translateX()`, and `rotate()`.
    *   **Animations:** `@keyframes` and the `animation` property.

---

## 4. How to View the Project

1.  Clone or download the project repository.
2.  Navigate to the project folder.
3.  Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Safari).

The animation will begin immediately upon loading the page.