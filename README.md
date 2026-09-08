# Awesome-Space-Situational-Awareness

## Top Space Situational Awareness (SSA) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Satellite Tracking, Conjunction Assessment, Debris Monitoring, Collision Avoidance & Orbital Traffic Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Space Situational Awareness (SSA)**. These systems help satellite operators, agencies, and researchers track objects in orbit, detect close approaches, assess collision risk, and support space traffic management.



**Examples** include LeoLabs, Slingshot Aerospace, COMSPOC, ExoAnalytic Solutions, Kayhan Space, Privateer Space, Scout Space, Share My Space, Look Up Space, and Okapi:Orbits (the category leaders).



**Open-source emphasis**: Full commercial SSA platforms rely on proprietary sensor networks and large catalogs. However, a growing set of open-source tools supports conjunction assessment, TLE/SGP4 propagation, collision probability calculation, and visualization using public data (CelesTrak, Space-Track). **OrbVeil**, **Kessler**, **ESA Cascade**, **SatGuard**, and related projects provide practical foundations. This section lists every major relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[LeoLabs](https://leolabs.space/)**  

  Leading commercial SSA provider with a global radar network focused on low-Earth orbit mapping, tracking, and space traffic management services.



- **[Slingshot Aerospace](https://www.slingshotaerospace.com/)**  

  AI-powered platform that fuses real-time and historical satellite data for orbital risk, anomaly detection, and space domain awareness, backed by an optical sensor network.



- **[COMSPOC](https://comspoc.com/)**  

  Commercial space operations center offering high-fidelity orbit determination, conjunction assessment, and SSA products for operators and governments.



- **[ExoAnalytic Solutions](https://exoanalytic.com/)**  

  Optical SSA and space domain awareness provider specializing in GEO and other regimes with telescope networks and analytics.



- **[Kayhan Space](https://kayhan.space/)**  

  Collision avoidance and space traffic coordination platform that helps operators manage conjunctions and plan safe maneuvers.



- **[Privateer Space, Scout Space, Share My Space, Look Up Space, Okapi:Orbits](https://www.privateer.space/)**  

  Emerging and specialized platforms focused on debris tracking, open data, European SSA services, and orbital analytics.



- **[Other SSA & STM providers](https://leolabs.space/)**  

  Additional commercial and government-supported services for catalog maintenance, re-entry prediction, and space traffic management.



## Open-Source GitHub Projects



- **[OrbVeil](https://github.com/ncdrone/orbveil)**  

  Open-source satellite conjunction screening engine. Screens tens of thousands of objects quickly, computes collision probability, and parses CDMs—built for transparency in safety-critical decisions.



- **[Kessler](https://github.com/siddhashutosh/kessler)**  

  Open orbital conjunction assessment toolkit that parses CDMs, computes collision probability with multiple methods, and ranks risk using real Space-Track data.



- **[ESA Cascade](https://github.com/esa/cascade)**  

  C++/Python library from ESA for propagating large numbers of orbiting objects while reliably detecting conjunctions and collisions—useful for debris and population studies.



- **[SatGuard](https://github.com/cesabici-bit/satguard)**  

  Open-source conjunction assessment pipeline covering TLE ingest, SGP4 propagation, collision probability (Foster/Chan/Alfano), 3D visualization, and maneuver planning concepts.



- **[nano-debris](https://github.com/shynsec/nano-debris)**  

  Lightweight, self-contained real-time space debris monitoring dashboard that fetches live TLE data, propagates positions, and visualizes objects on a 3D globe.



- **[COCA and maneuver tools](https://github.com/ASTRONIAN/COCA)**  

  Scripts and frameworks for conjunction assessment and basic collision-avoidance maneuver planning using TLE data.



- **[NASA CARA Analysis Tools](https://github.com/nasa/CARA_Analysis_Tools)**  

  Publicly available algorithms and software development kits from NASA’s Conjunction Assessment Risk Analysis team for probability-of-collision methods.



- **[Other orbital mechanics & SSA tools](https://github.com/search?q=conjunction+assessment+OR+space+debris+OR+SGP4+OR+TLE+open+source)**  

  Community projects for catalog screening, high-fidelity propagation, and research-grade risk analysis.



### Additional Strong Open-Source Options



- **SGP4 / SDP4 libraries**: Core orbital propagation implementations in multiple languages (Python, JavaScript, etc.).

- **poliastro / Orekit**: Broader open-source astrodynamics libraries that support orbit determination and analysis.

- **CelesTrak & public TLE tooling**: Scripts and APIs for ingesting and managing publicly available orbital element sets.

- **3D visualization**: CesiumJS and related open viewers for rendering catalogs and conjunction geometry.

- **Monte-Carlo & covariance tools**: Research code for higher-fidelity collision probability estimation.

- Debris environment models and population evolution simulators.



**Frameworks for building custom systems**:  

For open conjunction assessment and screening, start with **OrbVeil**, **Kessler**, or **SatGuard**.  

**ESA Cascade** and **NASA CARA** tools provide research-grade foundations for population studies and probability algorithms.  

Commercial SSA platforms (LeoLabs, Slingshot, COMSPOC, ExoAnalytic, Kayhan, etc.) remain essential for high-accuracy catalogs, proprietary sensor data, operational conjunction services, and regulatory-grade products.  

Many operators combine public-data open-source pipelines for internal analysis with commercial SSA feeds for operational decision-making.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Space situational awareness and conjunction assessment are safety-critical. Decisions about maneuvers or risk acceptance can affect valuable assets and the long-term sustainability of orbital regimes.

- Open-source tools that rely on public TLEs have inherent accuracy and completeness limitations compared with commercial or governmental catalogs. Users must understand data quality, covariance realism, and algorithmic assumptions before relying on results for operational decisions.



---



**Made for satellite operators, SSA analysts, space traffic managers, researchers, and space sustainability advocates.**  

Let's advance transparent, open, and collaborative tools that help keep space safe and sustainable for everyone.
