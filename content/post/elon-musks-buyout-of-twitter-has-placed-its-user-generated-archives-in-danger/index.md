---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Re-Posted from the Conversation: Elon Musk’s buyout of Twitter has placed its user-generated archives in danger"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2022-11-22T01:36:23-05:00
lastmod: 2022-11-22T01:36:23-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Since its founding in 2006, Twitter has become one of the largest digital datasets of a record of human history. (Shutterstock)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Twitter is in disarray. This is troubling for a platform that comprises no small part of the historical record of today.

While only used by a percentage of Americans ([some 23 per cent in 2022](https://www.pewresearch.org/fact-tank/2022/05/05/10-facts-about-americans-and-twitter/)) and Canadians ([42 per cent of adults in 2018](https://www.cbc.ca/radio/spark/388-pokemon-go-for-ecologists-fake-videos-and-more-1.4569277/how-does-your-social-media-use-stack-up-against-other-canadians-1.4569280)), it has outsized value for sharing information, capturing ongoing events and shaping the cultural conversation.

Twitter’s role cannot be underemphasized. In advance of the 2022 American midterm elections, Twitter realized its pivotal role in shaping electoral information meant that its plan to verify anybody who paid US$8 could “[sow discord](https://www.nytimes.com/2022/11/06/technology/twitter-verification-check-marks.html).”

Similarly, Twitter is where many turned to information during the opening weeks of the [COVID-19 pandemic](https://www.brookings.edu/blog/techtank/2022/01/04/the-vital-role-of-twitter-in-responding-to-covid/) and the [Ukraine war](https://theconversation.com/guns-tanks-and-twitter-how-russia-and-ukraine-are-using-social-media-as-the-war-drags-on-180131).

[![neon sign in red reading #TWEET TWEET, installed on top of green patterned wallpaper](https://images.theconversation.com/files/496486/original/file-20221121-23-er6qlp.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=754&fit=clip)](https://images.theconversation.com/files/496486/original/file-20221121-23-er6qlp.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=1000&fit=clip)

Twitter has become an important site for information (and disinformation). (Unsplash/Chris J. Davis)

The end of Twitter?
-------------------

Amidst predictions [of bankruptcy](https://www.npr.org/2022/11/12/1136205315/musk-twitter-bankruptcy-how-likely) or even wholesale [technical collapse](https://www.technologyreview.com/2022/11/08/1062886/heres-how-a-twitter-engineer-says-it-will-break-in-the-coming-weeks/), the cultural record of all of these critical moments are [now endangered](https://www.technologyreview.com/2022/11/11/1063162/twitters-imminent-collapse-could-wipe-out-vast-records-of-recent-human-history/).

This is terrible because the [information that our society creates today is tomorrow’s historical record](https://theconversation.com/historians-archival-research-looks-quite-different-in-the-digital-age-121096). For better or worse, Twitter has been with us throughout the last decade and a half: [election cycles](https://help.twitter.com/en/using-twitter/us-elections), the COVID-19 pandemic (where it has been an exemplar platform for [misinformation](https://doi.org/10.1038/s41598-020-73510-5) and [information](https://doi.org/10.1038/s41598-021-98396-9) alike), and online culture more generally (some tweets have even [become TV shows](https://www.imdb.com/title/tt1612578/)).

Future historians may be able to learn about these things through media coverage of Twitter, but the ability to access the tweets themselves will be invaluable for historical research. This is doubly true for the spread of information during breaking events, when the platform itself became the main primary source for observers and participants.

Given the centrality of this source, it is hard to believe that it could all disappear. Could it?

Unique vulnerability
--------------------

Twitter archives take several shapes and sizes. For a time, the most famous one was the Library of Congress’s Twitter archive. In 2010, the Library of Congress announced that it would both receive all the text of tweets dating back to 2006 and acquire them going forward.

[Then in December 2017](https://blogs.loc.gov/loc/2017/12/update-on-the-twitter-archive-at-the-library-of-congress-2/), the Library of Congress moved from a collect _everything_ approach to a “selective basis,” curating rather [than taking everything](https://www.nytimes.com/2017/12/27/technology/library-congress-tweets.html).

The Internet Archive, a digital library based in the United States, also collects many Twitter streams, both through its [Wayback Machine](https://archive.org/web/) and its subscription service [Archive-It](https://archive-it.org), where members can choose and curate the accounts that they collect.

Users can go back and look at the suspended (and since reinstated) [@realDonaldTrump account](https://web.archive.org/web/20161109000022/https://twitter.com/realDonaldTrump), for example. These web archives, however, are targeted: one needs to know the username or particular hashtag that one wants to study.

The Internet Archive’s holdings are not at risk, but they are very hard to search and slow to use. To truly unlock the power of Twitter research, more access is required.

At-risk datasets
----------------

Fortunately — for now — there is a better way: the [Twitter Application Programming Interface](https://help.twitter.com/en/rules-and-policies/twitter-api) (API). APIs are ways for computer programs to speak to each other. The [Twitter API for Academic Research](https://developer.twitter.com/en/products/twitter-api/academic-research) program allowed researchers to apply for accounts and then design or use programs to create their own collections of both real-time or historical data.

The [DocNow Catalog](https://catalog.docnow.io), has a subset of these Twitter collections, and currently has some 142 datasets consisting of over six _billion_ tweets, on topics ranging from [#BlackLivesMatter](https://catalog.docnow.io/datasets/20201020-twitter-corpus-of-the-blacklivesmatter-movement-and-counter-protests-2013-to-2020/) (41 million tweets) to the [2018 American Congressional Election](https://catalog.docnow.io/datasets/20190222-2018-us-congressional-election/) (171 million tweets).

However, to use the API, one needs to agree to the [terms of service](https://developer.twitter.com/en/developer-terms/agreement-and-policy). Each tweet has its own unique number. This means that these datasets do not contain the data, rather they just contain the numbers that are required to _get_ the data. In other words, think of it as a library where you could only share the call numbers with other patrons, not the books themselves.

When the API is functional, this makes sense. Every time a search request is made, a dataset is generated. This means that the same search conducted at different moments in time would produce a different dataset. If somebody had deleted their tweet in the meantime, it would not be available for download.

For example, if in 2020 I had tweeted something which was recorded by a researcher but in 2021 decided to delete it, if the dataset was requested in 2022, my tweet would no longer be there.

But if Twitter disappears — or if the API collapses — this data could suddenly become lost. If Twitter was to completely disappear, perhaps scholars could share their original, full datasets. But some of this data may have already been deleted, perhaps due to researchers running out of storage space or facing other institutional or ethical requirements.

We truly are facing the prospect of widespread erasure.

An incalculable loss
--------------------

The loss of Twitter’s 16 years of user-generated content would be a tragedy.

Digital platforms like Twitter are the public town squares of today, unlike more private social media platforms like Facebook. We all have a stake in ensuring its material is preserved: governments, archivists, librarians, historians, activists, among other institutional and private stakeholders.

Without the Twitter archive, we risk losing important voices from the past. Many of us have experienced elections, protest and the pandemic through [280-character tweets](https://techcrunch.com/2018/10/30/twitters-doubling-of-character-count-from-140-to-280-had-little-impact-on-length-of-tweets/). Without these voices, we lose the unique flavour of the tumultuous times we have lived through.

And the next time a platform comes along, it is important for developers to consider how to archive its content for future consideration.

In the meantime, we can [download our own Twitter archives](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive). [Several instructional guides have appeared](https://www.theverge.com/23453703/twitter-archive-download-how-to-tweets) [walking users through the process](https://www.cnet.com/tech/services-and-software/dont-delete-twitter-before-you-download-all-your-tweets-and-messages/) of [downloading this data and making it usable](https://mashable.com/article/how-to-leave-twitter-guide-elon-musk).

While lacking the preservation power of the Library of Congress, perhaps these digital scrapbooks will one day remind us of the Twitter that was.

[![](https://images.theconversation.com/files/479539/original/file-20220817-20-g5jxhm.png?ixlib=rb-1.1.0&q=45&auto=format&w=754&h=144&fit=crop&dpr=1)](https://theconversation.com/topics/social-media-and-society-125586)![The Conversation](https://counter.theconversation.com/content/194596/count.gif?distributor=republish-lightbox-basic)

[Ian Milligan](https://theconversation.com/profiles/ian-milligan-789716), Professor of History, _[University of Waterloo](https://theconversation.com/institutions/university-of-waterloo-1284)_

This article is republished from [The Conversation](https://theconversation.com) under a Creative Commons license. Read the [original article](https://theconversation.com/elon-musks-buyout-of-twitter-has-placed-its-user-generated-archives-in-danger-194596).