# Stencil-Test
Stencil Test for oBundle Interview Project

### Demo Links
- URL: https://stencil-test4.mybigcommerce.com/special-items/
- Preview Code: twqdu1cwzf

### Brief Description
The primary goal of this project was to familiarize myself with the BigCommerce Stencil CLI and template customization via Handlebars. The most challenging aspect of this project was getting the API endpoints to work properly and proxying API calls so I could utilize them safely on the client-side. I was able to build out all of the functionality listed in the tasks below, along with the bonus task of showing customer details in a banner at the top of the page. 

### Task
1. Create a product called Special Item which will be assigned to a new category called Special Items. Be sure to add at least 2 images during the product creation
2. Create a custom template for the Special Items category page (you may need to restart the CLI to see the custom template after creating it). 
3. The Special Item should be the only item which shows in this category - create a feature that will show the product's second image when it is hovered on. 
4. Add a button at the top of the category page labeled Add All To Cart. When clicked, the product will be added to the cart. Notify the user that the product has been added. 
5. If the cart has an item in it - show a button next to the Add All To Cart button which says Remove All Items. When clicked it should clear the cart and notify the user.
6. Both buttons should utilize the Storefront API for completion.

Bonus: If a customer is logged in - at the top of the category page show a banner that shows some customer details. This should utilize the data that is rendered via Handlebars on the Customer object.
