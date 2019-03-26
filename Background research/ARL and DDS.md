# Army Research Labs and the Defense Digital Service

Jordan’s worked on [Code.mil](https://code.mil/) since July 2017 or so — as a secondary priority to his primary work, he takes meetings with folks within DoD that would like to open source software (or use open source software) and helps them navigate the process to do so. As a result, he’s “intimately familiar” with ARL’s process, as he’s spent considerable time working with Cem previously. 

Cem originally reached out to the Defence Digital Service to ask for assistance in implementing better open source policies at ARL, but they declined as it’s outside their typical work — which is how ARL found their way to 18F.

## Work with the DoD’s CIO

Jordan and the DDS more broadly is interested in getting the DoD CIO’s office to publish a memorandum on open source software, stating that software which (a) follows contributor and license policies stated on Code.mil and (b) uses continuous integration tools which include security analysis, a test for licenses, and general software testing will be implicitly approved for open source release by DoD’s general counsel. 

This would go a long way, but often the Army’s general counsel, for example, would want to review things independently rather than taking the advice of DoD’s general counsel.

## Open Source Software Task Force

DoD’s CIO office generally supports an Open Source Software Task Force, but hasn’t made it a priority to make it happen — so they are likely to support this kind of an effort. A good contact would be Dan Risacher in DoD’s CIO office, who is already on our Open Source Software Task Force email list.

## Positioning for impact

Ideally for biggest impact, this project would be spearheaded by the Army CIO/G-6, not ARL. In the absence of policy, ARL is free to pursue their own path. In writing a policy such as this, it’s important to keep in mind that software takes lots of forms — and a good policy is flexible and can be adapted to work for any number of kinds of software (from individual algorithms to full projects).

If this policy work can be general enough to apply to different forms of software coming out of ARL, it can also likely be used by other research labs inside DoD (and other similar groups). This falls in line with the thinking of Jin and the Open Source Software Task Force. 

Jordan gave a few tips about getting things done at DoD — generally that it’s easy to get buy in from top-level folks (they want to improve the organization generally) and easy to get support from those doing the work (motivated to improve their processes), but it’s harder to get the folks in the middle to push your agenda. He’s found what may be typical — that folks are risk averse and don’t want to make too many waves. Finding folks who are “in a terminal position” (I’ve never heard this expression, but people who won’t be advancing in ranks due to retirement or other reasons) can help motivate change, since they’re less risk averse. Getting someone who’s a Colonel/O-6 (roughly equivalent to a GS-15) to sign off on something can mean a lot.

## Open source in other areas

Generally, DoD has a rich history of open source, including perhaps most notably [SELinux](https://en.wikipedia.org/wiki/Security-Enhanced_Linux) out of the National Security Agency.

While discussing [Lawrence Livermore National Laboratory’s open source policy](https://software.llnl.gov/about/licenses/), Jordan mentioned that DoE has a leg up on open source, because they have both support from above and a critical mass of examples of software that has been open sourced under DoE’s name.

## Complementary efforts

- [DI2E](https://www.di2e.net/display/DI2E), which is a set of software development tools designed to be a secure coding environment within DoD, including source code hosting (Bitbucket), continuous integration (Jenkins), chat services (XMPP), issue tracking (JIRA), code reviews (FishEye+Crucible), and more. On GitHub, the project seems relatively dead (with latest activity in 2012, which seems to fit with the visual appeal of that site) with one exception — the [Open Storefront](https://github.com/di2e/openstorefront) project seems to be active with commits in the last few days.
- Nicolas Chaillan’s work at [Acquisition and Sustainment](https://www.acq.osd.mil/) within a DevSecOps pipeline for the DoD (hoping to flag a specific set of tools and get them approved for use by DoD’s general counsel).


