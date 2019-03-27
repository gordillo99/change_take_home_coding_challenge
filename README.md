Change.org Take-Home Coding Exercise
=================================

This is a take-home coding exercise used to help evaluate and work
with candidates looking to join the team at Change.org. The general idea
is for candidates to complete the challenge before the
engineering interview. During the interview we will use the code as a
discussion point.

### What we are looking for?

You can submit the code by providing a pointer to a source control repository. In your submission, you should include:
 - The code (include all relevant files).
 - A small __README__ documenting any assumptions or simplifications you have made, and a link to the __working website__.

Snacky Snacks Online Shop
--------------------
Snacky Snacks has hired you to develop their payment processing web page. They believe an online store will be the best way
to buy snacks by weight.

### Price List (per Kg) and in $USD
| Snack          | Cost per Kg  |
| ---------------|--------------|
| Chocolate      | $5.60        |
| Dark Chocolate | $6.00        |
| Bubble Gum     | $2.00        |
| Cotton Candy   | $1.50        |

### Requirements
The following features **must** be part of your final submission.
  1. The user must be able to pick the type and weight of the snack.
  1. Payments must be processed using Stripe.
  1. The user must be able to clearly see any errors that occur while submitting the payment.
  1. Aim for the best possible user experience (clear user interface, minimal number of clicks, fast loading, etc).
  
### Nice to Haves
The following features are **not** mandatory, but they will add bonus points.
  1. Live validation of credit card field see https://stripe.com/docs/stripe-js/v2#card-validation-helpers for more information.
  1. Let the user charged by the payment processor using multiple currencies; the cost of each snack stays equivalent for all      currencies.
  1. Make the website responsive.

### Above and Beyond
The following features are **not** mandatory and more challenging. However, these are not expected to be implemented by most candidates.
  1. Allow users to sign up for monthly snack plans; the users should automatically be charegd monthly by the payment     processor. 
  1. Implement anti-fraud measures (we'll let you come up with what these can be).
  1. Add unit tests for your code.
  1. Ability to process Google Pay, Microsoft Pay, and Apple Pay using the Stripe Payment Request Button https://stripe.com/docs/stripe-js/elements/payment-request-button
  1. Ability to process payments using Braintree https://developers.braintreepayments.com/start/overview
  
Glossary
--------
1. Payment Processor
  A payment processor is a company appointed by a merchant to handle transactions from various channels such as credit cards.   Examples: Stripe, Braintree

2. Stripe

3. Braintree


F.A.Q.
------

1. Is it OK to share your solutions publicly?

   You do the work, you own the code. Given we are asking you to give up your
   time, it is entirely reasonable for you to keep and use your solution as you
   see fit.

2. Should I do X?

   For any value of `X`, it is up to you, we intentionally leave the problems a
   little open-ended and will leave it up to you to provide us with what you
   see as important.

3. Something is ambiguous, and I don't know what to do?

   The first thing is: don't get stuck. We really don't want to trip you
   up unintentionally, we are just attempting to see how you approach
   problems. That said, there are intentional ambiguities in the
   specification, partly to see how you fill in those gaps.

   If you really feel stuck, our first preference is for you to make a
   decision and document it with your submission - in this case there is
   really no wrong answer. If you feel it is not possible to do this,
   just send us an email and we will try to clarify or correct the
   question for you.
