---
layout: post
title: Keys to Good Data Science
date: 2016-10-31
excerpt: I’ve been working as a Data Scientist for a few years now, so I’ve decided to share what I think is key to good data science. A lot of the advice is applicable to other areas...
author: Ruby Childs
image: images/blog/data-science.png
---

I’ve been working as a Data Scientist for a few years now, so I’ve decided to share what I think is key to good data science. A lot of the advice is applicable to other areas, so there’s cross over in other roles. Also you may disagree with some of it! Am always happy to discuss it, so drop me an email if you think otherwise. I may even evolve and develop these thoughts as time goes on!

#### 1. Models

Often as a data scientist, we may think, let’s use Model X, this solves our problem. But does it? Often its good to choose a model early on that is simple. We need to provide tangible outcomes early on and you often need to explain a model. For example if you have a deep learning model, can you explain in day-to-day language the outcomes and how the model has been formulated. Deep learning is great (like seriously cool shit), but you can’t just try something shiny for the sake of it! So try the basics first - its amazing how many companies are using simple models.

#### 2. Stakeholders

We must always keep in mind the business value and our stakeholders. Often as a DS you can run away with ideas, and exploration. Here its key to produce outcome. Try and understand the business objectives and enable others to understand the data. Clearly they do not need to know all the ins and outs, but provide a high level overview. Look at an endpoint where maybe you can provide a visualization or similar.

Also ensure you have difficult talks early on, such as outcomes of a project and whether a project is viable. Not everyone has data understanding nor should they, but with all these articles on Big Data and Data Science, everyone seems to want to do it and yes they do want magic. You need to ensure you discuss the process in terms of data landing, prep, explorations, models and so on. But you also need to ensure your project has realistic outcomes that you believe are achievable. You need to convey that it is hard work and will take time. Within previous experiences at a consultancy, I saw a lot of selling and buzzwords. I avoid these as I want to ensure I can provide value and that I do not oversell data science as well as my own skills.

My final piece of advice is business understanding. If your working in a company full-time, you will obtain area expertise, but the bigger the company the more segregated business concerns may be, or equally if you contract then you need to pick up domain knowledge asap. Ensure you set up any discussions and knowledge transfer sessions early. I wish I had done this earlier in my career in full time roles and I have found as a contractor I have got more domain and industry knowledge than I would do if working ft, due to early on meetings. In a FT post

#### 3. Prototyping

It’s key not to jump to big solutions. Instead you can actually prototype data science solutions. For example, rather than working on whole datasets, select and make a few features, not the total number of features you think a project will need.

I’d also recommend feedback early on into a project. When I worked in a startup, I was testing out new data driven product features on a user testing group. If they did’t understand this new data driven feature, we would go back to the whiteboard. It’s key to act lean, prototype and test. This is applicable for many positions, not just those within data. In this particular company I was autofilling profile data in with a sense of DNA, aka favourite hobbies, likes, places and movies. Sounds like an easy concept right? But data produced some rare junk, which caused upset. Hence as a feature, this was dropped, without too much time and resources being spent on it.

#### 4. Data Landing

Data Landing is one of those things where you can really struggle at. You may either be granted data access instantly if in a full time position, or go through a process of trying to get data for weeks, sometimes months. To help the process, try and push for sample data. This will at least let you know if the data relates to the business problem.

I had one company I was working FT in which was a huge company and the data was so scattered around the company in different departments. Everyone protected their data as if they were Golem - ‘My data, my precious data’ (LOTR). Pushing for samples can help with this protectiveness and ownership.

In some cases you’ll have an issue of no data. I have seen companies be able to provide a very small data set (approx 5 rows), expecting magic. Now as you are probably all aware, you can’t really be doing analysis and science on no data. So raise this early on. Some data sets may even require manual tagging - raise this if so. Maybe your trying to do something too early on when the company is in its infancy and it needs to invest more into its data pipeline.

#### 5.Data Preparation

People often underestimate how long data can take to prepare. By prepare we often mean standardise and normalise. You’ll here figures of around 70-80% of a data scientists time is spent on cleaning and that’s about right. You could get lucky that your data is clean (lol, I’d like to see this happen once...)

My advice is to overestimate cleaning time and effort placed in. Start with an initial draft of data and improve it once you’ve completed your first model iteration. You can always make it better! Again only clean the data that you actually need for the handful of features that you want to start initial tests with.

#### 6. Don’t Fear Failure

We are often told failure is bad, and we often treat as such. Realistically failure is great! Embrace it. Every time you fail, you are closer to success.

Every time a model doesn’t work the way you want to it, it should act as an indication of what works and what doesn’t. Learn from this. Again it is likely to lead you to success.

Also time box your work, so that beyond a time and a number of experiments, if it still isn’t providing value you can put it aside. When this happens, you are not wasting time, you have gained skills and understanding of that data.

#### 7. Don’t expect to know everything

As a DS, I’ve often felt pressure to pick up new tools, try new methods and I do. But its important to understand DS is a pretty big field. So as obvious as it may sound do learn from others and use others strengths. Particularly if you work in a team, discuss and assist others. Request time to pair programme to understand newer techniques and software. Equally provide your team with debriefs when you use something new in your project, and get them to show you too.

If your an alone DS, like I often am, I find meet ups most useful. I have now pivoted myself in a position where if I get stuck I can go to community members to request their ideas and assistance. I really can’t emphasise how helpful this is and if your in London, come and join me at PyData as well as Hack&&Tell.

Also regardless of being alone, or in a large team, learn how to learn. People often think they already know this, as we are fed information through news, teaching and peers. But really you can’t be spoon fed, so its important to know sources and people to broaden your ability to learn.
