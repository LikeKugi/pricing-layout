# Design a Pricing Plans Layout Page

Build an app, give it your own personal style.

## Objective: 

Fulfill the user stories below and get all the tests to pass to complete the lab.

## User Stories:

1. Your page should have an h1 element with the text Pricing Plans.
2. Your page should have a div element with the class pricing-container below the h1 element.
   - The .pricing-container selector should have a display property with the value of flex and a flex-wrap property with the value of wrap.
3. Within the .pricing-container element, you should have three div elements with the class pricing-card to represent the pricing plans.
   - One of the .pricing-card elements should have the class basic-plan in addition to the pricing-card class.
   - One of the .pricing-card elements should have the class pro-plan in addition to the pricing-card class.
   - One of the .pricing-card elements should have the class premium-plan in addition to the pricing-card class.
4. Your .basic-plan element should have an h2 element with the text Basic.
5. Your .basic-plan element should have a p element with the text $9/month.
6. Your .pro-plan element should have an h2 element with the text Pro.
7. Your .pro-plan element should have a p element with the text $19/month.
8. Your .premium-plan element should have an h2 element with the text Premium.
9. Your .premium-plan element should have a p element with the text $29/month.
10. Each of your .pricing-card elements should:
    - Use Flexbox to stack its content in a column and justify the space between the children using space-between.
    - Set the flex property to 0 0 200px to give it a consistent width and prevent it from growing or shrinking in the layout.
    - Set the border property to 2px solid black to see how the different cards take up space.
11. The .basic-plan element should appear first in the layout. You should use the order property for this.
12. The .pro-plan element should appear second in the layout. You should use the order property and set its flex-grow property to 2 so it takes up more space than the other plans.
13. The .premium-plan element should come last in the layout. You should use the order property for this.
14. Note: Be sure to link your stylesheet in your HTML and apply your CSS.

## Tests:

Waiting:1. You should have an h1 element.
Waiting:2. Your page should have an h1 element with the text Pricing Plans.
Waiting:3. You should have a div element below the h1 element.
Waiting:4. Your div element should have the class pricing-container.
Waiting:5. You should have a .pricing-container selector.
Waiting:6. Your pricing-container selector should have the property display with a value of flex.
Waiting:7. Your .pricing-container selector should have the property flex-wrap with a value of wrap.
Waiting:8. You should have three div elements with the class pricing-card within the .pricing-container element.
Waiting:9. One of your .pricing-card elements should have the class basic-plan.
Waiting:10. One of your .pricing-card elements should have the class premium-plan.
Waiting:11. One of your .pricing-card elements should have the class pro-plan.
Waiting:12. You should have a .pricing-card selector.
Waiting:13. Your .pricing-card selector should have the property display with a value of flex.
Waiting:14. Your .pricing-card selector should have the property flex-direction with a value of column.
Waiting:15. Your .pricing-card selector should have the property justify-content with a value of space-between.
Waiting:16. Your .pricing-card selector should have the property flex with a value of 0 0 200px.
Waiting:17. Your .pricing-card selector should have the property border with a value of 2px solid black.
Waiting:18. Your .basic-plan selector should have the property order with a value of 0.
Waiting:19. Your .basic-plan element should have an h2 element with the text Basic.
Waiting:20. Your .basic-plan element should have a p element with the text $9/month.
Waiting:21. Your .pro-plan element should have an h2 element with the text Pro.
Waiting:22. Your .pro-plan element should have a p element with the text $19/month.
Waiting:23. Your .pro-plan element should have the property order with a value of 1.
Waiting:24. Your .pro-plan element should have the property flex-grow with a value of 2.
Waiting:25. Your .premium-plan element should have an h2 element with the text Premium.
Waiting:26. Your .premium-plan element should have a p element with the text $29/month.
Waiting:27. Your premium-plan element should be the last element in the layout and have the property order and the value 2.
