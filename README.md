<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
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
[![Issues][issues-shield]][issues-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">


  <h3 align="center">Coin Track — Balance Tracker</h3>

  <p align="center">
    Coin Track is a balance tracking application. 
    <br />
    <a href="https://github.com/ErikTsai/coin-track"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ErikTsai/coin-track">View Demo</a>
    ·
    <a href="https://github.com/ErikTsai/coin-track/issues">Report Bug</a>
    ·
    <a href="https://github.com/ErikTsai/coin-track/issues">Request Feature</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<div style="width:100%; display: flex; justify-content: center; align-items: center;">


![Picture](https://raw.githubusercontent.com/ErikTsai/coin-track/main/coinTrackPreview.png)
</div>


Coin Track is a balance tracker where the user enters the price, title, description, and date of the transaction. The details of the transaction are displayed on the application paged, as well as being stored in the database. This application has not been deployed.

Key Features
  - Keeps track of balance through transactions
  - Stores information inside a database so the user can access the information again


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* ![MongoDB Badge](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat)
* ![Express Badge](https://img.shields.io/badge/Express-000?logo=express&logoColor=fff&style=flat)
* ![React Badge](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=flat)
* ![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Install Node.JS at [https://nodejs.org/en/download/current](https://nodejs.org/en/download/current)

* Install npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Create a free MongoDB Cluster by following this video and save the URL: [https://youtu.be/jXgJyuBeb_o?si=pAZKJtX1tzfMZBSj](https://youtu.be/jXgJyuBeb_o?si=pAZKJtX1tzfMZBSj) 
2. Clone the repo
   ```sh
   git clone https://github.com/ErikTsai/coin-track
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your MongoDB Cluster URL in `api/.env`
   ```js
   MONGO_URL="ENTER URL HERE"
   ```
5. Navigate to the path of the api folder and run in your terminal
   ```sh
    nodemon index.js
   ```
6. In a separate terminal, start the React app
    ```sh
    npm start
   ```
7. To close the server and application by closing the terminals used to start the server and application

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- Deploy Application
- Improve Current Styling
- Add Mobile Styling


See the [open issues](https://github.com/ErikTsai/coin-track/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- CONTACT -->
## Contact

* LinkedIn: [Erik Tsai](https://www.linkedin.com/in/erik-tsai/)
* Project Link: [Coin Track](https://github.com/ErikTsai/coin-track)

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ErikTsai/coin-track.svg?style=for-the-badge
[contributors-url]: https://github.com/ErikTsai/coin-track/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ErikTsai/coin-track.svg?style=for-the-badge
[forks-url]: https://github.com/ErikTsai/coin-track/network/members
[issues-shield]: https://img.shields.io/github/issues/ErikTsai/coin-track.svg?style=for-the-badge
[issues-url]: https://github.com/ErikTsai/coin-track/issues
