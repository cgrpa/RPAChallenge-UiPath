<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>



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



<br />
<h3 align="center">RPAChallenge in UiPath</h3>

  <p align="center">
    Created as part of my RPA Speed Observation project.
    <br />
    The goal of this challenge is to create a workflow that will input data from a spreadsheet into the form fields on the screen.
    <br />
    The fields will change position on the screen after every submission throughout 10 rounds thus the workflow must correctly identify where each spreadsheet record must be typed every time.
    <br />
    <br />
    The fastest speed I achieved was 4183ms.
    <br />
    <br>
    <a href="https://rpachallenge.com">RPAChallenge</a>
    <a href="https://www.linkedin.com/posts/chegamble_rpa-uipath-rpachallenge-activity-6990601937469505536-nq9U?utm_source=share&utm_medium=member_desktop">View Demo</a>
    ·
    <a href="https://github.com/cgrpa/RPAChallenge-UiPath/issues">Report Bug</a>
   
  </p>
</div>





<!-- ABOUT THE PROJECT -->
## About The Project


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Clone the repository to a directory of your choice, build and run the solution.



### Installation
1. Clone the repo - using git or UiPath has source control built in 
   ```
   git clone https://github.com/cgrpa/RPAChallenge-UiPath.git
   ```
2. Change the argument in_strEntryDataPath argument in the Main.xaml workflow to the location of the RPAChallenge data, it is located within the Data folder in the project folder.
![image](https://user-images.githubusercontent.com/95618126/208202944-50c642f2-518c-4992-a128-bafe3c493f9d.png)
![image](https://user-images.githubusercontent.com/95618126/208202974-40aebfb0-85d1-42ed-a80c-7389fcfa2992.png)

3. Run the project
4. Bob's your uncle, fanny's your aunt

### Dependencies
NuGet packages: 
* [UiPath Excel Activities](UiPath.Excel.Activities)
* [UiPath UiAutomation Activities](UiPath.UiAutomation.Activities)
* [UiPath System Activities](UiPath.System.Activities)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

[Comparison Video](https://www.linkedin.com/posts/chegamble_rpa-uipath-rpachallenge-activity-6990601937469505536-nq9U?utm_source=share&utm_medium=member_desktop)
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



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Che Gamble - [![LinkedIn][linkedin-shield]][linkedin-url] - chegamblerpa@gmail.com

Project Link: [https://github.com/cgrpa/RPAChallenge-UiPath](https://github.com/cgrpa/RPAChallenge-UiPath)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [ReadMe Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/cgrpa/RPAChallenge---CSharp.svg?style=for-the-badge
[contributors-url]: https://github.com/cgrpa/RPAChallenge-UiPath/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cgrpa/RPAChallenge---CSharp.svg?style=for-the-badge
[forks-url]: https://github.com/cgrpa/RPAChallenge-UiPath/network/members
[stars-shield]: https://img.shields.io/github/stars/cgrpa/RPAChallenge---CSharp.svg?style=for-the-badge
[stars-url]: https://github.com/cgrpa/RPAChallenge-UiPath/stargazers
[issues-shield]: https://img.shields.io/github/issues/cgrpa/RPAChallenge---CSharp.svg?style=for-the-badge
[issues-url]: https://github.com/cgrpa/RPAChallenge-UiPath/issues
[license-shield]: https://img.shields.io/github/license/cgrpa/RPAChallenge---CSharp.svg?style=for-the-badge
[license-url]: https://github.com/cgrpa/RPAChallenge-UiPath/blob/master/license.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/chegamble
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
