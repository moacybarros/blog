---
toc: true
layout: post
description: An continuous integration proposal for SDC Foundation team.
categories: [markdown]
title: An continuous integration proposal for SDC Foundation team
---
# SDC CI pipeline

## TODO
- [ ] Exercise Github Actions and Heroku for Lametric app. 
    + [ ] [Creating CI/CD Pipeline using GitHub Actions for Python Project (Heroku Deployment Example)](https://www.youtube.com/watch?v=WTofttoD2xg)
- [ ] Improve metrics collection notebooks
    + [ ] Save only on Snowflake
    + [ ] Restore PostgreSQL instance on SDC Sandbox
        * [ ] Terraform for creating RDS PostgreSQL
    + [ ] [Jupyter Notebook (Tips, Tricks and Hacks)](https://www.youtube.com/playlist?list=PLyb_C2HpOQSDhIfHn6LZkCICnx5numsRE)
- [ ] Create github workflow for data-engineer project
- [ ] [Building a Map of Your Python Project Using Graph Technology — Visualize Your Code](https://towardsdatascience.com/building-a-map-of-your-python-project-using-graph-technology-visualize-your-code-6764e81f3500)
- [ ] [manage-heroku-infrastructure-with-terraform](https://medium.com/rackbrains/manage-heroku-infrastructure-with-terraform-4a167b850300)



## Ref:


## Components
- Github Actions
	+ on: [push, pull_request]
	+ build
	+ run unit tests
- DockerFile with test environment
- 