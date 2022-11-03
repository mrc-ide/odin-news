---
title: "New JavaScript Support"
date: 2022-10-24
version: 1.4.0
---

We have overhauled (entirely) the JavaScript support in odin, replacing an earlier attempt at this. The new approach uses our new TypeScript packages for working with ODE ([`odin-js`](https://mrc-ide.github.io/odin-js/)) and discrete-time ([`dust-js`](https://mrc-ide.github.io/dust-js/)) models, and power our new web interface to odin ([see the wodin blog](https://reside-ic.github.io/wodin-news/about/) for more information on this).

Over the coming months, we plan to port some of the core sequential Monte Carlo algorithms (particle filtering and particle MCMC) to `dust-js` and enable use of these models on the web. We will also create some tutorials to get going with the models.
