# Postman + newman + github actions (Simple store template)
## [Report](https://andreycar.github.io/Postman-newman-ghActions/)
## Step to run
1. Clone repo `git clone `;
3. Run `npm i` (install node.js dependencies);
4. Run `npm run tern-on-api`(to run testing server locally );
5. Upload store.collection.json in Postman app;
6. Run collection.

### Overview
Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |
