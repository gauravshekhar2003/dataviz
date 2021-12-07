---
layout: post
title: Critique - Published Chart 
subtitle: Create a Leaf and color it using R
gh-repo: gauravshekhar2003/dataviz
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/chart_line.png
tags: [visual, charts]
comments: true
---

![Visual](https://raw.githubusercontent.com/gauravshekhar2003/dataviz/master/assets/img/A1Covid19.png)

Source: [John Hopkins University](https://coronavirus.jhu.edu/data/state-timeline/new-confirmed-cases/texas/1)

The above visual talks about the impact of social distancing measures on the trends of cases and deaths. Dots on the timeline indicate key events in each state – closings (in red), openings (in green) and other policy changes and events (in grey).
The visual that we see in the screenshot talks about the Cases only. Since the data is temporal, a time series/line chart makes a lot of sense. The superimposition of the dotted line show us very clearly how the policy stance changed and what effect it had on the cases. Now even though the chart takes about either the cases or deaths at a time, it would have been better if both the graphs were superimposed to help readers compare the 2 trends. One of the reasons it wasn’t done was because the data on the ‘Y’ axis is different in terms of proportion for both the charts. This is where things like ‘Percent Change’ can help normalize the differences. 
