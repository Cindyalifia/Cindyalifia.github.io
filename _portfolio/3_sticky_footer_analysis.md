---
layout: portfolio_post
title: Removing the Mobile Sticky Footer for the "Add to Cart" Button
description: null
image: /assets/images/image10.png
author: null
show_tile: false
background: "
To test the assumption that closing the sticky \"Add to Cart\" button on the landing page of some products in the mobile version will reduce user churn, as some users might be deterred by the price without scrolling to the curriculum or clicking the \"Add to Cart\" button.
"
goal: "
Through the analysis, we can determine if removing the sticky footer for the \"Add to Cart\" button is the best option to reduce user churn on the product page or not.
"
conclussion: "
<ul>
<li>Removing only the price in the sticky footer</li>
<li>Rearranging and redesigning the add to cart button (not removing)</li>
<li>Optimizing the sticky footer</li>
</ul>
"
---
- #### Add to Cart Conversion: view item to add to cart

|           | Visit Landing Page | Add to Cart CTR |
|-----------|--------------------|-----------------|
| Product A | 765,000            | 10.52%          |
| Product B | 362,000            | 5.21%           |
| Product C | 482,000            | 7.98%           |
| Product D | 823,000            | 12.64%          |

Regarding Add to Cart CTR for mobile devices, we know that a lot of users are clicking the add to cart button in the sticky footer. This means, the add to cart button is working properly.

- #### Page Scroll Depth

![-](/assets/images/image10.png)

In terms of scroll depth, most of the user are scrolling only until 25% of the page depth. While only a few users are scrolling up to 75%. After we did some testing, it shows that the **Add to Cart button starts to appear after the user scrolls until roughly 55%**. However, most of the users are scrolling until 25% only. If we remove the add to cart button in the sticky footer, **we might lose a potential user that will convert but not scroll more than 55% of the page depth**.
