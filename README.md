# example-basket
The purpose of this repository is to write simple code in a multilayer architecture so that I can then practice BDD on it 

# TODO:
1. User can add available product variants to the cart.
2. User can remove a product variant from the cart, as well as change the size and quantity of products variants in the cart
3. User can move product to the wishlist.
4. The shopping cart shows the base and promotional price of each variant
5. When you add products for (at least 50 zł, or 5 other products), you can pick up an additional product from the pool (each promotion may have a different one) of promotional products for 1 zł
6. Cart always shows information about all enabled promotions of this type. If the promotion is still blocked, it is grayed out
7. Only logged-in user can add discount code to the cart
8. Some discount codes are only available if the cart value exceeds the amount specified in the promo code configuration
9. On the cart page, I can see how many promotional points I will gain after paying for my order. The total points are the value of the order in zł (always rounded up)
10. If I am not logged in, the system informs me that I have to be logged in for the points to be credited to my account
11. A third-party service tells us, based on EANs, how long it will take to deliver the order. If the service is currently unavailable, or the delivery will take more than two weeks, we hide this information.
