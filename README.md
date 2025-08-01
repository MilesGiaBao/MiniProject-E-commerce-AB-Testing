# MiniProject-E-commerce-AB-Testing
We used R language coordinate with A/B testing method to check which web page is better than the other.\

A company have been developing a new webpage and trying to increase the number of "changed" customers, which is the number of users decided to pay for company's product. Our target is to research the number of "changed" customers in two webpages (old and new), so that the company can make decisions to use the new webpage or keep the old one.\

The data **ab_test_commerce.csv** has 294,478 users with some features below:
1. *user_id*: The unique id of each user.
2. *timestamp*: The operating time of users for the web.
3. *group*: The group (**control** - old page, **treatment** - new page) each user was put in.
4. *landing_page*: The web which each user was used.
5. *converted*: The change (0 - not buy, 1 - buy).
