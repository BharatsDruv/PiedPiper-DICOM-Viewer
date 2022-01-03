

<!--
*** Thanks for checking out the ShareTheMeal. If you have a suggestion
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

    <img src="http://cdn.onlinewebfonts.com/svg/img_45133.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">DICOM Analyser</h3>

  <p align="center">
    Technology for Enhancing the viewing experience of practitioner
    <br />
    <a href="https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/issues">Report Bug</a>
    ·
    <a href="https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

 <img src="https://raw.githubusercontent.com/BharatsDruv/PiedPiper-DICOM-Viewer/master/PiedPiper.png" alt="Logo" width="384" height="216">

Our system allows to display DICOM images quickly and easily. It uses DICOM images (e.g. MRI scan) or video stream, that comes as an input from operating room which is combined with metadata and transmits to a remote browser through WebRTC. It allows real time peer to peer communication between multiple users with just their browsers. 

Need of the application:

Here's why:
* Telemonitoring: A remote doctor can follow an ongoing surgery  in almost real-time,  using a compatible browser in a simple and transparent way. For instance a senior surgeon may supervise and even guide a junior surgeon in real-time from outside the Operating room.
* Education: The live streaming of an ongoing surgery  can be a great learning tool for the medical students and especially future surgeons.
:smile:

Of course, this application is not market ready or a product. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. 

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With


This are the tools and plugins we've used to built this application
* [JavaScript](https://www.javascript.com/)
* [HTML/CSS](https://www.w3schools.com/html/html_css.asp)
* [JSZip library](https://stuk.github.io/jszip/)
* [Cornerstone dicomParser.js library](https://cornerstonejs.org/)
* [Cornerstone Viewer](https://cornerstonejs.org/)



<!-- GETTING STARTED -->
## Getting Started

Instructions on setting up DICOM Analyser locally.
To get a local copy up and running follow these simple steps.

### Prerequisites

[Install Node.js](https://nodejs.org/en/download/)
  </br>


### Installation

1. Clone the repo
   ```sh
   git clone BharatsDruv/PiedPiper-DICOM-Viewer
   ```
3. Install npm
   ```sh
   npm install
   ```
4. Run the app
   ```sh
   npm start
   ```



<!-- USAGE EXAMPLES -->
## Behind Tech

WebRTC (Web Real-Time Communication): 
- It provides web browsers and mobile applications with real-time communication (RTC) via simple APIs.

It is composed of the two clients and the signalling server WebRTC:
- Client 1 represents the extremity of the operating room. A WebRTC session needs to established In order to communicate with client 2 (e.g. a remote expert) to view the live streaming.
- The client 1 can stream the video flow with the client 2 in a peer-to-peer fashion via the RTP media channel and the DICOM metadata flow via the data channel directly. 
The video/file stream on client 2 sides is displayed  to user.




<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

* Bharat Shrivastava - [@LinkedIn](https://www.linkedin.com/in/bharatshrivastava/) - bharatsdruv@gmail.com 
* Abhishek Singh Baghel - [@LinkedIn](https://www.linkedin.com/in/asbaghel/) - abhisheksbaghel99@gmail.com 
* Yashsvi Sharma - [@LinkedIn](https://www.linkedin.com/in/yashsvi-sharma-9663a9172/) - yashsvi30201@gmail.com


Project Link: [https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer](https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/BharatsDruv/PiedPiper-DICOM-Viewer.svg?style=for-the-badge
[contributors-url]: https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/BharatsDruv/PiedPiper-DICOM-Viewer.svg?style=for-the-badge
[forks-url]: https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/network/members
[stars-shield]: https://img.shields.io/github/stars/BharatsDruv/PiedPiper-DICOM-Viewer.svg?style=for-the-badge
[stars-url]: https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/stargazers
[issues-shield]: https://img.shields.io/github/issues/BharatsDruv/PiedPiper-DICOM-Viewer.svg?style=for-the-badge
[issues-url]: https://github.com/BharatsDruv/PiedPiper-DICOM-Viewer/issues
[license-shield]: https://img.shields.io/github/license/BharatsDruv/PiedPiper-DICOM-Viewer.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/bharatshrivastava/
[product-screenshot]: PiedPiper.png
