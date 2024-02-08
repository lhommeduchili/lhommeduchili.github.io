---
layout: projects
title: projects
permalink: /:basename/
---

# Tracking _Paenibacillus vortex_ bacteria in time-lapse microscopy images @ [openFIESTA][5]{: .pretty_border}

{% capture details %}
Several bacterial species can form complicated growth patterns on a wide variety of environmental conditions. Because the development of such complex structures requires self-organization and cooperative behavior of individual cells, the study of microbial pattern formation has been a basis for understanding intricate biological and social phenomena such as multicellularity.

_P. vortex_ generates swarming patterns with leading groups of cells containing tens to thousands of bacteria that cooperatively whirl around a common center. These vortices expand in size and move outward as a unit, leaving behind a trail -the vortex branch-. Although vortices are easy to identify, its dynamics are quite complicated and include attraction, repulsion, merging, and splitting; hence the task of tracking these moving structures imposes a challenge that is interdisciplinary at its core.

This project aims to explore the use of [**optical flow**][6] to identify swarming structures in spatial time series data of microbial dynamics, which are then sequentially mapped to statistical models that can help us to develop some understanding of these bacteria's motility.

[6]: https://en.wikipedia.org/wiki/Optical_flow "i.e. motion field between two image frames"
{% endcapture %}

{% capture summary %}
<span style="color: #666666;">Optical Flow & Particle Filter.</span>
{% endcapture %}{% include details.html %}

[5]: http://www.fiesta.tsinghua.edu.cn/ "Open Faculty for Innovation, Education, Science, Technology and Arts"

---
# The Swarm @ [biotexturas][1]{: .pretty_border}

{% capture details %}
**The Swarm** is a decentralized and diverse research group that study microbes, not in an ordinary way, but through building open-source hardware (e.g. [**HomeScope**][2], an open-source robotic microscope) and playing **My Swarm**, a (biotic) game that operates on the biological process of adaptation and computation of swarming bacteria living in complex habitats.

In the gamified context of the project, The Swarm is a group of researchers-players who build their HomeScope, a microscope turned into a game console, along with the game cartridges (simple microfluidic devices) where soil bacteria grow, develop and expand over its surface. In these cell-ecosystem machines, computer vision and machine learning algorithms abstract living biological structures and map them into game elements that make up My Swarm, which creates a virtual ecology where real bacterial cultures living in different HomeScope consoles can compete and play, providing an ecological context for the directed evolution of game-winner strains.

Our vision is deeply motivated by the idea of making science accessible for everyone and decentralized, which is why we are learning how to run My Swarm on a blockchain's virtual machine and tokenize observations of natural history (strain's data) made by people.

[2]: http://homescope.biotexturas.org "DIY robotic microscope"
{% endcapture %}

{% capture summary %}
<span style="color: #666666;">DAO, [biotic games][3], OSH, and beyond.</span>

[3]: https://pubs.rsc.org/en/content/articlelanding/2011/lc/c0lc00399a "go to I. H. Riedel-Kruse's article"
*[DAO]: Decentralized Autonomous Organization
*[OSH]: Open-Source Hardware
{% endcapture %}{% include details.html %}

[1]: https://biotexturas.org "Collective of intelligent people, machines, and ecosystems"

---
# [HomeScope][4]{: .pretty_border} <span>&#x1F52C;</span>

{% capture details %}
![HomeScope 3D frame](/assets/images/homescope.png){: .centered_img width="350px;"}

Homemade RaspiCam/Arduino-based digital microscope system capable of recording video and image capture (time-lapse microscopy) while robotically scanning a sample. The HomeScope as a whole package is not only a DIY biologist solution for developing robotic microscopy capabilities for the home laboratory but also a means to learn (and teach) subjects across disciplines.

This open-source project is being developed collectively by biotexturas and collaborators.
{% endcapture %}

{% capture summary %}
<span style="color: #666666;">An open-source microscope with a robotized XYZ stage.</span>
{% endcapture %}{% include details.html %}

[4]: http://homescope.biotexturas.org "DIY robotic microscope"
