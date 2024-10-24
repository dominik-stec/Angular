<!--
*** Thanks for checking out c. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
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
[![LinkedIn][linkedin-shield]][linkedin-url]
[![NO LICENSE][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://gdansk.pja.edu.pl/pl/">
    <img src="images/logo.jpg" alt="Logo" width="540" height="80">
  </a>

  <h2 align="center">Angular</h2>

  <p align="center">
    <h4> Bogate Interfejsy Użytkownika (BIU) lecture module in PJATK </h4>
    <!-- <br /> -->
    <!-- <a href="https://github.com/dominik-stec/Rich_Internet_Application_PJA"><strong>» go to source code »</strong></a> -->
    <!-- <br />
    <br /> -->
    <!-- <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a> -->
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of contents</summary>
  <ol>
    <li>
      <a href="#Project-description">Project description</a>
      <ul>
        <li><a href="#Libraries-and-frameworks">Libraries / Frameworks</a></li>
      </ul>
    </li>
    <li>
      <a href="#Docker-deploy">Docker deploy</a>
    </li>
    <li>
      <a href="#Native-deploy">Native deploy</a>
      <ul>
        <li><a href="#Prerequisites">Prerequisites</a></li>
        <li><a href="#Installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#How-to-use">How to use ?</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li> -->
    <li><a href="#License">License</a></li>
    <li><a href="#Contact">Contact with me</a></li>
    <!-- <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Project description

<!-- [![Main_view][product-screenshot]][product-screenshot] -->
<img src="images/screenshot.png" width="500"/>

In this project I realise Single Page Application with Angular in version 5. SPA module is representation of user authorization process with field content control against throws exceptions caused wrong keybord typing.

### Libraries and frameworks

This project use technology below.

- [![Bootstrap][bootstrap-shield]][bootstrap-url]
- [![Angular][angular-shield]][angular-url]

<!-- DOCKER -->

## Docker deploy

```sh
docker build -t biupjatk:latest .
docker run -it -p 4200:4200 --name biupjatk biupjatk:latest
```

Run project in web browser <br>
Default adress set in framewrok is: <br>
[https://localhost:4200/](https://localhost:4200/)

<!-- NATIVE DEPLOY -->

## Native deploy

This is instructions on setting up this project locally.

### Prerequisites

NodeJS framework is required. <br />
Angular CLI package install with Node Package Manager is need. <br />
Angular devkit package install with Node Package Manager is need. <br />

- npm
  ```sh
  npm install -g @angular/cli
  npm install --save-dev @angular-devkit/build-angular
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/dominik-stec/Angular.git
   ```
2. Go to folder with Angular sources
   ```sh
   cd AngularFolder
   ```
3. Build and run sources with Angular CLI
   ```sh
   ng serve
   ```
4. Run project in web browser <br>
   Default adress set in framewrok is: <br>
   [https://localhost:4200/](https://localhost:4200/)

<!-- USAGE EXAMPLES -->

## How to use

As first we need to register user in system use fields with personal user data. Unappropriate entries are detected and user will see typing error. After user registration process we can sign into service with given user name and password.

<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->

<!-- ROADMAP
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).

-->

<!-- CONTRIBUTING
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

-->

<!-- LICENSE -->

## License

This project has not a license.
All rights are reserved and it is not Open Source or free. You cannot modify or redistribute this code without explicit permission from the copyright holder, because projects which I realised are private conception from PJATK studies.
See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Dominik Stec - dccstcc@gmail.com

[![LinkedIn][linkedin-shield]][linkedin-url]

Project URL:
<br />
`https://github.com/dominik-stec/Angular`

<!-- ACKNOWLEDGEMENTS
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)

-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/dominik-stec/Angular.svg?style=for-the-badge
[contributors-url]: https://github.com/dominik-stec/Angular/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dominik-stec/Angular.svg?style=for-the-badge
[forks-url]: https://github.com/dominik-stec/Angular/network/members
[stars-shield]: https://img.shields.io/github/stars/dominik-stec/Angular.svg?style=for-the-badge
[stars-url]: https://github.com/dominik-stec/Angular/stargazers
[issues-shield]: https://img.shields.io/github/issues/dominik-stec/Angular.svg?style=for-the-badge
[issues-url]: https://github.com/dominik-stec/Angular/issues
[license-shield]: https://img.shields.io/badge/License-NONE-orange
[license-url]: https://github.com/dominik-stec/Angular/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/dominik-stec
[product-screenshot]: images/screenshot.png
[angular-shield]: https://img.shields.io/badge/-Angular-red
[angular-url]: https://angular.io/
[bootstrap-shield]: https://img.shields.io/badge/-Bootstrap-blue
[bootstrap-url]: https://getbootstrap.com/
