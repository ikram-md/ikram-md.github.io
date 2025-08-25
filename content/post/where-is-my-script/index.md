---
title: 🔍 Where is my script?
summary: The ultimate guide to a cleaner data science project structure
date: 2025-07-25
authors:
  - admin
tags:
  - Clean code
  - Data Science
  - Strcuture
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

We have all been there, when you realize that the results you have obtained are quiet wierd and you start to doubt that maybe I did a mistake somwhere in the data processing code. But geuss what, the codebase is large, there are many datasets and different scripts for every dataset and you were in such a rush that you fogot documentation. If this feels familiar, then I got you.

One of the lessons I learned in my previous job as a software developer is that : “strcuture matters” and this doesn’t only apply on software engineering projects consiting of front-end, back-end and devops part. But also in machine learning project, since after all, all the math on the board is translated into code written and reviewed by humans. Before starting any data science or machine learning project one should always think about the structure. Today, one the first things I ask myself before stepping into the model-engineering step (in which you translate the theory you discussed with your colleagues to code) is : *“How can I build this so that it’s dynamic to any dataset or model additions that I could do later” And turns out the time spent attempting to answer is never gone to a waste.*

Whether it’s in a data science job within a company, or a project to be published one day. A good structure is the reason why we can *easily stand on the shoulder of giants* these days; Therefore, In this blogpost, I will be sharing some of my tips on what I think helps towards building a structure that scales with augmentation and project complexities along with modern tools that help tidy up the code and the process of building the blocks.

## Techniques and steps
### Know your enemy

