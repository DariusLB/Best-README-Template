<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://bitbucket.org/swbs_academy/jsprojdb/src/master/">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Gallery Saver</h3>

  <p align="center">
    Develop a web application to consume the {JSON} Placeholder API (https://jsonplaceholder.typicode.com/) in order for a user to be able to create entities named "Photo Albums" in which you can add photos. You are always able to add or remove albums as a user. Inside an album you can also edit the Title of the photo album and you can add or remove photos. For each photo you can also add and remove comments.
    <br />
    <a href="https://github.com/DariusLB/Best-README-Template/blob/db/AcademyProject"><strong>Explore the docs »</strong></a>
    <br />
    <br />
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
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

I have created two interfaces in html, named indexAlbum.html and indexPhoto.html. 
In the first page, Photo Viewer, there are:
  * a button for viewing all the albums that are automatically generated from tipycode usign the albums resource from JSONPlaceholder
  * <img src="images/2021-11-09_15h57_23.png" width="800" height="400">
  * a button for creating a new album
  * <img src="images/2021-11-09_15h56_48.png" width="800" height="400">
  * a button for updating the title of an album
  * <img src="images/2021-11-09_15h57_02.png" width="800" height="400">
  * a button to delete an album
  * <img src="images/2021-11-09_15h57_11.png" width="800" height="400">



In the second page, Photo Viewer, there are:
  * a button for viewing all the albums that are automatically generated from tipycode usign the albums resource from JSONPlaceholder
  * <img src="images/2021-11-09_15h57_35.png" width="800" height="400">
  * a button for creating a new album
  * <img src="images/2021-11-09_15h58_00.png" width="800" height="400">
  * a button for updating the title of an album
  * <img src="images/2021-11-09_15h58_47.png" width="800" height="400">
  * a button to delete an album
  * <img src="images/2021-11-09_15h58_56.png" width="800" height="400">
  * for the upload a photo from computer I have created a form with two input forms, a button to submit and a button and an input form for an image
  * <img src="images/2021-11-09_15h59_40.png" width="800" height="400">
  * <img src="images/2021-11-09_16h00_21.png" width="800" height="400">
  * an input field to add a comment
  * <img src="images/2021-11-09_16h01_10.png" width="800" height="400">

### Built With

* [Popper.js](https://cdnjs.com/libraries/popper.js/2.10.2)
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

For completing this project I used the free fake API named [JSONPlaceholder](https://jsonplaceholder.typicode.com/) from typicode. Using this, I needed the fetch API function. 
I have used the [albums](https://jsonplaceholder.typicode.com/albums) and [photos](https://jsonplaceholder.typicode.com/photos).
For the create, update and delele button, you can only see the results in the console of the page.
After completing the title and comment input forms and after pressing the submit button, the data will be showed on the screen underneath.
For uploading a photo from computer, I have only a button that uploads the picture in the image input form that I have created.

<!-- ROADMAP -->
## Roadmap

- [x] Create, modify and delete a gallery.
    - [x] User is able to create a gallery
    - [x] User is able to edit the title of the gallery
    - [x] User is able to delete a gallery

- [x] Upload and delete a photo.
    - [x] User is able to upload a photo from computer
    - [x] User is able to visualize all photos from a gallery
    - [x] User is able to delete a photo from a gallery

- [x] Write and delete a comment to images.
    - [x] User is able to write a comment at one image
    - [x] User is able to delete a comment

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Darius-Lorenzo.Boncila@ro.bosch.com

Project Link: [Gallery Saver - Project](https://bitbucket.org/swbs_academy/jsprojdb/src/master/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
