# Drizzle paywall
Drizzle paywall is simple scalable and most user-friendly paywall, subscription and membership product. It's built using React, JS, Meteor, Node, MongoDB. It's compatible with any web technology and stack. Implemented natively, not via external JS file. It takes about 30 min to set up and deploy product, and only 5 min to install it on any type of website. If you are on Wordpress or Drupal, you are in luck, contact Kelly (kelly@getdrizzle.com) and we can provide WP plugin or Drupal module to make installation even smoother (via API key). This product is built mainly by @klyburke, @delgermurun and me with contributions from @lnmunhoz. 

#### Live example: https://coachesonly.breakingmuscle.com/business-development/how-to-stay-ahead-of-changes-in-personal-training

License: General Public License v3.0. We also offer commercial license in case you don't want to publish and distribute your content. Product under commercial license includes extra features, which are needed for particular types of online publishers, for example metered paywall.

# It's built for:
- any size online publisher with premium online content who believes that advertising revenue should be supplemented with direct revenue;
- any startup which sells premium content or digital product (example, videos) or premium features;
- any website owner who has premium, valuable, unique content and wants to sell it via membership and subscriptions.

# Why this product exists?
If you know why this product exists, go read about how you can get more paying users by using this product: https://medium.com/@getdrizzle/how-to-get-more-subscribers-with-a-user-friendly-paywall-part-i-83887372547d#.y1ifi09us

If you are not sure why this product exists, read:
- Why Medium ditched ad-based business model and launches subscriptions: https://medium.com/@getdrizzle/subscriptions-on-medium-f23de6677464#.92s0vj4xa

- Why online ad revenue is declining: https://medium.com/@getdrizzle/big-shifts-in-online-content-monetization-bdebd920bf4b#.oyjvxcqif

- Why it is so hard for ad-supported business to pivot: 
https://medium.com/@getdrizzle/challenges-for-content-monetization-7a1b813ba19d#.wr3ousv2o

# Features
### Open-source license (this repo)
- User-frienly paywall. Login in 2 clicks, pay in 2 more clicks. Screenshots: https://medium.com/@getdrizzle/how-to-get-more-subscribers-with-a-user-friendly-paywall-part-i-83887372547d#.g0sx8k3km
- Paywalled data is hidden via server-side method, not client-side.
- Paywall is server-side rendered.
- Mobile-optimized paywall.
- Content performance. Detailed analytics for every web page with paywalled content:
![screen shot 2017-03-18 at 11 39 01 am](https://cloud.githubusercontent.com/assets/10218864/24074929/93ad21de-0bcf-11e7-98a8-c9e01b9ccd98.png)
- Membership. Detailed analytics for every user, user are segmented into groups, similar sales funnel:
![screen shot 2017-03-18 at 11 40 12 am](https://cloud.githubusercontent.com/assets/10218864/24074944/af9c9348-0bcf-11e7-8969-c59ac1a39b3d.png)
- Payments and Payouts analytics.
- One-click refunds.
- Stripe integration.
- Customizable UI.
- Social proof.
- Curated lists: Newest, Popular lists.
- Footer bar and in-site links.
- Mailgun and Mailchimp integration.
- Welcome email and email notifications.
- Set up single payments.
- Set up subscriptions.
- Set up Free Trial for subscriptions.
- Ability to create single sign-on system accross multiple websites.
- Set up on Wordpress or Drupal site via plugin or module (via API key).

### Commercial license
- Paywall videos
- Metered paywall
- Lead generation (ask for verified email instead of payment)
- Daily pass
- Curated lists: Trending, Similar.
- Referral feature
- Discount code for subscriptions
- Annual and Weekly subscriptions
- Section-specific subscriptions
- Export users data

# Setup of Publishers app (./publishers)



# Setup of Users apps (./users/..)



# Setup of paywall on local website (./users/publisher)


# Deploy
You will need to deploy 2 apps: Publishers app ( ./publishers) and Widget app (./users/widget). There is a detailed description for deployment of Meteor apps with mupx tool: https://github.com/tima101/meteor-deploy-letsencrypt

# Future and Contributions
This section will need more work. The next 3 steps for open-source project:
- Improve UI and UX on Publishers app (./publishers).
- Meteor 1.5 to reduce initial bundle size for Widget app (./users/widget).
- Add Apple pay for easier payments on Mobile.


