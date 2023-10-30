# Next E-commerce Store Application

Next full stack application for E-commerce stores + Admin dashboard & CMS using Next.js, React, Tailwind, Prisma, Planetscale, MySQL & Stripe.

This project uses the [ADMIN DASHBOARD CMS PROJECT](https://github.com/nrocchi/next-ecommerce-admin-app)

use [Stripe Testing Cards](https://stripe.com/docs/testing)

## Features

- Admin dashboard CMS with multiple stores : handle multiple stores through this single CMS! (For example you can have a "First store" and a "Second store", and our CMS will generate API routes for all of those individually!)
- CMS for Billboards, Products, Categories, Sizes, Colors, Settings...
- Search Feature and Pagination for each API
- Featured products for the Home page
- Chart statistics with Recharts
- Tailwind CSS with Shadcn UI
- Clerk Authentication
- Cloudinary images upload
- Orders creation
- Stripe checkout
- Stripe webhooks
- MySQL + Prisma + PlanetScale

## Installation

### MAKE SURE YOU HAVE [ADMIN DASHBOARD CMS](https://github.com/nrocchi/next-ecommerce-admin-app) SETUP FIRST

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/nrocchi/next-ecommerce-store-app.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_API_URL=
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

## Contributors

The original author is [Nicolas Rocchi](https://github.com/nrocchi).
