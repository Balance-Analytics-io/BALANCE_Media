---
title: Cardano Foundation Grant Work Report
description: A work report covering the progress and accomplishments the BALNC Pool Cardano Foundation Delegation Grant
slug: work-report-cardano-foundation-grant-01-2023-03-30
published: 2023-3-30
category: Work Reports
series: false
---

# Cardano Foundation Grant Work Report

**Highlights**
- New Website and Fast, Crisp Charts
- New Email Newsletter Subscription and Website Articles
- Work completed, design ethos and decisions
- Roadmap and look-ahead

## Table of Contents

The Cardano Foundation (CF) Delegation Grant is a huge sign of appreciation and support of BALANCE’s core mission and work, namely decentralization metrics and pool group tracking for Cardano insights.  The CF Grant and support from the greater Cardano Community at large has really validated that our work and passion at BALANCE is valuable. The Grant has sparked and reinvigorated our focus and work. We now want to take our charts and analysis for Cardano to the next level!

Therefore, this report captures our updates, work accomplished so far, and our roadmap planning look-ahead. Get ready!

------------
## Updates

### New Website and Fast, Crisp Charts
The BALANCE website and charts are being revamped for a fast and crisp big data experience!  On our old site, the Stake Vs Leverage Chart loading was so slow because there was so much big data to load. Also, the interactive experience was sluggish and laggy.  

Not anymore! BALANCE has decided to totally revamp the website design to be fast, crisp, and look great.

### New Email Newsletter Subscription and Website Articles
What good is analysis if it’s not in your hands? The BALANCE Website will now have an email newsletter subscription for our Cardano insights! The newsletter articles will link back to the website to our article library.

------------
## Work Accomplished

### New Bespoke Website & Application Development
After months of hard work, BALANCE is proud to announce the eminent launch of our brand new bespoke website!

The website will be complete with an email newsletter subscriptio, article library, and most importantly our curated chart boards.

The real reason to renovate and clean house on the old website was to tackle the problem of how to create beautiful charts and analysis that are *also* a great user experience of being fast, responsive, crisp, and exploratory. 

We explored different open source frameworks and libraries that would position us to have the best chart experience, quality, and future proof advantage.

Ultimately, after an extensive trade study was performed exploring the solution space, the design decision was made to pursue a _*Sveltekit Web-app with D3.js Charts combo*_.

Though this design decision carried significant work and schedule impacts, and a difficult and uncertain path, the fundamental quality and performance under the hood was the driving factor to create a product that will last for years to come. 

The Cardano culture is no stranger to these difficult design decisions for principles.  This is akin to choosing Haskell for the cardano-node, but for us, a web application of the highest quality visualization experience and design curation.

{% img src="cip50-stake-v-leverage-preview.png" alt="stake v leverage chart" %}

Please explore and play with the __CIP-50 Charts__ on the website.

### Why Sveltekit for the Website & Application?

{% img src="svelte_kit_homepage_screenshot.png" alt="svelte kit home page screenshot" %}

Basically, Sveltekit is a new framework and language that has the significant advantages of a fast, clean, and crisp user experience that far out-weighs its predecessor of React and Javascript. 

From the Svelte website: 

> "Svelte is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app. Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.” 

In layman’s terms, running Svelte at build-time compiles your code into lightweight and super simple javascript code, thus the user gets a fast experience. The heavy lifting is done at compile time.

But what is Sveltekit? Well, from the Sveltekit Introduction:  

> “SvelteKit is a framework for rapidly developing robust, performant web applications using Svelte.” 
“Svelte renders UI components. You can compose these components and render an entire page with just Svelte, but you need more than just Svelte to write an entire app.  SvelteKit provides basic functionality like a router — which updates the UI when a link is clicked — and server-side rendering (SSR).”

In layman’s terms again, Sveltekit is the tooling and framework that let’s you build a web app using Svelte (and other stuff), including the server-client side fetch and push interactions, shared memory, and full stack capabilities.

Sveltekit is a hot new language that is being adopted for good reason, but it is still young, has poor documentation at times, and has growing pains. So, the design decision to use Svelte was not the easy route, but we believe the right decision.

### Why D3.js Charts?

{% img src="d3js_homepage_screenshot.png" alt="d3js homepage screenshot" %}

Ultimately, to make serious, professional grade charts and curated data visualizations, we needed a robust and extensive library that is compatible with Sveltekit.  That ultimately lead us to D3.

What is D3 you ask?  Well from the D3.js website:

>“D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation.”

In layman’s terms, D3 is a robust and mature javascript visualization library used by the pros, with the trade off of complexity for additional control and artistic work.  After browsing what is possible from the very creators of Sveltekit showcasing their data visualization story telling, it is very impressive and BALANCE was sold.

It should be clear by now BALANCE is going for timeless work and the learning curve investment is worth the time for quality.

----
### Website Email Newsletter Subscription and Articles

The newsletter and article topics covered will be mainly stake pool groupings, landscape, and BALNC pool updates. Cardano blockchain intelligence will come right to your inbox and be available to read in bulk on the website.

### Listed on Cardano Developer Portal & Single Pool Alliance
In addition to website building, in parallel we have branched out to get the BALNCE name out there and recognize. We have been successfully listed in the Cardano Developer Portal and the Cardano Single Pool Alliance. We’ve also update our website with an About Page on the Founder and Team.

As you can tell, the CF Grant Delegation has been put to hard work, and we hope the results speak for itself from the CIP-50 Chart Board Web App experience. 

-------------
## Roadmap
So where is BALANCE going with continued Grant support?

Well, we have big plans.  If our CF Grant support stays for the next delegation round, and also the support from our loyal delegators, the following will be the funded work in exchange.

Phase II: Website & Community Building
By creating and delivering on our public services, we hope to exchange value-for-value and gain BALNC stake pool delegators to sustain our work and mission.

Continued Website Building
Currently the website is our Minimal Viable Product.

More Highly Curated Charts

Building an Intelligence Community in the Matrix

More Analysis for Newsletter Content
SQL Script development and standardization, metrics, stake pool pledge changes, pool stake in-flows and out-flows, decentralization and network health metrics.

New Social Media Presence
Doing heads down work is our favorite thing to do, but we’ll be stepping up our social media presence to inform the community with key intelligence, as well as receive open source tips to investigate.  This will not only strengthen our watchdog presence but also provide more robust publicly available data and insights.

Phase III+: Business Development & Growth
Once the BALNC pool grows and the BALANCE website content and brand matures, BALANCE’s ultimate goal is to expand into the Data-as-a-Service business model.  

There are many untapped ideas since BALANCE has the entire db-sync blockchain (not just an index), and a unique set of skills. One possible avenue could be to provide on-chain data to wallets or charts, or any project that needs it. We may also explore Delegation-as-a-Service where the high end intelligence value is only provided to the stake pool delegators.  We could also create tutorials or educational courses for small group education or pool delegates.  This may attract others who wish to learn and build a learning and teaching culture within the pool’s Matrix Space.

### What's Possible? An Overview

{% img src="d3_piechart_example.png" alt="d3 pie chart example" %}


{% img src="d3_examples_1.png" alt="d3 future idea pool bubble chart example" %}
**Figure: Test heading bold**

{% img src="d3_example_pools2.png" alt="d3 future idea pool group bubble example 2" %}
__Figure: Test heading italics__

{% embed src="https://www.youtube.com/embed/bnd64ZrHC0U?start=1113" title="Svelte and D3 - Matthias Stahl @ Svelte Society Stockholm" %}

Cheers! 

Sincerely,
- The BALANCE Team
