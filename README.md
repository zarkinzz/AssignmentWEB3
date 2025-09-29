# Assignment 3 - Website Design and Layout

**Authors:** Shokobalinova Dana, Unerbek Yerassyl
**Course:** SE-2402
**Deployed Site:** [https://air.yeunikey.dev](https://air.yeunikey.dev)
**GitHub Repository:** [https://github.com/zarkinzz/AssignmentWEB3.git](https://github.com/zarkinzz/AssignmentWEB3.git)

## Overview

This project involves creating a simple, responsive website layout using HTML and CSS. The website includes a header with navigation links, a flexible card layout for popular travel destinations, and a grid-based image gallery for a clean and structured presentation.

## Header Section

The header of the website is designed with a **container class** called `header_top`. It includes two main sections:

* **Company Name**: A label showing the company or site name.
* **Navigation Links**: Links to other pages such as "Поиск рейсов" (Search Flights) and "Галерея" (Gallery).
* **User Profile**: A small section displaying the user's profile picture and name ("Ерасыл").

This layout is simple and allows users to quickly access different sections of the site.

## Card Layout Using Flexbox

For the card section, a **Flexbox layout** is used to create three responsive cards. Each card represents a popular travel destination and includes:

* An image of the destination.
* A "Search" button placed under each image for interaction.

The Flexbox layout ensures that the cards are evenly spaced and adapt to various screen sizes, making the design both desktop- and mobile-friendly.

## Page Layout with Fixed Header and Footer

The website layout uses a **fixed header and footer**. The header remains at the top of the screen, while the footer stays at the bottom. The main content area expands to fill the space between the header and footer, ensuring a clean and organized structure. This layout makes the website easy to navigate and keeps important elements like flight details always accessible.

## Image Gallery Layout with Grid

An **image gallery** is designed using a **grid layout**. The gallery contains several images that are:

* Each image is placed inside a container with the `gallery_item` class.
* A parent div with the class `gallery_grid` uses the grid system to arrange the images in a uniform and responsive manner.

The images are displayed in equal sizes to maintain a consistent look and are distributed evenly across the container. This ensures the gallery looks well-organized on various screen sizes.

## Conclusion

The website features a clean and responsive design with easy navigation, a flexible card layout, and an organized image gallery. The use of Flexbox and Grid layouts makes the site adaptable to different devices, ensuring a great user experience on both desktop and mobile devices.
