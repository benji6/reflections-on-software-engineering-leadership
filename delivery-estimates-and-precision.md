# Delivery estimates and precision

Consider estimating the delivery time of a complicated software engineering project. If you were to plot a graph of delivery likelihood on the y axis against time on the x axis you would typically not get a symmetrical [Gaussian distribution](https://en.wikipedia.org/wiki/Normal_distribution). Typically you would see an asymmetrical curve with a long tail stretching off to the future ([positive skew](https://en.wikipedia.org/wiki/Skewness)).

If you to commit to a delivery time that lies in the middle of that distribution then 50% of the time you will either deliver on time or a bit before scheduled and 50% of the time you will deliver on time or potentially quite a long way after scheduled. This is undesirable as we may appear unreliable and ineffective.

If we are constrained to providing a delivery time under so much uncertainty it makes sense to pad it as much as possible (without seeming overly pessimistic or ineffective) such that most of the time we will complete the project on time or before schedule.

Now consider [Parkinson's law](parkinsons-law.md). Given the delivery time now seems to have so much padding how aggressively is the team going to push and prioritize delivery of this project? We've just changed the shape of the delivery time probability curve by pushing it out slightly.

In this way, I find it quite likely that increased delivery time precision leads to longer delivery times.
