# online-store-project
This project is originally for an internship acceptance test (still awaiting result) where a server code was provided (original server code: https://github.com/scandiweb/junior-react-endpoint)

I built the entire frontend of the web app and improved the server by adding the ability to make orders, update order statuses and store products and orders data on a MongoDB database instead of locally on the server.

## Tech stack used: 
- Create React App, Apollo Client, Nodejs, Apollo Server, and MongoDB.
## Code:
- Frontend code: https://github.com/mohagras903/online-store-client.git
- Backend code: https://github.com/mohagras903/online-store-api.git

## Live URL:
https://online-store-client.vercel.app
## Features
- Home page:
  - filtering products based on category
<img width="1436" alt="Screen Shot 2022-09-12 at 12 34 43 PM" src="https://user-images.githubusercontent.com/64911020/189634198-5be3a076-4325-4295-adf7-76cc695bd68f.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 12 45 29 PM" src="https://user-images.githubusercontent.com/64911020/189634906-298f91da-84dd-4af4-8117-b592754c75b3.png">

  - Changing currency which updates all prices right away (last currency selected by user is is persistent everytime the user opens the store)
  <img width="1436" alt="Screen Shot 2022-09-12 at 12 48 00 PM" src="https://user-images.githubusercontent.com/64911020/189635400-ef53adc6-bdff-4428-818b-0f0579a68693.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 12 48 51 PM" src="https://user-images.githubusercontent.com/64911020/189635509-755d9c1d-cbb4-4f2d-b8ea-7ae6eba472ad.png">

  - Quick add to cart with the ability to select product attributes 
 <img width="1436" alt="Screen Shot 2022-09-12 at 12 50 20 PM" src="https://user-images.githubusercontent.com/64911020/189635733-fe7548b1-c2aa-49ec-9f66-61ddef965c5d.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 12 50 41 PM" src="https://user-images.githubusercontent.com/64911020/189635795-e617fe43-c2c0-4e9d-9ea9-df5c044ff2f9.png">

  - Mini cart in the header, viewing all products in cart with selected attributes, providing the ability to increase quantity

<img width="1436" alt="Screen Shot 2022-09-12 at 12 51 58 PM" src="https://user-images.githubusercontent.com/64911020/189636102-378eb91e-391e-42f4-81cc-60276e9c358f.png">


- Product details page:
  - Product gallery, name, brand, description, attributes with add to cart button.
<img width="1436" alt="Screen Shot 2022-09-12 at 12 57 03 PM" src="https://user-images.githubusercontent.com/64911020/189636879-204572e9-ea3c-41ac-b568-e3369af34ca7.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 12 58 00 PM" src="https://user-images.githubusercontent.com/64911020/189637038-462c2b3f-4e48-46cf-b47b-d070c0163ae8.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 12 59 32 PM" src="https://user-images.githubusercontent.com/64911020/189637312-ed19a613-239a-454c-b91c-fce0fed500b4.png">
  - When adding more than one of the same product with the same attributes, they stack in the cart. However, when added with different attributes, they're added as seperate products
<img width="1436" alt="Screen Shot 2022-09-12 at 1 01 47 PM" src="https://user-images.githubusercontent.com/64911020/189637733-7b3eb016-5576-4628-9ac9-a8be7d31b614.png">
- Cart Page:
   - Cart page is just like the mini cart but on a greater scale, with the ability to view all the images of the products not only the first.
 <img width="1436" alt="Screen Shot 2022-09-12 at 1 05 44 PM" src="https://user-images.githubusercontent.com/64911020/189638386-788d8bb5-a996-4455-8096-667c30f9e473.png">
<img width="1436" alt="Screen Shot 2022-09-12 at 1 07 32 PM" src="https://user-images.githubusercontent.com/64911020/189638693-37d05fd2-6de1-492a-b6a6-23c616a8ac25.png">

- Checkout page:
  - Checkout page allows user to order the wished items by filling the simple form.
<img width="1436" alt="Screen Shot 2022-09-12 at 1 09 45 PM" src="https://user-images.githubusercontent.com/64911020/189639157-bc99288d-2cef-4c08-85d0-542d38e7a556.png">

- Admin panel: 
   - Admins have to log in first with their credentials
   - to log to view the admin panel use the following credentials: 
   - email: mohamed.hagras2002@gmail.com
   - pass: onlinestoreadminpanel
<img width="1436" alt="Screen Shot 2022-09-12 at 1 27 56 PM" src="https://user-images.githubusercontent.com/64911020/189642338-6454c521-b363-4d82-aa2b-069e655e083f.png">
    
   - if login is successful, admin can view the orders and their status and update their status, which automatically sends an email to the user.
 <img width="1436" alt="Screen Shot 2022-09-12 at 1 29 36 PM" src="https://user-images.githubusercontent.com/64911020/189642600-1d81f6f5-81e6-40dc-9e54-dc3c6aa2d6c4.png">
 
<img width="1436" alt="Screen Shot 2022-09-12 at 1 30 46 PM" src="https://user-images.githubusercontent.com/64911020/189642791-510ef3b4-200d-4781-ac77-7d18e9f5e355.png">
