---
title: Guide Vaccine
summary: Modelling Covid-19 growth and finding optimial vaccine distribution between countries
tags:
  - Deep Learning
  - Reinforcement Learning
date: '2021-01-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/SarthakHa/VaccineGuidecuHacking'

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart


url_code: 'https://github.com/SarthakHa/VaccineGuidecuHacking'
url_pdf: ''
url_slides: ''
url_video: ''

---

Optimial Vaccine Distribution amongst countries suffering Covid-19 can be a challenging as countries with more cases need more vaccines while those with less cases need less vaccines. We implemented models to model the growth of Covid-19 in country using the SIRD model which is based on continous markov decision processes. Then we implemented a reinforcmenent learning agent that can choose the optimial vaccine distribution policy between countries per day depending on some fixed supply of vaccines to minimize total number of deaths between a chosen set of countries. Our agent is able to learn better policies than naive methods such as distributing vaccines based on the ratio of cases or a countries population, as it is able to understand how the cases in a country will change overtime. We implemented a webapp based on Heryoku and Figma to allow users to select their own scenarios of which countries to consider and train an agent to learn a policy for that. 

This project was implemented in 24 hours and won best use of google cloud for CuHacking. 
