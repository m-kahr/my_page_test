---
title: 'Determining optimal locations for electric car-sharing stations under stochastic demand'

event: '8th International Network Optimization Conference 2017, Lisbon, Portugal, Feb 26-28, 2017'
event_url: http://inoc2017.fc.ul.pt/

location: Universidade de Lisboa, Lisbon, Portugal
  #street: 450 Serra Mall
  #city: Espoo
  #region: CA
  #postcode: '94305'
#  country: Online

summary: Conference talk.
abstract: 'The expected growth of the human population by two to four billion in the first half of the 21st century will impose severe challenges to humanity. Some of them are intensified by the increasing trend towards urbanization, especially in developing countries. Two main sources of such challenges are the expected large increases in demand for energy and transportation. Without significant changes in the mode of transportation and type of fuel used, these may lead to shortages of fossil fuels, which are still the dominating source of energy and are estimated to be exhausted before 2050. In addition, severely amplified problems with respect to pollution, congestion, noise and lack of parking space are expected.
These challenges might be partly met by the consideration and implementation of new concepts of transportation such as car-sharing systems that use electric-powered vehicles (EVs), i.e., electric car-sharing systems. Such systems can reduce the number of circulating cars, as well as the total distance traveled by them and are therefore likely to reduce congestion-related delays and to free up parking space. Moreover, they offer the possibility to overcome the rapid exhaustion of fossil fuels and therefore to inhibit the emissions of greenhouse gases, premised that the electric power comes from clean energy sources. The fact that the market-share of EVs was extremely low (0.1%) compared to the number of all passenger vehicles worldwide in 2015 underlines their potential. However, a major disadvantage of EVs is the comparably large amount of time needed for recharging them, and the lack of (private) charging stations in urban areas, which retards the growth of privately held EVs notably. 
Therefore, a successful implementation of electric car-sharing systems may help overcome the aforementioned environmental challenges as they combine the advantages of car-sharing and electric vehicles. 
Operators or cities supporting electric car-sharing systems must, however, address difficult strategic questions before possibly opening their business. Besides selecting an appropriate mode and area of operation, these particularly include the question of where to build charging stations at which cars can be recharged while not used by customers. Additional aspects that shall be considered include the number of purchased cars and their (initial) distribution over the operational area in order to best meet customer demands. 


We introduce the stochastic charging station location problem (SCSLP), which is a new combinatorial optimization problem targeting the strategic planning process of electric car-sharing systems, in order to appropriately support decision makers. Given a stochastic demand forecast, its aim is to identify optimal locations for charging stations out of a given set of potential locations, and an associated number of required EVs in order maximize the expected profit in a predetermined planning period. Thereby we focus on a station-based, one-way mode of operation including the possibility of round-trips and assume that no pre-booking of the vehicles is required, i.e., we refer to ad-hoc systems.
Thereby, we model the SCSLP as a time-dependent two-stage stochastic integer linear program. Since the model`s complexity increases rapidly with the number of considered vehicles, we use a heuristic algorithm for determining a reasonable upper bound on that parameter. The heuristic is also used to generate initial solutions for warm starting a black-box solver and as a stand-alone method to solve very large scale problem instances in reasonable time. 


We provide a computational study on the performance of the algorithms on real world instances from the city of Vienna, as well as on artificial grid-graph-based instances. We analyze the influence of different parameters (e.g., available budget) on the overall performance. Results show that the developed exact approach is suitable for medium sized instances such as the ones obtained from the inner districts of Vienna but, however, fails to solve large instances like those obtained from the dataset of the whole city. In addition the results also show that the heuristic can be used to tackle very large scale instances that cannot be approached successfully by the integer-programming-based method.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2017-02-02'
#date_end: '2022-07-04T12:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# social media share buttons
share: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: ''
#url_pdf: ''
#url_slides: ''
#url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---

