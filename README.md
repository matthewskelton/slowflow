# Slow flow - contexts where fast flow might not be suitable. #fastflow 

The ideas from approaches like [Team Topologies](https://teamtopologies.com/) assume a need for fast flow of changes. In 2022 and beyond, it's fair to say that the majority of organizations building and running software-enriched services need fast flow, but there are exceptions. 

_How to contribute: add a topic to the bulleted list and a corresponding subheading with explanation. US English spellings, please (we have to pick one option!)._ 

[Prompted by this tweet](https://twitter.com/matthewpskelton/status/1555633739681652736) (thanks to Muhammad Sufyian (محمد سفیان)), here are some situations where the need for #fastflow might be reduced or not relevant:

- Research and Development (R&D)
- Policy formation
- Artistic creativity
- Palliative care
- ... and any context where the underlying environment/landscape/technologies/primitives are unstable and changing so unpredictably that platform abstractions are not possible or not helpful 

By extension, #fastflow is suitable in most other areas.

## Research & Development (R&D)

R&D is concerned with discovery and unknown aspects of a domain, so it's difficult to even know what the domain really contains. If the domain is still unknown, it's difficult to align to streams of change in the domain.

Experimentation can vary wildly, but in most cases, we try and fail based on changing few parameters in order to clearly understand what works and why.

## Policy formation

Policy formation is a kind of innovation, a bit like R&D, with similar dynamics.

We have huge issues arise in policy formation because we fail to experiment, simulate, and share proposals for feedback. We fail even further when we don't effectively synthesize feedback. All this is enabled by fast flow.

## Artistic creativity

Artisitic creativity generally does not use a linear process but something more chaotic, at least at the individual level. 

Professional art is another domain where experimentation, feedback, and delivery are important. If you succeed, there will be demand, and though it may not be mutually beneficial to fulfill it, fast flow can minimize the waste and burden of creative work.

## Palliative care

Ideas from [Team Topologies](https://teamtopologies.com/) are being used in many healthcare contexts, especially emergency care, but [end-of-life care (aka palliative care)](https://www.nhs.uk/conditions/end-of-life-care/what-it-involves-and-when-it-starts/) is possibly less in need of fast flow approaches because the changes needed are minimal. 

This would seem to be an area of relative stability. With ever-advancing technology the need to deliver and adapt is growing. We also have breakouts of disease that require rapid response and in many cases continuous effort.

## General caveat to slow flow

Flow is a dimension at all levels of scale. Every individual, team, organization, industry etc have flow, and fast is typically preferred. Even if fast isn't needed, it's usually beneficial to have the capability to rapidly respond and adapt.

## Unstable execution environment preventing useful platform abstractions

Situations where the underlying execution environment (business landscape, technology, primitives, etc.) is changing frequently in unpredictable ways can make it difficult to provide useful, stable abstractions in an X-as-a-Service mode from a platform to other groups.

_Example: development of an autonomous robot for executing tasks in a human environment where the physical hardware platform (chassis, wheels, etc.) is undergoing rapid and transformational development together with rapid and substantial changes to the firmware operating system AND the behavioural features of the robot. In this situation, it is difficult (although not impossible) to make useful platform abstractions that can help fast flow._

This situation can be close to [Cynefin Chaotic](https://en.wikipedia.org/wiki/Cynefin_framework#Chaotic) in terms of the effect on teams building and evolving the different services. A key goal here should be - when possible - to introduce useful platform abstractions to reduce team cognitive load and avoid whole-system change coupling.
