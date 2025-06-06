# Phone Catalog👌

## Description

A responsive single-page application (SPA) that showcases a catalog of phones, tablets, and accessories. Built with React and TypeScript, the project offers a smooth and intuitive shopping experience with dynamic data loading and Skeleton placeholders to enhance perceived performance. Users can browse, filter, and sort products, view detailed product pages, switch between light and dark themes, and manage items in a shopping cart or favorites list. The application aims to simulate a real online store environment for learning and practice purposes.

## Live Demo

Experience the live website: [Phone Catalog Demo](https://VladTk.github.io/phone-catalog/)

## Design Reference

The project was built based on the following Figma designs:
- [Phone Catalog — Light Theme](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original)
- [Phone Catalog — Dark Theme](https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog--V2--Original-Dark)

## Technologies Used

- HTML5
- CSS3
- SCSS
- React
- TypeScript
- Rest API
- Git
- Vite
- React Router
- React Context API

## Features

* **Responsive Design:** Fully responsive layout with breakpoints at 320px, 640px and 1200px — optimized for all screen sizes.
* **Navigation:** Implemented with *react-router-dom*, supporting dynamic routing and persistent URL query parameters.
* **Favorites & Cart:** Users can add items to favorites or the shopping cart, with real-time total price calculation and persistent storage via *localStorage*.
* **Product Filtering:** Products can be filtered by internal specifications (like capacity and color) directly within product cards.
* **Sorting:** Sorting options include price (ascending/descending), year of release, and alphabetical order.
* **Search:** Search functionality based on URL query parameters with immediate filtering results.
* **Pagination:** Pagination with customizable items per page; supports smooth transitions between product pages.
* **Dark/Light Theme Toggle:** Switch between themes to match user preference and system settings.
* **Sticky Header:** Main navigation remains visible during scroll for improved usability.
* **Scroll to Top Button:** Allows users to quickly return to the top of the page with a smooth scroll.
* **Skeleton Loader:** Displays loading placeholders while data is being fetched, improving perceived performance.
* **Lazy Loading for Images:** Product images are loaded lazily to optimize initial load time and performance.

## Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/VladTk/phone-catalog.git
cd project-name
```

### 2. Install dependencies

Using npm:
```bash
npm install
```

Or using yarn:
```bash
yarn install
```

### 3. Run the development server

Using npm:
```bash
npm start
```

Or using yarn:
```bash
yarn start
```

The application will be available at http://localhost:3000/ by default.

## Preview
[![Screenshot of the home page](https://i.postimg.cc/j5P1Vp3Y/Screenshot-2025-06-06-013250.png)](https://postimg.cc/R6CdKDzg)
