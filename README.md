# BookNest Full Working Demo

## Run as a static website
Open `index.html` in a browser. Cart, wishlist and seller listing work in browser storage.

## Run as a full local application
Requires Node.js 18+.

```bash
npm install
npm start
```

Open `http://localhost:3000`

## Test data
- Buyer: `buyer@booknest.test`
- Seller: `seller@booknest.test`
- 12 seeded books
- 2 seeded orders
- 5 categories and multiple sellers

## API
```text
GET  /api/books
GET  /api/books/:id
POST /api/books
POST /api/orders
GET  /api/orders?userId=1
GET  /api/users
GET  /api/stats
```

Example:
```bash
curl http://localhost:3000/api/books
curl http://localhost:3000/api/stats
```

This is an educational/demo application. For production, add real authentication, a database, payment gateway, secure image uploads, validation, rate limiting, HTTPS and proper authorization.
