<!-- 7min -->

# 

## Then, we created a <span style="color:yellow">network service</span>

## New goal

![](https://docs.google.com/drawings/d/e/2PACX-1vSvNRJpmhIwaV2Uyubyq0MlOlw7ZfzpNvglQhu1txAtaAGgaVK1DSH6RKfUiIDpyz2mZ-V8OBZ6SGus/pub?w=1257&h=630)

## Requirements

* Easy onboarding / <span style="color:yellow">selfserve</span>
* Users should be <span style="color:yellow">autonomous</span> to handle connections
* <span style="color:yellow">Abstract</span> all network details from users, and pick the <span style="color:yellow">best</span> option in every case
* Support <span style="color:yellow">several</span> providers/platforms
* Offer a <span style="color:yellow">secure</span> service
* Continuous monitoring of connection <span style="color:yellow">status</span>

## Assumptions

* Mgmt-API users will be <span style="color:yellow">authenticated</span> through a SSO / Token
* <span style="color:yellow">Permissions</span> to manipulate others' network infrastructure
* External APIs to <span style="color:yellow">integrate</span> with
* <span style="color:yellow">Consistent</span> address plan (less pain)

## Actual implementation

* A <span style="color:yellow">rest API</span>
* A distributed <span style="color:yellow">asynchronous</span> architecture
* <span style="color:yellow">Extensible modules</span> to talk with underlying network services
* Running on <span style="color:yellow">dynamic infrastructure</span> (IaaS, PaaS, SaaS)
* Infrastructure as <span style="color:yellow">Code</span> and <span style="color:yellow">Continous</span> Integration and Deployment


## Architecture

![](https://docs.google.com/drawings/d/e/2PACX-1vSefaisqNFTjHAS33TVa9Qt4eWLu4ENwoPer-uIWlm4Gvu0wpimBfI0ydN2l6lSOkL2vqgE8EXpd0Sz/pub?w=1352&h=692)

## Entities

* <span style="color:yellow">**Service**</span>: Abstract container of <span style="color:yellow">Providers</span> and <span style="color:yellow">Resources</span>, owned by OKTA <span style="color:yellow">users</span>
* <span style="color:yellow">**Provider**</span>: Environment/Platform where <span style="color:yellow">Resources</span> are deployed
* <span style="color:yellow">**Resource**</span>: A <span style="color:yellow">network element</span> defined by the network address (CIDR)
* <span style="color:yellow">**Connection**</span>: <span style="color:yellow">Bidirectional link</span> between <span style="color:yellow">Resources</span>


##

![](https://docs.google.com/drawings/d/e/2PACX-1vQkPKUxJsimq_RU17U6bAbI21mEpEBmthmqGJGf6sJQvsyWfZrbK3hq-2-VveRzBIwaBcls-FNFtz1_/pub?w=1257&h=630)

