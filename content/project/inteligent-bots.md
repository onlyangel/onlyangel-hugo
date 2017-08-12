+++
title = "Inteligent Bots"
date = "2017-08-12T10:53:15-05:00"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-learning","deep-learning","social-media","bots"]

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

A few years ago I was asked to create a bot network that can handle around 30,000 bots. We end creating an incredibly complex campaign.

The objective was to target people that talk about an specific subject. Once we found those persons we analise who they follow and how those persons write. Then we train a simple DNN written by me (there doesn't exists Tensor Flow or nothing like that) for every targeted person and the platform started to write random texts that sound similar to that the targeted user are used to see in a series of bots assigned to that individual person. That's how we make them look real.

Eventually from a different neural network we start talking about the subject we target initially trying to write positively or negatively depending in the campaign in such way that the bots could influence the readers that at this moment normaly have a dozen of organic followers that are usually some of the targeted users.

With this methodology we get to have up to 31k bots working at the same time creating their own content, looking real. 

And all this written in PHP and more than 5 years ago. 