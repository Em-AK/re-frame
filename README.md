

<img width="0.3vw" src="docs/images/logo/re-frame_256w.png?raw=true">

<p align="center"><a href="https://day8.github.io/re-frame" target="_blank" rel="noopener noreferrer"><img width="250" src="docs/images/logo/re-frame_256w.png?raw=true" alt="re-frame logo"></a></p>

## Derived Values, Flowing

> This, milord, is my family's axe. We have owned it for almost nine hundred years, see. Of course,
sometimes it needed a new blade. And sometimes it has required a new handle, new designs on the
metalwork, a little refreshing of the ornamentation ... but is this not the nine hundred-year-old
axe of my family? And because it has changed gently over time, it is still a pretty good axe,
y'know. Pretty good.

> -- Terry Pratchett, The Fifth Elephant <br>
> &nbsp;&nbsp;&nbsp; reflecting on identity, flow and derived values  (aka [The Ship of Theseus](https://en.wikipedia.org/wiki/Ship_of_Theseus))


[![CI](https://github.com/day8/re-frame/workflows/ci/badge.svg)](https://github.com/day8/re-frame/actions?workflow=ci)
[![CD](https://github.com/day8/re-frame/workflows/cd/badge.svg)](https://github.com/day8/re-frame/actions?workflow=cd)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/day8/re-frame?style=flat)](https://github.com/day8/re-frame/tags)
[![Clojars Project](https://img.shields.io/clojars/v/re-frame.svg)](https://clojars.org/re-frame)
[![GitHub issues](https://img.shields.io/github/issues-raw/day8/re-frame?style=flat)](https://github.com/day8/re-frame/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/day8/re-frame)](https://github.com/day8/re-frame/pulls)
[![License](https://img.shields.io/github/license/day8/re-frame.svg)](license.txt)

## Overview

re-frame is a ClojureScript framework for building user interfaces.
It is has a data-oriented, functional design.

re-frame has been designed from the ground up to make developers **very**
productive when building large Single-Page applications. That's its promise to you. 
So far it seems to have met this 
the goal, and it has been enthusiastically praised by many.

Developed in late 2014, and released in 2015, it is mature and stable. 
It has outlasted multiple generations of Javascript churn, and still delivers a substantially better developer experience. Imagine your productivity if you didn't have to contend with technical churn, and have new magic burn your fingers every two years.  


re-frame provides another unfair advantage - ClojureScript is a Lisp. Alan Kay
once described Lisp as "Maxwell's equations of software". Paul Graham 
regarded Lisp as a competitive advantage for his startup.  By using a Lisp, we 
get to leverage 50 years of foliated excellence from the very best minds available.
We also get to leverage a thriving ClojureScript community which delivers modern ideas and best-in-class tooling.


re-frame was created by a programmer who had already been developing for two decades
before the Web was even invented. Yeah, that old. Seen a UI or two along the way. Still has hair.

Although re-frame leverages React (and the brilliant [Reagent](http://reagent-project.github.io/)), it only needs 
React to be a V in MVC, no more. re-frame does not buy into the sadly pervasive idea that Views should be causal (colocated queries, ComponentDidMount, hooks, etc).
In re-frame, events are causal and views are reactive. 

## Documentation 

The re-frame documentation is on [the website](http://day8.github.io/re-frame/).

