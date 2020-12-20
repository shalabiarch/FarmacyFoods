# Requirements Analysis
Requirements are provided by customer [Farmayc Food](https://github.com/shalabiarch/FarmacyFoods/FarmacyFoodSpecs.pdf). Looking at the provided requirements we can find it consists of the following parts:
- Integration with smart storage devices (Smartfridge).
- Integration with point of sales.
- Central kitchen.
- e-commerce Web application which provides feedback, recommendations, coupons and promotional pricing, and etc.
- Food items.

## Key to business success
There are important aspects about this business which is not mentioned in the requirements, but are key to this business success and solution architecture.
- Central kitchens are independent from each other. This means if a center kitchen went down, this will have no effect on other center kitchens. for example in there is a power down on Boston city for some reason, this will effect only fridges on Boston city but will have no effect at all to fridges on LA.

- This is food industry, it is important to track food expiration and other food characteristics. This means that center kitchen need to provide a sort of alarming system which track these food characteristics. 

- Central kitchen need to be smart by knowing which foods every fridge should have.


