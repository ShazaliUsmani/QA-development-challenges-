# QA-development-challenges-
QA DEVELOPMENT CHALLENGES 

1.	 1. General Test Cases:-

1.	Check that user is able to navigate through all the products across different categories.
2.	Check that all the links are redirecting to correct product/category pages and none of the links are broken.
3.	Check that the company logo is clearly visible.
4.	Check that all the text – product, category name, price and product description are clearly visible.
5.	Check that all the images are clearly visible.
6.	Check that category pages have a relevant product listed specifically for the category.
7.	Check that correct count of total products is listed on the category pages
2.	Login Page Test Cases:-
1.	Check that there are proper validations on Login Page.
2.	Check for error message if email, password or any required field is left blank.
3.	Check the validations on Email and password.
4.	When you log in check that you stay logged in as you browse products. Also, you need to test the behavior when the user doesn’t interact with the site for some time. Will the session expire after a period of time? Make sure the user has actually been logged out after the session times out.
5.	when you are logged in, log out and make sure you are logged out and that you cannot access any of the accounts pages

3.	. Registration Page Test Cases:-

1.	Check that all the required fields are present on the registration page.
2.	Check that the required/mandatory fields are marked with * against the field.
3.	Check that for better user interface dropdowns, radio buttons and checkboxes etc fields are displayed wherever possible instead of just text boxes.
4.	Check the page has both submit and cancel/reset buttons at the end.
5.	Check that on clicking submit button after entering all the required fields, the data is submitted to the server.
6.	Check that clicking cancel/reset button after entering all the required fields, cancels the submit request and resets all the fields.
7.	Check that whenever possible validation should take place on the client side.
8.	Check that not filling the mandatory fields and clicking submit button will lead to the validation error.
9.	Check that not filling the optional fields and clicking submit button will still send data to the server without any validation error.
10.	Check the upper limit of the text boxes.
11.	Check validation on the date and email fields (only valid dates and valid email Ids should be allowed.
12.	Check validation on numeric fields by entering alphabets and special characters.
13.	Check that leading and trailing spaces are trimmed.
14.	Check that entering blank spaces on mandatory fields lead to validation error

4.	Search Test Cases:-

1.	Check that the products displayed are related to what was searched for.
2.	Check that the products should display an image, name, price and maybe customer ratings and number of reviews.
3.	Check the more relevant product for the search term are displayed on the top for a particular search term.
4.	Check that all items in next page is different to the previous page, i.e. no duplicates.
5.	Check that when both sort and filter have been applied, they remain as we paginate or more products are loaded
6.	Check that count of products is correctly displayed on the search result page for a particular search term.
7.	Check that filtering functionality correctly filters product based on the filter applied.
8.	Check that filtering works correctly on category pages.
9.	Check that filtering works correctly on the search result page.
10.	Check that correct count of total products is displayed after a filter is applied.
11.	Check that all the sort options work correctly – correctly sort the products based on the sort option chosen.
12.	Check that sorting works correctly on the category pages.
13.	Check that sorting works correctly on the search result page.
14.	Check that sorting works correctly on the pages containing filtered result, after applying filters.
15.	Check that product count remains intact irrespective of sorting option applied
5.	Wish list Page Test Cases:-
1.	Verify that added product is present on the wishlist page.
2.	Check that Update of the wishlist is working correctly.
3.	Check the Share wishlist functionality.
4.	Check that user is able to Add products to Cart from wishlist page.
6.	7. Product Details Page Test Cases:-
1.	Verify Actual product details with expected product details.
2.	Verify Add to cart should work properly.
3.	Check that user is able to add products in the wish list.
4.	Check that complete description of Product including images is shown properly.
5.	Check that option to check the availability of product is present.
6.	Check that user can rate, review the product

7.	Cart Test Cases:-

1.	Check that user is able to add products to cart.
2.	Check that the cart is updated with the correct name, image, and price of the product.
3.	Check that user is able to add same product multiple times.
4.	Check that the price increase accordingly when a product is added multiple times.
5.	Check that user can add multiple products of different types.
6.	Check that For each item added, a corresponding name, image, and price and the total price of all items is shown.
7.	Check that when a product is removed from the cart the cart gets updated and shows the existing items in the cart, total price according to the products left in the cart.
8.	Check that when all the products are removed from cart then cart balance becomes zero, no items should be displayed in the cart.
9.	Check that customer should be able to see more information about the product when clicked on the product either as a popup or redirect to the product page.
10.	When a user adds products to cart and then closes the tab then ideally, the cart should still hold your items or particularly depends on the requirements on how the cart should behave.
11.	Check that the price of the cart is discounted when we apply a coupon and not discounted when we apply an invalid or expired coupon

8.	. Product Buy Flow Test Cases:-

1.	Check that on the product page, a user can select the desired attribute of the product e.g. size, color etc.
2.	Check that user can add to cart one or more products.
3.	Check that user can add products to the wish list.
4.	Check that user can buy products added to cart after signing in to the application (or as per the functionality of the website).
5.	Check that user can successfully buy more than one products that were added to his/her cart.
6.	Check that the limit to the number of products a user can by is working correctly by displaying an error message and preventing the user from buying more than the limit.
7.	Check the availability of products at desired locations.
8.	Check that Cash on Delivery option of payment is working fine.
9.	Verify that the different pre paid methods of payments are working fine.
10.	Check that product return functionality works fine.
11.	Check that Cancel Order option is present.

9.	Payment Page Test Cases:-

1.	Check that  After fill shipping address and payment, the product is purchased successfully.
2.	Check that Different payment types should be present, e.g. Credit Card, PayPal, Bank Transfers, Installments, etc.
3.	Check that security of client’s card details when entered for payment
10.	Seller – Product creation Test Cases:-
1.	Check that authenticated sellers get access to product creation panel specific to the authorized categories.
2.	Check that product creation is working fine for single product creation.
3.	Check that product creation is working fine for multiple product creations.
4.	Check that maximum product creation limit for the seller is working fine, limiting seller to create more than the desired number of products.
5.	Check validation for checking mandatory fields.
6.	Check that duplicate product creation is restricted.
7.	Check that seller can update information and price of existing products.
8.	Check that product created by seller get visible on the website after the certain period of time.
9.	Check that updation made by seller get visible on the website after the certain period of time.

11.	Seller – Product creation Test Cases:-

1.	Check that authenticated sellers get access to product creation panel specific to the authorized categories.
2.	Check that product creation is working fine for single product creation.
3.	Check that product creation is working fine for multiple product creations.
4.	Check that maximum product creation limit for the seller is working fine, limiting seller to create more than the desired number of products.
5.	Check validation for checking mandatory fields.
6.	Check that duplicate product creation is restricted.
7.	Check that seller can update information and price of existing products.
8.	Check that product created by seller get visible on the website after the certain period of time.
9.	Check that updation made by seller get visible on the website after the certain period of time.
12.	12. Post Purchase Test Cases:-
1.	Check that customer is able to Cancel the order or change the quantity of the order.
2.	Check that customer is able to Review recent order and history of purchased items.
3.	Check that customer is able to Change information, such as billing address, shipping address, change password, change profile information such as name, email address and even deleting an account.

