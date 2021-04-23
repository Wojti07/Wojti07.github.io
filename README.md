# Portfolio

https://wojti07.github.io/

## Table of contents

- [General info](#general-info)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Contact](#contact)

## General info

Responsive portfolio page about me. It consists of several pages, uses a CSS preprocessor,
also contains a small JavaScript code. Maybe you can read some information about me privately
and about my professional experience. You can also find some projects made by me.e.

## Screenshots

![Example screenshot](./src/images/portfolio.jpg)

## Technologies

- HTML 5
- CSS 3
- JavaScript
- Sass
- RWD

## Code Examples

"use strict";

const menuBtn = document.querySelector(".menu-btn");
const hamburger = document.querySelector(".menu-btn**burger");
const nav = document.querySelector(".nav");
const menuNav = document.querySelector(".menu-nav");
const navItems = document.querySelectorAll(".menu-nav**item");

let showMenu = false;

menuBtn.addEventListener("click", toggleMenu);

function toggleMenu() {
if (!showMenu) {
hamburger.classList.add("open");
nav.classList.add("open");
menuNav.classList.add("open");
navItems.forEach((item) => item.classList.add("open"));

    showMenu = true;

} else {
hamburger.classList.remove("open");
nav.classList.remove("open");
menuNav.classList.remove("open");
navItems.forEach((item) => item.classList.remove("open"));

    showMenu = false;

}
}

## Contact

Created by me - feel free to contact me!
