# 🐢 [Rolling Alice...](https://github.com/intel/dffml/blob/alice/docs/tutorials/rolling_alice/0000_architecting_alice/README.md#rolling-alice-volume-0-introduction-and-context) ⏳

Hello Entity of the Internet! I'm John.

I've fallen down the open source supply chain security rabbit hole.

My current focus is around leveraging threat model and architecture
information to facilitate automated context aware decentralized gamification
/ continuous improvement of the security lifecycle / posture of open source
projects.

I would love if you'd join in on this adventure.

> Source: [Living Threat Models Are Better Than Dead Threat Models](https://gist.github.com/pdxjohnny/07b8c7b4a9e05579921aa3cc8aed4866#file-rolling_alice_progress_report_0006_living_threat_models_are_better_than_dead_threat_models-md) [John L. Whiteman and John S. Andersen]
>
> *The cornerstone of security for every application starts with a threat model. Without it, how does one know what to protect and from whom? Remarkably, most applications do not have threat models, take a look at the open-source community. And, even if a threat model is created, it tends to be neglected as the project matures since any new code checked in by the development team can potentially change the threat landscape. One could say that the existing threat model is as good as dead if such a gap exists.*
>
> *Our talk is about creating a Living Threat Model (LTM) where the same best practices used in the continuous integration of source code can aptly apply to the model itself. LTMs are machine readable text files that coexist in the Git repository and, like, source code, can be updated, scanned, peer reviewed and approved by the community in a transparent way. Wouldn’t it be nice to see a threat model included in every open-source project?*
>
> *We need to consider automation too to make this work in the CI/CD pipeline. We use the open-source Data Flow Facilitator for Machine Learning (DFFML) framework to establish a bidirectional data bridge between the LTM and source code. When a new pull request is created, an audit-like scan is initiated to check to see if the LTM needs to be updated. For example, if a scan detects that new cryptography has been added to the code, but the existing LTM doesn’t know about it, then a warning is triggered. Project teams can triage the issue to determine whether it is a false positive or not, just like source code scans.*
>
> *We have been working on this effort for a few years and feel we are on the right track to make open-source applications more secure in a way that developers can understand.*

- [johnandersenpdx@gmail.com](mailto:johnandersenpdx@gmail.com?subject=Introduction)
- [@pdxjohnny@mastodon.social](https://mastodon.social/@pdxjohnny)
- [Rolling Alice: Progress Reports](https://www.youtube.com/playlist?list=PLtzAOVTpO2jYt71umwc-ze6OmwwCIMnLw)
- [Rolling Alice: Progress Report Transcripts](https://gist.github.com/pdxjohnny/07b8c7b4a9e05579921aa3cc8aed4866)
- [Alice Engineering Comms](https://github.com/intel/dffml/discussions/1406?sort=new)
  - Come! Roll Alice with us!

[![hole-rabbit-hole](https://user-images.githubusercontent.com/5950433/196436807-68881b75-2006-4734-b4a2-63dc3d17b634.gif)](https://github.com/intel/dffml/commit/291cfbe5153414932afe446aa4f6c2e298069914)
