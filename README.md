# Awesome Industry 4.0

<a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://img.shields.io/github/license/MfgOpen/awesome-industry4.0.svg" alt="Licensed under the Creative Commons Attribution 4.0 International license." />
</a>
<a href="https://discord.gg/ssvcVNJ">
    <img src="https://img.shields.io/discord/677517706940907521.svg" alt="ManufacturingOpen Discord Chat" />
</a>
<a href="https://discord.gg/ssvcVNJ">
    <img src="https://img.shields.io/badge/Join%20Our-Chat%20Server-red" alt="ManufacturingOpen Discord Chat" />
</a>

A curated list of Industry 4.0 research, popular events, open-source software projects and learning resources that are worth looking into!

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Industrial Computer Programming](#industrial-computer-programming)
  - [Python](#python)
  - [TypeScript](#typescript)
- [Open Source Projects](#open-source-projects)
  - [Machine Vision](#machine-vision)
  - [Platforms](#platforms)
  - [Robotics](#robotics)
  - [Simulators](#simulators)
- [Industry Nonprofit Organizations](#industry-nonprofit-organizations)
- [Video Channels](#video-channels)
- [Trade Shows and Events](#trade-shows-and-events)
- [Newsletters and Digital Magazines](#newsletters-and-digital-magazines)
- [Other Awesome Lists](#other-awesome-lists)
- [Code of Conduct](#code-of-conduct)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Industrial Computer Programming

Computer programming is the capstone of Industry 4.0, Smart Manufacturing and modern Systems Engineering.

If you have an interest in working with and implementing advanced manufacturing and modern, connected systems, then you will need excellent computer programming skills.

### Python

**Overview**

[Python](https://www.python.org/) is a great general programming language that is very popular across a wide-variety of
domains. In some measurements, it is _the_ most popular programming language. Python is an excellent choice to start
with if you have never programmed before with its clear and clean syntax, emphasis on code readability and vast amount
reusable libraries.

Python likely has one of the richest open-source ecosystem of libraries for physical engineering and manufacturing work
at the moment.

**Typical Industrial Use Cases**

* Numerical computing and computational geometry (e.g. PCB layouts, path planning)
* Robotics design analysis and programming
* Discrete simulation (e.g. process simulation)
* Data Science
* Artificial Intelligence
* Machine Vision
* Server-side web applications

**Resources**

None, yet.

### TypeScript

**Overview**

[TypeScript](https://www.typescriptlang.org/) is a programming language that is developed and maintained primarily by
Microsoft. It is a strict superset of JavaScript (a core technology of the World Wide Web) and adds optional static
typing. Given its enhanced feature set and design, TypeScript is arguably a better choice for large web applications
over Vanilla JavaScript and large applications are not uncommon in engineering and manufacturing.

TypeScript has design traits that make it similar to C# (another language developed and maintained by Microsoft) as both
TypeScript and C# share the same language designer - [Anders Hejlsberg](https://en.wikipedia.org/wiki/Anders_Hejlsberg).

The popularity of TypeScript is
[rising rapidly](https://www.techrepublic.com/article/10-most-popular-programming-languages-rise-of-typescript/) and it
may very well, one day, become as popular as JavaScript itself.

**Typical Industrial Use Cases**

* Edge computing for Industrial Internet of Things (IIoT) applications (typically via [WebAssembly](https://webassembly.org/))
* Industrial graphics via [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) and [WebXR](https://blog.mozvr.com/tag/webxr/)
* Data visualization (for example, using [D3.js](https://d3js.org/))
* Soft real-time, server-side web applications (via [Node.js](https://nodejs.org/en/))

**Resources**

* [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/) - by [basarat](https://twitter.com/basarat)
* [Intro to D3](https://wattenberger.com/blog/d3#intro) - by [Amelia Wattenberger](https://twitter.com/wattenberger)
* [Introduction to D3](https://observablehq.com/@mitvis/introduction-to-d3) - by [Arvind Satyanarayan](https://twitter.com/arvindsatya1)

## Open Source Projects

### Machine Vision

* **[OpenCV](https://opencv.org/)** [![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-yellow.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![OpenCV Repo](https://img.shields.io/badge/Link%20to-Code-red)](https://github.com/opencv/opencv) [![OpenCV Docs](https://img.shields.io/badge/Link%20to-Docs-blue)](https://docs.opencv.org/) - Library for building real-time computer vision systems.

### Platforms

* **[Eclipse BaSyx](https://www.eclipse.org/basyx/)** [![License: EPL 2.0](https://img.shields.io/badge/License-EPL%202.0-brightgreen.svg)](https://spdx.org/licenses/EPL-2.0.html) [![Eclipse BaSyx Code](https://img.shields.io/badge/Link%20to-Code-red)](https://git.eclipse.org/r/plugins/gitiles/basyx/basyx) [![Eclipse BaSyx Docs](https://img.shields.io/badge/Link%20to-Docs-blue)](https://wiki.eclipse.org/BaSyx) - Provides software application middleware for end users interested in implementing Industry 4.0 within industry and academia.
* **[United Manufacturing Hub](https://www.umh.app/)** [![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0) [![United Manufacturing Hub Code](https://img.shields.io/badge/Link%20to-Code-red)](https://github.com/united-manufacturing-hub/united-manufacturing-hub) [![United Manufacturing Hub Docs](https://img.shields.io/badge/Link%20to-Docs-blue)](https://docs.umh.app/docs/) - Industrial IoT and manufacturing application platform enabling users to connect, store, and access all relevant data sources in industrial manufacturing sites and build user-centric dashboards and applications.

### Robotics

* **[Robot Operating System (ROS)](https://www.ros.org/)** [![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-yellow.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Robot Operating System Repo](https://img.shields.io/badge/Link%20to-Code-red)](https://github.com/ros2) [![Robot Operating System Docs](https://img.shields.io/badge/Link%20to-Docs-blue)](https://docs.ros.org/) - Robotics middleware suite which provides low-level device control, message passing infrastructure, mapping, localization, perception and simulation tooling.
    * [ROS Q&A Forum](https://answers.ros.org/questions/) - Question and answer forum for newcomers to the Robot Operating System (ROS) project.
    * [ROS General Discussion Forum](https://discourse.ros.org/) - Discussion forum for news, help and other related topics about the Robot Operating System (ROS) open-source project.
    * [ROSCon](https://roscon.ros.org/) - Annual networking and educational conference for system developers of all experience levels (beginners to experts) that utilize the [Robot Operating System](https://www.ros.org/).

### Simulators

* **[Manufacturing Line PackML MQTT Simulator](https://github.com/Spruik/PackML-MQTT-Simulator)** [![License: MIT](https://img.shields.io/badge/License-MIT-orange)](https://spdx.org/licenses/MIT.html) [![Manufacturing Line PackML MQTT Simulator Repo](https://img.shields.io/badge/Link%20to-Code-red)](https://github.com/Spruik/PackML-MQTT-Simulator) - Manufacturing line simulation platform that utilizes PackML implemented over MQTT.

## Industry Nonprofit Organizations

* **[Association for Computing Machinery (ACM)](https://www.acm.org/)** - World's largest educational and scientific computing society with nearly 100,000 members, and unites computing professionals, educators, and researchers from industry, academia, and government.
    * [YouTube Channel](https://www.youtube.com/user/TheOfficialACM)
* **[Women in Robotics](https://womeninrobotics.org/)** - Global community supporting women who work in, are interested in or perform research in the robotics industry.
    * [YouTube Channel](https://www.youtube.com/channel/UCCjeoPPo_1-3R4bi4hVXn-Q)
    * [Newsletter](https://womeninrobotics.org/newsletter/)

## Video Channels

* **[3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)** - Rich, animated and entertaining video tutorials on various mathematics topics that are typically related to physical product simulations (differential equations) and Machine Learning (linear algebra, eigenvalues).
* **[ETH Zurich Autonomous Systems Lab](https://www.youtube.com/c/aslteam)** and **[ETH Zurich Robotic Systems Lab](https://www.youtube.com/user/leggedrobotics)** - Novel autonomous systems research and concepts for robotics operating on the ground, air, water and other challenging environments.
* **[JetsonHacks](https://www.youtube.com/channel/UCQs0lwV6E4p7LQaGJ6fgy5Q)** - Overviews and tutorials focused on the NVIDIA Jetson Developer Kit along with great project ideas for university student groups.
* **[MinutePROFINET](https://www.youtube.com/channel/UC1o6hU1Na8uIpkBVa_tpuqA)** - Short, approachable videos on the PROFINET Industrial Ethernet protocol.
* **[omlox](https://www.youtube.com/channel/UC5gf595MjHXAnWZAliucdzg)** - Short, educational videos on omlox, an open locating standard, which provides a real-time asset/product tracking standard for networked industrial factories.
* **[PyTorch](https://www.youtube.com/channel/UCWXI5YeOsh03QvJ59PMaXFw)** - Tutorials and conference talks about PyTorch, a popular, open-source Machine Learning framework.
* **[RealPars](https://www.youtube.com/c/realpars)** - Short videos, with extremely high production value, covering everything from industrial factory maintenance to industrial control systems to industrial computer programming.
* **[ROS-Industrial (ROS-I) Consortium](https://www.youtube.com/channel/UCXyGVRiCwUMc1gav-G7z2ew)** - Open-source project that extends the use of the Robot Operating System (ROS) for industrial and manufacturing-oriented use cases. The ROS-I YouTube channel contains talks from industry partners on how they are leveraging ROS-I in industrial robots, presentations on robotics research and recaps of annual ROS-I industry meetings.

## Trade Shows and Events

Trade shows and recurring events of which a substantial portion is
dedicated to Industry 4.0 conversations, topics and equipment.

* **[Automate](https://www.automateshow.com/)** - Bi-annual robotics, machine vision and industrial automation show held in Detroit, Michigan.
* **[Hannover Messe](https://www.hannovermesse.de/en/)** - Annual manufacturing technology show held in Hanover, Germany that is intended to demonstrate the latest industry trends in manufacturing and energy distribution. A core focus of this show is "digitalization" of traditional industry.
* **[International Manufacturing Technology Show (IMTS)](https://www.imts.com/)** - Bi-annual manufacturing technology show in North America which typically includes several talks, exhibits and vendors that feature Industry 4.0 and Digital Manufacturing. This show is held in Chicago, Illinois.

## Newsletters and Digital Magazines

* **[AI Weekly](https://aiweekly.co/)** - Weekly newsletter containing a collection of news and opinions regarding Artificial Intelligence developments, a summary of "What's New" in the robotics industry and upcoming industry events.
* **[Computer Vision News](https://www.rsipvision.com/computer-vision-news/)** - Monthly newsletter and digital magazine that surfaces the latest developments in the Computer Vision and AI communities across multiple domains. This newsletter is designed to fill the empty space between scientific journals and commercial publications.
* **[Weekly Robotics](https://weeklyrobotics.com/)** - Weekly newsletter that consolidates notable industry developments, latest robotics research, blog posts, startup investments in robotics companies and open-source projects of interest.

## Other Awesome Lists

Other Awesome lists for programming languages and other technologies that are commonly
used in the context of Industry 4.0.

* [Awesome .NET](https://github.com/quozd/awesome-dotnet)
* [Awesome .NET Core](https://github.com/thangchung/awesome-dotnet-core)
* [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
* [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
* [Awesome Electronics](https://github.com/kitspace/awesome-electronics)
* [Awesome Embedded](https://github.com/nhivp/Awesome-Embedded)
* [Awesome Industrial Control System (ICS) Security](https://github.com/hslatman/awesome-industrial-control-system-security)
* [Awesome IoT](https://github.com/phodal/awesome-iot)
* [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript)
* [Awesome Julia](https://github.com/svaksha/Julia.jl)
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Awesome Python](https://github.com/vinta/awesome-python)
* [Awesome Robotics](https://github.com/kiloreux/awesome-robotics)
* [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
* [Awesome TypeScript](https://github.com/dzharii/awesome-typescript)
* [Awesome Vulkan](https://github.com/vinjn/awesome-vulkan)
* [Awesome WebGL](https://github.com/sjfricke/awesome-webgl)
* [Awesome WebGPU](https://github.com/mikbry/awesome-webgpu)

## Code of Conduct

As with all ManufacturingOpen projects, we have adopted the [Alliedstrand Open Source Community Participation Guidelines](https://github.com/Alliedstrand/os-community-guidelines).

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg