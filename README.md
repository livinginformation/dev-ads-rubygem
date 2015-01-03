dev-ads-rubygem (placeholder until a better name is found)
===============

Accept Bitcoin from users to remove ads.


Project overview:
===============
Advertisements are a "necessary evil", and are currently necessary as a source of website revenue. Developers dislike how ads affect site aesthetics, and users dislike the impact they have on the user experience. A single user on a website generates pennies for their browsing, and despite this low cost, no micropayment channel exists that would allow users to pay those pennies, in return for temporary removal of ads. This project seeks to create an alternative website revenue stream, in which users pay in bitcoin for the privilege of ad-free site browsing.


Implementation goals:
================
 - Simple content container
 - Service agnostic, no dependency on any ad platforms
 - Add an overlay to the wrapped content, clicking replaces(?) the ad with a QR code/Bitcoin address and blurb
 - Use an HD wallet to generate a custom payment address per-user
 

Future milestones:
=================
 - Allow website operators to use a payment processor (Bitpay) to aggregate micropayments, and cash out to a bank account once a threshhold is reached.
