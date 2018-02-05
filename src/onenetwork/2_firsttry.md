<!-- 5min -->

#

## A brief story of a <span style="color:yellow">network</span> service

## Typical IT ecosystem

![](https://docs.google.com/drawings/d/e/2PACX-1vTHReaikhEnE5P6ibNIZnz9oUeM8fBMkahaALKEzpe5yNg9Zu5gzBitPMigYQxi_KZ5Q1646zjB5oc6/pub?w=1262&h=642)


## How the network looks like

![](https://docs.google.com/drawings/d/e/2PACX-1vRUX-foYcEbVO4d3slCY8Jwzk4OWYGnib6j0KbZzM7MtpPaFmrBUeZFevD4g70w0It_WwQw2Ww6afIL/pub?w=1262&h=642)

## Downsides

* By default, inter/intra platform communications use <span style="color:yellow">Internet</span>
* Internet is not (always) the most <span style="color:yellow">performant and cheapest</span> communication channel
* Manual network provisioning doesn’t work in terms of <span style="color:yellow">speed and reliability</span>
* Prone to <span style="color:yellow">errors</span> and lack of consistency
* Some communications still need <span style="color:yellow">network layer security</span> (no TLS)

## We tried to solve all in one

![](https://docs.google.com/drawings/d/e/2PACX-1vQc-NEus2L7gFkKqEugb6pWPY4xoFt7WVK-2Q2yiC9ngIYSCkB5rqGcWSZEyIQ7ZqD-VkL9NJpJ_FBr/pub?w=1257&h=630)

##  ... and we <span style="color:yellow">failed</span>

## (non-technical) Lessons learned

* Think as your <span style="color:yellow">users</span> will do
* Get <span style="color:yellow">feedback</span> as soon as possible, iterate!
* The solution has to be <span style="color:yellow">flexible</span> enough to be accommodate plugins <!-- multiple underlying solutions -->
*  Evaluate <span style="color:yellow">current</span> needs case-per-case (capability, performance, cost, etc.)
*  Apply Pareto Rule, <span style="color:yellow">focus</span> on solving most urgent first
