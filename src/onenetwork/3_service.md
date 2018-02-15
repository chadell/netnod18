<!-- 6min -->

# 

## Then, we created a <span style="color:yellow">network service</span>

## New goal

![](https://docs.google.com/drawings/d/e/2PACX-1vSvNRJpmhIwaV2Uyubyq0MlOlw7ZfzpNvglQhu1txAtaAGgaVK1DSH6RKfUiIDpyz2mZ-V8OBZ6SGus/pub?w=1257&h=630)

## Requirements

* Easy onboarding / <span style="color:yellow">selfserve</span>
* Users should be <span style="color:yellow">autonomous</span> to handle connections
* <span style="color:yellow">Abstract</span> all network details from users, and use the <span style="color:yellow">best</span> option in every case
* Support <span style="color:yellow">several</span> providers/platforms
* Offer a <span style="color:yellow">secure</span> service
* Continuous monitoring of connection <span style="color:yellow">status</span>, and notify users when it doesn't match

## Assumptions

* API consumers will be <span style="color:yellow">authenticated</span> through a SSO / Token
* <span style="color:yellow">Rights</span> to manipulate others' networks
* External APIs to <span style="color:yellow">integrate</span> with
* <span style="color:yellow">Consistent</span> address plan (less pain)

## Actual implementation

* A <span style="color:yellow">rest API</span>
* A distributed <span style="color:yellow">asynchronous</span> architecture
* <span style="color:yellow">Extensible modules</span> to talk with underlying network services
* A user/machine <span style="color:yellow">interface</span> (CLI + API wrapper)
* Running on <span style="color:yellow">dynamic infrastructure</span> (IaaS, PaaS, SaaS)

## Architecture

![](https://docs.google.com/drawings/d/e/2PACX-1vSefaisqNFTjHAS33TVa9Qt4eWLu4ENwoPer-uIWlm4Gvu0wpimBfI0ydN2l6lSOkL2vqgE8EXpd0Sz/pub?w=1352&h=692)

## Mappings

![](https://docs.google.com/drawings/d/e/2PACX-1vQkPKUxJsimq_RU17U6bAbI21mEpEBmthmqGJGf6sJQvsyWfZrbK3hq-2-VveRzBIwaBcls-FNFtz1_/pub?w=1257&h=630)

## How

All of this, applying <span style="color:yellow">DevOps</span> principles:

* <span style="color:yellow">Infrastructure as Code</span>
* Continuous Integration & Continuous Delivery
* Following (most) of the <span style="color:yellow">12-Factor App</span> design principles

<span style="color:yellow">You build it, you run it!</span>

## from idea to <span style="color:yellow">Production</span> in <span style="color:yellow">4 months</span> 
