# Deep Vision by Taijitu AI

**From sensing to understanding. From understanding to responsible action.**

Taijitu AI is developing an agentic extension of Cisco's open-source DeepVision
project: connecting video and other sensor observations to useful, human-led
responses.

The goal is to move beyond isolated detections and alerts toward systems that
help people investigate a situation, connect evidence, choose an authorized
response, and understand what happened afterward.

> **Early-stage project:** This repository currently contains the project
> overview, not a released Taijitu AI implementation. The architecture and
> applications below describe our development direction, not validated
> deployments or available integrations.

## Cisco heritage

The starting point is [Cisco's original DeepVision project](https://github.com/cisco-open/DeepVision),
a serverless edge platform for explainable computer vision and multimodal
spatiotemporal analytics. Its research spans perception, tracking, structured
observations, reasoning, self-supervised and lifelong learning, and persistent
memory for language models through RecallM.

That broader Cisco research lineage includes smart-city and traffic analytics,
as well as sensing and operational awareness for wildlife conservation. Hugo
Latapie, Taijitu AI's founder and a former Principal Engineer at Cisco Research,
brings experience from that work to this new project.

We credit Cisco and the upstream contributors for the foundation. Deep Vision
by Taijitu AI is an independent Taijitu AI project; this attribution does not
imply Cisco sponsorship or endorsement.

- [Original source code: cisco-open/DeepVision](https://github.com/cisco-open/DeepVision)
- [Cisco Research project overview](https://research.cisco.com/research-projects/deep-vision)

## Where we are going

We want to connect continuous sensing with goal-directed investigation:

- **Observe and structure:** Turn authorized video and sensor inputs into
  tracks, events, time series, and context.
- **Investigate:** Let people, agents, and applications express questions and
  objectives, examine relevant observations, and request more evidence.
- **Respond responsibly:** Support human review and authorized actions within
  the operating environment's constraints.
- **Check outcomes:** Relate responses to observed effects and use that
  feedback to improve subsequent decisions.

The proposed architecture uses open interfaces for compatible agents and
language models, with connections to Taijitu AI's AOCA through authorized SaaS
access. AOCA and other proprietary Taijitu systems remain outside the planned
open-source distribution. Adapter compatibility and end-to-end operation still
require implementation and validation.

Source identity, event time, uncertainty, and links to original evidence should
remain available throughout the process.

## Applications we want to explore

- **Child safety at home and beyond:** Help trusted adults notice potential
  risks around kitchens, yards, pools, and concerning situations beyond the
  home, review context, and respond appropriately. Technology must never
  replace adult supervision.
- **Transportation and smart cities:** Connect road-user observations,
  changing conditions, and relevant evidence to safer, better-informed
  operations.
- **Conservation:** Support wildlife protection and ranger awareness through
  thermal sensing, contextual observations, and human-led investigation.

These are intended application areas, not prevention guarantees or measured
Taijitu deployment results. Privacy, authorized access, human oversight, and
evaluation in the actual operating environment are essential.

## Open-source direction

Cisco's upstream repository is licensed under
[Apache 2.0](https://github.com/cisco-open/DeepVision/blob/main/LICENSE).
We plan to release the open-source extension under Apache 2.0, preserving
Cisco's upstream attribution and applicable notices. Third-party components
remain subject to their respective licenses.


## Build with us

We welcome researchers, developers, families, cities, and conservation partners
who can bring a use case, domain knowledge, and a way to evaluate useful
outcomes.

[Open an issue](https://github.com/taijituai/DeepVision/issues) to discuss a use
case or collaboration, or contact [Hugo Latapie](mailto:hugo@taijitu.ai).
Please do not post private footage, personal information, or sensitive incident
details in public issues.
