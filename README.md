# Nice Shop

## Overview

Nice Shop is an online store for phones, tablets and accessories, built with a focus on user experience and modern web practices. Users can browse product catalogs, filter and sort items, view detailed product pages with photo galleries and technical specs, add products to a shopping cart, and save favorites — all with state persisted in the browser.

## Demo

You can view a live demo of the application here: [DEMO](https://artembaranovsky1.github.io/react_phone-catalog)

## Key Features

- **Image Sliders:** Banner and product sliders built with Swiper.
- **Product Catalogs:** Separate catalogs for phones, tablets and accessories.
- **Filtering and Sorting:** Sort and filter products to quickly find the right item.
- **Product Details:** Photo gallery, color and capacity selection, and full technical specs.
- **Shopping Cart:** Add and remove products and manage quantities, with state saved in localStorage.
- **Favorites:** Save products to a favorites list that persists between sessions.
- **Responsive Layout:** Adapted for desktop, tablet and mobile screens.

## Challenges

Building the application involved several challenges around feature integration and keeping the experience smooth across devices.

- **State Management:** Keeping the cart and favorites in sync across pages and persisting them in localStorage.
- **Product Variants:** Handling color and capacity selection so that the correct product, photos and specs are shown for each variant.
- **Filtering and Sorting:** Combining filters, sorting and URL parameters so that catalog state is preserved on navigation and page reload.
- **Responsive Design:** Making sliders, galleries and product grids work well on all screen sizes.
- **Testing:** Covering key user flows with Cypress end-to-end tests.

## Installation & Setup

1. Clone the repository:

```
git clone https://github.com/artembaranovsky1/Nice-Shop.git
```

2. Navigate to the project directory:

```
cd Nice-Shop
```

3. Install dependencies:

```
npm install
```

4. Start the local development server:

```
npm start
```

5. Build the project:

```
npm run build
```

## Technologies Used

- **React:** For building the user interface.
- **TypeScript:** For type safety and a better development experience.
- **React Router:** For routing and navigation.
- **Sass (SCSS):** For advanced styling capabilities.
- **Bulma:** For base layout and UI components.
- **Swiper:** For image and product sliders.
- **Vite:** For fast development and optimized builds.
- **Cypress:** For end-to-end testing.
