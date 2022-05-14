<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT/blob/main/src/test.png">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Dynamic Dec-LOS-RTT</h3>
  <h4 align="center">By Saahil Parikh and Yi Wang</h4>

  <p align="center">
    Research involving dynamic agents with line of sight communication.
    <br />
    <a href="https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://saahilparikh.github.io/DYNAMIC-DEC-LOS-RRT/">Live Site</a>
    ·
    <a href="https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT/issues">Report Bug</a>
    ·
    <a href="https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The problem of ensuring the safety of multi-agent motion when agents cannot contact each other is essential for path planning in the real world. It is difficult to control the agents experiencing instantaneous stops to avoid collisions. To address this problem, we develop a new algorithm Dynamic DEC-LOS-RRT based on the existing approach DEC-LOS- RRT. A new radial velocity set is defined around the corners of each obstacle to make robots stop smoothly. This is implemented by constraining the configuration space of each robot and adding constraints to the local planning algorithm. Simulation and hardware show our algorithm guarantees the effectiveness of path planning and safety for decentralized planning for multi-agent systems.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Reveal.js](https://revealjs.com/)
* [Robotarium](https://www.robotarium.gatech.edu)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

All source code is located in the src folder. Run it as you would a normal python notebook. 

### Prerequisites

* numpy
  ```sh
  pip install numpy
  ```
  
* scipy
  ```sh
  pip install scipy
  ```



<!-- USAGE EXAMPLES -->
## Usage

This project implements RRT, DEC-LOS-RRT and Dynamic DEC-LOS-RRT all with kd trees. If you would like to use the algorithms implemented please cite us.

<p align="right">(<a href="#top">back to top</a>)</p>






<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT](https://github.com/SaahilParikh/DYNAMIC-DEC-LOS-RRT)

<p align="right">(<a href="#top">back to top</a>)</p>







<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png

