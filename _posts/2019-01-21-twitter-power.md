---
title: 'Using Twitter data to correlate power grid malfunctions'
date: 2019-01-21
permalink: /posts/2019/01/twitter-power/
tags:
  - Blackout
  - Research Methods
  - Social Media
  - Twitter
---

There's an increasing excitement about using new technologies - like social media and 'big data' - in research about disasters and emergencies. There are a large number of possible ways of approaching this question, though, so developing these methods first requires 'pilot' attempts at testing whether they actually work. In this post, I'll explore an article - "[Embracing Human Noise as a Resilience Indicator: Twitter as Power Grid Correlate](https://www.tandfonline.com/doi/abs/10.1080/23789689.2017.1328920)" - that attempts a proof-of-concept for one way of applying these tweets.

The article takes on three very different tasks, each of which feels a little disconnected from the previous. They (1) explore the contrasting definitions of resilience, (2) investigate Tweets as a way of measuring impact on a community, and (3) reflect on challenges with using Twitter data for this purpose. I'll discuss each of these in sequence:

The first thing the authors set out to do is to define what resilience means. As they rightfully point out, there's little agreement on what resilience means - "let alone how to measure it" (p. 2). They do a good job of identifying and contrasting different approaches to resilience, such as physical measures (what is lost and how quickly is normal functionality regained) and sociological measures (e.g., how much capacity does a community have to come together). Within each category, they explore different subtypes of resilience, such as technical, organizational, social, and economic manifestations of what it means to be resilient.

The link to the second topic, social media, is a little bit confusing. The end goal is very clear: If you can identify people tweeting about a power outage, for instance, you can put together a good picture of who is being affected without even having a map of the portions of the grid that are down. This is useful in real time (e.g., perhaps you could detect who is suffering from an outage as quick or quicker than conventional assessments) and in retrospect (e.g., if you wanted to forensically recreate a crisis, perhaps you could use the tweets as a way of mapping impact over time). The method is straightforward (download tweets, look for certain terms, and compare frequency of tweets to the size of the outage). It could be expanded in future applications by adding geotagging (e.g., tracing where individual tweets were sent from), but provides a ready proof of concept that the method can work.

The final topic is perhaps the most valuable. In it, the authors reflect on six 'barriers' that face this kind of research and application:

* Privatized data, such as the fact that often energy grid failures are not available with sufficient detail or accessibility for the public or researchers.
* Incompatible scales, meaning that it can hard to square the level of resilience (e.g., thinking about a community) with the level of data (e.g., perhaps only by zip code) with the level of impact (e.g., a single transmission tower being down).
* Incompatible data standards, meaning that it's difficult to translate the various forms of data (again, such as power grid failures) into usable, cleaned data for analysis.
* Privacy and terms of service, meaning that some features (like geo-location) are only available for a small subset of tweets.
* The inadequacy of current statistical measures, especially with respect to dealing with 'big data' like hundreds of thousands of tweets, where it's simply impossible to analyze things manually.
* Polyvocality, which is a term that the authors use to refer to the many different voices within a community, and the fact that not all of them have equal access to technology (e.g., certain demographics might not be represented at all on Twitter, or picked up by your algorithms).

What's the utility of this article for practitioners? The method itself that the authors have developed is a very early stage proof of concept, meaning that it's not likely to be immediately usable by emergency managers. But, it does raise interesting opportunities to develop similar approaches to help answer questions practitioners might have (e.g., how might we use tweets to measure preparedness or track wildfire spread?). And, the six barriers the authors identify at the end are crucial: as practitioners, how can we work to fight against these barriers (for instance, by making our data more easily available in more standardized ways) and think about their implications for our own work (for instance, whose voices are missing in our current assessments of risk and preparedness)?
