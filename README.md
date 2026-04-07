# NewdreamCMS

NewdreamCMS is a Next.js admin dashboard for managing furniture products and customer orders.

## Features

- Add products with title, category, description, price, and optional image URL.
- View incoming orders from the storefront.
- Update order status flow:
  - placed
  - inprocess
  - shipped
  - out_for_delivery
  - delivered

## Local Development

1. Install dependencies:

	npm install

2. Configure environment in `.env.local`:

	MONGODB_URI=<your_mongodb_uri>

3. Run development server:

	npm run dev -- --port 3001

4. Open:

	http://localhost:3001
