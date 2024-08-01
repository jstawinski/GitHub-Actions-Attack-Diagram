# GitHub Actions Attack Diagram

The GitHub Actions Attack Diagram provides guidance for identifying GitHub Actions vulnerabilities. Starting with read-only or write access to a GitHub organization/repository, you can follow the diagram to determine how to identify and exploit GitHub Actions misconfigurations, from self-hosted runner takeover, to PWN requests, to secrets exfiltration. Throughout the diagram, various resources are linked to provide additional context.


The diagram outlines common attack paths [Adnan Khan ](https://adnanthekhan.com/) and I have used on Red Team engagements and during public vulnerability research. We presented this research in-depth at Black Hat USA 2024 ([Continuous Integration, Continuous Desctruction](https://www.blackhat.com/us-24/briefings/schedule/index.html#self-hosted-github-cicd-runners-continuous-integration-continuous-destruction-38308)) and DEF CON 32 ([Grand Theft Actions](https://defcon.org/html/defcon-32/dc-32-speakers.html#54489)).

These attack paths may change over time as GitHub updates their internal configurations. If you notice that certain TTPs are no longer valid, or to request the addition of new TTPs, please create an Issue. 

This diagram is not inclusive, rather, it outlines major attack paths and TTPs we have used on targets in live environments.

Enjoy:)

# Exploits in the Wild

If you're curious about how we've used these TTPs to exploit critical CI/CD vulnerabilities in the wild, you can check out our BH/DC talks linked above, or read some of the following blog posts we've released.

* [Playing With Fire - How We Executed a Critical Supply Chain Attack on PyTorch](https://johnstawinski.com/2024/01/11/playing-with-fire-how-we-executed-a-critical-supply-chain-attack-on-pytorch/comment-page-1/)
* [Fixing Typos and Breaching Microsoft's Perimeter](https://johnstawinski.com/2024/04/15/fixing-typos-and-breaching-microsofts-perimeter/)
* [One Supply Chain Attack to Rule Them All](https://adnanthekhan.com/2023/12/20/one-supply-chain-attack-to-rule-them-all/)
* [RoguePuppet](https://adnanthekhan.com/2024/07/02/roguepuppet-a-critical-puppet-forge-supply-chain-vulnerability/)
* [AStar Network Supply Chain Attack](https://adnanthekhan.com/2024/01/19/web3s-achilles-heel-a-supply-chain-attack-on-astar-network/)
* [Worse Than Solarwinds - Three Steps to Hack Blockchains, GitHub, and ML Through GitHub Actions](https://johnstawinski.com/2024/01/05/worse-than-solarwinds-three-steps-to-hack-blockchains-github-and-ml-through-github-actions/)
* [TensorFlow Supply Chain Compromise via Self-Hosted Runner Attack](https://www.praetorian.com/blog/tensorflow-supply-chain-compromise-via-self-hosted-runner-attack)
* [Compromising ByteDance’s Rspack using GitHub Actions Vulnerabilities](https://www.praetorian.com/blog/compromising-bytedances-rspack-github-actions-vulnerabilities/)

