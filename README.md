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

## Policy formation

Policy formation is a kind of innovation, a bit like R&D, with similar dynamics.

## Artistic creativity

Artisitic creativity generally does not use a linear process but something more chaotic, at least at the individual level. 

## Palliative care

Ideas from [Team Topologies](https://teamtopologies.com/) are being used in many healthcare contexts, especially emergency care, but [end-of-life care (aka palliative care)](https://www.nhs.uk/conditions/end-of-life-care/what-it-involves-and-when-it-starts/) is possibly less in need of fast flow approaches because the changes needed are minimal. 

## Unstable execution environment preventing useful platform abstractions

Situations where the underlying execution environment (business landscape, technology, primitives, etc.) is changing frequently in unpredictable ways can make it difficult to provide useful, stable abstractions in an X-as-a-Service mode from a platform to other groups.

_Example: development of an autonomous robot for executing tasks in a human environment where the physical hardware platform (chassis, wheels, etc.) is undergoing rapid and transformational development together with rapid and substantial changes to the firmware operating system AND the behavioural features of the robot. In this situation, it is difficult (although not impossible) to make useful platform abstractions that can help fast flow._

This situation can be close to [Cynefin Chaotic](https://en.wikipedia.org/wiki/Cynefin_framework#Chaotic) in terms of the effect on teams building and evolving the different services. A key goal here should be - when possible - to introduce useful platform abstractions to reduce team cognitive load and avoid whole-system change coupling.
