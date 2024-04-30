# Restocking-ShoppingCart
This is a shopping cart excersise, in which we can restock the cart items by connecting Strapi DB
Using Strapi we can create the API with the data we want in JSON format.
When the user click on Restock button, it hit on that API endpoint and access the data from server side.
# How to Run
In this excersise react used in client side and Strapi used in server side.
For running react, needs all necessory links - react, react DOM, babel and npm 
For creating Strapi make sure we installed Node version greater than 18 </br>
 `npx create-strapi-app <appname> --quickstart`
 To understand and learn more about Strapi please go through the following link
 https://docs.strapi.io/dev-docs/intro
# Roadmap
The shopping cart add divided into three part
- **Product List** : Here we can view the products and it's price. Each product has a submit button after clicking this button that corresponding product moves to Cart content and Checkout box with it's price
- **Cart Content** : This has accordion feature added,so by clicking each product accordion body will display where the price and country of origin of that product also shows. If you click on the accordion body the product removes from that cart and from Checkout list as well
- **Checkout** : In Checkout shows the added products and the sum of it's prices
# License
MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
